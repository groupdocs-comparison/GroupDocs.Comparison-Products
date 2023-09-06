---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "Java 문서 비교 API | PDF Word Excel HTML의 텍스트 및 스타일 비교"
head_description: "Word Excel PPTX OpenOffice, 웹, PDF, AutoCAD 및 기타 파일 형식을 비교하고 병합하는 Java 문서 비교 API입니다. 변경 내용을 추적하여 문서를 비교합니다."

############################# Header ############################
title: "파일을 비교하는 Java API"
description: "모든 표준 문서 및 이미지 파일 형식의 차이점에 대해 파일 내용을 효과적으로 비교하는 Java 애플리케이션을 만듭니다."
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
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
        product: "GroupDocs.Comparison"
        platform: "Java"

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
            - link: "https://purchase.groupdocs.com/pricing/comparison/java"
              text: "가격"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    example_image: "/comparison/comparison-example.png"
    content: |
      
    more_overview:
      # more_overview_loop
      - title: "GroupDocs.Comparison for Java이(가) 무엇인가요?"
        content: "GroupDocs.Comparison for Java은 Java 환경에서 문서 비교 애플리케이션을 개발하는 데 도움이 되는 가장 유연하고 사용하기 쉬운 API입니다. 차이 검사기 및 문서 병합 API를 사용하면 유사한 문서 형식 간의 텍스트 스타일뿐만 아니라 콘텐츠의 변경 및 차이점을 감지할 수 있습니다."

      # more_overview_loop
      - title: "지원되는 형식"
        content: "GroupDocs.Comparison 라이브러리는 PDF, HTML, 전자 메일 Outlook, Microsoft Office Word 문서, Excel 스프레드시트, PowerPoint 프레젠테이션, OneNote, Visio 다이어그램, 텍스트, png 등 널리 사용되는 이미지와 문서 형식 간의 콘텐츠 및 텍스트 스타일 차이 감지를 지원합니다. , gif, bmp 이미지와 기타 수백 가지 형식이 있습니다."
        
      # more_overview_loop
      - title: "비교 기능"
        content: "비교를 수행하여 단어, 단락, 표 또는 차트의 내용과 스타일의 변경 사항을 감지할 수 있으며 차이점, 해당 번호 및 유형에 대한 요약을 나열하는 비교 문서를 제공합니다. GroupDocs.Comparison for Java은(는) 원본 문서에 대한 기본 정보를 쉽게 추출하고, 파일이나 데이터 스트림을 통해 다양한 형식의 단순하고 비밀번호로 보호되고 암호화된 문서를 비교하고 저장할 수 있습니다."
        
      # more_overview_loop
      - title: "문서 및 예제"
        content: "코드 예제와 함께 다양한 플랫폼에서 비교 라이브러리를 사용하는 방법에 대한 많은 문서가 이미 있으므로 애플리케이션에서 Java API에 대한 GroupDocs.Comparison을 사용하여 작업하는 방법에 대해 열심히 생각할 필요가 없습니다."
        
      # more_overview_loop
      - title: "호환성"
        content: "GroupDocs.Comparison for Java은(는) 시스템에 외부 소프트웨어를 설치할 필요가 없습니다. 모든 버전의 Java와 호환되며 Java 런타임 환경을 실행할 수 있는 널리 사용되는 운영 체제(Windows, Linux, MacOS)를 지원합니다."
    examples:
      enable: true
      
    more_feature:
      # more_feature_loop
      - title: "Java API를 사용하여 쉽게 문서 비교"
        content: |
          GroupDocs.Comparison for Java API를 통해 지원되는 형식의 문서를 쉽게 비교하여 차이점을 찾을 수 있습니다. 다음 예에서는 Java를 사용하여 두 개의 Microsoft Word 문서를 비교하는 방법을 보여줍니다.
          
          ```java
          try (Comparer comparer = new Comparer("D:\\source.pdf")) {
              comparer.add("D:\\target.pdf");
              comparer.compare("D:\\result.pdf");
          }
          ```
      # more_feature_loop
      - title: "비교 세부 수준 지정"
        content: "GroupDocs.Comparison for Java을(를) 사용하면 세 가지 수준에서 문서를 비교할 수 있습니다. 비교 강도를 낮음(이미징 그리드의 정확도로 텍스트를 단어별로 비교 = 50), 중간(이미징 그리드의 정확도로 문자별로 텍스트 비교 = 100) 또는 높음(이미지의 정확도로 텍스트를 문자별로 비교)으로 설정할 수 있습니다. 그리드 = 150)."

      # more_feature_loop
      - title: "텍스트 스타일 비교"
        content: "문서 내용과 함께 GroupDocs.Comparison for Java API를 사용하면 텍스트 스타일도 비교할 수 있습니다.

        글꼴 이름, 크기, 색상, 스타일(굵게, 기울임꼴, 밑줄, 작은 대문자 및 하이퍼링크) 및 해당하는 경우 아래 색상을 비교하여 비교 문서 간의 차이점을 확인하고 단어와 문자를 비교할 수도 있습니다.  

        문단 비교를 위해 정렬, 들여쓰기(왼쪽 들여쓰기, 오른쪽 들여쓰기), 간격(뒤 공백, 앞 공백), 첫 줄 들여쓰기, 줄 간격도 비교할 수 있습니다.  

        마찬가지로, 해당되는 경우 페이지의 다른 섹션도 GroupDocs.Comparison for Java API를 통해 비교할 수 있습니다. 섹션에는 바닥글 거리, 페이지 여백(왼쪽, 오른쪽, 위쪽 및 아래쪽), 페이지 높이, 페이지 방향, 테두리 색상 및 선 너비가 포함됩니다."
      
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          다음은 GroupDocs.Comparison for Java의 개요입니다.
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "개요"
          content: |
            * 내용 및 스타일 비교
            * 비교 요약 가져오기
            * Word의 변경 사항 수락/거부
            * 3개의 Word 파일 병합 및 비교
            * 스트림 지원
            * 스트림을 통한 파일 유형 감지
            * 보호된 파일 비교
            * 암호화된 파일 비교
            * 비교를 이미지로 저장
            * Word의 특정 페이지 비교
            * PDF의 워터마크 비교
            * 변경사항 적용/취소
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison for Java은(는) Microsoft Office, 이미지, 다이어그램 등을 포함하여 널리 사용되는 모든 [문서 파일 형식](https://docs.groupdocs.com/comparison/java/supported-document-formats/)을 지원합니다. .
        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** [DOC](https://products.groupdocs.com/comparison/java/doc/), [DOCX](https://products.groupdocs.com/comparison/java/docx/), [DOCM](https://products.groupdocs.com/comparison/java/docm/), [DOT](https://products.groupdocs.com/comparison/java/dot/), [DOTX](https://products.groupdocs.com/comparison/java/dotx/), [DOTM](https://products.groupdocs.com/comparison/java/dotm/), [RTF](https://products.groupdocs.com/comparison/java/rtf/), [TXT](https://products.groupdocs.com/comparison/java/txt/)
                * **Excel:** [XLS](https://products.groupdocs.com/comparison/java/xls/), [XLSX](https://products.groupdocs.com/comparison/java/xlsx/), [XLSM](https://products.groupdocs.com/comparison/java/xlsm/), [XLSB](https://products.groupdocs.com/comparison/java/xlsb/), [XLTM](https://products.groupdocs.com/comparison/java/xltm/), [XLT](https://products.groupdocs.com/comparison/java/xlt/), [XLTM](https://products.groupdocs.com/comparison/java/xltm/), [XLTX](https://products.groupdocs.com/comparison/java/xltx/), [XLAM](https://products.groupdocs.com/comparison/java/xlam/), [SXC](https://products.groupdocs.com/comparison/java/sxc/), [SpreadsheetML](https://products.groupdocs.com/comparison/java/xml/)
                * **PowerPoint:** [PPT](https://products.groupdocs.com/comparison/java/ppt/), [PPTX](https://products.groupdocs.com/comparison/java/pptx/), [PPS](https://products.groupdocs.com/comparison/java/pps/), [PPSX](https://products.groupdocs.com/comparison/java/ppsx/), [PPSM](https://products.groupdocs.com/comparison/java/ppsm/), [POT](https://products.groupdocs.com/comparison/java/pot/), [POTM](https://products.groupdocs.com/comparison/java/potm/), [POTX](https://products.groupdocs.com/comparison/java/potx/), [PPTM](https://products.groupdocs.com/comparison/java/pptm/)
                * **Visio:** [VSD](https://products.groupdocs.com/comparison/java/vsd/), [VDX](https://products.groupdocs.com/comparison/java/vdx/), [VSS](https://products.groupdocs.com/comparison/java/vss/), [VSSX](https://products.groupdocs.com/comparison/java/vssx/), [VSX](https://products.groupdocs.com/comparison/java/vsx/), [VST](https://products.groupdocs.com/comparison/java/vst/), [VSTX](https://products.groupdocs.com/comparison/java/vstx/), [VTX](https://products.groupdocs.com/comparison/java/vtx/), [VSDX](https://products.groupdocs.com/comparison/java/vsdx/), [VDW](https://products.groupdocs.com/comparison/java/vdw/), [VSTM](https://products.groupdocs.com/comparison/java/vstm/), [VSSM](https://products.groupdocs.com/comparison/java/vssm/), [VSDM](https://products.groupdocs.com/comparison/java/vsdm/)
                * **Outlook:** [MSG](https://products.groupdocs.com/comparison/java/msg/), [EML](https://products.groupdocs.com/comparison/java/eml/), [EMLX](https://products.groupdocs.com/comparison/java/emlx/), [PST](https://products.groupdocs.com/comparison/java/pst/), [OST](https://products.groupdocs.com/comparison/java/ost/)
                * **OneNote:** [ONE](https://products.groupdocs.com/comparison/java/one/)

        right:
          enable: true
          table:
            # table loop
            - title: "기타 형식"
              content: |
                * **프로그래밍 언어**: [CS](https://products.groupdocs.com/comparison/java/cs/), [Java](https://products.groupdocs.com/comparison/java/java/), [CPP](https://products.groupdocs.com/comparison/java/cpp/), [JS](https://products.groupdocs.com/comparison/java/js/), [PY](https://products.groupdocs.com/comparison/java/py/), [RB](https://products.groupdocs.com/comparison/java/rb/), [PL](https://products.groupdocs.com/comparison/java/pl/), [ASM](https://products.groupdocs.com/comparison/java/asm/), [GROOVY](https://products.groupdocs.com/comparison/java/groovy/), [JSON](https://products.groupdocs.com/comparison/java/json/), [PHP](https://products.groupdocs.com/comparison/java/php/), [SQL](https://products.groupdocs.com/comparison/java/sql/), [LOG](https://products.groupdocs.com/comparison/java/log/), [DIFF](https://products.groupdocs.com/comparison/java/diff/), [LESS](https://products.groupdocs.com/comparison/java/less/), [SCALA](https://products.groupdocs.com/comparison/java/scala/)
                * **OpenDocument**: [ODT](https://products.groupdocs.com/comparison/java/odt/), [OTT](https://products.groupdocs.com/comparison/java/ott/), [ODS](https://products.groupdocs.com/comparison/java/ods/), [ODP](https://products.groupdocs.com/comparison/java/odp/), [OTP](https://products.groupdocs.com/comparison/java/otp/)
                * **Portable**: [PDF](https://products.groupdocs.com/comparison/java/pdf/), [MOBI](https://products.groupdocs.com/comparison/java/mobi/)
                * **AutoCAD**: [DXF](https://products.groupdocs.com/comparison/java/dxf/), [DWG](https://products.groupdocs.com/comparison/java/dwg/)
                * **Email**: [EML](https://products.groupdocs.com/comparison/java/eml/), [EMLX](https://products.groupdocs.com/comparison/java/emlx/), [MSG](https://products.groupdocs.com/comparison/java/msg/)
                * **Images**: [JPEG](https://products.groupdocs.com/comparison/java/jpeg/), [BMP](https://products.groupdocs.com/comparison/java/bmp/), [PNG](https://products.groupdocs.com/comparison/java/png/), [GIF](https://products.groupdocs.com/comparison/java/gif/), [DCM](https://products.groupdocs.com/comparison/java/dcm/), [DICOM](https://products.groupdocs.com/comparison/java/dicom/), [DjVu](https://products.groupdocs.com/comparison/java/djvu/)
                * **Web**: [HTM](https://products.groupdocs.com/comparison/java/htm/), [HTML](https://products.groupdocs.com/comparison/java/html/), [MHTML](https://products.groupdocs.com/comparison/java/mhtml/)
                * **Text**: [TXT](https://products.groupdocs.com/comparison/java/txt/)

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Comparison for Java은(는) 다음 운영 체제, 프레임워크 및 패키지 관리자를 지원합니다.
      
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "운영체제"
              content: |
                * Microsoft Windows Desktop
                * Microsoft Windows Server
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "지원되는 프레임워크"
              content: |
                * Java 7 (1.7) 또는 더 높게

        right:
          enable: true
          table:
            
            # table loop
            - icon: "fas fa-cogs"
              title: "개발 환경"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse
            # table loop
            - icon: "fas fa-tools"
              title: "빌드 자동화 도구"
              content: |
                * Maven

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Comparison for Java 기능"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "[콘텐츠 및 텍스트 스타일의 변경 사항을 비교하고 식별합니다.](https://docs.groupdocs.com/comparison/java/compare-documents/)"

      # feature loop
      - icon: "fas fa-eye"
        content: "[비교된 문서에 대한 요약된 비교 목록 저장](https://docs.groupdocs.com/comparison/java/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-bolt"
        content: "[Word 문서의 특정 페이지 비교](https://docs.groupdocs.com/comparison/java/accept-or-reject-detected-changes/)"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "[“변경 사항 추적” 지원과 비교할 최대 3개의 Microsoft Word 파일 병합](https://docs.groupdocs.com/comparison/java/compare-multiple-documents-with-specific-compare-settings/)"

      # feature loop
      - icon: "fas fa-code"
        content: "[비교 중에 어떤 문서에서 어떤 변경 사항이 발생하는지 쉽게 확인](https://docs.groupdocs.com/comparison/java/get-list-of-changes/)"

      # feature loop
      - icon: "fas fa-cloud"
        content: "[소스 문서 읽기 및 스트림을 통한 결과 문서 전송 지원](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "[스트림에서 가져오는 동안 파일 형식 유형 감지](https://docs.groupdocs.com/comparison/java/get-file-info/)"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "[비밀번호로 보호된 문서 비교](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/)"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "[비교 결과를 이미지로 저장](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-border-all"
        content: "[다양한 파일 형식을 이미지로 비교](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-wrench"
        content: "[PDF 문서의 워터마크 비교](https://docs.groupdocs.com/comparison/java/how-to-spot-photos-differences-in-java-or-kotlin/)"

      # feature loop
      - icon: "fas fa-columns"
        content: "[파일 또는 스트림의 문서를 비교하고 스트림 또는 파일을 통해 결과 문서를 보냅니다.](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-file-word"
        content: "[Word, PDF 또는 Excel 파일 비교 후 변경 사항 수락 또는 취소](https://docs.groupdocs.com/comparison/java/accept-or-reject-detected-changes/)"

      # feature loop
      - icon: "fas fa-envelope"
        content: "[파일 또는 스트림을 통해 암호화된 문서 비교](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-print"
        content: "[비교 작업을 위한 측정 라이선스 옵션](https://docs.groupdocs.com/comparison/java/evaluation-limitations-and-licensing-of-groupdocs-comparison/)"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "[PDF, Word, Excel, PowerPoint 및 메모 문서를 비교할 때 표시된 변경 사항에 대한 텍스트 강조 표시](https://docs.groupdocs.com/comparison/java/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-lock"
        content: "[PDF, PowerPoint 슬라이드 및 다이어그램의 변경 사항에 대한 올바른 좌표 계산](https://docs.groupdocs.com/comparison/java/get-changes-coordinates/)"

      # feature loop
      - icon: "fas fa-file-code"
        content: "[여러(2개 이상) PDF, Excel, OneNote, 다이어그램, 이메일 및 텍스트 문서 비교](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/)"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "[지원되는 파일 형식의 머리글 및 바닥글 비교](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "[문서 비교 및 ​​다양한 형식의 문서 페이지를 이미지로 저장](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"


############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison은 기타 널리 사용되는 개발 환경을 위한 문서 보기 API를 제공합니다."

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
          product: "GroupDocs.Comparison"
          platform: ".NET"
          link: "/comparison/net/"

############################# Back to top ###############################
back_to_top:
  enable: true
---