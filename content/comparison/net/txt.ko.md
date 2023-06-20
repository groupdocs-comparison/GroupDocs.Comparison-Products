
---
############################# Static ############################
layout: "auto-gen-comparison"
date: 2021-05-13T12:45:19+03:00
draft: false

############################# Head ############################
head_title: ".NET에서 두 TXT 파일 비교 | 문서 비교 API"
head_description: "C# .NET 애플리케이션에서 두 개 이상의 TXT 파일을 비교하고 병합합니다. TXT 파일, 이미지 및 문서 형식의 콘텐츠, 텍스트 및 스타일의 차이점 요약을 검색합니다."

############################# Header ############################
title: "C# .NET에서 TXT 파일 비교"
description: ".NET 문서 비교 API는 TXT 파일의 두 버전 간 변경 사항을 감지하고 비교된 문서 간의 차이점에 대한 자세한 요약과 함께 최종 문서로 내보냅니다."
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "무료 평가판 다운로드"
    link: "https://downloads.groupdocs.com/comparison/net"

############################# SubMenu ############################
submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Comparison for .NET"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-comparison-net.png"
        product: "GroupDocs.Comparison"
        platform: ".그물"

    middle:
        button: 
            # 버튼 루프
            - link: "https://apireference.groupdocs.com/comparison/net"
              text: "API 참조"

            # 버튼 루프
            - link: "https://github.com/groupdocs-comparison"
              text: "코드 예제"

            # 버튼 루프
            - link: "https://products.groupdocs.app/comparison/family"
              text: "라이브 데모"

            # 버튼 루프
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "가격"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/net"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: ".NET API용 GroupDocs.Comparison 정보"
    content: |
        [GroupDocs.Comparison for .NET](/ko/comparison/net/)은 동일한 형식의 여러 이미지와 문서를 비교하기 위한 기본 .NET API입니다. 비교 문서의 단락, 단어, 문자, 모양, 심지어 텍스트 스타일 내의 차이점을 감지하고 변경 사항을 병합하고 최종 문서로 내보낼 수 있습니다. 외부 라이브러리를 사용하지 않고 PDF, Word 문서, Excel 스프레드시트, PowerPoint 프레젠테이션, Visio 다이어그램, Outlook 이메일, HTML, 그림 및 이미지 파일 형식을 비교하고 병합할 수 있습니다.

############################# Steps ############################
steps:
    enable: true
    title_left: "C#에서 TXT 파일을 비교하는 단계"
    content_left: |
        [GroupDocs.Comparison](/comparison/net/)을 사용하면 .NET 개발자가 몇 가지 간단한 단계를 구현하여 애플리케이션에서 여러 TXT 파일을 쉽게 비교 및 ​​병합할 수 있습니다.
        *   소스 문서 경로 또는 스트림으로 **Comparer** 개체를 인스턴스화합니다.
        * Add 메서드를 호출하고 대상 문서 경로 또는 스트림을 지정합니다. 모든 대상 문서에 대해 이 단계를 반복합니다.
        * 호출 비교 방법.
    title_right: "시스템 요구 사항"
    content_right: |
        GroupDocs.Comparison for .NET API는 모든 주요 플랫폼 및 운영 체제에서 지원됩니다. 아래 코드를 실행하기 전에 시스템에 다음 필수 구성 요소가 설치되어 있는지 확인하십시오.
        *   운영 체제: Microsoft Windows, Linux, MacOS
        * 개발 환경: Microsoft Visual Studio, Xamarin, MonoDevelop
        * 프레임워크: .NET Framework, .NET Standard, .NET Core, Mono
        * [NuGet](https://www.nuget.org/packages/groupdocs.comparison)에서 다운로드한 .NET용 GroupDocs.Comparison의 최신 버전을 받으세요.
    code: |
        ```cs
        // 로컬 디스크에서 여러 문서를 비교합니다.
        
        using (Comparer comparer = new Comparer("source.txt"))
        {
        	comparer.Add("target1.txt");
            comparer.Add("target2.txt");
            comparer.Add("target3.txt");
            comparer.Compare("result.txt"); // 지정된 이름으로 결과 파일 생성
        }
        
        // 스트림에서 여러 문서 비교
        
        using (Comparer comparer = new Comparer(File.OpenRead("source.txt")))
        {
        	comparer.Add(File.OpenRead("target1.txt"));
            comparer.Add(File.OpenRead("target2.txt"));
            comparer.Add(File.OpenRead("target3.txt"));
            comparer.Compare(File.Create("result.txt")); // 지정된 이름으로 결과 파일 생성
        }
        ```

############################# Demos ############################
demos:
    enable: true
    title: "TXT 파일 비교 라이브 데모"
    content: |
        지금 바로 [GroupDocs.Comparison Live Demos](https://products.groupdocs.app/comparison/family) 웹사이트를 방문하여 TXT 파일 간의 차이점을 감지하세요.
        라이브 데모에는 다음과 같은 이점이 있습니다.

############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-txt"
          title: "TXT 파일 형식 정보"
          content: |
            .TXT 확장자를 가진 파일은 라인 형태의 일반 텍스트를 포함하는 텍스트 문서를 나타냅니다. 텍스트 문서의 단락은 캐리지 리턴으로 인식되며 파일 내용을 더 잘 정렬하는 데 사용됩니다. 표준 텍스트 문서는 다른 운영 체제의 모든 텍스트 편집기 또는 워드 프로세싱 응용 프로그램에서 열 수 있습니다. 이러한 파일에 포함된 모든 텍스트는 사람이 읽을 수 있는 형식이며 일련의 문자로 표시됩니다.
          link: "https://docs.fileformat.com/image/txt/"

############################# More Formats ############################
more_formats:
    enable: true
    title: "다른 파일 형식 비교"
    content: |
        .NET용 다중 형식 문서 및 이미지 비교 API. 외부 도구를 사용하지 않고 동일한 형식의 문서 간의 차이점을 분석합니다.
    format: 
        # format loop
        - name: "Compare PDF Files"
          link: "https://products.groupdocs.com/comparison/net/pdf/"
          description: "Adobe Portable Document Format"

        # format loop
        - name: "Compare DOC Files"
          link: "https://products.groupdocs.com/comparison/net/doc/"
          description: "Microsoft Word Document"

        # format loop
        - name: "Compare DOCM Files"
          link: "https://products.groupdocs.com/comparison/net/docm/"
          description: "Microsoft Word Macro-Enabled Document"

        # format loop
        - name: "Compare DOCX Files"
          link: "https://products.groupdocs.com/comparison/net/docx/"
          description: "Microsoft Word Open XML Document"

        # format loop
        - name: "Compare DOT Files"
          link: "https://products.groupdocs.com/comparison/net/dot/"
          description: "Microsoft Word Document Template"

        # format loop
        - name: "Compare DOTM Files"
          link: "https://products.groupdocs.com/comparison/net/dotm/"
          description: "Microsoft Word Macro-Enabled Template"

        # format loop
        - name: "Compare DOTX Files"
          link: "https://products.groupdocs.com/comparison/net/dotx/"
          description: "Word Open XML Document Template"

        # format loop
        - name: "Compare RTF Files"
          link: "https://products.groupdocs.com/comparison/net/rtf/"
          description: "Rich Text File Format"

        # format loop
        - name: "Compare TXT Files"
          link: "https://products.groupdocs.com/comparison/net/txt/"
          description: "Plain Text File Format"

        # format loop
        - name: "Compare XLS Files"
          link: "https://products.groupdocs.com/comparison/net/xls/"
          description: "Microsoft Excel Binary File Format"

        # format loop
        - name: "Compare XLSX Files"
          link: "https://products.groupdocs.com/comparison/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop
        - name: "Compare XLTM Files"
          link: "https://products.groupdocs.com/comparison/net/xltm/"
          description: "Microsoft Excel macro-enabled template"

        # format loop
        - name: "Compare XLSM Files"
          link: "https://products.groupdocs.com/comparison/net/xlsm/"
          description: "Microsoft Excel Macro-Enabled Spreadsheet"

        # format loop
        - name: "Compare XLSB Files"
          link: "https://products.groupdocs.com/comparison/net/xlsb/"
          description: "Microsoft Excel Binary Spreadsheet File"

        # format loop
        - name: "Compare CSV Files"
          link: "https://products.groupdocs.com/comparison/net/csv/"
          description: "Comma Separated Values File"

        # format loop
        - name: "Compare PPT Files"
          link: "https://products.groupdocs.com/comparison/net/ppt/"
          description: "PowerPoint Presentation"

        # format loop
        - name: "Compare PPS Files"
          link: "https://products.groupdocs.com/comparison/net/pps/"
          description: "Microsoft PowerPoint Slide Show"

        # format loop
        - name: "Compare PPTX Files"
          link: "https://products.groupdocs.com/comparison/net/pptx/"
          description: "PowerPoint Open XML Presentation"

        # format loop
        - name: "Compare PPSX Files"
          link: "https://products.groupdocs.com/comparison/net/ppsx/"
          description: "PowerPoint Open XML Slide Show"

        # format loop
        - name: "Compare POT Files"
          link: "https://products.groupdocs.com/comparison/net/pot/"
          description: "Microsoft PowerPoint template"

        # format loop
        - name: "Compare POTX Files"
          link: "https://products.groupdocs.com/comparison/net/potx/"
          description: "Microsoft PowerPoint Open XML Template"

        # format loop
        - name: "Compare ODS Files"
          link: "https://products.groupdocs.com/comparison/net/ods/"
          description: "Open Document Spreadsheet"

        # format loop
        - name: "Compare ODP Files"
          link: "https://products.groupdocs.com/comparison/net/odp/"
          description: "OpenDocument Presentation File Format"

        # format loop
        - name: "Compare OTP Files"
          link: "https://products.groupdocs.com/comparison/net/otp/"
          description: "Origin Graph Template"

        # format loop
        - name: "Compare ODT Files"
          link: "https://products.groupdocs.com/comparison/net/odt/"
          description: "Open Document Text"

        # format loop
        - name: "Compare OTT Files"
          link: "https://products.groupdocs.com/comparison/net/ott/"
          description: "Open Document Template"

        # format loop
        - name: "Compare VST Files"
          link: "https://products.groupdocs.com/comparison/net/vst/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare JPEG Files"
          link: "https://products.groupdocs.com/comparison/net/jpeg/"
          description: "JPEG Image"

        # format loop
        - name: "Compare PNG Files"
          link: "https://products.groupdocs.com/comparison/net/png/"
          description: "Portable Network Graphic"

        # format loop
        - name: "Compare GIF Files"
          link: "https://products.groupdocs.com/comparison/net/gif/"
          description: "Graphical Interchange Format File"

        # format loop
        - name: "Compare BMP Files"
          link: "https://products.groupdocs.com/comparison/net/bmp/"
          description: "Bitmap File Format"

        # format loop
        - name: "Compare HTML Files"
          link: "https://products.groupdocs.com/comparison/net/html/"
          description: "Hyper Text Markup Language"

        # format loop
        - name: "Compare MHT Files"
          link: "https://products.groupdocs.com/comparison/net/mht/"
          description: "Mime HTML"

        # format loop
        - name: "Compare MHTML Files"
          link: "https://products.groupdocs.com/comparison/net/mhtml/"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop
        - name: "Compare MSG Files"
          link: "https://products.groupdocs.com/comparison/net/msg/"
          description: "Microsoft Outlook E-mail Message"

        # format loop
        - name: "Compare EML Files"
          link: "https://products.groupdocs.com/comparison/net/eml/"
          description: "E-mail Message"

        # format loop
        - name: "Compare EMLX Files"
          link: "https://products.groupdocs.com/comparison/net/emlx/"
          description: "Apple Mail E-mail File"

        # format loop
        - name: "Compare ONE Files"
          link: "https://products.groupdocs.com/comparison/net/one/"
          description: "Microsoft OneNote"

        # format loop
        - name: "Compare VSD Files"
          link: "https://products.groupdocs.com/comparison/net/vsd/"
          description: "Microsoft Visio 2003-2010 Drawing"

        # format loop
        - name: "Compare VSDX Files"
          link: "https://products.groupdocs.com/comparison/net/vsdx/"
          description: "Microsoft Visio Drawing"

        # format loop
        - name: "Compare VSS Files"
          link: "https://products.groupdocs.com/comparison/net/vss/"
          description: "Microsoft Visio 2003-2010 Stencil"

        # format loop
        - name: "Compare VST Files"
          link: "https://products.groupdocs.com/comparison/net/vst/"
          description: "Microsoft Visio 2003-2010 Template"

        # format loop
        - name: "Compare VDX Files"
          link: "https://products.groupdocs.com/comparison/net/vdx/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare CS Files"
          link: "https://products.groupdocs.com/comparison/net/cs/"
          description: "CSharp Language"

        # format loop
        - name: "Compare Java Files"
          link: "https://products.groupdocs.com/comparison/net/java/"
          description: "Java Language"

        # format loop
        - name: "Compare CPP Files"
          link: "https://products.groupdocs.com/comparison/net/cpp/"
          description: "C++ Language"

        # format loop
        - name: "Compare JS Files"
          link: "https://products.groupdocs.com/comparison/net/js/"
          description: "JavaScript Language"

        # format loop
        - name: "Compare PY Files"
          link: "https://products.groupdocs.com/comparison/net/py/"
          description: "Python Language"

        # format loop
        - name: "Compare RB Files"
          link: "https://products.groupdocs.com/comparison/net/rb/"
          description: "Ruby Language"

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison offers document viewing APIs for other popular formats"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for Java TXT"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/txt/"

############################# Back to top ###############################
back_to_top:
    enable: true
---
