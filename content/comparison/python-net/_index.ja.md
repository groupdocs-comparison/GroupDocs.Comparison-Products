
---
############################# Static ############################
layout: "landing"
date: 2024-12-19T07:50:02
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
head_title: "Python ドキュメント比較ツール |文書分析"
head_description: "徹底的なドキュメント分析のための Python ドキュメント比較ツールの機能を体験してください。 Python と簡単に統合して、変更を包括的に追跡します。"

############################# Header ############################
title: "ドキュメントを Python と比較: 相違点を強調表示"
description: "GroupDocs.Comparison API を利用して、カスタマイズ可能な比較機能を備えたネイティブ アプリケーションを Python で作成します。ファイル、そのコンテンツ、およびドキュメント形式全体のスタイルのバリエーションを調べます。"
words:
  for: "にとって"

actions:
  main: "今すぐ無料の PyPi を入手してダウンロード"
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
  title: "Python を使用して BMP 画像を比較する"
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
  description: "Python アプリケーション内で PDF、Microsoft Office ファイル、HTML、電子メール、画像などの広く使用されているドキュメント タイプを比較するために設計された API。"
  features:
    # feature loop
    - title: "包括的な出力レポート"
      content: "GroupDocs.Comparison は、ドキュメントのコンテンツ (文字、単語、段落、表、グラフ) の変更とドキュメントのスタイルの変更を検出します。ユーザーは、変更の性質と数を示す詳細なレポートを受け取ります。"

    # feature loop
    - title: "幅広いファイルおよびドキュメント形式"
      content: "GroupDocs.Comparison API を使用すると、PDF、HTML、電子メール、Microsoft Office Word、Excel ワークブック、PowerPoint ファイル、OneNote ノート、Visio 図、テキスト ドキュメント、JPEG、PNG、GIF、BMP 画像などの形式のドキュメントを比較できます。他の多くの人の中でも。"

    # feature loop
    - title: "徹底したドキュメントとコードサンプル"
      content: "さまざまなプラットフォームにわたる比較ライブラリの詳細なドキュメントとサンプル コードがすぐに入手できるため、GroupDocs.Comparison API の Python アプリケーションへの統合が簡素化されます。"

    # feature loop
    - title: "変更を選択して 1 つのドキュメントに結合する"
      content: "ドキュメントのさまざまなバージョンを所有している場合は、GroupDocs.Comparison ライブラリを使用して、変更を単一の新しいファイルに選択的にコンパイルできます。"

############################# Platforms ############################
platforms:
  enable: true
  title: "プラットフォーム独立性"
  description: "GroupDocs.Comparison for Python via .NET は、次のオペレーティング システム、フレームワーク、パッケージ マネージャーと互換性があります。"
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
    GroupDocs.Comparison for Python via .NET は、次の [ファイル形式](https://docs.groupdocs.com/comparison/net/supported-document-formats/) で動作できます。
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
  description: "PDF、Office ドキュメント、画像、その他のさまざまな形式をシームレスに比較します。"

  items:
    # feature loop
    - icon: "compare"
      title: "直感的なドキュメントの比較"
      content: "2 つの文書間の相違点を調べて強調表示します。"

    # feature loop
    - icon: "note-stack"
      title: "複数の文書の比較"
      content: "複数のドキュメントの相違点を同時に検査します。"

    # feature loop
    - icon: "stacks"
      title: "広範なフォーマットのサポート"
      content: "さまざまなカテゴリにわたって一般的に使用される 50 を超えるドキュメント形式と互換性があります。"

    # feature loop
    - icon: "rule"
      title: "変更を承認または拒否する"
      content: "変更を明確に視覚化し、編集を承認または拒否するためのオプションを提供します。"

    # feature loop
    - icon: "preview"
      title: "ビジュアルプレビューの生成"
      content: "比較結果のプレビューを画像形式で作成します。"

    # feature loop
    - icon: "two-pager"
      title: "テキストベースのコンテンツの比較"
      content: "行ごと、段落ごと、単語ごと、または文字ごとの比較を実行して、変更を強調表示します。"

    # feature loop
    - icon: "format_color_text"
      title: "書式変更の検出"
      content: "文書のスタイルと書式設定の変更を特定します。"

    # feature loop
    - icon: "folder-managed"
      title: "カスタマイズ可能なメタデータの処理"
      content: "ソース ファイルまたはターゲット ファイルのメタデータを保持するか、ユーザーが新しいメタデータを定義できるようにします。"

    # feature loop
    - icon: "lock"
      title: "パスワードで保護されたファイルの処理"
      content: "暗号化されたドキュメントを操作したり、パスワードで保護された安全なドキュメントを作成したりできます。"

    # feature loop
    - icon: "select"
      title: "焦点を絞ったページの比較"
      content: "ドキュメントの特定のセクションまたは個々のページを選択して比較します。"

    # feature loop
    - icon: "speaker-notes"
      title: "コメントの公開設定を管理する"
      content: "ソース文書を調べるときに、コメントを表示するか非表示にするかを決定します。"

############################# Code samples ############################
code_samples:
  enable: true
  title: "コードサンプル"
  description: "GroupDocs.Comparison for Python via .NET の機能を利用するための一般的なシナリオを確認します。"
  items:
    # code sample loop
    - title: "パスワード保護されたドキュメントの比較"
      content: |
        [パスワードで保護されている]ドキュメント(https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/)を比較するには、ドキュメントをロードするときにパスワードを指定する必要があります。
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