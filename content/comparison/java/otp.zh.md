
---
############################# Static ############################
layout: "auto-gen-comparison"
date: 2021-05-13T12:45:19+03:00
draft: false

############################# Head ############################
head_title: "Java OTP 比较 API - 比较 OTP 文件的差异"
head_description: "比较和合并 Java、J2EE、J2SE 应用程序中的 OTP 文件。分析 OTP 文件、图像和文档格式在内容、文本和样式方面的差异摘要。"

############################# Header ############################
title: "在Java中比较OTP文件"
description: "在 Java 中对两个以上的 OTP 文件进行逐行比较。检索差异列表并将比较的文件保存到单个文档中。"
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "下载免费试用版"
    link: "https://downloads.groupdocs.com/comparison/java"

############################# SubMenu ############################
submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Comparison for Java"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-comparison-java.png"
        product: "GroupDocs.Comparison"
        platform: "爪哇"

    middle:
        button: 
            # 按钮循环
            - link: "https://apireference.groupdocs.com/comparison/java"
              text: "API 参考"

            # 按钮循环
            - link: "https://github.com/groupdocs-comparison"
              text: "代码示例"

            # 按钮循环
            - link: "https://products.groupdocs.app/comparison/family"
              text: "现场演示"

            # 按钮循环
            - link: "https://purchase.groupdocs.com/pricing/comparison/java"
              text: "定价"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/java"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: "关于 GroupDocs.Comparison for Java API"
    content: |
        使用 [GroupDocs.Comparison for Java](/zh/comparison/java/) API 为您的 Java 应用程序提供图像和文档比较功能。它可以帮助您识别段落、单词、字符、形状之间的差异，甚至是相同格式的比较文档的文本样式，允许合并更改并导出到最终文档。它支持比较和合并各种文档，包括 PDF、Word、Excel 工作表、PowerPoint 演示文稿、Visio 图表、Outlook 电子邮件、HTML、绘图和图像文件格式，而无需使用任何外部库。

############################# Steps ############################
steps:
    enable: true
    title_left: "在 Java 中比较 OTP 文件的步骤"
    content_left: |
        [GroupDocs.Comparison](/comparison/java/) 使 Java 开发人员可以使用几行代码轻松比较其应用程序中的 OTP 文件。
        *   使用源文档路径或流实例化 **Comparer** 对象。
        * 调用add方法并指定目标文档路径或流。
        * 调用比较方法。
    title_right: "系统要求"
    content_right: |
        所有主要平台和操作系统都支持 Java API 的 GroupDocs.Comparison。在执行下面的代码之前，请确保您的系统上安装了以下先决条件。
        *   操作系统：Microsoft Windows、Linux、MacOS
        * 开发环境：NetBeans、Intellij IDEA、Eclipse等
        * Java运行环境：J2SE 6.0及以上
        * 从 [Maven](https://repository.groupdocs.com/webapp/#/artifacts/browse/tree/General/repo/com/groupdocs/groupdocs-comparison) 获取最新版本的 GroupDocs.Comparison for Java
    code: |
        ```java
        // 比较本地文件中的文档
        
        try (Comparer comparer = new Comparer("C:\\source.otp")) {
            comparer.add("C:\\target.otp");
            comparer.compare("C:\\result.otp"); // 创建指定名称的结果文件
        }
        
        // 比较流中的文档
        
        try (Comparer comparer = new Comparer(new FileInputStream("C:\\source.otp"))) {
            comparer.add(new FileInputStream("C:\\target.otp"));
            comparer.compare(new FileOutputStream("C:\\result.otp")); // 创建指定名称的结果文件
        }
        ```

############################# Demos ############################
demos:
    enable: true
    title: "比较 OTP 文件的现场演示"
    content: |
        立即访问 [GroupDocs.Comparison Live Demos](https://products.groupdocs.app/comparison/family) 网站比较 OTP 文件。
        现场演示有以下好处

############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-otp"
          title: "关于 OTP 文件格式"
          content: |
            带有 .OTP 扩展名的文件代表应用程序以 OASIS OpenDocument 标准格式创建的演示文稿模板文件。此类文件的内容包括幻灯片形式的演示信息，其中包含文本、图像、形状、多媒体内容、过渡效果和其他幻灯片元素。这些模板文件用于根据存储在模板本身中的样式信息快速创建新的演示文稿。 OTP 文件可以使用几个不同的应用程序创建和保存，例如 OpenOffice 套件和 Microsoft PowerPoint 附带的 Impress。 OTP 文件格式类似于 Microsoft PowerPoint 模板文件 .POT 和 .POTX。
          link: "https://docs.fileformat.com/image/otp/"

############################# More Formats ############################
more_formats:
    enable: true
    title: "比较其他文件格式"
    content: |
        用于 Java 的多格式图像和文档比较 API。在没有任何外部软件的情况下比较以下一些流行的文件格式。
    format: 
        # format loop
        - name: "Compare PDF Files"
          link: "https://products.groupdocs.com/comparison/java/pdf/"
          description: "Adobe Portable Document Format"

        # format loop
        - name: "Compare DOC Files"
          link: "https://products.groupdocs.com/comparison/java/doc/"
          description: "Microsoft Word Document"

        # format loop
        - name: "Compare DOCM Files"
          link: "https://products.groupdocs.com/comparison/java/docm/"
          description: "Microsoft Word Macro-Enabled Document"

        # format loop
        - name: "Compare DOCX Files"
          link: "https://products.groupdocs.com/comparison/java/docx/"
          description: "Microsoft Word Open XML Document"

        # format loop
        - name: "Compare DOT Files"
          link: "https://products.groupdocs.com/comparison/java/dot/"
          description: "Microsoft Word Document Template"

        # format loop
        - name: "Compare DOTM Files"
          link: "https://products.groupdocs.com/comparison/java/dotm/"
          description: "Microsoft Word Macro-Enabled Template"

        # format loop
        - name: "Compare DOTX Files"
          link: "https://products.groupdocs.com/comparison/java/dotx/"
          description: "Word Open XML Document Template"

        # format loop
        - name: "Compare RTF Files"
          link: "https://products.groupdocs.com/comparison/java/rtf/"
          description: "Rich Text File Format"

        # format loop
        - name: "Compare TXT Files"
          link: "https://products.groupdocs.com/comparison/java/txt/"
          description: "Plain Text File Format"

        # format loop
        - name: "Compare XLS Files"
          link: "https://products.groupdocs.com/comparison/java/xls/"
          description: "Microsoft Excel Binary File Format"

        # format loop
        - name: "Compare XLSX Files"
          link: "https://products.groupdocs.com/comparison/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop
        - name: "Compare XLTM Files"
          link: "https://products.groupdocs.com/comparison/java/xltm/"
          description: "Microsoft Excel macro-enabled template"

        # format loop
        - name: "Compare XLSM Files"
          link: "https://products.groupdocs.com/comparison/java/xlsm/"
          description: "Microsoft Excel Macro-Enabled Spreadsheet"

        # format loop
        - name: "Compare XLSB Files"
          link: "https://products.groupdocs.com/comparison/java/xlsb/"
          description: "Microsoft Excel Binary Spreadsheet File"

        # format loop
        - name: "Compare CSV Files"
          link: "https://products.groupdocs.com/comparison/java/csv/"
          description: "Comma Separated Values File"

        # format loop
        - name: "Compare PPT Files"
          link: "https://products.groupdocs.com/comparison/java/ppt/"
          description: "PowerPoint Presentation"

        # format loop
        - name: "Compare PPS Files"
          link: "https://products.groupdocs.com/comparison/java/pps/"
          description: "Microsoft PowerPoint Slide Show"

        # format loop
        - name: "Compare PPTX Files"
          link: "https://products.groupdocs.com/comparison/java/pptx/"
          description: "PowerPoint Open XML Presentation"

        # format loop
        - name: "Compare PPSX Files"
          link: "https://products.groupdocs.com/comparison/java/ppsx/"
          description: "PowerPoint Open XML Slide Show"

        # format loop
        - name: "Compare POT Files"
          link: "https://products.groupdocs.com/comparison/java/pot/"
          description: "Microsoft PowerPoint template"

        # format loop
        - name: "Compare POTX Files"
          link: "https://products.groupdocs.com/comparison/java/potx/"
          description: "Microsoft PowerPoint Open XML Template"

        # format loop
        - name: "Compare ODS Files"
          link: "https://products.groupdocs.com/comparison/java/ods/"
          description: "Open Document Spreadsheet"

        # format loop
        - name: "Compare ODP Files"
          link: "https://products.groupdocs.com/comparison/java/odp/"
          description: "OpenDocument Presentation File Format"

        # format loop
        - name: "Compare OTP Files"
          link: "https://products.groupdocs.com/comparison/java/otp/"
          description: "Origin Graph Template"

        # format loop
        - name: "Compare ODT Files"
          link: "https://products.groupdocs.com/comparison/java/odt/"
          description: "Open Document Text"

        # format loop
        - name: "Compare OTT Files"
          link: "https://products.groupdocs.com/comparison/java/ott/"
          description: "Open Document Template"

        # format loop
        - name: "Compare VST Files"
          link: "https://products.groupdocs.com/comparison/java/vst/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare JPEG Files"
          link: "https://products.groupdocs.com/comparison/java/jpeg/"
          description: "JPEG Image"

        # format loop
        - name: "Compare PNG Files"
          link: "https://products.groupdocs.com/comparison/java/png/"
          description: "Portable Network Graphic"

        # format loop
        - name: "Compare GIF Files"
          link: "https://products.groupdocs.com/comparison/java/gif/"
          description: "Graphical Interchange Format File"

        # format loop
        - name: "Compare BMP Files"
          link: "https://products.groupdocs.com/comparison/java/bmp/"
          description: "Bitmap File Format"

        # format loop
        - name: "Compare HTML Files"
          link: "https://products.groupdocs.com/comparison/java/html/"
          description: "Hyper Text Markup Language"

        # format loop
        - name: "Compare MHT Files"
          link: "https://products.groupdocs.com/comparison/java/mht/"
          description: "Mime HTML"

        # format loop
        - name: "Compare MHTML Files"
          link: "https://products.groupdocs.com/comparison/java/mhtml/"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop
        - name: "Compare MSG Files"
          link: "https://products.groupdocs.com/comparison/java/msg/"
          description: "Microsoft Outlook E-mail Message"

        # format loop
        - name: "Compare EML Files"
          link: "https://products.groupdocs.com/comparison/java/eml/"
          description: "E-mail Message"

        # format loop
        - name: "Compare EMLX Files"
          link: "https://products.groupdocs.com/comparison/java/emlx/"
          description: "Apple Mail E-mail File"

        # format loop
        - name: "Compare ONE Files"
          link: "https://products.groupdocs.com/comparison/java/one/"
          description: "Microsoft OneNote"

        # format loop
        - name: "Compare VSD Files"
          link: "https://products.groupdocs.com/comparison/java/vsd/"
          description: "Microsoft Visio 2003-2010 Drawing"

        # format loop
        - name: "Compare VSDX Files"
          link: "https://products.groupdocs.com/comparison/java/vsdx/"
          description: "Microsoft Visio Drawing"

        # format loop
        - name: "Compare VSS Files"
          link: "https://products.groupdocs.com/comparison/java/vss/"
          description: "Microsoft Visio 2003-2010 Stencil"

        # format loop
        - name: "Compare VST Files"
          link: "https://products.groupdocs.com/comparison/java/vst/"
          description: "Microsoft Visio 2003-2010 Template"

        # format loop
        - name: "Compare VDX Files"
          link: "https://products.groupdocs.com/comparison/java/vdx/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare CS Files"
          link: "https://products.groupdocs.com/comparison/java/cs/"
          description: "CSharp Language"

        # format loop
        - name: "Compare Java Files"
          link: "https://products.groupdocs.com/comparison/java/java/"
          description: "Java Language"

        # format loop
        - name: "Compare CPP Files"
          link: "https://products.groupdocs.com/comparison/java/cpp/"
          description: "C++ Language"

        # format loop
        - name: "Compare JS Files"
          link: "https://products.groupdocs.com/comparison/java/js/"
          description: "JavaScript Language"

        # format loop
        - name: "Compare PY Files"
          link: "https://products.groupdocs.com/comparison/java/py/"
          description: "Python Language"

        # format loop
        - name: "Compare RB Files"
          link: "https://products.groupdocs.com/comparison/java/rb/"
          description: "Ruby Language"

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison offers document viewing APIs for other popular formats"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for .NET OTP"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
          product: "GroupDocs.Comparison"
          platform: ".NET"
          link: "/comparison/net/otp/"

############################# Back to top ###############################
back_to_top:
    enable: true
---
