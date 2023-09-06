---
############################# Static ############################
layout: "auto-gen-comparison"
date: 2021-05-13T12:45:19+03:00
draft: false

############################# Head ############################
head_title: ".NET で 2 つの PDF ファイルを比較する |ドキュメント比較 API"
head_description: "C# .NET アプリケーションで 3 つ以上の PDF ファイルを比較およびマージします。 PDF ファイル、画像、ドキュメント形式のコンテンツ、テキスト、スタイルの相違点の概要を取得します。"

############################# Header ############################
title: "C# .NET での PDF ファイルの比較"
description: ".NET ドキュメント比較 API。PDF ファイルの 2 つのバージョン間の変更を検出し、比較されたドキュメント間の相違点の詳細な概要を含む最終ドキュメントにエクスポートします。"
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
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
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-comparison-net.png"
        product: "GroupDocs.Comparison"
        platform: ".NET"

    middle:
        button: 
            # button loop
            - link: "https://apireference.groupdocs.com/comparison/net"
              text: "APIリファレンス"

            # button loop
            - link: "https://github.com/groupdocs-comparison"
              text: "コード例"

            # button loop
            - link: "https://products.groupdocs.app/comparison/family"
              text: "ライブデモ"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "価格設定"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/net"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: "GroupDocs.Comparison for .NET API について"
    content: |
        [GroupDocs.Comparison for .NET](/comparison/net/) は、同じ形式の複数の画像とドキュメントを比較するためのネイティブ .NET API です。比較した文書の段落、単語、文字、図形、さらにはテキスト スタイル内の相違点を検出し、変更を結合して最終文書にエクスポートするのに役立ちます。外部ライブラリを使用せずに、PDF、Word 文書、Excel スプレッドシート、PowerPoint プレゼンテーション、Visio 図、Outlook 電子メール、HTML、図面、画像ファイル形式の比較と結合をサポートします。

############################# Steps ############################
steps:
    enable: true
    title_left: "C# で PDF ファイルを比較する手順"
    content_left: |
        [GroupDocs.Comparison](/comparison/net/) を使用すると、.NET 開発者は、いくつかの簡単な手順を実装することで、アプリケーション内の複数の PDF ファイルを簡単に比較およびマージできます。
        * ソース ドキュメント パスまたはストリームを使用して **Comparer** オブジェクトをインスタンス化します。
        * Add メソッドを呼び出し、対象のドキュメント パスまたはストリームを指定します。ターゲットドキュメントごとにこの手順を繰り返します。
        * Compare メソッドを呼び出します。
    title_right: "システム要求"
    content_right: |
        GroupDocs.Comparison for .NET API は、すべての主要なプラットフォームとオペレーティング システムでサポートされています。以下のコードを実行する前に、次の前提条件がシステムにインストールされていることを確認してください。
        * オペレーティング システム: Microsoft Windows、Linux、MacOS
        * 開発環境: Microsoft Visual Studio, Xamarin, MonoDevelop
        * フレームワーク: .NET Framework、.NET Standard、.NET Core、Mono
        * [NuGet](https://www.nuget.org/packages/groupdocs.comparison) からダウンロードした GroupDocs.Comparison for .NET の最新バージョンを入手します。
    code: |
        ```cs
        // ローカルディスクから複数のドキュメントを比較する
        
        using (Comparer comparer = new Comparer("source.pdf"))
        {
        	comparer.Add("target1.pdf");
            comparer.Add("target2.pdf");
            comparer.Add("target3.pdf");
            comparer.Compare("result.pdf"); // 指定された名前で結果ファイルを作成します
        }
        
        // ストリームからの複数のドキュメントを比較する
        
        using (Comparer comparer = new Comparer(File.OpenRead("source.pdf")))
        {
        	comparer.Add(File.OpenRead("target1.pdf"));
            comparer.Add(File.OpenRead("target2.pdf"));
            comparer.Add(File.OpenRead("target3.pdf"));
            comparer.Compare(File.Create("result.pdf")); // 指定された名前で結果ファイルを作成します
        }
        ```

############################# Demos ############################
demos:
    enable: true
    title: "PDF ファイルを比較するライブ デモ"
    content: |
        [GroupDocs.Comparison Live Demos](https://products.groupdocs.app/comparison/family) Web サイトにアクセスして、今すぐ PDF ファイル間の違いを検出してください。
        ライブデモには次のようなメリットがあります

############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-pdf"
          title: "PDF ファイル形式について"
          content: |
            PDF (Portable Document Format) は、1990 年代に Adob​​e によって作成されたドキュメントの種類です。このファイル形式の目的は、アプリケーション ソフトウェア、ハードウェア、オペレーティング システムに依存しない形式でドキュメントやその他の参考資料を表現するための標準を導入することでした。 PDF ファイルは、Adobe Acrobat Reader/Writer で開くことができるほか、拡張機能/プラグインを介して Chrome、Safari、Firefox などのほとんどの最新ブラウザでも開くことができます。市販のソフトウェア スイートのほとんどは、追加のソフトウェア コンポーネントを必要とせずに、ドキュメントを PDF ファイル形式に変換することもできます。したがって、PDF ファイル形式には、テキスト、画像、ハイパーリンク、フォームフィールド、リッチメディア、デジタル署名、添付ファイル、メタデータ、地理空間機能、ソースドキュメントの一部となる 3D オブジェクトなどの情報を含める完全な機能が備わっています。
          link: "https://docs.fileformat.com/image/pdf/"

############################# More Formats ############################
more_formats:
    enable: true
    title: "他のファイル形式の比較"
    content: |
        .NET 用のマルチフォーマットのドキュメントと画像比較 API。外部ツールを使用せずに、同じ形式のドキュメント間の差異を分析します。
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
    title: "GroupDocs.Comparison は、他の一般的な開発環境向けのドキュメント表示 API を提供します"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for Java PDF"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/pdf/"

############################# Back to top ###############################
back_to_top:
    enable: true
---
