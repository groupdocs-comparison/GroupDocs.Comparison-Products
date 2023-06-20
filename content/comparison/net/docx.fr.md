
---
############################# Static ############################
layout: "auto-gen-comparison"
date: 2021-05-13T12:45:19+03:00
draft: false

############################# Head ############################
head_title: "Comparez deux fichiers DOCX dans .NET | API de comparaison de documents"
head_description: "Comparez et fusionnez plus de deux fichiers DOCX dans des applications C# .NET. Récupérez le résumé des différences dans le contenu, le texte et le style des fichiers, images et formats de document DOCX."

############################# Header ############################
title: "Comparez les fichiers DOCX en C# .NET"
description: "API de comparaison de documents .NET pour détecter les changements entre deux versions de fichiers DOCX et exporter vers un document final avec un résumé détaillé des différences entre les documents comparés."
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Télécharger la version d'essai gratuite"
    link: "https://downloads.groupdocs.com/comparison/net"

############################# SubMenu ############################
submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Comparison pour .NET"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-comparison-net.png"
        product: "GroupDocs.Comparison"
        platform: ".FILET"

    middle:
        button: 
            # boucle de bouton
            - link: "https://apireference.groupdocs.com/comparison/net"
              text: "Référence API"

            # boucle de bouton
            - link: "https://github.com/groupdocs-comparison"
              text: "Exemples de code"

            # boucle de bouton
            - link: "https://products.groupdocs.app/comparison/family"
              text: "Démos en direct"

            # boucle de bouton
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "Prix"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/net"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: "À propos de GroupDocs.Comparison pour l'API .NET"
    content: |
        [GroupDocs.Comparison pour .NET](/fr/comparison/net/) est une API .NET native permettant de comparer plusieurs images et documents du même format. Il vous aide à détecter les différences entre les paragraphes, les mots, les caractères, les formes, même les styles de texte des documents comparés, à fusionner les modifications et à les exporter vers un document final. Il prend en charge la comparaison et la fusion de PDF, de documents Word, de feuilles de calcul Excel, de présentations PowerPoint, de diagrammes Visio, d'e-mails Outlook, de HTML, de dessins et de formats de fichiers image sans utiliser de bibliothèque externe.

############################# Steps ############################
steps:
    enable: true
    title_left: "Étapes pour comparer les fichiers DOCX en C#"
    content_left: |
        [GroupDocs.Comparison](/comparison/net/) permet aux développeurs .NET de comparer et de fusionner facilement plusieurs fichiers DOCX dans leurs applications en mettant en œuvre quelques étapes simples.
        *   Instanciez l'objet **Comparateur** avec le chemin ou le flux du document source.
        *   Appelez la méthode Add et spécifiez le chemin ou le flux du document cible. Répétez cette étape pour chaque document cible.
        *   Appelez la méthode de comparaison.
    title_right: "Configuration requise"
    content_right: |
        Les API GroupDocs.Comparison pour .NET sont prises en charge sur toutes les principales plateformes et systèmes d'exploitation. Avant d'exécuter le code ci-dessous, assurez-vous que les prérequis suivants sont installés sur votre système.
        *   Systèmes d'exploitation : Microsoft Windows, Linux, MacOS
        *   Environnements de développement : Microsoft Visual Studio, Xamarin, MonoDevelop
        *   Frameworks : .NET Framework, .NET Standard, .NET Core, Mono
        *   Obtenez la dernière version de GroupDocs.Comparison pour .NET téléchargée depuis [NuGet](https://www.nuget.org/packages/groupdocs.comparison)
    code: |
        ```cs
        // Comparer plusieurs documents à partir du disque local
        
        using (Comparer comparer = new Comparer("source.docx"))
        {
        	comparer.Add("target1.docx");
            comparer.Add("target2.docx");
            comparer.Add("target3.docx");
            comparer.Compare("result.docx"); // Crée un fichier résultat avec le nom spécifié
        }
        
        // Comparer plusieurs documents à partir du flux
        
        using (Comparer comparer = new Comparer(File.OpenRead("source.docx")))
        {
        	comparer.Add(File.OpenRead("target1.docx"));
            comparer.Add(File.OpenRead("target2.docx"));
            comparer.Add(File.OpenRead("target3.docx"));
            comparer.Compare(File.Create("result.docx")); // Crée un fichier résultat avec le nom spécifié
        }
        ```

############################# Demos ############################
demos:
    enable: true
    title: "Démonstrations en direct de la comparaison de fichiers DOCX"
    content: |
        Détectez dès maintenant les différences entre les fichiers DOCX en visitant le site Web [GroupDocs.Comparison Live Demos](https://products.groupdocs.app/comparison/family).
        La démo en direct présente les avantages suivants

############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-docx"
          title: "À propos du format de fichier DOCX"
          content: |
            DOCX est un format bien connu pour les documents Microsoft Word. Introduit à partir de 2007 avec la sortie de Microsoft Office 2007, la structure de ce nouveau format de document est passée de binaire brut à une combinaison de fichiers XML et binaires. Les fichiers Docx peuvent être ouverts avec Word 2007 et les versions latérales, mais pas avec les versions antérieures de MS Word qui prennent en charge les extensions de fichier DOC.
          link: "https://docs.fileformat.com/image/docx/"

############################# More Formats ############################
more_formats:
    enable: true
    title: "Comparaison d'autres formats de fichiers"
    content: |
        API de comparaison de documents et d'images multiformats pour .NET. Analysez les différences entre des documents d'un même format sans utiliser d'outil externe.
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
    title: "GroupDocs.Comparison offers document viewing APIs for other popular formats"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for Java DOCX"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/docx/"

############################# Back to top ###############################
back_to_top:
    enable: true
---
