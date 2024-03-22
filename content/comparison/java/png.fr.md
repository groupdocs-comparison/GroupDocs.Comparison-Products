
---
############################# Static ############################
layout: "format"
date:  2024-03-22T13:27:40
draft: false
lang: fr
format: Png
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "Obtenez des rapports de différences pour PNG photos à l'aide de Java."
head_description: "L'API GroupDocs.Comparison for Java génère des rapports de comparaison utiles pour PNG documents dans les applications qui prennent en charge J2EE et J2SE."

############################# Header ############################
title: "Comparaison de PNG photos à l'aide de Java" 
description: "Renforcez vos applications Java, J2EE ou J2SE avec l'API GroupDocs.Comparison. Obtenez des informations détaillées sur les modifications apportées à vos PNG photos."
subtitle: "Cadre de vérification des différences de documents"  

header_actions:
  enable: true
  items:
    #  loop
    - title: "Téléchargement gratuit Maven"
      link: "https://releases.groupdocs.com/comparison/java/"
      
############################# About ############################
about:
    enable: true
    title: "Soyez informé des fonctionnalités de l'API GroupDocs.Comparison for Java"
    link: "/comparison/java/"
    link_title: "En savoir plus"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison développée en tant qu'API native Java adaptée à la rédaction de rapports détaillés basés sur les variations entre les différentes versions des images représentées au format PNG. Le format PNG n'est pas le seul à être pris en charge. De nombreuses fonctionnalités utiles fournies par notre API.

############################# Steps ############################
steps:
    enable: true
    title: "Utilisez Java pour comparer PNG fichiers"
    content: |
      Comparez PNG fichiers avec [GroupDocs.Comparison](https://products.groupdocs.com/comparison/java/) et récupérez un rapport pertinent sur leurs modifications
      
      1. Installez le package GroupDocs.Comparison for Java en le téléchargeant depuis [Maven](https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/)
      2. Fournissez une instance de comparaison et transmettez le chemin vers PNG
      3. Ajoutez PNG fichiers pour une comparaison plus approfondie
      4. Enregistrer le rapport sur le disque local
   
    code:
      platform: "net"
      copy_title: "Copier"
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
        copy_tip: "cliquez pour copier"
        copy_done: "copié"
      links:
        #  loop
        - title: "Plus d'exemples"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
        #  loop
        - title: "Documentation"
          link: "https://docs.groupdocs.com/comparison/java/"
          
      content: |
        ```java {style=abap}

        // Vérifiez les différences ou les similitudes entre les fichiers de votre disque dur

        // Créez un objet Comparer en spécifiant le fichier initial
        try (Comparer comparer = new Comparer("main.png") 
        {
            // Incluez des fichiers supplémentaires pour comparer
        	comparer.add("version1.png");
            comparer.add("version2.png");
            comparer.add("version3.png");

            // Obtenez le rapport avec le nom spécifié comme résultat
            final Path resultPath = comparer.compare("full_report.png"); 

            System.out.println("\nDocuments compared successfully.");
        }
        
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "Prêt à démarrer ?"
  description: "Essayez GroupDocs.Comparison fonctionnalités gratuitement ou demandez une licence"
  items:
    #  loop
    - title: "Maven télécharger"
      link: "https://releases.groupdocs.com/comparison/java/"
      color: "red"
        #  loop
    - title: "Licences"
      link: "https://purchase.groupdocs.com/pricing/comparison/java/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Trouvez des distinctions entre les différentes versions de PNG images via Java"
    exclude: "PNG"
    description: "GroupDocs.Comparison for Java L'API suit les modifications apportées à PNG images et rédige des rapports de démonstration pour une analyse plus approfondie."
    items: 
        # format loop 1
        - name: "Comparer PDF fichiers"
          format: "PDF"
          link: "/comparison/java/pdf/"
          description: "Format de document Adobe Portable"

        # format loop 2
        - name: "Comparer DOCX fichiers"
          format: "DOCX"
          link: "/comparison/java/docx/"
          description: "Microsoft Word Ouvrir un document XML"

        # format loop 3
        - name: "Comparer RTF fichiers"
          format: "RTF"
          link: "/comparison/java/rtf/"
          description: "Format de fichier RTF"

        # format loop 4
        - name: "Comparer TXT fichiers"
          format: "TXT"
          link: "/comparison/java/txt/"
          description: "Format de fichier texte brut"

        # format loop 5
        - name: "Comparer XLSX fichiers"
          format: "XLSX"
          link: "/comparison/java/xlsx/"
          description: "Feuille de calcul Microsoft Excel Open XML"

        # format loop 6
        - name: "Comparez les fichiers CSV"
          format: "CSV"
          link: "/comparison/java/csv/"
          description: "Fichier de valeurs séparées par des virgules"

        # format loop 7
        - name: "Comparer PPTX fichiers"
          format: "PPTX"
          link: "/comparison/java/pptx/"
          description: "PowerPoint Présentation Open XML"

        # format loop 8
        - name: "Comparer ODS fichiers"
          format: "ODS"
          link: "/comparison/java/ods/"
          description: "Open Document Feuille de calcul"

        # format loop 9
        - name: "Comparez les fichiers ODP"
          format: "ODP"
          link: "/comparison/java/odp/"
          description: "OpenDocument Format de fichier de présentation"

        # format loop 10
        - name: "Comparer ODT fichiers"
          format: "ODT"
          link: "/comparison/java/odt/"
          description: "Open Document Texte"

        # format loop 11
        - name: "Comparer JPEG fichiers"
          format: "JPEG"
          link: "/comparison/java/jpeg/"
          description: "JPEG Photo"

        # format loop 12
        - name: "Comparer PNG fichiers"
          format: "PNG"
          link: "/comparison/java/png/"
          description: "Portable Graphique du réseau"

        # format loop 13
        - name: "Comparer GIF fichiers"
          format: "GIF"
          link: "/comparison/java/gif/"
          description: "Fichier de format d'échange graphique"

        # format loop 14
        - name: "Comparer BMP fichiers"
          format: "BMP"
          link: "/comparison/java/bmp/"
          description: "Format de fichier bitmap"

        # format loop 15
        - name: "Comparer des fichiers HTML"
          format: "HTML"
          link: "/comparison/java/html/"
          description: "Langage de balisage Hyper Text"

        # format loop 16
        - name: "Comparer MSG fichiers"
          format: "MSG"
          link: "/comparison/java/msg/"
          description: "Message électronique Microsoft Outlook"

        # format loop 17
        - name: "Comparer ONE fichiers"
          format: "ONE"
          link: "/comparison/java/one/"
          description: "Microsoft OneNote"

        # format loop 18
        - name: "Comparer VSDX fichiers"
          format: "VSDX"
          link: "/comparison/java/vsdx/"
          description: "Dessin Microsoft Visio"

        # format loop 19
        - name: "Comparez les fichiers CS"
          format: "CS"
          link: "/comparison/java/cs/"
          description: "Langage CSharp"

        # format loop 20
        - name: "Comparer Java fichiers"
          format: "Java"
          link: "/comparison/java/java/"
          description: "Java Langue"
          
        # format loop 21
        - name: "Comparez les fichiers CPP"
          format: "CPP"
          link: "/comparison/java/cpp/"
          description: "Langage C++"
---