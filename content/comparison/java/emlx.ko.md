
---
############################# Static ############################
layout: "format"
date:  2024-12-19T07:49:42
draft: false
lang: ko
format: Emlx
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "Java EMLX 비교 API - EMLX 파일에 차이점이 있는지 확인하세요."
head_description: "Java, J2EE, J2SE 애플리케이션의 EMLX 개의 파일을 비교하고 병합합니다.콘텐츠, 텍스트 및 스타일의 차이점 요약을 분석합니다."

############################# Header ############################
title: "Java 의 EMLX 개 파일 비교" 
description: "Java 에 있는 두 개 이상의 EMLX 파일 간의 콘텐츠 비교를 수행합니다.차이점 목록을 검색하고 비교한 파일을 단일 문서에 저장합니다."
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
    title: "GroupDocs.Comparison for Java 라이브러리의 기능 살펴보기"
    link: "/comparison/java/"
    link_title: "자세히 알아보기"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison for Java 는 동일한 형식을 공유하는 여러 이미지와 문서를 비교하기 위해 만들어진 내장 Java 소프트웨어입니다.비교 문서 간의 단락, 단어, 문자, 모양 및 텍스트 스타일 내의 차이를 식별하는 데 도움이 됩니다.이러한 변경 내용을 병합하고 최종 문서로 내보낼 수 있으므로 PDF 개, Word 문서, Excel 스프레드시트, PowerPoint 프레젠테이션, Visio 다이어그램, Outlook 이메일, HTML, 그림 및 다양한 이미지 파일 형식을 쉽게 비교하고 병합할 수 있으므로 외부 라이브러리가 필요하지 않습니다.

############################# Steps ############################
steps:
    enable: true
    title: "Java 을 사용하여 여러 EMLX 문서를 비교하는 방법"
    content: |
      [GroupDocs.Comparison](https://products.groupdocs.com/comparison/java/) 를 사용하여 여러 EMLX 개의 파일을 비교하고 차이점을 자세히 설명하는 보고서를 생성합니다.
      
      1. 선호하는 패키지 관리자를 사용하여 [Maven](https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/) 에서 GroupDocs.Comparison for Java 를 설치하십시오.
      2. EMLX 파일 중 하나에 대한 Comparer 클래스 설정 경로의 인스턴스를 생성합니다.
      3. 콤퍼러 인스턴스에 EMLX 를 하나 이상 추가합니다.
      4. 정확한 차이점을 요약한 상세한 최종 보고서 받기
   
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
        try (Comparer comparer = new Comparer("source.emlx") 
        {
            // 비교할 추가 파일 포함
        	comparer.add("target1.emlx");
            comparer.add("target2.emlx");

            // 결과로 지정된 이름의 보고서를 가져옵니다.
            final Path resultPath = comparer.compare("result.emlx"); 

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
    title: "Java 를 사용하여 다양한 문서 비교"
    exclude: "EMLX"
    description: "Java 솔루션을 사용하면 다양한 형식의 문서를 비교할 수 있습니다.문서 변경 사항을 손쉽게 처리하여 최신 상태를 유지할 수 있습니다."
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