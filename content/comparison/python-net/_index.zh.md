
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: zh
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
head_title: "Python 文档比较 API |差异检查器"
head_description: "Python 文档比较 API 提供了用于比较文档的有效工具。与 Python 无缝集成以进行即时更改跟踪"

############################# Header ############################
title: "将文档与 Python 进行比较：突出显示任何差异"
description: "使用 GroupDocs.Comparison API 开发具有高度可配置比较功能的本机 Python 应用程序。比较类似文档格式之间的文件、其内容和文本样式。"
words:
  for: "为了"

actions:
  main: "免费下载PyPi"
  main_link: "https://pypi.org/project/groupdocs-comparison-net/"
  alt: "许可"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/python-net/"
  title: "准备好开始了吗？"
  description: "免费试用 GroupDocs.Comparison 项功能或申请许可证"

release:
  title: "版本 {0} 已发布"
  notes: "查看新增内容"
  downloads: "下载"

code:
  title: "比较 Python 中的 BMP 图像"
  more: "更多例子"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET/"
  install: "pip install groupdocs-comparison-net"
  content: |
    ```python {style=abap}
    def run():

        # 指定源文档
        with groupdocs.comparison.Comparer("in.bmp") as comparer:

            # 添加一个或多个目标文档
            comparer.add("target.bmp")

            # 指定比较选项
            options = new groupdocs.comparison.CompareOptions()
            options.setGenerateSummaryPage(false)

            # 比较并保存结果
            comparer.compare("result.bmp", options)
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison 一览"
  description: "用于比较流行文档类型（例如 PDF、Microsoft Office、HTML、电子邮件或 Python 应用程序中的图像）的 API。"
  features:
    # feature loop
    - title: "详细的输出报告"
      content: "GroupDocs.Comparison 识别文档内容（字符、单词、段落、表格、图表）的更改以及文档样式的更改。它为用户提供了一份报告，其中包含有关差异的详细信息，包括差异的数量和类型。"

    # feature loop
    - title: "支持流行的文件和文档格式"
      content: "借助 GroupDocs.Comparison API，您可以高效地比较 PDF、HTML、电子邮件、Microsoft Office Word、Excel 电子表格、PowerPoint 演示文稿、OneNote、Visio 图表、文本文件、JPEG、PNG、GIF、BMP 图像等格式的文档，以及许多其他格式。"

    # feature loop
    - title: "全面的文档和示例"
      content: "提供了在不同平台上使用比较库的大量文档和代码示例，使您可以轻松地将 GroupDocs.Comparison API 集成到您的 Python 应用程序中。"

    # feature loop
    - title: "选择更改并将更改合并到一个文件中"
      content: "如果您有不同版本的文档，您可以选择特定更改并使用 GroupDocs.Comparison 库编译新文档。"

############################# Platforms ############################
platforms:
  enable: true
  title: "平台独立性"
  description: "GroupDocs.Comparison for Python via .NET 支持以下操作系统、框架和包管理器"
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
  title: "支持的文件格式"
  description: |
    GroupDocs.Comparison for Python via .NET 支持以下[文件格式](https://docs.groupdocs.com/comparison/net/supported-document-formats/) 的操作。
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office 和 OpenDocument 格式
        * **Word:** DOCX, DOC, DOCM,DOT, DOTM, DOTX, RTX, RTF, TXT
        * **Excel:** XLSX, XLS, XLT, XLTM, XLSB, XLSM
        * **PowerPoint:** PPTX, PPT, POT, POTX, PPS, PPSX
        * **Outlook:** EML, EMLX, MSG
        * **OneNote:** ONE
        * **OpenDocument:** ODT, ODP, OTP, ODS, OTT
        * **固定页面布局:** PDF        
    # group loop
    - color: "blue"
      content: |
        ### 图像、图形和图表
        * **光栅图像:** BMP, GIF, JPG, JPEG, PNG
        * **医学成像:** DICOM
        * **Microsoft Visio:** VSDX, VSD, VSS, VST, VDX
        * **AutoCAD Drawing:** DWG, DXF
      # group loop
    - color: "red"
      content: |
        ### 其他
        * **文本:** TXT
        * **编程语言:** CS, Java, CPP, JS, PY, RB, PL, ASM, GROOVY, JSON, PHP, SQL, LOG, DIFF, LESS, SCALA
        * **网页:** HTM, HTML, MHT, MHTML
        * **电子书:** MOBI, DjVu
        * **分隔符分隔的值:** CSV

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Comparison for Python via .NET 功能"
  description: "轻松比较 PDF 和 Office 文档、图像和其他格式。"

  items:
    # feature loop
    - icon: "compare"
      title: "用户友好的文档比较"
      content: "分析并识别两个文档之间的差异。"

    # feature loop
    - icon: "note-stack"
      title: "比较多个文档"
      content: "同时分析和识别多个文档中的差异。"

    # feature loop
    - icon: "stacks"
      title: "支持的格式"
      content: "支持 50 多种不同类别的流行文档格式。"

    # feature loop
    - icon: "rule"
      title: "接受或拒绝更改"
      content: "已识别更改的清晰视觉表示，可以选择接受或拒绝修改。"

    # feature loop
    - icon: "preview"
      title: "生成预览"
      content: "将比较结果保存为图像。"

    # feature loop
    - icon: "two-pager"
      title: "内容比较"
      content: "逐行、按段落、按单词或按字符比较文本内容。突出显示更改。"

    # feature loop
    - icon: "format_color_text"
      title: "风格比较"
      content: "检测格式和样式的变化。"

    # feature loop
    - icon: "folder-managed"
      title: "设置元数据"
      content: "保留源文件或目标文件中的元数据，或允许用户指定。"

    # feature loop
    - icon: "lock"
      title: "密码保护"
      content: "分析加密文档，或使用密码保护生成的文档。"

    # feature loop
    - icon: "select"
      title: "比较特定页面"
      content: "加载并比较文档的特定部分或页面。"

    # feature loop
    - icon: "speaker-notes"
      title: "显示评论"
      content: "选择加载源文档时隐藏或显示注释。"

############################# Code samples ############################
code_samples:
  enable: true
  title: "代码示例"
  description: "探索 GroupDocs.Comparison for Python via .NET 操作的典型用例"
  items:
    # code sample loop
    - title: "比较受密码保护的文档"
      content: |
        要比较[受密码保护](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/)的文档，您需要在加载文档时指定密码：
        {{< landing/code title="如何比较受密码保护的文档。">}}
        ```python {style=abap}
        def run():

            # 加载源文档并指定其密码
            with groupdocs.comparison.Comparer("source.docx", new LoadOptions("1234")) as comparer:

                # 加载目标文档并指定其密码
                comparer.add("target.docx", new LoadOptions("5678"));

                # 将比较结果保存到指定文件中
                comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "比较多个 PDF 个文档。"
      content: |
        GroupDocs.Comparison 允许您 [比较两个以上的文档](https://docs.groupdocs.com/comparison/python-net/compare-multiple-documents/)。该操作与比较两个文件时的操作几乎相同。你只需要在 “比较器” 类中添加更多目标文件即可。
        {{< landing/code title="如何比较三个或更多文档。">}}
        ```python {style=abap}
        def run():

            # 加载源文档
            with groupdocs.comparison.Comparer(source.pdf") as comparer:

                # 指定第二个文件进行比较
                comparer.add("target2.pdf");

                # 指定第三个文件进行比较
                comparer.add("target3.pdf");

                # 将比较结果保存到指定文件中
                comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---