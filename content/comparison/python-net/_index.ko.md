
---
############################# Static ############################
layout: "landing"
date: 2024-11-18T09:49:37
draft: false

lang: ko
product: "Comparison"
product_tag: "comparison"
platform: "Python via .NET"
platform_tag: "python-net"

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
head_title: "Python 문서 비교 도구 | 문서분석"
head_description: "철저한 문서 분석을 위한 Python 문서 비교 도구의 강력한 기능을 알아보세요. 수정 사항을 포괄적으로 추적하기 위해 Python과 쉽게 통합됩니다."

############################# Header ############################
title: "Python 으로 문서 비교: 차이점 강조 표시"
description: "GroupDocs.Comparison API를 활용하여 사용자 정의 가능한 비교 기능이 포함된 Python 기본 애플리케이션을 생성하세요. 문서 형식 전반에 걸쳐 파일, 콘텐츠, 스타일 변형을 검사합니다."
words:
  for: "...에 대한"

actions:
  main: "지금 무료 PyPi 다운로드 받기"
  main_link: "https://pypi.org/project/groupdocs-comparison-net/"
  alt: "라이선싱"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/python-net/"
  title: "시작할 준비가 되셨나요?"
  description: "GroupDocs.Comparison 기능을 무료로 체험하거나 라이선스를 요청하세요"

release:
  title: "버전 {4.13} 출시"
  notes: "새 소식 보기"
  downloads: "다운로드"

code:
  title: "Python을 사용하여 BMP 이미지 비교"
  more: "더 많은 예시"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET/"
  install: "pip install groupdocs-comparison-net"
  content: |
    ```python {style=abap}
    def run():

        # 원본 문서 지정
        with groupdocs.comparison.Comparer("in.bmp") as comparer:

            # 하나 이상의 대상 문서 추가
            comparer.add("target.bmp")

            # 비교 옵션 지정
            options = new groupdocs.comparison.CompareOptions()
            options.setGenerateSummaryPage(false)

            # 이미 번역됨
            comparer.compare("result.bmp", options)
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison 한 눈에"
  description: "Python 애플리케이션 내에서 PDF, Microsoft Office 파일, HTML, 이메일 또는 이미지와 같이 널리 사용되는 문서 유형을 비교하기 위해 설계된 API입니다."
  features:
    # feature loop
    - title: "종합적인 출력 보고서"
      content: "GroupDocs.Comparison은 문서 콘텐츠(문자, 단어, 단락, 표, 차트)의 변경 사항과 문서 스타일 변경 사항을 감지합니다. 사용자는 변경 내용과 횟수를 강조하는 자세한 보고서를 받습니다."

    # feature loop
    - title: "광범위한 파일 및 문서 형식"
      content: "GroupDocs.Comparison API를 사용하면 PDF, HTML, 이메일, Microsoft Office Word, Excel 통합 문서, PowerPoint 파일, OneNote 노트, Visio 다이어그램, 텍스트 문서, JPEG, PNG, GIF, BMP 이미지, 다른 많은 것 중에서."

    # feature loop
    - title: "철저한 문서 및 코드 샘플"
      content: "다양한 플랫폼에서 비교 라이브러리에 대한 심층적인 문서와 샘플 코드를 쉽게 사용할 수 있으므로 GroupDocs.Comparison API를 Python 응용 프로그램에 쉽게 통합할 수 있습니다."

    # feature loop
    - title: "변경 사항을 선택하고 하나의 문서로 결합"
      content: "다양한 버전의 문서를 보유하고 있는 경우 GroupDocs.Comparison 라이브러리를 사용하여 변경 사항을 하나의 새 파일로 선택적으로 컴파일할 수 있습니다."

############################# Platforms ############################
platforms:
  enable: true
  title: "플랫폼 독립성"
  description: "GroupDocs.Comparison for Python via .NET은(는) 다음 운영 체제, 프레임워크 및 패키지 관리자와 호환됩니다."
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
    GroupDocs.Comparison for Python via .NET은(는) 다음 [파일 형식](https://docs.groupdocs.com/comparison/net/supported-document-formats/)으로 작동할 수 있습니다.
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
  title: "GroupDocs.Comparison for Python via .NET의 기능"
  description: "PDF, Office 문서, 이미지 및 기타 다양한 형식을 원활하게 비교할 수 있습니다."

  items:
    # feature loop
    - icon: "compare"
      title: "직관적인 문서 비교"
      content: "두 문서 간의 차이점을 조사하고 강조 표시합니다."

    # feature loop
    - icon: "note-stack"
      title: "여러 문서 비교"
      content: "여러 문서의 차이점을 동시에 검사하세요."

    # feature loop
    - icon: "stacks"
      title: "광범위한 형식 지원"
      content: "다양한 카테고리에 걸쳐 일반적으로 사용되는 50개 이상의 문서 형식과 호환됩니다."

    # feature loop
    - icon: "rule"
      title: "변경 사항 수락 또는 거부"
      content: "변경 사항을 명확하게 시각화하고 편집 승인 또는 거부 옵션을 제공합니다."

    # feature loop
    - icon: "preview"
      title: "시각적 미리보기 생성"
      content: "이미지 형식으로 비교 결과 미리보기를 생성합니다."

    # feature loop
    - icon: "two-pager"
      title: "텍스트 기반 콘텐츠 비교"
      content: "행별, 단락, 단어 또는 문자 비교를 수행하여 변경 사항을 강조 표시합니다."

    # feature loop
    - icon: "format_color_text"
      title: "서식 변경 감지"
      content: "문서 스타일 및 형식의 변경 사항을 식별합니다."

    # feature loop
    - icon: "folder-managed"
      title: "맞춤형 메타데이터 처리"
      content: "소스 또는 대상 파일의 메타데이터를 유지하거나 사용자가 새 메타데이터를 정의하도록 허용합니다."

    # feature loop
    - icon: "lock"
      title: "비밀번호로 보호된 파일 처리"
      content: "암호화된 문서로 작업하거나 비밀번호로 보호되는 보안 문서를 만드세요."

    # feature loop
    - icon: "select"
      title: "집중 페이지 비교"
      content: "문서의 특정 섹션이나 개별 페이지를 선택하고 비교하세요."

    # feature loop
    - icon: "speaker-notes"
      title: "댓글 가시성 관리"
      content: "원본 문서를 검토할 때 주석을 표시할지 숨길지 결정합니다."

############################# Code samples ############################
code_samples:
  enable: true
  title: "코드 샘플"
  description: "GroupDocs.Comparison for Python via .NET 기능 활용에 대한 일반적인 시나리오를 알아보세요."
  items:
    # code sample loop
    - title: "비밀번호 보호 기능이 있는 문서 비교"
      content: |
        [비밀번호로 보호된](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/) 문서를 비교하려면 문서를 로드할 때 비밀번호를 지정해야 합니다.
        {{< landing/code title="암호로 보호된 문서를 비교하는 방법">}}
        ```python {style=abap}
        def run():

            # 소스 문서를 로드하고 암호를 지정합니다.
            with groupdocs.comparison.Comparer("source.docx", new LoadOptions("1234")) as comparer:

                # 대상 문서를 로드하고 암호를 지정합니다.
                comparer.add("target.docx", new LoadOptions("5678"));

                # 비교 결과를 지정된 파일에 저장
                comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "여러 PDF 개의 문서를 비교하는 중입니다."
      content: |
        GroupDocs.Comparison 를 사용하면 [두 개 이상의 문서 비교](https://docs.groupdocs.com/comparison/python-net/compare-multiple-documents/) 할 수 있습니다.작업은 두 파일을 비교할 때와 거의 같습니다.`comparer` 클래스에 대상 파일을 더 추가하기만 하면 됩니다.
        {{< landing/code title="세 개 이상의 문서를 비교하는 방법">}}
        ```python {style=abap}
        def run():

            # 소스 문서 로드
            with groupdocs.comparison.Comparer(source.pdf") as comparer:

                # 비교할 두 번째 파일을 지정합니다.
                comparer.add("target2.pdf");

                # 비교할 세 번째 파일을 지정합니다.
                comparer.add("target3.pdf");

                # 비교 결과를 지정된 파일에 저장
                comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---