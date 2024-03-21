
---
############################# Static ############################
layout: "landing"
date: 2024-03-21T15:26:29
draft: false

lang: ko
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

############################# Drop-down ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"
    # supported_platforms loop
    - title: "Java"
      tag: "java"
    # supported_platforms loop
    - title: "Node.js"
      tag: "nodejs-java"

############################# Head ############################
head_title: "Node.js 문서 비교 API | 차이점 검사기"
head_description: "Node.js 문서 비교 API는 문서 비교를 위한 효율적인 도구를 제공합니다.실시간 변경 사항 추적을 위해 Node.js 와 원활하게 통합됩니다."

############################# Header ############################
title: "Node.js 와 문서 비교: 차이점 강조"
description: "GroupDocs.Comparison API를 사용하여 고도로 구성 가능한 비교 기능을 갖춘 네이티브 Java 스크립트 애플리케이션을 개발할 수 있습니다.비슷한 문서 형식 간의 파일, 콘텐츠 및 텍스트 스타일을 비교하세요."
words:
  for: "...에 대한"

actions:
  main: "무료 NPM 다운로드"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.comparison"
  alt: "라이선싱"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/java/"
  title: "시작할 준비가 되셨나요?"
  description: "GroupDocs.Comparison 기능을 무료로 체험하거나 라이선스를 요청하세요"

release:
  title: "버전 {4.13} 출시"
  notes: "새 소식 보기"
  downloads: "다운로드"

code:
  title: "Java 스크립트의 BMP 개 이미지 비교"
  more: "더 많은 예시"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.comparison"
  content: |
    ```javascript {style=abap}

    // 원본 문서 지정
    let comparer = new Comparer("source.bmp");

    // 하나 이상의 대상 문서 추가
    comparer.add("target.bmp");

    // 비교 옵션 지정
    comparer.compare("result.bmp"); 
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison 한 눈에"
  description: "Node.js 애플리케이션 내에서 PDF, Microsoft Office, HTML, 이메일 또는 이미지와 같은 다양한 유형의 문서를 비교하기 위한 API"
  features:
    # feature loop
    - title: "상세 출력 보고서"
      content: "GroupDocs.Comparison 는 문서 내용의 변화 (문자, 단어, 단락, 표, 차트) 와 문서 스타일의 변화를 식별합니다.고객에게 차이점, 번호 및 유형에 대한 풍부한 정보가 포함된 결과 보고서를 제공합니다."

    # feature loop
    - title: "가장 많이 사용되는 파일 및 문서 형식이 지원됩니다."
      content: "GroupDocs.Comparison API를 사용하면 PDF, HTML, 이메일, Microsoft Office Word 문서, Excel 스프레드시트, PowerPoint 프레젠테이션, OneNote, Visio 다이어그램, 텍스트, JPEG, PNG, GIF 및 BMP 이미지 등 지원되는 모든 형식의 문서와 기타 여러 형식을 효율적으로 비교할 수 있습니다."

    # feature loop
    - title: "설명서 및 예제"
      content: "코드 예제와 함께 여러 플랫폼에서 Comparsion 라이브러리를 사용하는 방법에 대한 많은 문서가 이미 있으므로 Node.js 애플리케이션에서 GroupDocs.Comparison API를 사용하는 방법에 대해 열심히 생각할 필요가 없습니다."

    # feature loop
    - title: "변경 내용을 선택하여 하나의 파일에 병합"
      content: "한 문서의 버전이 다른 경우 원하는 변경 사항만 선택하고 GroupDocs.Comparison 라이브러리를 사용하여 새 문서를 컴파일할 수 있습니다."

############################# Platforms ############################
platforms:
  enable: true
  title: "플랫폼 독립성"
  description: "GroupDocs.Comparison for Node.js via Java 는 다음 운영 체제, 프레임워크 및 패키지 관리자를 지원합니다."
  items:
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "macOS"
      image: "finder"      
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NPM"
      image: "npm"  
    # platform loop
    - title: "NuGet"
      image: "nuget"      
    # platform loop
    - title: "Amazon"
      image: "amazon"
    # platform loop
    - title: "Docker"
      image: "docker"
    # platform loop
    - title: "Azure"
      image: "azure"
    # platform loop
    - title: "VS Code"
      image: "vs_code"
    # platform loop
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"

############################# File formats ############################
formats:
  enable: true
  title: "지원되는 파일 형식"
  description: |
    GroupDocs.Comparison for Node.js via Java 는 다음과 같은 [파일 형식](https://docs.groupdocs.com/comparison/nodejs-java/supported-document-formats/) 의 작업을 지원합니다.
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office 및 OpenDocument 형식
        * **Word:** DOCX, DOC, DOCM,DOT, DOTM, DOTX, RTX, RTF, TXT
        * **Excel:** XLSX, XLS, XLT, XLTM, XLSB, XLSM
        * **PowerPoint:** PPTX, PPT, POT, POTX, PPS, PPSX
        * **Outlook:** EML, EMLX, MSG
        * **OneNote:** ONE
        * **OpenDocument:** ODT, ODP, OTP, ODS, OTT
        * **고정 페이지 레이아웃:** PDF        
    # group loop
    - color: "blue"
      content: |
        ### 이미지, 그래픽 및 다이어그램
        * **래스터 이미지:** BMP, GIF, JPG, JPEG, PNG
        * **의료 영상:** DICOM
        * **Microsoft Visio:** VSDX, VSD, VSS, VST, VDX
        * **AutoCAD Drawing:** DWG, DXF
      # group loop
    - color: "red"
      content: |
        ### 기타
        * **텍스트:** TXT
        * **프로그래밍 언어:** CS, Java, CPP, JS, PY, RB, PL, ASM, GROOVY, JSON, PHP, SQL, LOG, DIFF, LESS, SCALA
        * **웹:** HTM, HTML, MHT, MHTML
        * **전자책:** MOBI, DjVu
        * **구분자로 구분된 값:** CSV

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Comparison for Node.js via Java 개의 특징"
  description: "PDF 과 Office 문서, 이미지 및 기타 형식을 쉽게 비교할 수 있습니다."

  items:
    # feature loop
    - icon: "compare"
      title: "사용하기 쉬운 문서 비교"
      content: "두 문서 간의 차이점을 분석하고 식별합니다."

    # feature loop
    - icon: "note-stack"
      title: "여러 문서 비교"
      content: "여러 문서 내의 차이점을 동시에 분석하고 식별합니다."

    # feature loop
    - icon: "stacks"
      title: "지원되는 형식"
      content: "다양한 범주에서 널리 사용되는 50개 이상의 문서 형식을 지원합니다."

    # feature loop
    - icon: "rule"
      title: "변경 적용 또는 거부"
      content: "식별된 변경 사항을 시각적으로 명확하게 표현하여 수정을 수락하거나 거부할 수 있는 옵션을 제공합니다."

    # feature loop
    - icon: "preview"
      title: "미리 보기 생성"
      content: "비교 결과를 이미지로 저장합니다."

    # feature loop
    - icon: "two-pager"
      title: "콘텐츠 비교"
      content: "텍스트 내용을 줄별, 단락별, 단어별, 문자별로 비교합니다.변경 사항을 강조하세요."

    # feature loop
    - icon: "format_color_text"
      title: "스타일 비교"
      content: "서식 및 스타일의 변화를 감지합니다."

    # feature loop
    - icon: "folder-managed"
      title: "메타데이터 설정"
      content: "소스 또는 대상 파일의 메타데이터를 보관하거나 사용자가 지정할 수 있도록 허용합니다."

    # feature loop
    - icon: "lock"
      title: "비밀번호 보호"
      content: "암호화된 문서를 분석하거나 결과 문서를 암호로 보호합니다."

    # feature loop
    - icon: "select"
      title: "특정 페이지 비교"
      content: "문서의 특정 섹션 또는 페이지만 로드합니다."

    # feature loop
    - icon: "speaker-notes"
      title: "댓글 표시"
      content: "소스 문서를 로드할 때 주석을 숨길지 또는 표시할지를 선택할 수 있습니다."

############################# Code samples ############################
code_samples:
  enable: true
  title: "코드 샘플"
  description: "일반적인 GroupDocs.Comparison for Node.js via Java 작업의 일부 사용 사례"
  items:
    # code sample loop
    - title: "암호로 보호된 문서 비교"
      content: |
        [암호로 보호됨](https://docs.groupdocs.com/comparison/nodejs-java/load-password-protected-documents/) 인 문서를 비교하려면 해당 문서를 지정한 다음 문서를 로드해야 합니다.
        {{< landing/code title="암호로 보호된 문서를 비교하는 방법">}}
        ```javascript {style=abap}

        import { Comparer, LoadOptions } from '@groupdocs/groupdocs.comparison'

        // 소스 문서를 로드하고 암호를 지정합니다.
        const comparer = new Comparer("source.docx", new LoadOptions("1234"));

        // 대상 문서를 로드하고 암호를 지정합니다.
        comparer.add("target.docx", new LoadOptions("5678"));

        // 비교 결과를 지정된 파일에 저장
        comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "여러 PDF 개의 문서를 비교하는 중입니다."
      content: |
        GroupDocs.Comparison 를 사용하면 [두 개 이상의 문서 비교](https://docs.groupdocs.com/comparison/nodejs-java/compare-multiple-documents/) 할 수 있습니다.작업은 두 파일을 비교할 때와 거의 같습니다.`comparer` 클래스에 대상 파일을 더 추가하기만 하면 됩니다.
        {{< landing/code title="세 개 이상의 문서를 비교하는 방법">}}
        ```javascript {style=abap}
        import { Comparer } from '@groupdocs/groupdocs.comparison'

        // 소스 문서 로드
        const comparer = new Comparer(source.pdf");

        // 비교할 두 번째 파일을 지정합니다.
        comparer.add("target2.pdf");

        // 비교할 세 번째 파일을 지정합니다.
        comparer.add("target3.pdf");

        // 비교 결과를 지정된 파일에 저장
        comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---