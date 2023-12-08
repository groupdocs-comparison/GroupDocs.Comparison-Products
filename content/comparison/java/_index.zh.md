---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "Java 文檔比較 API |比較 PDF Word Excel HTML 的文本和样式"
head_description: "Java 文檔比較 API 用於比較和合併 Word Excel PPTX OpenOffice、Web、PDF、AutoCAD 和其他文件格式。將文檔與跟踪更改進行比較。"

############################# Header ############################
title: "用於比較文件的 Java API"
description: "創建 Java 應用程序以有效比較所有標准文檔和圖像文件格式的文件內容差異。"
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
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
        product: "GroupDocs.Comparison"
        platform: "Java"

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
            - link: "https://purchase.groupdocs.com/pricing/comparison/java"
              text: "價錢"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    example_image: "/comparison/comparison-example.webp"
    content: |
      
    more_overview:
      # more_overview_loop
      - title: "什麼是 GroupDocs.Comparison for Java"
        content: "GroupDocs.Comparison for Java 是最靈活且易於使用的 API，可幫助您在 Java 環境中開發文檔比較應用程序。差異檢查器和文檔合併 API 允許您檢測相似文檔格式之間內容以及文本樣式的變化和差異。"

      # more_overview_loop
      - title: "支持的格式"
        content: "GroupDocs.Comparison 庫支持檢測流行圖像和文檔格式（例如PDF、HTML、電子郵件Outlook、Microsoft Office Word 文檔、Excel 電子表格、PowerPoint 演示文稿、OneNote、Visio 圖表、文本、png）之間內容和文本樣式的差異、gif 和 bmp 圖像以及一百種其他格式。"
        
      # more_overview_loop
      - title: "比較能力"
        content: "可以執行比較來檢測單詞、段落、表格或圖表的內容及其樣式的變化，並為您提供比較文檔，其中列出了差異的摘要、數量和類型所屬。 GroupDocs.Comparison for Java可以輕鬆提取源文檔的基本信息，通過文件或數據流比較和保存各種格式的簡單、受密碼保護和加密的文檔。"
        
      # more_overview_loop
      - title: "文檔和示例"
        content: "已經有很多關於在不同平台上使用 Comparison 庫的文檔和代碼示例，因此您不必費力思考如何在應用程序中使用 GroupDocs.Comparison for Java API。"
        
      # more_overview_loop
      - title: "兼容性"
        content: "GroupDocs.Comparison for Java 不需要在系統中安裝任何外部軟件。它兼容所有版本的Java，並支持能夠運行Java運行環境的流行操作系統（Windows、Linux、MacOS）。"
    examples:
      enable: true
      
    more_feature:
      # more_feature_loop
      - title: "使用 Java API 輕鬆比較文檔"
        content: |
          通過 GroupDocs.Comparison for Java API，您可以輕鬆比較支持格式的文檔以找出它們之間的差異。以下示例顯示如何使用 Java 比較兩個 Microsoft Word 文檔：
          
          ```java
          try (Comparer comparer = new Comparer("D:\\source.pdf")) {
              comparer.add("D:\\target.pdf");
              comparer.compare("D:\\result.pdf");
          }
          ```
      # more_feature_loop
      - title: "指定比較詳細程度"
        content: "GroupDocs.Comparison for Java 允許您比較三個級別的文檔。您可以將比較強度設置為低（逐字比較文本與成像網格精度 = 50）、中（逐字符比較文本與成像網格精度 = 100）或高（逐字符比較文本與成像網格精度）網格= 150)。"

      # more_feature_loop
      - title: "比較文本樣式"
        content: "除了文檔內容之外，GroupDocs.Comparison for Java API 還允許比較文本樣式。

        在比較單詞和字符的同時，還可以比較字體名稱、大小、顏色、樣式（粗體、斜體、下劃線、小型大寫字母和超鏈接）以及下劃線顏色（如果適用），以檢查比較文檔之間的差異。  

        對於段落比較，還可以比較對齊方式、縮進（左縮進、右縮進）、間距（後空格、前空格）、首行縮進和行間距。  

        同樣，只要適用，頁面的其他部分也可以通過 GroupDocs.Comparison for Java API 進行比較。這些部分包括頁腳距離、頁邊距（左、右、上、下）、頁面高度、頁面方向、邊框顏色和線條寬度。"
      
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          以下是 GroupDocs.Comparison for Java 的概述：
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "概述"
          content: |
            * 比較內容和風格
            * 獲取比較摘要
            * 接受/拒絕 Word 中的更改
            * 合併和比較 3 個 Word 文件
            * 支持流
            * 通過流檢測文件類型
            * 比較受保護的文件
            * 比較加密文件
            * 將比較保存為圖像
            * 比較Word中的特定頁面
            * 比較PDF中的水印
            * 應用/放棄更改
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison for Java 支持所有流行的[文檔文件格式](https://docs.groupdocs.com/comparison/java/supported-document-formats/)，包括：Microsoft Office、圖像、圖表等。
        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** [DOC](https://products.groupdocs.com/comparison/java/doc/), [DOCX](https://products.groupdocs.com/comparison/java/docx/), [DOCM](https://products.groupdocs.com/comparison/java/docm/), [DOT](https://products.groupdocs.com/comparison/java/dot/), [DOTX](https://products.groupdocs.com/comparison/java/dotx/), [DOTM](https://products.groupdocs.com/comparison/java/dotm/), [RTF](https://products.groupdocs.com/comparison/java/rtf/), [TXT](https://products.groupdocs.com/comparison/java/txt/)
                * **Excel:** [XLS](https://products.groupdocs.com/comparison/java/xls/), [XLSX](https://products.groupdocs.com/comparison/java/xlsx/), [XLSM](https://products.groupdocs.com/comparison/java/xlsm/), [XLSB](https://products.groupdocs.com/comparison/java/xlsb/), [XLTM](https://products.groupdocs.com/comparison/java/xltm/), [XLT](https://products.groupdocs.com/comparison/java/xlt/), [XLTM](https://products.groupdocs.com/comparison/java/xltm/), [XLTX](https://products.groupdocs.com/comparison/java/xltx/), [XLAM](https://products.groupdocs.com/comparison/java/xlam/), [SXC](https://products.groupdocs.com/comparison/java/sxc/), [SpreadsheetML](https://products.groupdocs.com/comparison/java/xml/)
                * **PowerPoint:** [PPT](https://products.groupdocs.com/comparison/java/ppt/), [PPTX](https://products.groupdocs.com/comparison/java/pptx/), [PPS](https://products.groupdocs.com/comparison/java/pps/), [PPSX](https://products.groupdocs.com/comparison/java/ppsx/), [PPSM](https://products.groupdocs.com/comparison/java/ppsm/), [POT](https://products.groupdocs.com/comparison/java/pot/), [POTM](https://products.groupdocs.com/comparison/java/potm/), [POTX](https://products.groupdocs.com/comparison/java/potx/), [PPTM](https://products.groupdocs.com/comparison/java/pptm/)
                * **Visio:** [VSD](https://products.groupdocs.com/comparison/java/vsd/), [VDX](https://products.groupdocs.com/comparison/java/vdx/), [VSS](https://products.groupdocs.com/comparison/java/vss/), [VSSX](https://products.groupdocs.com/comparison/java/vssx/), [VSX](https://products.groupdocs.com/comparison/java/vsx/), [VST](https://products.groupdocs.com/comparison/java/vst/), [VSTX](https://products.groupdocs.com/comparison/java/vstx/), [VTX](https://products.groupdocs.com/comparison/java/vtx/), [VSDX](https://products.groupdocs.com/comparison/java/vsdx/), [VDW](https://products.groupdocs.com/comparison/java/vdw/), [VSTM](https://products.groupdocs.com/comparison/java/vstm/), [VSSM](https://products.groupdocs.com/comparison/java/vssm/), [VSDM](https://products.groupdocs.com/comparison/java/vsdm/)
                * **Outlook:** [MSG](https://products.groupdocs.com/comparison/java/msg/), [EML](https://products.groupdocs.com/comparison/java/eml/), [EMLX](https://products.groupdocs.com/comparison/java/emlx/), [PST](https://products.groupdocs.com/comparison/java/pst/), [OST](https://products.groupdocs.com/comparison/java/ost/)
                * **OneNote:** [ONE](https://products.groupdocs.com/comparison/java/one/)

        right:
          enable: true
          table:
            # table loop
            - title: "其他格式"
              content: |
                * **編程語言**: [CS](https://products.groupdocs.com/comparison/java/cs/), [Java](https://products.groupdocs.com/comparison/java/java/), [CPP](https://products.groupdocs.com/comparison/java/cpp/), [JS](https://products.groupdocs.com/comparison/java/js/), [PY](https://products.groupdocs.com/comparison/java/py/), [RB](https://products.groupdocs.com/comparison/java/rb/), [PL](https://products.groupdocs.com/comparison/java/pl/), [ASM](https://products.groupdocs.com/comparison/java/asm/), [GROOVY](https://products.groupdocs.com/comparison/java/groovy/), [JSON](https://products.groupdocs.com/comparison/java/json/), [PHP](https://products.groupdocs.com/comparison/java/php/), [SQL](https://products.groupdocs.com/comparison/java/sql/), [LOG](https://products.groupdocs.com/comparison/java/log/), [DIFF](https://products.groupdocs.com/comparison/java/diff/), [LESS](https://products.groupdocs.com/comparison/java/less/), [SCALA](https://products.groupdocs.com/comparison/java/scala/)
                * **OpenDocument**: [ODT](https://products.groupdocs.com/comparison/java/odt/), [OTT](https://products.groupdocs.com/comparison/java/ott/), [ODS](https://products.groupdocs.com/comparison/java/ods/), [ODP](https://products.groupdocs.com/comparison/java/odp/), [OTP](https://products.groupdocs.com/comparison/java/otp/)
                * **Portable**: [PDF](https://products.groupdocs.com/comparison/java/pdf/), [MOBI](https://products.groupdocs.com/comparison/java/mobi/)
                * **AutoCAD**: [DXF](https://products.groupdocs.com/comparison/java/dxf/), [DWG](https://products.groupdocs.com/comparison/java/dwg/)
                * **Email**: [EML](https://products.groupdocs.com/comparison/java/eml/), [EMLX](https://products.groupdocs.com/comparison/java/emlx/), [MSG](https://products.groupdocs.com/comparison/java/msg/)
                * **Images**: [JPEG](https://products.groupdocs.com/comparison/java/jpeg/), [BMP](https://products.groupdocs.com/comparison/java/bmp/), [PNG](https://products.groupdocs.com/comparison/java/png/), [GIF](https://products.groupdocs.com/comparison/java/gif/), [DCM](https://products.groupdocs.com/comparison/java/dcm/), [DICOM](https://products.groupdocs.com/comparison/java/dicom/), [DjVu](https://products.groupdocs.com/comparison/java/djvu/)
                * **Web**: [HTM](https://products.groupdocs.com/comparison/java/htm/), [HTML](https://products.groupdocs.com/comparison/java/html/), [MHTML](https://products.groupdocs.com/comparison/java/mhtml/)
                * **Text**: [TXT](https://products.groupdocs.com/comparison/java/txt/)

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Comparison for Java 支持以下操作系統、框架和包管理器：
      
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "操作系統"
              content: |
                * Microsoft Windows Desktop
                * Microsoft Windows Server
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "支持的框架"
              content: |
                * Java 7 (1.7) 或更高

        right:
          enable: true
          table:
            
            # table loop
            - icon: "fas fa-cogs"
              title: "開發環境"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse
            # table loop
            - icon: "fas fa-tools"
              title: "構建自動化工具"
              content: |
                * Maven

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Comparison for Java 功能"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "[比較並識別內容和文本樣式的變化](https://docs.groupdocs.com/comparison/java/compare-documents/)"

      # feature loop
      - icon: "fas fa-eye"
        content: "[保存有關比較文檔的匯總比較列表](https://docs.groupdocs.com/comparison/java/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-bolt"
        content: "[比較 Word 文檔的特定頁面](https://docs.groupdocs.com/comparison/java/accept-or-reject-detected-changes/)"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "[合併最多 3 個 Microsoft Word 文件以進行比較，並支持“跟踪更改”](https://docs.groupdocs.com/comparison/java/compare-multiple-documents-with-specific-compare-settings/)"

      # feature loop
      - icon: "fas fa-code"
        content: "[在比較過程中輕鬆發現哪些更改來自哪個文檔](https://docs.groupdocs.com/comparison/java/get-list-of-changes/)"

      # feature loop
      - icon: "fas fa-cloud"
        content: "[支持讀取源文檔並通過流發送結果文檔](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "[從流中獲取時檢測文件格式類型](https://docs.groupdocs.com/comparison/java/get-file-info/)"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "[比較受密碼保護的文檔](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/)"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "[將比較結果保存為圖像](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-border-all"
        content: "[將不同文件格式作為圖像進行比較](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-wrench"
        content: "[比較 PDF 文檔中的水印](https://docs.groupdocs.com/comparison/java/how-to-spot-photos-differences-in-java-or-kotlin/)"

      # feature loop
      - icon: "fas fa-columns"
        content: "[比較文件或流中的文檔並通過流或文件發送結果文檔](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-file-word"
        content: "[比較 Word、PDF 或 Excel 文件後接受或放棄更改](https://docs.groupdocs.com/comparison/java/accept-or-reject-detected-changes/)"

      # feature loop
      - icon: "fas fa-envelope"
        content: "[通過文件或流比較加密文檔](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-print"
        content: "[用於比較操作的計量許可選項](https://docs.groupdocs.com/comparison/java/evaluation-limitations-and-licensing-of-groupdocs-comparison/)"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "[比較 PDF、Word、Excel、PowerPoint 和註釋文檔時突出顯示標記更改的文本](https://docs.groupdocs.com/comparison/java/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-lock"
        content: "[計算 PDF、PowerPoint 幻燈片和圖表中變化的正確坐標](https://docs.groupdocs.com/comparison/java/get-changes-coordinates/)"

      # feature loop
      - icon: "fas fa-file-code"
        content: "[比較多個（兩個以上）PDF、Excel、OneNote、圖表、電子郵件和文本文檔](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/)"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "[比較支持的文件格式的頁眉和頁腳](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "[比較文檔並將不同格式的文檔頁面另存為圖像](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"


############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison 為其他流行的開發環境提供文檔查看 API"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
          product: "GroupDocs.Comparison"
          platform: ".NET"
          link: "/comparison/net/"

############################# Back to top ###############################
back_to_top:
  enable: true
---