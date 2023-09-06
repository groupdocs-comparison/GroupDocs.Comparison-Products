---
############################# Static ############################
layout: "auto-gen-comparison"
date: 2021-05-13T12:45:19+03:00
draft: false

############################# Head ############################
head_title: "Comparez deux fichiers DOC dans .NET | API de comparaison de documents"
head_description: "Comparez et fusionnez plus de deux fichiers DOC dans des applications C# .NET. Récupérez le résumé des différences dans le contenu, le texte et le style des fichiers, images et formats de documents DOC."

############################# Header ############################
title: "Comparez les fichiers DOC en C# .NET"
description: "API de comparaison de documents .NET pour détecter les modifications entre deux versions de fichiers DOC et exporter vers un document final avec un résumé détaillé des différences entre les documents comparés."
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Télécharger l'essai gratuit"
    link: "https://downloads.groupdocs.com/comparison/net"

############################# SubMenu ############################
submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Comparison for .NET"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-comparison-net.png"
        product: "GroupDocs.Comparison"
        platform: ".NET"

    middle:
        button: 
            # button loop
            - link: "https://apireference.groupdocs.com/comparison/net"
              text: "Référence API"

            # button loop
            - link: "https://github.com/groupdocs-comparison"
              text: "Exemples de codes"

            # button loop
            - link: "https://products.groupdocs.app/comparison/family"
              text: "Démos en direct"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "Tarifs"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/net"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: "À propos de l'API GroupDocs.Comparison for .NET"
    content: |
        [GroupDocs.Comparison for .NET](/comparison/net/) est une API .NET native permettant de comparer plusieurs images et documents du même format. Il vous aide à détecter les différences entre les paragraphes, les mots, les caractères, les formes et même les styles de texte des documents comparés, à fusionner les modifications et à les exporter vers un document final. Il prend en charge la comparaison et la fusion de documents PDF, Word, feuilles de calcul Excel, présentations PowerPoint, diagrammes Visio, e-mails Outlook, HTML, dessins et formats de fichiers image sans utiliser de bibliothèque externe.

############################# Steps ############################
steps:
    enable: true
    title_left: "Étapes pour comparer les fichiers DOC en C#"
    content_left: |
        [GroupDocs.Comparison](/comparison/net/) permet aux développeurs .NET de comparer et de fusionner facilement plusieurs fichiers DOC dans leurs applications en implémentant quelques étapes simples.
        * Instanciez l'objet **Comparer** avec le chemin ou le flux du document source.
        * Appelez la méthode Add et spécifiez le chemin ou le flux du document cible. Répétez cette étape pour chaque document cible.
        * Appelez la méthode Compare.
    title_right: "Configuration requise"
    content_right: |
        Les API GroupDocs.Comparison for .NET sont prises en charge sur toutes les principales plates-formes et systèmes d'exploitation. Avant d'exécuter le code ci-dessous, assurez-vous que les conditions préalables suivantes sont installées sur votre système.
        * Systèmes d'exploitation : Microsoft Windows, Linux, MacOS
        * Environnements de développement : Microsoft Visual Studio, Xamarin, MonoDevelop
        * Frameworks : .NET Framework, .NET Standard, .NET Core, Mono
        * Obtenez la dernière version de GroupDocs.Comparison for .NET téléchargée depuis [NuGet](https://www.nuget.org/packages/groupdocs.comparison)
    code: |
        ```cs
        // Comparez plusieurs documents à partir du disque local
        
        using (Comparer comparer = new Comparer("source.doc"))
        {
        	comparer.Add("target1.doc");
            comparer.Add("target2.doc");
            comparer.Add("target3.doc");
            comparer.Compare("result.doc"); // Créer un fichier de résultats avec le nom spécifié
        }
        
        // Comparer plusieurs documents du flux
        
        using (Comparer comparer = new Comparer(File.OpenRead("source.doc")))
        {
        	comparer.Add(File.OpenRead("target1.doc"));
            comparer.Add(File.OpenRead("target2.doc"));
            comparer.Add(File.OpenRead("target3.doc"));
            comparer.Compare(File.Create("result.doc")); // Créer un fichier de résultats avec le nom spécifié
        }
        ```

############################# Demos ############################
demos:
    enable: true
    title: "Démonstrations en direct de comparaison de fichiers DOC"
    content: |
        Détectez dès maintenant les différences entre les fichiers DOC en visitant le site Web [GroupDocs.Comparison Live Demos](https://products.groupdocs.app/comparison/family).
        La démo en direct présente les avantages suivants

############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-doc"
          title: "À propos du format de fichier DOC"
          content: |
            Les fichiers avec l'extension .doc représentent des documents générés par Microsoft Word ou d'autres documents de traitement de texte au format de fichier binaire. L'extension était initialement utilisée pour la documentation en texte brut sur plusieurs systèmes d'exploitation différents. Il peut contenir plusieurs types de données différents, tels que des images, du texte formaté ou brut, des graphiques, des tableaux, des objets incorporés, des liens, des pages, le formatage des pages, les paramètres d'impression et bien d'autres. Le format était populaire pour toutes sortes de documentation en raison de la variété d'options qu'il offre aux utilisateurs pour rédiger des manuels, des propositions, des spécifications, des curriculum vitae, des articles ou tout autre document similaire. La version mise à jour de DOC est DOCX qui est basée sur Office OpenXML dont les spécifications sont librement disponibles.
          link: "https://docs.fileformat.com/image/doc/"

############################# More Formats ############################
more_formats:
    enable: true
    title: "Comparaison d'autres formats de fichiers"
    content: |
        API de comparaison de documents et d'images multiformats pour .NET. Analysez les différences entre des documents de même format sans utiliser d'outil externe.
    format: 
        # format loop
        - name: "Compare PDF Files"
          link: "https://products.groupdocs.com/comparison/net/pdf/"
          description: "Adobe Portable Document Format"

        # format loop
        - name: "Compare DOC Files"
          link: "https://products.groupdocs.com/comparison/net/doc/"
          description: "Microsoft Word Document"

        # format loop
        - name: "Compare DOCM Files"
          link: "https://products.groupdocs.com/comparison/net/docm/"
          description: "Microsoft Word Macro-Enabled Document"

        # format loop
        - name: "Compare DOCX Files"
          link: "https://products.groupdocs.com/comparison/net/docx/"
          description: "Microsoft Word Open XML Document"

        # format loop
        - name: "Compare DOT Files"
          link: "https://products.groupdocs.com/comparison/net/dot/"
          description: "Microsoft Word Document Template"

        # format loop
        - name: "Compare DOTM Files"
          link: "https://products.groupdocs.com/comparison/net/dotm/"
          description: "Microsoft Word Macro-Enabled Template"

        # format loop
        - name: "Compare DOTX Files"
          link: "https://products.groupdocs.com/comparison/net/dotx/"
          description: "Word Open XML Document Template"

        # format loop
        - name: "Compare RTF Files"
          link: "https://products.groupdocs.com/comparison/net/rtf/"
          description: "Rich Text File Format"

        # format loop
        - name: "Compare TXT Files"
          link: "https://products.groupdocs.com/comparison/net/txt/"
          description: "Plain Text File Format"

        # format loop
        - name: "Compare XLS Files"
          link: "https://products.groupdocs.com/comparison/net/xls/"
          description: "Microsoft Excel Binary File Format"

        # format loop
        - name: "Compare XLSX Files"
          link: "https://products.groupdocs.com/comparison/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop
        - name: "Compare XLTM Files"
          link: "https://products.groupdocs.com/comparison/net/xltm/"
          description: "Microsoft Excel macro-enabled template"

        # format loop
        - name: "Compare XLSM Files"
          link: "https://products.groupdocs.com/comparison/net/xlsm/"
          description: "Microsoft Excel Macro-Enabled Spreadsheet"

        # format loop
        - name: "Compare XLSB Files"
          link: "https://products.groupdocs.com/comparison/net/xlsb/"
          description: "Microsoft Excel Binary Spreadsheet File"

        # format loop
        - name: "Compare CSV Files"
          link: "https://products.groupdocs.com/comparison/net/csv/"
          description: "Comma Separated Values File"

        # format loop
        - name: "Compare PPT Files"
          link: "https://products.groupdocs.com/comparison/net/ppt/"
          description: "PowerPoint Presentation"

        # format loop
        - name: "Compare PPS Files"
          link: "https://products.groupdocs.com/comparison/net/pps/"
          description: "Microsoft PowerPoint Slide Show"

        # format loop
        - name: "Compare PPTX Files"
          link: "https://products.groupdocs.com/comparison/net/pptx/"
          description: "PowerPoint Open XML Presentation"

        # format loop
        - name: "Compare PPSX Files"
          link: "https://products.groupdocs.com/comparison/net/ppsx/"
          description: "PowerPoint Open XML Slide Show"

        # format loop
        - name: "Compare POT Files"
          link: "https://products.groupdocs.com/comparison/net/pot/"
          description: "Microsoft PowerPoint template"

        # format loop
        - name: "Compare POTX Files"
          link: "https://products.groupdocs.com/comparison/net/potx/"
          description: "Microsoft PowerPoint Open XML Template"

        # format loop
        - name: "Compare ODS Files"
          link: "https://products.groupdocs.com/comparison/net/ods/"
          description: "Open Document Spreadsheet"

        # format loop
        - name: "Compare ODP Files"
          link: "https://products.groupdocs.com/comparison/net/odp/"
          description: "OpenDocument Presentation File Format"

        # format loop
        - name: "Compare OTP Files"
          link: "https://products.groupdocs.com/comparison/net/otp/"
          description: "Origin Graph Template"

        # format loop
        - name: "Compare ODT Files"
          link: "https://products.groupdocs.com/comparison/net/odt/"
          description: "Open Document Text"

        # format loop
        - name: "Compare OTT Files"
          link: "https://products.groupdocs.com/comparison/net/ott/"
          description: "Open Document Template"

        # format loop
        - name: "Compare VST Files"
          link: "https://products.groupdocs.com/comparison/net/vst/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare JPEG Files"
          link: "https://products.groupdocs.com/comparison/net/jpeg/"
          description: "JPEG Image"

        # format loop
        - name: "Compare PNG Files"
          link: "https://products.groupdocs.com/comparison/net/png/"
          description: "Portable Network Graphic"

        # format loop
        - name: "Compare GIF Files"
          link: "https://products.groupdocs.com/comparison/net/gif/"
          description: "Graphical Interchange Format File"

        # format loop
        - name: "Compare BMP Files"
          link: "https://products.groupdocs.com/comparison/net/bmp/"
          description: "Bitmap File Format"

        # format loop
        - name: "Compare HTML Files"
          link: "https://products.groupdocs.com/comparison/net/html/"
          description: "Hyper Text Markup Language"

        # format loop
        - name: "Compare MHT Files"
          link: "https://products.groupdocs.com/comparison/net/mht/"
          description: "Mime HTML"

        # format loop
        - name: "Compare MHTML Files"
          link: "https://products.groupdocs.com/comparison/net/mhtml/"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop
        - name: "Compare MSG Files"
          link: "https://products.groupdocs.com/comparison/net/msg/"
          description: "Microsoft Outlook E-mail Message"

        # format loop
        - name: "Compare EML Files"
          link: "https://products.groupdocs.com/comparison/net/eml/"
          description: "E-mail Message"

        # format loop
        - name: "Compare EMLX Files"
          link: "https://products.groupdocs.com/comparison/net/emlx/"
          description: "Apple Mail E-mail File"

        # format loop
        - name: "Compare ONE Files"
          link: "https://products.groupdocs.com/comparison/net/one/"
          description: "Microsoft OneNote"

        # format loop
        - name: "Compare VSD Files"
          link: "https://products.groupdocs.com/comparison/net/vsd/"
          description: "Microsoft Visio 2003-2010 Drawing"

        # format loop
        - name: "Compare VSDX Files"
          link: "https://products.groupdocs.com/comparison/net/vsdx/"
          description: "Microsoft Visio Drawing"

        # format loop
        - name: "Compare VSS Files"
          link: "https://products.groupdocs.com/comparison/net/vss/"
          description: "Microsoft Visio 2003-2010 Stencil"

        # format loop
        - name: "Compare VST Files"
          link: "https://products.groupdocs.com/comparison/net/vst/"
          description: "Microsoft Visio 2003-2010 Template"

        # format loop
        - name: "Compare VDX Files"
          link: "https://products.groupdocs.com/comparison/net/vdx/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare CS Files"
          link: "https://products.groupdocs.com/comparison/net/cs/"
          description: "CSharp Language"

        # format loop
        - name: "Compare Java Files"
          link: "https://products.groupdocs.com/comparison/net/java/"
          description: "Java Language"

        # format loop
        - name: "Compare CPP Files"
          link: "https://products.groupdocs.com/comparison/net/cpp/"
          description: "C++ Language"

        # format loop
        - name: "Compare JS Files"
          link: "https://products.groupdocs.com/comparison/net/js/"
          description: "JavaScript Language"

        # format loop
        - name: "Compare PY Files"
          link: "https://products.groupdocs.com/comparison/net/py/"
          description: "Python Language"

        # format loop
        - name: "Compare RB Files"
          link: "https://products.groupdocs.com/comparison/net/rb/"
          description: "Ruby Language"

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison propose des API de visualisation de documents pour d'autres environnements de développement populaires"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for Java DOC"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/doc/"

############################# Back to top ###############################
back_to_top:
    enable: true
---
