
---
############################# Static ############################
layout: "landing"
date: 2024-03-21T15:26:29
draft: false

lang: fr
product: "Comparison"
product_tag: "comparison"
platform: "Net"
platform_tag: "net"

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
head_title: "C# .NET Logiciel de comparaison de documents | diff checker"
head_description: "C# .NET Logiciel pour comparer le style et le contenu des documents. Comparez des documents de différents formats pris en charge pour identifier les modifications entre les fichiers."

############################# Header ############################
title: "Comparez facilement des documents dans vos solutions C# .NET"
description: "Créez C# applications à l'aide d'une API de comparaison de documents flexible qui permet de comparer des fichiers en fonction du contenu et du style dans différents formats de documents."
words:
  for: "pour"

actions:
  main: "Télécharger gratuitement NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Comparison"
  alt: "Licences"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/net/"
  title: "Prêt à démarrer ?"
  description: "Essayez GroupDocs.Comparison fonctionnalités gratuitement ou demandez une licence"

release:
  title: "Version {0} publiée"
  notes: "Découvrez les nouveautés"
  downloads: "Téléchargements"

code:
  title: "Comparez DOCX fichiers dans C#"
  more: "Plus d'exemples"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET"
  install: "dotnet add package GroupDocs.Comparison"
  content: |
    ```csharp {style=abap}   
    // Spécifiez le document source
    using (Comparer comparer = new Comparer("source.docx"))
    {
        // Ajouter un ou plusieurs documents cibles
        comparer.Add("target.docx");

        // Spécifier les options de comparaison
        CompareOptions options = new CompareOptions() 
        {ShowRevisions = false};

        // Effectuez la comparaison et enregistrez le document obtenu
        comparer.Compare("result.docx", options);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison en un coup d'œil"
  description: "API pour comparer les différences entre les documents dans .NET applications"
  features:
    # feature loop
    - title: "Comparaison de fichiers dans C#"
      content: "Détectez les différences entre les fichiers source et cible pour les modifications au niveau des paragraphes, des mots et des caractères. Identifiez les changements de style et de mise en forme tels que le gras, l'italique, le soulignement, les barres barrées, les types de police, etc."

    # feature loop
    - title: "Les formats de fichiers et de documents les plus courants sont pris en charge"
      content: "L'API GroupDocs.Comparison permet de comparer efficacement des documents dans un large éventail de formats, notamment PDF, HTML, e-mails, Microsoft Office documents (Word, Excel, PowerPoint, OneNote, Visio), différents types d'images (JPEG, PNG, GIF, BMP), fichiers texte, etc."

    # feature loop
    - title: "Appliquez ou rejetez facilement les modifications"
      content: "Chaque différence identifiée dans les documents comparés à l'aide de l'API GroupDocs.Comparison peut être appliquée ou rejetée de manière sélective, ce qui permet la personnalisation avant l'exportation vers le document de sortie final."

    # feature loop
    - title: "Rapport de synthèse de comparaison"
      content: "Générez un rapport récapitulatif des différences, détaillant toutes les modifications trouvées dans les documents comparés, et enregistrez-le pour référence."

############################# Platforms ############################
platforms:
  enable: true
  title: "Indépendance de la plateforme"
  description: "GroupDocs.Comparison for .NET prend en charge les systèmes d'exploitation, les frameworks et les gestionnaires de packages suivants"
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
    - title: "VS Code"
      image: "vs_code"
    # platform loop
    - title: "ReSharper"
      image: "resharper"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NuGet"
      image: "nuget"

############################# File formats ############################
formats:
  enable: true
  title: "Formats de fichiers pris en charge"
  description: |
    GroupDocs.Comparison for .NET prend en charge les opérations utilisant les [formats de fichiers] suivants (https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
      content: "Analysez et identifiez les différences entre deux documents."

    # feature loop
    - icon: "note-stack"
      title: "Comparez plusieurs documents"
      content: "Analysez et identifiez simultanément les différences entre plusieurs documents."

    # feature loop
    - icon: "stacks"
      title: "Formats pris en charge"
      content: "Compatible avec plus de 50 formats de documents largement utilisés appartenant à différentes catégories, garantissant une large applicabilité."

    # feature loop
    - icon: "rule"
      title: "Accepter ou rejeter les modifications"
      content: "Affichage visuel clair des modifications détectées, avec des options permettant d'accepter ou de rejeter ces modifications."

    # feature loop
    - icon: "preview"
      title: "Générez des aperçus"
      content: "Possibilité d'enregistrer les résultats de comparaison sous forme d'aperçus d'images pour faciliter la consultation et le partage."

    # feature loop
    - icon: "two-pager"
      title: "Comparaison de contenus"
      content: "Effectuez des comparaisons de textes approfondies à différents niveaux, y compris ligne par ligne, paragraphe, mot et caractère, en mettant en évidence les différences pour plus de clarté."

    # feature loop
    - icon: "format_color_text"
      title: "Comparaison du style et de la mise en forme"
      content: "Détecte et met en évidence les modifications de mise en forme et de style des documents, garantissant ainsi une révision complète."

    # feature loop
    - icon: "folder-managed"
      title: "Paramètres de métadonnées flexibles"
      content: "Préservez les métadonnées des fichiers source ou cible, ou personnalisez-les en fonction des préférences de l'utilisateur."

    # feature loop
    - icon: "lock"
      title: "Protection par mot de passe"
      content: "Analysez les documents protégés par mot de passe et sécurisez le document de sortie à l'aide d'un cryptage par mot de passe pour plus de sécurité."

    # feature loop
    - icon: "select"
      title: "Comparaison sélective de pages"
      content: "Chargez et comparez des sections ou des pages spécifiques d'un document pour une analyse ciblée."

    # feature loop
    - icon: "speaker-notes"
      title: "Afficher les commentaires"
      content: "Choisissez d'afficher ou de masquer les commentaires lors du chargement du document source, afin de mieux contrôler le processus de comparaison."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Exemples de code"
  description: "Quelques cas d'utilisation d'opérations typiques de GroupDocs.Comparison for .NET"
  items:
    # code sample loop
    - title: "Comparaison de documents protégés par mot de passe."
      content: |
        Pour comparer des documents qui sont [protégés par mot de passe](https://docs.groupdocs.com/comparison/net/load-password-protected-documents/), vous devez le spécifier puis charger les documents :
        {{< landing/code title="Comment comparer des documents protégés par mot de passe.">}}
        ```csharp {style=abap}
        // Chargez le document source et spécifiez son mot de passe
        using(Comparer comparer = new Comparer("source.docx", new LoadOptions() {Password = "1234"}))  
        {
            // Chargez le document cible et spécifiez son mot de passe
            comparer.Add("target.docx", new LoadOptions() {Password = "5678"});

            // Enregistrer le résultat de la comparaison dans un fichier spécifié
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Comparaison de plusieurs PDF documents."
      content: |
        GroupDocs.Comparison vous permet de [comparer plus de deux documents](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/). Le fonctionnement est quasiment le même que lors de la comparaison de deux fichiers. Il vous suffit d'ajouter d'autres fichiers cibles à la classe `comparer`.
        {{< landing/code title="Comment comparer trois documents ou plus.">}}
        ```csharp {style=abap}   
        // Charger le document source
        using(Comparer comparer = new Comparer("source.docx") 
        {
            // Spécifiez le deuxième fichier à comparer
            comparer.Add("target2.docx");
            
            // Spécifiez le troisième fichier à comparer
            comparer.Add("target3.docx");
            
            // Enregistrer le résultat de la comparaison dans un fichier spécifié
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---
