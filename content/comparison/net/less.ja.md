
---
############################# Static ############################
layout: "auto-gen-comparison"
date: 2021-05-13T12:45:11+03:00
draft: false

############################# Head ############################
head_title: ".NETの2つのLESSファイルを比較する|ドキュメント比較API"
head_description: "3つ以上を比較してマージします（C＃.NETアプリケーションのLESSファイル。LESSファイル、画像、ドキュメント形式のコンテンツ、テキスト、スタイルの違いの概要を取得します."

############################# Header ############################
title: "C＃.NETでLESSファイルを比較する"
description: ".2つのバージョンのLESSファイル間の変更を検出し、比較されたドキュメント間の違いの詳細な要約を含む最終的なドキュメントにエクスポートするためのNETドキュメント比較API."
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
    title: "GroupDocs.Comparison for .NET APIについて"
    content: |
        [GroupDocs.Comparison for .NET](/ja/comparison/net/)は、同じ形式の複数の画像とドキュメントを比較するためのネイティブ.NETAPIです。段落、単語、文字、図形、さらには比較されたドキュメントのテキストスタイル内の違いを検出し、変更をマージして最終的なドキュメントにエクスポートするのに役立ちます。外部ライブラリを使用せずに、PDF、Word文書、Excelスプレッドシート、PowerPointプレゼンテーション、Visioダイアグラム、Outlook電子メール、HTML、図面、および画像ファイル形式の比較とマージをサポートします。

############################# Steps ############################
steps:
    enable: true
    title_left: "C＃でLESSファイルを比較する手順"
    content_left: |
        [GroupDocs.Comparison](/ja/comparison/net/)を使用すると、.NET開発者は、いくつかの簡単な手順を実装することで、アプリケーション内の複数のLESSファイルを簡単に比較およびマージできます。
    
        
        * ソースドキュメントパスまたはストリームを使用して**Comparer**オブジェクトをインスタンス化します。
        * Addメソッドを呼び出し、ターゲットドキュメントのパスまたはストリームを指定します。ターゲットドキュメントごとにこの手順を繰り返します。
        * compareメソッドを呼び出します。
    
    title_right: "システム要求"
    content_right: |
        GroupDocs.Comparison for .NET APIは、すべての主要なプラットフォームとオペレーティングシステムでサポートされています。以下のコードを実行する前に、システムに次の前提条件がインストールされていることを確認してください。
    
        
        *オペレーティングシステム：Microsoft Windows、Linux、MacOS
        *開発環境：Microsoft Visual Studio、Xamarin、MonoDevelop
        *フレームワーク：.NET Framework、.NET Standard、.NET Core、Mono
        * [NuGet](https://www.nuget.org/packages/groupdocs.comparison)からダウンロードしたGroupDocs.Comparisonfor.NETの最新バージョンを入手します。
    
    code: |
        ```cs
        //ローカルディスクの複数のドキュメントを比較します
        
        using (Comparer comparer = new Comparer("source.less"))
        {
        	comparer.Add("target1.less");
            comparer.Add("target2.less");
            comparer.Add("target3.less");
            comparer.Compare("result.less"); // 指定された名前の結果ファイルを作成する
        }
        
        //ストリームからの複数のドキュメントを比較します
        
        using (Comparer comparer = new Comparer(File.OpenRead("source.less")))
        {
        	comparer.Add(File.OpenRead("target1.less"));
            comparer.Add(File.OpenRead("target2.less"));
            comparer.Add(File.OpenRead("target3.less"));
            comparer.Compare(File.Create("result.less")); // 指定された名前の結果ファイルを作成する
        }
        ```

############################# Demos ############################
demos:
    enable: true
    title: "LESSファイルの比較のライブデモ"
    content: |
        [GroupDocs.Comparisonライブデモ](https://products.groupdocs.app/comparison/family)サイトにアクセスして、LESSファイル間の違いを今すぐ検出してください。  
        ライブデモには次の利点があります

############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-less"
          title: "LESSファイル形式について"
          content: |
            {{以下}}
          link: "https://docs.fileformat.com/image/less/"

############################# More Formats ############################
more_formats:
    enable: true
    title: "他のファイル形式の比較"
    content: |
        .NET用のマルチフォーマットドキュメントと画像比較API。外部ツールを使用せずに、同じ形式のドキュメント間の違いを分析します。
    format: 
        
        - name: "PDFファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/pdf/"
          description: "AdobePortableドキュメント形式"

        - name: "DOCファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/doc/"
          description: "MicrosoftWordドキュメント"

        - name: "DOCMファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/docm/"
          description: "MicrosoftWordマクロ対応ドキュメント"

        - name: "DOCXファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/docx/"
          description: "Microsoft WordOpenXMLドキュメント"

        - name: "DOTファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/dot/"
          description: "MicrosoftWord文書テンプレート"

        - name: "DOTMファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/dotm/"
          description: "MicrosoftWordマクロ対応テンプレート"

        - name: "DOTXファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/dotx/"
          description: "WordOpenXMLドキュメントテンプレート"

        - name: "RTFファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/rtf/"
          description: "リッチテキストファイル形式"

        - name: "TXTファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/txt/"
          description: "プレーンテキストファイル形式"

        - name: "XLSファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/xls/"
          description: "MicrosoftExcelバイナリファイル形式"

        - name: "XLSXファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/xlsx/"
          description: "Microsoft ExcelOpenXMLスプレッドシート"

        - name: "XLTMファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/xltm/"
          description: "MicrosoftExcelマクロ対応テンプレート"

        - name: "XLSMファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/xlsm/"
          description: "MicrosoftExcelマクロ対応スプレッドシート"

        - name: "XLSBファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/xlsb/"
          description: "MicrosoftExcelバイナリスプレッドシートファイル"

        - name: "CSVファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/csv/"
          description: "カンマ区切り値ファイル"

        - name: "PPTファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/ppt/"
          description: "PowerPointプレゼンテーション"

        - name: "PPSファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/pps/"
          description: "MicrosoftPowerPointスライドショー"

        - name: "PPTXファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/pptx/"
          description: "PowerPointOpenXMLプレゼンテーション"

        - name: "PPSXファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/ppsx/"
          description: "PowerPointOpenXMLスライドショー"

        - name: "POTファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/pot/"
          description: "MicrosoftPowerPointテンプレート"

        - name: "POTXファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/potx/"
          description: "Microsoft PowerPointOpenXMLテンプレート"

        - name: "ODSファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/ods/"
          description: "ドキュメントスプレッドシートを開く"

        - name: "ODPファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/odp/"
          description: "OpenDocumentプレゼンテーションファイル形式"

        - name: "OTPファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/otp/"
          description: "原点グラフテンプレート"

        - name: "ODTファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/odt/"
          description: "ドキュメントテキストを開く"

        - name: "OTTファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/ott/"
          description: "ドキュメントテンプレートを開く"

        - name: "VSTファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/vst/"
          description: "Microsoft Visio2003-2010XML図面"

        - name: "JPEGファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/jpeg/"
          description: "JPEG画像"

        - name: "PNGファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/png/"
          description: "ポータブルネットワークグラフィック"

        - name: "GIFファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/gif/"
          description: "グラフィカルな交換フォーマットファイル"

        - name: "BMPファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/bmp/"
          description: "ビットマップファイル形式"

        - name: "HTMLファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/html/"
          description: "ハイパーテキストマークアップ言語"

        - name: "MHTファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/mht/"
          description: "Mime HTML"

        - name: "MHTMLファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/mhtml/"
          description: "集約HTMLのMIMEカプセル化"

        - name: "MSGファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/msg/"
          description: "MicrosoftOutlookの電子メールメッセージ"

        - name: "EMLファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/eml/"
          description: "電子メールメッセージ"

        - name: "EMLXファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/emlx/"
          description: "AppleMailEメールファイル"

        - name: "ONEファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/one/"
          description: "Microsoft OneNote"

        - name: "VSDファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/vsd/"
          description: "MicrosoftVisio2003-2010図面"

        - name: "VSDXファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/vsdx/"
          description: "MicrosoftVisio図面"

        - name: "VSSファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/vss/"
          description: "MicrosoftVisio2003-2010ステンシル"

        - name: "VSTファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/vst/"
          description: "MicrosoftVisio2003-2010テンプレート"

        - name: "VDXファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/vdx/"
          description: "Microsoft Visio2003-2010XML図面"

        - name: "CSファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/cs/"
          description: "CSharp言語"

        - name: "JAVAファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/java/"
          description: "Java言語"

        - name: "CPPファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/cpp/"
          description: "C++言語"

        - name: "JSファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/js/"
          description: "JavaScript言語"

        - name: "PYファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/py/"
          description: "Python言語"

        - name: "RBファイルの比較"
          link: "https://products.groupdocs.com/comparison/net/rb/"
          description: "Ruby言語"

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison offers document viewing APIs for other popular formats"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for Java LESS"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/less/"

############################# Back to top ###############################
back_to_top:
    enable: true
---
