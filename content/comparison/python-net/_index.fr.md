
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: fr
product: "Comparison"
product_tag: "comparison"
platform: "Python via .NET"
platform_tag: "python-net"

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
    # supported_platforms loop
    - title: "Python"
      tag: "python-net"

############################# Head ############################
head_title: "Python API de comparaison de documents | vérificateur de différences"
head_description: "L'API de comparaison de documents Python offre des outils efficaces pour comparer des documents. S'intègre parfaitement à Python pour un suivi instantané des modifications"

############################# Header ############################
title: "Comparez les documents avec Python : mettez en évidence les différences"
description: "Utilisez l'API GroupDocs.Comparison pour développer des applications Python natives avec des fonctionnalités de comparaison hautement configurables. Comparez les fichiers, leur contenu et les styles de texte entre des formats de documents similaires."
words:
  for: "pour"

actions:
  main: "Téléchargement gratuit de PyPi"
  main_link: "https://pypi.org/project/groupdocs-comparison-net/"
  alt: "Licences"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/python-net/"
  title: "Prêt à démarrer ?"
  description: "Essayez GroupDocs.Comparison fonctionnalités gratuitement ou demandez une licence"

release:
  title: "Version {0} publiée"
  notes: "Découvrez les nouveautés"
  downloads: "Téléchargements"

code:
  title: "Comparez les images BMP dans Python"
  more: "Plus d'exemples"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET/"
  install: "pip install groupdocs-comparison-net"
  content: |
    ```python {style=abap}
    def run():

        # Spécifiez le document source
        with groupdocs.comparison.Comparer("in.bmp") as comparer:

            # Ajouter un ou plusieurs documents cibles
            comparer.add("target.bmp")

            # Spécifier les options de comparaison
            options = new groupdocs.comparison.CompareOptions()
            options.setGenerateSummaryPage(false)

            # Comparer et enregistrer le résultat
            comparer.compare("result.bmp", options)
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison en un coup d'œil"
  description: "Une API pour comparer les types de documents courants tels que PDF, Microsoft Office, HTML, e-mails ou images dans les applications Python."
  features:
    # feature loop
    - title: "Rapports de sortie détaillés"
      content: "GroupDocs.Comparison identifie les modifications apportées au contenu du document (caractères, mots, paragraphes, tableaux, graphiques) ainsi que les modifications apportées au style du document. Il fournit aux utilisateurs un rapport contenant des informations détaillées sur les différences, notamment leur nombre et leur type."

    # feature loop
    - title: "Prend en charge les formats de fichiers et de documents populaires"
      content: "Avec l'API GroupDocs.Comparison, vous pouvez comparer efficacement des documents dans des formats tels que PDF, HTML, courrier électronique, Microsoft Office Word, feuilles de calcul Excel, présentations PowerPoint, OneNote, diagrammes Visio, fichiers texte, JPEG, PNG, GIF, images BMP, et bien d'autres formats."

    # feature loop
    - title: "Documentation complète et exemples"
      content: "Une documentation complète et des exemples de code pour l'utilisation de la bibliothèque Comparison sur différentes plates-formes sont disponibles, ce qui facilite l'intégration de l'API GroupDocs.Comparison dans votre application Python."

    # feature loop
    - title: "Sélectionner et fusionner les modifications en un seul fichier"
      content: "Si vous disposez de différentes versions d'un document, vous pouvez sélectionner des modifications spécifiques et compiler un nouveau document à l'aide de la bibliothèque GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Indépendance de la plateforme"
  description: "GroupDocs.Comparison for Python via .NET prend en charge les systèmes d'exploitation, frameworks et gestionnaires de packages suivants"
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
    GroupDocs.Comparison for Python via .NET prend en charge les opérations avec les [formats de fichiers](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
  title: "GroupDocs.Comparison for Python via .NET Fonctionnalités"
  description: "Comparez facilement les documents, images et autres formats PDF et Office."

  items:
    # feature loop
    - icon: "compare"
      title: "Comparaison de documents conviviale"
      content: "Analyser et identifier les différences entre deux documents."

    # feature loop
    - icon: "note-stack"
      title: "Comparer plusieurs documents"
      content: "Analysez et identifiez les différences au sein de plusieurs documents simultanément."

    # feature loop
    - icon: "stacks"
      title: "Formats pris en charge"
      content: "Prend en charge plus de 50 formats de documents populaires de diverses catégories."

    # feature loop
    - icon: "rule"
      title: "Accepter ou refuser les modifications"
      content: "Représentation visuelle claire des modifications identifiées, avec la possibilité d'accepter ou de rejeter les modifications."

    # feature loop
    - icon: "preview"
      title: "Générer des aperçus"
      content: "Enregistrez les résultats de la comparaison sous forme d’images."

    # feature loop
    - icon: "two-pager"
      title: "Comparaison de contenu"
      content: "Comparez le contenu du texte ligne par ligne, par paragraphes, par mots ou par caractères. Mettez en surbrillance les changements."

    # feature loop
    - icon: "format_color_text"
      title: "Comparaison des styles"
      content: "Détectez les changements de formatage et de styles."

    # feature loop
    - icon: "folder-managed"
      title: "Définir les métadonnées"
      content: "Conservez les métadonnées des fichiers source ou cible, ou autorisez leur spécification par les utilisateurs."

    # feature loop
    - icon: "lock"
      title: "Mot de passe de protection"
      content: "Analysez les documents cryptés ou sécurisez le document obtenu avec un mot de passe."

    # feature loop
    - icon: "select"
      title: "Comparer des pages spécifiques"
      content: "Chargez et comparez des sections ou des pages spécifiques d’un document."

    # feature loop
    - icon: "speaker-notes"
      title: "Afficher les commentaires"
      content: "Choisissez de masquer ou d'afficher les commentaires lors du chargement du document source."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Exemples de code"
  description: "Explorez les cas d'utilisation typiques des opérations GroupDocs.Comparison for Python via .NET"
  items:
    # code sample loop
    - title: "Comparaison de documents protégés par mot de passe"
      content: |
        Pour comparer des documents [protégés par un mot de passe](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/), vous devez spécifier le mot de passe lors du chargement des documents :
        {{< landing/code title="Comment comparer des documents protégés par mot de passe.">}}
        ```python {style=abap}
        def run():

            # Chargez le document source et spécifiez son mot de passe
            with groupdocs.comparison.Comparer("source.docx", new LoadOptions("1234")) as comparer:

                # Chargez le document cible et spécifiez son mot de passe
                comparer.add("target.docx", new LoadOptions("5678"));

                # Enregistrer le résultat de la comparaison dans un fichier spécifié
                comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Comparaison de plusieurs PDF documents."
      content: |
        GroupDocs.Comparison vous permet de [comparer plus de deux documents](https://docs.groupdocs.com/comparison/python-net/compare-multiple-documents/). Le fonctionnement est quasiment le même que lors de la comparaison de deux fichiers. Il vous suffit d'ajouter d'autres fichiers cibles à la classe `comparer`.
        {{< landing/code title="Comment comparer trois documents ou plus.">}}
        ```python {style=abap}
        def run():

            # Charger le document source
            with groupdocs.comparison.Comparer(source.pdf") as comparer:

                # Spécifiez le deuxième fichier à comparer
                comparer.add("target2.pdf");

                # Spécifiez le troisième fichier à comparer
                comparer.add("target3.pdf");

                # Enregistrer le résultat de la comparaison dans un fichier spécifié
                comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---