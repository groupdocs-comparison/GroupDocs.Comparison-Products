
---
############################# Static ############################
layout: "format"
date:  2024-12-19T07:49:45
draft: false
lang: it
format: Jpg
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "Analizza JPG immagini con GroupDocs.Comparison for Java."
head_description: "L'API GroupDocs.Comparison for Java genera report utili per JPG immagini. Supporta Java, J2EE e J2SE."

############################# Header ############################
title: "Analizza le modifiche nei file JPG tramite la nostra soluzione Java" 
description: "Le app Java, J2EE o J2SE che utilizzano l'API GroupDocs.Comparison sono in grado di generare report JPG dettagliati."
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
    title: "Esplora l'API GroupDocs.Comparison for Java"
    link: "/comparison/java/"
    link_title: "Scopri di più"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       La soluzione nativa Java, GroupDocs.Comparison, crea report dettagliati sulle JPG modifiche. Supporta i formati di immagine più diffusi per il confronto e l'ulteriore elaborazione.

############################# Steps ############################
steps:
    enable: true
    title: "Confronta i file JPG usando Java"
    content: |
      Recupera i dati sulle JPG differenze con [GroupDocs.Comparison](https://products.groupdocs.com/comparison/java/)
      
      1. Migliora la funzionalità del tuo prodotto aggiungendo GroupDocs.Comparison for Java da [Maven](https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/)
      2. Crea un'istanza di Comparer con il percorso JPG
      3. Aggiungi altre JPG immagini all'elaborazione
      4. Ottieni il rapporto risultante
   
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
        try (Comparer comparer = new Comparer("main.jpg") 
        {
            // Includi file aggiuntivi da confrontare
        	comparer.add("version1.jpg");
            comparer.add("version2.jpg");
            comparer.add("version3.jpg");

            // Ottieni il rapporto con il nome specificato come risultato
            final Path resultPath = comparer.compare("full_report.jpg"); 

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
    title: "Tieni traccia di eventuali modifiche nelle diverse versioni di JPG immagini utilizzando Java"
    exclude: "JPG"
    description: "Rileva le alterazioni nelle JPG immagini con GroupDocs.Comparison for Java. Migliora i processi aziendali con report dettagliati."
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