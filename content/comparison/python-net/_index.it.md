
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: it
product: "Comparison"
product_tag: "comparison"
platform: "Python via .NET"
platform_tag: "python-net"

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
head_title: "Python API di confronto documenti | controllo del differenziale"
head_description: "L'API di confronto dei documenti Python offre strumenti efficienti per confrontare i documenti. Si integra perfettamente con Python per il monitoraggio immediato delle modifiche"

############################# Header ############################
title: "Confronta i documenti con Python: evidenzia eventuali differenze"
description: "Utilizza l'API GroupDocs.Comparison per sviluppare applicazioni Python native con funzionalità di confronto altamente configurabili. Confronta file, contenuto e stili di testo tra formati di documento simili."
words:
  for: "per"

actions:
  main: "Download gratuito di PyPi"
  main_link: "https://pypi.org/project/groupdocs-comparison-net/"
  alt: "Licenze"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/python-net/"
  title: "Pronto per iniziare?"
  description: "Prova le funzioni GroupDocs.Comparison gratuitamente o richiedi una licenza"

release:
  title: "Rilasciata la versione {0}"
  notes: "Scopri cosa c'è di nuovo"
  downloads: "Download"

code:
  title: "Confronta le immagini BMP in Python"
  more: "Altri esempi"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET/"
  install: "pip install groupdocs-comparison-net"
  content: |
    ```python {style=abap}
    def run():

        # Specifica il documento di origine
        with groupdocs.comparison.Comparer("in.bmp") as comparer:

            # Aggiungere uno o più documenti di destinazione
            comparer.add("target.bmp")

            # Specifica le opzioni di confronto
            options = new groupdocs.comparison.CompareOptions()
            options.setGenerateSummaryPage(false)

            # Confronta e salva risultato
            comparer.compare("result.bmp", options)
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison a colpo d'occhio"
  description: "Un'API per confrontare i tipi di documenti più diffusi come PDF, Microsoft Office, HTML, email o immagini all'interno delle applicazioni Python."
  features:
    # feature loop
    - title: "Rapporti di output dettagliati"
      content: "GroupDocs.Comparison identifica i cambiamenti nel contenuto del documento (caratteri, parole, paragrafi, tabelle, grafici) nonché i cambiamenti nello stile del documento. Fornisce agli utenti un rapporto contenente informazioni dettagliate sulle differenze, incluso il loro numero e tipo."

    # feature loop
    - title: "Supporta i formati di file e documenti più diffusi"
      content: "Con l'API GroupDocs.Comparison puoi confrontare in modo efficiente documenti in formati come PDF, HTML, e-mail, Microsoft Office Word, fogli di calcolo Excel, presentazioni PowerPoint, OneNote, diagrammi Visio, file di testo, JPEG, PNG, GIF, immagini BMP, e molti altri formati."

    # feature loop
    - title: "Documentazione completa ed esempi"
      content: "Sono disponibili un'ampia documentazione ed esempi di codice per l'utilizzo della libreria di confronto su diverse piattaforme, semplificando l'integrazione dell'API GroupDocs.Comparison nella tua applicazione Python."

    # feature loop
    - title: "Seleziona e unisci le modifiche in un unico file"
      content: "Se disponi di versioni diverse di un documento, puoi selezionare modifiche specifiche e compilare un nuovo documento utilizzando la libreria GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Indipendenza dalla piattaforma"
  description: "GroupDocs.Comparison for Python via .NET supporta i seguenti sistemi operativi, framework e gestori di pacchetti"
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
    GroupDocs.Comparison for Python via .NET supporta operazioni con i seguenti [formati di file](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
  title: "Funzionalità di GroupDocs.Comparison for Python via .NET"
  description: "Confronta facilmente documenti PDF e Office, immagini e altri formati."

  items:
    # feature loop
    - icon: "compare"
      title: "Confronto di documenti intuitivo"
      content: "Analizzare e identificare le differenze tra due documenti."

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
      content: "Chiara rappresentazione visiva delle modifiche identificate, con la possibilità di accettare o rifiutare le modifiche."

    # feature loop
    - icon: "preview"
      title: "Genera anteprime"
      content: "Salva i risultati del confronto come immagini."

    # feature loop
    - icon: "two-pager"
      title: "Confronto dei contenuti"
      content: "Confronta il contenuto del testo riga per riga, per paragrafi, per parole o per caratteri. Evidenzia le modifiche."

    # feature loop
    - icon: "format_color_text"
      title: "Confronto di stili"
      content: "Rileva modifiche nella formattazione e negli stili."

    # feature loop
    - icon: "folder-managed"
      title: "Imposta metadati"
      content: "Conserva i metadati dei file di origine o di destinazione oppure consenti che vengano specificati dagli utenti."

    # feature loop
    - icon: "lock"
      title: "Protezione della password"
      content: "Analizza documenti crittografati o proteggi il documento risultante con una password."

    # feature loop
    - icon: "select"
      title: "Confronta pagine specifiche"
      content: "Carica e confronta sezioni o pagine specifiche di un documento."

    # feature loop
    - icon: "speaker-notes"
      title: "Visualizza commenti"
      content: "Scegli di nascondere o mostrare i commenti durante il caricamento del documento di origine."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Esempi di codice"
  description: "Esplora i casi d'uso tipici delle operazioni di GroupDocs.Comparison for Python via .NET"
  items:
    # code sample loop
    - title: "Confronto di documenti protetti da password"
      content: |
        Per confrontare i documenti [protetti con password](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/), è necessario specificare la password durante il caricamento dei documenti:
        {{< landing/code title="Come confrontare i documenti protetti da password.">}}
        ```python {style=abap}
        def run():

            # Carica il documento sorgente e specifica la sua password
            with groupdocs.comparison.Comparer("source.docx", new LoadOptions("1234")) as comparer:

                # Carica il documento di destinazione e specificane la password
                comparer.add("target.docx", new LoadOptions("5678"));

                # Salva il risultato del confronto in un file specificato
                comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Confronto di più documenti PDF."
      content: |
        GroupDocs.Comparison consente di [confrontare più di due documenti](https://docs.groupdocs.com/comparison/python-net/compare-multiple-documents/). L'operazione è quasi la stessa di quando si confrontano due file. Devi solo aggiungere altri file di destinazione alla classe `comparer`.
        {{< landing/code title="Come confrontare tre o più documenti.">}}
        ```python {style=abap}
        def run():

            # Carica il documento sorgente
            with groupdocs.comparison.Comparer(source.pdf") as comparer:

                # Specifica il secondo file per il confronto
                comparer.add("target2.pdf");

                # Specifica il terzo file per il confronto
                comparer.add("target3.pdf");

                # Salva il risultato del confronto in un file specificato
                comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---