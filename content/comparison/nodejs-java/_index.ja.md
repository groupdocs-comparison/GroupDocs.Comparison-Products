
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: ja
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

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
head_title: "Node.js ドキュメント比較 API | 差分チェッカー"
head_description: "Node.js 文書比較 API は、文書比較のための効率的なツールを提供します。Node.js とシームレスに統合され、リアルタイムの変更追跡が可能です。"

############################# Header ############################
title: "Node.js と文書を比較:相違点を強調表示"
description: "GroupDocs.Comparison API を使用して、高度に設定可能な比較機能を備えたネイティブ Java スクリプトアプリケーションを開発してください。ファイル、その内容、テキストスタイルを類似のドキュメントフォーマット間で比較できます。"
words:
  for: "にとって"

actions:
  main: "NPM の無料ダウンロード"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.comparison"
  alt: "ライセンス"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/nodejs-java/"
  title: "始める準備はできましたか?"
  description: "GroupDocs.Comparison の機能を無料で試すか、ライセンスをリクエストしてください"

release:
  title: "バージョン {0} がリリースされました"
  notes: "新機能を見る"
  downloads: "ダウンロード"

code:
  title: "Java スクリプトの BMP 枚の画像を比較"
  more: "その他の例"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.comparison"
  content: |
    ```javascript {style=abap}

    // ソースドキュメントを指定
    const comparer = new Comparer("source.bmp");

    // 1 つまたは複数のターゲットドキュメントを追加
    comparer.add("target.bmp");

    // 比較オプションを指定
    const options = new groupdocs.comparison.CompareOptions();
    options.setGenerateSummaryPage(false);

    // 比較して結果を保存する
    await comparer.compare("result.bmp", options);
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison 一目でわかる"
  description: "PDF、Microsoft Office、HTML、電子メール、Node.js アプリケーション内の画像など、さまざまなタイプのドキュメントを比較するためのAPI"
  features:
    # feature loop
    - title: "詳細な出力レポート"
      content: "GroupDocs.Comparison は、文書内容 (文字、単語、段落、表、グラフ) の変更と文書スタイルの変更を識別します。これにより、相違点、数、種類に関する豊富な情報を含むレポートが顧客に提供されます。"

    # feature loop
    - title: "最も一般的なファイルおよび文書形式がサポートされています"
      content: "GroupDocs.Comparison APIを使用すると、PDF、HTML、電子メール、Microsoft Office Word ドキュメント、Excel スプレッドシート、PowerPoint プレゼンテーション、OneNote、Visio ダイアグラム、テキスト、JPEG、PNG、GIF、BMP 画像など、サポートされているあらゆる形式のドキュメントを効率的に比較できます。"

    # feature loop
    - title: "ドキュメンテーションと例"
      content: "さまざまなプラットフォームでの比較ライブラリの使用に関するコード例については、すでに多くのドキュメントが用意されているので、Node.js アプリケーションで GroupDocs.Comparison API を操作する方法について真剣に考える必要はありません。"

    # feature loop
    - title: "変更を選択して1つのファイルに結合"
      content: "1つのドキュメントに異なるバージョンがある場合は、必要な変更のみを選択し、GroupDocs.Comparison ライブラリを使用して新しいドキュメントをコンパイルできます。"

############################# Platforms ############################
platforms:
  enable: true
  title: "プラットフォーム独立性"
  description: "GroupDocs.Comparison for Node.js via Java は、以下のオペレーティングシステム、フレームワーク、パッケージマネージャーをサポートしています"
  items:
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "macOS"
      image: "finder"      
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NPM"
      image: "npm"  
    # platform loop
    - title: "NuGet"
      image: "nuget"      
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
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"

############################# File formats ############################
formats:
  enable: true
  title: "対応ファイル形式"
  description: |
    GroupDocs.Comparison for Node.js via Java は次の [ファイル形式](https://docs.groupdocs.com/comparison/nodejs-java/supported-document-formats/) での操作をサポートします。
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
  title: "GroupDocs.Comparison for Node.js via Java の機能"
  description: "PDF と Office ドキュメント、画像、その他の形式を簡単に比較"

  items:
    # feature loop
    - icon: "compare"
      title: "使いやすい文書比較"
      content: "2 つの文書内の違いを分析して特定します。"

    # feature loop
    - icon: "note-stack"
      title: "複数の文書を比較"
      content: "複数の文書内の違いを同時に分析して特定します。"

    # feature loop
    - icon: "stacks"
      title: "対応フォーマット"
      content: "さまざまなカテゴリの50を超える一般的なドキュメント形式をサポートします。"

    # feature loop
    - icon: "rule"
      title: "変更を承認または拒否"
      content: "識別された変更を明確に視覚的に表示し、変更を受け入れるか拒否するかを選択できます。"

    # feature loop
    - icon: "preview"
      title: "プレビューを生成"
      content: "比較結果を画像として保存します。"

    # feature loop
    - icon: "two-pager"
      title: "コンテンツ比較"
      content: "テキストコンテンツを 1 行ごと、段落ごと、単語ごと、文字ごとに比較します。変更点を強調表示します。"

    # feature loop
    - icon: "format_color_text"
      title: "スタイル比較"
      content: "書式とスタイルの変更を検出します。"

    # feature loop
    - icon: "folder-managed"
      title: "メタデータを設定"
      content: "ソースファイルまたはターゲットファイルのメタデータを保持するか、ユーザーがメタデータを指定できるようにします。"

    # feature loop
    - icon: "lock"
      title: "パスワード保護"
      content: "暗号化された文書を解析するか、生成された文書をパスワードで保護します。"

    # feature loop
    - icon: "select"
      title: "特定のページを比較する"
      content: "文書の特定のセクションまたはページだけをロードします。"

    # feature loop
    - icon: "speaker-notes"
      title: "コメントを表示"
      content: "ソース文書を読み込むときに、コメントを表示するか非表示にするかを選択できます。"

############################# Code samples ############################
code_samples:
  enable: true
  title: "コードサンプル"
  description: "一般的な GroupDocs.Comparison for Node.js via Java 操作のいくつかのユースケース"
  items:
    # code sample loop
    - title: "パスワードで保護された文書を比較しています。"
      content: |
        [パスワードで保護されている](https://docs.groupdocs.com/comparison/nodejs-java/load-password-protected-documents/) 文書を比較するには、その文書を指定してから文書を読み込む必要があります。
        {{< landing/code title="パスワードで保護された文書を比較する方法">}}
        ```javascript {style=abap}

        import { Comparer, LoadOptions } from '@groupdocs/groupdocs.comparison'

        // ソースドキュメントを読み込み、そのパスワードを指定します
        const comparer = new Comparer("source.docx", new LoadOptions("1234"));

        // ターゲットドキュメントをロードし、そのパスワードを指定します
        comparer.add("target.docx", new LoadOptions("5678"));

        // 比較結果を指定したファイルに保存する
        comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "複数の PDF ドキュメントを比較しています。"
      content: |
        GroupDocs.Comparison では [3つ以上の文書を比較](https://docs.groupdocs.com/comparison/nodejs-java/compare-multiple-documents/) できます。操作は 2 つのファイルを比較する場合とほぼ同じです。あとは、`comparer` クラスにさらにターゲットファイルを追加すればいいだけです。
        {{< landing/code title="3 つ以上の文書を比較する方法">}}
        ```javascript {style=abap}
        import { Comparer } from '@groupdocs/groupdocs.comparison'

        // ソースドキュメントを読み込む
        const comparer = new Comparer(source.pdf");

        // 比較する 2 番目のファイルを指定してください
        comparer.add("target2.pdf");

        // 比較する 3 番目のファイルを指定
        comparer.add("target3.pdf");

        // 比較結果を指定したファイルに保存する
        comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---