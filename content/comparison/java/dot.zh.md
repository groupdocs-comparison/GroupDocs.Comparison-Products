---
############################# Static ############################
layout: "auto-gen-comparison"
date: 2021-05-13T12:45:19+03:00
draft: false

############################# Head ############################
head_title: "Java DOT 比較 API - 比較 DOT 文件的差異"
head_description: "比較並合併 Java、J2EE、J2SE 應用程序中的 DOT 文件。分析 DOT 文件、圖像和文檔格式的內容、文本和風格的差異摘要。"

############################# Header ############################
title: "在 Java 中比較 DOT 文件"
description: "在 Java 中對兩個以上的 DOT 文件進行逐行比較。檢索差異列表並將比較的文件保存到單個文檔中。"
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "下載免費試用版"
    link: "https://downloads.groupdocs.com/comparison/java"

############################# SubMenu ############################
submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Comparison for Java"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-comparison-java.png"
        product: "GroupDocs.Comparison"
        platform: "Java"

    middle:
        button: 
            # button loop
            - link: "https://apireference.groupdocs.com/comparison/java"
              text: "API參考"

            # button loop
            - link: "https://github.com/groupdocs-comparison"
              text: "代碼示例"

            # button loop
            - link: "https://products.groupdocs.app/comparison/family"
              text: "現場演示"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/java"
              text: "價錢"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/java"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: "關於 GroupDocs.Comparison for Java API"
    content: |
        使用 [GroupDocs.Comparison for Java](/comparison/java/) API 為您的 Java 應用程序提供圖像和文檔比較功能。它可以幫助您識別相同格式的比較文檔的段落、單詞、字符、形狀甚至文本樣式之間的差異，允許合併更改並導出到最終文檔。它支持比較和合併各種文檔，包括 PDF、Word、Excel 工作表、PowerPoint 演示文稿、Visio 圖表、Outlook 電子郵件、HTML、繪圖和圖像文件格式，而無需使用任何外部庫。

############################# Steps ############################
steps:
    enable: true
    title_left: "在 Java 中比較 DOT 文件的步驟"
    content_left: |
        [GroupDocs.Comparison](/comparison/java/) 使 Java 開發人員可以使用幾行代碼輕鬆比較應用程序中的 DOT 文件。
        * 使用源文檔路徑或流實例化 **Comparer** 對象。
        * 調用add方法並指定目標文檔路徑或流。
        * 調用比較方法。
    title_right: "系統要求"
    content_right: |
        所有主要平台和操作系統均支持 GroupDocs.Comparison for Java API。在執行下面的代碼之前，請確保您的系統上安裝了以下先決條件。
        * 操作系統：Microsoft Windows、Linux、MacOS
        * 開發環境：NetBeans, Intellij IDEA, Eclipse etc
        * Java運行環境：J2SE 6.0及以上
        * 從 [Maven](https://repository.groupdocs.com/webapp/#/artifacts/browse/tree/General/repo/com/groupdocs/groupdocs-comparison) 獲取最新版本的 GroupDocs.Comparison for Java
    code: |
        ```java
        // 比較本地文件中的文檔
        
        try (Comparer comparer = new Comparer("C:\\source.dot")) {
            comparer.add("C:\\target.dot");
            comparer.compare("C:\\result.dot"); // 創建指定名稱的結果文件
        }
        
        // 比較流中的文檔
        
        try (Comparer comparer = new Comparer(new FileInputStream("C:\\source.dot"))) {
            comparer.add(new FileInputStream("C:\\target.dot"));
            comparer.compare(new FileOutputStream("C:\\result.dot")); // 創建指定名稱的結果文件
        }
        ```

############################# Demos ############################
demos:
    enable: true
    title: "比較 DOT 文件的現場演示"
    content: |
        立即訪問 [GroupDocs.Comparison Live Demos](https://products.groupdocs.app/comparison/family) 網站比較 DOT 文件。
        現場演示有以下好處

############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-dot"
          title: "關於 DOT 文件格式"
          content: |
            擴展名為 .DOT 的文件是由 Microsoft Word 創建的模板文件，具有用於生成更多 DOC 或 DOCX 文件的預格式化設置。創建模板文件是為了具有應應用於從這些文件創建的後續文件的特定用戶設置。這些設置包括頁邊距、邊框、頁眉、頁腳和其他頁面設置。此類模板用於官方文件，例如公司信頭和標準化表格。 DOT 文件格式特定於 Microsoft Word 2003 及更早版本，但更高版本也支持。默認情況下，Microsoft Word 基於 normal.dot 文件打開每個新文檔。如果進行修改，創建的所有新文件將產生與模板文件相同的設置。在 Microsoft Word 2007 中，DOT 文件格式已替換為基於 Office OpenXML 的 DOTX 文件格式。
          link: "https://docs.fileformat.com/image/dot/"

############################# More Formats ############################
more_formats:
    enable: true
    title: "比較其他文件格式"
    content: |
        適用於 Java 的多格式圖像和文檔比較 API。無需任何外部軟件即可比較以下一些流行的文件格式。
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
    title: "GroupDocs.Comparison 為其他流行的開發環境提供文檔查看 API"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for .NET DOT"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
          product: "GroupDocs.Comparison"
          platform: ".NET"
          link: "/comparison/net/dot/"

############################# Back to top ###############################
back_to_top:
    enable: true
---
