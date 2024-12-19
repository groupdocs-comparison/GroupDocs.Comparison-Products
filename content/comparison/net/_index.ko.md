
---
############################# Static ############################
layout: "landing"
date: 2024-12-19T07:50:01
draft: false

lang: ko
product: "Comparison"
product_tag: "comparison"
platform: "Net"
platform_tag: "net"

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
    # supported_platforms loop
    - title: "Python"
      tag: "python-net"

############################# Head ############################
head_title: "C# .NET 문서 비교 소프트웨어 | 차이점 검사기"
head_description: "C# .NET 문서 스타일과 내용을 비교하는 소프트웨어입니다.지원되는 여러 형식의 문서를 비교하여 파일 간의 변경 사항을 식별합니다."

############################# Header ############################
title: "C# .NET 솔루션에서 문서를 쉽게 비교하세요"
description: "다양한 문서 형식에서 콘텐츠 및 스타일별로 파일을 비교할 수 있는 유연한 문서 비교 API로 C# 개의 애플리케이션을 빌드하세요."
words:
  for: "...에 대한"

actions:
  main: "무료 NuGet 다운로드"
  main_link: "https://www.nuget.org/packages/GroupDocs.Comparison"
  alt: "라이선싱"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/net/"
  title: "시작할 준비가 되셨나요?"
  description: "GroupDocs.Comparison 기능을 무료로 체험하거나 라이선스를 요청하세요"

release:
  title: "버전 {4.13} 출시"
  notes: "새 소식 보기"
  downloads: "다운로드"

code:
  title: "C# 에서 DOCX 개의 파일을 비교하십시오."
  more: "더 많은 예시"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET"
  install: "dotnet add package GroupDocs.Comparison"
  content: |
    ```csharp {style=abap}   
    // 원본 문서 지정
    using (Comparer comparer = new Comparer("source.docx"))
    {
        // 하나 이상의 대상 문서 추가
        comparer.Add("target.docx");

        // 비교 옵션 지정
        CompareOptions options = new CompareOptions() 
        {ShowRevisions = false};

        // 이미 번역됨
        comparer.Compare("result.docx", options);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison 한 눈에"
  description: ".NET 애플리케이션의 문서 간 차이를 비교하는 API"
  features:
    # feature loop
    - title: "C# 에서의 파일 비교"
      content: "단락, 단어 및 문자 수준의 변경 사항에 대한 소스 파일과 대상 파일 간의 차이를 감지합니다.굵게, 기울임꼴, 밑줄, 취소선, 글꼴 유형 등과 같은 스타일 및 서식 변경 사항을 식별할 수 있습니다."

    # feature loop
    - title: "가장 많이 사용되는 파일 및 문서 형식이 지원됩니다."
      content: "GroupDocs.Comparison API를 사용하면 PDF, HTML, 이메일, Microsoft Office 문서 (Word, Excel, PowerPoint, OneNote, Visio), 다양한 이미지 유형 (JPEG, PNG, GIF, BMP), 텍스트 파일 등 다양한 형식에서 문서를 효율적으로 비교할 수 있습니다."

    # feature loop
    - title: "변경 사항을 쉽게 적용하거나 거부할 수 있습니다."
      content: "GroupDocs.Comparison API를 사용하여 비교 문서에서 식별한 각 차이를 선택적으로 적용하거나 거부할 수 있으므로 최종 출력 문서로 내보내기 전에 사용자 지정할 수 있습니다."

    # feature loop
    - title: "비교 요약 보고서"
      content: "비교 문서에서 발견된 모든 변경 사항을 자세히 설명하는 차이점에 대한 요약 보고서를 생성하고 참조용으로 저장합니다."

############################# Platforms ############################
platforms:
  enable: true
  title: "플랫폼 독립성"
  description: "GroupDocs.Comparison for .NET 는 다음 운영 체제, 프레임워크 및 패키지 관리자를 지원합니다."
  items:
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
    - title: "ReSharper"
      image: "resharper"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NuGet"
      image: "nuget"

############################# File formats ############################
formats:
  enable: true
  title: "지원되는 파일 형식"
  description: |
    GroupDocs.Comparison for .NET 는 다음과 같은 [파일 형식](https://docs.groupdocs.com/comparison/net/supported-document-formats/) 의 작업을 지원합니다.
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
  title: "GroupDocs.Comparison 개의 특징"
  description: "PDF 과 Office 문서, 이미지 및 기타 형식을 쉽게 비교할 수 있습니다."

  items:
    # feature loop
    - icon: "compare"
      title: "사용하기 쉬운 문서 비교"
      content: "두 문서 간의 차이점을 분석하고 식별합니다."

    # feature loop
    - icon: "note-stack"
      title: "여러 문서 비교"
      content: "여러 문서의 차이점을 동시에 분석하고 식별합니다."

    # feature loop
    - icon: "stacks"
      title: "지원되는 형식"
      content: "다양한 범주에서 널리 사용되는 50개 이상의 문서 형식과 호환되므로 폭넓은 적용이 가능합니다."

    # feature loop
    - icon: "rule"
      title: "변경 적용 또는 거부"
      content: "감지된 변경 사항을 시각적으로 선명하게 표시하고 이러한 수정을 수락하거나 거부할 수 있는 옵션이 함께 제공됩니다."

    # feature loop
    - icon: "preview"
      title: "미리 보기 생성"
      content: "비교 결과를 이미지 미리보기로 저장하여 쉽게 참조하고 공유할 수 있습니다."

    # feature loop
    - icon: "two-pager"
      title: "콘텐츠 비교"
      content: "줄별, 단락, 단어, 문자 등 다양한 수준에서 차이점을 강조하여 텍스트를 철저하게 비교하여 명확성을 높입니다."

    # feature loop
    - icon: "format_color_text"
      title: "스타일 및 서식 비교"
      content: "문서 서식 및 스타일의 변경을 감지하고 강조 표시하여 종합적인 검토를 보장합니다."

    # feature loop
    - icon: "folder-managed"
      title: "유연한 메타데이터 설정"
      content: "소스 또는 대상 파일의 메타데이터를 보존하거나 사용자 기본 설정에 따라 사용자 지정할 수 있습니다."

    # feature loop
    - icon: "lock"
      title: "비밀번호 보호"
      content: "암호로 보호된 문서를 분석하고 출력 문서를 암호 암호화로 보호하여 보안을 강화합니다."

    # feature loop
    - icon: "select"
      title: "선택적 페이지 비교"
      content: "대상 분석을 위해 문서의 특정 섹션 또는 페이지를 로드하고 비교합니다."

    # feature loop
    - icon: "speaker-notes"
      title: "댓글 표시"
      content: "원본 문서를 로드할 때 설명을 표시하거나 숨기도록 선택하여 비교 프로세스를 보다 효과적으로 제어할 수 있습니다."

############################# Code samples ############################
code_samples:
  enable: true
  title: "코드 샘플"
  description: "일반적인 GroupDocs.Comparison for .NET 작업의 일부 사용 사례"
  items:
    # code sample loop
    - title: "암호로 보호된 문서 비교"
      content: |
        [암호로 보호됨](https://docs.groupdocs.com/comparison/net/load-password-protected-documents/) 인 문서를 비교하려면 해당 문서를 지정한 다음 문서를 로드해야 합니다.
        {{< landing/code title="암호로 보호된 문서를 비교하는 방법">}}
        ```csharp {style=abap}
        // 소스 문서를 로드하고 암호를 지정합니다.
        using(Comparer comparer = new Comparer("source.docx", new LoadOptions() {Password = "1234"}))  
        {
            // 대상 문서를 로드하고 암호를 지정합니다.
            comparer.Add("target.docx", new LoadOptions() {Password = "5678"});

            // 비교 결과를 지정된 파일에 저장
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "여러 PDF 개의 문서를 비교하는 중입니다."
      content: |
        GroupDocs.Comparison 를 사용하면 [두 개 이상의 문서 비교](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/) 할 수 있습니다.작업은 두 파일을 비교할 때와 거의 같습니다.`comparer` 클래스에 대상 파일을 더 추가하기만 하면 됩니다.
        {{< landing/code title="세 개 이상의 문서를 비교하는 방법">}}
        ```csharp {style=abap}   
        // 소스 문서 로드
        using(Comparer comparer = new Comparer("source.docx") 
        {
            // 비교할 두 번째 파일을 지정합니다.
            comparer.Add("target2.docx");
            
            // 비교할 세 번째 파일을 지정합니다.
            comparer.Add("target3.docx");
            
            // 비교 결과를 지정된 파일에 저장
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---
