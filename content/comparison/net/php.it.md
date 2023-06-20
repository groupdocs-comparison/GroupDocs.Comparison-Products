
---
############################# Static ############################
layout: "auto-gen-comparison"
date: 2021-05-13T12:45:19+03:00
draft: false

############################# Head ############################
head_title: "Confronta due file PHP in .NET | API di confronto dei documenti"
head_description: "Confronta e unisci più di due file PHP in applicazioni C# .NET. Recupera il riepilogo delle differenze nel contenuto, nel testo e nello stile di PHP file, immagini e formati di documenti."

############################# Header ############################
title: "Confronta i file PHP in C# .NET"
description: "API di confronto dei documenti .NET per rilevare le modifiche tra due versioni di file PHP ed esportare in un documento finale con un riepilogo dettagliato delle differenze tra i documenti confrontati."
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Scarica la prova gratuita"
    link: "https://downloads.groupdocs.com/comparison/net"

############################# SubMenu ############################
submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Comparison per .NET"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-comparison-net.png"
        product: "GroupDocs.Comparison"
        platform: ".NETTO"

    middle:
        button: 
            # ciclo di pulsanti
            - link: "https://apireference.groupdocs.com/comparison/net"
              text: "Riferimento API"

            # ciclo di pulsanti
            - link: "https://github.com/groupdocs-comparison"
              text: "Esempi di codice"

            # ciclo di pulsanti
            - link: "https://products.groupdocs.app/comparison/family"
              text: "Demo dal vivo"

            # ciclo di pulsanti
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "Prezzi"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/net"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: "Informazioni su GroupDocs.Comparison per l'API .NET"
    content: |
        [GroupDocs.Comparison per .NET](/it/comparison/net/) è un'API .NET nativa per il confronto di più immagini e documenti dello stesso formato. Ti aiuta a rilevare le differenze all'interno di paragrafi, parole, caratteri, forme, persino gli stili di testo dei documenti confrontati, unire le modifiche ed esportare in un documento finale. Supporta il confronto e l'unione di PDF, documenti Word, fogli di calcolo Excel, presentazioni PowerPoint, diagrammi Visio, e-mail di Outlook, HTML, disegni e formati di file immagine senza utilizzare alcuna libreria esterna.

############################# Steps ############################
steps:
    enable: true
    title_left: "Passaggi per confrontare i file PHP in C#"
    content_left: |
        [GroupDocs.Comparison](/comparison/net/) semplifica agli sviluppatori .NET il confronto e l'unione di più file PHP nelle loro applicazioni implementando pochi semplici passaggi.
        *   Crea un'istanza dell'oggetto **Comparer** con il percorso o il flusso del documento di origine.
        * Chiamare il metodo Add e specificare il percorso o il flusso del documento di destinazione. Ripetere questo passaggio per ogni documento di destinazione.
        * Chiama il metodo Confronta.
    title_right: "Requisiti di sistema"
    content_right: |
        GroupDocs.Comparison per le API .NET è supportato su tutte le principali piattaforme e sistemi operativi. Prima di eseguire il codice seguente, assicurati di avere i seguenti prerequisiti installati sul tuo sistema.
        *   Sistemi operativi: Microsoft Windows, Linux, Mac OS
        * Ambienti di sviluppo: Microsoft Visual Studio, Xamarin, MonoDevelop
        * Framework: .NET Framework, .NET Standard, .NET Core, Mono
        * Ottieni l'ultima versione di GroupDocs.Comparison per .NET scaricata da [NuGet](https://www.nuget.org/packages/groupdocs.comparison)
    code: |
        ```cs
        // Confronta più documenti dal disco locale
        
        using (Comparer comparer = new Comparer("source.php"))
        {
        	comparer.Add("target1.php");
            comparer.Add("target2.php");
            comparer.Add("target3.php");
            comparer.Compare("result.php"); // Crea il file dei risultati con il nome specificato
        }
        
        // Confronta più documenti dallo stream
        
        using (Comparer comparer = new Comparer(File.OpenRead("source.php")))
        {
        	comparer.Add(File.OpenRead("target1.php"));
            comparer.Add(File.OpenRead("target2.php"));
            comparer.Add(File.OpenRead("target3.php"));
            comparer.Compare(File.Create("result.php")); // Crea il file dei risultati con il nome specificato
        }
        ```

############################# Demos ############################
demos:
    enable: true
    title: "Demo live di confronto di PHP file"
    content: |
        Rileva subito le differenze tra i file PHP visitando il sito web [GroupDocs.Comparison Live Demos](https://products.groupdocs.app/comparison/family).
        La demo dal vivo ha i seguenti vantaggi

############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-php"
          title: "Informazioni sul formato file PHP"
          content: |
            Un file con estensione .php si riferisce al linguaggio di programmazione open source utilizzato per scrivere script lato server da eseguire sul server. È il linguaggio di scripting Web più popolare e potente ampiamente utilizzato per lo sviluppo di applicazioni Web su larga scala. PHP è al centro del più grande sistema di blogging sul web, ovvero WordPress, e gestisce il più grande social network Facebook. Funziona su varie piattaforme come Windows, Linux, Unix, Mac OS X, ecc. ed è compatibile con quasi tutti i server utilizzati oggi, ad esempio Apache, IIS, ecc. PHP supporta un'ampia gamma di database incluso MySQL.
          link: "https://docs.fileformat.com/image/php/"

############################# More Formats ############################
more_formats:
    enable: true
    title: "Confronto di altri formati di file"
    content: |
        API di confronto di immagini e documenti multiformato per .NET. Analizza le differenze tra documenti dello stesso formato senza utilizzare alcuno strumento esterno.
    format: 
        # format loop
        - name: "Compare PDF Files"
          link: "https://products.groupdocs.com/comparison/net/pdf/"
          description: "Adobe Portable Document Format"

        # format loop
        - name: "Compare DOC Files"
          link: "https://products.groupdocs.com/comparison/net/doc/"
          description: "Microsoft Word Document"

        # format loop
        - name: "Compare DOCM Files"
          link: "https://products.groupdocs.com/comparison/net/docm/"
          description: "Microsoft Word Macro-Enabled Document"

        # format loop
        - name: "Compare DOCX Files"
          link: "https://products.groupdocs.com/comparison/net/docx/"
          description: "Microsoft Word Open XML Document"

        # format loop
        - name: "Compare DOT Files"
          link: "https://products.groupdocs.com/comparison/net/dot/"
          description: "Microsoft Word Document Template"

        # format loop
        - name: "Compare DOTM Files"
          link: "https://products.groupdocs.com/comparison/net/dotm/"
          description: "Microsoft Word Macro-Enabled Template"

        # format loop
        - name: "Compare DOTX Files"
          link: "https://products.groupdocs.com/comparison/net/dotx/"
          description: "Word Open XML Document Template"

        # format loop
        - name: "Compare RTF Files"
          link: "https://products.groupdocs.com/comparison/net/rtf/"
          description: "Rich Text File Format"

        # format loop
        - name: "Compare TXT Files"
          link: "https://products.groupdocs.com/comparison/net/txt/"
          description: "Plain Text File Format"

        # format loop
        - name: "Compare XLS Files"
          link: "https://products.groupdocs.com/comparison/net/xls/"
          description: "Microsoft Excel Binary File Format"

        # format loop
        - name: "Compare XLSX Files"
          link: "https://products.groupdocs.com/comparison/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop
        - name: "Compare XLTM Files"
          link: "https://products.groupdocs.com/comparison/net/xltm/"
          description: "Microsoft Excel macro-enabled template"

        # format loop
        - name: "Compare XLSM Files"
          link: "https://products.groupdocs.com/comparison/net/xlsm/"
          description: "Microsoft Excel Macro-Enabled Spreadsheet"

        # format loop
        - name: "Compare XLSB Files"
          link: "https://products.groupdocs.com/comparison/net/xlsb/"
          description: "Microsoft Excel Binary Spreadsheet File"

        # format loop
        - name: "Compare CSV Files"
          link: "https://products.groupdocs.com/comparison/net/csv/"
          description: "Comma Separated Values File"

        # format loop
        - name: "Compare PPT Files"
          link: "https://products.groupdocs.com/comparison/net/ppt/"
          description: "PowerPoint Presentation"

        # format loop
        - name: "Compare PPS Files"
          link: "https://products.groupdocs.com/comparison/net/pps/"
          description: "Microsoft PowerPoint Slide Show"

        # format loop
        - name: "Compare PPTX Files"
          link: "https://products.groupdocs.com/comparison/net/pptx/"
          description: "PowerPoint Open XML Presentation"

        # format loop
        - name: "Compare PPSX Files"
          link: "https://products.groupdocs.com/comparison/net/ppsx/"
          description: "PowerPoint Open XML Slide Show"

        # format loop
        - name: "Compare POT Files"
          link: "https://products.groupdocs.com/comparison/net/pot/"
          description: "Microsoft PowerPoint template"

        # format loop
        - name: "Compare POTX Files"
          link: "https://products.groupdocs.com/comparison/net/potx/"
          description: "Microsoft PowerPoint Open XML Template"

        # format loop
        - name: "Compare ODS Files"
          link: "https://products.groupdocs.com/comparison/net/ods/"
          description: "Open Document Spreadsheet"

        # format loop
        - name: "Compare ODP Files"
          link: "https://products.groupdocs.com/comparison/net/odp/"
          description: "OpenDocument Presentation File Format"

        # format loop
        - name: "Compare OTP Files"
          link: "https://products.groupdocs.com/comparison/net/otp/"
          description: "Origin Graph Template"

        # format loop
        - name: "Compare ODT Files"
          link: "https://products.groupdocs.com/comparison/net/odt/"
          description: "Open Document Text"

        # format loop
        - name: "Compare OTT Files"
          link: "https://products.groupdocs.com/comparison/net/ott/"
          description: "Open Document Template"

        # format loop
        - name: "Compare VST Files"
          link: "https://products.groupdocs.com/comparison/net/vst/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare JPEG Files"
          link: "https://products.groupdocs.com/comparison/net/jpeg/"
          description: "JPEG Image"

        # format loop
        - name: "Compare PNG Files"
          link: "https://products.groupdocs.com/comparison/net/png/"
          description: "Portable Network Graphic"

        # format loop
        - name: "Compare GIF Files"
          link: "https://products.groupdocs.com/comparison/net/gif/"
          description: "Graphical Interchange Format File"

        # format loop
        - name: "Compare BMP Files"
          link: "https://products.groupdocs.com/comparison/net/bmp/"
          description: "Bitmap File Format"

        # format loop
        - name: "Compare HTML Files"
          link: "https://products.groupdocs.com/comparison/net/html/"
          description: "Hyper Text Markup Language"

        # format loop
        - name: "Compare MHT Files"
          link: "https://products.groupdocs.com/comparison/net/mht/"
          description: "Mime HTML"

        # format loop
        - name: "Compare MHTML Files"
          link: "https://products.groupdocs.com/comparison/net/mhtml/"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop
        - name: "Compare MSG Files"
          link: "https://products.groupdocs.com/comparison/net/msg/"
          description: "Microsoft Outlook E-mail Message"

        # format loop
        - name: "Compare EML Files"
          link: "https://products.groupdocs.com/comparison/net/eml/"
          description: "E-mail Message"

        # format loop
        - name: "Compare EMLX Files"
          link: "https://products.groupdocs.com/comparison/net/emlx/"
          description: "Apple Mail E-mail File"

        # format loop
        - name: "Compare ONE Files"
          link: "https://products.groupdocs.com/comparison/net/one/"
          description: "Microsoft OneNote"

        # format loop
        - name: "Compare VSD Files"
          link: "https://products.groupdocs.com/comparison/net/vsd/"
          description: "Microsoft Visio 2003-2010 Drawing"

        # format loop
        - name: "Compare VSDX Files"
          link: "https://products.groupdocs.com/comparison/net/vsdx/"
          description: "Microsoft Visio Drawing"

        # format loop
        - name: "Compare VSS Files"
          link: "https://products.groupdocs.com/comparison/net/vss/"
          description: "Microsoft Visio 2003-2010 Stencil"

        # format loop
        - name: "Compare VST Files"
          link: "https://products.groupdocs.com/comparison/net/vst/"
          description: "Microsoft Visio 2003-2010 Template"

        # format loop
        - name: "Compare VDX Files"
          link: "https://products.groupdocs.com/comparison/net/vdx/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare CS Files"
          link: "https://products.groupdocs.com/comparison/net/cs/"
          description: "CSharp Language"

        # format loop
        - name: "Compare Java Files"
          link: "https://products.groupdocs.com/comparison/net/java/"
          description: "Java Language"

        # format loop
        - name: "Compare CPP Files"
          link: "https://products.groupdocs.com/comparison/net/cpp/"
          description: "C++ Language"

        # format loop
        - name: "Compare JS Files"
          link: "https://products.groupdocs.com/comparison/net/js/"
          description: "JavaScript Language"

        # format loop
        - name: "Compare PY Files"
          link: "https://products.groupdocs.com/comparison/net/py/"
          description: "Python Language"

        # format loop
        - name: "Compare RB Files"
          link: "https://products.groupdocs.com/comparison/net/rb/"
          description: "Ruby Language"

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison offers document viewing APIs for other popular formats"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for Java PHP"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/php/"

############################# Back to top ###############################
back_to_top:
    enable: true
---
