
---
############################# Static ############################
layout: "format"
date:  2024-03-22T13:27:37
draft: false
lang: it
format: Mht
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "API di confronto Java MHT - Verifica la presenza di differenze tra i file MHT"
head_description: "Confronta e unisci i file MHT nelle applicazioni Java, J2EE, J2SE. Analizza il riepilogo delle differenze in termini di contenuto, testo e stile."

############################# Header ############################
title: "Confronta MHT file in Java" 
description: "Esegui il confronto dei contenuti tra più di due file MHT in Java. Recupera un elenco di differenze e salva i file confrontati in un unico documento."
subtitle: "Struttura di verifica delle differenze dei documenti" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Download gratuito di Maven"
      link: "https://releases.groupdocs.com/comparison/java/"
      
############################# About ############################
about:
    enable: true
    title: "Esplora le funzionalità della libreria GroupDocs.Comparison for Java"
    link: "/comparison/java/"
    link_title: "Scopri di più"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison for Java è un software intrinseco Java creato per confrontare più immagini e documenti che condividono lo stesso formato. Aiuta a identificare le variazioni all'interno di paragrafi, parole, caratteri, forme e persino stili di testo tra i documenti confrontati. Grazie alla capacità di unire queste modifiche ed esportarle in un documento finale, facilita il confronto e l'unione di PDF documenti, Word, Excel fogli di calcolo, PowerPoint presentazioni, Visio diagrammi, Outlook email, HTML, disegni e vari formati di file di immagine, eliminando la necessità di librerie esterne.

############################# Steps ############################
steps:
    enable: true
    title: "Come confrontare diversi documenti MHT utilizzando Java"
    content: |
      Usa [GroupDocs.Comparison](https://products.groupdocs.com/comparison/java/) per confrontare più file MHT e generare un rapporto che descriva in dettaglio le loro differenze
      
      1. Usa il tuo gestore di pacchetti preferito per installare GroupDocs.Comparison for Java da [Maven](https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/)
      2. Crea un'istanza della classe Comparer impostando il percorso di uno dei file MHT
      3. Aggiungi almeno un altro MHT all'istanza di Comparer
      4. Ricevi un rapporto finale dettagliato che illustra le differenze esatte
   
    code:
      platform: "net"
      copy_title: "Copia"
      install:
        command: |
          <dependencies>
            <dependency>
              <groupId>com.groupdocs</groupId>
              <artifactId>groupdocs-comparison</artifactId>
              <version>{0}</version>
            </dependency>
          </dependencies>

          <repositories>
            <repository>
              <id>repository.groupdocs.com</id>
              <name>GroupDocs Repository</name>
              <url>https://repository.groupdocs.com/repo/</url>
            </repository>
          </repositories>
        copy_tip: "clicca per copiare"
        copy_done: "copiato"
      links:
        #  loop
        - title: "Altri esempi"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
        #  loop
        - title: "Documentazione"
          link: "https://docs.groupdocs.com/comparison/java/"
          
      content: |
        ```java {style=abap}

        // Controlla i file dal tuo disco rigido per differenze o somiglianze

        // Crea un oggetto Comparer specificando il file iniziale
        try (Comparer comparer = new Comparer("source.mht") 
        {
            // Includi file aggiuntivi da confrontare
        	comparer.add("target1.mht");
            comparer.add("target2.mht");

            // Ottieni il rapporto con il nome specificato come risultato
            final Path resultPath = comparer.compare("result.mht"); 

            System.out.println("\nDocuments compared successfully.");
        }
        
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "Pronto per iniziare?"
  description: "Prova le funzioni GroupDocs.Comparison gratuitamente o richiedi una licenza"
  items:
    #  loop
    - title: "Maven scarica"
      link: "https://releases.groupdocs.com/comparison/java/"
      color: "red"
        #  loop
    - title: "Licenze"
      link: "https://purchase.groupdocs.com/pricing/comparison/java/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Confronta vari documenti usando Java"
    exclude: "MHT"
    description: "Le nostre soluzioni Java consentono di confrontare documenti di vari formati. Rimani aggiornato sulle modifiche ai documenti elaborandole senza sforzo."
    items: 
        # format loop 1
        - name: "Confronta PDF file"
          format: "PDF"
          link: "/comparison/java/pdf/"
          description: "Formato documento Adobe Portable"

        # format loop 2
        - name: "Confronta DOCX file"
          format: "DOCX"
          link: "/comparison/java/docx/"
          description: "Documento XML aperto Microsoft Word"

        # format loop 3
        - name: "Confronta RTF file"
          format: "RTF"
          link: "/comparison/java/rtf/"
          description: "Formato di file RTF"

        # format loop 4
        - name: "Confronta TXT file"
          format: "TXT"
          link: "/comparison/java/txt/"
          description: "Formato di file di testo normale"

        # format loop 5
        - name: "Confronta XLSX file"
          format: "XLSX"
          link: "/comparison/java/xlsx/"
          description: "Foglio di calcolo Microsoft Excel Open XML"

        # format loop 6
        - name: "Confronta i file CSV"
          format: "CSV"
          link: "/comparison/java/csv/"
          description: "File con valori separati da virgole"

        # format loop 7
        - name: "Confronta PPTX file"
          format: "PPTX"
          link: "/comparison/java/pptx/"
          description: "PowerPoint Presentazione XML aperta"

        # format loop 8
        - name: "Confronta ODS file"
          format: "ODS"
          link: "/comparison/java/ods/"
          description: "Open Document Foglio di calcolo"

        # format loop 9
        - name: "Confronta i file ODP"
          format: "ODP"
          link: "/comparison/java/odp/"
          description: "OpenDocument Formato del file di presentazione"

        # format loop 10
        - name: "Confronta ODT file"
          format: "ODT"
          link: "/comparison/java/odt/"
          description: "Open Document Testo"

        # format loop 11
        - name: "Confronta JPEG file"
          format: "JPEG"
          link: "/comparison/java/jpeg/"
          description: "JPEG Immagine"

        # format loop 12
        - name: "Confronta PNG file"
          format: "PNG"
          link: "/comparison/java/png/"
          description: "Portable Grafica di rete"

        # format loop 13
        - name: "Confronta GIF file"
          format: "GIF"
          link: "/comparison/java/gif/"
          description: "File di formato di interscambio grafico"

        # format loop 14
        - name: "Confronta BMP file"
          format: "BMP"
          link: "/comparison/java/bmp/"
          description: "Formato di file bitmap"

        # format loop 15
        - name: "Confronta i file HTML"
          format: "HTML"
          link: "/comparison/java/html/"
          description: "Linguaggio di markup Hyper Text"

        # format loop 16
        - name: "Confronta MSG file"
          format: "MSG"
          link: "/comparison/java/msg/"
          description: "Messaggio di posta elettronica Microsoft Outlook"

        # format loop 17
        - name: "Confronta ONE file"
          format: "ONE"
          link: "/comparison/java/one/"
          description: "Microsoft OneNote"

        # format loop 18
        - name: "Confronta VSDX file"
          format: "VSDX"
          link: "/comparison/java/vsdx/"
          description: "Disegno Microsoft Visio"

        # format loop 19
        - name: "Confronta i file CS"
          format: "CS"
          link: "/comparison/java/cs/"
          description: "Linguaggio CSharp"

        # format loop 20
        - name: "Confronta Java file"
          format: "Java"
          link: "/comparison/java/java/"
          description: "Java Lingua"
          
        # format loop 21
        - name: "Confronta i file CPP"
          format: "CPP"
          link: "/comparison/java/cpp/"
          description: "Linguaggio C++"
---