
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: ja
product: "Comparison"
product_tag: "comparison"
platform: "Net"
platform_tag: "net"

############################# Drop-down ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"
    # supported_platforms loop
    - title: "Java"
      tag: "java"
    # supported_platforms loop
    - title: "Node.js"
      tag: "nodejs-java"
    # supported_platforms loop
    - title: "Python"
      tag: "python-net"

############################# Head ############################
head_title: "C# .NET 文書比較ソフトウェア | 差分チェッカー"
head_description: "C# .NET 文書のスタイルと内容を比較するソフトウェア。サポートされている複数の形式の文書を比較して、ファイル間の違いを特定できます。"

############################# Header ############################
title: "C# .NET ソリューションのドキュメントを簡単に比較できます"
description: "さまざまなドキュメント形式のコンテンツやスタイルによるファイル比較を可能にする柔軟なドキュメント比較 API を使用して C# 個のアプリケーションを構築できます。"
words:
  for: "にとって"

actions:
  main: "無料 NuGet ダウンロード"
  main_link: "https://www.nuget.org/packages/GroupDocs.Comparison"
  alt: "ライセンス"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/net/"
  title: "始める準備はできましたか?"
  description: "GroupDocs.Comparison の機能を無料で試すか、ライセンスをリクエストしてください"

release:
  title: "バージョン {0} がリリースされました"
  notes: "新機能を見る"
  downloads: "ダウンロード"

code:
  title: "C# の DOCX 個のファイルを比較"
  more: "その他の例"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET"
  install: "dotnet add package GroupDocs.Comparison"
  content: |
    ```csharp {style=abap}   
    // ソースドキュメントを指定
    using (Comparer comparer = new Comparer("source.docx"))
    {
        // 1 つまたは複数のターゲットドキュメントを追加
        comparer.Add("target.docx");

        // 比較オプションを指定
        CompareOptions options = new CompareOptions() 
        {ShowRevisions = false};

        // 比較して結果を保存する
        comparer.Compare("result.docx", options);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison 一目でわかる"
  description: ".NET アプリケーションのドキュメント間の違いを比較する API"
  features:
    # feature loop
    - title: "C# でのファイル比較"
      content: "ソースファイルとターゲットファイルの違いを検出して、段落、単語、および文字レベルでの変更を検出します。太字、斜体、下線、取り消し線、フォントの種類など、スタイルやフォーマットの変更を識別します。"

    # feature loop
    - title: "最も一般的なファイルおよび文書形式がサポートされています"
      content: "GroupDocs.Comparison API を使用すると、PDF、HTML、電子メール、Microsoft Office ドキュメント (Word、Excel、PowerPoint、OneNote、Visio)、さまざまな画像タイプ (JPEG、PNG、GIF、BMP)、テキストファイルなど、さまざまな形式のドキュメントを効率的に比較できます。"

    # feature loop
    - title: "変更を簡単に適用または却下できます"
      content: "GroupDocs.Comparison APIを使用して比較された文書で特定された各相違点を選択的に適用または拒否できるため、最終出力文書にエクスポートする前にカスタマイズできます。"

    # feature loop
    - title: "比較概要レポート"
      content: "比較した文書で見つかったすべての変更を詳述した相違点の要約レポートを生成し、参照用に保存します。"

############################# Platforms ############################
platforms:
  enable: true
  title: "プラットフォーム独立性"
  description: "GroupDocs.Comparison for .NET は、以下のオペレーティングシステム、フレームワーク、パッケージマネージャーをサポートしています"
  items:
    # platform loop
    - title: "Amazon"
      image: "amazon"
    # platform loop
    - title: "Docker"
      image: "docker"
    # platform loop
    - title: "Azure"
      image: "azure"
    # platform loop
    - title: "VS Code"
      image: "vs_code"
    # platform loop
    - title: "ReSharper"
      image: "resharper"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NuGet"
      image: "nuget"

############################# File formats ############################
formats:
  enable: true
  title: "対応ファイル形式"
  description: |
    GroupDocs.Comparison for .NET は次の [ファイル形式](https://docs.groupdocs.com/comparison/net/supported-document-formats/) での操作をサポートします。
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office および OpenDocument フォーマット
        * **Word:** DOCX, DOC, DOCM,DOT, DOTM, DOTX, RTX, RTF, TXT
        * **Excel:** XLSX, XLS, XLT, XLTM, XLSB, XLSM
        * **PowerPoint:** PPTX, PPT, POT, POTX, PPS, PPSX
        * **Outlook:** EML, EMLX, MSG
        * **OneNote:** ONE
        * **OpenDocument:** ODT, ODP, OTP, ODS, OTT
        * **固定ページレイアウト:** PDF        
    # group loop
    - color: "blue"
      content: |
        ### 画像、グラフィックス、ダイアグラム
        * **ラスター画像:** BMP, GIF, JPG, JPEG, PNG
        * **医療画像処理:** DICOM
        * **Microsoft Visio:** VSDX, VSD, VSS, VST, VDX
        * **AutoCAD Drawing:** DWG, DXF
      # group loop
    - color: "red"
      content: |
        ### その他
        * **[テキスト]:** TXT
        * **プログラミング言語:** CS, Java, CPP, JS, PY, RB, PL, ASM, GROOVY, JSON, PHP, SQL, LOG, DIFF, LESS, SCALA
        * **ウェブ:** HTM, HTML, MHT, MHTML
        * **電子書籍:** MOBI, DjVu
        * **区切り文字で区切られた値:** CSV

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Comparison の機能"
  description: "PDF と Office ドキュメント、画像、その他の形式を簡単に比較"

  items:
    # feature loop
    - icon: "compare"
      title: "使いやすい文書比較"
      content: "2 つの文書間の違いを分析して特定します。"

    # feature loop
    - icon: "note-stack"
      title: "複数の文書を比較"
      content: "複数の文書間の相違点を同時に分析して特定します。"

    # feature loop
    - icon: "stacks"
      title: "対応フォーマット"
      content: "さまざまなカテゴリの50を超える広く使用されているドキュメント形式と互換性があり、幅広い適用性を保証します。"

    # feature loop
    - icon: "rule"
      title: "変更を承認または拒否"
      content: "検出された変更が視覚的にわかりやすく表示され、変更を受け入れるか拒否するかのオプションも付いています。"

    # feature loop
    - icon: "preview"
      title: "プレビューを生成"
      content: "比較結果を画像プレビューとして保存して、簡単に参照および共有できます。"

    # feature loop
    - icon: "two-pager"
      title: "コンテンツ比較"
      content: "行ごと、段落、単語、文字など、さまざまなレベルでテキストを徹底的に比較し、違いを強調してわかりやすくします。"

    # feature loop
    - icon: "format_color_text"
      title: "スタイルとフォーマットの比較"
      content: "文書のフォーマットやスタイルの変更を検出して強調表示し、包括的なレビューを行います。"

    # feature loop
    - icon: "folder-managed"
      title: "柔軟なメタデータ設定"
      content: "ソースファイルまたはターゲットファイルのメタデータを保存するか、ユーザーの好みに合わせてカスタマイズします。"

    # feature loop
    - icon: "lock"
      title: "パスワード保護"
      content: "パスワードで保護された文書を分析し、出力文書をパスワード暗号化で保護してセキュリティを強化します。"

    # feature loop
    - icon: "select"
      title: "選択的ページ比較"
      content: "文書の特定のセクションまたはページを読み込んで比較し、的を絞った分析を行います。"

    # feature loop
    - icon: "speaker-notes"
      title: "コメントを表示"
      content: "ソース文書を読み込むときにコメントを表示するか非表示にするかを選択して、比較プロセスをより細かく制御できます。"

############################# Code samples ############################
code_samples:
  enable: true
  title: "コードサンプル"
  description: "一般的な GroupDocs.Comparison for .NET 操作のいくつかのユースケース"
  items:
    # code sample loop
    - title: "パスワードで保護された文書を比較しています。"
      content: |
        [パスワードで保護されている](https://docs.groupdocs.com/comparison/net/load-password-protected-documents/) 文書を比較するには、その文書を指定してから文書を読み込む必要があります。
        {{< landing/code title="パスワードで保護された文書を比較する方法">}}
        ```csharp {style=abap}
        // ソースドキュメントを読み込み、そのパスワードを指定します
        using(Comparer comparer = new Comparer("source.docx", new LoadOptions() {Password = "1234"}))  
        {
            // ターゲットドキュメントをロードし、そのパスワードを指定します
            comparer.Add("target.docx", new LoadOptions() {Password = "5678"});

            // 比較結果を指定したファイルに保存する
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "複数の PDF ドキュメントを比較しています。"
      content: |
        GroupDocs.Comparison では [3つ以上の文書を比較](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/) できます。操作は 2 つのファイルを比較する場合とほぼ同じです。あとは、`comparer` クラスにさらにターゲットファイルを追加すればいいだけです。
        {{< landing/code title="3 つ以上の文書を比較する方法">}}
        ```csharp {style=abap}   
        // ソースドキュメントを読み込む
        using(Comparer comparer = new Comparer("source.docx") 
        {
            // 比較する 2 番目のファイルを指定してください
            comparer.Add("target2.docx");
            
            // 比較する 3 番目のファイルを指定
            comparer.Add("target3.docx");
            
            // 比較結果を指定したファイルに保存する
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---
