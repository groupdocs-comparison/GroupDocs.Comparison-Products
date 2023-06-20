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
head_description: "API di confronto dei documenti C# .NET. Confronta e unisci PDF Word DOC DOCX, Excel Spreadsheet, PPT, PPTX, HTML, EMLX MSG, VSDX, DXF DWG e formati di file immagine."

############################# Header ############################
title: "API .NET per confrontare i file"
description: "Sviluppa applicazioni utilizzando l'API di confronto dei documenti .NET per controllare e confrontare i file per differenze di contenuto e stile."
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
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
        product: "GroupDocs.Comparison"
        platform: ".NET"

    middle:
        button:
            # ciclo di pulsanti
            - link: "#overview"
              text: "Panoramica"

            # ciclo di pulsanti
            - link: "#features"
              text: "Caratteristiche"

            # ciclo di pulsanti
            - link: "#support"
              text: "Supporto"

            # ciclo di pulsanti
            - link: "https://products.groupdocs.app/comparison"
              text: "Demo dal vivo"

            # ciclo di pulsanti
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
      - title: "Cos'è GroupDocs.Comparison"
        content: "GroupDocs.Comparison per .NET API è una soluzione veloce e affidabile pronta per l'uso durante la creazione di applicazioni per la ricerca e l'evidenziazione delle differenze tra documenti dello stesso o diversi formati in C#, ASP.NET o altre tecnologie legate al software .NET piattaforma."

      # more_overview_loop
      - title: "Formati supportati"
        content: "La libreria GroupDocs.Comparison supporta il rilevamento delle differenze sia nel contenuto che nello stile del testo tra i formati di immagini e documenti più diffusi come PDF, HTML, e-mail Outlook, documenti Microsoft Office Word, fogli di calcolo Excel, presentazioni PowerPoint, OneNote, diagrammi Visio, testi, immagini png, gif e bmp oltre a centinaia di altri formati."
        
      # more_overview_loop
      - title: "Capacità di confronto"
        content: "Il confronto può essere eseguito per rilevare i cambiamenti nel contenuto di parole, paragrafi, tabelle o grafici e i loro stili e ti fornirà un documento di confronto che elenca un riepilogo delle differenze, il loro numero e il tipo di appartenenza. GroupDocs.Comparison for .NET può facilmente estrarre informazioni di base sul documento di origine, confrontare e salvare documenti semplici, protetti da password e crittografati di vari formati attraverso un file o un flusso di dati."
        
      # more_overview_loop
      - title: "Documentazione ed esempi"
        content: "C'è già molta documentazione sull'utilizzo della libreria Comparison su diverse piattaforme con esempi di codice, quindi non devi pensare a come lavorare con GroupDocs.Comparison per l'API .NET nella tua applicazione."
        
      # more_overview_loop
      - title: "Compatibilità"
        content: "È possibile utilizzare GroupDocs.Comparison per .NET per creare applicazioni in qualsiasi ambiente di sviluppo orientato alla piattaforma .NET. È compatibile con tutti i linguaggi basati su .NET e supporta i sistemi operativi più diffusi (Windows, Linux, MacOS) su cui è possibile installare framework Mono o .NET (incluso .NET Core)."
    examples:
      enable: true
      
    more_feature:
      # more_feature_loop
      - title: "Confronta facilmente i documenti utilizzando l'API .NET"
        content: |
          GroupDocs.Comparison per .NET API ti offre un modo semplice ed efficiente per confrontare i tuoi file. Di seguito è riportato un esempio che mostra come confrontare due documenti DOCX utilizzando C#:

          ```cs
          //File sorgente e destinazione da confrontare
          string source = @"source.docx";
          string target = @"target.docx";
          Comparer comparer = new Comparer();
          // Confronta due documenti
          ICompareResult result = comparer.Compare(source, target, new ComparisonSettings());
          ```
      # more_feature_loop
      - title: "Scegli il livello di dettaglio per il confronto"
        content: "Con GroupDocs.Comparison per .NET puoi specificare la misura in cui desideri che i documenti vengano confrontati. Puoi scegliere tra, basso (confronta il testo parola per parola con precisione per la griglia di imaging = 50), medio (confronta il testo carattere per carattere con accuratezza per la griglia dell'immagine = 100) o alta (confrontare il testo carattere per carattere con precisione per la griglia dell'immagine = 150)."

      # more_feature_loop
      - title: "Supporto per il confronto degli stili di testo"
        content: |
          GroupDocs.Comparison per .NET offre funzionalità per confrontare lo stile del testo.

          Durante il confronto di parole e caratteri di documenti, è possibile confrontare il nome del carattere, la dimensione del carattere, il colore del carattere, lo stile del carattere (grassetto, corsivo, sottolineato, maiuscoletto, collegamento ipertestuale) e il colore della sottolineatura (se applicabile) per trovare le differenze.

          Durante il confronto dei paragrafi, puoi confrontare stili come allineamento del paragrafo, rientro (rientro sinistro, rientro destro), spaziatura paragrafo (spazio dopo, spazio prima), rientro prima riga e interlinea.

          GroupDocs.Comparison per .NET supporta anche il confronto di altre sezioni di una pagina, ove applicabile, come la distanza del piè di pagina, l'altezza e l'orientamento della pagina, i margini (sinistro, destro, superiore e inferiore), la larghezza della linea del bordo e il colore del bordo.
      
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Di seguito è riportata una panoramica di GroupDocs.Comparison per .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Panoramica"
          content: |
            * Confronto documenti
            * Confronto di file HTML
            * Confronto PDF
            * Confronto del diagramma
            * Confronta il contenuto del file
            * Confronta gli stili di testo
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison per .NET supporta tutti i più diffusi [formati di file di documenti](https://docs.groupdocs.com/comparison/net/supported-document-formats/) tra cui: Microsoft Office, PDF, immagini e molti altri.
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
            - title: "Altri Formati"
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
          GroupDocs.Comparison per .NET supporta i seguenti sistemi operativi, framework e gestori di pacchetti:
      
        left:
          enable: true
          table:
            # ciclo di tabella
            - icon: "fab fa-windows"
              title: "Sistemi operativi"
              content: |
                * Windows Desktop
                * Windows Server
                * Windows Azure
                * Linux
                * MacOS

            # ciclo di tabella
            - icon: "fas fa-code"
              title: "Framework supportati"
              content: |
                * .NET Framework 2.0 o superiore
                * Mono Framework 1.2 o superiore
                * .NET Standard 2.0
                * .NET Core 2.0

        right:
          enable: true
          table:
            # ciclo di tabella
            - icon: "fas fa-box"
              title: "Gestione pacchetti"
              content: |
                * NuGet

            # ciclo di tabella
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
    title: "GroupDocs.Comparison per le funzionalità .NET"

    feature:
      # ciclo di funzionalità
      - icon: "fas fa-copy"
        content: "[Identifica le differenze nei contenuti e negli stili dei caratteri](https://docs.groupdocs.com/comparison/net/compare-documents/)"

      # ciclo di funzionalità
      - icon: "fas fa-eye"
        content: "[Salva un rapporto riassuntivo di tutte le differenze trovate dopo il confronto dei file](https://docs.groupdocs.com/comparison/net/get-extended-information-on-the-summary-page/)"

      # ciclo di funzionalità
      - icon: "fas fa-bolt"
        content: "[Applica o rifiuta le modifiche dopo aver analizzato le differenze ed esportato il file risultante](https://docs.groupdocs.com/comparison/net/accept-or-reject-detected-changes/)"
      
      # ciclo di funzionalità
      - icon: "fas fa-file-powerpoint"
        content: "[Supporto per la funzionalità “Traccia modifiche” di Microsoft Word durante il confronto dei file di Word](https://docs.groupdocs.com/comparison/net/show-revisions/)"

      # ciclo di funzionalità
      - icon: "fas fa-code"
        content: "[Individua in modo univoco le modifiche provenienti da ciascun documento confrontato](https://docs.groupdocs.com/comparison/net/get-list-of-changes/)"

      # ciclo di funzionalità
      - icon: "fas fa-cloud"
        content: "[Leggi e invia documenti tramite flussi](https://docs.groupdocs.com/comparison/net/load-file-from-stream/)"

      # ciclo di funzionalità
      - icon: "fas fa-remove-format"
        content: "[Licenze a consumo – Fatturazione in base all'utilizzo dell'API](https://docs.groupdocs.com/comparison/net/licensing-and-evaluation-limitations/)"

      # ciclo di funzionalità
      - icon: "fas fa-comment-slash"
        content: "[Confronta più documenti di origine con un unico documento di destinazione](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/)"

      # ciclo di funzionalità
      - icon: "fas fa-location-arrow"
        content: "[Confronta tra loro pagine specifiche di file Word – Accetta o rifiuta tutte le modifiche in un singolo documento Word](https://docs.groupdocs.com/comparison/net/accept-or-reject-detected-changes/ )"

      # ciclo di funzionalità
      - icon: "fas fa-border-all"
        content: "[Unisci fino a 3 documenti Word e confronta le formule utilizzate nei file Word](https://docs.groupdocs.com/comparison/net/how-to-merge-source-code-files/)"

      # ciclo di funzionalità
      - icon: "fas fa-wrench"
        content: "[Ottieni informazioni sui documenti da filePath](https://docs.groupdocs.com/comparison/net/get-file-info/)"

      # ciclo di funzionalità
      - icon: "fas fa-columns"
        content: "[Salva il risultato del confronto HTML come immagini](https://docs.groupdocs.com/comparison/net/generate-document-pages-preview/)"

      # ciclo di funzionalità
      - icon: "fas fa-file-word"
        content: "[Opzione per mostrare o nascondere i contenuti eliminati](https://docs.groupdocs.com/comparison/net/show-gap-lines/)"

      # ciclo di funzionalità
      - icon: "fas fa-envelope"
        content: "[Opzione per attivare o disattivare il confronto di stile dei documenti](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # ciclo di funzionalità
      - icon: "fas fa-print"
        content: "[Specificare le stringhe per contrassegnare gli elementi inseriti, eliminati e di modifica dello stile nel documento di confronto](https://docs.groupdocs.com/comparison/net/customize-changes-styles/)"

      # ciclo di funzionalità
      - icon: "fas fa-file-archive"
        content: "[Specificare il separatore di parole e il colore del carattere per stilizzare il testo confrontato](https://docs.groupdocs.com/comparison/net/customize-changes-styles/)"

      # ciclo di funzionalità
      - icon: "fas fa-lock"
        content: "[Calcola le coordinate corrette delle modifiche in diapositive e diagrammi PDF, Word, PowerPoint](https://docs.groupdocs.com/comparison/net/get-changes-coordinates/)"

      # ciclo di funzionalità
      - icon: "fas fa-file-code"
        content: "[Confronta file protetti da password](https://docs.groupdocs.com/comparison/net/how-to-compare-password-protected-files/)"
      
      # ciclo di funzionalità
      - icon: "fas fa-fill-drip"
        content: "[Confronta i titoli dei grafici nei fogli di calcolo – Genera grafico nei file delle celle risultanti](https://docs.groupdocs.com/comparison/net/how-to-compare-spreadsheet-or-tables/)"

      # ciclo di funzionalità
      - icon: "fas fa-file-excel"
        content: "[Ridimensiona automaticamente le forme automatiche nel file risultante del documento Cells](https://docs.groupdocs.com/comparison/net/how-to-compare-spreadsheet-or-tables/)"

      # ciclo di funzionalità
      - icon: "fas fa-heading"
        content: "[Accedi alla pagina di riepilogo dettagliata per rilevare le modifiche tra i file del documento di origine e di destinazione](https://docs.groupdocs.com/comparison/net/get-extended-information-on-the-summary-page/)"

      # ciclo di funzionalità
      - icon: "fas fa-project-diagram"
        content: "[Confronta i file dei linguaggi di programmazione e scripting più diffusi](https://docs.groupdocs.com/comparison/net/get-supported-document-formats/)"

      # ciclo di funzionalità
      - icon: "fas fa-cube"
        content: "[Confronta più (più di due) documenti PDF, Word, Excel, Diagram, Email, Text e OneNote](https://docs.groupdocs.com/comparison/net/compare-multiple-documents-with-specific -compare-impostazioni/)"

      # ciclo di funzionalità
      - icon: "fab fa-uncharted"
        content: "[Confronta intestazione e piè di pagina dei formati di file supportati](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # ciclo di funzionalità
      - icon: "fab fa-uncharted"
        content: "[Confronta segnalibri, variabili e proprietà personalizzate dei formati di documenti Word](https://docs.groupdocs.com/comparison/net/compare-bookmarks-in-word/)"

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison offre API per la visualizzazione di documenti per altri ambienti di sviluppo popolari"

    solution:
        # ciclo di soluzione
        - img_alt: "GroupDocs.Comparison per Java"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---