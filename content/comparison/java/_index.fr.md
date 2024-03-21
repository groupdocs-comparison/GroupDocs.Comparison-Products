
---
############################# Static ############################
layout: "landing"
date: 2024-03-21T15:26:29
draft: false

lang: fr
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

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
head_title: "Java Bibliothèque de comparaison de documents | diff checker"
head_description: "Logiciel natif Java pour comparer le style et le contenu des documents. Comparez des documents de différents formats pour identifier les différences."

############################# Header ############################
title: "Comparez et vérifiez les différences entre les fichiers à l'aide de l'API Java"
description: "Développez Java applications avec une bibliothèque de comparaison de documents hautement configurable pour comparer des formats de documents similaires, notamment des fichiers, leur contenu et leur style de texte."
words:
  for: "pour"

actions:
  main: "Téléchargement gratuit de Maven"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/"
  alt: "Licences"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/java/"
  title: "Prêt à démarrer ?"
  description: "Essayez GroupDocs.Comparison fonctionnalités gratuitement ou demandez une licence"

release:
  title: "Version {0} publiée"
  notes: "Découvrez les nouveautés"
  downloads: "Téléchargements"

code:
  title: "Comparez DOCX fichiers dans Java"
  more: "Plus d'exemples"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
  install: |
    <dependency>
      <groupId>com.groupdocs</groupId>
      <artifactId>groupdocs-comparison</artifactId>
      <version>{0}</version>
    </dependency>
  content: |
    ```java {style=abap}  
    // Spécifiez le document source
    try (Comparer comparer = new Comparer("source.docx"))
    {    
      // Ajouter un ou plusieurs documents cibles
      comparer.add("target.docx");

      // Spécifier les options de comparaison
      CompareOptions options = new CompareOptions();
      options.setShowRevisions(false);

      // Effectuez la comparaison et enregistrez le document obtenu
      final comparer.compare("result.docx", options);
    }    
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison en un coup d'œil"
  description: "API pour comparer les différences entre les documents dans Java applications"
  features:
    # feature loop
    - title: "Comparaison de fichiers dans Java"
      content: "Détectez les changements entre les fichiers source et cible au niveau des paragraphes, des mots et des caractères. Identifiez les modifications de style et de mise en forme telles que le gras, l'italique, le soulignement, les barrés, les types de police, etc."

    # feature loop
    - title: "Un grand nombre de formats pris en charge"
      content: "Grâce à l'API GroupDocs.Comparison, vous pouvez facilement comparer des documents de différents formats pris en charge. Cela inclut PDF, HTML, e-mail, Microsoft Office Word documents, Excel feuilles de calcul, PowerPoint présentations, OneNote, Visio diagrammes, textes, JPEG, PNG, GIF et BMP images, ainsi que de nombreux autres formats."

    # feature loop
    - title: "Appliquez ou rejetez facilement les modifications"
      content: "Chaque différence entre les documents comparés peut être appliquée ou rejetée, puis exportée vers le document de sortie."

    # feature loop
    - title: "Rapport de synthèse de comparaison"
      content: "Générez un rapport récapitulatif répertoriant toutes les modifications apportées aux documents comparés."

############################# Platforms ############################
platforms:
  enable: true
  title: "Indépendance de la plateforme"
  description: "GroupDocs.Comparison for Java prend en charge les systèmes d'exploitation, les frameworks et les gestionnaires de packages suivants"
  items:
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
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "Maven"
      image: "maven"

############################# File formats ############################
formats:
  enable: true
  title: "Formats de fichiers pris en charge"
  description: |
    GroupDocs.Comparison for Java prend en charge les opérations utilisant les [formats de fichiers] suivants (https://docs.groupdocs.com/comparison/java/supported-document-formats/).
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
  title: "GroupDocs.Comparison fonctionnalités"
  description: "Comparez facilement PDF et des documents, images et autres formats Office"

  items:
    # feature loop
    - icon: "compare"
      title: "Comparaison de documents facile à utiliser"
      content: "Analysez et identifiez facilement les différences entre deux documents."

    # feature loop
    - icon: "note-stack"
      title: "Comparez plusieurs documents"
      content: "Examinez et mettez en évidence simultanément les écarts entre plusieurs documents."

    # feature loop
    - icon: "stacks"
      title: "Formats pris en charge"
      content: "Compatibilité avec plus de 50 formats de documents largement utilisés provenant de différentes catégories."

    # feature loop
    - icon: "rule"
      title: "Accepter ou rejeter les modifications"
      content: "Visualisation claire des modifications identifiées, avec des options permettant d'accepter ou de rejeter les modifications."

    # feature loop
    - icon: "preview"
      title: "Générez des aperçus"
      content: "Possibilité d'enregistrer les résultats de comparaison sous forme d'aperçus d'images."

    # feature loop
    - icon: "two-pager"
      title: "Comparaison de contenus"
      content: "Comparaison approfondie du contenu du texte à différents niveaux, y compris l'analyse ligne par ligne, paragraphe, mot et caractère, en mettant l'accent sur les modifications."

    # feature loop
    - icon: "format_color_text"
      title: "Comparaison de styles"
      content: "Possibilité de détecter et de mettre en évidence les modifications de mise en forme et de style des éléments."

    # feature loop
    - icon: "folder-managed"
      title: "Définir les métadonnées"
      content: "Possibilité de conserver les métadonnées des fichiers source ou cible, ou d'autoriser les paramètres de métadonnées définis par l'utilisateur."

    # feature loop
    - icon: "lock"
      title: "Protection par mot de passe"
      content: "Facilite l'analyse des documents protégés par mot de passe et permet de protéger par mot de passe les documents qui en résultent."

    # feature loop
    - icon: "select"
      title: "Comparez des pages spécifiques"
      content: "Chargez et comparez des sections ou des pages spécifiques d'un document selon les besoins."

    # feature loop
    - icon: "speaker-notes"
      title: "Afficher les commentaires"
      content: "Possibilité d'afficher ou de masquer les commentaires lors du chargement du document source."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Exemples de code"
  description: "Quelques cas d'utilisation d'opérations typiques de GroupDocs.Comparison for Java"
  items:
    # code sample loop
    - title: "Comparaison de documents protégés par mot de passe."
      content: |
        Pour comparer des documents qui sont [protégés par mot de passe](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/), vous devez le spécifier puis charger les documents :
        {{< landing/code title="Comment comparer des documents protégés par mot de passe.">}}
        ```java {style=abap}
        // Chargez le document source et spécifiez son mot de passe
        try (Comparer comparer = new Comparer("source.docx", new LoadOptions("1234")))
        {
            // Chargez le document cible et spécifiez son mot de passe
            comparer.add("target.docx", new LoadOptions("5678"));
        
            // Enregistrer le résultat de la comparaison dans un fichier spécifié
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Comparaison de plusieurs PDF documents."
      content: |
        GroupDocs.Comparison vous permet de [comparer plus de deux documents](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/). Le fonctionnement est quasiment le même que lors de la comparaison de deux fichiers. Il vous suffit d'ajouter d'autres fichiers cibles à la classe `comparer`.
        {{< landing/code title="Comment comparer trois documents ou plus.">}}
        ```java {style=abap}   
        // Charger le document source
        try (Comparer comparer = new Comparer("source.docx") 
        {
            // Spécifiez le deuxième fichier à comparer
            comparer.add("target2.docx");

            // Spécifiez le troisième fichier à comparer
            comparer.add("target3.docx");

            // Enregistrer le résultat de la comparaison dans un fichier spécifié
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---

