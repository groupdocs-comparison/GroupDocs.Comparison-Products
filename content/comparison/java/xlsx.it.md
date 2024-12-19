
---
############################# Static ############################
layout: "format"
date:  2024-12-19T07:49:45
draft: false
lang: it
format: Xlsx
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "GroupDocs.Comparison for Java per il confronto XLSX."
head_description: "L'API GroupDocs.Comparison offre il recupero di report che descrivono in dettaglio le varianze nei documenti XLSX. Compatibile con gli ambienti Java, J2EE e J2SE."

############################# Header ############################
title: "Java applicazioni per il rilevamento delle modifiche nei XLSX fogli di calcolo" 
description: "L'API GroupDocs.Comparison Java consente il confronto di XLSX fogli di calcolo all'interno di applicazioni Java, J2EE o J2SE."
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
    title: "Esplora i vantaggi dell'API GroupDocs.Comparison for Java"
    link: "/comparison/java/"
    link_title: "Scopri di più"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       L'API GroupDocs.Comparison for Java semplifica il confronto dei fogli di calcolo XLSX, generando report sulle differenze riscontrate nel testo, nei paragrafi, nelle forme, negli stili e in altri elementi. Inoltre, supporta l'unione di modifiche da più file originali senza richiedere librerie esterne. Migliora i tuoi Java progetti con un'integrazione minima del codice.

############################# Steps ############################
steps:
    enable: true
    title: "Usa Java per confrontare più file XLSX"
    content: |
      Usa [GroupDocs.Comparison](https://products.groupdocs.com/comparison/java/) per analizzare MS Excel fogli di calcolo
      
      1. Installa il pacchetto da [Maven](https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/)
      2. Crea un'istanza del Comparer con il primo foglio di calcolo XLSX come parametro
      3. Includi XLSX fogli di calcolo aggiuntivi per il confronto
      4. Goditi un rapporto completo
   
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
        try (Comparer comparer = new Comparer("main.xlsx") 
        {
            // Includi file aggiuntivi da confrontare
        	comparer.add("version1.xlsx");
            comparer.add("version2.xlsx");
            comparer.add("version3.xlsx");

            // Ottieni il rapporto con il nome specificato come risultato
            final Path resultPath = comparer.compare("full_report.xlsx"); 

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
    title: "Gestisci le modifiche nei fogli di calcolo XLSX utilizzando Java"
    exclude: "XLSX"
    description: "La libreria GroupDocs.Comparison Java consente agli utenti di monitorare diverse versioni di fogli di calcolo XLSX attraverso report dettagliati e precisi che possono essere composti facilmente."
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