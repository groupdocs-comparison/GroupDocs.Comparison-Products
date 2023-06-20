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
head_title: "API di confronto dei documenti Java | Confronta testo e stile di PDF Word Excel HTML"
head_description: "API Java Document Comparison per confrontare e unire Word Excel PPTX OpenOffice, Web, PDF, AutoCAD e altri formati di file. Confronta i documenti con le revisioni."

############################# Header ############################
title: "API Java per confrontare i file"
description: "Crea applicazioni Java per confrontare in modo efficace il contenuto dei file per le differenze in tutti i formati standard di file di documenti e immagini."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Scarica la prova gratuita"
    link: "https://downloads.groupdocs.com/comparison/java"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Comparison per Java"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
        product: "GroupDocs.Comparison"
        platform: "Java"

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
            - link: "https://purchase.groupdocs.com/pricing/comparison/java"
              text: "Prezzi"

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
      - title: "Cos'è GroupDocs.Comparison"
        content: "GroupDocs.Comparison per Java è l'API più flessibile e facile da usare per aiutarti a sviluppare applicazioni di confronto dei documenti nell'ambiente Java. Il controllo delle differenze e l'API di unione dei documenti ti consentono di rilevare modifiche e differenze nel contenuto, nonché in stile testo tra formati di documenti simili."

      # more_overview_loop
      - title: "Formati supportati"
        content: "La libreria GroupDocs.Comparison supporta il rilevamento delle differenze sia nel contenuto che nello stile del testo tra i formati di immagini e documenti più diffusi come PDF, HTML, e-mail Outlook, documenti Microsoft Office Word, fogli di calcolo Excel, presentazioni PowerPoint, OneNote, diagrammi Visio, testi, immagini png, gif e bmp oltre a centinaia di altri formati."
        
      # more_overview_loop
      - title: "Capacità di confronto"
        content: "Il confronto può essere eseguito per rilevare i cambiamenti nel contenuto di parole, paragrafi, tabelle o grafici e i loro stili e ti fornirà un documento di confronto che elenca un riepilogo delle differenze, il loro numero e il tipo di appartenenza. GroupDocs.Comparison for Java può facilmente estrarre informazioni di base sul documento di origine, confrontare e salvare documenti semplici, protetti da password e crittografati di vari formati attraverso un file o un flusso di dati."
        
      # more_overview_loop
      - title: "Documentazione ed esempi"
        content: "C'è già molta documentazione sull'utilizzo della libreria Comparison su diverse piattaforme con esempi di codice, quindi non devi pensare a come lavorare con GroupDocs.Comparison per l'API Java nella tua applicazione."
        
      # more_overview_loop
      - title: "Compatibilità"
        content: "GroupDocs.Comparison per Java non richiede l'installazione di alcun software esterno nel sistema. È compatibile con tutte le versioni di Java e supporta i sistemi operativi più diffusi (Windows, Linux, MacOS) in grado di eseguire l'ambiente runtime Java."
    examples:
      enable: true
      more_feature:
      # more_feature_loop
      - title: "Confronta facilmente i documenti utilizzando l'API Java"
        content: |
          Attraverso GroupDocs.Comparison per Java API puoi facilmente confrontare documenti di formati supportati per trovare differenze tra loro. L'esempio seguente mostra come confrontare due documenti Microsoft Word utilizzando Java:
          
          ```java
          try (Comparer comparer = new Comparer("D:\\source.pdf")) {
              comparer.add("D:\\target.pdf");
              comparer.compare("D:\\result.pdf");
          }
          ```
      # more_feature_loop
      - title: "Specifica il livello di dettaglio del confronto"
        content: "GroupDocs.Comparison per Java ti consente di confrontare i documenti a tre livelli di profondità. Puoi impostare l'intensità del confronto su bassa (confronta il testo parola per parola con precisione per la griglia di imaging = 50), media (confronta il testo carattere per carattere con precisione per la griglia dell'immagine = 100) o alta (confrontare il testo carattere per carattere con precisione per la griglia dell'immagine = 150)."

      # more_feature_loop
      - title: "Confronta lo stile del testo"
        content: "Insieme al contenuto del documento, GroupDocs.Comparison per l'API Java consente di confrontare anche lo stile del testo.

        È inoltre possibile confrontare il nome del carattere, la dimensione, il colore, lo stile (grassetto, corsivo, sottolineato, maiuscoletto e collegamenti ipertestuali) e, se applicabile, sotto il colore per verificare la differenza tra i documenti confrontati, mentre le parole e i caratteri vengono confrontati.

        Per il confronto dei paragrafi, è possibile confrontare anche l'allineamento, il rientro (rientro sinistro, rientro destro), la spaziatura (spazio dopo, spazio prima), il rientro prima riga e l'interlinea.

        Allo stesso modo, ove applicabile, è possibile confrontare anche altre sezioni di una pagina tramite GroupDocs.Comparison per l'API Java. Le sezioni includono la distanza del piè di pagina, i margini della pagina (sinistro, destro, superiore e inferiore), l'altezza della pagina, l'orientamento della pagina, il colore del bordo e lo spessore della linea."
      
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Di seguito è riportata una panoramica di GroupDocs.Comparison per Java:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Panoramica"
          content: |
            * Confronta contenuti e stili
            * Ottieni un riepilogo del confronto
            * Accetta/rifiuta modifiche in Word
            * Unisci e confronta 3 file di Word
            * Supporto per i flussi
            * Rilevamento del tipo di file tramite flusso
            * Confronta i file protetti
            * Confronta i file crittografati
            * Salva confronto come immagine
            * Confronta una pagina specifica in Word
            * Confronta filigrana in PDF
            * Applica/Scarta le modifiche
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison per Java supporta tutti i più diffusi [formati di file di documenti](https://docs.groupdocs.com/comparison/java/supported-document-formats/) tra cui: Microsoft Office, immagini, diagrammi e molti altri .
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
            - title: "Altri Formati"
              content: |
                * **Linguaggi di programmazione**: [CS](https://products.groupdocs.com/comparison/java/cs/), [Java](https://products.groupdocs.com/comparison/java/java/), [CPP](https://products.groupdocs.com/comparison/java/cpp/), [JS](https://products.groupdocs.com/comparison/java/js/), [PY](https://products.groupdocs.com/comparison/java/py/), [RB](https://products.groupdocs.com/comparison/java/rb/), [PL](https://products.groupdocs.com/comparison/java/pl/), [ASM](https://products.groupdocs.com/comparison/java/asm/), [GROOVY](https://products.groupdocs.com/comparison/java/groovy/), [JSON](https://products.groupdocs.com/comparison/java/json/), [PHP](https://products.groupdocs.com/comparison/java/php/), [SQL](https://products.groupdocs.com/comparison/java/sql/), [LOG](https://products.groupdocs.com/comparison/java/log/), [DIFF](https://products.groupdocs.com/comparison/java/diff/), [LESS](https://products.groupdocs.com/comparison/java/less/), [SCALA](https://products.groupdocs.com/comparison/java/scala/)
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
          GroupDocs.Comparison per Java supporta i seguenti sistemi operativi, framework e gestori di pacchetti:
      
        left:
          enable: true
          table:
            # ciclo di tabella
            - icon: "fab fa-windows"
              title: "Sistemi operativi"
              content: |
                * Microsoft Windows Desktop
                * Microsoft Windows Server
                * Linux
                * MacOS

            # ciclo di tabella
            - icon: "fas fa-code"
              title: "Framework supportati"
              content: |
                * Java 7 (1.7) e versioni successive

        right:
          enable: true
          table:
            # ciclo di tabella
            - icon: "fas fa-cogs"
              title: "Ambienti di sviluppo"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse
            # ciclo di tabella
            - icon: "fas fa-tools"
              title: "Crea strumento di automazione"
              content: |
                * Maven

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Comparison per le funzionalità Java"

    feature:
      # ciclo di funzionalità
      - icon: "fas fa-copy"
        content: "[Confronta e identifica le modifiche sia nel contenuto che nello stile del testo](https://docs.groupdocs.com/comparison/java/compare-documents/)"

      # ciclo di funzionalità
      - icon: "fas fa-eye"
        content: "[Salva elenco di confronto riepilogativo sui documenti confrontati](https://docs.groupdocs.com/comparison/java/get-extended-information-on-the-summary-page/)"

      # ciclo di funzionalità
      - icon: "fas fa-bolt"
        content: "[Confronta pagine specifiche di documenti Word](https://docs.groupdocs.com/comparison/java/accept-or-reject-detected-changes/)"
      
      # ciclo di funzionalità
      - icon: "fas fa-file-powerpoint"
        content: "[Unisci fino a 3 file Microsoft Word da confrontare con il supporto per \"Revisioni\"](https://docs.groupdocs.com/comparison/java/compare-multiple-documents-with-specific-compare-settings/)"

      # ciclo di funzionalità
      - icon: "fas fa-code"
        content: "[Individua facilmente quali modifiche provengono da quale documento durante il confronto](https://docs.groupdocs.com/comparison/java/get-list-of-changes/)"

      # ciclo di funzionalità
      - icon: "fas fa-cloud"
        content: "[Supporto per la lettura dei documenti di origine e l'invio del documento risultante tramite flussi](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # ciclo di funzionalità
      - icon: "fas fa-remove-format"
        content: "[Rileva il tipo di formato del file durante il recupero dallo stream](https://docs.groupdocs.com/comparison/java/get-file-info/)"

      # ciclo di funzionalità
      - icon: "fas fa-comment-slash"
        content: "[Confronta documenti protetti da password](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/)"

      # ciclo di funzionalità
      - icon: "fas fa-location-arrow"
        content: "[Salva il risultato del confronto come immagine](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"

      # ciclo di funzionalità
      - icon: "fas fa-border-all"
        content: "[Confronta diversi formati di file come immagine](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"

      # ciclo di funzionalità
      - icon: "fas fa-wrench"
        content: "[Confronta le filigrane nei documenti PDF](https://docs.groupdocs.com/comparison/java/how-to-spot-photos-differences-in-java-or-kotlin/)"

      # ciclo di funzionalità
      - icon: "fas fa-columns"
        content: "[Confronta i documenti da file o stream e invia il documento dei risultati tramite stream o file](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # ciclo di funzionalità
      - icon: "fas fa-file-word"
        content: "[Accetta o annulla modifiche dopo il confronto di file Word, PDF o Excel](https://docs.groupdocs.com/comparison/java/accept-or-reject-detected-changes/)"

      # ciclo di funzionalità
      - icon: "fas fa-envelope"
        content: "[Confronta i documenti crittografati tramite file o flusso](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # ciclo di funzionalità
      - icon: "fas fa-print"
        content: "[Opzione di licenza misurata per operazioni di confronto](https://docs.groupdocs.com/comparison/java/evaluation-limitations-and-licensing-of-groupdocs-comparison/)"

      # ciclo di funzionalità
      - icon: "fas fa-file-archive"
        content: "[Evidenzia il testo per le modifiche contrassegnate durante il confronto di documenti PDF, Word, Excel, PowerPoint e note](https://docs.groupdocs.com/comparison/java/customize-changes-styles/)"

      # ciclo di funzionalità
      - icon: "fas fa-lock"
        content: "[Calcola le coordinate corrette delle modifiche in PDF, diapositive PowerPoint e diagrammi](https://docs.groupdocs.com/comparison/java/get-changes-coordinates/)"

      # ciclo di funzionalità
      - icon: "fas fa-file-code"
        content: "[Confronta più (più di due) PDF, Excel, OneNote, diagrammi, e-mail e documenti di testo](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/)"
      
      # ciclo di funzionalità
      - icon: "fas fa-fill-drip"
        content: "[Confronta intestazione e piè di pagina dei formati di file supportati](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # ciclo di funzionalità
      - icon: "fas fa-file-excel"
        content: "[Confronta documenti e salva pagine di documenti di diversi formati come immagini](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison offre API per la visualizzazione di documenti per altri ambienti di sviluppo popolari"

    solution:
        # ciclo di soluzione
        - img_alt: "GroupDocs.Comparison per .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
          product: "GroupDocs.Comparison"
          platform: ".NET"
          link: "/comparison/net/"

############################# Back to top ###############################
back_to_top:
  enable: true
---