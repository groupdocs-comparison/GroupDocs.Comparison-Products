---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "C# .NET 文檔比較 API |比較和合併 PDF Word Excel Web 和文本"
head_description: "C# .NET 文檔比較 API。比較和合併 PDF、Word DOC DOCX、Excel 電子表格、PPT、PPTX、HTML、EMLX MSG、VSDX、DXF DWG 和圖像文件格式。"

############################# Header ############################
title: "用於比較文件的 .NET API"
description: "使用 .NET 文檔比較 API 開發應用程序來檢查和比較文件的內容和風格差異。"
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
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
        product: "GroupDocs.Comparison"
        platform: ".NET"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "概述"

            # button loop
            - link: "#features"
              text: "特徵"

            # button loop
            - link: "#support"
              text: "支持"

            # button loop
            - link: "https://products.groupdocs.app/comparison"
              text: "現場演示"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "價錢"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    example_image: "/comparison/comparison-example.png"
    content: |
      
    more_overview:
      # more_overview_loop
      - title: "什麼是 GroupDocs.Comparison for .NET"
        content: "GroupDocs.Comparison for .NET API 是一種快速可靠的解決方案，可在創建用於搜索和突出顯示C#、ASP.NET 或與.NET 軟件平台相關的其他技術中相同或不同格式的文檔之間的差異的應用程序時使用。"

      # more_overview_loop
      - title: "支持的格式"
        content: "GroupDocs.Comparison 庫支持檢測流行圖像和文檔格式（例如PDF、HTML、電子郵件Outlook、Microsoft Office Word 文檔、Excel 電子表格、PowerPoint 演示文稿、OneNote、Visio 圖表、文本、png）之間內容和文本樣式的差異、gif 和 bmp 圖像以及一百種其他格式。"
        
      # more_overview_loop
      - title: "比較能力"
        content: "可以執行比較來檢測單詞、段落、表格或圖表的內容及其樣式的變化，並為您提供比較文檔，其中列出了差異的摘要、數量和類型所屬。 GroupDocs.Comparison for .NET可以輕鬆提取源文檔的基本信息，通過文件或數據流比較和保存各種格式的簡單、受密碼保護和加密的文檔。"
        
      # more_overview_loop
      - title: "文檔和示例"
        content: "已經有很多關於在不同平台上使用 Comparison 庫的文檔和代碼示例，因此您不必費力思考如何在應用程序中使用 GroupDocs.Comparison for .NET API。"
        
      # more_overview_loop
      - title: "兼容性"
        content: "您可以使用 GroupDocs.Comparison for .NET 在任何面向 .NET 平台的開發環境中創建應用程序。它與所有基於 .NET 的語言兼容，並支持流行的操作系統（Windows、Linux、MacOS），您可以在這些操作系統上安裝 Mono 或 .NET 框架（包括 .NET Core）。"
    examples:
      enable: true
      
    more_feature:
      # more_feature_loop
      - title: "使用 .NET API 輕鬆比較文檔"
        content: |
          GroupDocs.Comparison for .NET API 為您提供了一種簡單有效的方法來比較文件。以下示例展示瞭如何使用 C# 比較兩個 DOCX 文檔：  

          ```cs
          // 要比較的源文件和目標文件
          string source = @"source.docx";
          string target = @"target.docx";
          Comparer comparer = new Comparer();
          // 比較兩個文檔
          ICompareResult result = comparer.Compare(source, target, new ComparisonSettings());
          ```
      # more_feature_loop
      - title: "選擇比較的詳細程度"
        content: "使用 GroupDocs.Comparison for .NET 您可以指定要比較文檔的範圍。您可以選擇低（逐字比較文本與成像網格的準確度= 50）、中（逐字符比較文本與成像網格的準確度= 100）或高（逐字符比較文本與成像網格的準確度= 100） 150）。"

      # more_feature_loop
      - title: "支持文本樣式比較"
        content: |
          GroupDocs.Comparison for .NET 提供比較文本樣式的功能。  

          在比較文檔的文字和字符時，可以比較字體名稱、字體大小、字體顏色、字體樣式（粗體、斜體、下劃線、小型大寫字母、超鏈接）和下劃線顏色（如果適用）以查找差異。  

          比較段落時，您可以比較段落對齊、縮進（左縮進、右縮進）、段落間距（前後空格）、首行縮進和行距等樣式。  

          GroupDocs.Comparison for .NET 還支持比較頁面的其他部分（如果適用），例如頁腳距離、頁面高度和方向、邊距（左、右、上、下）、邊框線寬度和邊框顏色。  
      
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          以下是 GroupDocs.Comparison for .NET 的概述：
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "概述"
          content: |
            * 文檔比較
            * HTML 文件比較
            * PDF比較
            * 圖表比較
            * 比較文件內容
            * 比較文本樣式
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison for .NET 支持所有流行的[文檔文件格式](https://docs.groupdocs.com/comparison/net/supported-document-formats/)，包括：Microsoft Office、PDF、圖像等。
        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** [DOC](https://products.groupdocs.com/comparison/net/doc/), [DOCX](https://products.groupdocs.com/comparison/net/docx/), [DOCM](https://products.groupdocs.com/comparison/net/docm/), [DOT](https://products.groupdocs.com/comparison/net/dot/), [DOTX](https://products.groupdocs.com/comparison/net/dotx/), [DOTM](https://products.groupdocs.com/comparison/net/dotm/), [RTF](https://products.groupdocs.com/comparison/net/rtf/), [TXT](https://products.groupdocs.com/comparison/net/txt/)
                * **Excel:** [XLS](https://products.groupdocs.com/comparison/net/xls/), [XLSX](https://products.groupdocs.com/comparison/net/xlsx/), [XLSM](https://products.groupdocs.com/comparison/net/xlsm/), [XLSB](https://products.groupdocs.com/comparison/net/xlsb/), [XLTM](https://products.groupdocs.com/comparison/net/xltm/), [XLT](https://products.groupdocs.com/comparison/net/xlt/), [XLTM](https://products.groupdocs.com/comparison/net/xltm/), [XLTX](https://products.groupdocs.com/comparison/net/xltx/), [XLAM](https://products.groupdocs.com/comparison/net/xlam/), [SXC](https://products.groupdocs.com/comparison/net/sxc/), [SpreadsheetML](https://products.groupdocs.com/comparison/net/xml/)
                * **PowerPoint:** [PPT](https://products.groupdocs.com/comparison/net/ppt/), [PPTX](https://products.groupdocs.com/comparison/net/pptx/), [PPS](https://products.groupdocs.com/comparison/net/pps/), [PPSX](https://products.groupdocs.com/comparison/net/ppsx/), [PPSM](https://products.groupdocs.com/comparison/net/ppsm/), [POT](https://products.groupdocs.com/comparison/net/pot/), [POTM](https://products.groupdocs.com/comparison/net/potm/), [POTX](https://products.groupdocs.com/comparison/net/potx/), [PPTM](https://products.groupdocs.com/comparison/net/pptm/)
                * **Visio:** [VSD](https://products.groupdocs.com/comparison/net/vsd/), [VDX](https://products.groupdocs.com/comparison/net/vdx/), [VSS](https://products.groupdocs.com/comparison/net/vss/), [VSSX](https://products.groupdocs.com/comparison/net/vssx/), [VSX](https://products.groupdocs.com/comparison/net/vsx/), [VST](https://products.groupdocs.com/comparison/net/vst/), [VSTX](https://products.groupdocs.com/comparison/net/vstx/), [VTX](https://products.groupdocs.com/comparison/net/vtx/), [VSDX](https://products.groupdocs.com/comparison/net/vsdx/), [VDW](https://products.groupdocs.com/comparison/net/vdw/), [VSTM](https://products.groupdocs.com/comparison/net/vstm/), [VSSM](https://products.groupdocs.com/comparison/net/vssm/), [VSDM](https://products.groupdocs.com/comparison/net/vsdm/)
                * **Outlook:** [MSG](https://products.groupdocs.com/comparison/net/msg/), [EML](https://products.groupdocs.com/comparison/net/eml/), [EMLX](https://products.groupdocs.com/comparison/net/emlx/), [PST](https://products.groupdocs.com/comparison/net/pst/), [OST](https://products.groupdocs.com/comparison/net/ost/)
                * **OneNote:** [ONE](https://products.groupdocs.com/comparison/net/one/)

        right:
          enable: true
          table:
            # table loop
            - title: "其他格式"
              content: |
                * **編程語言**: [CS](https://products.groupdocs.com/comparison/net/cs/), [Java](https://products.groupdocs.com/comparison/net/java/), [CPP](https://products.groupdocs.com/comparison/net/cpp/), [JS](https://products.groupdocs.com/comparison/net/js/), [PY](https://products.groupdocs.com/comparison/net/py/), [RB](https://products.groupdocs.com/comparison/net/rb/), [PL](https://products.groupdocs.com/comparison/net/pl/), [ASM](https://products.groupdocs.com/comparison/net/asm/), [GROOVY](https://products.groupdocs.com/comparison/net/groovy/), [JSON](https://products.groupdocs.com/comparison/net/json/), [PHP](https://products.groupdocs.com/comparison/net/php/), [SQL](https://products.groupdocs.com/comparison/net/sql/), [LOG](https://products.groupdocs.com/comparison/net/log/), [DIFF](https://products.groupdocs.com/comparison/net/diff/), [LESS](https://products.groupdocs.com/comparison/net/less/), [SCALA](https://products.groupdocs.com/comparison/net/scala/)
                * **OpenDocument**: [ODT](https://products.groupdocs.com/comparison/net/odt/), [OTT](https://products.groupdocs.com/comparison/net/ott/), [ODS](https://products.groupdocs.com/comparison/net/ods/), [ODP](https://products.groupdocs.com/comparison/net/odp/), [OTP](https://products.groupdocs.com/comparison/net/otp/)
                * **Portable**: [PDF](https://products.groupdocs.com/comparison/net/pdf/), [MOBI](https://products.groupdocs.com/comparison/net/mobi/)
                * **AutoCAD**: [DXF](https://products.groupdocs.com/comparison/net/dxf/), [DWG](https://products.groupdocs.com/comparison/net/dwg/)
                * **Email**: [EML](https://products.groupdocs.com/comparison/net/eml/), [EMLX](https://products.groupdocs.com/comparison/net/emlx/), [MSG](https://products.groupdocs.com/comparison/net/msg/)
                * **Images**: [JPEG](https://products.groupdocs.com/comparison/net/jpeg/), [BMP](https://products.groupdocs.com/comparison/net/bmp/), [PNG](https://products.groupdocs.com/comparison/net/png/), [GIF](https://products.groupdocs.com/comparison/net/gif/), [DCM](https://products.groupdocs.com/comparison/net/dcm/), [DICOM](https://products.groupdocs.com/comparison/net/dicom/), [DjVu](https://products.groupdocs.com/comparison/net/djvu/)
                * **Web**: [HTM](https://products.groupdocs.com/comparison/net/htm/), [HTML](https://products.groupdocs.com/comparison/net/html/), [MHTML](https://products.groupdocs.com/comparison/net/mhtml/)
                * **Text**: [TXT](https://products.groupdocs.com/comparison/net/txt/)

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Comparison for .NET 支持以下操作系統、框架和包管理器：
      
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "操作系統"
              content: |
                * Windows Desktop
                * Windows Server
                * Windows Azure
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "支持的框架"
              content: |
                * .NET Framework 2.0 或更高
                * Mono Framework 1.2 或更高
                * .NET Standard 2.0
                * .NET Core 2.0

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "包管理器"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "開發環境"
              content: |
                * Microsoft Visual Studio
                * Xamarin.Android
                * Xamarin.IOS
                * Xamarin.Mac
                * MonoDevelop

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Comparison for .NET 功能"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "[識別內容和字體樣式的差異](https://docs.groupdocs.com/comparison/net/compare-documents/)"

      # feature loop
      - icon: "fas fa-eye"
        content: "[保存文件比較後發現的所有差異的匯總報告](https://docs.groupdocs.com/comparison/net/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-bolt"
        content: "[分析差異並導出結果文件後應用或拒絕更改](https://docs.groupdocs.com/comparison/net/accept-or-reject-detected-changes/)"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "[比較 Word 文件時支持 Microsoft Word“跟踪更改”功能](https://docs.groupdocs.com/comparison/net/show-revisions/)"

      # feature loop
      - icon: "fas fa-code"
        content: "[獨特地發現來自所比較的每個文檔的變化](https://docs.groupdocs.com/comparison/net/get-list-of-changes/)"

      # feature loop
      - icon: "fas fa-cloud"
        content: "[通過流讀取和發送文檔](https://docs.groupdocs.com/comparison/net/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "[計量許可 – 根據 API 使用情況計費](https://docs.groupdocs.com/comparison/net/licensing-and-evaluation-limitations/)"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "[將多個源文檔與單個目標文檔進行比較](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/)"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "[相互比較 Word 文件的特定頁面 – 接受或拒絕單個 Word 文檔中的所有更改](https://docs.groupdocs.com/comparison/net/accept-or-reject-detected-changes/)"

      # feature loop
      - icon: "fas fa-border-all"
        content: "[合併最多 3 個 Word 文檔並比較 Word 文件中使用的公式](https://docs.groupdocs.com/comparison/net/how-to-merge-source-code-files/)"

      # feature loop
      - icon: "fas fa-wrench"
        content: "[從 filePath 獲取有關文檔的信息](https://docs.groupdocs.com/comparison/net/get-file-info/)"

      # feature loop
      - icon: "fas fa-columns"
        content: "[將 HTML 比較結果另存為圖像](https://docs.groupdocs.com/comparison/net/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-file-word"
        content: "[顯示或隱藏已刪除內容的選項](https://docs.groupdocs.com/comparison/net/show-gap-lines/)"

      # feature loop
      - icon: "fas fa-envelope"
        content: "[打開或關閉文檔樣式比較的選項](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fas fa-print"
        content: "[指定字符串以標記比較文檔中的插入、刪除和样式更改項目](https://docs.groupdocs.com/comparison/net/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "[指定單詞分隔符和字體顏色以風格化比較文本](https://docs.groupdocs.com/comparison/net/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-lock"
        content: "[計算 PDF、Word、PowerPoint 幻燈片和圖表中變化的正確坐標](https://docs.groupdocs.com/comparison/net/get-changes-coordinates/)"

      # feature loop
      - icon: "fas fa-file-code"
        content: "[比較受密碼保護的文件](https://docs.groupdocs.com/comparison/net/how-to-compare-password-protected-files/)"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "[比較電子表格中的圖表標題 - 在結果單元格文件中生成圖表](https://docs.groupdocs.com/comparison/net/how-to-compare-spreadsheet-or-tables/)"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "[自動調整單元格文檔結果文件中的自動形狀大小](https://docs.groupdocs.com/comparison/net/how-to-compare-spreadsheet-or-tables/)"

      # feature loop
      - icon: "fas fa-heading"
        content: "[訪問詳細摘要頁面以檢測源文檔文件和目標文檔文件之間的更改](https://docs.groupdocs.com/comparison/net/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "[比較最流行的編程和腳本語言文件](https://docs.groupdocs.com/comparison/net/get-supported-document-formats/)"

      # feature loop
      - icon: "fas fa-cube"
        content: "[比較多個（兩個以上）PDF、Word、Excel、圖表、電子郵件、文本和 OneNote 文檔](https://docs.groupdocs.com/comparison/net/compare-multiple-documents-with-specific-compare-settings/)"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "[比較支持的文件格式的頁眉和頁腳](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "[比較 Word 文檔格式的書籤、變量和自定義屬性](https://docs.groupdocs.com/comparison/net/compare-bookmarks-in-word/)"

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison 為其他流行的開發環境提供文檔查看 API"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for Java"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---