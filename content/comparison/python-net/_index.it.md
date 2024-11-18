
---
############################# Static ############################
layout: "landing"
date: 2024-11-18T09:49:37
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
head_title: "Python Strumento di confronto documenti | Analisi dei documenti"
head_description: "Scopri la potenza dello strumento di confronto dei documenti Python per un'analisi approfondita dei documenti. Si integra facilmente con Python per il monitoraggio completo delle modifiche."

############################# Header ############################
title: "Confronta i documenti con Python: evidenzia eventuali differenze"
description: "Utilizza l'API GroupDocs.Comparison per creare applicazioni native in Python con funzionalità di confronto personalizzabili. Esamina i file, il loro contenuto e le variazioni di stile nei diversi formati di documento."
words:
  for: "per"

actions:
  main: "Ottieni subito il download gratuito di PyPi"
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
  title: "Confronta le immagini BMP utilizzando Python"
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
  description: "Un'API progettata per confrontare tipi di documenti ampiamente utilizzati come PDF, file di Microsoft Office, HTML, email o immagini all'interno delle applicazioni Python."
  features:
    # feature loop
    - title: "Rapporti di output completi"
      content: "GroupDocs.Comparison rileva le alterazioni nel contenuto del documento (caratteri, parole, paragrafi, tabelle, grafici) nonché le modifiche allo stile del documento. Gli utenti ricevono un rapporto dettagliato che evidenzia la natura e il numero delle modifiche."

    # feature loop
    - title: "Ampia gamma di formati di file e documenti"
      content: "L'API GroupDocs.Comparison ti consente di confrontare documenti in formati come PDF, HTML, e-mail, Microsoft Office Word, cartelle di lavoro Excel, file PowerPoint, note OneNote, diagrammi Visio, documenti di testo, JPEG, PNG, GIF, immagini BMP, tra molti altri."

    # feature loop
    - title: "Documentazione approfondita ed esempi di codice"
      content: "Sono subito disponibili documentazione approfondita e codici di esempio per la libreria Comparison su varie piattaforme, semplificando l'integrazione dell'API GroupDocs.Comparison nelle tue applicazioni Python."

    # feature loop
    - title: "Seleziona e combina le modifiche in un unico documento"
      content: "Se possiedi varie versioni di un documento, puoi compilare selettivamente le modifiche in un unico nuovo file utilizzando la libreria GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Indipendenza dalla piattaforma"
  description: "GroupDocs.Comparison for Python via .NET è compatibile con i seguenti sistemi operativi, framework e gestori di pacchetti."
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
    GroupDocs.Comparison for Python via .NET può funzionare con i seguenti [formati di file](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
  description: "Confronta facilmente PDF, documenti Office, immagini e un'ampia varietà di altri formati."

  items:
    # feature loop
    - icon: "compare"
      title: "Confronto intuitivo dei documenti"
      content: "Esaminare ed evidenziare le differenze tra due documenti."

    # feature loop
    - icon: "note-stack"
      title: "Confronto di più documenti"
      content: "Ispeziona più documenti per individuare eventuali differenze contemporaneamente."

    # feature loop
    - icon: "stacks"
      title: "Ampio supporto dei formati"
      content: "Compatibile con oltre 50 formati di documenti comunemente utilizzati in varie categorie."

    # feature loop
    - icon: "rule"
      title: "Accetta o rifiuta le modifiche"
      content: "Visualizza le modifiche con chiarezza, offrendo opzioni per l'accettazione o il rifiuto delle modifiche."

    # feature loop
    - icon: "preview"
      title: "Genera anteprime visive"
      content: "Crea anteprime dei risultati del confronto in formati immagine."

    # feature loop
    - icon: "two-pager"
      title: "Confronto dei contenuti basato su testo"
      content: "Esegui confronti riga per riga, paragrafo, parola o carattere per evidenziare le modifiche."

    # feature loop
    - icon: "format_color_text"
      title: "Rilevamento delle modifiche di formattazione"
      content: "Identificare le alterazioni negli stili e nella formattazione dei documenti."

    # feature loop
    - icon: "folder-managed"
      title: "Gestione dei metadati personalizzabile"
      content: "Conserva i metadati dai file di origine o di destinazione oppure consenti agli utenti di definire nuovi metadati."

    # feature loop
    - icon: "lock"
      title: "Gestire file protetti da password"
      content: "Lavora con documenti crittografati o crea documenti protetti protetti da password."

    # feature loop
    - icon: "select"
      title: "Confronti di pagine mirate"
      content: "Seleziona e confronta sezioni particolari o singole pagine di un documento."

    # feature loop
    - icon: "speaker-notes"
      title: "Gestisci la visibilità dei commenti"
      content: "Decidere di rivelare o nascondere i commenti durante l'esame del documento originale."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Esempi di codice"
  description: "Scopri scenari comuni per l'utilizzo delle funzionalità di GroupDocs.Comparison for Python via .NET."
  items:
    # code sample loop
    - title: "Confronto di documenti con protezione tramite password"
      content: |
        Per confrontare i documenti [protetti con una password](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/), è necessario specificare la password durante il caricamento dei documenti:
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