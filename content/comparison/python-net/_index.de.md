
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: de
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
head_title: "Python Dokumentvergleichs-API | Diff-Checker"
head_description: "Die Python Document Compare API bietet effiziente Tools zum Vergleichen von Dokumenten. Nahtlose Integration mit Python für sofortige Änderungsverfolgung"

############################# Header ############################
title: "Vergleichen Sie Dokumente mit Python: Markieren Sie alle Unterschiede"
description: "Verwenden Sie die GroupDocs.Comparison-API, um native Python-Anwendungen mit hochgradig konfigurierbaren Vergleichsfunktionen zu entwickeln. Vergleichen Sie Dateien, deren Inhalte und Textstile zwischen ähnlichen Dokumentformaten."
words:
  for: "zum"

actions:
  main: "Kostenloser PyPi-Download"
  main_link: "https://pypi.org/project/groupdocs-comparison-net/"
  alt: "Lizenzierung"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/python-net/"
  title: "Bereit loszulegen?"
  description: "Testen Sie GroupDocs.Comparison Funktionen kostenlos oder fordern Sie eine Lizenz an"

release:
  title: "Version {0} veröffentlicht"
  notes: "Schau dir an, was es Neues gibt"
  downloads: "herunterladbare"

code:
  title: "Vergleichen Sie BMP-Bilder in Python"
  more: "Mehr Beispiele"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET/"
  install: "pip install groupdocs-comparison-net"
  content: |
    ```python {style=abap}
    def run():

        # Geben Sie das Quelldokument an
        with groupdocs.comparison.Comparer("in.bmp") as comparer:

            # Fügen Sie ein oder mehrere Zieldokumente hinzu
            comparer.add("target.bmp")

            # Vergleichsoptionen angeben
            options = new groupdocs.comparison.CompareOptions()
            options.setGenerateSummaryPage(false)

            # Vergleichen und Ergebnis speichern
            comparer.compare("result.bmp", options)
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison auf einen Blick"
  description: "Eine API zum Vergleich gängiger Dokumenttypen wie PDF, Microsoft Office, HTML, E-Mails oder Bilder in Python-Anwendungen."
  features:
    # feature loop
    - title: "Detaillierte Ausgabeberichte"
      content: "GroupDocs.Comparison identifiziert Änderungen im Dokumentinhalt (Zeichen, Wörter, Absätze, Tabellen, Diagramme) sowie Änderungen im Dokumentstil. Es bietet Benutzern einen Bericht mit detaillierten Informationen zu Unterschieden, einschließlich deren Anzahl und Art."

    # feature loop
    - title: "Unterstützt gängige Datei- und Dokumentformate"
      content: "Mit der GroupDocs.Comparison-API können Sie Dokumente in Formaten wie PDF, HTML, E-Mail, Microsoft Office Word, Excel-Tabellen, PowerPoint-Präsentationen, OneNote, Visio-Diagramme, Textdateien, JPEG, PNG, GIF, BMP-Bilder usw. effizient vergleichen. und viele andere Formate."

    # feature loop
    - title: "Umfassende Dokumentation und Beispiele"
      content: "Es stehen umfangreiche Dokumentationen und Codebeispiele für die Verwendung der Vergleichsbibliothek auf verschiedenen Plattformen zur Verfügung, sodass Sie die GroupDocs.Comparison-API problemlos in Ihre Python-Anwendung integrieren können."

    # feature loop
    - title: "Wählen Sie Änderungen aus und führen Sie sie in einer Datei zusammen"
      content: "Wenn Sie über verschiedene Versionen eines Dokuments verfügen, können Sie mithilfe der GroupDocs.Comparison-Bibliothek bestimmte Änderungen auswählen und ein neues Dokument kompilieren."

############################# Platforms ############################
platforms:
  enable: true
  title: "Plattformunabhängigkeit"
  description: "GroupDocs.Comparison for Python via .NET unterstützt die folgenden Betriebssysteme, Frameworks und Paketmanager"
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
  title: "Unterstützte Dateiformate"
  description: |
    GroupDocs.Comparison for Python via .NET unterstützt Vorgänge mit den folgenden [Dateiformaten](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office & OpenDocument Formate
        * **Word:** DOCX, DOC, DOCM,DOT, DOTM, DOTX, RTX, RTF, TXT
        * **Excel:** XLSX, XLS, XLT, XLTM, XLSB, XLSM
        * **PowerPoint:** PPTX, PPT, POT, POTX, PPS, PPSX
        * **Outlook:** EML, EMLX, MSG
        * **OneNote:** ONE
        * **OpenDocument:** ODT, ODP, OTP, ODS, OTT
        * **Festes Seitenlayout:** PDF        
    # group loop
    - color: "blue"
      content: |
        ### Bilder, Grafiken und Diagramme
        * **Rasterbilder:** BMP, GIF, JPG, JPEG, PNG
        * **Medizinische Bildgebung:** DICOM
        * **Microsoft Visio:** VSDX, VSD, VSS, VST, VDX
        * **AutoCAD Drawing:** DWG, DXF
      # group loop
    - color: "red"
      content: |
        ### Andere
        * **Text:** TXT
        * **Programmiersprachen:** CS, Java, CPP, JS, PY, RB, PL, ASM, GROOVY, JSON, PHP, SQL, LOG, DIFF, LESS, SCALA
        * **Netz:** HTM, HTML, MHT, MHTML
        * **E-Bücher:** MOBI, DjVu
        * **Durch Trennzeichen getrennte Werte:** CSV

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Comparison for Python via .NET Funktionen"
  description: "Vergleichen Sie ganz einfach PDF- und Office-Dokumente, Bilder und andere Formate."

  items:
    # feature loop
    - icon: "compare"
      title: "Benutzerfreundlicher Dokumentenvergleich"
      content: "Analysieren und identifizieren Sie Unterschiede zwischen zwei Dokumenten."

    # feature loop
    - icon: "note-stack"
      title: "Vergleichen Sie mehrere Dokumente"
      content: "Analysieren und identifizieren Sie Unterschiede in mehreren Dokumenten gleichzeitig."

    # feature loop
    - icon: "stacks"
      title: "Unterstützte Formate"
      content: "Unterstützt mehr als 50 gängige Dokumentformate aus verschiedenen Kategorien."

    # feature loop
    - icon: "rule"
      title: "Änderungen akzeptieren oder ablehnen"
      content: "Klare visuelle Darstellung der identifizierten Änderungen mit der Möglichkeit, Änderungen zu akzeptieren oder abzulehnen."

    # feature loop
    - icon: "preview"
      title: "Vorschauen generieren"
      content: "Speichern Sie die Vergleichsergebnisse als Bilder."

    # feature loop
    - icon: "two-pager"
      title: "Inhaltsvergleich"
      content: "Vergleichen Sie Textinhalte Zeile für Zeile, nach Absätzen, nach Wörtern oder nach Zeichen. Markieren Sie die Änderungen."

    # feature loop
    - icon: "format_color_text"
      title: "Stilvergleich"
      content: "Erkennen Sie Änderungen in Formatierung und Stilen."

    # feature loop
    - icon: "folder-managed"
      title: "Metadaten festlegen"
      content: "Behalten Sie Metadaten entweder aus den Quell- oder Zieldateien bei oder lassen Sie zu, dass sie von Benutzern angegeben werden."

    # feature loop
    - icon: "lock"
      title: "Passwortschutz"
      content: "Analysieren Sie verschlüsselte Dokumente oder sichern Sie das resultierende Dokument mit einem Passwort."

    # feature loop
    - icon: "select"
      title: "Vergleichen Sie bestimmte Seiten"
      content: "Laden und vergleichen Sie bestimmte Abschnitte oder Seiten eines Dokuments."

    # feature loop
    - icon: "speaker-notes"
      title: "Kommentare anzeigen"
      content: "Wählen Sie, ob Kommentare beim Laden des Quelldokuments ausgeblendet oder angezeigt werden sollen."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Codebeispiele"
  description: "Entdecken Sie typische Anwendungsfälle von GroupDocs.Comparison for Python via .NET-Vorgängen"
  items:
    # code sample loop
    - title: "Vergleich passwortgeschützter Dokumente"
      content: |
        Um Dokumente zu vergleichen, die [durch ein Passwort geschützt](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/) sind, müssen Sie beim Laden der Dokumente das Passwort angeben:
        {{< landing/code title="So vergleichen Sie passwortgeschützte Dokumente.">}}
        ```python {style=abap}
        def run():

            # Laden Sie das Quelldokument und geben Sie sein Passwort an
            with groupdocs.comparison.Comparer("source.docx", new LoadOptions("1234")) as comparer:

                # Laden Sie das Zieldokument und geben Sie sein Passwort an
                comparer.add("target.docx", new LoadOptions("5678"));

                # Vergleichsergebnis in einer angegebenen Datei speichern
                comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Vergleich mehrerer PDF Dokumente."
      content: |
        GroupDocs.Comparison ermöglicht es Ihnen, [mehr als zwei Dokumente zu vergleichen](https://docs.groupdocs.com/comparison/python-net/compare-multiple-documents/). Die Operation ist fast dieselbe wie beim Vergleich zweier Dateien. Sie müssen der Klasse `comparer` nur weitere Zieldateien hinzufügen.
        {{< landing/code title="So vergleichen Sie drei oder mehr Dokumente.">}}
        ```python {style=abap}
        def run():

            # Laden Sie das Quelldokument
            with groupdocs.comparison.Comparer(source.pdf") as comparer:

                # Geben Sie die zweite Datei für den Vergleich an
                comparer.add("target2.pdf");

                # Geben Sie die dritte Datei für den Vergleich an
                comparer.add("target3.pdf");

                # Vergleichsergebnis in einer angegebenen Datei speichern
                comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---