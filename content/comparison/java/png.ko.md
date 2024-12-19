
---
############################# Static ############################
layout: "format"
date:  2024-12-19T07:49:45
draft: false
lang: ko
format: Png
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "Java 를 사용하여 PNG 개의 사진에 대한 차이 보고서를 가져옵니다."
head_description: "GroupDocs.Comparison for Java API는 J2EE 및 J2SE를 지원하는 애플리케이션의 PNG 문서에 대한 유용한 비교 보고서를 생성합니다."

############################# Header ############################
title: "Java 를 사용하여 PNG 개의 사진 비교" 
description: "GroupDocs.Comparison API를 사용하여 Java, J2EE 또는 J2SE 애플리케이션의 성능을 강화하십시오.PNG 장의 사진에서 변경 사항에 대한 세부 정보를 검색하십시오."
subtitle: "문서 차이점 검사 프레임워크"  

header_actions:
  enable: true
  items:
    #  loop
    - title: "무료 Maven 다운로드"
      link: "https://releases.groupdocs.com/comparison/java/"
      
############################# About ############################
about:
    enable: true
    title: "GroupDocs.Comparison for Java 개의 API 기능에 대한 정보 받기"
    link: "/comparison/java/"
    link_title: "자세히 알아보기"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison 는 PNG 형식으로 표시된 다양한 버전의 이미지 간의 변형을 기반으로 세부 보고서를 작성하는 데 적합한 네이티브 Java API로 개발되었습니다.PNG 형식만 지원되는 것은 아닙니다.API에서 제공하는 유용한 기능이 많이 있습니다.

############################# Steps ############################
steps:
    enable: true
    title: "Java 를 사용하여 PNG 개의 파일을 비교하십시오."
    content: |
      PNG 파일을 [GroupDocs.Comparison](https://products.groupdocs.com/comparison/java/) 와 비교하고 변경 사항에 대한 관련 보고서를 검색합니다.
      
      1. [Maven](https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/) 에서 다운로드하여 GroupDocs.Comparison for Java 패키지를 설치합니다.
      2. PNG 에 대한 비교기 인스턴스 및 패스 경로 제공
      3. 추가 비교를 위해 PNG 개의 파일 추가
      4. 보고서를 로컬 디스크에 저장
   
    code:
      platform: "net"
      copy_title: "복사"
      install:
        command: |
          <dependencies>
            <dependency>
              <groupId>com.groupdocs</groupId>
              <artifactId>groupdocs-comparison</artifactId>
              <version>{0}</version>
            </dependency>
          </dependencies>

          <repositories>
            <repository>
              <id>repository.groupdocs.com</id>
              <name>GroupDocs Repository</name>
              <url>https://repository.groupdocs.com/repo/</url>
            </repository>
          </repositories>
        copy_tip: "클릭하여 복사"
        copy_done: "복사"
      links:
        #  loop
        - title: "더 많은 예시"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
        #  loop
        - title: "문서화"
          link: "https://docs.groupdocs.com/comparison/java/"
          
      content: |
        ```java {style=abap}

        // 하드 드라이브에서 파일의 차이점이나 유사점을 확인합니다.

        // 초기 파일을 지정하여 Comparer 객체 만들기
        try (Comparer comparer = new Comparer("main.png") 
        {
            // 비교할 추가 파일 포함
        	comparer.add("version1.png");
            comparer.add("version2.png");
            comparer.add("version3.png");

            // 결과로 지정된 이름의 보고서를 가져옵니다.
            final Path resultPath = comparer.compare("full_report.png"); 

            System.out.println("\nDocuments compared successfully.");
        }
        
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "시작할 준비가 되셨나요?"
  description: "GroupDocs.Comparison 기능을 무료로 체험하거나 라이선스를 요청하세요"
  items:
    #  loop
    - title: "Maven 다운로드"
      link: "https://releases.groupdocs.com/comparison/java/"
      color: "red"
        #  loop
    - title: "라이선싱"
      link: "https://purchase.groupdocs.com/pricing/comparison/java/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Java 를 통해 PNG 개의 다양한 이미지 버전에서 차이점을 찾으십시오."
    exclude: "PNG"
    description: "GroupDocs.Comparison for Java API는 PNG 사진 내부의 변경 사항을 추적하고 추가 분석을 위한 설명 보고서를 작성합니다."
    items: 
        # format loop 1
        - name: "PDF 개의 파일 비교"
          format: "PDF"
          link: "/comparison/java/pdf/"
          description: "어도비 Portable 문서 형식"

        # format loop 2
        - name: "DOCX 개의 파일 비교"
          format: "DOCX"
          link: "/comparison/java/docx/"
          description: "마이크로소프트 Word 오픈 XML 문서"

        # format loop 3
        - name: "RTF 개의 파일 비교"
          format: "RTF"
          link: "/comparison/java/rtf/"
          description: "리치 텍스트 파일 포맷"

        # format loop 4
        - name: "TXT 개의 파일 비교"
          format: "TXT"
          link: "/comparison/java/txt/"
          description: "일반 텍스트 파일 형식"

        # format loop 5
        - name: "XLSX 개의 파일 비교"
          format: "XLSX"
          link: "/comparison/java/xlsx/"
          description: "마이크로소프트 Excel 오픈 XML 스프레드시트"

        # format loop 6
        - name: "CSV 파일 비교"
          format: "CSV"
          link: "/comparison/java/csv/"
          description: "쉼표로 구분된 값 파일"

        # format loop 7
        - name: "PPTX 개의 파일 비교"
          format: "PPTX"
          link: "/comparison/java/pptx/"
          description: "PowerPoint 오픈 XML 프레젠테이션"

        # format loop 8
        - name: "ODS 개의 파일 비교"
          format: "ODS"
          link: "/comparison/java/ods/"
          description: "Open Document 스프레드시트"

        # format loop 9
        - name: "ODP 파일 비교"
          format: "ODP"
          link: "/comparison/java/odp/"
          description: "OpenDocument 프레젠테이션 파일 형식"

        # format loop 10
        - name: "ODT 개의 파일 비교"
          format: "ODT"
          link: "/comparison/java/odt/"
          description: "Open Document 텍스트"

        # format loop 11
        - name: "JPEG 개의 파일 비교"
          format: "JPEG"
          link: "/comparison/java/jpeg/"
          description: "JPEG 이미지"

        # format loop 12
        - name: "PNG 개의 파일 비교"
          format: "PNG"
          link: "/comparison/java/png/"
          description: "Portable 네트워크 그래픽"

        # format loop 13
        - name: "GIF 개의 파일 비교"
          format: "GIF"
          link: "/comparison/java/gif/"
          description: "그래픽 인터체인지 형식 파일"

        # format loop 14
        - name: "BMP 개의 파일 비교"
          format: "BMP"
          link: "/comparison/java/bmp/"
          description: "비트맵 파일 형식"

        # format loop 15
        - name: "HTML 파일 비교"
          format: "HTML"
          link: "/comparison/java/html/"
          description: "하이퍼 텍스트 마크업 언어"

        # format loop 16
        - name: "MSG 개의 파일 비교"
          format: "MSG"
          link: "/comparison/java/msg/"
          description: "마이크로소프트 Outlook 이메일 메시지"

        # format loop 17
        - name: "ONE 개의 파일 비교"
          format: "ONE"
          link: "/comparison/java/one/"
          description: "마이크로소프트 OneNote"

        # format loop 18
        - name: "VSDX 개의 파일 비교"
          format: "VSDX"
          link: "/comparison/java/vsdx/"
          description: "마이크로소프트 Visio 드로잉"

        # format loop 19
        - name: "CS 파일 비교"
          format: "CS"
          link: "/comparison/java/cs/"
          description: "샤프 언어"

        # format loop 20
        - name: "Java 개의 파일 비교"
          format: "Java"
          link: "/comparison/java/java/"
          description: "Java 언어"
          
        # format loop 21
        - name: "CPP 파일 비교"
          format: "CPP"
          link: "/comparison/java/cpp/"
          description: "C++ 언어"
---