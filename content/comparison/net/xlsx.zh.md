
---
############################# Static ############################
layout: "format"
date:  2024-03-22T13:27:45
draft: false
lang: zh
format: Xlsx
product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "MS Excel 电子表格比较"
head_description: "GroupDocs.Comparison for .NET API 便于检查 XLSX 个电子表格的差异和分析。支持 C# .NET。"

############################# Header ############################
title: "利用 C# 项技术比较 XLSX 个电子表格" 
description: ".NET API 专为比较各种文档类型而设计，可识别和报告 MS Excel 文件中的区别。使用 C#、ASP .NET、VB .NET 或 .NET Core 构建应用程序，以利用其优势。只需最少的代码实现即可获得详细报告。"
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
    title: "探索 GroupDocs.Comparison for .NET API 的功能"
    link: "/comparison/net/"
    link_title: "了解更多"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       通过 .NET 项目中的便捷报告，检测您的 XLSX 电子表格中的变化。此外，检索有关样式、形状和其他内容的信息，并将 XSLX 电子表格合并到新文档中。只需几行代码即可将 GroupDocs.Comparison for .NET API 集成到您的项目中。无需第三方开发人员即可使用我们的软件。

############################# Steps ############################
steps:
    enable: true
    title: "使用 C# 生成 MS Excel XLSX 比较报告"
    content: |
      使用 [GroupDocs.Comparison](https://products.groupdocs.com/comparison/net/) 为 XLSX 文件创建区别报告
      
      1. 从 [Nuget](https://www.nuget.org/packages/GroupDocs.Comparison) 下载并安装 GroupDocs.Comparison for .NET 软件包
      2. 通过提供 XLSX 文件路径来实例化 Comparer 对象
      3. 包括 XLSX 张电子表格以供比较
      4. 检索包含区别信息的比较报告
   
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

        // 生成 XLSX 个文件中的变更报告

        // 实例化用于电子表格处理的 Comparer 对象
        using (Comparer comparer = new Comparer("source.xlsx"))
        {
            // 至少包含一个文件进行比较
        	comparer.Add("file_to_compare_1.xlsx");
            comparer.Add("file_to_compare_2.xlsx");
            comparer.Add("file_to_compare_3.xlsx");

            // 分析比较结果
            comparer.Compare("result.xlsx"); 
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
    title: "比较 C# 个应用程序的 MS Excel 个电子表格"
    exclude: "XLSX"
    description: "探索 GroupDocs.Comparison for .NET 在控制 XLSX 文档版本方面的优势。快速轻松地从 MS Excel 电子表格中收集信息以进行进一步分析。"
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