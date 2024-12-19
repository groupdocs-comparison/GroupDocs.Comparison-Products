
---
############################# Static ############################
layout: "format"
date:  2024-12-19T07:49:45
draft: false
lang: ko
format: Xlsx
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "XLSX 비교의 경우 GroupDocs.Comparison for Java 를 참조하십시오."
head_description: "GroupDocs.Comparison API는 XLSX 문서의 차이를 자세히 설명하는 보고서 검색을 제공합니다.Java, J2EE 및 J2SE 환경과 호환됩니다."

############################# Header ############################
title: "XLSX 스프레드시트의 변경 사항을 감지하기 위한 Java 개의 애플리케이션" 
description: "GroupDocs.Comparison Java API를 사용하면 Java, J2EE 또는 J2SE 애플리케이션 내의 XLSX 스프레드시트를 비교할 수 있습니다."
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
    title: "GroupDocs.Comparison for Java API의 이점 살펴보기"
    link: "/comparison/java/"
    link_title: "자세히 알아보기"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison for Java API를 사용하면 텍스트, 단락, 도형, 스타일 및 기타 요소에서 발견된 차이점에 대한 보고서를 생성하여 XLSX 스프레드시트를 쉽게 비교할 수 있습니다.또한 외부 라이브러리 없이도 여러 원본 파일의 변경 내용을 병합할 수 있습니다.최소한의 코드 통합으로 Java 프로젝트를 개선하세요.

############################# Steps ############################
steps:
    enable: true
    title: "여러 XLSX 개의 파일을 비교하려면 Java 를 사용하십시오."
    content: |
      [GroupDocs.Comparison](https://products.groupdocs.com/comparison/java/) 를 사용하여 MS Excel 개의 스프레드시트를 분석할 수 있습니다.
      
      1. [Maven](https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/) 에서 패키지 설치
      2. 첫 번째 XLSX 스프레드시트를 매개변수로 사용하여 비교기를 인스턴스화합니다.
      3. 비교를 위해 XLSX 개의 스프레드시트를 추가로 포함하세요.
      4. 종합적인 보고서 즐기기
   
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
        try (Comparer comparer = new Comparer("main.xlsx") 
        {
            // 비교할 추가 파일 포함
        	comparer.add("version1.xlsx");
            comparer.add("version2.xlsx");
            comparer.add("version3.xlsx");

            // 결과로 지정된 이름의 보고서를 가져옵니다.
            final Path resultPath = comparer.compare("full_report.xlsx"); 

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
    title: "Java 를 사용하여 XLSX 스프레드시트의 변경 사항 관리"
    exclude: "XLSX"
    description: "GroupDocs.Comparison Java 라이브러리는 사용자가 쉽게 작성할 수 있는 상세하고 정확한 보고서를 통해 다양한 버전의 XLSX 스프레드시트를 모니터링할 수 있도록 합니다."
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