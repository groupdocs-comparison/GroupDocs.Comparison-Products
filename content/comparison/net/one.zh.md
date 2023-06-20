
---
############################# Static ############################
layout: "auto-gen-comparison"
date: 2021-05-13T12:45:19+03:00
draft: false

############################# Head ############################
head_title: "在 .NET 中比较两个 ONE 文件 |文档比较 API"
head_description: "在 C# .NET 应用程序中比较和合并两个以上的 ONE 文件。检索 ONE 文件、图像和文档格式的内容、文本和样式的差异摘要。"

############################# Header ############################
title: "在 C# .NET 中比较 ONE 文件"
description: ".NET 文档比较 API 检测两个版本的 ONE 文件之间的变化，并导出到最终文档，其中包含比较文档之间差异的详细摘要。"
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "下载免费试用版"
    link: "https://downloads.groupdocs.com/comparison/net"

############################# SubMenu ############################
submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Comparison for .NET"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-comparison-net.png"
        product: "GroupDocs.Comparison"
        platform: "。网"

    middle:
        button: 
            # 按钮循环
            - link: "https://apireference.groupdocs.com/comparison/net"
              text: "API 参考"

            # 按钮循环
            - link: "https://github.com/groupdocs-comparison"
              text: "代码示例"

            # 按钮循环
            - link: "https://products.groupdocs.app/comparison/family"
              text: "现场演示"

            # 按钮循环
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "定价"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/net"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: "关于 .NET API 的 GroupDocs.Comparison"
    content: |
        [GroupDocs.Comparison for .NET](/zh/comparison/net/) 是一种本机 .NET API，用于比较相同格式的多个图像和文档。它可以帮助您检测段落、单词、字符、形状甚至比较文档的文本样式之间的差异，合并更改并导出到最终文档。它支持比较和合并 PDF、Word 文档、Excel 电子表格、PowerPoint 演示文稿、Visio 图表、Outlook 电子邮件、HTML、绘图和图像文件格式，而无需使用任何外部库。

############################# Steps ############################
steps:
    enable: true
    title_left: "在 C# 中比较 ONE 文件的步骤"
    content_left: |
        [GroupDocs.Comparison](/comparison/net/) 使 .NET 开发人员可以通过实施几个简单的步骤轻松地比较和合并应用程序中的多个 ONE 文件。
        *   使用源文档路径或流实例化 **Comparer** 对象。
        * 调用 Add 方法并指定目标文档路径或流。对每个目标文档重复此步骤。
        * 调用比较方法。
    title_right: "系统要求"
    content_right: |
        所有主要平台和操作系统都支持 .NET API 的 GroupDocs.Comparison。在执行下面的代码之前，请确保您的系统上安装了以下先决条件。
        *   操作系统：Microsoft Windows、Linux、MacOS
        * 开发环境：Microsoft Visual Studio、Xamarin、MonoDevelop
        * 框架：.NET Framework、.NET Standard、.NET Core、Mono
        * 从 [NuGet](https://www.nuget.org/packages/groupdocs.comparison) 下载最新版本的 GroupDocs.Comparison for .NET
    code: |
        ```cs
        // 比较本地磁盘中的多个文档
        
        using (Comparer comparer = new Comparer("source.one"))
        {
        	comparer.Add("target1.one");
            comparer.Add("target2.one");
            comparer.Add("target3.one");
            comparer.Compare("result.one"); // 创建指定名称的结果文件
        }
        
        // 比较流中的多个文档
        
        using (Comparer comparer = new Comparer(File.OpenRead("source.one")))
        {
        	comparer.Add(File.OpenRead("target1.one"));
            comparer.Add(File.OpenRead("target2.one"));
            comparer.Add(File.OpenRead("target3.one"));
            comparer.Compare(File.Create("result.one")); // 创建指定名称的结果文件
        }
        ```

############################# Demos ############################
demos:
    enable: true
    title: "比较 ONE 文件的现场演示"
    content: |
        通过访问 [GroupDocs.Comparison Live Demos](https://products.groupdocs.app/comparison/family) 网站立即检测 ONE 文件之间的差异。
        现场演示有以下好处

############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-one"
          title: "关于 ONE 文件格式"
          content: |
            .ONE 扩展名表示的文件是由 Microsoft OneNote 应用程序创建的。 OneNote 让您可以使用该应用程序收集信息，就像您使用草稿本做笔记一样。 OneNote 文件可以包含不同的元素，这些元素可以放置在文档页面上的非固定位置。这些元素可能包含文本、数字化笔迹和从其他应用程序复制的对象，包括图像、绘图和多媒体（音频/视频）剪辑。 Microsoft 现在提供 OneNote 的在线版本作为 Office365 的一部分，其中可以通过 Internet 与其他 OneNote 用户共享笔记。
          link: "https://docs.fileformat.com/image/one/"

############################# More Formats ############################
more_formats:
    enable: true
    title: "比较其他文件格式"
    content: |
        .NET 的多格式文档和图像比较 API。在不使用任何外部工具的情况下分析相同格式文档之间的差异。
    format: 
        # format loop
        - name: "Compare PDF Files"
          link: "https://products.groupdocs.com/comparison/net/pdf/"
          description: "Adobe Portable Document Format"

        # format loop
        - name: "Compare DOC Files"
          link: "https://products.groupdocs.com/comparison/net/doc/"
          description: "Microsoft Word Document"

        # format loop
        - name: "Compare DOCM Files"
          link: "https://products.groupdocs.com/comparison/net/docm/"
          description: "Microsoft Word Macro-Enabled Document"

        # format loop
        - name: "Compare DOCX Files"
          link: "https://products.groupdocs.com/comparison/net/docx/"
          description: "Microsoft Word Open XML Document"

        # format loop
        - name: "Compare DOT Files"
          link: "https://products.groupdocs.com/comparison/net/dot/"
          description: "Microsoft Word Document Template"

        # format loop
        - name: "Compare DOTM Files"
          link: "https://products.groupdocs.com/comparison/net/dotm/"
          description: "Microsoft Word Macro-Enabled Template"

        # format loop
        - name: "Compare DOTX Files"
          link: "https://products.groupdocs.com/comparison/net/dotx/"
          description: "Word Open XML Document Template"

        # format loop
        - name: "Compare RTF Files"
          link: "https://products.groupdocs.com/comparison/net/rtf/"
          description: "Rich Text File Format"

        # format loop
        - name: "Compare TXT Files"
          link: "https://products.groupdocs.com/comparison/net/txt/"
          description: "Plain Text File Format"

        # format loop
        - name: "Compare XLS Files"
          link: "https://products.groupdocs.com/comparison/net/xls/"
          description: "Microsoft Excel Binary File Format"

        # format loop
        - name: "Compare XLSX Files"
          link: "https://products.groupdocs.com/comparison/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop
        - name: "Compare XLTM Files"
          link: "https://products.groupdocs.com/comparison/net/xltm/"
          description: "Microsoft Excel macro-enabled template"

        # format loop
        - name: "Compare XLSM Files"
          link: "https://products.groupdocs.com/comparison/net/xlsm/"
          description: "Microsoft Excel Macro-Enabled Spreadsheet"

        # format loop
        - name: "Compare XLSB Files"
          link: "https://products.groupdocs.com/comparison/net/xlsb/"
          description: "Microsoft Excel Binary Spreadsheet File"

        # format loop
        - name: "Compare CSV Files"
          link: "https://products.groupdocs.com/comparison/net/csv/"
          description: "Comma Separated Values File"

        # format loop
        - name: "Compare PPT Files"
          link: "https://products.groupdocs.com/comparison/net/ppt/"
          description: "PowerPoint Presentation"

        # format loop
        - name: "Compare PPS Files"
          link: "https://products.groupdocs.com/comparison/net/pps/"
          description: "Microsoft PowerPoint Slide Show"

        # format loop
        - name: "Compare PPTX Files"
          link: "https://products.groupdocs.com/comparison/net/pptx/"
          description: "PowerPoint Open XML Presentation"

        # format loop
        - name: "Compare PPSX Files"
          link: "https://products.groupdocs.com/comparison/net/ppsx/"
          description: "PowerPoint Open XML Slide Show"

        # format loop
        - name: "Compare POT Files"
          link: "https://products.groupdocs.com/comparison/net/pot/"
          description: "Microsoft PowerPoint template"

        # format loop
        - name: "Compare POTX Files"
          link: "https://products.groupdocs.com/comparison/net/potx/"
          description: "Microsoft PowerPoint Open XML Template"

        # format loop
        - name: "Compare ODS Files"
          link: "https://products.groupdocs.com/comparison/net/ods/"
          description: "Open Document Spreadsheet"

        # format loop
        - name: "Compare ODP Files"
          link: "https://products.groupdocs.com/comparison/net/odp/"
          description: "OpenDocument Presentation File Format"

        # format loop
        - name: "Compare OTP Files"
          link: "https://products.groupdocs.com/comparison/net/otp/"
          description: "Origin Graph Template"

        # format loop
        - name: "Compare ODT Files"
          link: "https://products.groupdocs.com/comparison/net/odt/"
          description: "Open Document Text"

        # format loop
        - name: "Compare OTT Files"
          link: "https://products.groupdocs.com/comparison/net/ott/"
          description: "Open Document Template"

        # format loop
        - name: "Compare VST Files"
          link: "https://products.groupdocs.com/comparison/net/vst/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare JPEG Files"
          link: "https://products.groupdocs.com/comparison/net/jpeg/"
          description: "JPEG Image"

        # format loop
        - name: "Compare PNG Files"
          link: "https://products.groupdocs.com/comparison/net/png/"
          description: "Portable Network Graphic"

        # format loop
        - name: "Compare GIF Files"
          link: "https://products.groupdocs.com/comparison/net/gif/"
          description: "Graphical Interchange Format File"

        # format loop
        - name: "Compare BMP Files"
          link: "https://products.groupdocs.com/comparison/net/bmp/"
          description: "Bitmap File Format"

        # format loop
        - name: "Compare HTML Files"
          link: "https://products.groupdocs.com/comparison/net/html/"
          description: "Hyper Text Markup Language"

        # format loop
        - name: "Compare MHT Files"
          link: "https://products.groupdocs.com/comparison/net/mht/"
          description: "Mime HTML"

        # format loop
        - name: "Compare MHTML Files"
          link: "https://products.groupdocs.com/comparison/net/mhtml/"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop
        - name: "Compare MSG Files"
          link: "https://products.groupdocs.com/comparison/net/msg/"
          description: "Microsoft Outlook E-mail Message"

        # format loop
        - name: "Compare EML Files"
          link: "https://products.groupdocs.com/comparison/net/eml/"
          description: "E-mail Message"

        # format loop
        - name: "Compare EMLX Files"
          link: "https://products.groupdocs.com/comparison/net/emlx/"
          description: "Apple Mail E-mail File"

        # format loop
        - name: "Compare ONE Files"
          link: "https://products.groupdocs.com/comparison/net/one/"
          description: "Microsoft OneNote"

        # format loop
        - name: "Compare VSD Files"
          link: "https://products.groupdocs.com/comparison/net/vsd/"
          description: "Microsoft Visio 2003-2010 Drawing"

        # format loop
        - name: "Compare VSDX Files"
          link: "https://products.groupdocs.com/comparison/net/vsdx/"
          description: "Microsoft Visio Drawing"

        # format loop
        - name: "Compare VSS Files"
          link: "https://products.groupdocs.com/comparison/net/vss/"
          description: "Microsoft Visio 2003-2010 Stencil"

        # format loop
        - name: "Compare VST Files"
          link: "https://products.groupdocs.com/comparison/net/vst/"
          description: "Microsoft Visio 2003-2010 Template"

        # format loop
        - name: "Compare VDX Files"
          link: "https://products.groupdocs.com/comparison/net/vdx/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare CS Files"
          link: "https://products.groupdocs.com/comparison/net/cs/"
          description: "CSharp Language"

        # format loop
        - name: "Compare Java Files"
          link: "https://products.groupdocs.com/comparison/net/java/"
          description: "Java Language"

        # format loop
        - name: "Compare CPP Files"
          link: "https://products.groupdocs.com/comparison/net/cpp/"
          description: "C++ Language"

        # format loop
        - name: "Compare JS Files"
          link: "https://products.groupdocs.com/comparison/net/js/"
          description: "JavaScript Language"

        # format loop
        - name: "Compare PY Files"
          link: "https://products.groupdocs.com/comparison/net/py/"
          description: "Python Language"

        # format loop
        - name: "Compare RB Files"
          link: "https://products.groupdocs.com/comparison/net/rb/"
          description: "Ruby Language"

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison offers document viewing APIs for other popular formats"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for Java ONE"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/one/"

############################# Back to top ###############################
back_to_top:
    enable: true
---
