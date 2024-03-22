
---
############################# Static ############################
layout: "format"
date:  2024-03-22T13:27:44
draft: false
lang: zh
format: Vsdx
product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "将 VSDX 个文件与 C# 比较软件进行比较"
head_description: "比较并合并 C# .NET 应用程序中的 VSDX 个文件。检索内容、文本和样式中的差异摘要。"

############################# Header ############################
title: "比较 C# .NET 中的 VSDX" 
description: ".NET 文档比较 API 用于检查 VSDX 文件的两个版本之间的差异，并导出到包含比较文档之间差异的详细摘要的最终文档。"
subtitle: "文件比较解决方案" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "免费 Nuget 下载"
      link: "https://releases.groupdocs.com/comparison/net/"
      
############################# About ############################
about:
    enable: true
    title: "探索 GroupDocs.Comparison for .NET API 的优势"
    link: "/comparison/net/"
    link_title: "了解更多"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison for .NET 是一个原生 .NET API，专为比较相同格式的多个图像和文档而设计。它有助于检测段落、文字、字符、形状甚至对比文档的文本样式之间的差异。由于能够合并这些更改并导出到最终文档，它支持比较和合并 PDF、Word 个文档、Excel 个电子表格、PowerPoint 演示文稿、Visio 个图表、Outlook 封电子邮件、HTML、绘图和各种图像文件格式，所有这些都无需任何外部库。

############################# Steps ############################
steps:
    enable: true
    title: "如何使用 C# 比较多个 VSDX 个文件"
    content: |
      可以使用 [GroupDocs.Comparison](https://products.groupdocs.com/comparison/net/) 来获取有关许多 VSDX 文件差异的报告。
      
      1. 使用你最喜欢的软件包管理器从 [Nuget](https://www.nuget.org/packages/GroupDocs.Comparison) 安装 GroupDocs.Comparison for .NET
      2. 提供一个包含初始 VSDX 文件完整路径的 Comparer 类实例
      3. 向 Comparer 追加至少一个 VSDX
      4. 获取包含精确描述差异的最终报告
   
    code:
      platform: "net"
      copy_title: "复制"
      install:
        command: "dotnet add package GroupDocs.Comparison"
        copy_tip: "点击复制"
        copy_done: "复制的"
      links:
        #  loop
        - title: "更多例子"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET"
        #  loop
        - title: "文档"
          link: "https://docs.groupdocs.com/comparison/net/"
          
      content: |
        ```csharp {style=abap}

        // 比较本地磁盘中的多个文档

        // 实例化比较器提供第一个文件
        using (Comparer comparer = new Comparer("main_document.vsdx"))
        {
            // 添加其他文件
        	comparer.Add("modified_1.vsdx");
            comparer.Add("modified_2.vsdx");

            // 获取具有指定名称的结果文件
            comparer.Compare("report.vsdx"); 
        }
        
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "准备好开始了吗？"
  description: "免费试用 GroupDocs.Comparison 项功能或申请许可证"
  items:
    #  loop
    - title: "Nuget 下载"
      link: "https://releases.groupdocs.com/comparison/net/"
      color: "red"
        #  loop
    - title: "许可"
      link: "https://purchase.groupdocs.com/pricing/comparison/net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "使用 C# 比较常用的文件格式"
    exclude: "VSDX"
    description: ".NET 用于比较文档格式的 API。无需额外努力，即可充分了解文档处理过程中的变化。"
    items: 
        # format loop 1
        - name: "比较 PDF 个文件"
          format: "PDF"
          link: "/comparison/net/pdf/"
          description: "Adobe Portable 文档格式"

        # format loop 2
        - name: "比较 DOCX 个文件"
          format: "DOCX"
          link: "/comparison/net/docx/"
          description: "微软 Word 打开 XML 文档"

        # format loop 3
        - name: "比较 RTF 个文件"
          format: "RTF"
          link: "/comparison/net/rtf/"
          description: "富文本文件格式"

        # format loop 4
        - name: "比较 TXT 个文件"
          format: "TXT"
          link: "/comparison/net/txt/"
          description: "纯文本文件格式"

        # format loop 5
        - name: "比较 XLSX 个文件"
          format: "XLSX"
          link: "/comparison/net/xlsx/"
          description: "微软 Excel 打开 XML 电子表格"

        # format loop 6
        - name: "比较 CSV 文件"
          format: "CSV"
          link: "/comparison/net/csv/"
          description: "逗号分隔值文件"

        # format loop 7
        - name: "比较 PPTX 个文件"
          format: "PPTX"
          link: "/comparison/net/pptx/"
          description: "PowerPoint 打开 XML 演示文稿"

        # format loop 8
        - name: "比较 ODS 个文件"
          format: "ODS"
          link: "/comparison/net/ods/"
          description: "Open Document 电子表格"

        # format loop 9
        - name: "比较 ODP 文件"
          format: "ODP"
          link: "/comparison/net/odp/"
          description: "OpenDocument 演示文件格式"

        # format loop 10
        - name: "比较 ODT 个文件"
          format: "ODT"
          link: "/comparison/net/odt/"
          description: "Open Document 文本"

        # format loop 11
        - name: "比较 JPEG 个文件"
          format: "JPEG"
          link: "/comparison/net/jpeg/"
          description: "JPEG 图片"

        # format loop 12
        - name: "比较 PNG 个文件"
          format: "PNG"
          link: "/comparison/net/png/"
          description: "Portable 网络图形"

        # format loop 13
        - name: "比较 GIF 个文件"
          format: "GIF"
          link: "/comparison/net/gif/"
          description: "图形交换格式文件"

        # format loop 14
        - name: "比较 BMP 个文件"
          format: "BMP"
          link: "/comparison/net/bmp/"
          description: "位图文件格式"

        # format loop 15
        - name: "比较 HTML 文件"
          format: "HTML"
          link: "/comparison/net/html/"
          description: "超文本标记语言"

        # format loop 16
        - name: "比较 MSG 个文件"
          format: "MSG"
          link: "/comparison/net/msg/"
          description: "微软 Outlook 电子邮件"

        # format loop 17
        - name: "比较 ONE 个文件"
          format: "ONE"
          link: "/comparison/net/one/"
          description: "微软 OneNote"

        # format loop 18
        - name: "比较 VSDX 个文件"
          format: "VSDX"
          link: "/comparison/net/vsdx/"
          description: "微软 Visio 绘图"

        # format loop 19
        - name: "比较 CS 文件"
          format: "CS"
          link: "/comparison/net/cs/"
          description: "cSharp 语言"

        # format loop 20
        - name: "比较 Java 个文件"
          format: "Java"
          link: "/comparison/net/java/"
          description: "Java 语言"
          
        # format loop 21
        - name: "比较 CPP 文件"
          format: "CPP"
          link: "/comparison/net/cpp/"
          description: "C++ 语言"
---