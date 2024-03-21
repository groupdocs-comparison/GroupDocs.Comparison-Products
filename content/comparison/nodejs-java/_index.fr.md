
---
############################# Static ############################
layout: "landing"
date: 2024-03-21T15:26:29
draft: false

lang: fr
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

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

############################# Head ############################
head_title: "Node.js API de comparaison de documents | vérificateur de différences"
head_description: "L'API de comparaison de documents Node.js propose des outils efficaces pour comparer des documents. S'intègre parfaitement à Node.js pour un suivi des modifications en temps réel"

############################# Header ############################
title: "Comparez des documents avec Node.js : mettez en évidence les différences"
description: "Utilisez l'API GroupDocs.Comparison pour développer des applications de script natives Java dotées de fonctionnalités de comparaison hautement configurables. Comparez des fichiers, leur contenu et leur style de texte entre des formats de documents similaires."
words:
  for: "pour"

actions:
  main: "Téléchargement gratuit de NPM"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.comparison"
  alt: "Licences"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/java/"
  title: "Prêt à démarrer ?"
  description: "Essayez GroupDocs.Comparison fonctionnalités gratuitement ou demandez une licence"

release:
  title: "Version {0} publiée"
  notes: "Découvrez les nouveautés"
  downloads: "Téléchargements"

code:
  title: "Comparez BMP images dans le script Java"
  more: "Plus d'exemples"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.comparison"
  content: |
    ```javascript {style=abap}

    // Spécifiez le document source
    let comparer = new Comparer("source.bmp");

    // Ajouter un ou plusieurs documents cibles
    comparer.add("target.bmp");

    // Spécifier les options de comparaison
    comparer.compare("result.bmp"); 
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison en un coup d'œil"
  description: "API permettant de comparer différents types de documents tels que PDF, Microsoft Office, HTML, e-mails ou images dans Node.js applications"
  features:
    # feature loop
    - title: "Rapports de sortie détaillés"
      content: "GroupDocs.Comparison identifie les modifications du contenu du document (caractères, mots, paragraphes, tableaux, graphiques), ainsi que les modifications de style du document. Il fournit aux clients un rapport contenant des informations détaillées sur les différences, leur nombre et leur type."

    # feature loop
    - title: "Les formats de fichiers et de documents les plus courants sont pris en charge"
      content: "Avec l'API GroupDocs.Comparison, vous pouvez comparer efficacement des documents de tous les formats pris en charge, tels que PDF, HTML, e-mail, Microsoft Office Word documents, Excel feuilles de calcul, PowerPoint présentations, OneNote, Visio diagrammes, textes, JPEG, PNG, GIF et BMP images ainsi que de nombreux autres formats."

    # feature loop
    - title: "Documentation et exemples"
      content: "Il existe déjà une grande documentation sur l'utilisation de la bibliothèque de comparaison sur différentes plateformes avec des exemples de code. Vous n'avez donc pas à réfléchir sérieusement à la manière de travailler avec l'API GroupDocs.Comparison dans votre application Node.js."

    # feature loop
    - title: "Sélectionnez les modifications et fusionnez-les en un seul fichier"
      content: "Si vous avez différentes versions d'un même document, il est possible de sélectionner uniquement les modifications souhaitées et de compiler un nouveau document à l'aide de la bibliothèque GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Indépendance de la plateforme"
  description: "GroupDocs.Comparison for Node.js via Java prend en charge les systèmes d'exploitation, les frameworks et les gestionnaires de packages suivants"
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
  title: "Formats de fichiers pris en charge"
  description: |
    GroupDocs.Comparison for Node.js via Java prend en charge les opérations utilisant les [formats de fichiers] suivants (https://docs.groupdocs.com/comparison/nodejs-java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### formats Microsoft Office et OpenDocument
        * **Word:** DOCX, DOC, DOCM,DOT, DOTM, DOTX, RTX, RTF, TXT
        * **Excel:** XLSX, XLS, XLT, XLTM, XLSB, XLSM
        * **PowerPoint:** PPTX, PPT, POT, POTX, PPS, PPSX
        * **Outlook:** EML, EMLX, MSG
        * **OneNote:** ONE
        * **OpenDocument:** ODT, ODP, OTP, ODS, OTT
        * **Mise en page fixe:** PDF        
    # group loop
    - color: "blue"
      content: |
        ### Images, graphiques et diagrammes
        * **Images matricielles:** BMP, GIF, JPG, JPEG, PNG
        * **Imagerie médicale:** DICOM
        * **Microsoft Visio:** VSDX, VSD, VSS, VST, VDX
        * **AutoCAD Drawing:** DWG, DXF
      # group loop
    - color: "red"
      content: |
        ### Autres
        * **Texte:** TXT
        * **Langages de programmation:** CS, Java, CPP, JS, PY, RB, PL, ASM, GROOVY, JSON, PHP, SQL, LOG, DIFF, LESS, SCALA
        * **Web:** HTM, HTML, MHT, MHTML
        * **Livres électroniques:** MOBI, DjVu
        * **Valeurs séparées par des délimiteurs:** CSV

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Comparison for Node.js via Java fonctionnalités"
  description: "Comparez facilement PDF et des documents, images et autres formats Office"

  items:
    # feature loop
    - icon: "compare"
      title: "Comparaison de documents facile à utiliser"
      content: "Analysez et identifiez les différences entre deux documents."

    # feature loop
    - icon: "note-stack"
      title: "Comparez plusieurs documents"
      content: "Analysez et identifiez les différences au sein de plusieurs documents simultanément."

    # feature loop
    - icon: "stacks"
      title: "Formats pris en charge"
      content: "Supporte plus de 50 formats de documents populaires de différentes catégories."

    # feature loop
    - icon: "rule"
      title: "Accepter ou rejeter les modifications"
      content: "Représentation visuelle claire des modifications identifiées, offrant la possibilité d'accepter ou de rejeter les modifications."

    # feature loop
    - icon: "preview"
      title: "Générez des aperçus"
      content: "Enregistrez les résultats de la comparaison sous forme d'images."

    # feature loop
    - icon: "two-pager"
      title: "Comparaison de contenus"
      content: "Comparez le contenu du texte ligne par ligne, par paragraphes, par mots, par caractères. Mettez en évidence les modifications."

    # feature loop
    - icon: "format_color_text"
      title: "Comparaison de styles"
      content: "Détectez les modifications de mise en forme et de styles."

    # feature loop
    - icon: "folder-managed"
      title: "Définir les métadonnées"
      content: "Conservez les métadonnées des fichiers source ou cible ou autorisez les utilisateurs à les spécifier."

    # feature loop
    - icon: "lock"
      title: "Protection par mot de passe"
      content: "Analysez les documents cryptés ou sécurisez le document obtenu avec un mot de passe."

    # feature loop
    - icon: "select"
      title: "Comparez des pages spécifiques"
      content: "Chargez uniquement les sections ou pages spécifiques du document."

    # feature loop
    - icon: "speaker-notes"
      title: "Afficher les commentaires"
      content: "Lorsque vous chargez le document source, vous pouvez choisir de masquer ou d'afficher les commentaires."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Exemples de code"
  description: "Quelques cas d'utilisation d'opérations typiques de GroupDocs.Comparison for Node.js via Java"
  items:
    # code sample loop
    - title: "Comparaison de documents protégés par mot de passe."
      content: |
        Pour comparer des documents qui sont [protégés par mot de passe](https://docs.groupdocs.com/comparison/nodejs-java/load-password-protected-documents/), vous devez le spécifier puis charger les documents :
        {{< landing/code title="Comment comparer des documents protégés par mot de passe.">}}
        ```javascript {style=abap}

        import { Comparer, LoadOptions } from '@groupdocs/groupdocs.comparison'

        // Chargez le document source et spécifiez son mot de passe
        const comparer = new Comparer("source.docx", new LoadOptions("1234"));

        // Chargez le document cible et spécifiez son mot de passe
        comparer.add("target.docx", new LoadOptions("5678"));

        // Enregistrer le résultat de la comparaison dans un fichier spécifié
        comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Comparaison de plusieurs PDF documents."
      content: |
        GroupDocs.Comparison vous permet de [comparer plus de deux documents](https://docs.groupdocs.com/comparison/nodejs-java/compare-multiple-documents/). Le fonctionnement est quasiment le même que lors de la comparaison de deux fichiers. Il vous suffit d'ajouter d'autres fichiers cibles à la classe `comparer`.
        {{< landing/code title="Comment comparer trois documents ou plus.">}}
        ```javascript {style=abap}
        import { Comparer } from '@groupdocs/groupdocs.comparison'

        // Charger le document source
        const comparer = new Comparer(source.pdf");

        // Spécifiez le deuxième fichier à comparer
        comparer.add("target2.pdf");

        // Spécifiez le troisième fichier à comparer
        comparer.add("target3.pdf");

        // Enregistrer le résultat de la comparaison dans un fichier spécifié
        comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---