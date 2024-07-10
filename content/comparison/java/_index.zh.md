
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: zh
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

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
head_title: "Java 文档比较库| 差异检查器"
head_description: "用于比较文档风格和内容的本机 Java 软件。比较多种格式的文档以确定差异。"

############################# Header ############################
title: "使用 Java API 比较和检查文件差异"
description: "使用高度可配置的文档比较库开发 Java 个应用程序，以比较相似的文档格式，包括文件、其内容和文本样式。"
words:
  for: "为了"

actions:
  main: "免费下载 Maven"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/"
  alt: "许可"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/java/"
  title: "准备好开始了吗？"
  description: "免费试用 GroupDocs.Comparison 项功能或申请许可证"

release:
  title: "版本 {0} 已发布"
  notes: "查看新增内容"
  downloads: "下载"

code:
  title: "比较 Java 中的 DOCX 个文件"
  more: "更多例子"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
  install: |
    <dependency>
      <groupId>com.groupdocs</groupId>
      <artifactId>groupdocs-comparison</artifactId>
      <version>{0}</version>
    </dependency>
  content: |
    ```java {style=abap}  
    // 指定源文档
    try (Comparer comparer = new Comparer("source.docx"))
    {    
      // 添加一个或多个目标文档
      comparer.add("target.docx");

      // 指定比较选项
      CompareOptions options = new CompareOptions();
      options.setShowRevisions(false);

      // 比较并保存结果
      final comparer.compare("result.docx", options);
    }    
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison 一览"
  description: "用于比较 Java 个应用程序中文档之间差异的 API"
  features:
    # feature loop
    - title: "Java 中的文件比较"
      content: "在段落、单词和字符级别检测源文件和目标文件之间的变化。识别样式和格式变化，例如粗体、斜体、下划线、删除线、字体类型等。"

    # feature loop
    - title: "支持的大量格式"
      content: "使用 GroupDocs.Comparison API，您可以轻松比较多种支持格式的文档。这包括 PDF、HTML、电子邮件、Microsoft Office Word 个文档、Excel 个电子表格、PowerPoint 演示文稿、OneNote、Visio 图表、文本、JPEG、PNG、GIF 和 BMP 图像以及许多其他格式。"

    # feature loop
    - title: "轻松应用或拒绝更改"
      content: "比较文档之间的每一个差异都可以应用或拒绝，然后导出到输出文档。"

    # feature loop
    - title: "比较摘要报告"
      content: "生成摘要报告，列出比较文档中的所有更改。"

############################# Platforms ############################
platforms:
  enable: true
  title: "平台独立性"
  description: "GroupDocs.Comparison for Java 支持以下操作系统、框架和包管理器"
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
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "Maven"
      image: "maven"

############################# File formats ############################
formats:
  enable: true
  title: "支持的文件格式"
  description: |
    GroupDocs.Comparison for Java 支持以下 [文件格式](https://docs.groupdocs.com/comparison/java/supported-document-formats/) 的操作。
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
  title: "GroupDocs.Comparison 个功能"
  description: "轻松比较 PDF 和 Office 文档、图像和其他格式"

  items:
    # feature loop
    - icon: "compare"
      title: "易于使用的文档对比"
      content: "轻松分析和查明两个文档之间的差异。"

    # feature loop
    - icon: "note-stack"
      title: "比较多个文档"
      content: "同时检查和突出显示多个文档之间的差异。"

    # feature loop
    - icon: "stacks"
      title: "支持的格式"
      content: "与来自不同类别的50多种广泛使用的文档格式兼容。"

    # feature loop
    - icon: "rule"
      title: "接受或拒绝更改"
      content: "对已识别的更改进行清晰的可视化，并提供接受或拒绝修改的选项。"

    # feature loop
    - icon: "preview"
      title: "生成预览"
      content: "能够将比较结果保存为图像预览。"

    # feature loop
    - icon: "two-pager"
      title: "内容对比"
      content: "全面比较各个层面的文本内容，包括逐行、段落、单词和字符分析，重点是修改。"

    # feature loop
    - icon: "format_color_text"
      title: "风格对比"
      content: "能够检测和突出显示格式和样式元素的变化。"

    # feature loop
    - icon: "folder-managed"
      title: "设置元数据"
      content: "可以选择保留源文件或目标文件中的元数据，或允许用户定义的元数据设置。"

    # feature loop
    - icon: "lock"
      title: "密码保护"
      content: "便于分析受密码保护的文档，并为生成的文档启用密码保护。"

    # feature loop
    - icon: "select"
      title: "比较特定页面"
      content: "根据需要加载和比较文档的特定部分或页面。"

    # feature loop
    - icon: "speaker-notes"
      title: "显示评论"
      content: "加载源文档时可灵活显示或隐藏注释。"

############################# Code samples ############################
code_samples:
  enable: true
  title: "代码示例"
  description: "典型 GroupDocs.Comparison for Java 操作的一些用例"
  items:
    # code sample loop
    - title: "比较受密码保护的文档。"
      content: |
        要比较 [受密码保护](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/) 的文档，您需要指定它然后加载文档：
        {{< landing/code title="如何比较受密码保护的文档。">}}
        ```java {style=abap}
        // 加载源文档并指定其密码
        try (Comparer comparer = new Comparer("source.docx", new LoadOptions("1234")))
        {
            // 加载目标文档并指定其密码
            comparer.add("target.docx", new LoadOptions("5678"));
        
            // 将比较结果保存到指定文件中
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "比较多个 PDF 个文档。"
      content: |
        GroupDocs.Comparison 允许您 [比较两个以上的文档](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/)。该操作与比较两个文件时的操作几乎相同。你只需要在 “比较器” 类中添加更多目标文件即可。
        {{< landing/code title="如何比较三个或更多文档。">}}
        ```java {style=abap}   
        // 加载源文档
        try (Comparer comparer = new Comparer("source.docx") 
        {
            // 指定第二个文件进行比较
            comparer.add("target2.docx");

            // 指定第三个文件进行比较
            comparer.add("target3.docx");

            // 将比较结果保存到指定文件中
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---

