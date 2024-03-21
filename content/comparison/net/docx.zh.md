
---
############################# Static ############################
layout: "format"
date:  2024-03-21T15:26:23
draft: false
lang: zh
format: Docx
product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "比较 MS Word DOCX via C# 和 .NET"
head_description: "DOCX 与 GroupDocs.Comparison for .NET 的比较。详细报告，重点介绍了 DOCX 个文档之间的变动。将我们的 API 与 C# 一起使用。"

############################# Header ############################
title: "MS Word DOCX 与 C# .NET 应用程序的比较" 
description: ".NET 专为文档比较而设计的 API 可查找并报告 MS Word 文件中的任何差异。基于 C#、ASP .NET、VB .NET 或 .NET 核心构建应用程序以获得优势。获取添加几行代码的详细报告。"
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
    title: "检查 GroupDocs.Comparison for .NET 个 API 功能"
    link: "/comparison/net/"
    link_title: "了解更多"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       在您的 .NET 项目中使用便捷的报告显示您的 DOCX 文档中的变更。此外，获取有关样式、形状和其他内容的信息，并将 DOCX 个文件合并到一个新文件中。只需几行代码即可为您的项目带来 GroupDocs.Comparison for .NET API 的优势。无需第三方开发人员即可使用我们的软件。

############################# Steps ############################
steps:
    enable: true
    title: "通过 .NET 和 C# 提交比较报告 MS Word DOCX"
    content: |
      使用 [GroupDocs.Comparison](https://products.groupdocs.com/comparison/net/) 为 DOCX 文件撰写区别报告
      
      1. 从 [Nuget](https://www.nuget.org/packages/GroupDocs.Comparison) 下载 GroupDocs.Comparison for .NET 软件包并进行安装
      2. 实例化将路径传递给 DOCX 的比较器对象
      3. 添加 DOCX 个文件进行比较
      4. 获取包含区别信息的报告
   
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

        // DOCX 文件变更报告

        // 实例化比较器进行文档处理
        using (Comparer comparer = new Comparer("source.docx"))
        {
            // 添加至少一个文件进行比较
        	comparer.Add("file_to_compare_1.docx");
            comparer.Add("file_to_compare_2.docx");
            comparer.Add("file_to_compare_3.docx");

            // 分析结果
            comparer.Compare("result.docx"); 
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
    title: "比较 DOCX 个 C# 个应用程序"
    exclude: "DOCX"
    description: "GroupDocs.Comparison for .NET 控制常用文件格式版本的优势。快速、轻松地收集 MS Word 个文档信息。"
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