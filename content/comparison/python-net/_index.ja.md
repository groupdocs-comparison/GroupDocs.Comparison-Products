
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: ja
product: "Comparison"
product_tag: "comparison"
platform: "Python via .NET"
platform_tag: "python-net"

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
head_title: "{{ランタイム}} ドキュメント比較 API |差分チェッカー"
head_description: "Python Document Comparison API は、ドキュメントを比較するための効率的なツールを提供します。 Python とシームレスに統合し、即座に変更を追跡します"

############################# Header ############################
title: "ドキュメントを Python と比較: 相違点を強調表示"
description: "GroupDocs.Comparison API を使用して、高度に構成可能な比較機能を備えたネイティブ Python アプリケーションを開発します。類似したドキュメント形式間でファイル、そのコンテンツ、テキスト スタイルを比較します。"
words:
  for: "にとって"

actions:
  main: "無料の PyPi ダウンロード"
  main_link: "https://pypi.org/project/groupdocs-comparison-net/"
  alt: "ライセンス"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/python-net/"
  title: "始める準備はできましたか?"
  description: "GroupDocs.Comparison の機能を無料で試すか、ライセンスをリクエストしてください"

release:
  title: "バージョン {0} がリリースされました"
  notes: "新機能を見る"
  downloads: "ダウンロード"

code:
  title: "Python で BMP 画像を比較"
  more: "その他の例"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET/"
  install: "pip install groupdocs-comparison-net"
  content: |
    ```python {style=abap}
    def run():

        # ソースドキュメントを指定
        with groupdocs.comparison.Comparer("in.bmp") as comparer:

            # 1 つまたは複数のターゲットドキュメントを追加
            comparer.add("target.bmp")

            # 比較オプションを指定
            options = new groupdocs.comparison.CompareOptions()
            options.setGenerateSummaryPage(false)

            # 比較して結果を保存する
            comparer.compare("result.bmp", options)
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison 一目でわかる"
  description: "Python アプリケーション内の PDF、Microsoft Office、HTML、電子メール、画像などの一般的なドキュメント タイプを比較する API。"
  features:
    # feature loop
    - title: "詳細な出力レポート"
      content: "GroupDocs.Comparison は、ドキュメント コンテンツ (文字、単語、段落、表、グラフ) の変更とドキュメント スタイルの変更を識別します。これは、相違点の数や種類などの詳細情報を含むレポートをユーザーに提供します。"

    # feature loop
    - title: "一般的なファイルおよびドキュメント形式をサポート"
      content: "GroupDocs.Comparison API を使用すると、PDF、HTML、電子メール、Microsoft Office Word、Excel スプレッドシート、PowerPoint プレゼンテーション、OneNote、Visio 図、テキスト ファイル、JPEG、PNG、GIF、BMP 画像などの形式のドキュメントを効率的に比較できます。および他の多くの形式。"

    # feature loop
    - title: "包括的なドキュメントと例"
      content: "さまざまなプラットフォームで比較ライブラリを使用するための広範なドキュメントとコード例が用意されているため、GroupDocs.Comparison API を Python アプリケーションに簡単に統合できます。"

    # feature loop
    - title: "変更を選択して 1 つのファイルにマージする"
      content: "ドキュメントのバージョンが異なる場合は、特定の変更を選択し、GroupDocs.Comparison ライブラリを使用して新しいドキュメントをコンパイルできます。"

############################# Platforms ############################
platforms:
  enable: true
  title: "プラットフォーム独立性"
  description: "GroupDocs.Comparison for Python via .NET は、次のオペレーティング システム、フレームワーク、パッケージ マネージャーをサポートしています"
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
    GroupDocs.Comparison for Python via .NET は、次の [ファイル形式](https://docs.groupdocs.com/comparison/net/supported-document-formats/) での操作をサポートしています。
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
  title: "GroupDocs.Comparison for Python via .NET の機能"
  description: "PDF と Office のドキュメント、画像、その他の形式を簡単に比較します。"

  items:
    # feature loop
    - icon: "compare"
      title: "ユーザーフレンドリーなドキュメントの比較"
      content: "2 つの文書間の相違点を分析して特定します。"

    # feature loop
    - icon: "note-stack"
      title: "複数のドキュメントを比較する"
      content: "複数のドキュメント内の差異を同時に分析して特定します。"

    # feature loop
    - icon: "stacks"
      title: "サポートされている形式"
      content: "さまざまなカテゴリの 50 以上の一般的なドキュメント形式をサポートします。"

    # feature loop
    - icon: "rule"
      title: "変更を受け入れるか拒否する"
      content: "変更を受け入れるか拒否するかを選択できる、特定された変更を明確に視覚的に表現します。"

    # feature loop
    - icon: "preview"
      title: "プレビューの生成"
      content: "比較結果を画像として保存します。"

    # feature loop
    - icon: "two-pager"
      title: "内容の比較"
      content: "テキストの内容を行ごと、段落ごと、単語ごと、または文字ごとに比較します。変更を強調表示します。"

    # feature loop
    - icon: "format_color_text"
      title: "スタイルの比較"
      content: "書式設定とスタイルの変更を検出します。"

    # feature loop
    - icon: "folder-managed"
      title: "メタデータの設定"
      content: "ソース ファイルまたはターゲット ファイルのメタデータを保持するか、ユーザーによるメタデータの指定を許可します。"

    # feature loop
    - icon: "lock"
      title: "パスワード保護"
      content: "暗号化されたドキュメントを分析するか、結果として得られたドキュメントをパスワードで保護します。"

    # feature loop
    - icon: "select"
      title: "特定のページを比較する"
      content: "ドキュメントの特定のセクションまたはページをロードして比較します。"

    # feature loop
    - icon: "speaker-notes"
      title: "コメントの表示"
      content: "ソースドキュメントをロードするときにコメントを非表示にするか表示するかを選択します。"

############################# Code samples ############################
code_samples:
  enable: true
  title: "コードサンプル"
  description: "GroupDocs.Comparison for Python via .NET 操作の一般的な使用例を調べる"
  items:
    # code sample loop
    - title: "パスワードで保護されたドキュメントの比較"
      content: |
        [パスワードで保護されているドキュメント](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/)を比較するには、ドキュメントをロードするときにパスワードを指定する必要があります。
        {{< landing/code title="パスワードで保護された文書を比較する方法">}}
        ```python {style=abap}
        def run():

            # ソースドキュメントを読み込み、そのパスワードを指定します
            with groupdocs.comparison.Comparer("source.docx", new LoadOptions("1234")) as comparer:

                # ターゲットドキュメントをロードし、そのパスワードを指定します
                comparer.add("target.docx", new LoadOptions("5678"));

                # 比較結果を指定したファイルに保存する
                comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "複数の PDF ドキュメントを比較しています。"
      content: |
        GroupDocs.Comparison では [3つ以上の文書を比較](https://docs.groupdocs.com/comparison/python-net/compare-multiple-documents/) できます。操作は 2 つのファイルを比較する場合とほぼ同じです。あとは、`comparer` クラスにさらにターゲットファイルを追加すればいいだけです。
        {{< landing/code title="3 つ以上の文書を比較する方法">}}
        ```python {style=abap}
        def run():

            # ソースドキュメントを読み込む
            with groupdocs.comparison.Comparer(source.pdf") as comparer:

                # 比較する 2 番目のファイルを指定してください
                comparer.add("target2.pdf");

                # 比較する 3 番目のファイルを指定
                comparer.add("target3.pdf");

                # 比較結果を指定したファイルに保存する
                comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---