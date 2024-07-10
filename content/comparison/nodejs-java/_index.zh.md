
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: zh
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
    # supported_platforms loop
    - title: "Python"
      tag: "python-net"

############################# Head ############################
head_title: "Node.js 文档比较 API | 差异检查器"
head_description: "Node.js 文档比较 API 为文档比较提供了有效的工具。与 Node.js 无缝集成，实现实时变更跟踪"

############################# Header ############################
title: "将文档与 Node.js 进行比较：突出显示所有差异"
description: "使用 GroupDocs.Comparison API 开发具有高度可配置比较功能的原生 Java 脚本应用程序。比较相似文档格式之间的文件、其内容和文本样式。"
words:
  for: "为了"

actions:
  main: "免费下载 NPM"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.comparison"
  alt: "许可"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/nodejs-java/"
  title: "准备好开始了吗？"
  description: "免费试用 GroupDocs.Comparison 项功能或申请许可证"

release:
  title: "版本 {0} 已发布"
  notes: "查看新增内容"
  downloads: "下载"

code:
  title: "比较 Java 脚本中的 BMP 张图像"
  more: "更多例子"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.comparison"
  content: |
    ```javascript {style=abap}

    // 指定源文档
    const comparer = new Comparer("source.bmp");

    // 添加一个或多个目标文档
    comparer.add("target.bmp");

    // 指定比较选项
    const options = new groupdocs.comparison.CompareOptions();
    options.setGenerateSummaryPage(false);

    // 比较并保存结果
    await comparer.compare("result.bmp", options);
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison 一览"
  description: "用于比较 Node.js 应用程序中各种类型的文档（例如 PDF、Microsoft Office、HTML、电子邮件或图像）的 API"
  features:
    # feature loop
    - title: "详细的输出报告"
      content: "GroupDocs.Comparison 标识文档内容（字符、文字、段落、表格、图表）的变化以及文档样式的变化。它为客户提供一份结果报告，其中包含有关差异、差异数量和类型的丰富信息。"

    # feature loop
    - title: "支持最常用的文件和文档格式"
      content: "使用 GroupDocs.Comparison API，您可以高效地比较任何支持格式的文档，例如 PDF、HTML、电子邮件、Microsoft Office Word 文档、Excel 电子表格、PowerPoint 演示文稿、OneNote、Visio 图表、文本、JPEG、PNG、GIF 和 BMP 图像以及许多其他格式。"

    # feature loop
    - title: "文档和示例"
      content: "已经有很多关于在不同平台上使用比较库的文档以及代码示例，因此您不必费心思考如何在 Node.js 应用程序中使用 GroupDocs.Comparison API。"

    # feature loop
    - title: "选择更改并将它们合并到一个文件中"
      content: "如果一个文档有不同的版本，则可以只选择所需的更改并使用 GroupDocs.Comparison 库编译新文档。"

############################# Platforms ############################
platforms:
  enable: true
  title: "平台独立性"
  description: "GroupDocs.Comparison for Node.js via Java 支持以下操作系统、框架和包管理器"
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
    GroupDocs.Comparison for Node.js via Java 支持以下 [文件格式](https://docs.groupdocs.com/comparison/nodejs-java/supported-document-formats/) 的操作。
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
  title: "GroupDocs.Comparison for Node.js via Java 个功能"
  description: "轻松比较 PDF 和 Office 文档、图像和其他格式"

  items:
    # feature loop
    - icon: "compare"
      title: "易于使用的文档对比"
      content: "分析并识别两个文档中的差异。"

    # feature loop
    - icon: "note-stack"
      title: "比较多个文档"
      content: "同时分析和识别多个文档中的差异。"

    # feature loop
    - icon: "stacks"
      title: "支持的格式"
      content: "支持来自不同类别的 50 多种流行文档格式。"

    # feature loop
    - icon: "rule"
      title: "接受或拒绝更改"
      content: "清晰直观地呈现已识别的更改，提供接受或拒绝修改的选项。"

    # feature loop
    - icon: "preview"
      title: "生成预览"
      content: "将比较结果另存为图像。"

    # feature loop
    - icon: "two-pager"
      title: "内容对比"
      content: "逐行、逐段、逐字、逐字符比较文本内容。突出显示更改。"

    # feature loop
    - icon: "format_color_text"
      title: "风格对比"
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
      content: "仅加载文档的特定部分或页面。"

    # feature loop
    - icon: "speaker-notes"
      title: "显示评论"
      content: "加载源文档时，您可以选择隐藏还是显示注释。"

############################# Code samples ############################
code_samples:
  enable: true
  title: "代码示例"
  description: "典型 GroupDocs.Comparison for Node.js via Java 操作的一些用例"
  items:
    # code sample loop
    - title: "比较受密码保护的文档。"
      content: |
        要比较 [受密码保护](https://docs.groupdocs.com/comparison/nodejs-java/load-password-protected-documents/) 的文档，您需要指定它然后加载文档：
        {{< landing/code title="如何比较受密码保护的文档。">}}
        ```javascript {style=abap}

        import { Comparer, LoadOptions } from '@groupdocs/groupdocs.comparison'

        // 加载源文档并指定其密码
        const comparer = new Comparer("source.docx", new LoadOptions("1234"));

        // 加载目标文档并指定其密码
        comparer.add("target.docx", new LoadOptions("5678"));

        // 将比较结果保存到指定文件中
        comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "比较多个 PDF 个文档。"
      content: |
        GroupDocs.Comparison 允许您 [比较两个以上的文档](https://docs.groupdocs.com/comparison/nodejs-java/compare-multiple-documents/)。该操作与比较两个文件时的操作几乎相同。你只需要在 “比较器” 类中添加更多目标文件即可。
        {{< landing/code title="如何比较三个或更多文档。">}}
        ```javascript {style=abap}
        import { Comparer } from '@groupdocs/groupdocs.comparison'

        // 加载源文档
        const comparer = new Comparer(source.pdf");

        // 指定第二个文件进行比较
        comparer.add("target2.pdf");

        // 指定第三个文件进行比较
        comparer.add("target3.pdf");

        // 将比较结果保存到指定文件中
        comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---