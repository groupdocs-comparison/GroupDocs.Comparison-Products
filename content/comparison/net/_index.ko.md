---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "C# .NET 문서 비교 API | PDF Word Excel 웹 및 텍스트 비교 및 ​​병합"
head_description: "C# .NET 문서 비교 API. PDF Word DOC DOCX, Excel 스프레드시트, PPT, PPTX, HTML, EMLX MSG, VSDX, DXF DWG 및 이미지 파일 형식을 비교하고 병합합니다."

############################# Header ############################
title: "파일을 비교하는 .NET API"
description: ".NET 문서 비교 API를 사용하여 파일의 콘텐츠 및 스타일 차이를 확인하고 비교하는 애플리케이션을 개발합니다."
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
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
        product: "GroupDocs.Comparison"
        platform: ".NET"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "개요"

            # button loop
            - link: "#features"
              text: "특징"

            # button loop
            - link: "#support"
              text: "지원하다"

            # button loop
            - link: "https://products.groupdocs.app/comparison"
              text: "라이브 데모"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "가격"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    example_image: "/comparison/comparison-example.webp"
    content: |
      
    more_overview:
      # more_overview_loop
      - title: "GroupDocs.Comparison for .NET이(가) 무엇인가요?"
        content: "GroupDocs.Comparison for .NET API는 C#, ASP.NET 또는 .NET 소프트웨어 플랫폼과 관련된 기타 기술에서 동일하거나 다른 형식의 문서 간의 차이점을 검색하고 강조 표시하기 위한 애플리케이션을 만들 때 사용할 수 있는 빠르고 안정적인 솔루션입니다."

      # more_overview_loop
      - title: "지원되는 형식"
        content: "GroupDocs.Comparison 라이브러리는 PDF, HTML, 전자 메일 Outlook, Microsoft Office Word 문서, Excel 스프레드시트, PowerPoint 프레젠테이션, OneNote, Visio 다이어그램, 텍스트, png 등 널리 사용되는 이미지와 문서 형식 간의 콘텐츠 및 텍스트 스타일 차이 감지를 지원합니다. , gif, bmp 이미지와 기타 수백 가지 형식이 있습니다."
        
      # more_overview_loop
      - title: "비교 기능"
        content: "비교를 수행하여 단어, 단락, 표 또는 차트의 내용과 스타일의 변경 사항을 감지할 수 있으며 차이점, 해당 번호 및 유형에 대한 요약을 나열하는 비교 문서를 제공합니다. GroupDocs.Comparison for .NET은(는) 원본 문서에 대한 기본 정보를 쉽게 추출하고, 파일이나 데이터 스트림을 통해 다양한 형식의 단순하고 비밀번호로 보호되고 암호화된 문서를 비교하고 저장할 수 있습니다."
        
      # more_overview_loop
      - title: "문서 및 예제"
        content: "코드 예제와 함께 다양한 플랫폼에서 비교 라이브러리를 사용하는 방법에 대한 많은 문서가 이미 있으므로 애플리케이션에서 .NET API에 대한 GroupDocs.Comparison을 사용하여 작업하는 방법에 대해 열심히 생각할 필요가 없습니다."
        
      # more_overview_loop
      - title: "호환성"
        content: "GroupDocs.Comparison for .NET을(를) 사용하여 .NET 플랫폼 기반의 모든 개발 환경에서 애플리케이션을 생성할 수 있습니다. 모든 .NET 기반 언어와 호환되며 Mono 또는 .NET 프레임워크(.NET Core 포함)를 설치할 수 있는 널리 사용되는 운영 체제(Windows, Linux, MacOS)를 지원합니다."
    examples:
      enable: true
      
    more_feature:
      # more_feature_loop
      - title: ".NET API를 사용하여 쉽게 문서 비교"
        content: |
          GroupDocs.Comparison for .NET API는 파일을 비교하는 쉽고 효율적인 방법을 제공합니다. 다음은 C#을 사용하여 두 DOCX 문서를 비교하는 방법을 보여주는 예입니다.  

          ```cs
          // 비교할 소스 및 대상 파일
          string source = @"source.docx";
          string target = @"target.docx";
          Comparer comparer = new Comparer();
          // 두 문서 비교
          ICompareResult result = comparer.Compare(source, target, new ComparisonSettings());
          ```
      # more_feature_loop
      - title: "비교를 위한 세부 수준 선택"
        content: "GroupDocs.Comparison for .NET을 사용하면 문서를 비교할 범위를 지정할 수 있습니다. 낮음(이미지 그리드의 정확도로 텍스트를 단어 단위로 비교 = 50), 중간(이미지 그리드의 정확도로 텍스트를 문자별로 비교 = 100) 또는 높음(이미지 그리드의 정확도로 문자별로 텍스트 비교 = ) 중에서 선택할 수 있습니다. 150)."

      # more_feature_loop
      - title: "텍스트 스타일 비교 지원"
        content: |
          GroupDocs.Comparison for .NET은(는) 텍스트 스타일을 비교하는 기능을 제공합니다.  

          문서의 단어와 문자를 비교하는 동안 글꼴 이름, 글꼴 크기, 글꼴 색상, 글꼴 스타일(굵게, 기울임꼴, 밑줄, 작은 대문자, 하이퍼링크) 및 밑줄 색상(해당되는 경우)을 비교하여 차이점을 찾을 수 있습니다.  

          단락을 비교하면서 단락 정렬, 들여쓰기(왼쪽 들여쓰기, 오른쪽 들여쓰기), 단락 간격(뒤 공백, 앞 공백), 첫 줄 들여쓰기, 줄 간격 등의 스타일을 비교할 수 있습니다.  

          GroupDocs.Comparison for .NET은(해당되는 경우) 바닥글 거리, 페이지 높이 및 방향, 여백(왼쪽, 오른쪽, 위쪽 및 아래쪽), 테두리 선 너비, 테두리 색상 등 페이지의 다른 섹션 비교도 지원합니다.  
      
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          다음은 GroupDocs.Comparison for .NET의 개요입니다.
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "개요"
          content: |
            * 문서 비교
            * HTML 파일 비교
            * PDF 비교
            * 다이어그램 비교
            * 파일 내용 비교
            * 텍스트 스타일 비교
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison for .NET은(는) Microsoft Office, PDF, 이미지 등을 포함하여 널리 사용되는 모든 [문서 파일 형식](https://docs.groupdocs.com/comparison/net/supported-document-formats/)을 지원합니다. .
        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** [DOC](https://products.groupdocs.com/comparison/net/doc/), [DOCX](https://products.groupdocs.com/comparison/net/docx/), [DOCM](https://products.groupdocs.com/comparison/net/docm/), [DOT](https://products.groupdocs.com/comparison/net/dot/), [DOTX](https://products.groupdocs.com/comparison/net/dotx/), [DOTM](https://products.groupdocs.com/comparison/net/dotm/), [RTF](https://products.groupdocs.com/comparison/net/rtf/), [TXT](https://products.groupdocs.com/comparison/net/txt/)
                * **Excel:** [XLS](https://products.groupdocs.com/comparison/net/xls/), [XLSX](https://products.groupdocs.com/comparison/net/xlsx/), [XLSM](https://products.groupdocs.com/comparison/net/xlsm/), [XLSB](https://products.groupdocs.com/comparison/net/xlsb/), [XLTM](https://products.groupdocs.com/comparison/net/xltm/), [XLT](https://products.groupdocs.com/comparison/net/xlt/), [XLTM](https://products.groupdocs.com/comparison/net/xltm/), [XLTX](https://products.groupdocs.com/comparison/net/xltx/), [XLAM](https://products.groupdocs.com/comparison/net/xlam/), [SXC](https://products.groupdocs.com/comparison/net/sxc/), [SpreadsheetML](https://products.groupdocs.com/comparison/net/xml/)
                * **PowerPoint:** [PPT](https://products.groupdocs.com/comparison/net/ppt/), [PPTX](https://products.groupdocs.com/comparison/net/pptx/), [PPS](https://products.groupdocs.com/comparison/net/pps/), [PPSX](https://products.groupdocs.com/comparison/net/ppsx/), [PPSM](https://products.groupdocs.com/comparison/net/ppsm/), [POT](https://products.groupdocs.com/comparison/net/pot/), [POTM](https://products.groupdocs.com/comparison/net/potm/), [POTX](https://products.groupdocs.com/comparison/net/potx/), [PPTM](https://products.groupdocs.com/comparison/net/pptm/)
                * **Visio:** [VSD](https://products.groupdocs.com/comparison/net/vsd/), [VDX](https://products.groupdocs.com/comparison/net/vdx/), [VSS](https://products.groupdocs.com/comparison/net/vss/), [VSSX](https://products.groupdocs.com/comparison/net/vssx/), [VSX](https://products.groupdocs.com/comparison/net/vsx/), [VST](https://products.groupdocs.com/comparison/net/vst/), [VSTX](https://products.groupdocs.com/comparison/net/vstx/), [VTX](https://products.groupdocs.com/comparison/net/vtx/), [VSDX](https://products.groupdocs.com/comparison/net/vsdx/), [VDW](https://products.groupdocs.com/comparison/net/vdw/), [VSTM](https://products.groupdocs.com/comparison/net/vstm/), [VSSM](https://products.groupdocs.com/comparison/net/vssm/), [VSDM](https://products.groupdocs.com/comparison/net/vsdm/)
                * **Outlook:** [MSG](https://products.groupdocs.com/comparison/net/msg/), [EML](https://products.groupdocs.com/comparison/net/eml/), [EMLX](https://products.groupdocs.com/comparison/net/emlx/), [PST](https://products.groupdocs.com/comparison/net/pst/), [OST](https://products.groupdocs.com/comparison/net/ost/)
                * **OneNote:** [ONE](https://products.groupdocs.com/comparison/net/one/)

        right:
          enable: true
          table:
            # table loop
            - title: "기타 형식"
              content: |
                * **프로그래밍 언어**: [CS](https://products.groupdocs.com/comparison/net/cs/), [Java](https://products.groupdocs.com/comparison/net/java/), [CPP](https://products.groupdocs.com/comparison/net/cpp/), [JS](https://products.groupdocs.com/comparison/net/js/), [PY](https://products.groupdocs.com/comparison/net/py/), [RB](https://products.groupdocs.com/comparison/net/rb/), [PL](https://products.groupdocs.com/comparison/net/pl/), [ASM](https://products.groupdocs.com/comparison/net/asm/), [GROOVY](https://products.groupdocs.com/comparison/net/groovy/), [JSON](https://products.groupdocs.com/comparison/net/json/), [PHP](https://products.groupdocs.com/comparison/net/php/), [SQL](https://products.groupdocs.com/comparison/net/sql/), [LOG](https://products.groupdocs.com/comparison/net/log/), [DIFF](https://products.groupdocs.com/comparison/net/diff/), [LESS](https://products.groupdocs.com/comparison/net/less/), [SCALA](https://products.groupdocs.com/comparison/net/scala/)
                * **OpenDocument**: [ODT](https://products.groupdocs.com/comparison/net/odt/), [OTT](https://products.groupdocs.com/comparison/net/ott/), [ODS](https://products.groupdocs.com/comparison/net/ods/), [ODP](https://products.groupdocs.com/comparison/net/odp/), [OTP](https://products.groupdocs.com/comparison/net/otp/)
                * **Portable**: [PDF](https://products.groupdocs.com/comparison/net/pdf/), [MOBI](https://products.groupdocs.com/comparison/net/mobi/)
                * **AutoCAD**: [DXF](https://products.groupdocs.com/comparison/net/dxf/), [DWG](https://products.groupdocs.com/comparison/net/dwg/)
                * **Email**: [EML](https://products.groupdocs.com/comparison/net/eml/), [EMLX](https://products.groupdocs.com/comparison/net/emlx/), [MSG](https://products.groupdocs.com/comparison/net/msg/)
                * **Images**: [JPEG](https://products.groupdocs.com/comparison/net/jpeg/), [BMP](https://products.groupdocs.com/comparison/net/bmp/), [PNG](https://products.groupdocs.com/comparison/net/png/), [GIF](https://products.groupdocs.com/comparison/net/gif/), [DCM](https://products.groupdocs.com/comparison/net/dcm/), [DICOM](https://products.groupdocs.com/comparison/net/dicom/), [DjVu](https://products.groupdocs.com/comparison/net/djvu/)
                * **Web**: [HTM](https://products.groupdocs.com/comparison/net/htm/), [HTML](https://products.groupdocs.com/comparison/net/html/), [MHTML](https://products.groupdocs.com/comparison/net/mhtml/)
                * **Text**: [TXT](https://products.groupdocs.com/comparison/net/txt/)

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Comparison for .NET은(는) 다음 운영 체제, 프레임워크 및 패키지 관리자를 지원합니다.
      
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "운영체제"
              content: |
                * Windows Desktop
                * Windows Server
                * Windows Azure
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "지원되는 프레임워크"
              content: |
                * .NET Framework 2.0 또는 더 높게
                * Mono Framework 1.2 또는 더 높게
                * .NET Standard 2.0
                * .NET Core 2.0

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "패키지 관리자"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "개발 환경"
              content: |
                * Microsoft Visual Studio
                * Xamarin.Android
                * Xamarin.IOS
                * Xamarin.Mac
                * MonoDevelop

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Comparison for .NET 기능"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "[콘텐츠 및 글꼴 스타일의 차이점 식별](https://docs.groupdocs.com/comparison/net/compare-documents/)"

      # feature loop
      - icon: "fas fa-eye"
        content: "[파일 비교 후 발견된 모든 차이점에 대한 요약 보고서 저장](https://docs.groupdocs.com/comparison/net/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-bolt"
        content: "[차이점 분석 후 변경 사항 적용 또는 거부 및 결과 파일 내보내기](https://docs.groupdocs.com/comparison/net/accept-or-reject-detected-changes/)"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "[Word 파일을 비교하는 동안 Microsoft Word “변경 사항 추적” 기능 지원](https://docs.groupdocs.com/comparison/net/show-revisions/)"

      # feature loop
      - icon: "fas fa-code"
        content: "[비교되는 각 문서에서 발생하는 변경 사항을 고유하게 찾아냅니다.](https://docs.groupdocs.com/comparison/net/get-list-of-changes/)"

      # feature loop
      - icon: "fas fa-cloud"
        content: "[스트림을 통해 문서 읽기 및 보내기](https://docs.groupdocs.com/comparison/net/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "[종량제 라이선스 - API 사용량에 따라 청구](https://docs.groupdocs.com/comparison/net/licensing-and-evaluation-limitations/)"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "[여러 소스 문서를 단일 대상 문서와 비교](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/)"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "[Word 파일의 특정 페이지를 서로 비교 - 단일 Word 문서의 모든 변경 사항을 수락하거나 거부합니다.](https://docs.groupdocs.com/comparison/net/accept-or-reject-detected-changes/)"

      # feature loop
      - icon: "fas fa-border-all"
        content: "[최대 3개의 Word 문서를 병합하고 Word 파일에 사용된 수식을 비교합니다.](https://docs.groupdocs.com/comparison/net/how-to-merge-source-code-files/)"

      # feature loop
      - icon: "fas fa-wrench"
        content: "[filePath에서 문서에 대한 정보 가져오기](https://docs.groupdocs.com/comparison/net/get-file-info/)"

      # feature loop
      - icon: "fas fa-columns"
        content: "[HTML 비교 결과를 이미지로 저장](https://docs.groupdocs.com/comparison/net/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-file-word"
        content: "[삭제된 콘텐츠를 표시하거나 숨기는 옵션](https://docs.groupdocs.com/comparison/net/show-gap-lines/)"

      # feature loop
      - icon: "fas fa-envelope"
        content: "[문서의 스타일 비교를 켜거나 끄는 옵션](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fas fa-print"
        content: "[비교 문서에서 삽입, 삭제 및 스타일 변경 항목을 표시하기 위한 문자열 지정](https://docs.groupdocs.com/comparison/net/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "[비교 텍스트의 스타일을 지정하기 위해 단어 구분 기호 및 글꼴 색상 지정](https://docs.groupdocs.com/comparison/net/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-lock"
        content: "[PDF, Word, PowerPoint 슬라이드 및 다이어그램의 변경 사항에 대한 올바른 좌표 계산](https://docs.groupdocs.com/comparison/net/get-changes-coordinates/)"

      # feature loop
      - icon: "fas fa-file-code"
        content: "[비밀번호로 보호된 파일 비교](https://docs.groupdocs.com/comparison/net/how-to-compare-password-protected-files/)"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "[스프레드시트의 차트 제목 비교 – 결과 셀 파일에서 차트 생성](https://docs.groupdocs.com/comparison/net/how-to-compare-spreadsheet-or-tables/)"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "[Cells 문서의 결과 파일에서 자동 모양 자동 크기 조정](https://docs.groupdocs.com/comparison/net/how-to-compare-spreadsheet-or-tables/)"

      # feature loop
      - icon: "fas fa-heading"
        content: "[자세한 요약 페이지에 액세스하여 소스 및 대상 문서 파일 간의 변경 사항 감지](https://docs.groupdocs.com/comparison/net/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "[가장 인기 있는 프로그래밍 및 스크립팅 언어 파일 비교](https://docs.groupdocs.com/comparison/net/get-supported-document-formats/)"

      # feature loop
      - icon: "fas fa-cube"
        content: "[여러(2개 이상) PDF, Word, Excel, 다이어그램, 이메일, 텍스트 및 OneNote 문서 비교](https://docs.groupdocs.com/comparison/net/compare-multiple-documents-with-specific-compare-settings/)"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "[지원되는 파일 형식의 머리글 및 바닥글 비교](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "[Word 문서 형식의 책갈피, 변수 및 사용자 정의 속성 비교](https://docs.groupdocs.com/comparison/net/compare-bookmarks-in-word/)"

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison은 기타 널리 사용되는 개발 환경을 위한 문서 보기 API를 제공합니다."

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for Java"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---