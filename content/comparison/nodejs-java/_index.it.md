
---
############################# Static ############################
layout: "landing"
date: 2024-12-19T07:50:01
draft: false

lang: it
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
    # supported_platforms loop
    - title: "Python"
      tag: "python-net"

############################# Head ############################
head_title: "Node.js API di confronto dei documenti | diff checker"
head_description: "L'API Node.js Document Comparison offre strumenti efficienti per il confronto dei documenti. Si integra perfettamente con Node.js per il monitoraggio delle modifiche in tempo reale"

############################# Header ############################
title: "Confronta i documenti con Node.js: evidenzia eventuali differenze"
description: "Usa l'API GroupDocs.Comparison per sviluppare applicazioni native di script Java con funzionalità di confronto altamente configurabili. Confronta i file, il loro contenuto e lo stile del testo tra formati di documento simili."
words:
  for: "per"

actions:
  main: "Download gratuito di NPM"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.comparison"
  alt: "Licenze"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/nodejs-java/"
  title: "Pronto per iniziare?"
  description: "Prova le funzioni GroupDocs.Comparison gratuitamente o richiedi una licenza"

release:
  title: "Rilasciata la versione {0}"
  notes: "Scopri cosa c'è di nuovo"
  downloads: "Download"

code:
  title: "Confronta BMP immagini in Java Script"
  more: "Altri esempi"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.comparison"
  content: |
    ```javascript {style=abap}

    // Specifica il documento di origine
    const comparer = new Comparer("source.bmp");

    // Aggiungere uno o più documenti di destinazione
    comparer.add("target.bmp");

    // Specifica le opzioni di confronto
    const options = new groupdocs.comparison.CompareOptions();
    options.setGenerateSummaryPage(false);

    // Confronta e salva risultato
    await comparer.compare("result.bmp", options);
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison a colpo d'occhio"
  description: "API per confrontare vari tipi di documenti come PDF, Microsoft Office, HTML, e-mail o immagini all'interno di Node.js applicazioni"
  features:
    # feature loop
    - title: "Rapporti di output dettagliati"
      content: "GroupDocs.Comparison identifica le modifiche nel contenuto del documento (caratteri, parole, paragrafi, tabelle, grafici), nonché le modifiche nello stile del documento. Fornisce ai clienti un report risultante che contiene informazioni dettagliate sulle differenze, sul loro numero e tipo."

    # feature loop
    - title: "Sono supportati i formati di file e documenti più diffusi"
      content: "Con l'API GroupDocs.Comparison puoi confrontare in modo efficiente documenti di qualsiasi formato supportato come PDF, HTML, e-mail, documenti Microsoft Office Word, fogli di calcolo Excel, PowerPoint presentazioni, OneNote, Visio diagrammi, testi, JPEG, PNG, PNG, GIF e BMP immagini e molti altri formati."

    # feature loop
    - title: "Documentazione ed esempi"
      content: "C'è già molta documentazione sull'uso della libreria Comparison su diverse piattaforme con esempi di codice, quindi non devi pensare a come lavorare con l'API GroupDocs.Comparison nella tua applicazione Node.js."

    # feature loop
    - title: "Seleziona le modifiche e uniscile in un unico file"
      content: "Se hai diverse versioni di un documento, è possibile selezionare solo le modifiche desiderate e compilare un nuovo documento utilizzando la libreria GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Indipendenza dalla piattaforma"
  description: "GroupDocs.Comparison for Node.js via Java supporta i seguenti sistemi operativi, framework e gestori di pacchetti"
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
  title: "Formati di file supportati"
  description: |
    GroupDocs.Comparison for Node.js via Java supporta le operazioni con i seguenti [formati di file](https://docs.groupdocs.com/comparison/nodejs-java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Formati Microsoft Office e OpenDocument
        * **Word:** DOCX, DOC, DOCM,DOT, DOTM, DOTX, RTX, RTF, TXT
        * **Excel:** XLSX, XLS, XLT, XLTM, XLSB, XLSM
        * **PowerPoint:** PPTX, PPT, POT, POTX, PPS, PPSX
        * **Outlook:** EML, EMLX, MSG
        * **OneNote:** ONE
        * **OpenDocument:** ODT, ODP, OTP, ODS, OTT
        * **Layout di pagina fisso:** PDF        
    # group loop
    - color: "blue"
      content: |
        ### Immagini, grafici e diagrammi
        * **Immagini raster:** BMP, GIF, JPG, JPEG, PNG
        * **Imaging medico:** DICOM
        * **Microsoft Visio:** VSDX, VSD, VSS, VST, VDX
        * **AutoCAD Drawing:** DWG, DXF
      # group loop
    - color: "red"
      content: |
        ### Altro
        * **Testo:** TXT
        * **Linguaggi di programmazione:** CS, Java, CPP, JS, PY, RB, PL, ASM, GROOVY, JSON, PHP, SQL, LOG, DIFF, LESS, SCALA
        * **Web:** HTM, HTML, MHT, MHTML
        * **E-book:** MOBI, DjVu
        * **Valori separati da delimitatori:** CSV

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Comparison for Node.js via Java caratteristiche"
  description: "Confronta facilmente documenti, immagini e altri formati PDF con quelli di Office"

  items:
    # feature loop
    - icon: "compare"
      title: "Comparazione di documenti facile da usare"
      content: "Analizza e identifica le differenze all'interno di due documenti."

    # feature loop
    - icon: "note-stack"
      title: "Confronta più documenti"
      content: "Analizza e identifica le differenze all'interno di più documenti contemporaneamente."

    # feature loop
    - icon: "stacks"
      title: "Formati supportati"
      content: "Supporta più di 50 formati di documenti popolari di varie categorie."

    # feature loop
    - icon: "rule"
      title: "Accetta o rifiuta le modifiche"
      content: "Rappresentazione visiva chiara delle modifiche identificate, con la possibilità di accettare o rifiutare le modifiche."

    # feature loop
    - icon: "preview"
      title: "Genera anteprime"
      content: "Salva i risultati del confronto come immagini."

    # feature loop
    - icon: "two-pager"
      title: "Confronto dei contenuti"
      content: "Confronta il contenuto del testo riga per riga, per paragrafi, per parole, per caratteri. Evidenzia le modifiche."

    # feature loop
    - icon: "format_color_text"
      title: "Confronto di stili"
      content: "Rileva le modifiche nella formattazione e negli stili."

    # feature loop
    - icon: "folder-managed"
      title: "Imposta i metadati"
      content: "Conserva i metadati dai file di origine o di destinazione o consenti che vengano specificati dagli utenti."

    # feature loop
    - icon: "lock"
      title: "Protezione tramite password"
      content: "Analizza i documenti crittografati o proteggi il documento risultante con una password."

    # feature loop
    - icon: "select"
      title: "Confronta pagine specifiche"
      content: "Carica solo le sezioni o le pagine particolari del documento."

    # feature loop
    - icon: "speaker-notes"
      title: "Visualizza commenti"
      content: "Quando carichi il documento sorgente puoi scegliere se nascondere o mostrare i commenti."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Esempi di codice"
  description: "Alcuni casi d'uso delle operazioni tipiche di GroupDocs.Comparison for Node.js via Java"
  items:
    # code sample loop
    - title: "Confronto tra documenti protetti da password."
      content: |
        Per confrontare i documenti che sono [protetti da password](https://docs.groupdocs.com/comparison/nodejs-java/load-password-protected-documents/), devi specificarlo e caricare i documenti:
        {{< landing/code title="Come confrontare i documenti protetti da password.">}}
        ```javascript {style=abap}

        import { Comparer, LoadOptions } from '@groupdocs/groupdocs.comparison'

        // Carica il documento sorgente e specifica la sua password
        const comparer = new Comparer("source.docx", new LoadOptions("1234"));

        // Carica il documento di destinazione e specificane la password
        comparer.add("target.docx", new LoadOptions("5678"));

        // Salva il risultato del confronto in un file specificato
        comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Confronto di più documenti PDF."
      content: |
        GroupDocs.Comparison consente di [confrontare più di due documenti](https://docs.groupdocs.com/comparison/nodejs-java/compare-multiple-documents/). L'operazione è quasi la stessa di quando si confrontano due file. Devi solo aggiungere altri file di destinazione alla classe `comparer`.
        {{< landing/code title="Come confrontare tre o più documenti.">}}
        ```javascript {style=abap}
        import { Comparer } from '@groupdocs/groupdocs.comparison'

        // Carica il documento sorgente
        const comparer = new Comparer(source.pdf");

        // Specifica il secondo file per il confronto
        comparer.add("target2.pdf");

        // Specifica il terzo file per il confronto
        comparer.add("target3.pdf");

        // Salva il risultato del confronto in un file specificato
        comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---