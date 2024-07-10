
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
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
head_title: "{{런타임}} 문서 비교 API | 차이점 검사기"
head_description: "{{런타임}} 문서 비교 API는 문서 비교를 위한 효율적인 도구를 제공합니다. 즉각적인 변경 추적을 위해 Python과 원활하게 통합됩니다."

############################# Header ############################
title: "{{런타임}}으로 문서 비교: 차이점 강조 표시"
description: "GroupDocs.Comparison API를 사용하여 고도로 구성 가능한 비교 기능을 갖춘 기본 Python 애플리케이션을 개발하세요. 유사한 문서 형식 간의 파일, 내용, 텍스트 스타일을 비교합니다."
words:
  for: "...에 대한"

actions:
  main: "무료 PyPi 다운로드"
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
  title: "Python의 BMP 이미지 비교"
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
  description: "{{런타임}} 애플리케이션 내에서 PDF, Microsoft Office, HTML, 이메일, 이미지 등 널리 사용되는 문서 유형을 비교하는 API입니다."
  features:
    # feature loop
    - title: "상세한 출력 보고서"
      content: "GroupDocs.Comparison은 문서 내용(문자, 단어, 단락, 표, 차트)의 변경 사항과 문서 스타일의 변경 사항을 식별합니다. 이는 사용자에게 차이점의 수와 유형을 포함하여 차이점에 대한 자세한 정보가 포함된 보고서를 제공합니다."

    # feature loop
    - title: "널리 사용되는 파일 및 문서 형식 지원"
      content: "GroupDocs.Comparison API를 사용하면 PDF, HTML, 이메일, Microsoft Office Word, Excel 스프레드시트, PowerPoint 프레젠테이션, OneNote, Visio 다이어그램, 텍스트 파일, JPEG, PNG, GIF, BMP 이미지, 그리고 다른 많은 형식."

    # feature loop
    - title: "포괄적인 문서 및 예제"
      content: "다양한 플랫폼에서 비교 라이브러리를 사용하기 위한 광범위한 문서와 코드 예제가 제공되므로 GroupDocs.Comparison API를 Python 애플리케이션에 쉽게 통합할 수 있습니다."

    # feature loop
    - title: "변경 사항을 선택하고 하나의 파일로 병합"
      content: "문서 버전이 다른 경우 특정 변경 사항을 선택하고 GroupDocs.Comparison 라이브러리를 사용하여 새 문서를 컴파일할 수 있습니다."

############################# Platforms ############################
platforms:
  enable: true
  title: "플랫폼 독립성"
  description: "GroupDocs.Comparison for Python via .NET은(는) 다음 운영 체제, 프레임워크 및 패키지 관리자를 지원합니다."
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
    GroupDocs.Comparison for Python via .NET은(는) 다음 [파일 형식](https://docs.groupdocs.com/comparison/net/supported-document-formats/)을 사용한 작업을 지원합니다.
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
  title: "GroupDocs.Comparison for Python via .NET 기능"
  description: "PDF와 Office 문서, 이미지, 기타 형식을 쉽게 비교할 수 있습니다."

  items:
    # feature loop
    - icon: "compare"
      title: "사용자 친화적인 문서 비교"
      content: "두 문서 간의 차이점을 분석하고 식별합니다."

    # feature loop
    - icon: "note-stack"
      title: "여러 문서 비교"
      content: "여러 문서 내의 차이점을 동시에 분석하고 식별합니다."

    # feature loop
    - icon: "stacks"
      title: "지원되는 형식"
      content: "다양한 카테고리에서 50개 이상의 널리 사용되는 문서 형식을 지원합니다."

    # feature loop
    - icon: "rule"
      title: "변경 사항 수락 또는 거부"
      content: "수정 사항을 승인하거나 거부할 수 있는 옵션을 통해 식별된 변경 사항을 시각적으로 명확하게 표현합니다."

    # feature loop
    - icon: "preview"
      title: "미리보기 생성"
      content: "비교 결과를 이미지로 저장합니다."

    # feature loop
    - icon: "two-pager"
      title: "콘텐츠 비교"
      content: "텍스트 내용을 한 줄씩, 단락별로, 단어별로, 문자별로 비교합니다. 변경 사항을 강조 표시합니다."

    # feature loop
    - icon: "format_color_text"
      title: "스타일 비교"
      content: "서식 및 스타일의 변경 사항을 감지합니다."

    # feature loop
    - icon: "folder-managed"
      title: "메타데이터 설정"
      content: "소스 또는 대상 파일의 메타데이터를 유지하거나 사용자가 지정할 수 있도록 허용합니다."

    # feature loop
    - icon: "lock"
      title: "비밀번호 보안"
      content: "암호화된 문서를 분석하거나 결과 문서를 비밀번호로 보호하세요."

    # feature loop
    - icon: "select"
      title: "특정 페이지 비교"
      content: "문서의 특정 섹션이나 페이지를 로드하고 비교합니다."

    # feature loop
    - icon: "speaker-notes"
      title: "댓글 표시"
      content: "소스 문서를 로드할 때 주석을 숨기거나 표시하도록 선택합니다."

############################# Code samples ############################
code_samples:
  enable: true
  title: "코드 샘플"
  description: "GroupDocs.Comparison for Python via .NET 작업의 일반적인 사용 사례 살펴보기"
  items:
    # code sample loop
    - title: "비밀번호로 보호된 문서 비교"
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