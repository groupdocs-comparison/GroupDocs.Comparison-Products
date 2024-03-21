
---
############################# Static ############################
layout: "format"
date:  2024-03-21T15:26:23
draft: false
lang: zh
format: Pdf
product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "查看 C# .NET 中的 PDF 个文档的差异"
head_description: "比较并合并 C# .NET 应用程序中的两个以上 PDF 个文件。检索 PDF 个文件的内容、文本和样式中的差异摘要。"

############################# Header ############################
title: "比较 C# .NET 应用程序中的 PDF 个文档" 
description: ".NET 文档比较 API 用于识别和显示基于 C#、ASP .NET、VB .NET 和 .NET 内核的应用程序内 PDF 的差异。轻松获取详细报告，享受无缝体验。"
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
    title: "发现 GroupDocs.Comparison for .NET API 功能"
    link: "/comparison/net/"
    link_title: "了解更多"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       在 .NET 个应用程序的 PDF 个文档中获取有关差异的详细报告。将不同的 PDF 合并为具有相同格式的新文件。通过添加几行代码来使用 GroupDocs.Comparison for .NET API。无需第三方软件即可处理 PDF 和其他格式。

############################# Steps ############################
steps:
    enable: true
    title: "如何使用 C# 比较 PDF"
    content: |
      使用 [GroupDocs.Comparison](https://products.groupdocs.com/comparison/net/) 获取有关许多 PDF 文件差异的报告
      
      1. 从 [Nuget](https://www.nuget.org/packages/GroupDocs.Comparison) 获取 GroupDocs.Comparison for .NET 并安装它
      2. 使用 PDF 文件路径创建全新的比较器实例
      3. 将其他 PDF 添加到比较中
      4. 结果包含关于两个 PDF 之间差异的报告
   
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

        // 编写 PDF 的区别报告

        // 使用第一个文件的路径实例化比较器
        using (Comparer comparer = new Comparer("source.pdf"))
        {
            // 将一个或多个 PDF 添加到比较中
        	comparer.Add("file_to_compare_1.pdf");
            comparer.Add("file_to_compare_2.pdf");
            comparer.Add("file_to_compare_3.pdf");

            // 结果报告待分析
            comparer.Compare("result.pdf"); 
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
    title: "使用 C# 比较 PDF 并获取完整报告"
    exclude: "PDF"
    description: ".NET C# 软件用于 PDF 个文档比较。轻松了解文档的任何更改。"
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