---
############################# Static ############################
layout: "auto-gen-comparison"
date: 2021-05-13T12:45:19+03:00
draft: false

############################# Head ############################
head_title: "比較 .NET 中的兩個 JS 文件 |文檔比較 API"
head_description: "在 C# .NET 應用程序中比較並合併兩個以上的 JS 文件。檢索 JS 文件、圖像和文檔格式的內容、文本和样式的差異摘要。"

############################# Header ############################
title: "比較 C# .NET 中的 JS 文件"
description: ".NET 文檔比較 API 用於檢測兩個版本的 JS 文件之間的更改，並導出到最終文檔，其中包含所比較文檔之間差異的詳細摘要。"
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "下載免費試用版"
    link: "https://downloads.groupdocs.com/comparison/net"

############################# SubMenu ############################
submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Comparison for .NET"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-comparison-net.png"
        product: "GroupDocs.Comparison"
        platform: ".NET"

    middle:
        button: 
            # button loop
            - link: "https://apireference.groupdocs.com/comparison/net"
              text: "API參考"

            # button loop
            - link: "https://github.com/groupdocs-comparison"
              text: "代碼示例"

            # button loop
            - link: "https://products.groupdocs.app/comparison/family"
              text: "現場演示"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "價錢"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/net"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: "關於 GroupDocs.Comparison for .NET API"
    content: |
        [GroupDocs.Comparison for .NET](/comparison/net/) 是一個本機 .NET API，用於比較相同格式的多個圖像和文檔。它可以幫助您檢測比較文檔的段落、單詞、字符、形狀甚至文本樣式之間的差異，合併更改並導出到最終文檔。它支持比較和合併 PDF、Word 文檔、Excel 電子表格、PowerPoint 演示文稿、Visio 圖表、Outlook 電子郵件、HTML、繪圖和圖像文件格式，而無需使用任何外部庫。

############################# Steps ############################
steps:
    enable: true
    title_left: "在 C# 中比較 JS 文件的步驟"
    content_left: |
        [GroupDocs.Comparison](/comparison/net/) 使 .NET 開發人員可以通過實施幾個簡單的步驟輕鬆比較和合併應用程序中的多個 JS 文件。
        * 使用源文檔路徑或流實例化 **Comparer** 對象。
        * 調用Add方法並指定目標文檔路徑或流。對每個目標文檔重複此步驟。
        * 調用Compare方法。
    title_right: "系統要求"
    content_right: |
        所有主要平台和操作系統均支持 GroupDocs.Comparison for .NET API。在執行下面的代碼之前，請確保您的系統上安裝了以下先決條件。
        * 操作系統：Microsoft Windows、Linux、MacOS
        * 開發環境：Microsoft Visual Studio, Xamarin, MonoDevelop
        * 框架：.NET Framework、.NET Standard、.NET Core、Mono
        * 獲取從 [NuGet](https://www.nuget.org/packages/groupdocs.comparison) 下載的最新版本的 GroupDocs.Comparison for .NET
    code: |
        ```cs
        // 比較本地磁盤中的多個文檔
        
        using (Comparer comparer = new Comparer("source.js"))
        {
        	comparer.Add("target1.js");
            comparer.Add("target2.js");
            comparer.Add("target3.js");
            comparer.Compare("result.js"); // 創建指定名稱的結果文件
        }
        
        // 比較流中的多個文檔
        
        using (Comparer comparer = new Comparer(File.OpenRead("source.js")))
        {
        	comparer.Add(File.OpenRead("target1.js"));
            comparer.Add(File.OpenRead("target2.js"));
            comparer.Add(File.OpenRead("target3.js"));
            comparer.Compare(File.Create("result.js")); // 創建指定名稱的結果文件
        }
        ```

############################# Demos ############################
demos:
    enable: true
    title: "比較 JS 文件的現場演示"
    content: |
        立即訪問 [GroupDocs.Comparison Live Demos](https://products.groupdocs.app/comparison/family) 網站檢測 JS 文件之間的差異。
        現場演示有以下好處

############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-js"
          title: "關於 JS 文件格式"
          content: |
            JS (JavaScript) 是包含在網頁上執行的 JavaScript 代碼的文件。 JavaScript 文件以 .js 擴展名存儲。在 HTML 文檔中，您可以使用標籤嵌入 JavaScript 代碼或包含 JS 文件。與CSS文件類似，JS文件可以包含在多個HTML文檔中以實現代碼的可重用性。 JavaScript 可用於操作 HTML DOM。
          link: "https://docs.fileformat.com/image/js/"

############################# More Formats ############################
more_formats:
    enable: true
    title: "比較其他文件格式"
    content: |
        適用於 .NET 的多格式文檔和圖像比較 API。無需使用任何外部工具即可分析相同格式文檔之間的差異。
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
    title: "GroupDocs.Comparison 為其他流行的開發環境提供文檔查看 API"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for Java JS"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/js/"

############################# Back to top ###############################
back_to_top:
    enable: true
---
