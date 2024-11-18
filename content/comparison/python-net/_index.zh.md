
---
############################# Static ############################
layout: "landing"
date: 2024-11-18T09:49:37
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
head_title: "Python 文档比较工具 |文件分析"
head_description: "探索 Python 文档比较工具进行彻底文档分析的强大功能。轻松与 Python 集成以全面跟踪修改。"

############################# Header ############################
title: "将文档与 Python 进行比较：突出显示任何差异"
description: "利用 GroupDocs.Comparison API 在 Python 中创建具有可自定义比较功能的本机应用程序。检查文件、其内容以及跨文档格式的样式变化。"
words:
  for: "为了"

actions:
  main: "立即免费下载 PyPi"
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
  title: "使用 Python 比较 BMP 图像"
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
  description: "设计用于比较广泛使用的文档类型（例如 PDF、Microsoft Office 文件、HTML、电子邮件或 Python 应用程序中的图像）的 API。"
  features:
    # feature loop
    - title: "综合输出报告"
      content: "GroupDocs.Comparison 检测文档内容（字符、单词、段落、表格、图表）的更改以及文档样式的更改。用户会收到一份详细的报告，突出显示更改的性质和数量。"

    # feature loop
    - title: "多种文件和文档格式"
      content: "GroupDocs.Comparison API 允许您比较 PDF、HTML、电子邮件、Microsoft Office Word、Excel 工作簿、PowerPoint 文件、OneNote 笔记、Visio 图表、文本文档、JPEG、PNG、GIF、BMP 图像等格式的文档，等等。"

    # feature loop
    - title: "完整的文档和代码示例"
      content: "跨各种平台的比较库的深入文档和示例代码随时可用，简化了将 GroupDocs.Comparison API 集成到 Python 应用程序中的过程。"

    # feature loop
    - title: "选择更改并将其合并到一个文档中"
      content: "如果您拥有文档的多个版本，则可以使用 GroupDocs.Comparison 库有选择地将更改编译到单个新文件中。"

############################# Platforms ############################
platforms:
  enable: true
  title: "平台独立性"
  description: "GroupDocs.Comparison for Python via .NET 与以下操作系统、框架和包管理器兼容。"
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
    GroupDocs.Comparison for Python via .NET 可以使用以下[文件格式](https://docs.groupdocs.com/comparison/net/supported-document-formats/)。
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
  title: "GroupDocs.Comparison for Python via .NET 的功能"
  description: "无缝比较 PDF、Office 文档、图像和各种其他格式。"

  items:
    # feature loop
    - icon: "compare"
      title: "直观的文档比较"
      content: "检查并突出显示两个文档之间的差异。"

    # feature loop
    - icon: "note-stack"
      title: "多个文档的比较"
      content: "同时检查多个文档是否存在差异。"

    # feature loop
    - icon: "stacks"
      title: "广泛的格式支持"
      content: "与不同类别的 50 多种常用文档格式兼容。"

    # feature loop
    - icon: "rule"
      title: "接受或拒绝更改"
      content: "清晰地可视化更改，提供接受或拒绝编辑的选项。"

    # feature loop
    - icon: "preview"
      title: "生成视觉预览"
      content: "以图像格式创建比较结果的预览。"

    # feature loop
    - icon: "two-pager"
      title: "基于文本的内容比较"
      content: "执行逐行、段落、单词或字符比较以突出显示更改。"

    # feature loop
    - icon: "format_color_text"
      title: "格式更改检测"
      content: "识别文档样式和格式的更改。"

    # feature loop
    - icon: "folder-managed"
      title: "可定制的元数据处理"
      content: "保留源文件或目标文件中的元数据，或允许用户定义新的元数据。"

    # feature loop
    - icon: "lock"
      title: "处理受密码保护的文件"
      content: "处理加密文档，或创建受密码保护的安全文档。"

    # feature loop
    - icon: "select"
      title: "重点页面比较"
      content: "选择并比较文档的特定部分或单个页面。"

    # feature loop
    - icon: "speaker-notes"
      title: "管理评论可见性"
      content: "在检查源文档时决定公开或隐藏评论。"

############################# Code samples ############################
code_samples:
  enable: true
  title: "代码示例"
  description: "了解使用 GroupDocs.Comparison for Python via .NET 功能的常见场景。"
  items:
    # code sample loop
    - title: "比较文档与密码保护"
      content: |
        要比较[使用密码保护](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/) 的文档，您需要在加载文档时指定密码：
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