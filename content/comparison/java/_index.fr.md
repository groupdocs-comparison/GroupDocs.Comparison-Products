---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "API de comparaison de documents Java | Comparez le texte et le style du PDF Word Excel HTML"
head_description: "API de comparaison de documents Java pour comparer et fusionner Word Excel PPTX OpenOffice, Web, PDF, AutoCAD et autres formats de fichiers. Comparez les documents et suivez les modifications."

############################# Header ############################
title: "API Java pour comparer des fichiers"
description: "Créez des applications Java pour comparer efficacement le contenu des fichiers afin de détecter les différences dans tous les formats de documents et de fichiers image standard."
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
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
        product: "GroupDocs.Comparison"
        platform: "Java"

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
            - link: "https://purchase.groupdocs.com/pricing/comparison/java"
              text: "Tarifs"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    example_image: "/comparison/comparison-example.png"
    content: |
      
    more_overview:
      # more_overview_loop
      - title: "Qu'est-ce que GroupDocs.Comparison for Java"
        content: "GroupDocs.Comparison for Java est l'API la plus flexible et la plus simple à utiliser pour vous aider à développer des applications de comparaison de documents dans l'environnement Java. Le vérificateur de différences et l'API de fusion de documents vous permettent de détecter les changements et les différences de contenu ainsi que de style de texte entre des formats de documents similaires."

      # more_overview_loop
      - title: "Formats pris en charge"
        content: "La bibliothèque GroupDocs.Comparison prend en charge la détection des différences de contenu et de style de texte entre les formats d'image et de document courants tels que PDF, HTML, courrier électronique Outlook, documents Microsoft Office Word, feuilles de calcul Excel, présentations PowerPoint, OneNote, diagrammes Visio, textes, png , images gif et bmp ainsi qu'une centaine d'autres formats."
        
      # more_overview_loop
      - title: "Capacités de comparaison"
        content: "La comparaison peut être effectuée pour détecter les changements dans le contenu des mots, des paragraphes, des tableaux ou des graphiques et leurs styles, et vous fournira un document de comparaison répertoriant un résumé des différences, leur nombre et leur type d'appartenance. GroupDocs.Comparison for Java peut facilement extraire des informations de base sur le document source, comparer et enregistrer des documents simples, protégés par mot de passe et cryptés de différents formats via un fichier ou un flux de données."
        
      # more_overview_loop
      - title: "Documentation et exemples"
        content: "Il existe déjà de nombreuses documentations sur l'utilisation de la bibliothèque Comparison sur différentes plates-formes avec des exemples de code, vous n'avez donc pas à réfléchir sérieusement à la façon de travailler avec GroupDocs.Comparison pour l'API Java dans votre application."
        
      # more_overview_loop
      - title: "Compatibilité"
        content: "GroupDocs.Comparison for Java ne nécessite l'installation d'aucun logiciel externe sur le système. Il est compatible avec toutes les versions de Java et prend en charge les systèmes d'exploitation courants (Windows, Linux, MacOS) capables d'exécuter l'environnement d'exécution Java."
    examples:
      enable: true
      
    more_feature:
      # more_feature_loop
      - title: "Comparez facilement des documents à l'aide de l'API Java"
        content: |
          Grâce à l'API GroupDocs.Comparison for Java, vous pouvez facilement comparer des documents de formats pris en charge pour trouver les différences entre eux. L'exemple suivant montre comment comparer deux documents Microsoft Word à l'aide de Java :
          
          ```java
          try (Comparer comparer = new Comparer("D:\\source.pdf")) {
              comparer.add("D:\\target.pdf");
              comparer.compare("D:\\result.pdf");
          }
          ```
      # more_feature_loop
      - title: "Spécifier le niveau de détail de la comparaison"
        content: "GroupDocs.Comparison for Java vous permet de comparer des documents à trois niveaux de profondeur. Vous pouvez définir l'intensité de la comparaison sur faible (comparez le texte mot par mot avec une précision pour la grille d'imagerie = 50), moyenne (comparez le texte caractère par caractère avec une précision pour la grille d'imagerie = 100) ou élevée (comparez le texte caractère par caractère avec une précision pour l'imagerie). grille = 150)."

      # more_feature_loop
      - title: "Comparer le style de texte"
        content: "Outre le contenu du document, l'API GroupDocs.Comparison for Java permet également de comparer le style de texte.

        Le nom de la police, la taille, la couleur, le style (gras, italique, souligné, petites majuscules et hyperliens) et, le cas échéant, la sous-couleur peuvent également être comparés pour vérifier les différences entre les documents comparés, pendant que les mots et les caractères sont comparés.  

        Pour la comparaison de paragraphes, l'alignement, l'indentation (retrait gauche, retrait droit), l'espacement (espace après, espace avant), le retrait de la première ligne et l'espacement des lignes peuvent également être comparés.  

        De même, le cas échéant, d'autres sections d'une page peuvent également être comparées via l'API GroupDocs.Comparison for Java. Les sections incluent la distance du pied de page, les marges de la page (gauche, droite, haut et bas), la hauteur de la page, l'orientation de la page, la couleur de la bordure et la largeur de la ligne."
      
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Voici un aperçu de GroupDocs.Comparison for Java :
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Aperçu"
          content: |
            * Comparez les contenus et les styles
            * Obtenez un résumé de comparaison
            * Accepter/rejeter les modifications dans Word
            * Fusionner et comparer 3 fichiers Word
            * Prise en charge des flux
            * Détection du type de fichier via Stream
            * Comparez les fichiers protégés
            * Comparez les fichiers cryptés
            * Enregistrer la comparaison sous forme d'image
            * Comparez une page spécifique dans Word
            * Comparez le filigrane en PDF
            * Appliquer/annuler les modifications
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison for Java prend en charge tous les [formats de fichiers de documents](https://docs.groupdocs.com/comparison/java/supported-document-formats/) populaires, notamment : Microsoft Office, images, diagrammes et bien d'autres. .
        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** [DOC](https://products.groupdocs.com/comparison/java/doc/), [DOCX](https://products.groupdocs.com/comparison/java/docx/), [DOCM](https://products.groupdocs.com/comparison/java/docm/), [DOT](https://products.groupdocs.com/comparison/java/dot/), [DOTX](https://products.groupdocs.com/comparison/java/dotx/), [DOTM](https://products.groupdocs.com/comparison/java/dotm/), [RTF](https://products.groupdocs.com/comparison/java/rtf/), [TXT](https://products.groupdocs.com/comparison/java/txt/)
                * **Excel:** [XLS](https://products.groupdocs.com/comparison/java/xls/), [XLSX](https://products.groupdocs.com/comparison/java/xlsx/), [XLSM](https://products.groupdocs.com/comparison/java/xlsm/), [XLSB](https://products.groupdocs.com/comparison/java/xlsb/), [XLTM](https://products.groupdocs.com/comparison/java/xltm/), [XLT](https://products.groupdocs.com/comparison/java/xlt/), [XLTM](https://products.groupdocs.com/comparison/java/xltm/), [XLTX](https://products.groupdocs.com/comparison/java/xltx/), [XLAM](https://products.groupdocs.com/comparison/java/xlam/), [SXC](https://products.groupdocs.com/comparison/java/sxc/), [SpreadsheetML](https://products.groupdocs.com/comparison/java/xml/)
                * **PowerPoint:** [PPT](https://products.groupdocs.com/comparison/java/ppt/), [PPTX](https://products.groupdocs.com/comparison/java/pptx/), [PPS](https://products.groupdocs.com/comparison/java/pps/), [PPSX](https://products.groupdocs.com/comparison/java/ppsx/), [PPSM](https://products.groupdocs.com/comparison/java/ppsm/), [POT](https://products.groupdocs.com/comparison/java/pot/), [POTM](https://products.groupdocs.com/comparison/java/potm/), [POTX](https://products.groupdocs.com/comparison/java/potx/), [PPTM](https://products.groupdocs.com/comparison/java/pptm/)
                * **Visio:** [VSD](https://products.groupdocs.com/comparison/java/vsd/), [VDX](https://products.groupdocs.com/comparison/java/vdx/), [VSS](https://products.groupdocs.com/comparison/java/vss/), [VSSX](https://products.groupdocs.com/comparison/java/vssx/), [VSX](https://products.groupdocs.com/comparison/java/vsx/), [VST](https://products.groupdocs.com/comparison/java/vst/), [VSTX](https://products.groupdocs.com/comparison/java/vstx/), [VTX](https://products.groupdocs.com/comparison/java/vtx/), [VSDX](https://products.groupdocs.com/comparison/java/vsdx/), [VDW](https://products.groupdocs.com/comparison/java/vdw/), [VSTM](https://products.groupdocs.com/comparison/java/vstm/), [VSSM](https://products.groupdocs.com/comparison/java/vssm/), [VSDM](https://products.groupdocs.com/comparison/java/vsdm/)
                * **Outlook:** [MSG](https://products.groupdocs.com/comparison/java/msg/), [EML](https://products.groupdocs.com/comparison/java/eml/), [EMLX](https://products.groupdocs.com/comparison/java/emlx/), [PST](https://products.groupdocs.com/comparison/java/pst/), [OST](https://products.groupdocs.com/comparison/java/ost/)
                * **OneNote:** [ONE](https://products.groupdocs.com/comparison/java/one/)

        right:
          enable: true
          table:
            # table loop
            - title: "Autres formats"
              content: |
                * **Langages de programmation**: [CS](https://products.groupdocs.com/comparison/java/cs/), [Java](https://products.groupdocs.com/comparison/java/java/), [CPP](https://products.groupdocs.com/comparison/java/cpp/), [JS](https://products.groupdocs.com/comparison/java/js/), [PY](https://products.groupdocs.com/comparison/java/py/), [RB](https://products.groupdocs.com/comparison/java/rb/), [PL](https://products.groupdocs.com/comparison/java/pl/), [ASM](https://products.groupdocs.com/comparison/java/asm/), [GROOVY](https://products.groupdocs.com/comparison/java/groovy/), [JSON](https://products.groupdocs.com/comparison/java/json/), [PHP](https://products.groupdocs.com/comparison/java/php/), [SQL](https://products.groupdocs.com/comparison/java/sql/), [LOG](https://products.groupdocs.com/comparison/java/log/), [DIFF](https://products.groupdocs.com/comparison/java/diff/), [LESS](https://products.groupdocs.com/comparison/java/less/), [SCALA](https://products.groupdocs.com/comparison/java/scala/)
                * **OpenDocument**: [ODT](https://products.groupdocs.com/comparison/java/odt/), [OTT](https://products.groupdocs.com/comparison/java/ott/), [ODS](https://products.groupdocs.com/comparison/java/ods/), [ODP](https://products.groupdocs.com/comparison/java/odp/), [OTP](https://products.groupdocs.com/comparison/java/otp/)
                * **Portable**: [PDF](https://products.groupdocs.com/comparison/java/pdf/), [MOBI](https://products.groupdocs.com/comparison/java/mobi/)
                * **AutoCAD**: [DXF](https://products.groupdocs.com/comparison/java/dxf/), [DWG](https://products.groupdocs.com/comparison/java/dwg/)
                * **Email**: [EML](https://products.groupdocs.com/comparison/java/eml/), [EMLX](https://products.groupdocs.com/comparison/java/emlx/), [MSG](https://products.groupdocs.com/comparison/java/msg/)
                * **Images**: [JPEG](https://products.groupdocs.com/comparison/java/jpeg/), [BMP](https://products.groupdocs.com/comparison/java/bmp/), [PNG](https://products.groupdocs.com/comparison/java/png/), [GIF](https://products.groupdocs.com/comparison/java/gif/), [DCM](https://products.groupdocs.com/comparison/java/dcm/), [DICOM](https://products.groupdocs.com/comparison/java/dicom/), [DjVu](https://products.groupdocs.com/comparison/java/djvu/)
                * **Web**: [HTM](https://products.groupdocs.com/comparison/java/htm/), [HTML](https://products.groupdocs.com/comparison/java/html/), [MHTML](https://products.groupdocs.com/comparison/java/mhtml/)
                * **Text**: [TXT](https://products.groupdocs.com/comparison/java/txt/)

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Comparison for Java prend en charge les systèmes d'exploitation, les frameworks et les gestionnaires de packages suivants :
      
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Systèmes d'exploitation"
              content: |
                * Microsoft Windows Desktop
                * Microsoft Windows Server
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "Cadres pris en charge"
              content: |
                * Java 7 (1.7) ou plus

        right:
          enable: true
          table:
            
            # table loop
            - icon: "fas fa-cogs"
              title: "Environnements de développement"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse
            # table loop
            - icon: "fas fa-tools"
              title: "Outil d'automatisation de construction"
              content: |
                * Maven

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Comparison for Java Fonctionnalités"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "[Comparez et identifiez les changements dans le style du contenu et du texte](https://docs.groupdocs.com/comparison/java/compare-documents/)"

      # feature loop
      - icon: "fas fa-eye"
        content: "[Enregistrer la liste de comparaison résumée des documents comparés](https://docs.groupdocs.com/comparison/java/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-bolt"
        content: "[Comparez des pages spécifiques de documents Word](https://docs.groupdocs.com/comparison/java/accept-or-reject-detected-changes/)"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "[Fusionnez jusqu'à 3 fichiers Microsoft Word pour comparer avec la prise en charge du « Suivi des modifications »](https://docs.groupdocs.com/comparison/java/compare-multiple-documents-with-specific-compare-settings/)"

      # feature loop
      - icon: "fas fa-code"
        content: "[Repérez facilement quelles modifications proviennent de quel document lors de la comparaison](https://docs.groupdocs.com/comparison/java/get-list-of-changes/)"

      # feature loop
      - icon: "fas fa-cloud"
        content: "[Prise en charge de la lecture des documents sources et de l'envoi du document résultant via des flux](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "[Détecter le type de format de fichier lors de la récupération à partir du flux](https://docs.groupdocs.com/comparison/java/get-file-info/)"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "[Comparez les documents protégés par mot de passe](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/)"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "[Enregistrer le résultat de la comparaison sous forme d'image](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-border-all"
        content: "[Comparez différents formats de fichiers sous forme d'image](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-wrench"
        content: "[Comparer les filigranes dans les documents PDF](https://docs.groupdocs.com/comparison/java/how-to-spot-photos-differences-in-java-or-kotlin/)"

      # feature loop
      - icon: "fas fa-columns"
        content: "[Comparez les documents à partir d'un fichier ou d'un flux et envoyez le document de résultat via un flux ou un fichier](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-file-word"
        content: "[Accepter ou rejeter les modifications après comparaison de fichiers Word, PDF ou Excel](https://docs.groupdocs.com/comparison/java/accept-or-reject-detected-changes/)"

      # feature loop
      - icon: "fas fa-envelope"
        content: "[Comparez les documents cryptés via un fichier ou un flux](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-print"
        content: "[Option de licence limitée pour les opérations de comparaison](https://docs.groupdocs.com/comparison/java/evaluation-limitations-and-licensing-of-groupdocs-comparison/)"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "[Surligner le texte pour les modifications marquées lors de la comparaison de documents PDF, Word, Excel, PowerPoint et Note](https://docs.groupdocs.com/comparison/java/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-lock"
        content: "[Calculer les coordonnées correctes des modifications dans les diapositives et diagrammes PDF, PowerPoint](https://docs.groupdocs.com/comparison/java/get-changes-coordinates/)"

      # feature loop
      - icon: "fas fa-file-code"
        content: "[Comparez plusieurs (plus de deux) documents PDF, Excel, OneNote, diagrammes, courrier électronique et texte](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/)"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "[Comparez l'en-tête et le pied de page des formats de fichiers pris en charge](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "[Comparez des documents et enregistrez des pages de documents de différents formats sous forme d'images](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"


############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison propose des API de visualisation de documents pour d'autres environnements de développement populaires"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
          product: "GroupDocs.Comparison"
          platform: ".NET"
          link: "/comparison/net/"

############################# Back to top ###############################
back_to_top:
  enable: true
---