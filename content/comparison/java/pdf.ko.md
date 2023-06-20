
---
############################# Static ############################
layout: "auto-gen-comparison"
date: 2021-05-13T12:45:19+03:00
draft: false

############################# Head ############################
head_title: "Java PDF 비교 API - PDF 파일의 차이점 비교"
head_description: "Java, J2EE, J2SE 애플리케이션에서 PDF 파일을 비교하고 병합합니다. PDF 파일, 이미지 및 문서 형식의 내용, 텍스트 및 스타일의 차이점 요약을 분석합니다."

############################# Header ############################
title: "Java의 PDF 파일 비교"
description: "Java에서 2개 이상의 PDF 파일 간에 라인별로 비교를 수행합니다. 차이점 목록을 검색하고 비교된 파일을 단일 문서에 저장합니다."
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "무료 평가판 다운로드"
    link: "https://downloads.groupdocs.com/comparison/java"

############################# SubMenu ############################
submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Comparison for Java"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-comparison-java.png"
        product: "GroupDocs.Comparison"
        platform: "자바"

    middle:
        button: 
            # 버튼 루프
            - link: "https://apireference.groupdocs.com/comparison/java"
              text: "API 참조"

            # 버튼 루프
            - link: "https://github.com/groupdocs-comparison"
              text: "코드 예제"

            # 버튼 루프
            - link: "https://products.groupdocs.app/comparison/family"
              text: "라이브 데모"

            # 버튼 루프
            - link: "https://purchase.groupdocs.com/pricing/comparison/java"
              text: "가격"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/java"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: "GroupDocs.Comparison for Java API 정보"
    content: |
        [GroupDocs.Comparison for Java](/ko/comparison/java/) API를 사용하여 이미지 및 문서 비교 기능으로 Java 애플리케이션을 강화하십시오. 동일한 형식의 비교 문서의 단락, 단어, 문자, 도형, 심지어 텍스트 스타일 내의 차이점을 식별하여 변경 사항을 병합하고 최종 문서로 내보낼 수 있습니다. 외부 라이브러리를 사용하지 않고도 PDF, Word, Excel 워크시트, PowerPoint 프레젠테이션, Visio 다이어그램, Outlook 이메일, HTML, 그림 및 이미지 파일 형식을 포함한 광범위한 문서를 비교하고 병합할 수 있습니다.

############################# Steps ############################
steps:
    enable: true
    title_left: "Java에서 PDF 파일을 비교하는 단계"
    content_left: |
        [GroupDocs.Comparison](/comparison/java/)을 사용하면 Java 개발자가 몇 줄의 코드를 사용하여 애플리케이션 내에서 PDF 파일을 쉽게 비교할 수 있습니다.
        *   소스 문서 경로 또는 스트림으로 **Comparer** 개체를 인스턴스화합니다.
        * add 메서드를 호출하고 대상 문서 경로 또는 스트림을 지정합니다.
        * 비교 메서드를 호출합니다.
    title_right: "시스템 요구 사항"
    content_right: |
        GroupDocs.Comparison for Java API는 모든 주요 플랫폼 및 운영 체제에서 지원됩니다. 아래 코드를 실행하기 전에 시스템에 다음 필수 구성 요소가 설치되어 있는지 확인하십시오.
        *   운영 체제: Microsoft Windows, Linux, MacOS
        * 개발 환경: NetBeans, Intellij IDEA, Eclipse 등
        * 자바 런타임 환경: J2SE 6.0 이상
        * [Maven](https://repository.groupdocs.com/webapp/#/artifacts/browse/tree/General/repo/com/groupdocs/groupdocs-comparison)에서 최신 버전의 Java용 GroupDocs.Comparison을 다운로드하십시오.
    code: |
        ```java
        // 로컬 파일의 문서 비교
        
        try (Comparer comparer = new Comparer("C:\\source.pdf")) {
            comparer.add("C:\\target.pdf");
            comparer.compare("C:\\result.pdf"); // 지정된 이름으로 결과 파일 생성
        }
        
        // 스트림에서 문서 비교
        
        try (Comparer comparer = new Comparer(new FileInputStream("C:\\source.pdf"))) {
            comparer.add(new FileInputStream("C:\\target.pdf"));
            comparer.compare(new FileOutputStream("C:\\result.pdf")); //지정된 이름으로 결과 파일 생성
        }
        ```

############################# Demos ############################
demos:
    enable: true
    title: "PDF 파일을 비교하기 위한 라이브 데모"
    content: |
        지금 바로 [GroupDocs.Comparison Live Demos](https://products.groupdocs.app/comparison/family) 웹사이트를 방문하여 PDF 파일을 비교하세요.
        라이브 데모에는 다음과 같은 이점이 있습니다.

############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-pdf"
          title: "PDF 파일 형식 정보"
          content: |
            PDF(Portable Document Format)는 Adobe에서 1990년대에 만든 문서 유형입니다. 이 파일 형식의 목적은 응용 프로그램 소프트웨어, 하드웨어 및 운영 체제와 독립적인 형식으로 문서 및 기타 참조 자료를 표현하기 위한 표준을 도입하는 것이었습니다. PDF 파일은 확장 프로그램/플러그인을 통해 Adobe Acrobat Reader/Writer는 물론 Chrome, Safari, Firefox와 같은 대부분의 최신 브라우저에서 열 수 있습니다. 상업적으로 사용 가능한 대부분의 소프트웨어 제품군은 추가 소프트웨어 구성 요소 없이도 문서를 PDF 파일 형식으로 변환할 수 있습니다. 따라서 PDF 파일 형식은 원본 문서의 일부가 될 수 있는 텍스트, 이미지, 하이퍼링크, 양식 필드, 리치 미디어, 디지털 서명, 첨부 파일, 메타데이터, 지형 공간 기능 및 3D 개체와 같은 정보를 포함할 수 있는 완전한 기능을 가지고 있습니다.
          link: "https://docs.fileformat.com/image/pdf/"

############################# More Formats ############################
more_formats:
    enable: true
    title: "다른 파일 형식 비교"
    content: |
        Java용 다중 형식 이미지 및 문서 비교 API. 외부 소프트웨어 없이 아래에서 널리 사용되는 일부 파일 형식을 비교하십시오.
    format: 
        # format loop
        - name: "Compare PDF Files"
          link: "https://products.groupdocs.com/comparison/java/pdf/"
          description: "Adobe Portable Document Format"

        # format loop
        - name: "Compare DOC Files"
          link: "https://products.groupdocs.com/comparison/java/doc/"
          description: "Microsoft Word Document"

        # format loop
        - name: "Compare DOCM Files"
          link: "https://products.groupdocs.com/comparison/java/docm/"
          description: "Microsoft Word Macro-Enabled Document"

        # format loop
        - name: "Compare DOCX Files"
          link: "https://products.groupdocs.com/comparison/java/docx/"
          description: "Microsoft Word Open XML Document"

        # format loop
        - name: "Compare DOT Files"
          link: "https://products.groupdocs.com/comparison/java/dot/"
          description: "Microsoft Word Document Template"

        # format loop
        - name: "Compare DOTM Files"
          link: "https://products.groupdocs.com/comparison/java/dotm/"
          description: "Microsoft Word Macro-Enabled Template"

        # format loop
        - name: "Compare DOTX Files"
          link: "https://products.groupdocs.com/comparison/java/dotx/"
          description: "Word Open XML Document Template"

        # format loop
        - name: "Compare RTF Files"
          link: "https://products.groupdocs.com/comparison/java/rtf/"
          description: "Rich Text File Format"

        # format loop
        - name: "Compare TXT Files"
          link: "https://products.groupdocs.com/comparison/java/txt/"
          description: "Plain Text File Format"

        # format loop
        - name: "Compare XLS Files"
          link: "https://products.groupdocs.com/comparison/java/xls/"
          description: "Microsoft Excel Binary File Format"

        # format loop
        - name: "Compare XLSX Files"
          link: "https://products.groupdocs.com/comparison/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop
        - name: "Compare XLTM Files"
          link: "https://products.groupdocs.com/comparison/java/xltm/"
          description: "Microsoft Excel macro-enabled template"

        # format loop
        - name: "Compare XLSM Files"
          link: "https://products.groupdocs.com/comparison/java/xlsm/"
          description: "Microsoft Excel Macro-Enabled Spreadsheet"

        # format loop
        - name: "Compare XLSB Files"
          link: "https://products.groupdocs.com/comparison/java/xlsb/"
          description: "Microsoft Excel Binary Spreadsheet File"

        # format loop
        - name: "Compare CSV Files"
          link: "https://products.groupdocs.com/comparison/java/csv/"
          description: "Comma Separated Values File"

        # format loop
        - name: "Compare PPT Files"
          link: "https://products.groupdocs.com/comparison/java/ppt/"
          description: "PowerPoint Presentation"

        # format loop
        - name: "Compare PPS Files"
          link: "https://products.groupdocs.com/comparison/java/pps/"
          description: "Microsoft PowerPoint Slide Show"

        # format loop
        - name: "Compare PPTX Files"
          link: "https://products.groupdocs.com/comparison/java/pptx/"
          description: "PowerPoint Open XML Presentation"

        # format loop
        - name: "Compare PPSX Files"
          link: "https://products.groupdocs.com/comparison/java/ppsx/"
          description: "PowerPoint Open XML Slide Show"

        # format loop
        - name: "Compare POT Files"
          link: "https://products.groupdocs.com/comparison/java/pot/"
          description: "Microsoft PowerPoint template"

        # format loop
        - name: "Compare POTX Files"
          link: "https://products.groupdocs.com/comparison/java/potx/"
          description: "Microsoft PowerPoint Open XML Template"

        # format loop
        - name: "Compare ODS Files"
          link: "https://products.groupdocs.com/comparison/java/ods/"
          description: "Open Document Spreadsheet"

        # format loop
        - name: "Compare ODP Files"
          link: "https://products.groupdocs.com/comparison/java/odp/"
          description: "OpenDocument Presentation File Format"

        # format loop
        - name: "Compare OTP Files"
          link: "https://products.groupdocs.com/comparison/java/otp/"
          description: "Origin Graph Template"

        # format loop
        - name: "Compare ODT Files"
          link: "https://products.groupdocs.com/comparison/java/odt/"
          description: "Open Document Text"

        # format loop
        - name: "Compare OTT Files"
          link: "https://products.groupdocs.com/comparison/java/ott/"
          description: "Open Document Template"

        # format loop
        - name: "Compare VST Files"
          link: "https://products.groupdocs.com/comparison/java/vst/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare JPEG Files"
          link: "https://products.groupdocs.com/comparison/java/jpeg/"
          description: "JPEG Image"

        # format loop
        - name: "Compare PNG Files"
          link: "https://products.groupdocs.com/comparison/java/png/"
          description: "Portable Network Graphic"

        # format loop
        - name: "Compare GIF Files"
          link: "https://products.groupdocs.com/comparison/java/gif/"
          description: "Graphical Interchange Format File"

        # format loop
        - name: "Compare BMP Files"
          link: "https://products.groupdocs.com/comparison/java/bmp/"
          description: "Bitmap File Format"

        # format loop
        - name: "Compare HTML Files"
          link: "https://products.groupdocs.com/comparison/java/html/"
          description: "Hyper Text Markup Language"

        # format loop
        - name: "Compare MHT Files"
          link: "https://products.groupdocs.com/comparison/java/mht/"
          description: "Mime HTML"

        # format loop
        - name: "Compare MHTML Files"
          link: "https://products.groupdocs.com/comparison/java/mhtml/"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop
        - name: "Compare MSG Files"
          link: "https://products.groupdocs.com/comparison/java/msg/"
          description: "Microsoft Outlook E-mail Message"

        # format loop
        - name: "Compare EML Files"
          link: "https://products.groupdocs.com/comparison/java/eml/"
          description: "E-mail Message"

        # format loop
        - name: "Compare EMLX Files"
          link: "https://products.groupdocs.com/comparison/java/emlx/"
          description: "Apple Mail E-mail File"

        # format loop
        - name: "Compare ONE Files"
          link: "https://products.groupdocs.com/comparison/java/one/"
          description: "Microsoft OneNote"

        # format loop
        - name: "Compare VSD Files"
          link: "https://products.groupdocs.com/comparison/java/vsd/"
          description: "Microsoft Visio 2003-2010 Drawing"

        # format loop
        - name: "Compare VSDX Files"
          link: "https://products.groupdocs.com/comparison/java/vsdx/"
          description: "Microsoft Visio Drawing"

        # format loop
        - name: "Compare VSS Files"
          link: "https://products.groupdocs.com/comparison/java/vss/"
          description: "Microsoft Visio 2003-2010 Stencil"

        # format loop
        - name: "Compare VST Files"
          link: "https://products.groupdocs.com/comparison/java/vst/"
          description: "Microsoft Visio 2003-2010 Template"

        # format loop
        - name: "Compare VDX Files"
          link: "https://products.groupdocs.com/comparison/java/vdx/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare CS Files"
          link: "https://products.groupdocs.com/comparison/java/cs/"
          description: "CSharp Language"

        # format loop
        - name: "Compare Java Files"
          link: "https://products.groupdocs.com/comparison/java/java/"
          description: "Java Language"

        # format loop
        - name: "Compare CPP Files"
          link: "https://products.groupdocs.com/comparison/java/cpp/"
          description: "C++ Language"

        # format loop
        - name: "Compare JS Files"
          link: "https://products.groupdocs.com/comparison/java/js/"
          description: "JavaScript Language"

        # format loop
        - name: "Compare PY Files"
          link: "https://products.groupdocs.com/comparison/java/py/"
          description: "Python Language"

        # format loop
        - name: "Compare RB Files"
          link: "https://products.groupdocs.com/comparison/java/rb/"
          description: "Ruby Language"

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison offers document viewing APIs for other popular formats"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for .NET PDF"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
          product: "GroupDocs.Comparison"
          platform: ".NET"
          link: "/comparison/net/pdf/"

############################# Back to top ###############################
back_to_top:
    enable: true
---
