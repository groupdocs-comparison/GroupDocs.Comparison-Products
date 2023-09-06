---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "API de comparaison de documents C# .NET | Comparer et fusionner PDF Word Excel Web et texte"
head_description: "API de comparaison de documents C# .NET. Comparez et fusionnez les formats de fichiers PDF Word DOC DOCX, Excel Spreadsheet, PPT, PPTX, HTML, EMLX MSG, VSDX, DXF DWG et image."

############################# Header ############################
title: "API .NET pour comparer les fichiers"
description: "Développez des applications à l'aide de l'API de comparaison de documents .NET pour vérifier et comparer les fichiers pour détecter les différences de contenu et de style."
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
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
        product: "GroupDocs.Comparison"
        platform: ".NET"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "Aperçu"

            # button loop
            - link: "#features"
              text: "Caractéristiques"

            # button loop
            - link: "#support"
              text: "Soutien"

            # button loop
            - link: "https://products.groupdocs.app/comparison"
              text: "Démo en direct"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "Tarifs"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    example_image: "/comparison/comparison-example.png"
    content: |
      
    more_overview:
      # more_overview_loop
      - title: "Qu'est-ce que GroupDocs.Comparison for .NET"
        content: "L'API GroupDocs.Comparison for .NET est une solution rapide et fiable prête à être utilisée lors de la création d'applications pour rechercher et mettre en évidence les différences entre des documents de formats identiques ou différents en C#, ASP.NET ou d'autres technologies liées à la plate-forme logicielle .NET."

      # more_overview_loop
      - title: "Formats pris en charge"
        content: "La bibliothèque GroupDocs.Comparison prend en charge la détection des différences de contenu et de style de texte entre les formats d'image et de document courants tels que PDF, HTML, courrier électronique Outlook, documents Microsoft Office Word, feuilles de calcul Excel, présentations PowerPoint, OneNote, diagrammes Visio, textes, png , images gif et bmp ainsi qu'une centaine d'autres formats."
        
      # more_overview_loop
      - title: "Capacités de comparaison"
        content: "La comparaison peut être effectuée pour détecter les changements dans le contenu des mots, des paragraphes, des tableaux ou des graphiques et leurs styles, et vous fournira un document de comparaison répertoriant un résumé des différences, leur nombre et leur type d'appartenance. GroupDocs.Comparison for .NET peut facilement extraire des informations de base sur le document source, comparer et enregistrer des documents simples, protégés par mot de passe et cryptés de différents formats via un fichier ou un flux de données."
        
      # more_overview_loop
      - title: "Documentation et exemples"
        content: "Il existe déjà de nombreuses documentations sur l'utilisation de la bibliothèque Comparison sur différentes plates-formes avec des exemples de code, vous n'avez donc pas à réfléchir sérieusement à la façon de travailler avec GroupDocs.Comparison pour l'API .NET dans votre application."
        
      # more_overview_loop
      - title: "Compatibilité"
        content: "Vous pouvez utiliser GroupDocs.Comparison for .NET pour créer des applications dans n'importe quel environnement de développement orienté sur la plateforme .NET. Il est compatible avec tous les langages basés sur .NET et prend en charge les systèmes d'exploitation courants (Windows, Linux, MacOS) sur lesquels vous pouvez installer des frameworks Mono ou .NET (y compris .NET Core)."
    examples:
      enable: true
      
    more_feature:
      # more_feature_loop
      - title: "Comparez facilement des documents à l'aide de l'API .NET"
        content: |
          L'API GroupDocs.Comparison for .NET vous offre un moyen simple et efficace de comparer vos fichiers. Voici un exemple qui montre comment comparer deux documents DOCX en utilisant C# :  

          ```cs
          // Fichiers source et cible à comparer
          string source = @"source.docx";
          string target = @"target.docx";
          Comparer comparer = new Comparer();
          // Comparez deux documents
          ICompareResult result = comparer.Compare(source, target, new ComparisonSettings());
          ```
      # more_feature_loop
      - title: "Choisir le niveau de détail pour la comparaison"
        content: "Avec GroupDocs.Comparison for .NET, vous pouvez spécifier dans quelle mesure vous souhaitez que les documents soient comparés. Vous pouvez choisir entre faible (comparez le texte mot par mot avec une précision pour la grille d'imagerie = 50), moyen (comparez le texte caractère par caractère avec une précision pour la grille d'imagerie = 100) ou élevé (comparez le texte caractère par caractère avec une précision pour la grille d'imagerie = 150)."

      # more_feature_loop
      - title: "Prise en charge de la comparaison des styles de texte"
        content: |
          GroupDocs.Comparison for .NET offre une fonctionnalité permettant de comparer le style de texte.  

          Pendant que les mots et les caractères des documents sont comparés, le nom de la police, la taille de la police, la couleur de la police, le style de police (gras, italique, souligné, petites majuscules, lien hypertexte) et la couleur de soulignement (le cas échéant) peuvent être comparés pour trouver des différences.  

          Lors de la comparaison de paragraphes, vous pouvez comparer des styles tels que l'alignement des paragraphes, l'indentation (retrait gauche, retrait droit), l'espacement des paragraphes (espace après, espace avant), le retrait de la première ligne et l'espacement des lignes.  

          GroupDocs.Comparison for .NET prend également en charge la comparaison d'autres sections d'une page, le cas échéant, telles que la distance du pied de page, la hauteur et l'orientation de la page, les marges (gauche, droite, haut et bas), la largeur de la bordure et la couleur de la bordure.  
      
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Voici un aperçu de GroupDocs.Comparison for .NET :
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Aperçu"
          content: |
            * Comparaison de documents
            * Comparaison des fichiers HTML
            * Comparaison PDF
            * Comparaison des diagrammes
            * Comparer le contenu du fichier
            * Comparez les styles de texte
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison for .NET prend en charge tous les [formats de fichiers de documents](https://docs.groupdocs.com/comparison/net/supported-document-formats/) populaires, notamment : Microsoft Office, PDF, images et bien d'autres. .
        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** [DOC](https://products.groupdocs.com/comparison/net/doc/), [DOCX](https://products.groupdocs.com/comparison/net/docx/), [DOCM](https://products.groupdocs.com/comparison/net/docm/), [DOT](https://products.groupdocs.com/comparison/net/dot/), [DOTX](https://products.groupdocs.com/comparison/net/dotx/), [DOTM](https://products.groupdocs.com/comparison/net/dotm/), [RTF](https://products.groupdocs.com/comparison/net/rtf/), [TXT](https://products.groupdocs.com/comparison/net/txt/)
                * **Excel:** [XLS](https://products.groupdocs.com/comparison/net/xls/), [XLSX](https://products.groupdocs.com/comparison/net/xlsx/), [XLSM](https://products.groupdocs.com/comparison/net/xlsm/), [XLSB](https://products.groupdocs.com/comparison/net/xlsb/), [XLTM](https://products.groupdocs.com/comparison/net/xltm/), [XLT](https://products.groupdocs.com/comparison/net/xlt/), [XLTM](https://products.groupdocs.com/comparison/net/xltm/), [XLTX](https://products.groupdocs.com/comparison/net/xltx/), [XLAM](https://products.groupdocs.com/comparison/net/xlam/), [SXC](https://products.groupdocs.com/comparison/net/sxc/), [SpreadsheetML](https://products.groupdocs.com/comparison/net/xml/)
                * **PowerPoint:** [PPT](https://products.groupdocs.com/comparison/net/ppt/), [PPTX](https://products.groupdocs.com/comparison/net/pptx/), [PPS](https://products.groupdocs.com/comparison/net/pps/), [PPSX](https://products.groupdocs.com/comparison/net/ppsx/), [PPSM](https://products.groupdocs.com/comparison/net/ppsm/), [POT](https://products.groupdocs.com/comparison/net/pot/), [POTM](https://products.groupdocs.com/comparison/net/potm/), [POTX](https://products.groupdocs.com/comparison/net/potx/), [PPTM](https://products.groupdocs.com/comparison/net/pptm/)
                * **Visio:** [VSD](https://products.groupdocs.com/comparison/net/vsd/), [VDX](https://products.groupdocs.com/comparison/net/vdx/), [VSS](https://products.groupdocs.com/comparison/net/vss/), [VSSX](https://products.groupdocs.com/comparison/net/vssx/), [VSX](https://products.groupdocs.com/comparison/net/vsx/), [VST](https://products.groupdocs.com/comparison/net/vst/), [VSTX](https://products.groupdocs.com/comparison/net/vstx/), [VTX](https://products.groupdocs.com/comparison/net/vtx/), [VSDX](https://products.groupdocs.com/comparison/net/vsdx/), [VDW](https://products.groupdocs.com/comparison/net/vdw/), [VSTM](https://products.groupdocs.com/comparison/net/vstm/), [VSSM](https://products.groupdocs.com/comparison/net/vssm/), [VSDM](https://products.groupdocs.com/comparison/net/vsdm/)
                * **Outlook:** [MSG](https://products.groupdocs.com/comparison/net/msg/), [EML](https://products.groupdocs.com/comparison/net/eml/), [EMLX](https://products.groupdocs.com/comparison/net/emlx/), [PST](https://products.groupdocs.com/comparison/net/pst/), [OST](https://products.groupdocs.com/comparison/net/ost/)
                * **OneNote:** [ONE](https://products.groupdocs.com/comparison/net/one/)

        right:
          enable: true
          table:
            # table loop
            - title: "Autres formats"
              content: |
                * **Langages de programmation**: [CS](https://products.groupdocs.com/comparison/net/cs/), [Java](https://products.groupdocs.com/comparison/net/java/), [CPP](https://products.groupdocs.com/comparison/net/cpp/), [JS](https://products.groupdocs.com/comparison/net/js/), [PY](https://products.groupdocs.com/comparison/net/py/), [RB](https://products.groupdocs.com/comparison/net/rb/), [PL](https://products.groupdocs.com/comparison/net/pl/), [ASM](https://products.groupdocs.com/comparison/net/asm/), [GROOVY](https://products.groupdocs.com/comparison/net/groovy/), [JSON](https://products.groupdocs.com/comparison/net/json/), [PHP](https://products.groupdocs.com/comparison/net/php/), [SQL](https://products.groupdocs.com/comparison/net/sql/), [LOG](https://products.groupdocs.com/comparison/net/log/), [DIFF](https://products.groupdocs.com/comparison/net/diff/), [LESS](https://products.groupdocs.com/comparison/net/less/), [SCALA](https://products.groupdocs.com/comparison/net/scala/)
                * **OpenDocument**: [ODT](https://products.groupdocs.com/comparison/net/odt/), [OTT](https://products.groupdocs.com/comparison/net/ott/), [ODS](https://products.groupdocs.com/comparison/net/ods/), [ODP](https://products.groupdocs.com/comparison/net/odp/), [OTP](https://products.groupdocs.com/comparison/net/otp/)
                * **Portable**: [PDF](https://products.groupdocs.com/comparison/net/pdf/), [MOBI](https://products.groupdocs.com/comparison/net/mobi/)
                * **AutoCAD**: [DXF](https://products.groupdocs.com/comparison/net/dxf/), [DWG](https://products.groupdocs.com/comparison/net/dwg/)
                * **Email**: [EML](https://products.groupdocs.com/comparison/net/eml/), [EMLX](https://products.groupdocs.com/comparison/net/emlx/), [MSG](https://products.groupdocs.com/comparison/net/msg/)
                * **Images**: [JPEG](https://products.groupdocs.com/comparison/net/jpeg/), [BMP](https://products.groupdocs.com/comparison/net/bmp/), [PNG](https://products.groupdocs.com/comparison/net/png/), [GIF](https://products.groupdocs.com/comparison/net/gif/), [DCM](https://products.groupdocs.com/comparison/net/dcm/), [DICOM](https://products.groupdocs.com/comparison/net/dicom/), [DjVu](https://products.groupdocs.com/comparison/net/djvu/)
                * **Web**: [HTM](https://products.groupdocs.com/comparison/net/htm/), [HTML](https://products.groupdocs.com/comparison/net/html/), [MHTML](https://products.groupdocs.com/comparison/net/mhtml/)
                * **Text**: [TXT](https://products.groupdocs.com/comparison/net/txt/)

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Comparison for .NET prend en charge les systèmes d'exploitation, les frameworks et les gestionnaires de packages suivants :
      
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Systèmes d'exploitation"
              content: |
                * Windows Desktop
                * Windows Server
                * Windows Azure
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "Cadres pris en charge"
              content: |
                * .NET Framework 2.0 ou plus
                * Mono Framework 1.2 ou plus
                * .NET Standard 2.0
                * .NET Core 2.0

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Directeur chargé d'emballage"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Environnements de développement"
              content: |
                * Microsoft Visual Studio
                * Xamarin.Android
                * Xamarin.IOS
                * Xamarin.Mac
                * MonoDevelop

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Comparison for .NET Fonctionnalités"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "[Identifier les différences de contenu et de styles de police](https://docs.groupdocs.com/comparison/net/compare-documents/)"

      # feature loop
      - icon: "fas fa-eye"
        content: "[Enregistrer un rapport résumé de toutes les différences trouvées après la comparaison de fichiers](https://docs.groupdocs.com/comparison/net/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-bolt"
        content: "[Appliquer ou rejeter les modifications après avoir analysé les différences et exporté le fichier résultant](https://docs.groupdocs.com/comparison/net/accept-or-reject-detected-changes/)"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "[Prise en charge de la fonctionnalité « Suivre les modifications » de Microsoft Word lors de la comparaison de fichiers Word](https://docs.groupdocs.com/comparison/net/show-revisions/)"

      # feature loop
      - icon: "fas fa-code"
        content: "[Repérez de manière unique les modifications provenant de chaque document comparé](https://docs.groupdocs.com/comparison/net/get-list-of-changes/)"

      # feature loop
      - icon: "fas fa-cloud"
        content: "[Lire et envoyer des documents via des flux](https://docs.groupdocs.com/comparison/net/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "[Licences mesurées – Facturation en fonction de l'utilisation de l'API](https://docs.groupdocs.com/comparison/net/licensing-and-evaluation-limitations/)"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "[Comparer plusieurs documents sources avec un seul document cible](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/)"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "[Comparez des pages spécifiques de fichiers Word entre elles – Acceptez ou rejetez toutes les modifications dans un seul document Word](https://docs.groupdocs.com/comparison/net/accept-or-reject-detected-changes/)"

      # feature loop
      - icon: "fas fa-border-all"
        content: "[Fusionnez jusqu'à 3 documents Word et comparez les formules utilisées dans les fichiers Word](https://docs.groupdocs.com/comparison/net/how-to-merge-source-code-files/)"

      # feature loop
      - icon: "fas fa-wrench"
        content: "[Obtenir des informations sur les documents à partir de filePath](https://docs.groupdocs.com/comparison/net/get-file-info/)"

      # feature loop
      - icon: "fas fa-columns"
        content: "[Enregistrer le résultat de la comparaison HTML sous forme d'images](https://docs.groupdocs.com/comparison/net/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-file-word"
        content: "[Option pour afficher ou masquer le contenu supprimé](https://docs.groupdocs.com/comparison/net/show-gap-lines/)"

      # feature loop
      - icon: "fas fa-envelope"
        content: "[Option pour activer ou désactiver la comparaison de styles de documents](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fas fa-print"
        content: "[Spécifier les chaînes pour marquer les éléments insérés, supprimés et modifiés par le style dans le document de comparaison](https://docs.groupdocs.com/comparison/net/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "[Spécifiez le séparateur de mots et la couleur de la police pour styliser le texte comparé](https://docs.groupdocs.com/comparison/net/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-lock"
        content: "[Calculer les coordonnées correctes des modifications dans les diapositives et diagrammes PDF, Word, PowerPoint](https://docs.groupdocs.com/comparison/net/get-changes-coordinates/)"

      # feature loop
      - icon: "fas fa-file-code"
        content: "[Comparez les fichiers protégés par mot de passe](https://docs.groupdocs.com/comparison/net/how-to-compare-password-protected-files/)"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "[Comparez les titres des graphiques dans des feuilles de calcul – Générez un graphique dans les fichiers de cellules résultants](https://docs.groupdocs.com/comparison/net/how-to-compare-spreadsheet-or-tables/)"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "[Dimensionner automatiquement les formes automatiques dans le fichier résultant du document Cellules](https://docs.groupdocs.com/comparison/net/how-to-compare-spreadsheet-or-tables/)"

      # feature loop
      - icon: "fas fa-heading"
        content: "[Accédez à la page de résumé détaillé pour détecter les modifications entre les fichiers de documents source et cible](https://docs.groupdocs.com/comparison/net/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "[Comparez les fichiers de langage de programmation et de script les plus populaires](https://docs.groupdocs.com/comparison/net/get-supported-document-formats/)"

      # feature loop
      - icon: "fas fa-cube"
        content: "[Comparez plusieurs (plus de deux) documents PDF, Word, Excel, diagrammes, e-mails, texte et OneNote](https://docs.groupdocs.com/comparison/net/compare-multiple-documents-with-specific-compare-settings/)"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "[Comparez l'en-tête et le pied de page des formats de fichiers pris en charge](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "[Comparez les signets, les variables et les propriétés personnalisées des formats de documents Word](https://docs.groupdocs.com/comparison/net/compare-bookmarks-in-word/)"

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison propose des API de visualisation de documents pour d'autres environnements de développement populaires"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for Java"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---