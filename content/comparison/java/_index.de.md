---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "Java-Dokumentvergleichs-API | Vergleichen Sie Text und Stil von PDF, Word, Excel und HTML"
head_description: "Java-Dokumentvergleichs-API zum Vergleichen und Zusammenführen von Word Excel PPTX OpenOffice, Web, PDF, AutoCAD und anderen Dateiformaten. Vergleichen Sie Dokumente und verfolgen Sie Änderungen."

############################# Header ############################
title: "Java-API zum Vergleichen von Dateien"
description: "Erstellen Sie Java-Anwendungen, um Dateiinhalte effektiv auf Unterschiede in allen Standarddokument- und Bilddateiformaten zu vergleichen."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download kostenlose Testversion"
    link: "https://downloads.groupdocs.com/comparison/java"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Comparison for Java"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
        product: "GroupDocs.Comparison"
        platform: "Java"

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
            - link: "https://purchase.groupdocs.com/pricing/comparison/java"
              text: "Preisgestaltung"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    example_image: "/comparison/comparison-example.png"
    content: |
      
    more_overview:
      # more_overview_loop
      - title: "Was ist GroupDocs.Comparison for Java?"
        content: "GroupDocs.Comparison for Java ist die flexibelste und benutzerfreundlichste API, die Sie bei der Entwicklung von Dokumentvergleichsanwendungen in der Java-Umgebung unterstützt. Mit der Differenzprüfung und der Dokumentzusammenführungs-API können Sie Änderungen und Unterschiede im Inhalt sowie im Textstil zwischen ähnlichen Dokumentformaten erkennen."

      # more_overview_loop
      - title: "Unterstützte Formate"
        content: "Die GroupDocs.Comparison-Bibliothek unterstützt die Erkennung von Unterschieden im Inhalt und Textstil zwischen gängigen Bild- und Dokumentformaten wie PDF, HTML, E-Mail-Outlook, Microsoft Office Word-Dokumenten, Excel-Tabellen, PowerPoint-Präsentationen, OneNote, Visio-Diagrammen, Texten und PNG , GIF- und BMP-Bilder sowie Hunderte anderer Formate."
        
      # more_overview_loop
      - title: "Vergleichsmöglichkeiten"
        content: "Ein Vergleich kann durchgeführt werden, um Änderungen im Inhalt von Wörtern, Absätzen, Tabellen oder Diagrammen und deren Stilen zu erkennen. Sie erhalten ein Vergleichsdokument, das eine Zusammenfassung der Unterschiede sowie deren Anzahl und Artzugehörigkeit auflistet. GroupDocs.Comparison for Java kann problemlos grundlegende Informationen über das Quelldokument extrahieren, einfache, passwortgeschützte und verschlüsselte Dokumente verschiedener Formate über eine Datei oder einen Datenstrom vergleichen und speichern."
        
      # more_overview_loop
      - title: "Dokumentation und Beispiele"
        content: "Es gibt bereits zahlreiche Dokumentationen zur Verwendung der Vergleichsbibliothek auf verschiedenen Plattformen mit Codebeispielen, sodass Sie nicht lange darüber nachdenken müssen, wie Sie mit der GroupDocs.Comparison für die Java-API in Ihrer Anwendung arbeiten."
        
      # more_overview_loop
      - title: "Kompatibilität"
        content: "Für GroupDocs.Comparison for Java muss keine externe Software im System installiert werden. Es ist mit allen Java-Versionen kompatibel und unterstützt gängige Betriebssysteme (Windows, Linux, MacOS), auf denen die Java-Laufzeitumgebung ausgeführt werden kann."
    examples:
      enable: true
      
    more_feature:
      # more_feature_loop
      - title: "Vergleichen Sie Dokumente ganz einfach mit der Java-API"
        content: |
          Über die GroupDocs.Comparison for Java-API können Sie Dokumente unterstützter Formate einfach vergleichen, um Unterschiede zwischen ihnen zu finden. Das folgende Beispiel zeigt, wie man zwei Microsoft Word-Dokumente mit Java vergleicht:
          
          ```java
          try (Comparer comparer = new Comparer("D:\\source.pdf")) {
              comparer.add("D:\\target.pdf");
              comparer.compare("D:\\result.pdf");
          }
          ```
      # more_feature_loop
      - title: "Geben Sie die Vergleichsdetailebene an"
        content: "Mit GroupDocs.Comparison for Java können Sie Dokumente auf drei Ebenen vergleichen. Sie können die Vergleichsintensität auf niedrig (Text Wort für Wort mit Genauigkeit für Bildraster = 50 vergleichen), mittel (Text Zeichen für Zeichen mit Genauigkeit für Bildraster = 100 vergleichen) oder hoch (Text Zeichen für Zeichen mit Genauigkeit für Bildgebung vergleichen) einstellen Raster = 150)."

      # more_feature_loop
      - title: "Vergleichen Sie den Textstil"
        content: "Neben dem Dokumentinhalt ermöglicht die GroupDocs.Comparison for Java-API auch den Vergleich des Textstils.

        Schriftartname, -größe, -farbe, -stil (fett, kursiv, unterstrichen, Kapitälchen und Hyperlinks) und gegebenenfalls die Unterfarbe können ebenfalls verglichen werden, um Unterschiede zwischen verglichenen Dokumenten zu überprüfen, während Wörter und Zeichen verglichen werden.  

        Für den Absatzvergleich können auch Ausrichtung, Einzug (linker Einzug, rechter Einzug), Abstand (Leerzeichen danach, Leerzeichen davor), Einzug der ersten Zeile und Zeilenabstand verglichen werden.  

        Ebenso können ggf. auch andere Abschnitte einer Seite über die GroupDocs.Comparison for Java-API verglichen werden. Zu den Abschnitten gehören Fußzeilenabstand, Seitenränder (links, rechts, oben und unten), Seitenhöhe, Seitenausrichtung, Rahmenfarbe und Linienbreite."
      
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Nachfolgend finden Sie eine Übersicht über GroupDocs.Comparison for Java:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Überblick"
          content: |
            * Vergleichen Sie Inhalte und Stile
            * Vergleichszusammenfassung abrufen
            * Änderungen in Word akzeptieren/ablehnen
            * 3 Word-Dateien zusammenführen und vergleichen
            * Unterstützung für Streams
            * Dateityperkennung über Stream
            * Geschützte Dateien vergleichen
            * Vergleichen Sie verschlüsselte Dateien
            * Vergleich als Bild speichern
            * Vergleichen Sie eine bestimmte Seite in Word
            * Wasserzeichen im PDF vergleichen
            * Änderungen übernehmen/verwerfen
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison for Java unterstützt alle gängigen [Dokumentdateiformate](https://docs.groupdocs.com/comparison/java/supported-document-formats/), einschließlich: Microsoft Office, Bilder, Diagramme und viele andere .
        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** [DOC](https://products.groupdocs.com/comparison/java/doc/), [DOCX](https://products.groupdocs.com/comparison/java/docx/), [DOCM](https://products.groupdocs.com/comparison/java/docm/), [DOT](https://products.groupdocs.com/comparison/java/dot/), [DOTX](https://products.groupdocs.com/comparison/java/dotx/), [DOTM](https://products.groupdocs.com/comparison/java/dotm/), [RTF](https://products.groupdocs.com/comparison/java/rtf/), [TXT](https://products.groupdocs.com/comparison/java/txt/)
                * **Excel:** [XLS](https://products.groupdocs.com/comparison/java/xls/), [XLSX](https://products.groupdocs.com/comparison/java/xlsx/), [XLSM](https://products.groupdocs.com/comparison/java/xlsm/), [XLSB](https://products.groupdocs.com/comparison/java/xlsb/), [XLTM](https://products.groupdocs.com/comparison/java/xltm/), [XLT](https://products.groupdocs.com/comparison/java/xlt/), [XLTM](https://products.groupdocs.com/comparison/java/xltm/), [XLTX](https://products.groupdocs.com/comparison/java/xltx/), [XLAM](https://products.groupdocs.com/comparison/java/xlam/), [SXC](https://products.groupdocs.com/comparison/java/sxc/), [SpreadsheetML](https://products.groupdocs.com/comparison/java/xml/)
                * **PowerPoint:** [PPT](https://products.groupdocs.com/comparison/java/ppt/), [PPTX](https://products.groupdocs.com/comparison/java/pptx/), [PPS](https://products.groupdocs.com/comparison/java/pps/), [PPSX](https://products.groupdocs.com/comparison/java/ppsx/), [PPSM](https://products.groupdocs.com/comparison/java/ppsm/), [POT](https://products.groupdocs.com/comparison/java/pot/), [POTM](https://products.groupdocs.com/comparison/java/potm/), [POTX](https://products.groupdocs.com/comparison/java/potx/), [PPTM](https://products.groupdocs.com/comparison/java/pptm/)
                * **Visio:** [VSD](https://products.groupdocs.com/comparison/java/vsd/), [VDX](https://products.groupdocs.com/comparison/java/vdx/), [VSS](https://products.groupdocs.com/comparison/java/vss/), [VSSX](https://products.groupdocs.com/comparison/java/vssx/), [VSX](https://products.groupdocs.com/comparison/java/vsx/), [VST](https://products.groupdocs.com/comparison/java/vst/), [VSTX](https://products.groupdocs.com/comparison/java/vstx/), [VTX](https://products.groupdocs.com/comparison/java/vtx/), [VSDX](https://products.groupdocs.com/comparison/java/vsdx/), [VDW](https://products.groupdocs.com/comparison/java/vdw/), [VSTM](https://products.groupdocs.com/comparison/java/vstm/), [VSSM](https://products.groupdocs.com/comparison/java/vssm/), [VSDM](https://products.groupdocs.com/comparison/java/vsdm/)
                * **Outlook:** [MSG](https://products.groupdocs.com/comparison/java/msg/), [EML](https://products.groupdocs.com/comparison/java/eml/), [EMLX](https://products.groupdocs.com/comparison/java/emlx/), [PST](https://products.groupdocs.com/comparison/java/pst/), [OST](https://products.groupdocs.com/comparison/java/ost/)
                * **OneNote:** [ONE](https://products.groupdocs.com/comparison/java/one/)

        right:
          enable: true
          table:
            # table loop
            - title: "Andere Formate"
              content: |
                * **Programmiersprachen**: [CS](https://products.groupdocs.com/comparison/java/cs/), [Java](https://products.groupdocs.com/comparison/java/java/), [CPP](https://products.groupdocs.com/comparison/java/cpp/), [JS](https://products.groupdocs.com/comparison/java/js/), [PY](https://products.groupdocs.com/comparison/java/py/), [RB](https://products.groupdocs.com/comparison/java/rb/), [PL](https://products.groupdocs.com/comparison/java/pl/), [ASM](https://products.groupdocs.com/comparison/java/asm/), [GROOVY](https://products.groupdocs.com/comparison/java/groovy/), [JSON](https://products.groupdocs.com/comparison/java/json/), [PHP](https://products.groupdocs.com/comparison/java/php/), [SQL](https://products.groupdocs.com/comparison/java/sql/), [LOG](https://products.groupdocs.com/comparison/java/log/), [DIFF](https://products.groupdocs.com/comparison/java/diff/), [LESS](https://products.groupdocs.com/comparison/java/less/), [SCALA](https://products.groupdocs.com/comparison/java/scala/)
                * **OpenDocument**: [ODT](https://products.groupdocs.com/comparison/java/odt/), [OTT](https://products.groupdocs.com/comparison/java/ott/), [ODS](https://products.groupdocs.com/comparison/java/ods/), [ODP](https://products.groupdocs.com/comparison/java/odp/), [OTP](https://products.groupdocs.com/comparison/java/otp/)
                * **Portable**: [PDF](https://products.groupdocs.com/comparison/java/pdf/), [MOBI](https://products.groupdocs.com/comparison/java/mobi/)
                * **AutoCAD**: [DXF](https://products.groupdocs.com/comparison/java/dxf/), [DWG](https://products.groupdocs.com/comparison/java/dwg/)
                * **Email**: [EML](https://products.groupdocs.com/comparison/java/eml/), [EMLX](https://products.groupdocs.com/comparison/java/emlx/), [MSG](https://products.groupdocs.com/comparison/java/msg/)
                * **Images**: [JPEG](https://products.groupdocs.com/comparison/java/jpeg/), [BMP](https://products.groupdocs.com/comparison/java/bmp/), [PNG](https://products.groupdocs.com/comparison/java/png/), [GIF](https://products.groupdocs.com/comparison/java/gif/), [DCM](https://products.groupdocs.com/comparison/java/dcm/), [DICOM](https://products.groupdocs.com/comparison/java/dicom/), [DjVu](https://products.groupdocs.com/comparison/java/djvu/)
                * **Web**: [HTM](https://products.groupdocs.com/comparison/java/htm/), [HTML](https://products.groupdocs.com/comparison/java/html/), [MHTML](https://products.groupdocs.com/comparison/java/mhtml/)
                * **Text**: [TXT](https://products.groupdocs.com/comparison/java/txt/)

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Comparison for Java unterstützt folgende Betriebssysteme, Frameworks und Paketmanager:
      
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Betriebssysteme"
              content: |
                * Microsoft Windows Desktop
                * Microsoft Windows Server
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "Unterstützte Frameworks"
              content: |
                * Java 7 (1.7) oder höher

        right:
          enable: true
          table:
            
            # table loop
            - icon: "fas fa-cogs"
              title: "Entwicklungsumgebungen"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse
            # table loop
            - icon: "fas fa-tools"
              title: "Build-Automatisierungstool"
              content: |
                * Maven

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Comparison for Java Funktionen"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "[Vergleichen und identifizieren Sie Änderungen im Inhalts- und Textstil](https://docs.groupdocs.com/comparison/java/compare-documents/)"

      # feature loop
      - icon: "fas fa-eye"
        content: "[Speichern Sie die zusammengefasste Vergleichsliste der verglichenen Dokumente](https://docs.groupdocs.com/comparison/java/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-bolt"
        content: "[Vergleichen Sie bestimmte Seiten von Word-Dokumenten](https://docs.groupdocs.com/comparison/java/accept-or-reject-detected-changes/)"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "[Führen Sie bis zu drei Microsoft Word-Dateien zum Vergleich zusammen und unterstützen Sie die Funktion „Änderungen verfolgen“.](https://docs.groupdocs.com/comparison/java/compare-multiple-documents-with-specific-compare-settings/)"

      # feature loop
      - icon: "fas fa-code"
        content: "[Erkennen Sie beim Vergleich ganz einfach, welche Änderungen aus welchem ​​Dokument stammen](https://docs.groupdocs.com/comparison/java/get-list-of-changes/)"

      # feature loop
      - icon: "fas fa-cloud"
        content: "[Unterstützung zum Lesen von Quelldokumenten und Senden des resultierenden Dokuments über Streams](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "[Erkennen Sie den Dateiformattyp beim Abrufen aus dem Stream](https://docs.groupdocs.com/comparison/java/get-file-info/)"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "[Vergleichen Sie passwortgeschützte Dokumente](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/)"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "[Vergleichsergebnis als Bild speichern](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-border-all"
        content: "[Vergleichen Sie verschiedene Dateiformate als Bild](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-wrench"
        content: "[Vergleichen Sie Wasserzeichen in PDF-Dokumenten](https://docs.groupdocs.com/comparison/java/how-to-spot-photos-differences-in-java-or-kotlin/)"

      # feature loop
      - icon: "fas fa-columns"
        content: "[Vergleichen Sie Dokumente aus einer Datei oder einem Stream und senden Sie das Ergebnisdokument per Stream oder Datei](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-file-word"
        content: "[Akzeptieren oder verwerfen Sie Änderungen nach dem Vergleich von Word-, PDF- oder Excel-Dateien](https://docs.groupdocs.com/comparison/java/accept-or-reject-detected-changes/)"

      # feature loop
      - icon: "fas fa-envelope"
        content: "[Vergleichen Sie verschlüsselte Dokumente per Datei oder Stream](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-print"
        content: "[Gemessene Lizenzierungsoption für Vergleichsvorgänge](https://docs.groupdocs.com/comparison/java/evaluation-limitations-and-licensing-of-groupdocs-comparison/)"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "[Markieren Sie Text für markierte Änderungen beim Vergleich von PDF-, Word-, Excel-, PowerPoint- und Notizdokumenten](https://docs.groupdocs.com/comparison/java/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-lock"
        content: "[Berechnen Sie die korrekten Koordinaten von Änderungen in PDF-, PowerPoint-Folien und Diagrammen](https://docs.groupdocs.com/comparison/java/get-changes-coordinates/)"

      # feature loop
      - icon: "fas fa-file-code"
        content: "[Vergleichen Sie mehrere (mehr als zwei) PDF-, Excel-, OneNote-, Diagramm-, E-Mail- und Textdokumente](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/)"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "[Vergleichen Sie Kopf- und Fußzeile der unterstützten Dateiformate](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "[Vergleichen Sie Dokumente und speichern Sie Dokumentseiten verschiedener Formate als Bilder](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"


############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison bietet APIs zum Anzeigen von Dokumenten für andere gängige Entwicklungsumgebungen"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
          product: "GroupDocs.Comparison"
          platform: ".NET"
          link: "/comparison/net/"

############################# Back to top ###############################
back_to_top:
  enable: true
---