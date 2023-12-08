---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "C# .NET-Dokumentvergleichs-API | Vergleichen und Zusammenführen von PDF, Word, Excel, Web und Text"
head_description: "C# .NET-Dokumentvergleichs-API. Vergleichen und führen Sie die Dateiformate PDF Word DOC DOCX, Excel-Tabelle, PPT, PPTX, HTML, EMLX MSG, VSDX, DXF DWG und Bild zusammen."

############################# Header ############################
title: ".NET-API zum Vergleichen von Dateien"
description: "Entwickeln Sie Anwendungen mithilfe der .NET-Dokumentvergleichs-API, um Dateien auf Unterschiede in Inhalt und Stil zu überprüfen und zu vergleichen."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download kostenlose Testversion"
    link: "https://downloads.groupdocs.com/comparison/net"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Comparison for .NET"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
        product: "GroupDocs.Comparison"
        platform: ".NET"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "Überblick"

            # button loop
            - link: "#features"
              text: "Merkmale"

            # button loop
            - link: "#support"
              text: "Unterstützung"

            # button loop
            - link: "https://products.groupdocs.app/comparison"
              text: "Live-Demo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "Preisgestaltung"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    example_image: "/comparison/comparison-example.webp"
    content: |
      
    more_overview:
      # more_overview_loop
      - title: "Was ist GroupDocs.Comparison for .NET?"
        content: "Die GroupDocs.Comparison for .NET API ist eine schnelle und zuverlässige Lösung, die beim Erstellen von Anwendungen zum Suchen und Hervorheben von Unterschieden zwischen Dokumenten gleichen oder unterschiedlichen Formats in C#, ASP.NET oder anderen Technologien im Zusammenhang mit der .NET-Softwareplattform verwendet werden kann."

      # more_overview_loop
      - title: "Unterstützte Formate"
        content: "Die GroupDocs.Comparison-Bibliothek unterstützt die Erkennung von Unterschieden im Inhalt und Textstil zwischen gängigen Bild- und Dokumentformaten wie PDF, HTML, E-Mail-Outlook, Microsoft Office Word-Dokumenten, Excel-Tabellen, PowerPoint-Präsentationen, OneNote, Visio-Diagrammen, Texten und PNG , GIF- und BMP-Bilder sowie Hunderte anderer Formate."
        
      # more_overview_loop
      - title: "Vergleichsmöglichkeiten"
        content: "Ein Vergleich kann durchgeführt werden, um Änderungen im Inhalt von Wörtern, Absätzen, Tabellen oder Diagrammen und deren Stilen zu erkennen. Sie erhalten ein Vergleichsdokument, das eine Zusammenfassung der Unterschiede sowie deren Anzahl und Artzugehörigkeit auflistet. GroupDocs.Comparison for .NET kann problemlos grundlegende Informationen über das Quelldokument extrahieren, einfache, passwortgeschützte und verschlüsselte Dokumente verschiedener Formate über eine Datei oder einen Datenstrom vergleichen und speichern."
        
      # more_overview_loop
      - title: "Dokumentation und Beispiele"
        content: "Es gibt bereits zahlreiche Dokumentationen zur Verwendung der Vergleichsbibliothek auf verschiedenen Plattformen mit Codebeispielen, sodass Sie nicht lange darüber nachdenken müssen, wie Sie mit der GroupDocs.Comparison für die .NET-API in Ihrer Anwendung arbeiten."
        
      # more_overview_loop
      - title: "Kompatibilität"
        content: "Mit GroupDocs.Comparison for .NET können Sie Anwendungen in jeder Entwicklungsumgebung erstellen, die auf der .NET-Plattform basiert. Es ist mit allen .NET-basierten Sprachen kompatibel und unterstützt gängige Betriebssysteme (Windows, Linux, MacOS), auf denen Sie Mono- oder .NET-Frameworks (einschließlich .NET Core) installieren können."
    examples:
      enable: true
      
    more_feature:
      # more_feature_loop
      - title: "Vergleichen Sie Dokumente ganz einfach mit der .NET-API"
        content: |
          Die GroupDocs.Comparison for .NET API bietet Ihnen eine einfache und effiziente Möglichkeit, Ihre Dateien zu vergleichen. Das folgende Beispiel zeigt, wie man zwei DOCX-Dokumente mit C# vergleicht:  

          ```cs
          // Zu vergleichende Quell- und Zieldateien
          string source = @"source.docx";
          string target = @"target.docx";
          Comparer comparer = new Comparer();
          // Vergleichen Sie zwei Dokumente
          ICompareResult result = comparer.Compare(source, target, new ComparisonSettings());
          ```
      # more_feature_loop
      - title: "Wählen Sie Detailebene für den Vergleich"
        content: "Mit GroupDocs.Comparison for .NET können Sie festlegen, in welchem ​​Umfang die Dokumente verglichen werden sollen. Sie können zwischen niedrig (Text Wort für Wort mit Genauigkeit für Bildraster = 50 vergleichen), mittel (Text Zeichen für Zeichen mit Genauigkeit für Bildraster = 100 vergleichen) und hoch (Text Zeichen für Zeichen mit Genauigkeit für Bildraster = vergleicht) wählen 150)."

      # more_feature_loop
      - title: "Unterstützung für Textstilvergleich"
        content: |
          GroupDocs.Comparison for .NET bietet eine Funktion zum Vergleichen des Textstils.  

          Während Wörter und Zeichen von Dokumenten verglichen werden, können Schriftartname, Schriftgröße, Schriftfarbe, Schriftstil (Fett, Kursiv, Unterstrichen, Kapitälchen, Hyperlink) und Unterstreichungsfarbe (falls zutreffend) verglichen werden, um Unterschiede festzustellen.  

          Beim Vergleichen von Absätzen können Sie Stile wie Absatzausrichtung, Einzug (linker Einzug, rechter Einzug), Absatzabstand (Leerzeichen danach, Leerzeichen davor), Einzug der ersten Zeile und Zeilenabstand vergleichen.  

          GroupDocs.Comparison for .NET unterstützt gegebenenfalls auch den Vergleich anderer Abschnitte einer Seite, z. B. Fußzeilenabstand, Seitenhöhe und -ausrichtung, Ränder (links, rechts, oben und unten), Rahmenlinienbreite und Rahmenfarbe.  
      
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Nachfolgend finden Sie eine Übersicht über GroupDocs.Comparison for .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Überblick"
          content: |
            * Dokumentenvergleich
            * Vergleich von HTML-Dateien
            * PDF-Vergleich
            * Diagrammvergleich
            * Vergleichen Sie den Dateiinhalt
            * Vergleichen Sie Textstile
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison for .NET unterstützt alle gängigen [Dokumentdateiformate](https://docs.groupdocs.com/comparison/net/supported-document-formats/), einschließlich: Microsoft Office, PDF, Bilder und viele andere .
        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** [DOC](https://products.groupdocs.com/comparison/net/doc/), [DOCX](https://products.groupdocs.com/comparison/net/docx/), [DOCM](https://products.groupdocs.com/comparison/net/docm/), [DOT](https://products.groupdocs.com/comparison/net/dot/), [DOTX](https://products.groupdocs.com/comparison/net/dotx/), [DOTM](https://products.groupdocs.com/comparison/net/dotm/), [RTF](https://products.groupdocs.com/comparison/net/rtf/), [TXT](https://products.groupdocs.com/comparison/net/txt/)
                * **Excel:** [XLS](https://products.groupdocs.com/comparison/net/xls/), [XLSX](https://products.groupdocs.com/comparison/net/xlsx/), [XLSM](https://products.groupdocs.com/comparison/net/xlsm/), [XLSB](https://products.groupdocs.com/comparison/net/xlsb/), [XLTM](https://products.groupdocs.com/comparison/net/xltm/), [XLT](https://products.groupdocs.com/comparison/net/xlt/), [XLTM](https://products.groupdocs.com/comparison/net/xltm/), [XLTX](https://products.groupdocs.com/comparison/net/xltx/), [XLAM](https://products.groupdocs.com/comparison/net/xlam/), [SXC](https://products.groupdocs.com/comparison/net/sxc/), [SpreadsheetML](https://products.groupdocs.com/comparison/net/xml/)
                * **PowerPoint:** [PPT](https://products.groupdocs.com/comparison/net/ppt/), [PPTX](https://products.groupdocs.com/comparison/net/pptx/), [PPS](https://products.groupdocs.com/comparison/net/pps/), [PPSX](https://products.groupdocs.com/comparison/net/ppsx/), [PPSM](https://products.groupdocs.com/comparison/net/ppsm/), [POT](https://products.groupdocs.com/comparison/net/pot/), [POTM](https://products.groupdocs.com/comparison/net/potm/), [POTX](https://products.groupdocs.com/comparison/net/potx/), [PPTM](https://products.groupdocs.com/comparison/net/pptm/)
                * **Visio:** [VSD](https://products.groupdocs.com/comparison/net/vsd/), [VDX](https://products.groupdocs.com/comparison/net/vdx/), [VSS](https://products.groupdocs.com/comparison/net/vss/), [VSSX](https://products.groupdocs.com/comparison/net/vssx/), [VSX](https://products.groupdocs.com/comparison/net/vsx/), [VST](https://products.groupdocs.com/comparison/net/vst/), [VSTX](https://products.groupdocs.com/comparison/net/vstx/), [VTX](https://products.groupdocs.com/comparison/net/vtx/), [VSDX](https://products.groupdocs.com/comparison/net/vsdx/), [VDW](https://products.groupdocs.com/comparison/net/vdw/), [VSTM](https://products.groupdocs.com/comparison/net/vstm/), [VSSM](https://products.groupdocs.com/comparison/net/vssm/), [VSDM](https://products.groupdocs.com/comparison/net/vsdm/)
                * **Outlook:** [MSG](https://products.groupdocs.com/comparison/net/msg/), [EML](https://products.groupdocs.com/comparison/net/eml/), [EMLX](https://products.groupdocs.com/comparison/net/emlx/), [PST](https://products.groupdocs.com/comparison/net/pst/), [OST](https://products.groupdocs.com/comparison/net/ost/)
                * **OneNote:** [ONE](https://products.groupdocs.com/comparison/net/one/)

        right:
          enable: true
          table:
            # table loop
            - title: "Andere Formate"
              content: |
                * **Programmiersprachen**: [CS](https://products.groupdocs.com/comparison/net/cs/), [Java](https://products.groupdocs.com/comparison/net/java/), [CPP](https://products.groupdocs.com/comparison/net/cpp/), [JS](https://products.groupdocs.com/comparison/net/js/), [PY](https://products.groupdocs.com/comparison/net/py/), [RB](https://products.groupdocs.com/comparison/net/rb/), [PL](https://products.groupdocs.com/comparison/net/pl/), [ASM](https://products.groupdocs.com/comparison/net/asm/), [GROOVY](https://products.groupdocs.com/comparison/net/groovy/), [JSON](https://products.groupdocs.com/comparison/net/json/), [PHP](https://products.groupdocs.com/comparison/net/php/), [SQL](https://products.groupdocs.com/comparison/net/sql/), [LOG](https://products.groupdocs.com/comparison/net/log/), [DIFF](https://products.groupdocs.com/comparison/net/diff/), [LESS](https://products.groupdocs.com/comparison/net/less/), [SCALA](https://products.groupdocs.com/comparison/net/scala/)
                * **OpenDocument**: [ODT](https://products.groupdocs.com/comparison/net/odt/), [OTT](https://products.groupdocs.com/comparison/net/ott/), [ODS](https://products.groupdocs.com/comparison/net/ods/), [ODP](https://products.groupdocs.com/comparison/net/odp/), [OTP](https://products.groupdocs.com/comparison/net/otp/)
                * **Portable**: [PDF](https://products.groupdocs.com/comparison/net/pdf/), [MOBI](https://products.groupdocs.com/comparison/net/mobi/)
                * **AutoCAD**: [DXF](https://products.groupdocs.com/comparison/net/dxf/), [DWG](https://products.groupdocs.com/comparison/net/dwg/)
                * **Email**: [EML](https://products.groupdocs.com/comparison/net/eml/), [EMLX](https://products.groupdocs.com/comparison/net/emlx/), [MSG](https://products.groupdocs.com/comparison/net/msg/)
                * **Images**: [JPEG](https://products.groupdocs.com/comparison/net/jpeg/), [BMP](https://products.groupdocs.com/comparison/net/bmp/), [PNG](https://products.groupdocs.com/comparison/net/png/), [GIF](https://products.groupdocs.com/comparison/net/gif/), [DCM](https://products.groupdocs.com/comparison/net/dcm/), [DICOM](https://products.groupdocs.com/comparison/net/dicom/), [DjVu](https://products.groupdocs.com/comparison/net/djvu/)
                * **Web**: [HTM](https://products.groupdocs.com/comparison/net/htm/), [HTML](https://products.groupdocs.com/comparison/net/html/), [MHTML](https://products.groupdocs.com/comparison/net/mhtml/)
                * **Text**: [TXT](https://products.groupdocs.com/comparison/net/txt/)

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Comparison for .NET unterstützt folgende Betriebssysteme, Frameworks und Paketmanager:
      
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Betriebssysteme"
              content: |
                * Windows Desktop
                * Windows Server
                * Windows Azure
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "Unterstützte Frameworks"
              content: |
                * .NET Framework 2.0 oder höher
                * Mono Framework 1.2 oder höher
                * .NET Standard 2.0
                * .NET Core 2.0

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Paket-Manager"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Entwicklungsumgebungen"
              content: |
                * Microsoft Visual Studio
                * Xamarin.Android
                * Xamarin.IOS
                * Xamarin.Mac
                * MonoDevelop

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Comparison for .NET Funktionen"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "[Identifizieren Sie Unterschiede im Inhalt und in den Schriftarten](https://docs.groupdocs.com/comparison/net/compare-documents/)"

      # feature loop
      - icon: "fas fa-eye"
        content: "[Speichern Sie einen zusammengefassten Bericht aller nach dem Dateivergleich gefundenen Unterschiede](https://docs.groupdocs.com/comparison/net/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-bolt"
        content: "[Übernehmen oder verwerfen Sie Änderungen nach der Analyse der Unterschiede und exportieren Sie die resultierende Datei](https://docs.groupdocs.com/comparison/net/accept-or-reject-detected-changes/)"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "[Unterstützung der Microsoft Word-Funktion „Änderungen verfolgen“ beim Vergleichen von Word-Dateien](https://docs.groupdocs.com/comparison/net/show-revisions/)"

      # feature loop
      - icon: "fas fa-code"
        content: "[Erkennen Sie auf einzigartige Weise Änderungen, die sich aus jedem verglichenen Dokument ergeben](https://docs.groupdocs.com/comparison/net/get-list-of-changes/)"

      # feature loop
      - icon: "fas fa-cloud"
        content: "[Lesen und senden Sie Dokumente über Streams](https://docs.groupdocs.com/comparison/net/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "[Gemessene Lizenzierung – Abrechnung nach API-Nutzung](https://docs.groupdocs.com/comparison/net/licensing-and-evaluation-limitations/)"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "[Vergleichen Sie mehrere Quelldokumente mit einem einzelnen Zieldokument](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/)"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "[Vergleichen Sie bestimmte Seiten von Word-Dateien miteinander – Akzeptieren oder lehnen Sie alle Änderungen in einem einzelnen Word-Dokument ab](https://docs.groupdocs.com/comparison/net/accept-or-reject-detected-changes/)"

      # feature loop
      - icon: "fas fa-border-all"
        content: "[Führen Sie bis zu 3 Word-Dokumente zusammen und vergleichen Sie die in Word-Dateien verwendeten Formeln](https://docs.groupdocs.com/comparison/net/how-to-merge-source-code-files/)"

      # feature loop
      - icon: "fas fa-wrench"
        content: "[Informationen zu Dokumenten aus filePath abrufen](https://docs.groupdocs.com/comparison/net/get-file-info/)"

      # feature loop
      - icon: "fas fa-columns"
        content: "[HTML-Vergleichsergebnis als Bilder speichern](https://docs.groupdocs.com/comparison/net/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-file-word"
        content: "[Option zum Anzeigen oder Ausblenden gelöschter Inhalte](https://docs.groupdocs.com/comparison/net/show-gap-lines/)"

      # feature loop
      - icon: "fas fa-envelope"
        content: "[Option zum Ein- und Ausschalten des Stilvergleichs von Dokumenten](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fas fa-print"
        content: "[Geben Sie Zeichenfolgen an, um eingefügte, gelöschte und Stiländerungselemente im Vergleichsdokument zu markieren](https://docs.groupdocs.com/comparison/net/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "[Geben Sie Worttrennzeichen und Schriftfarbe an, um verglichenen Text zu stilisieren](https://docs.groupdocs.com/comparison/net/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-lock"
        content: "[Berechnen Sie die korrekten Koordinaten von Änderungen in PDF-, Word-, PowerPoint-Folien und Diagrammen](https://docs.groupdocs.com/comparison/net/get-changes-coordinates/)"

      # feature loop
      - icon: "fas fa-file-code"
        content: "[Vergleichen Sie passwortgeschützte Dateien](https://docs.groupdocs.com/comparison/net/how-to-compare-password-protected-files/)"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "[Diagrammtitel in Tabellenkalkulationen vergleichen – Diagramm in den resultierenden Zellendateien erstellen](https://docs.groupdocs.com/comparison/net/how-to-compare-spreadsheet-or-tables/)"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "[Automatische Größenanpassung der automatischen Formen in der resultierenden Datei des Zellendokuments](https://docs.groupdocs.com/comparison/net/how-to-compare-spreadsheet-or-tables/)"

      # feature loop
      - icon: "fas fa-heading"
        content: "[Greifen Sie auf die detaillierte Zusammenfassungsseite zu, um Änderungen zwischen Quell- und Zieldokumentdateien zu erkennen](https://docs.groupdocs.com/comparison/net/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "[Vergleichen Sie die beliebtesten Programmier- und Skriptsprachendateien](https://docs.groupdocs.com/comparison/net/get-supported-document-formats/)"

      # feature loop
      - icon: "fas fa-cube"
        content: "[Vergleichen Sie mehrere (mehr als zwei) PDF-, Word-, Excel-, Diagramm-, E-Mail-, Text- und OneNote-Dokumente](https://docs.groupdocs.com/comparison/net/compare-multiple-documents-with-specific-compare-settings/)"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "[Vergleichen Sie Kopf- und Fußzeile der unterstützten Dateiformate](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "[Vergleichen Sie Lesezeichen, Variablen und benutzerdefinierte Eigenschaften von Word-Dokumentformaten](https://docs.groupdocs.com/comparison/net/compare-bookmarks-in-word/)"

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison bietet APIs zum Anzeigen von Dokumenten für andere gängige Entwicklungsumgebungen"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for Java"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---