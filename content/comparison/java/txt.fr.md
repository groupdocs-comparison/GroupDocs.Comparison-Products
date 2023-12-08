---
############################# Static ############################
layout: "auto-gen-comparison"
date: 2021-05-13T12:45:19+03:00
draft: false

############################# Head ############################
head_title: "API de comparaison Java TXT - Comparez les fichiers TXT pour les différences"
head_description: "Comparez et fusionnez des fichiers TXT dans des applications Java, J2EE, J2SE. Analysez le résumé des différences dans le contenu, le texte et le style des fichiers, images et formats de documents TXT."

############################# Header ############################
title: "Comparez les fichiers TXT en Java"
description: "Effectuez une comparaison ligne par ligne entre plus de deux fichiers TXT en Java. Récupérez une liste des différences et enregistrez les fichiers comparés dans un seul document."
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Télécharger l'essai gratuit"
    link: "https://downloads.groupdocs.com/comparison/java"

############################# SubMenu ############################
submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Comparison for Java"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-comparison-java.png"
        product: "GroupDocs.Comparison"
        platform: "Java"

    middle:
        button: 
            # button loop
            - link: "https://apireference.groupdocs.com/comparison/java"
              text: "Référence API"

            # button loop
            - link: "https://github.com/groupdocs-comparison"
              text: "Exemples de codes"

            # button loop
            - link: "https://products.groupdocs.app/comparison/family"
              text: "Démos en direct"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/java"
              text: "Tarifs"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/java"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: "À propos de l'API GroupDocs.Comparison for Java"
    content: |
        Renforcez vos applications Java avec des fonctionnalités de comparaison d'images et de documents à l'aide de l'API [GroupDocs.Comparison for Java](/comparison/java/). Il vous aide à identifier les différences au sein des paragraphes, des mots, des caractères, des formes, voire des styles de texte des documents comparés du même format, permet de fusionner les modifications et d'exporter vers un document final. Il prend en charge la comparaison et la fusion d'un large éventail de documents, notamment PDF, Word, feuilles de calcul Excel, présentations PowerPoint, diagrammes Visio, e-mails Outlook, HTML, dessins et formats de fichiers image sans utiliser de bibliothèque externe.

############################# Steps ############################
steps:
    enable: true
    title_left: "Étapes pour comparer les fichiers TXT en Java"
    content_left: |
        [GroupDocs.Comparison](/comparison/java/) permet aux développeurs Java de comparer facilement les fichiers TXT au sein de leurs applications à l'aide de quelques lignes de code.
        * Instanciez l'objet **Comparer** avec le chemin ou le flux du document source.
        * Appelez la méthode add et spécifiez le chemin ou le flux du document cible.
        * Appelez la méthode de comparaison.
    title_right: "Configuration requise"
    content_right: |
        Les API GroupDocs.Comparison for Java sont prises en charge sur toutes les principales plates-formes et systèmes d'exploitation. Avant d'exécuter le code ci-dessous, assurez-vous que les conditions préalables suivantes sont installées sur votre système.
        * Systèmes d'exploitation : Microsoft Windows, Linux, MacOS
        * Environnements de développement : NetBeans, Intellij IDEA, Eclipse etc
        * Environnement d'exécution Java : J2SE 6.0 et supérieur
        * Obtenez la dernière version de GroupDocs.Comparison for Java auprès de [Maven](https://repository.groupdocs.com/webapp/#/artifacts/browse/tree/General/repo/com/groupdocs/groupdocs-comparison)
    code: |
        ```java
        // Comparer les documents du fichier local
        
        try (Comparer comparer = new Comparer("C:\\source.txt")) {
            comparer.add("C:\\target.txt");
            comparer.compare("C:\\result.txt"); // Créer un fichier de résultats avec le nom spécifié
        }
        
        // Comparer les documents du flux
        
        try (Comparer comparer = new Comparer(new FileInputStream("C:\\source.txt"))) {
            comparer.add(new FileInputStream("C:\\target.txt"));
            comparer.compare(new FileOutputStream("C:\\result.txt")); // Créer un fichier de résultats avec le nom spécifié
        }
        ```

############################# Demos ############################
demos:
    enable: true
    title: "Démos en direct pour comparer les fichiers TXT"
    content: |
        Comparez dès maintenant les fichiers TXT en visitant le site Web [GroupDocs.Comparison Live Demos](https://products.groupdocs.app/comparison/family).
        La démo en direct présente les avantages suivants

############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-txt"
          title: "À propos du format de fichier TXT"
          content: |
            Un fichier avec l'extension .TXT représente un document texte contenant du texte brut sous forme de lignes. Les paragraphes d'un document texte sont reconnus par les retours chariot et sont utilisés pour une meilleure organisation du contenu du fichier. Un document texte standard peut être ouvert dans n'importe quel éditeur de texte ou application de traitement de texte sur différents systèmes d'exploitation. Tout le texte contenu dans un tel fichier est dans un format lisible par l'homme et représenté par une séquence de caractères.
          link: "https://docs.fileformat.com/image/txt/"

############################# More Formats ############################
more_formats:
    enable: true
    title: "Comparez d'autres formats de fichiers"
    content: |
        API de comparaison d'images et de documents multiformats pour Java. Comparez certains des formats de fichiers populaires ci-dessous sans aucun logiciel externe.
    format: 
        # format loop
        - name: "Compare PDF Files"
          link: "https://products.groupdocs.com/comparison/java/pdf/"
          description: "Adobe Portable Document Format"

        # format loop
        - name: "Compare DOC Files"
          link: "https://products.groupdocs.com/comparison/java/doc/"
          description: "Microsoft Word Document"

        # format loop
        - name: "Compare DOCM Files"
          link: "https://products.groupdocs.com/comparison/java/docm/"
          description: "Microsoft Word Macro-Enabled Document"

        # format loop
        - name: "Compare DOCX Files"
          link: "https://products.groupdocs.com/comparison/java/docx/"
          description: "Microsoft Word Open XML Document"

        # format loop
        - name: "Compare DOT Files"
          link: "https://products.groupdocs.com/comparison/java/dot/"
          description: "Microsoft Word Document Template"

        # format loop
        - name: "Compare DOTM Files"
          link: "https://products.groupdocs.com/comparison/java/dotm/"
          description: "Microsoft Word Macro-Enabled Template"

        # format loop
        - name: "Compare DOTX Files"
          link: "https://products.groupdocs.com/comparison/java/dotx/"
          description: "Word Open XML Document Template"

        # format loop
        - name: "Compare RTF Files"
          link: "https://products.groupdocs.com/comparison/java/rtf/"
          description: "Rich Text File Format"

        # format loop
        - name: "Compare TXT Files"
          link: "https://products.groupdocs.com/comparison/java/txt/"
          description: "Plain Text File Format"

        # format loop
        - name: "Compare XLS Files"
          link: "https://products.groupdocs.com/comparison/java/xls/"
          description: "Microsoft Excel Binary File Format"

        # format loop
        - name: "Compare XLSX Files"
          link: "https://products.groupdocs.com/comparison/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop
        - name: "Compare XLTM Files"
          link: "https://products.groupdocs.com/comparison/java/xltm/"
          description: "Microsoft Excel macro-enabled template"

        # format loop
        - name: "Compare XLSM Files"
          link: "https://products.groupdocs.com/comparison/java/xlsm/"
          description: "Microsoft Excel Macro-Enabled Spreadsheet"

        # format loop
        - name: "Compare XLSB Files"
          link: "https://products.groupdocs.com/comparison/java/xlsb/"
          description: "Microsoft Excel Binary Spreadsheet File"

        # format loop
        - name: "Compare CSV Files"
          link: "https://products.groupdocs.com/comparison/java/csv/"
          description: "Comma Separated Values File"

        # format loop
        - name: "Compare PPT Files"
          link: "https://products.groupdocs.com/comparison/java/ppt/"
          description: "PowerPoint Presentation"

        # format loop
        - name: "Compare PPS Files"
          link: "https://products.groupdocs.com/comparison/java/pps/"
          description: "Microsoft PowerPoint Slide Show"

        # format loop
        - name: "Compare PPTX Files"
          link: "https://products.groupdocs.com/comparison/java/pptx/"
          description: "PowerPoint Open XML Presentation"

        # format loop
        - name: "Compare PPSX Files"
          link: "https://products.groupdocs.com/comparison/java/ppsx/"
          description: "PowerPoint Open XML Slide Show"

        # format loop
        - name: "Compare POT Files"
          link: "https://products.groupdocs.com/comparison/java/pot/"
          description: "Microsoft PowerPoint template"

        # format loop
        - name: "Compare POTX Files"
          link: "https://products.groupdocs.com/comparison/java/potx/"
          description: "Microsoft PowerPoint Open XML Template"

        # format loop
        - name: "Compare ODS Files"
          link: "https://products.groupdocs.com/comparison/java/ods/"
          description: "Open Document Spreadsheet"

        # format loop
        - name: "Compare ODP Files"
          link: "https://products.groupdocs.com/comparison/java/odp/"
          description: "OpenDocument Presentation File Format"

        # format loop
        - name: "Compare OTP Files"
          link: "https://products.groupdocs.com/comparison/java/otp/"
          description: "Origin Graph Template"

        # format loop
        - name: "Compare ODT Files"
          link: "https://products.groupdocs.com/comparison/java/odt/"
          description: "Open Document Text"

        # format loop
        - name: "Compare OTT Files"
          link: "https://products.groupdocs.com/comparison/java/ott/"
          description: "Open Document Template"

        # format loop
        - name: "Compare VST Files"
          link: "https://products.groupdocs.com/comparison/java/vst/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare JPEG Files"
          link: "https://products.groupdocs.com/comparison/java/jpeg/"
          description: "JPEG Image"

        # format loop
        - name: "Compare PNG Files"
          link: "https://products.groupdocs.com/comparison/java/png/"
          description: "Portable Network Graphic"

        # format loop
        - name: "Compare GIF Files"
          link: "https://products.groupdocs.com/comparison/java/gif/"
          description: "Graphical Interchange Format File"

        # format loop
        - name: "Compare BMP Files"
          link: "https://products.groupdocs.com/comparison/java/bmp/"
          description: "Bitmap File Format"

        # format loop
        - name: "Compare HTML Files"
          link: "https://products.groupdocs.com/comparison/java/html/"
          description: "Hyper Text Markup Language"

        # format loop
        - name: "Compare MHT Files"
          link: "https://products.groupdocs.com/comparison/java/mht/"
          description: "Mime HTML"

        # format loop
        - name: "Compare MHTML Files"
          link: "https://products.groupdocs.com/comparison/java/mhtml/"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop
        - name: "Compare MSG Files"
          link: "https://products.groupdocs.com/comparison/java/msg/"
          description: "Microsoft Outlook E-mail Message"

        # format loop
        - name: "Compare EML Files"
          link: "https://products.groupdocs.com/comparison/java/eml/"
          description: "E-mail Message"

        # format loop
        - name: "Compare EMLX Files"
          link: "https://products.groupdocs.com/comparison/java/emlx/"
          description: "Apple Mail E-mail File"

        # format loop
        - name: "Compare ONE Files"
          link: "https://products.groupdocs.com/comparison/java/one/"
          description: "Microsoft OneNote"

        # format loop
        - name: "Compare VSD Files"
          link: "https://products.groupdocs.com/comparison/java/vsd/"
          description: "Microsoft Visio 2003-2010 Drawing"

        # format loop
        - name: "Compare VSDX Files"
          link: "https://products.groupdocs.com/comparison/java/vsdx/"
          description: "Microsoft Visio Drawing"

        # format loop
        - name: "Compare VSS Files"
          link: "https://products.groupdocs.com/comparison/java/vss/"
          description: "Microsoft Visio 2003-2010 Stencil"

        # format loop
        - name: "Compare VST Files"
          link: "https://products.groupdocs.com/comparison/java/vst/"
          description: "Microsoft Visio 2003-2010 Template"

        # format loop
        - name: "Compare VDX Files"
          link: "https://products.groupdocs.com/comparison/java/vdx/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare CS Files"
          link: "https://products.groupdocs.com/comparison/java/cs/"
          description: "CSharp Language"

        # format loop
        - name: "Compare Java Files"
          link: "https://products.groupdocs.com/comparison/java/java/"
          description: "Java Language"

        # format loop
        - name: "Compare CPP Files"
          link: "https://products.groupdocs.com/comparison/java/cpp/"
          description: "C++ Language"

        # format loop
        - name: "Compare JS Files"
          link: "https://products.groupdocs.com/comparison/java/js/"
          description: "JavaScript Language"

        # format loop
        - name: "Compare PY Files"
          link: "https://products.groupdocs.com/comparison/java/py/"
          description: "Python Language"

        # format loop
        - name: "Compare RB Files"
          link: "https://products.groupdocs.com/comparison/java/rb/"
          description: "Ruby Language"

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison propose des API de visualisation de documents pour d'autres environnements de développement populaires"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for .NET TXT"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
          product: "GroupDocs.Comparison"
          platform: ".NET"
          link: "/comparison/net/txt/"

############################# Back to top ###############################
back_to_top:
    enable: true
---