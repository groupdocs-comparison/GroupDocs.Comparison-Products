
---
############################# Static ############################
layout: "landing"
date: 2024-03-22T13:27:50
draft: false

lang: it
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

############################# Head ############################
head_title: "Java Libreria di confronto dei documenti| diff checker"
head_description: "Software nativo Java per confrontare lo stile e il contenuto dei documenti. Confronta documenti di diversi formati per identificare le differenze."

############################# Header ############################
title: "Confronta e verifica le differenze tra i file utilizzando l'API Java"
description: "Sviluppa Java applicazioni con una libreria di confronto documenti altamente configurabile per confrontare formati di documenti simili, inclusi i file, il loro contenuto e lo stile del testo."
words:
  for: "per"

actions:
  main: "Download gratuito di Maven"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/"
  alt: "Licenze"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/java/"
  title: "Pronto per iniziare?"
  description: "Prova le funzioni GroupDocs.Comparison gratuitamente o richiedi una licenza"

release:
  title: "Rilasciata la versione {0}"
  notes: "Scopri cosa c'è di nuovo"
  downloads: "Download"

code:
  title: "Confronta DOCX file in Java"
  more: "Altri esempi"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
  install: |
    <dependency>
      <groupId>com.groupdocs</groupId>
      <artifactId>groupdocs-comparison</artifactId>
      <version>{0}</version>
    </dependency>
  content: |
    ```java {style=abap}  
    // Specifica il documento di origine
    try (Comparer comparer = new Comparer("source.docx"))
    {    
      // Aggiungere uno o più documenti di destinazione
      comparer.add("target.docx");

      // Specifica le opzioni di confronto
      CompareOptions options = new CompareOptions();
      options.setShowRevisions(false);

      // Confronta e salva risultato
      final comparer.compare("result.docx", options);
    }    
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison a colpo d'occhio"
  description: "API per confrontare le differenze tra i documenti nelle applicazioni Java"
  features:
    # feature loop
    - title: "Confronto di file in Java"
      content: "Rileva le modifiche tra i file di origine e di destinazione a livello di paragrafo, parola e carattere. Identifica le modifiche di stile e formattazione come grassetto, corsivo, sottolineature, barrate, tipi di carattere e altro ancora."

    # feature loop
    - title: "Ampio numero di formati supportati"
      content: "Con l'API GroupDocs.Comparison, puoi confrontare facilmente documenti di diversi formati supportati. Ciò include PDF, HTML, email, documenti Microsoft Office Word, fogli di calcolo Excel, PowerPoint presentazioni, OneNote, Visio diagrammi, testi, JPEG, PNG, GIF e BMP immagini, oltre a molti altri formati."

    # feature loop
    - title: "Applica o rifiuta facilmente le modifiche"
      content: "Ogni differenza tra i documenti confrontati può essere applicata o rifiutata e quindi esportata nel documento di output."

    # feature loop
    - title: "Rapporto di riepilogo comparativo"
      content: "Genera un rapporto di riepilogo che elenca tutte le modifiche nei documenti confrontati."

############################# Platforms ############################
platforms:
  enable: true
  title: "Indipendenza dalla piattaforma"
  description: "GroupDocs.Comparison for Java supporta i seguenti sistemi operativi, framework e gestori di pacchetti"
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
  title: "Formati di file supportati"
  description: |
    GroupDocs.Comparison for Java supporta le operazioni con i seguenti [formati di file](https://docs.groupdocs.com/comparison/java/supported-document-formats/).
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
  title: "GroupDocs.Comparison caratteristiche"
  description: "Confronta facilmente documenti, immagini e altri formati PDF con quelli di Office"

  items:
    # feature loop
    - icon: "compare"
      title: "Comparazione di documenti facile da usare"
      content: "Analizza e individua facilmente le differenze tra due documenti."

    # feature loop
    - icon: "note-stack"
      title: "Confronta più documenti"
      content: "Esamina ed evidenzia simultaneamente le variazioni tra più documenti."

    # feature loop
    - icon: "stacks"
      title: "Formati supportati"
      content: "Compatibilità con oltre 50 formati di documenti ampiamente utilizzati appartenenti a diverse categorie."

    # feature loop
    - icon: "rule"
      title: "Accetta o rifiuta le modifiche"
      content: "Visualizzazione chiara delle modifiche identificate, con opzioni per accettare o rifiutare le modifiche."

    # feature loop
    - icon: "preview"
      title: "Genera anteprime"
      content: "Possibilità di salvare i risultati del confronto come anteprime delle immagini."

    # feature loop
    - icon: "two-pager"
      title: "Confronto dei contenuti"
      content: "Confronto approfondito dei contenuti testuali su vari livelli, inclusa l'analisi riga per riga, paragrafo, parola e carattere, con enfasi sulle modifiche."

    # feature loop
    - icon: "format_color_text"
      title: "Confronto di stili"
      content: "Capacità di rilevare ed evidenziare le alterazioni nella formattazione e negli elementi di stile."

    # feature loop
    - icon: "folder-managed"
      title: "Imposta i metadati"
      content: "Opzione per conservare i metadati dai file di origine o di destinazione o consentire le impostazioni dei metadati definite dall'utente."

    # feature loop
    - icon: "lock"
      title: "Protezione tramite password"
      content: "Facilita l'analisi dei documenti protetti da password e consente la protezione con password per i documenti risultanti."

    # feature loop
    - icon: "select"
      title: "Confronta pagine specifiche"
      content: "Carica e confronta sezioni o pagine specifiche di un documento come richiesto."

    # feature loop
    - icon: "speaker-notes"
      title: "Visualizza commenti"
      content: "Flessibilità per visualizzare o nascondere i commenti durante il caricamento del documento sorgente."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Esempi di codice"
  description: "Alcuni casi d'uso delle operazioni tipiche di GroupDocs.Comparison for Java"
  items:
    # code sample loop
    - title: "Confronto tra documenti protetti da password."
      content: |
        Per confrontare i documenti che sono [protetti da password](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/), devi specificarlo e caricare i documenti:
        {{< landing/code title="Come confrontare i documenti protetti da password.">}}
        ```java {style=abap}
        // Carica il documento sorgente e specifica la sua password
        try (Comparer comparer = new Comparer("source.docx", new LoadOptions("1234")))
        {
            // Carica il documento di destinazione e specificane la password
            comparer.add("target.docx", new LoadOptions("5678"));
        
            // Salva il risultato del confronto in un file specificato
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Confronto di più documenti PDF."
      content: |
        GroupDocs.Comparison consente di [confrontare più di due documenti](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/). L'operazione è quasi la stessa di quando si confrontano due file. Devi solo aggiungere altri file di destinazione alla classe `comparer`.
        {{< landing/code title="Come confrontare tre o più documenti.">}}
        ```java {style=abap}   
        // Carica il documento sorgente
        try (Comparer comparer = new Comparer("source.docx") 
        {
            // Specifica il secondo file per il confronto
            comparer.add("target2.docx");

            // Specifica il terzo file per il confronto
            comparer.add("target3.docx");

            // Salva il risultato del confronto in un file specificato
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---

