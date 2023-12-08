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
head_title: "Java ドキュメント比較 API | PDF Word Excel HTMLのテキストとスタイルを比較"
head_description: "Word Excel PPTX OpenOffice、Web、PDF、AutoCAD、その他のファイル形式を比較およびマージするための Java Document Comparison API。変更履歴を含むドキュメントを比較します。"

############################# Header ############################
title: "ファイルを比較するための Java API"
description: "Java アプリケーションを作成して、すべての標準ドキュメントおよび画像ファイル形式の違いについてファイルの内容を効果的に比較します。"
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "無料トライアルをダウンロード"
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
              text: "概要"

            # button loop
            - link: "#features"
              text: "特徴"

            # button loop
            - link: "#support"
              text: "サポート"

            # button loop
            - link: "https://products.groupdocs.app/comparison"
              text: "ライブデモ"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/java"
              text: "価格設定"

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
      - title: "GroupDocs.Comparison for Javaとは何ですか"
        content: "GroupDocs.Comparison for Java は、Java 環境でのドキュメント比較アプリケーションの開発に役立つ、最も柔軟で使いやすい API です。相違点チェッカーとドキュメント結合 API を使用すると、類似したドキュメント形式間のテキスト スタイルだけでなく、コンテンツの変更や相違点を検出できます。"

      # more_overview_loop
      - title: "サポートされている形式"
        content: "GroupDocs.Comparison ライブラリは、PDF、HTML、電子メール Outlook、Microsoft Office Word ドキュメント、Excel スプレッドシート、PowerPoint プレゼンテーション、OneNote、Visio 図、テキスト、png などの一般的な画像およびドキュメント形式間のコンテンツとテキスト スタイルの両方の違いの検出をサポートします。 、gif、bmp 画像、その他数百の形式に対応しています。"
        
      # more_overview_loop
      - title: "比較機能"
        content: "比較を実行すると、単語、段落、表、グラフの内容とそのスタイルの変更を検出でき、相違点、それらの数とタイプの所属の概要をリストした比較文書が提供されます。 GroupDocs.Comparison for Java は、ソース ドキュメントに関する基本情報を簡単に抽出し、ファイルまたはデータ ストリームを通じて、パスワードで保護され暗号化されたさまざまな形式の単純なドキュメントを比較および保存できます。"
        
      # more_overview_loop
      - title: "ドキュメントと例"
        content: "さまざまなプラットフォームでの比較ライブラリの使用に関するコード例付きのドキュメントがすでにたくさんあるため、アプリケーションで Java API の GroupDocs.Comparison を使用する方法について難しく考える必要はありません。"
        
      # more_overview_loop
      - title: "互換性"
        content: "GroupDocs.Comparison for Java では、システムに外部ソフトウェアをインストールする必要はありません。 Java のすべてのバージョンと互換性があり、Java ランタイム環境を実行できる一般的なオペレーティング システム (Windows、Linux、MacOS) をサポートします。"
    examples:
      enable: true
      
    more_feature:
      # more_feature_loop
      - title: "Java APIを使用してドキュメントを簡単に比較"
        content: |
          GroupDocs.Comparison for Java API を使用すると、サポートされている形式のドキュメントを簡単に比較して、ドキュメント間の違いを見つけることができます。次の例は、Java を使用して 2 つの Microsoft Word ドキュメントを比較する方法を示しています。
          
          ```java
          try (Comparer comparer = new Comparer("D:\\source.pdf")) {
              comparer.add("D:\\target.pdf");
              comparer.compare("D:\\result.pdf");
          }
          ```
      # more_feature_loop
      - title: "比較の詳細レベルの指定"
        content: "GroupDocs.Comparison for Java を使用すると、ドキュメントを 3 つのレベルで比較できます。比較強度を低 (イメージング グリッド = 50 の精度でテキストを単語ごとに比較)、中 (イメージング グリッド = 100 の精度でテキストを 1 文字ずつ比較)、または高 (イメージングの精度でテキストを 1 文字ずつ比較) に設定できます。グリッド = 150)。"

      # more_feature_loop
      - title: "テキストスタイルの比較"
        content: "GroupDocs.Comparison for Java API を使用すると、ドキュメントのコンテンツに加えて、テキスト スタイルも比較できます。

        単語や文字を比較しながら、フォント名、サイズ、色、スタイル (太字、斜体、下線、小文字、ハイパーリンク)、および該当する場合は下の色も比較して、比較するドキュメント間の違いを確認できます。  

        段落の比較では、配置、インデント（左インデント、右インデント）、スペース（後のスペース、前のスペース）、最初の行のインデント、行間も比較できます。  

        同様に、該当する場合は、ページの他のセクションも GroupDocs.Comparison for Java API を通じて比較できます。セクションには、フッターの距離、ページの余白 (左、右、上、下)、ページの高さ、ページの方向、境界線の色、線の幅が含まれます。"
      
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          以下は、GroupDocs.Comparison for Java の概要です。
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "概要"
          content: |
            * 内容とスタイルを比較
            * 比較の概要を取得
            * Word での変更の承認/拒否
            * 3 つの Word ファイルを結合して比較
            * ストリームのサポート
            * ストリーム経由のファイルタイプ検出
            * 保護されたファイルを比較
            * 暗号化されたファイルを比較
            * 比較を画像として保存
            * Wordで特定のページを比較
            * PDF のウォーターマークを比較
            * 変更の適用/破棄
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison for Java は、Microsoft Office、画像、図などを含むすべての一般的な [ドキュメント ファイル形式](https://docs.groupdocs.com/comparison/java/supported-document-formats/) をサポートしています。 。
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
            - title: "その他の形式"
              content: |
                * **プログラミング言語**: [CS](https://products.groupdocs.com/comparison/java/cs/), [Java](https://products.groupdocs.com/comparison/java/java/), [CPP](https://products.groupdocs.com/comparison/java/cpp/), [JS](https://products.groupdocs.com/comparison/java/js/), [PY](https://products.groupdocs.com/comparison/java/py/), [RB](https://products.groupdocs.com/comparison/java/rb/), [PL](https://products.groupdocs.com/comparison/java/pl/), [ASM](https://products.groupdocs.com/comparison/java/asm/), [GROOVY](https://products.groupdocs.com/comparison/java/groovy/), [JSON](https://products.groupdocs.com/comparison/java/json/), [PHP](https://products.groupdocs.com/comparison/java/php/), [SQL](https://products.groupdocs.com/comparison/java/sql/), [LOG](https://products.groupdocs.com/comparison/java/log/), [DIFF](https://products.groupdocs.com/comparison/java/diff/), [LESS](https://products.groupdocs.com/comparison/java/less/), [SCALA](https://products.groupdocs.com/comparison/java/scala/)
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
          GroupDocs.Comparison for Java は、次のオペレーティング システム、フレームワーク、パッケージ マネージャーをサポートしています。
      
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "オペレーティングシステム"
              content: |
                * Microsoft Windows Desktop
                * Microsoft Windows Server
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "サポートされているフレームワーク"
              content: |
                * Java 7 (1.7) 以上

        right:
          enable: true
          table:
            
            # table loop
            - icon: "fas fa-cogs"
              title: "開発環境"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse
            # table loop
            - icon: "fas fa-tools"
              title: "ビルド自動化ツール"
              content: |
                * Maven

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Comparison for Java の機能"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "[コンテンツとテキストスタイルの両方の変更を比較して特定する](https://docs.groupdocs.com/comparison/java/compare-documents/)"

      # feature loop
      - icon: "fas fa-eye"
        content: "[比較されたドキュメントに関する要約比較リストの保存](https://docs.groupdocs.com/comparison/java/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-bolt"
        content: "[Word 文書の特定のページを比較する](https://docs.groupdocs.com/comparison/java/accept-or-reject-detected-changes/)"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "[最大 3 つの Microsoft Word ファイルを結合して比較し、「変更の追跡」をサポート](https://docs.groupdocs.com/comparison/java/compare-multiple-documents-with-specific-compare-settings/)"

      # feature loop
      - icon: "fas fa-code"
        content: "[比較中にどのドキュメントからどの変更が加えられたのかを簡単に特定](https://docs.groupdocs.com/comparison/java/get-list-of-changes/)"

      # feature loop
      - icon: "fas fa-cloud"
        content: "[ソースドキュメントの読み取りと結果ドキュメントのストリーム経由での送信のサポート](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "[ストリームからのフェッチ中にファイル形式のタイプを検出する](https://docs.groupdocs.com/comparison/java/get-file-info/)"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "[パスワードで保護されたドキュメントを比較する](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/)"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "[比較結果を画像として保存](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-border-all"
        content: "[異なるファイル形式を画像として比較](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-wrench"
        content: "[PDF ドキュメント内のウォーターマークを比較する](https://docs.groupdocs.com/comparison/java/how-to-spot-photos-differences-in-java-or-kotlin/)"

      # feature loop
      - icon: "fas fa-columns"
        content: "[ファイルまたはストリームからドキュメントを比較し、結果ドキュメントをストリームまたはファイル経由で送信する](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-file-word"
        content: "[Word、PDF、または Excel ファイルの比較後の変更を受け入れるか破棄する](https://docs.groupdocs.com/comparison/java/accept-or-reject-detected-changes/)"

      # feature loop
      - icon: "fas fa-envelope"
        content: "[ファイルまたはストリーム経由で暗号化されたドキュメントを比較する](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-print"
        content: "[比較操作のための従量制ライセンス オプション](https://docs.groupdocs.com/comparison/java/evaluation-limitations-and-licensing-of-groupdocs-comparison/)"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "[PDF、Word、Excel、PowerPoint、メモドキュメントを比較するときに、マークされた変更のテキストを強調表示](https://docs.groupdocs.com/comparison/java/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-lock"
        content: "[PDF、PowerPointのスライド、図表内の変更の正確な座標を計算](https://docs.groupdocs.com/comparison/java/get-changes-coordinates/)"

      # feature loop
      - icon: "fas fa-file-code"
        content: "[複数（2 つ以上）の PDF、Excel、OneNote、図、電子メール、テキスト ドキュメントを比較](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/)"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "[サポートされているファイル形式のヘッダーとフッターを比較](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "[文書を比較し、異なる形式の文書ページを画像として保存](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"


############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison は、他の一般的な開発環境向けのドキュメント表示 API を提供します"

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