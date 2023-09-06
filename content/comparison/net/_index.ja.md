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
head_title: "C# .NET ドキュメント比較 API | PDF Word Excel Web とテキストの比較と結合"
head_description: "C# .NET ドキュメント比較 API。 PDF Word DOC DOCX、Excel スプレッドシート、PPT、PPTX、HTML、EMLX MSG、VSDX、DXF DWG および画像ファイル形式を比較および結合します。"

############################# Header ############################
title: "ファイルを比較するための .NET API"
description: ".NET Document Comparison API を使用してアプリケーションを開発し、ファイルのコンテンツとスタイルの違いをチェックして比較します。"
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "無料トライアルをダウンロード"
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
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "価格設定"

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
      - title: "GroupDocs.Comparison for .NETとは何ですか"
        content: "GroupDocs.Comparison for .NET API は、C#、ASP.NET、または .NET ソフトウェア プラットフォームに関連するその他のテクノロジで、同じ形式または異なる形式のドキュメント間の差異を検索および強調表示するアプリケーションを作成するときにすぐに使用できる、高速で信頼性の高いソリューションです。"

      # more_overview_loop
      - title: "サポートされている形式"
        content: "GroupDocs.Comparison ライブラリは、PDF、HTML、電子メール Outlook、Microsoft Office Word ドキュメント、Excel スプレッドシート、PowerPoint プレゼンテーション、OneNote、Visio 図、テキスト、png などの一般的な画像およびドキュメント形式間のコンテンツとテキスト スタイルの両方の違いの検出をサポートします。 、gif、bmp 画像、その他数百の形式に対応しています。"
        
      # more_overview_loop
      - title: "比較機能"
        content: "比較を実行すると、単語、段落、表、グラフの内容とそのスタイルの変更を検出でき、相違点、それらの数とタイプの所属の概要をリストした比較文書が提供されます。 GroupDocs.Comparison for .NET は、ソース ドキュメントに関する基本情報を簡単に抽出し、ファイルまたはデータ ストリームを通じて、パスワードで保護され暗号化されたさまざまな形式の単純なドキュメントを比較および保存できます。"
        
      # more_overview_loop
      - title: "ドキュメントと例"
        content: "さまざまなプラットフォームでの比較ライブラリの使用に関するコード例付きのドキュメントがすでにたくさんあるため、アプリケーションで .NET API の GroupDocs.Comparison を使用する方法について難しく考える必要はありません。"
        
      # more_overview_loop
      - title: "互換性"
        content: "GroupDocs.Comparison for .NET を使用すると、.NET プラットフォームを対象とした任意の開発環境でアプリケーションを作成できます。すべての .NET ベースの言語と互換性があり、Mono または .NET フレームワーク (.NET Core を含む) をインストールできる一般的なオペレーティング システム (Windows、Linux、MacOS) をサポートしています。"
    examples:
      enable: true
      
    more_feature:
      # more_feature_loop
      - title: ".NET APIを使用してドキュメントを簡単に比較"
        content: |
          GroupDocs.Comparison for .NET API は、ファイルを比較するための簡単かつ効率的な方法を提供します。以下は、C# を使用して 2 つの DOCX ドキュメントを比較する方法を示す例です。  

          ```cs
          // 比較するソース ファイルとターゲット ファイル
          string source = @"source.docx";
          string target = @"target.docx";
          Comparer comparer = new Comparer();
          // 2 つの文書を比較する
          ICompareResult result = comparer.Compare(source, target, new ComparisonSettings());
          ```
      # more_feature_loop
      - title: "比較の詳細レベルを選択してください"
        content: "GroupDocs.Comparison for .NET を使用すると、ドキュメントを比較する範囲を指定できます。低 (イメージング グリッド = 50 の精度でテキストを単語ごとに比較)、中 (イメージング グリッド = 100 の精度でテキストを 1 文字ずつ比較)、または高 (イメージング グリッド = の精度でテキストを 1 文字ずつ比較) から選択できます。 150）。"

      # more_feature_loop
      - title: "テキストスタイル比較のサポート"
        content: |
          GroupDocs.Comparison for .NET はテキスト スタイルを比較する機能を提供します。  

          文書の単語や文字を比較する際、フォント名、フォント サイズ、フォントの色、フォント スタイル (太字、斜体、下線、小文字、ハイパーリンク)、および下線の色 (該当する場合) を比較して相違点を見つけることができます。  

          段落を比較する際、段落の配置、インデント (左インデント、右インデント)、段落間隔 (後のスペース、前のスペース)、最初の行のインデント、行間隔などのスタイルを比較できます。  

          GroupDocs.Comparison for .NET は、該当する場合、フッターの距離、ページの高さと方向、余白 (左、右、上、下)、境界線の幅、境界線の色など、ページの他のセクションの比較もサポートします。  
      
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          以下は、GroupDocs.Comparison for .NET の概要です。
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "概要"
          content: |
            * 文書の比較
            * HTML ファイルの比較
            * PDFの比較
            * 図の比較
            * ファイルの内容を比較
            * テキストスタイルの比較
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison for .NET は、Microsoft Office、PDF、画像、その他多くの一般的な [ドキュメント ファイル形式](https://docs.groupdocs.com/comparison/net/supported-document-formats/) をすべてサポートしています。 。
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
            - title: "その他の形式"
              content: |
                * **プログラミング言語**: [CS](https://products.groupdocs.com/comparison/net/cs/), [Java](https://products.groupdocs.com/comparison/net/java/), [CPP](https://products.groupdocs.com/comparison/net/cpp/), [JS](https://products.groupdocs.com/comparison/net/js/), [PY](https://products.groupdocs.com/comparison/net/py/), [RB](https://products.groupdocs.com/comparison/net/rb/), [PL](https://products.groupdocs.com/comparison/net/pl/), [ASM](https://products.groupdocs.com/comparison/net/asm/), [GROOVY](https://products.groupdocs.com/comparison/net/groovy/), [JSON](https://products.groupdocs.com/comparison/net/json/), [PHP](https://products.groupdocs.com/comparison/net/php/), [SQL](https://products.groupdocs.com/comparison/net/sql/), [LOG](https://products.groupdocs.com/comparison/net/log/), [DIFF](https://products.groupdocs.com/comparison/net/diff/), [LESS](https://products.groupdocs.com/comparison/net/less/), [SCALA](https://products.groupdocs.com/comparison/net/scala/)
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
          GroupDocs.Comparison for .NET は、次のオペレーティング システム、フレームワーク、パッケージ マネージャーをサポートしています。
      
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "オペレーティングシステム"
              content: |
                * Windows Desktop
                * Windows Server
                * Windows Azure
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "サポートされているフレームワーク"
              content: |
                * .NET Framework 2.0 以上
                * Mono Framework 1.2 以上
                * .NET Standard 2.0
                * .NET Core 2.0

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "パッケージマネージャー"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "開発環境"
              content: |
                * Microsoft Visual Studio
                * Xamarin.Android
                * Xamarin.IOS
                * Xamarin.Mac
                * MonoDevelop

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Comparison for .NET の機能"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "[コンテンツとフォント スタイルの違いを特定する](https://docs.groupdocs.com/comparison/net/compare-documents/)"

      # feature loop
      - icon: "fas fa-eye"
        content: "[ファイル比較後に見つかったすべての相違点の要約レポートを保存する](https://docs.groupdocs.com/comparison/net/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-bolt"
        content: "[差異を分析した後に変更を適用または拒否し、結果のファイルをエクスポートする](https://docs.groupdocs.com/comparison/net/accept-or-reject-detected-changes/)"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "[Word ファイルの比較中の Microsoft Word の「変更の追跡」機能のサポート](https://docs.groupdocs.com/comparison/net/show-revisions/)"

      # feature loop
      - icon: "fas fa-code"
        content: "[比較されている各ドキュメントからの変更を独自に特定](https://docs.groupdocs.com/comparison/net/get-list-of-changes/)"

      # feature loop
      - icon: "fas fa-cloud"
        content: "[ストリーム経由でドキュメントを読み取り、送信する](https://docs.groupdocs.com/comparison/net/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "[従量制ライセンス – API 使用量に応じた課金](https://docs.groupdocs.com/comparison/net/licensing-and-evaluation-limitations/)"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "[複数のソースドキュメントと単一のターゲットドキュメントを比較する](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/)"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "[Word ファイルの特定のページを相互に比較 – 単一の Word 文書内のすべての変更を受け入れるか拒否する](https://docs.groupdocs.com/comparison/net/accept-or-reject-detected-changes/)"

      # feature loop
      - icon: "fas fa-border-all"
        content: "[最大 3 つの Word 文書を結合し、Word ファイルで使用されている数式を比較します](https://docs.groupdocs.com/comparison/net/how-to-merge-source-code-files/)"

      # feature loop
      - icon: "fas fa-wrench"
        content: "[filePath からドキュメントに関する情報を取得する](https://docs.groupdocs.com/comparison/net/get-file-info/)"

      # feature loop
      - icon: "fas fa-columns"
        content: "[HTML比較結果を画像として保存](https://docs.groupdocs.com/comparison/net/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-file-word"
        content: "[削除されたコンテンツを表示または非表示にするオプション](https://docs.groupdocs.com/comparison/net/show-gap-lines/)"

      # feature loop
      - icon: "fas fa-envelope"
        content: "[ドキュメントのスタイル比較をオンまたはオフにするオプション](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fas fa-print"
        content: "[比較ドキュメント内の挿入、削除、およびスタイル変更項目をマークする文字列を指定する](https://docs.groupdocs.com/comparison/net/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "[単語の区切り文字とフォントの色を指定して比較するテキストのスタイルを設定する](https://docs.groupdocs.com/comparison/net/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-lock"
        content: "[PDF、Word、PowerPointのスライドと図の変更の正確な座標を計算](https://docs.groupdocs.com/comparison/net/get-changes-coordinates/)"

      # feature loop
      - icon: "fas fa-file-code"
        content: "[パスワードで保護されたファイルを比較する](https://docs.groupdocs.com/comparison/net/how-to-compare-password-protected-files/)"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "[スプレッドシートのグラフ タイトルを比較 – 結果のセル ファイルにグラフを生成](https://docs.groupdocs.com/comparison/net/how-to-compare-spreadsheet-or-tables/)"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "[Cells ドキュメントの結果ファイル内のオートシェイプのサイズを自動調整します](https://docs.groupdocs.com/comparison/net/how-to-compare-spreadsheet-or-tables/)"

      # feature loop
      - icon: "fas fa-heading"
        content: "[詳細な概要ページにアクセスして、ソース ドキュメント ファイルとターゲット ドキュメント ファイル間の変更を検出する](https://docs.groupdocs.com/comparison/net/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "[最も人気のあるプログラミングおよびスクリプト言語ファイルを比較する](https://docs.groupdocs.com/comparison/net/get-supported-document-formats/)"

      # feature loop
      - icon: "fas fa-cube"
        content: "[複数（2 つ以上）の PDF、Word、Excel、図、電子メール、テキスト、OneNote ドキュメントを比較](https://docs.groupdocs.com/comparison/net/compare-multiple-documents-with-specific-compare-settings/)"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "[サポートされているファイル形式のヘッダーとフッターを比較](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "[Word ドキュメント形式のブックマーク、変数、カスタム プロパティを比較する](https://docs.groupdocs.com/comparison/net/compare-bookmarks-in-word/)"

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison は、他の一般的な開発環境向けのドキュメント表示 API を提供します"

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