
---
############################# Static ############################
layout: "landing"
date: 2024-03-21T15:26:29
draft: false

lang: de
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

############################# Head ############################
head_title: "C# .NET Software zum Vergleich von Dokumenten | diff checker"
head_description: "C# .NET Software zum Vergleich von Dokumentstil und Inhalt. Vergleichen Sie Dokumente mehrerer unterstützter Formate, um Änderungen zwischen Dateien zu erkennen."

############################# Header ############################
title: "Vergleichen Sie Dokumente mühelos in Ihren C# .NET Lösungen"
description: "Erstellen Sie C# Anwendungen mit einer flexiblen Dokumentvergleichs-API, die den Dateivergleich nach Inhalt und Stil in verschiedenen Dokumentformaten ermöglicht."
words:
  for: "zum"

actions:
  main: "Kostenlos NuGet Download"
  main_link: "https://www.nuget.org/packages/GroupDocs.Comparison"
  alt: "Lizenzierung"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/net/"
  title: "Bereit loszulegen?"
  description: "Testen Sie GroupDocs.Comparison Funktionen kostenlos oder fordern Sie eine Lizenz an"

release:
  title: "Version {0} veröffentlicht"
  notes: "Schau dir an, was es Neues gibt"
  downloads: "herunterladbare"

code:
  title: "Vergleiche DOCX Dateien in C#"
  more: "Mehr Beispiele"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET"
  install: "dotnet add package GroupDocs.Comparison"
  content: |
    ```csharp {style=abap}   
    // Geben Sie das Quelldokument an
    using (Comparer comparer = new Comparer("source.docx"))
    {
        // Fügen Sie ein oder mehrere Zieldokumente hinzu
        comparer.Add("target.docx");

        // Vergleichsoptionen angeben
        CompareOptions options = new CompareOptions() 
        {ShowRevisions = false};

        // Führen Sie den Vergleich durch und speichern Sie das resultierende Dokument
        comparer.Compare("result.docx", options);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison auf einen Blick"
  description: "API zum Vergleich von Unterschieden zwischen Dokumenten in .NET Anwendungen"
  features:
    # feature loop
    - title: "Dateivergleich in C#"
      content: "Ermitteln Sie Unterschiede zwischen Quell- und Zieldateien auf Absatz-, Wort- und Zeichenebene. Identifizieren Sie Stil- und Formatierungsänderungen wie Fett, Kursiv, Unterstreichungen, Durchstriche, Schrifttypen usw."

    # feature loop
    - title: "Die gängigsten Datei- und Dokumentformate werden unterstützt"
      content: "Die GroupDocs.Comparison API ermöglicht einen effizienten Dokumentenvergleich in einer Vielzahl von Formaten, darunter PDF, HTML, E-Mails, Microsoft Office Dokumente (Word, Excel, PowerPoint, OneNote, Visio), verschiedene Bildtypen (JPEG, PNG, GIF, BMP), Textdateien und mehr."

    # feature loop
    - title: "Änderungen einfach anwenden oder ablehnen"
      content: "Jeder Unterschied, der in den verglichenen Dokumenten mithilfe der GroupDocs.Comparison API identifiziert wurde, kann selektiv angewendet oder abgelehnt werden, sodass eine Anpassung vor dem Export in das endgültige Ausgabedokument möglich ist."

    # feature loop
    - title: "Zusammenfassender Vergleichsbericht"
      content: "Generieren Sie einen zusammenfassenden Bericht über die Unterschiede, in dem alle in den verglichenen Dokumenten gefundenen Änderungen detailliert beschrieben werden, und speichern Sie ihn als Referenz."

############################# Platforms ############################
platforms:
  enable: true
  title: "Plattformunabhängigkeit"
  description: "GroupDocs.Comparison for .NET unterstützt die folgenden Betriebssysteme, Frameworks und Paketmanager"
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
  title: "Unterstützte Dateiformate"
  description: |
    GroupDocs.Comparison for .NET unterstützt Operationen mit den folgenden [Dateiformaten](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
      content: "Analysieren und identifizieren Sie Unterschiede zwischen zwei Dokumenten."

    # feature loop
    - icon: "note-stack"
      title: "Vergleichen Sie mehrere Dokumente"
      content: "Analysieren und identifizieren Sie gleichzeitig Unterschiede in mehreren Dokumenten."

    # feature loop
    - icon: "stacks"
      title: "Unterstützte Formate"
      content: "Kompatibel mit über 50 weit verbreiteten Dokumentenformaten aus verschiedenen Kategorien, was eine breite Anwendbarkeit gewährleistet."

    # feature loop
    - icon: "rule"
      title: "Änderungen akzeptieren oder ablehnen"
      content: "Klare visuelle Anzeige der erkannten Änderungen, komplett mit Optionen, um diese Änderungen entweder zu akzeptieren oder abzulehnen."

    # feature loop
    - icon: "preview"
      title: "Vorschauen generieren"
      content: "Möglichkeit, Vergleichsergebnisse als Bildvorschau zum einfachen Nachschlagen und Teilen zu speichern."

    # feature loop
    - icon: "two-pager"
      title: "Vergleich der Inhalte"
      content: "Führen Sie gründliche Textvergleiche auf verschiedenen Ebenen durch — einschließlich Zeile für Zeile, Absatz, Wort und Zeichen — mit hervorgehobenen Unterschieden für eine bessere Übersichtlichkeit."

    # feature loop
    - icon: "format_color_text"
      title: "Vergleich von Stil und Formatierung"
      content: "Erkennt und markiert Änderungen an der Formatierung und im Stil von Dokumenten und gewährleistet so eine umfassende Überprüfung."

    # feature loop
    - icon: "folder-managed"
      title: "Flexible Metadateneinstellungen"
      content: "Bewahren Sie Metadaten aus Quell- oder Zieldateien bei oder passen Sie sie an die Benutzereinstellungen an."

    # feature loop
    - icon: "lock"
      title: "Passwortschutz"
      content: "Analysieren Sie kennwortgeschützte Dokumente und sichern Sie das Ausgabedokument mit einer Passwortverschlüsselung für zusätzliche Sicherheit."

    # feature loop
    - icon: "select"
      title: "Selektiver Seitenvergleich"
      content: "Laden und vergleichen Sie bestimmte Abschnitte oder Seiten eines Dokuments für eine gezielte Analyse."

    # feature loop
    - icon: "speaker-notes"
      title: "Kommentare anzeigen"
      content: "Wählen Sie, ob Kommentare beim Laden des Quelldokuments ein- oder ausgeblendet werden sollen, um den Vergleichsprozess besser steuern zu können."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Codebeispiele"
  description: "Einige Anwendungsfälle typischer GroupDocs.Comparison for .NET Operationen"
  items:
    # code sample loop
    - title: "Vergleich passwortgeschützter Dokumente."
      content: |
        Um Dokumente zu vergleichen, die [mit einem Passwort geschützt] sind (https://docs.groupdocs.com/comparison/net/load-password-protected-documents/), müssen Sie es angeben und dann die Dokumente laden:
        {{< landing/code title="So vergleichen Sie passwortgeschützte Dokumente.">}}
        ```csharp {style=abap}
        // Laden Sie das Quelldokument und geben Sie sein Passwort an
        using(Comparer comparer = new Comparer("source.docx", new LoadOptions() {Password = "1234"}))  
        {
            // Laden Sie das Zieldokument und geben Sie sein Passwort an
            comparer.Add("target.docx", new LoadOptions() {Password = "5678"});

            // Vergleichsergebnis in einer angegebenen Datei speichern
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Vergleich mehrerer PDF Dokumente."
      content: |
        GroupDocs.Comparison ermöglicht es Ihnen, [mehr als zwei Dokumente zu vergleichen](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/). Die Operation ist fast dieselbe wie beim Vergleich zweier Dateien. Sie müssen der Klasse `comparer` nur weitere Zieldateien hinzufügen.
        {{< landing/code title="So vergleichen Sie drei oder mehr Dokumente.">}}
        ```csharp {style=abap}   
        // Laden Sie das Quelldokument
        using(Comparer comparer = new Comparer("source.docx") 
        {
            // Geben Sie die zweite Datei für den Vergleich an
            comparer.Add("target2.docx");
            
            // Geben Sie die dritte Datei für den Vergleich an
            comparer.Add("target3.docx");
            
            // Vergleichsergebnis in einer angegebenen Datei speichern
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---
