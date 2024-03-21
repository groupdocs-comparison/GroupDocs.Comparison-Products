
---
############################# Static ############################
layout: "landing"
date: 2024-03-21T15:26:29
draft: false

lang: de
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

############################# Head ############################
head_title: "Node.js API für den Dokumentenvergleich | Diff-Checker"
head_description: "Die Node.js Document Comparison API bietet effiziente Tools für den Vergleich von Dokumenten. Lässt sich nahtlos in Node.js integrieren und ermöglicht so die Nachverfolgung von Änderungen in Echtzeit"

############################# Header ############################
title: "Dokumente mit Node.js vergleichen: Alle Unterschiede hervorheben"
description: "Verwenden Sie die GroupDocs.Comparison API, um native Java Script-Anwendungen mit hochgradig konfigurierbaren Vergleichsfunktionen zu entwickeln. Vergleichen Sie Dateien, ihren Inhalt und ihren Textstil zwischen ähnlichen Dokumentformaten."
words:
  for: "zum"

actions:
  main: "Kostenloser NPM-Download"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.comparison"
  alt: "Lizenzierung"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/java/"
  title: "Bereit loszulegen?"
  description: "Testen Sie GroupDocs.Comparison Funktionen kostenlos oder fordern Sie eine Lizenz an"

release:
  title: "Version {0} veröffentlicht"
  notes: "Schau dir an, was es Neues gibt"
  downloads: "herunterladbare"

code:
  title: "Vergleiche BMP Bilder in Java Script"
  more: "Mehr Beispiele"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.comparison"
  content: |
    ```javascript {style=abap}

    // Geben Sie das Quelldokument an
    let comparer = new Comparer("source.bmp");

    // Fügen Sie ein oder mehrere Zieldokumente hinzu
    comparer.add("target.bmp");

    // Vergleichsoptionen angeben
    comparer.compare("result.bmp"); 
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison auf einen Blick"
  description: "API zum Vergleich verschiedener Dokumenttypen wie PDF, Microsoft Office, HTML, E-Mails oder Bilder in Node.js Anwendungen"
  features:
    # feature loop
    - title: "Detaillierte Ausgabeberichte"
      content: "GroupDocs.Comparison identifiziert Änderungen im Dokumentinhalt (Zeichen, Wörter, Absätze, Tabellen, Diagramme) sowie Änderungen im Dokumentstil. Es bietet Kunden einen Ergebnisbericht, der umfangreiche Informationen über Unterschiede, deren Anzahl und Typ enthält."

    # feature loop
    - title: "Die gängigsten Datei- und Dokumentformate werden unterstützt"
      content: "Mit der GroupDocs.Comparison API können Sie Dokumente aller unterstützten Formate wie PDF, HTML, E-Mail, Microsoft Office Word Dokumente, Excel Tabellen, PowerPoint Präsentationen, OneNote, Visio Diagramme, Texte, JPEG, PNG, GIF und BMP Bilder sowie viele andere Formate effizient vergleichen."

    # feature loop
    - title: "Dokumentation und Beispiele"
      content: "Es gibt bereits eine Menge Dokumentation zur Verwendung der Comparison Library auf verschiedenen Plattformen mit Codebeispielen, sodass Sie nicht lange darüber nachdenken müssen, wie Sie mit der GroupDocs.Comparison API in Ihrer Node.js -Anwendung arbeiten können."

    # feature loop
    - title: "Wählen Sie Änderungen aus und führen Sie sie zu einer Datei zusammen"
      content: "Wenn Sie verschiedene Versionen eines Dokuments haben, ist es möglich, nur die gewünschten Änderungen auszuwählen und ein neues Dokument mithilfe der GroupDocs.Comparison -Bibliothek zu kompilieren."

############################# Platforms ############################
platforms:
  enable: true
  title: "Plattformunabhängigkeit"
  description: "GroupDocs.Comparison for Node.js via Java unterstützt die folgenden Betriebssysteme, Frameworks und Paketmanager"
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
    GroupDocs.Comparison for Node.js via Java unterstützt Operationen mit den folgenden [Dateiformaten](https://docs.groupdocs.com/comparison/nodejs-java/supported-document-formats/).
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
  title: "GroupDocs.Comparison for Node.js via Java Funktionen"
  description: "Vergleichen Sie einfach PDF und Office-Dokumente, Bilder und andere Formate"

  items:
    # feature loop
    - icon: "compare"
      title: "Einfach zu verwendender Dokumentenvergleich"
      content: "Analysieren und identifizieren Sie Unterschiede innerhalb von zwei Dokumenten."

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
      content: "Klare visuelle Darstellung der identifizierten Änderungen mit der Option, Änderungen zu akzeptieren oder abzulehnen."

    # feature loop
    - icon: "preview"
      title: "Vorschauen generieren"
      content: "Speichern Sie die Ergebnisse des Vergleichs als Bilder."

    # feature loop
    - icon: "two-pager"
      title: "Vergleich der Inhalte"
      content: "Vergleichen Sie Textinhalte zeilenweise, nach Absätzen, nach Wörtern, nach Zeichen. Markieren Sie die Änderungen."

    # feature loop
    - icon: "format_color_text"
      title: "Vergleich der Stile"
      content: "Erkennen Sie Änderungen an Formatierungen und Stilen."

    # feature loop
    - icon: "folder-managed"
      title: "Metadaten setzen"
      content: "Behalten Sie Metadaten aus den Quell- oder Zieldateien bei oder lassen Sie sie von Benutzern angeben."

    # feature loop
    - icon: "lock"
      title: "Passwortschutz"
      content: "Analysieren Sie die verschlüsselten Dokumente oder sichern Sie das resultierende Dokument mit einem Passwort."

    # feature loop
    - icon: "select"
      title: "Bestimmte Seiten vergleichen"
      content: "Laden Sie nur die bestimmten Abschnitte oder Seiten des Dokuments."

    # feature loop
    - icon: "speaker-notes"
      title: "Kommentare anzeigen"
      content: "Beim Laden des Quelldokuments können Sie wählen, ob Kommentare ein- oder ausgeblendet werden sollen."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Codebeispiele"
  description: "Einige Anwendungsfälle typischer GroupDocs.Comparison for Node.js via Java Operationen"
  items:
    # code sample loop
    - title: "Vergleich passwortgeschützter Dokumente."
      content: |
        Um Dokumente zu vergleichen, die [mit einem Passwort geschützt] sind (https://docs.groupdocs.com/comparison/nodejs-java/load-password-protected-documents/), müssen Sie es angeben und dann die Dokumente laden:
        {{< landing/code title="So vergleichen Sie passwortgeschützte Dokumente.">}}
        ```javascript {style=abap}

        import { Comparer, LoadOptions } from '@groupdocs/groupdocs.comparison'

        // Laden Sie das Quelldokument und geben Sie sein Passwort an
        const comparer = new Comparer("source.docx", new LoadOptions("1234"));

        // Laden Sie das Zieldokument und geben Sie sein Passwort an
        comparer.add("target.docx", new LoadOptions("5678"));

        // Vergleichsergebnis in einer angegebenen Datei speichern
        comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Vergleich mehrerer PDF Dokumente."
      content: |
        GroupDocs.Comparison ermöglicht es Ihnen, [mehr als zwei Dokumente zu vergleichen](https://docs.groupdocs.com/comparison/nodejs-java/compare-multiple-documents/). Die Operation ist fast dieselbe wie beim Vergleich zweier Dateien. Sie müssen der Klasse `comparer` nur weitere Zieldateien hinzufügen.
        {{< landing/code title="So vergleichen Sie drei oder mehr Dokumente.">}}
        ```javascript {style=abap}
        import { Comparer } from '@groupdocs/groupdocs.comparison'

        // Laden Sie das Quelldokument
        const comparer = new Comparer(source.pdf");

        // Geben Sie die zweite Datei für den Vergleich an
        comparer.add("target2.pdf");

        // Geben Sie die dritte Datei für den Vergleich an
        comparer.add("target3.pdf");

        // Vergleichsergebnis in einer angegebenen Datei speichern
        comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---