
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: zh
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
head_title: "C# .NET 文档比较软件 | 差异检查器"
head_description: "C# .NET 用于比较文档风格和内容的软件。比较多种支持格式的文档，以确定文件之间的变化。"

############################# Header ############################
title: "在 C# .NET 解决方案中轻松比较文档"
description: "使用灵活的文档比较 API 构建 C# 个应用程序，该应用程序支持按内容和样式比较各种文档格式的文件。"
words:
  for: "为了"

actions:
  main: "免费 NuGet 下载"
  main_link: "https://www.nuget.org/packages/GroupDocs.Comparison"
  alt: "许可"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/net/"
  title: "准备好开始了吗？"
  description: "免费试用 GroupDocs.Comparison 项功能或申请许可证"

release:
  title: "版本 {0} 已发布"
  notes: "查看新增内容"
  downloads: "下载"

code:
  title: "比较 C# 中的 DOCX 个文件"
  more: "更多例子"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET"
  install: "dotnet add package GroupDocs.Comparison"
  content: |
    ```csharp {style=abap}   
    // 指定源文档
    using (Comparer comparer = new Comparer("source.docx"))
    {
        // 添加一个或多个目标文档
        comparer.Add("target.docx");

        // 指定比较选项
        CompareOptions options = new CompareOptions() 
        {ShowRevisions = false};

        // 比较并保存结果
        comparer.Compare("result.docx", options);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison 一览"
  description: "用于比较 .NET 个应用程序中文档之间差异的 API"
  features:
    # feature loop
    - title: "C# 中的文件比较"
      content: "检测源文件和目标文件之间的差异，以了解段落、单词和字符级别的变化。识别样式和格式变化，例如粗体、斜体、下划线、删除线、字体类型等。"

    # feature loop
    - title: "支持最常用的文件和文档格式"
      content: "GroupDocs.Comparison API 允许对各种格式的文档进行有效的比较，包括 PDF、HTML、电子邮件、Microsoft Office 个文档（Word、Excel、PowerPoint、OneNote、Visio）、各种图像类型（JPEG、PNG、GIF、BMP）、文本文件等。"

    # feature loop
    - title: "轻松应用或拒绝更改"
      content: "使用 GroupDocs.Comparison API 在比较文档中确定的每种差异都可以选择性应用或拒绝，从而可以在导出到最终输出文档之前进行自定义。"

    # feature loop
    - title: "比较摘要报告"
      content: "生成差异摘要报告，详细说明比较文档中发现的所有更改，并将其保存以供参考。"

############################# Platforms ############################
platforms:
  enable: true
  title: "平台独立性"
  description: "GroupDocs.Comparison for .NET 支持以下操作系统、框架和包管理器"
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
  title: "支持的文件格式"
  description: |
    GroupDocs.Comparison for .NET 支持以下 [文件格式](https://docs.groupdocs.com/comparison/net/supported-document-formats/) 的操作。
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
      content: "分析并确定两个文档之间的差异。"

    # feature loop
    - icon: "note-stack"
      title: "比较多个文档"
      content: "同时分析和识别多个文档之间的差异。"

    # feature loop
    - icon: "stacks"
      title: "支持的格式"
      content: "兼容来自不同类别的 50 多种广泛使用的文档格式，确保了广泛的适用性。"

    # feature loop
    - icon: "rule"
      title: "接受或拒绝更改"
      content: "清晰直观地显示检测到的更改，并附有接受或拒绝这些修改的选项。"

    # feature loop
    - icon: "preview"
      title: "生成预览"
      content: "能够将比较结果保存为图像预览，便于参考和共享。"

    # feature loop
    - icon: "two-pager"
      title: "内容对比"
      content: "在各个层面进行全面的文本比较，包括逐行、段落、单词和字符，并突出显示差异，以提高清晰度。"

    # feature loop
    - icon: "format_color_text"
      title: "样式和格式比较"
      content: "检测并突出显示文档格式和样式的变化，确保全面审查。"

    # feature loop
    - icon: "folder-managed"
      title: "灵活的元数据设置"
      content: "保留源文件或目标文件中的元数据，或根据用户偏好对其进行自定义。"

    # feature loop
    - icon: "lock"
      title: "密码保护"
      content: "分析受密码保护的文档，并使用密码加密保护输出文档，以提高安全性。"

    # feature loop
    - icon: "select"
      title: "选择性页面比较"
      content: "加载和比较文档的特定部分或页面以进行有针对性的分析。"

    # feature loop
    - icon: "speaker-notes"
      title: "显示评论"
      content: "加载源文档时选择显示或隐藏注释，从而更好地控制比较过程。"

############################# Code samples ############################
code_samples:
  enable: true
  title: "代码示例"
  description: "典型 GroupDocs.Comparison for .NET 操作的一些用例"
  items:
    # code sample loop
    - title: "比较受密码保护的文档。"
      content: |
        要比较 [受密码保护](https://docs.groupdocs.com/comparison/net/load-password-protected-documents/) 的文档，您需要指定它然后加载文档：
        {{< landing/code title="如何比较受密码保护的文档。">}}
        ```csharp {style=abap}
        // 加载源文档并指定其密码
        using(Comparer comparer = new Comparer("source.docx", new LoadOptions() {Password = "1234"}))  
        {
            // 加载目标文档并指定其密码
            comparer.Add("target.docx", new LoadOptions() {Password = "5678"});

            // 将比较结果保存到指定文件中
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "比较多个 PDF 个文档。"
      content: |
        GroupDocs.Comparison 允许您 [比较两个以上的文档](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/)。该操作与比较两个文件时的操作几乎相同。你只需要在 “比较器” 类中添加更多目标文件即可。
        {{< landing/code title="如何比较三个或更多文档。">}}
        ```csharp {style=abap}   
        // 加载源文档
        using(Comparer comparer = new Comparer("source.docx") 
        {
            // 指定第二个文件进行比较
            comparer.Add("target2.docx");
            
            // 指定第三个文件进行比较
            comparer.Add("target3.docx");
            
            // 将比较结果保存到指定文件中
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---
