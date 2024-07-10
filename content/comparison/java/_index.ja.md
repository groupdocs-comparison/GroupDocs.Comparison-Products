
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: ja
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

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
head_title: "Java 文書比較ライブラリ| 差分チェッカー"
head_description: "ドキュメントのスタイルとコンテンツを比較するネイティブ Java ソフトウェア。複数の形式の文書を比較して相違点を特定します。"

############################# Header ############################
title: "Java API を使用してファイルの違いを比較および確認する"
description: "ファイル、その内容、テキストスタイルなど、類似した文書形式を比較するために、高度に設定可能な文書比較ライブラリを使用して Java 個のアプリケーションを開発してください。"
words:
  for: "にとって"

actions:
  main: "Mavenの無料ダウンロード"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/"
  alt: "ライセンス"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/java/"
  title: "始める準備はできましたか?"
  description: "GroupDocs.Comparison の機能を無料で試すか、ライセンスをリクエストしてください"

release:
  title: "バージョン {0} がリリースされました"
  notes: "新機能を見る"
  downloads: "ダウンロード"

code:
  title: "Java の DOCX 個のファイルを比較"
  more: "その他の例"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
  install: |
    <dependency>
      <groupId>com.groupdocs</groupId>
      <artifactId>groupdocs-comparison</artifactId>
      <version>{0}</version>
    </dependency>
  content: |
    ```java {style=abap}  
    // ソースドキュメントを指定
    try (Comparer comparer = new Comparer("source.docx"))
    {    
      // 1 つまたは複数のターゲットドキュメントを追加
      comparer.add("target.docx");

      // 比較オプションを指定
      CompareOptions options = new CompareOptions();
      options.setShowRevisions(false);

      // 比較して結果を保存する
      final comparer.compare("result.docx", options);
    }    
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison 一目でわかる"
  description: "Java アプリケーションのドキュメント間の違いを比較する API"
  features:
    # feature loop
    - title: "Java でのファイル比較"
      content: "ソースファイルとターゲットファイル間の変更を段落、単語、および文字レベルで検出します。太字、斜体、下線、取り消し線、フォントの種類など、スタイルやフォーマットの変更を識別できます。"

    # feature loop
    - title: "膨大な数の対応フォーマット"
      content: "GroupDocs.Comparison API を使用すると、サポートされている複数の形式のドキュメントを簡単に比較できます。これには PDF、HTML、電子メール、Microsoft Office Word ドキュメント、Excel スプレッドシート、PowerPoint プレゼンテーション、OneNote、Visio 図、テキスト、JPEG、PNG、GIF、BMP、BMP の画像、その他多くの形式が含まれます。"

    # feature loop
    - title: "変更を簡単に適用または却下できます"
      content: "比較された文書間のすべての相違点を適用または却下し、出力文書にエクスポートできます。"

    # feature loop
    - title: "比較概要レポート"
      content: "比較した文書のすべての変更を一覧表示する概要レポートを生成します。"

############################# Platforms ############################
platforms:
  enable: true
  title: "プラットフォーム独立性"
  description: "GroupDocs.Comparison for Java は、以下のオペレーティングシステム、フレームワーク、パッケージマネージャーをサポートしています"
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
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "Maven"
      image: "maven"

############################# File formats ############################
formats:
  enable: true
  title: "対応ファイル形式"
  description: |
    GroupDocs.Comparison for Java は次の [ファイル形式](https://docs.groupdocs.com/comparison/java/supported-document-formats/) での操作をサポートします。
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
      content: "2 つの文書間の違いを簡単に分析して特定できます。"

    # feature loop
    - icon: "note-stack"
      title: "複数の文書を比較"
      content: "複数の文書間の相違点を同時に調べて強調表示します。"

    # feature loop
    - icon: "stacks"
      title: "対応フォーマット"
      content: "さまざまなカテゴリの50を超える広く使用されているドキュメント形式との互換性。"

    # feature loop
    - icon: "rule"
      title: "変更を承認または拒否"
      content: "修正を承認または拒否するオプションを使用して、特定された変更を明確に視覚化します。"

    # feature loop
    - icon: "preview"
      title: "プレビューを生成"
      content: "比較結果を画像プレビューとして保存できます。"

    # feature loop
    - icon: "two-pager"
      title: "コンテンツ比較"
      content: "行単位、段落、単語、文字分析など、さまざまなレベルでのテキストコンテンツの徹底的な比較と、改変に重点を置いています。"

    # feature loop
    - icon: "format_color_text"
      title: "スタイル比較"
      content: "フォーマット要素とスタイル要素の変更を検出して強調表示する機能。"

    # feature loop
    - icon: "folder-managed"
      title: "メタデータを設定"
      content: "ソースファイルまたはターゲットファイルのメタデータを保持するか、ユーザー定義のメタデータ設定を許可するオプション。"

    # feature loop
    - icon: "lock"
      title: "パスワード保護"
      content: "パスワードで保護された文書の分析が容易になり、生成された文書のパスワード保護が可能になります。"

    # feature loop
    - icon: "select"
      title: "特定のページを比較する"
      content: "必要に応じて、文書の特定のセクションまたはページを読み込んで比較します。"

    # feature loop
    - icon: "speaker-notes"
      title: "コメントを表示"
      content: "ソースドキュメントを読み込むときにコメントを柔軟に表示または非表示にすることができます。"

############################# Code samples ############################
code_samples:
  enable: true
  title: "コードサンプル"
  description: "一般的な GroupDocs.Comparison for Java 操作のいくつかのユースケース"
  items:
    # code sample loop
    - title: "パスワードで保護された文書を比較しています。"
      content: |
        [パスワードで保護されている](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/) 文書を比較するには、その文書を指定してから文書を読み込む必要があります。
        {{< landing/code title="パスワードで保護された文書を比較する方法">}}
        ```java {style=abap}
        // ソースドキュメントを読み込み、そのパスワードを指定します
        try (Comparer comparer = new Comparer("source.docx", new LoadOptions("1234")))
        {
            // ターゲットドキュメントをロードし、そのパスワードを指定します
            comparer.add("target.docx", new LoadOptions("5678"));
        
            // 比較結果を指定したファイルに保存する
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "複数の PDF ドキュメントを比較しています。"
      content: |
        GroupDocs.Comparison では [3つ以上の文書を比較](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/) できます。操作は 2 つのファイルを比較する場合とほぼ同じです。あとは、`comparer` クラスにさらにターゲットファイルを追加すればいいだけです。
        {{< landing/code title="3 つ以上の文書を比較する方法">}}
        ```java {style=abap}   
        // ソースドキュメントを読み込む
        try (Comparer comparer = new Comparer("source.docx") 
        {
            // 比較する 2 番目のファイルを指定してください
            comparer.add("target2.docx");

            // 比較する 3 番目のファイルを指定
            comparer.add("target3.docx");

            // 比較結果を指定したファイルに保存する
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---

