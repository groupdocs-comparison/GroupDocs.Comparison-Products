
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: de
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
head_title: "Java Dokumentvergleichsbibliothek| Diff-Checker"
head_description: "Native Java Software zum Vergleich von Dokumentstil und Inhalt. Vergleichen Sie Dokumente verschiedener Formate, um Unterschiede zu erkennen."

############################# Header ############################
title: "Vergleiche und überprüfe Dateiunterschiede mit der Java API"
description: "Entwickeln Sie Java Anwendungen mit einer hochgradig konfigurierbaren Dokumentvergleichsbibliothek, um ähnliche Dokumentformate, einschließlich Dateien, deren Inhalt und Textstil, zu vergleichen."
words:
  for: "zum"

actions:
  main: "Kostenloser Maven-Download"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/"
  alt: "Lizenzierung"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/java/"
  title: "Bereit loszulegen?"
  description: "Testen Sie GroupDocs.Comparison Funktionen kostenlos oder fordern Sie eine Lizenz an"

release:
  title: "Version {0} veröffentlicht"
  notes: "Schau dir an, was es Neues gibt"
  downloads: "herunterladbare"

code:
  title: "Vergleiche DOCX Dateien in Java"
  more: "Mehr Beispiele"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
  install: |
    <dependency>
      <groupId>com.groupdocs</groupId>
      <artifactId>groupdocs-comparison</artifactId>
      <version>{0}</version>
    </dependency>
  content: |
    ```java {style=abap}  
    // Geben Sie das Quelldokument an
    try (Comparer comparer = new Comparer("source.docx"))
    {    
      // Fügen Sie ein oder mehrere Zieldokumente hinzu
      comparer.add("target.docx");

      // Vergleichsoptionen angeben
      CompareOptions options = new CompareOptions();
      options.setShowRevisions(false);

      // Vergleichen und Ergebnis speichern
      final comparer.compare("result.docx", options);
    }    
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison auf einen Blick"
  description: "API zum Vergleich von Unterschieden zwischen Dokumenten in Java Anwendungen"
  features:
    # feature loop
    - title: "Dateivergleich in Java"
      content: "Erkennt Änderungen zwischen Quell- und Zieldateien auf Absatz-, Wort- und Zeichenebene. Identifizieren Sie Stil- und Formatierungsänderungen wie Fett, Kursiv, Unterstreichungen, Durchstriche, Schrifttypen und mehr."

    # feature loop
    - title: "Große Anzahl unterstützter Formate"
      content: "Mit der GroupDocs.Comparison API können Sie ganz einfach Dokumente mehrerer unterstützter Formate vergleichen. Dazu gehören PDF, HTML, E-Mail, Microsoft Office Word Dokumente, Excel Tabellen, PowerPoint Präsentationen, OneNote, Visio Diagramme, Texte, JPEG, PNG, GIF und BMP Bilder sowie viele andere Formate."

    # feature loop
    - title: "Änderungen einfach anwenden oder ablehnen"
      content: "Jeder Unterschied zwischen den verglichenen Dokumenten kann angewendet oder abgelehnt und dann in das Ausgabedokument exportiert werden."

    # feature loop
    - title: "Zusammenfassender Vergleichsbericht"
      content: "Generieren Sie einen zusammenfassenden Bericht, der alle Änderungen in den verglichenen Dokumenten auflistet."

############################# Platforms ############################
platforms:
  enable: true
  title: "Plattformunabhängigkeit"
  description: "GroupDocs.Comparison for Java unterstützt die folgenden Betriebssysteme, Frameworks und Paketmanager"
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
  title: "Unterstützte Dateiformate"
  description: |
    GroupDocs.Comparison for Java unterstützt Operationen mit den folgenden [Dateiformaten](https://docs.groupdocs.com/comparison/java/supported-document-formats/).
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
  title: "GroupDocs.Comparison Funktionen"
  description: "Vergleichen Sie einfach PDF und Office-Dokumente, Bilder und andere Formate"

  items:
    # feature loop
    - icon: "compare"
      title: "Einfach zu verwendender Dokumentenvergleich"
      content: "Analysieren und lokalisieren Sie mühelos Unterschiede zwischen zwei Dokumenten."

    # feature loop
    - icon: "note-stack"
      title: "Vergleichen Sie mehrere Dokumente"
      content: "Untersuchen und markieren Sie gleichzeitig Abweichungen in mehreren Dokumenten."

    # feature loop
    - icon: "stacks"
      title: "Unterstützte Formate"
      content: "Kompatibilität mit über 50 weit verbreiteten Dokumentformaten aus verschiedenen Kategorien."

    # feature loop
    - icon: "rule"
      title: "Änderungen akzeptieren oder ablehnen"
      content: "Klare Visualisierung der identifizierten Änderungen mit Optionen zum Akzeptieren oder Ablehnen von Änderungen."

    # feature loop
    - icon: "preview"
      title: "Vorschauen generieren"
      content: "Möglichkeit, Vergleichsergebnisse als Bildvorschau zu speichern."

    # feature loop
    - icon: "two-pager"
      title: "Vergleich der Inhalte"
      content: "Gründlicher Vergleich von Textinhalten auf verschiedenen Ebenen — einschließlich zeilenweiser, Absatz-, Wort- und Zeichenanalyse, wobei der Schwerpunkt auf Änderungen liegt."

    # feature loop
    - icon: "format_color_text"
      title: "Vergleich der Stile"
      content: "Fähigkeit, Änderungen an Formatierungs- und Stilelementen zu erkennen und hervorzuheben."

    # feature loop
    - icon: "folder-managed"
      title: "Metadaten setzen"
      content: "Option, Metadaten aus Quell- oder Zieldateien beizubehalten oder benutzerdefinierte Metadateneinstellungen zuzulassen."

    # feature loop
    - icon: "lock"
      title: "Passwortschutz"
      content: "Erleichtert die Analyse kennwortgeschützter Dokumente und ermöglicht den Passwortschutz für die resultierenden Dokumente."

    # feature loop
    - icon: "select"
      title: "Bestimmte Seiten vergleichen"
      content: "Laden und vergleichen Sie nach Bedarf bestimmte Abschnitte oder Seiten eines Dokuments."

    # feature loop
    - icon: "speaker-notes"
      title: "Kommentare anzeigen"
      content: "Flexibilität beim Anzeigen oder Verbergen von Kommentaren beim Laden des Quelldokuments."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Codebeispiele"
  description: "Einige Anwendungsfälle typischer GroupDocs.Comparison for Java Operationen"
  items:
    # code sample loop
    - title: "Vergleich passwortgeschützter Dokumente."
      content: |
        Um Dokumente zu vergleichen, die [mit einem Passwort geschützt sind](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/), müssen Sie es angeben und dann die Dokumente laden:
        {{< landing/code title="So vergleichen Sie passwortgeschützte Dokumente.">}}
        ```java {style=abap}
        // Laden Sie das Quelldokument und geben Sie sein Passwort an
        try (Comparer comparer = new Comparer("source.docx", new LoadOptions("1234")))
        {
            // Laden Sie das Zieldokument und geben Sie sein Passwort an
            comparer.add("target.docx", new LoadOptions("5678"));
        
            // Vergleichsergebnis in einer angegebenen Datei speichern
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Vergleich mehrerer PDF Dokumente."
      content: |
        GroupDocs.Comparison ermöglicht es Ihnen, [mehr als zwei Dokumente zu vergleichen](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/). Die Operation ist fast dieselbe wie beim Vergleich zweier Dateien. Sie müssen der Klasse `comparer` nur weitere Zieldateien hinzufügen.
        {{< landing/code title="So vergleichen Sie drei oder mehr Dokumente.">}}
        ```java {style=abap}   
        // Laden Sie das Quelldokument
        try (Comparer comparer = new Comparer("source.docx") 
        {
            // Geben Sie die zweite Datei für den Vergleich an
            comparer.add("target2.docx");

            // Geben Sie die dritte Datei für den Vergleich an
            comparer.add("target3.docx");

            // Vergleichsergebnis in einer angegebenen Datei speichern
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---

