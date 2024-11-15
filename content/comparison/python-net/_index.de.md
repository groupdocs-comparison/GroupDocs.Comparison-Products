
---
############################# Static ############################
layout: "landing"
date: 2024-11-14T22:58:46
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
head_title: "Python Dokumentvergleichstool | Dokumentenanalyse"
head_description: "Entdecken Sie die Leistungsfähigkeit des Python-Dokumentenvergleichstools für eine gründliche Dokumentenanalyse. Lässt sich mühelos in Python integrieren, um eine umfassende Nachverfolgung von Änderungen zu ermöglichen."

############################# Header ############################
title: "Vergleichen Sie Dokumente mit Python: Markieren Sie alle Unterschiede"
description: "Nutzen Sie die GroupDocs.Comparison-API, um native Anwendungen in Python mit anpassbaren Vergleichsfunktionen zu erstellen. Untersuchen Sie Dateien, ihren Inhalt und Stilvariationen in verschiedenen Dokumentformaten."
words:
  for: "zum"

actions:
  main: "Holen Sie sich jetzt Ihren kostenlosen PyPi-Download"
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
  title: "Vergleichen Sie BMP-Bilder mit Python"
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
  description: "Eine API zum Vergleich weit verbreiteter Dokumenttypen wie PDFs, Microsoft Office-Dateien, HTML, E-Mails oder Bilder in Python-Anwendungen."
  features:
    # feature loop
    - title: "Umfassende Ausgabeberichte"
      content: "GroupDocs.Comparison erkennt Änderungen im Dokumentinhalt (Zeichen, Wörter, Absätze, Tabellen, Diagramme) sowie Änderungen im Dokumentstil. Benutzer erhalten einen detaillierten Bericht, der Art und Anzahl der Änderungen hervorhebt."

    # feature loop
    - title: "Große Auswahl an Datei- und Dokumentformaten"
      content: "Mit der GroupDocs.Comparison-API können Sie Dokumente in Formaten wie PDF, HTML, E-Mail, Microsoft Office Word, Excel-Arbeitsmappen, PowerPoint-Dateien, OneNote-Notizen, Visio-Diagramme, Textdokumente, JPEG, PNG, GIF, BMP-Bilder vergleichen. unter vielen anderen."

    # feature loop
    - title: "Gründliche Dokumentation und Codebeispiele"
      content: "Ausführliche Dokumentation und Beispielcodes für die Vergleichsbibliothek auf verschiedenen Plattformen sind sofort verfügbar und vereinfachen die Integration der GroupDocs.Comparison-API in Ihre Python-Anwendungen."

    # feature loop
    - title: "Wählen Sie Änderungen aus und kombinieren Sie sie in einem Dokument"
      content: "Wenn Sie über verschiedene Versionen eines Dokuments verfügen, können Sie mithilfe der Bibliothek GroupDocs.Comparison Änderungen gezielt in einer einzigen neuen Datei kompilieren."

############################# Platforms ############################
platforms:
  enable: true
  title: "Plattformunabhängigkeit"
  description: "GroupDocs.Comparison for Python via .NET ist mit den folgenden Betriebssystemen, Frameworks und Paketmanagern kompatibel."
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
    GroupDocs.Comparison for Python via .NET kann mit den folgenden [Dateiformaten](https://docs.groupdocs.com/comparison/net/supported-document-formats/) arbeiten.
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
  title: "Fähigkeiten von GroupDocs.Comparison for Python via .NET"
  description: "Vergleichen Sie nahtlos PDFs, Office-Dokumente, Bilder und eine Vielzahl anderer Formate."

  items:
    # feature loop
    - icon: "compare"
      title: "Intuitiver Dokumentenvergleich"
      content: "Untersuchen und markieren Sie Unterschiede zwischen zwei Dokumenten."

    # feature loop
    - icon: "note-stack"
      title: "Vergleich mehrerer Dokumente"
      content: "Überprüfen Sie mehrere Dokumente gleichzeitig auf Unterschiede."

    # feature loop
    - icon: "stacks"
      title: "Umfangreiche Formatunterstützung"
      content: "Kompatibel mit über 50 häufig verwendeten Dokumentformaten in verschiedenen Kategorien."

    # feature loop
    - icon: "rule"
      title: "Änderungen akzeptieren oder ablehnen"
      content: "Visualisieren Sie Änderungen klar und bieten Sie Optionen für die Annahme oder Ablehnung von Änderungen."

    # feature loop
    - icon: "preview"
      title: "Generieren Sie visuelle Vorschauen"
      content: "Erstellen Sie Vorschauen der Vergleichsergebnisse in Bildformaten."

    # feature loop
    - icon: "two-pager"
      title: "Textbasierter Inhaltsvergleich"
      content: "Führen Sie Zeile-für-Zeile-, Absatz-, Wort- oder Zeichenvergleiche durch, um Änderungen hervorzuheben."

    # feature loop
    - icon: "format_color_text"
      title: "Erkennung von Formatierungsänderungen"
      content: "Identifizieren Sie Änderungen im Dokumentstil und in der Formatierung."

    # feature loop
    - icon: "folder-managed"
      title: "Anpassbare Metadatenverarbeitung"
      content: "Behalten Sie Metadaten aus den Quell- oder Zieldateien bei oder ermöglichen Sie Benutzern, neue Metadaten zu definieren."

    # feature loop
    - icon: "lock"
      title: "Behandeln Sie passwortgeschützte Dateien"
      content: "Arbeiten Sie mit verschlüsselten Dokumenten oder erstellen Sie sichere Dokumente, die mit einem Passwort geschützt sind."

    # feature loop
    - icon: "select"
      title: "Fokussierte Seitenvergleiche"
      content: "Wählen Sie bestimmte Abschnitte oder einzelne Seiten eines Dokuments aus und vergleichen Sie sie."

    # feature loop
    - icon: "speaker-notes"
      title: "Kommentarsichtbarkeit verwalten"
      content: "Entscheiden Sie, ob Kommentare bei der Prüfung des Quelldokuments angezeigt oder verborgen werden sollen."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Codebeispiele"
  description: "Entdecken Sie gängige Szenarien für die Nutzung von GroupDocs.Comparison for Python via .NET-Funktionen."
  items:
    # code sample loop
    - title: "Vergleichen von Dokumenten mit Passwortschutz"
      content: |
        Um Dokumente zu vergleichen, die [mit einem Passwort gesichert](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/) sind, müssen Sie beim Laden der Dokumente das Passwort angeben:
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