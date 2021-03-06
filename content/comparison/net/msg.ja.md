---
layout: "auto-gen-comparison"
date: 2021-05-13T12:45:22+03:00
draft: false

head_title: ".NETの2つのMSGファイルを比較する|ドキュメント比較API"
head_description: "3つ以上を比較してマージします（C＃.NETアプリケーションのMSGファイル。MSGファイル、画像、ドキュメント形式のコンテンツ、テキスト、スタイルの違いの概要を取得します."

title: "C＃.NETでMSGファイルを比較する"
description: ".2つのバージョンのMSGファイル間の変更を検出し、比較されたドキュメント間の違いの詳細な要約を含む最終的なドキュメントにエクスポートするためのNETドキュメント比較API."
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "無料トライアルをダウンロード"
    link: "https://downloads.groupdocs.com/comparison/net"

submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Comparison for .NET"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-comparison-net.png"
        product: "GroupDocs.Comparison"
        platform: ".NET"

    middle:
        button:

            - link: "https://apireference.groupdocs.com/comparison/net"
              text: "APIリファレンス"

            - link: "https://github.com/groupdocs-comparison"
              text: "コード例"

            - link: "https://products.groupdocs.app/comparison/family"
              text: "ライブデモ"

            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "価格設定"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/net"
        link_buy: "https://purchase.groupdocs.com"

about:
    enable: true
    title: "GroupDocs.Comparison for .NET APIについて"
    content: |
        [GroupDocs.Comparison for .NET](/Comparison/net/)は、同じ形式の複数の画像とドキュメントを比較するためのネイティブ.NETAPIです。段落、単語、文字、図形、さらには比較されたドキュメントのテキストスタイル内の違いを検出し、変更をマージして最終的なドキュメントにエクスポートするのに役立ちます。外部ライブラリを使用せずに、PDF、Word文書、Excelスプレッドシート、PowerPointプレゼンテーション、Visioダイアグラム、Outlook電子メール、HTML、図面、および画像ファイル形式の比較とマージをサポートします。

steps:
    enable: true
    title_left: "C＃でMSGファイルを比較する手順"
    content_left: |
        [GroupDocs.Comparison](/Comparison/net/)を使用すると、.NET開発者は、いくつかの簡単な手順を実装することで、アプリケーション内の複数のMSGファイルを簡単に比較およびマージできます。

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
        
        using (Comparer comparer = new Comparer("source.msg")
        {
        	comparer.Add("target1.msg");
            comparer.Add("target2.msg");
            comparer.Add("target3.msg");
            comparer.Compare("result.msg"); // 指定された名前の結果ファイルを作成する
        }
        
        //ストリームからの複数のドキュメントを比較します
        
        using (Comparer comparer = new Comparer(File.OpenRead("source.msg"))
        {
        	comparer.Add(File.OpenRead("target1.msg"));
            comparer.Add(File.OpenRead("target2.msg"));
            comparer.Add(File.OpenRead("target3.msg"));
            comparer.Compare(File.Create("result.msg")); // 指定された名前の結果ファイルを作成する
        }
        ```
        
demos:
    enable: true
    title: "MSGファイルの比較のライブデモ"
    content: |
        [GroupDocs.Comparisonライブデモ](https://products.groupdocs.app/comparison/family)サイトにアクセスして、MSGファイル間の違いを今すぐ検出してください。  
        ライブデモには次の利点があります
        
about_formats:
    enable: true
    format:
        - icon: "far fa-file-msg"
          title: "MSGファイル形式について"
          content: |
            MSGは、Microsoft OutlookおよびExchangeが電子メールメッセージ、連絡先、予定、またはその他のタスクを保存するために使用するファイル形式です。このようなメッセージには、送信者、受信者、件名、日付、メッセージ本文、または連絡先情報、予定の詳細、および1つ以上のタスク仕様を含む1つ以上の電子メールフィールドが含まれる場合があります。を含むメッセージオブジェクトを構成するプロパティもMSGファイルの一部です。 MSGファイルには、ヘッダー、メインメッセージ本文、およびプレーンASCIIテキストとしてのハイパーリンクがあります。 MSGファイルは、Microsoftのメッセージングアプリケーションプログラミングインターフェイス（MAPI）を必要とするプログラムにも適しています。

          link: "https://docs.fileformat.com/email/msg/"

more_formats:
    enable: false
    title: "他のファイル形式の比較"
    content: |
        .NET用のマルチフォーマットドキュメントと画像比較API。外部ツールを使用せずに、同じ形式のドキュメント間の違いを分析します。
    format: 
          link: "https://products.groupdocs.com/comparison/net/pdf/"
          description: "AdobePortableドキュメント形式"

          link: "https://products.groupdocs.com/comparison/net/doc/"
          description: "MicrosoftWordドキュメント"

          link: "https://products.groupdocs.com/comparison/net/docm/"
          description: "MicrosoftWordマクロ対応ドキュメント"

          link: "https://products.groupdocs.com/comparison/net/docx/"
          description: "Microsoft WordOpenXMLドキュメント"

          link: "https://products.groupdocs.com/comparison/net/dot/"
          description: "MicrosoftWord文書テンプレート"

          link: "https://products.groupdocs.com/comparison/net/dotm/"
          description: "MicrosoftWordマクロ対応テンプレート"

          link: "https://products.groupdocs.com/comparison/net/dotx/"
          description: "WordOpenXMLドキュメントテンプレート"

          link: "https://products.groupdocs.com/comparison/net/rtf/"
          description: "リッチテキストファイル形式"

          link: "https://products.groupdocs.com/comparison/net/txt/"
          description: "プレーンテキストファイル形式"

          link: "https://products.groupdocs.com/comparison/net/xls/"
          description: "MicrosoftExcelバイナリファイル形式"

          link: "https://products.groupdocs.com/comparison/net/xlsx/"
          description: "Microsoft ExcelOpenXMLスプレッドシート"

          link: "https://products.groupdocs.com/comparison/net/xltm/"
          description: "MicrosoftExcelマクロ対応テンプレート"

          link: "https://products.groupdocs.com/comparison/net/xlsm/"
          description: "MicrosoftExcelマクロ対応スプレッドシート"

          link: "https://products.groupdocs.com/comparison/net/xlsb/"
          description: "MicrosoftExcelバイナリスプレッドシートファイル"

          link: "https://products.groupdocs.com/comparison/net/csv/"
          description: "カンマ区切り値ファイル"

          link: "https://products.groupdocs.com/comparison/net/ppt/"
          description: "PowerPointプレゼンテーション"

          link: "https://products.groupdocs.com/comparison/net/pps/"
          description: "MicrosoftPowerPointスライドショー"

          link: "https://products.groupdocs.com/comparison/net/pptx/"
          description: "PowerPointOpenXMLプレゼンテーション"

          link: "https://products.groupdocs.com/comparison/net/ppsx/"
          description: "PowerPointOpenXMLスライドショー"

          link: "https://products.groupdocs.com/comparison/net/pot/"
          description: "MicrosoftPowerPointテンプレート"

          link: "https://products.groupdocs.com/comparison/net/potx/"
          description: "Microsoft PowerPointOpenXMLテンプレート"

          link: "https://products.groupdocs.com/comparison/net/ods/"
          description: "ドキュメントスプレッドシートを開く"

          link: "https://products.groupdocs.com/comparison/net/odp/"
          description: "OpenDocumentプレゼンテーションファイル形式"

          link: "https://products.groupdocs.com/comparison/net/otp/"
          description: "原点グラフテンプレート"

          link: "https://products.groupdocs.com/comparison/net/odt/"
          description: "ドキュメントテキストを開く"

          link: "https://products.groupdocs.com/comparison/net/ott/"
          description: "ドキュメントテンプレートを開く"

          link: "https://products.groupdocs.com/comparison/net/vst/"
          description: "Microsoft Visio2003-2010XML図面"

          link: "https://products.groupdocs.com/comparison/net/jpeg/"
          description: "JPEG画像"

          link: "https://products.groupdocs.com/comparison/net/png/"
          description: "ポータブルネットワークグラフィック"

          link: "https://products.groupdocs.com/comparison/net/gif/"
          description: "グラフィカルな交換フォーマットファイル"

          link: "https://products.groupdocs.com/comparison/net/bmp/"
          description: "ビットマップファイル形式"

          link: "https://products.groupdocs.com/comparison/net/html/"
          description: "ハイパーテキストマークアップ言語"

          link: "https://products.groupdocs.com/comparison/net/mht/"
          description: "Mime HTML"

          link: "https://products.groupdocs.com/comparison/net/mhtml/"
          description: "集約HTMLのMIMEカプセル化"

          link: "https://products.groupdocs.com/comparison/net/eml/"
          description: "電子メールメッセージ"

          link: "https://products.groupdocs.com/comparison/net/emlx/"
          description: "AppleMailEメールファイル"

          link: "https://products.groupdocs.com/comparison/net/one/"
          description: "Microsoft OneNote"

          link: "https://products.groupdocs.com/comparison/net/vsd/"
          description: "MicrosoftVisio2003-2010図面"

          link: "https://products.groupdocs.com/comparison/net/vsdx/"
          description: "MicrosoftVisio図面"

          link: "https://products.groupdocs.com/comparison/net/vss/"
          description: "MicrosoftVisio2003-2010ステンシル"

          link: "https://products.groupdocs.com/comparison/net/vst/"
          description: "MicrosoftVisio2003-2010テンプレート"

          link: "https://products.groupdocs.com/comparison/net/vdx/"
          description: "Microsoft Visio2003-2010XML図面"

          link: "https://products.groupdocs.com/comparison/net/cs/"
          description: "CSharp言語"

          link: "https://products.groupdocs.com/comparison/net/java/"
          description: "Java言語"

          link: "https://products.groupdocs.com/comparison/net/cpp/"
          description: "C++言語"

          link: "https://products.groupdocs.com/comparison/net/js/"
          description: "JavaScript言語"

          link: "https://products.groupdocs.com/comparison/net/py/"
          description: "Python言語"

          link: "https://products.groupdocs.com/comparison/net/rb/"
          description: "Ruby言語"


back_to_top:
    enable: true
---
