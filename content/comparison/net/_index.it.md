
---
############################# Static ############################
layout: "landing"
date: 2024-03-21T15:26:29
draft: false

lang: it
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
head_title: "C# .NET Software per la comparazione dei documenti | diff checker"
head_description: "C# .NET Software per confrontare lo stile e il contenuto dei documenti. Confronta i documenti di diversi formati supportati per identificare le modifiche tra i file."

############################# Header ############################
title: "Confronta facilmente i documenti nelle tue soluzioni C# .NET"
description: "Crea applicazioni C# con un'API flessibile di confronto dei documenti che consente il confronto dei file per contenuto e stile in vari formati di documento."
words:
  for: "per"

actions:
  main: "Scarica NuGet gratis"
  main_link: "https://www.nuget.org/packages/GroupDocs.Comparison"
  alt: "Licenze"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/net/"
  title: "Pronto per iniziare?"
  description: "Prova le funzioni GroupDocs.Comparison gratuitamente o richiedi una licenza"

release:
  title: "Rilasciata la versione {0}"
  notes: "Scopri cosa c'è di nuovo"
  downloads: "Download"

code:
  title: "Confronta DOCX file in C#"
  more: "Altri esempi"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET"
  install: "dotnet add package GroupDocs.Comparison"
  content: |
    ```csharp {style=abap}   
    // Specifica il documento di origine
    using (Comparer comparer = new Comparer("source.docx"))
    {
        // Aggiungere uno o più documenti di destinazione
        comparer.Add("target.docx");

        // Specifica le opzioni di confronto
        CompareOptions options = new CompareOptions() 
        {ShowRevisions = false};

        // Esegui il confronto e salva il documento risultante
        comparer.Compare("result.docx", options);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison a colpo d'occhio"
  description: "API per confrontare le differenze tra i documenti nelle applicazioni .NET"
  features:
    # feature loop
    - title: "Confronto di file in C#"
      content: "Rileva le differenze tra i file di origine e di destinazione per le modifiche a livello di paragrafi, parole e caratteri. Identifica le modifiche di stile e formattazione come grassetto, corsivo, sottolineature, barrate, tipi di carattere, ecc."

    # feature loop
    - title: "Sono supportati i formati di file e documenti più diffusi"
      content: "L'API GroupDocs.Comparison consente un confronto efficiente dei documenti in un'ampia gamma di formati, tra cui PDF, HTML, email, Microsoft Office documenti (Word, Excel, PowerPoint, OneNote, Visio), vari tipi di immagini (JPEG, PNG, PNG, GIF, BMP), file di testo e altro ancora."

    # feature loop
    - title: "Applica o rifiuta facilmente le modifiche"
      content: "Ogni differenza identificata nei documenti confrontati utilizzando l'API GroupDocs.Comparison può essere applicata o rifiutata in modo selettivo, consentendo la personalizzazione prima dell'esportazione nel documento di output finale."

    # feature loop
    - title: "Rapporto di riepilogo comparativo"
      content: "Genera un rapporto riassuntivo delle differenze, che descriva in dettaglio tutte le modifiche rilevate nei documenti confrontati e salvalo come riferimento."

############################# Platforms ############################
platforms:
  enable: true
  title: "Indipendenza dalla piattaforma"
  description: "GroupDocs.Comparison for .NET supporta i seguenti sistemi operativi, framework e gestori di pacchetti"
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
  title: "Formati di file supportati"
  description: |
    GroupDocs.Comparison for .NET supporta le operazioni con i seguenti [formati di file](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
      content: "Analizza e identifica le differenze tra due documenti."

    # feature loop
    - icon: "note-stack"
      title: "Confronta più documenti"
      content: "Analizza e identifica simultaneamente le differenze tra più documenti."

    # feature loop
    - icon: "stacks"
      title: "Formati supportati"
      content: "Compatibile con oltre 50 formati di documenti ampiamente utilizzati di varie categorie, garantendo un'ampia applicabilità."

    # feature loop
    - icon: "rule"
      title: "Accetta o rifiuta le modifiche"
      content: "Visualizzazione visiva chiara delle modifiche rilevate, completa di opzioni per accettare o rifiutare tali modifiche."

    # feature loop
    - icon: "preview"
      title: "Genera anteprime"
      content: "Possibilità di salvare i risultati del confronto come anteprime delle immagini per una facile consultazione e condivisione."

    # feature loop
    - icon: "two-pager"
      title: "Confronto dei contenuti"
      content: "Effettua confronti testuali approfonditi a vari livelli, tra cui riga per riga, paragrafo, parola e carattere, evidenziando le differenze per una maggiore chiarezza."

    # feature loop
    - icon: "format_color_text"
      title: "Confronto di stili e formattazioni"
      content: "Rileva ed evidenzia le alterazioni nella formattazione e nello stile dei documenti, garantendo una revisione completa."

    # feature loop
    - icon: "folder-managed"
      title: "Impostazioni flessibili dei metadati"
      content: "Conserva i metadati dai file di origine o di destinazione o personalizzali in base alle preferenze dell'utente."

    # feature loop
    - icon: "lock"
      title: "Protezione tramite password"
      content: "Analizza i documenti protetti da password e proteggi il documento di output con la crittografia delle password per una maggiore sicurezza."

    # feature loop
    - icon: "select"
      title: "Confronto selettivo delle pagine"
      content: "Carica e confronta sezioni o pagine specifiche di un documento per un'analisi mirata."

    # feature loop
    - icon: "speaker-notes"
      title: "Visualizza commenti"
      content: "Scegli di visualizzare o nascondere i commenti durante il caricamento del documento di origine, offrendo un maggiore controllo sul processo di confronto."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Esempi di codice"
  description: "Alcuni casi d'uso delle operazioni tipiche di GroupDocs.Comparison for .NET"
  items:
    # code sample loop
    - title: "Confronto tra documenti protetti da password."
      content: |
        Per confrontare i documenti che sono [protetti da password](https://docs.groupdocs.com/comparison/net/load-password-protected-documents/), devi specificarlo e caricare i documenti:
        {{< landing/code title="Come confrontare i documenti protetti da password.">}}
        ```csharp {style=abap}
        // Carica il documento sorgente e specifica la sua password
        using(Comparer comparer = new Comparer("source.docx", new LoadOptions() {Password = "1234"}))  
        {
            // Carica il documento di destinazione e specificane la password
            comparer.Add("target.docx", new LoadOptions() {Password = "5678"});

            // Salva il risultato del confronto in un file specificato
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Confronto di più documenti PDF."
      content: |
        GroupDocs.Comparison consente di [confrontare più di due documenti](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/). L'operazione è quasi la stessa di quando si confrontano due file. Devi solo aggiungere altri file di destinazione alla classe `comparer`.
        {{< landing/code title="Come confrontare tre o più documenti.">}}
        ```csharp {style=abap}   
        // Carica il documento sorgente
        using(Comparer comparer = new Comparer("source.docx") 
        {
            // Specifica il secondo file per il confronto
            comparer.Add("target2.docx");
            
            // Specifica il terzo file per il confronto
            comparer.Add("target3.docx");
            
            // Salva il risultato del confronto in un file specificato
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---
