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
head_title: "API di confronto documenti C# .NET | Confronta e unisci PDF Word Excel Web e testo"
head_description: "API di confronto documenti C# .NET. Confronta e unisci PDF Word DOC DOCX, fogli di calcolo Excel, PPT, PPTX, HTML, EMLX MSG, VSDX, DXF DWG e formati di file immagine."

############################# Header ############################
title: "API .NET per confrontare file"
description: "Sviluppa applicazioni utilizzando l'API di confronto documenti .NET per controllare e confrontare i file per differenze di contenuto e stile."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Scarica la prova gratuita"
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
              text: "Panoramica"

            # button loop
            - link: "#features"
              text: "Caratteristiche"

            # button loop
            - link: "#support"
              text: "Supporto"

            # button loop
            - link: "https://products.groupdocs.app/comparison"
              text: "Dimostrazione dal vivo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "Prezzi"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    example_image: "/comparison/comparison-example.png"
    content: |
      
    more_overview:
      # more_overview_loop
      - title: "Cos'è GroupDocs.Comparison for .NET"
        content: "L'API GroupDocs.Comparison for .NET è una soluzione veloce e affidabile pronta per l'uso durante la creazione di applicazioni per la ricerca e l'evidenziazione delle differenze tra documenti dello stesso formato o di formati diversi in C#, ASP.NET o altre tecnologie correlate alla piattaforma software .NET."

      # more_overview_loop
      - title: "Formati supportati"
        content: "La libreria GroupDocs.Comparison supporta il rilevamento delle differenze sia nel contenuto che nello stile del testo tra i formati di immagini e documenti più diffusi come PDF, HTML, posta elettronica Outlook, documenti Microsoft Office Word, fogli di calcolo Excel, presentazioni PowerPoint, OneNote, diagrammi Visio, testi, png , immagini gif e bmp oltre a centinaia di altri formati."
        
      # more_overview_loop
      - title: "Funzionalità di confronto"
        content: "Il confronto può essere eseguito per rilevare cambiamenti nel contenuto di parole, paragrafi, tabelle o grafici e nei loro stili e fornirà un documento di confronto che elenca un riepilogo delle differenze, del loro numero e del tipo di appartenenza. GroupDocs.Comparison for .NET può facilmente estrarre informazioni di base sul documento di origine, confrontare e salvare documenti semplici, protetti da password e crittografati di vari formati tramite un file o un flusso di dati."
        
      # more_overview_loop
      - title: "Documentazione ed esempi"
        content: "Esiste già molta documentazione sull'utilizzo della libreria Comparison su diverse piattaforme con esempi di codice, quindi non devi pensare troppo a come lavorare con l'API GroupDocs.Comparison per .NET nella tua applicazione."
        
      # more_overview_loop
      - title: "Compatibilità"
        content: "Puoi utilizzare GroupDocs.Comparison for .NET per creare applicazioni in qualsiasi ambiente di sviluppo orientato alla piattaforma .NET. È compatibile con tutti i linguaggi basati su .NET e supporta i sistemi operativi più diffusi (Windows, Linux, MacOS) su cui è possibile installare Mono o framework .NET (incluso .NET Core)."
    examples:
      enable: true
      
    more_feature:
      # more_feature_loop
      - title: "Confronta facilmente i documenti utilizzando l'API .NET"
        content: |
          L'API GroupDocs.Comparison for .NET ti offre un modo semplice ed efficiente per confrontare i tuoi file. Di seguito è riportato un esempio che mostra come confrontare due documenti DOCX utilizzando C#:  

          ```cs
          // File di origine e di destinazione da confrontare
          string source = @"source.docx";
          string target = @"target.docx";
          Comparer comparer = new Comparer();
          // Confronta due documenti
          ICompareResult result = comparer.Compare(source, target, new ComparisonSettings());
          ```
      # more_feature_loop
      - title: "Scegli il livello di dettaglio per il confronto"
        content: "Con GroupDocs.Comparison for .NET puoi specificare in che misura desideri che i documenti vengano confrontati. È possibile scegliere tra basso (confronta il testo parola per parola con precisione per la griglia di imaging = 50), medio (confronta il testo carattere per carattere con precisione per la griglia di imaging = 100) o alto (confronta il testo carattere per carattere con precisione per la griglia di imaging = 150)."

      # more_feature_loop
      - title: "Supporto per il confronto degli stili di testo"
        content: |
          GroupDocs.Comparison for .NET offre funzionalità per confrontare lo stile del testo.  

          Durante il confronto delle parole e dei caratteri dei documenti, è possibile confrontare il nome del carattere, la dimensione del carattere, il colore del carattere, lo stile del carattere (grassetto, corsivo, sottolineato, maiuscoletto, collegamento ipertestuale) e il colore della sottolineatura (se applicabile) per individuare le differenze.  

          Durante il confronto dei paragrafi, puoi confrontare stili quali l'allineamento del paragrafo, il rientro (rientro sinistro, rientro destro), la spaziatura del paragrafo (spazio dopo, spazio prima), il rientro della prima riga e l'interlinea.  

          GroupDocs.Comparison for .NET supporta anche il confronto di altre sezioni di una pagina, ove applicabile, come distanza del piè di pagina, altezza e orientamento della pagina, margini (sinistro, destro, superiore e inferiore), larghezza della linea del bordo e colore del bordo.  
      
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Di seguito è riportata una panoramica di GroupDocs.Comparison for .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Panoramica"
          content: |
            * Confronto documenti
            * Confronto dei file HTML
            * Confronto PDF
            * Confronto dei diagrammi
            * Confronta il contenuto del file
            * Confronta gli stili di testo
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison for .NET supporta tutti i più diffusi [formati di file di documenti](https://docs.groupdocs.com/comparison/net/supported-document-formats/) tra cui: Microsoft Office, PDF, immagini e molti altri .
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
            - title: "Altri formati"
              content: |
                * **Linguaggi di programmazione**: [CS](https://products.groupdocs.com/comparison/net/cs/), [Java](https://products.groupdocs.com/comparison/net/java/), [CPP](https://products.groupdocs.com/comparison/net/cpp/), [JS](https://products.groupdocs.com/comparison/net/js/), [PY](https://products.groupdocs.com/comparison/net/py/), [RB](https://products.groupdocs.com/comparison/net/rb/), [PL](https://products.groupdocs.com/comparison/net/pl/), [ASM](https://products.groupdocs.com/comparison/net/asm/), [GROOVY](https://products.groupdocs.com/comparison/net/groovy/), [JSON](https://products.groupdocs.com/comparison/net/json/), [PHP](https://products.groupdocs.com/comparison/net/php/), [SQL](https://products.groupdocs.com/comparison/net/sql/), [LOG](https://products.groupdocs.com/comparison/net/log/), [DIFF](https://products.groupdocs.com/comparison/net/diff/), [LESS](https://products.groupdocs.com/comparison/net/less/), [SCALA](https://products.groupdocs.com/comparison/net/scala/)
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
          GroupDocs.Comparison for .NET supporta i seguenti sistemi operativi, framework e gestori di pacchetti:
      
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Sistemi operativi"
              content: |
                * Windows Desktop
                * Windows Server
                * Windows Azure
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "Framework supportati"
              content: |
                * .NET Framework 2.0 o più alto
                * Mono Framework 1.2 o più alto
                * .NET Standard 2.0
                * .NET Core 2.0

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Gestore dei pacchetti"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Ambienti di sviluppo"
              content: |
                * Microsoft Visual Studio
                * Xamarin.Android
                * Xamarin.IOS
                * Xamarin.Mac
                * MonoDevelop

############################# Features ############################
features:
    enable: true
    title: "Funzionalità di GroupDocs.Comparison for .NET"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "[Identificare le differenze nel contenuto e negli stili dei caratteri](https://docs.groupdocs.com/comparison/net/compare-documents/)"

      # feature loop
      - icon: "fas fa-eye"
        content: "[Salva un rapporto riepilogativo di tutte le differenze trovate dopo il confronto dei file](https://docs.groupdocs.com/comparison/net/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-bolt"
        content: "[Applica o rifiuta le modifiche dopo aver analizzato le differenze ed esportato il file risultante](https://docs.groupdocs.com/comparison/net/accept-or-reject-detected-changes/)"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "[Supporto per la funzionalità “Traccia modifiche” di Microsoft Word durante il confronto di file Word](https://docs.groupdocs.com/comparison/net/show-revisions/)"

      # feature loop
      - icon: "fas fa-code"
        content: "[Individua in modo univoco le modifiche provenienti da ciascun documento confrontato](https://docs.groupdocs.com/comparison/net/get-list-of-changes/)"

      # feature loop
      - icon: "fas fa-cloud"
        content: "[Leggere e inviare documenti tramite flussi](https://docs.groupdocs.com/comparison/net/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "[Licenze misurate: fatturazione in base all'utilizzo dell'API](https://docs.groupdocs.com/comparison/net/licensing-and-evaluation-limitations/)"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "[Confronta più documenti di origine con un singolo documento di destinazione](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/)"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "[Confronta tra loro pagine specifiche di file Word: accetta o rifiuta tutte le modifiche in un singolo documento Word](https://docs.groupdocs.com/comparison/net/accept-or-reject-detected-changes/)"

      # feature loop
      - icon: "fas fa-border-all"
        content: "[Unisci fino a 3 documenti Word e confronta le formule utilizzate nei file Word](https://docs.groupdocs.com/comparison/net/how-to-merge-source-code-files/)"

      # feature loop
      - icon: "fas fa-wrench"
        content: "[Ottieni informazioni sui documenti da filePath](https://docs.groupdocs.com/comparison/net/get-file-info/)"

      # feature loop
      - icon: "fas fa-columns"
        content: "[Salva il risultato del confronto HTML come immagini](https://docs.groupdocs.com/comparison/net/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-file-word"
        content: "[Opzione per mostrare o nascondere il contenuto eliminato](https://docs.groupdocs.com/comparison/net/show-gap-lines/)"

      # feature loop
      - icon: "fas fa-envelope"
        content: "[Opzione per attivare o disattivare il confronto degli stili dei documenti](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fas fa-print"
        content: "[Specifica le stringhe per contrassegnare gli elementi inseriti, eliminati e di modifica dello stile nel documento di confronto](https://docs.groupdocs.com/comparison/net/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "[Specifica il separatore di parole e il colore del carattere per stilizzare il testo confrontato](https://docs.groupdocs.com/comparison/net/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-lock"
        content: "[Calcola le coordinate corrette delle modifiche in PDF, Word, diapositive e diagrammi PowerPoint](https://docs.groupdocs.com/comparison/net/get-changes-coordinates/)"

      # feature loop
      - icon: "fas fa-file-code"
        content: "[Confronta file protetti da password](https://docs.groupdocs.com/comparison/net/how-to-compare-password-protected-files/)"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "[Confronta i titoli dei grafici nei fogli di calcolo: genera un grafico nei file di celle risultanti](https://docs.groupdocs.com/comparison/net/how-to-compare-spreadsheet-or-tables/)"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "[Dimensiona automaticamente le forme automatiche nel file risultante del documento Cells](https://docs.groupdocs.com/comparison/net/how-to-compare-spreadsheet-or-tables/)"

      # feature loop
      - icon: "fas fa-heading"
        content: "[Accedi alla pagina di riepilogo dettagliata per rilevare le modifiche tra i file di documento di origine e di destinazione](https://docs.groupdocs.com/comparison/net/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "[Confronta i file dei linguaggi di programmazione e scripting più popolari](https://docs.groupdocs.com/comparison/net/get-supported-document-formats/)"

      # feature loop
      - icon: "fas fa-cube"
        content: "[Confronta più documenti PDF, Word, Excel, diagrammi, e-mail, testo e OneNote (più di due).](https://docs.groupdocs.com/comparison/net/compare-multiple-documents-with-specific-compare-settings/)"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "[Confronta intestazione e piè di pagina dei formati di file supportati](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "[Confronta segnalibri, variabili e proprietà personalizzate dei formati di documenti Word](https://docs.groupdocs.com/comparison/net/compare-bookmarks-in-word/)"

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison offre API di visualizzazione di documenti per altri ambienti di sviluppo popolari"

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