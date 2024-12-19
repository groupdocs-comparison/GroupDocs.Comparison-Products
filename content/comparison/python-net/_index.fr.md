
---
############################# Static ############################
layout: "landing"
date: 2024-12-19T07:50:02
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
head_title: "Python Outil de comparaison de documents | Analyse de documents"
head_description: "Découvrez la puissance de l'outil de comparaison de documents Python pour une analyse approfondie des documents. S'intègre sans effort à Python pour un suivi complet des modifications."

############################# Header ############################
title: "Comparez les documents avec Python : mettez en évidence les différences"
description: "Utilisez l'API GroupDocs.Comparison pour créer des applications natives en Python avec des fonctionnalités de comparaison personnalisables. Examinez les fichiers, leur contenu et les variations de style selon les formats de documents."
words:
  for: "pour"

actions:
  main: "Obtenez votre téléchargement gratuit de PyPi maintenant"
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
  title: "Comparez les images BMP à l'aide de Python"
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
  description: "Une API conçue pour comparer les types de documents largement utilisés tels que les PDF, les fichiers Microsoft Office, le HTML, les e-mails ou les images dans les applications Python."
  features:
    # feature loop
    - title: "Rapports de sortie complets"
      content: "GroupDocs.Comparison détecte les modifications du contenu du document (caractères, mots, paragraphes, tableaux, graphiques) ainsi que les modifications de style du document. Les utilisateurs reçoivent un rapport détaillé mettant en évidence la nature et le nombre de modifications."

    # feature loop
    - title: "Large gamme de formats de fichiers et de documents"
      content: "L'API GroupDocs.Comparison vous permet de comparer des documents dans des formats tels que PDF, HTML, courrier électronique, Microsoft Office Word, classeurs Excel, fichiers PowerPoint, notes OneNote, diagrammes Visio, documents texte, JPEG, PNG, GIF, images BMP, parmi tant d'autres."

    # feature loop
    - title: "Documentation complète et exemples de code"
      content: "Une documentation approfondie et des exemples de codes pour la bibliothèque Comparison sur diverses plates-formes sont facilement disponibles, simplifiant ainsi l'intégration de l'API GroupDocs.Comparison dans vos applications Python."

    # feature loop
    - title: "Sélectionner et combiner les modifications dans un seul document"
      content: "Si vous possédez plusieurs versions d'un document, vous pouvez compiler de manière sélective les modifications dans un seul nouveau fichier à l'aide de la bibliothèque GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Indépendance de la plateforme"
  description: "GroupDocs.Comparison for Python via .NET est compatible avec les systèmes d'exploitation, frameworks et gestionnaires de packages suivants."
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
    GroupDocs.Comparison for Python via .NET peut fonctionner avec les [formats de fichiers](https://docs.groupdocs.com/comparison/net/supported-document-formats/) suivants.
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
  title: "Capacités de GroupDocs.Comparison for Python via .NET"
  description: "Comparez facilement des PDF, des documents Office, des images et une grande variété d'autres formats."

  items:
    # feature loop
    - icon: "compare"
      title: "Comparaison intuitive de documents"
      content: "Examiner et mettre en évidence les différences entre deux documents."

    # feature loop
    - icon: "note-stack"
      title: "Comparaison de plusieurs documents"
      content: "Inspectez plusieurs documents pour détecter les différences en même temps."

    # feature loop
    - icon: "stacks"
      title: "Prise en charge étendue des formats"
      content: "Compatible avec plus de 50 formats de documents couramment utilisés dans diverses catégories."

    # feature loop
    - icon: "rule"
      title: "Accepter ou refuser les modifications"
      content: "Visualisez les changements avec clarté, en offrant des options d'acceptation ou de rejet des modifications."

    # feature loop
    - icon: "preview"
      title: "Générer des aperçus visuels"
      content: "Créez des aperçus des résultats de comparaison dans des formats d'image."

    # feature loop
    - icon: "two-pager"
      title: "Comparaison de contenu textuel"
      content: "Effectuez des comparaisons ligne par ligne, paragraphe, mot ou caractère pour mettre en évidence les changements."

    # feature loop
    - icon: "format_color_text"
      title: "Détection des modifications de formatage"
      content: "Identifiez les modifications dans les styles et le formatage des documents."

    # feature loop
    - icon: "folder-managed"
      title: "Gestion des métadonnées personnalisables"
      content: "Conservez les métadonnées des fichiers source ou cible, ou autorisez les utilisateurs à définir de nouvelles métadonnées."

    # feature loop
    - icon: "lock"
      title: "Gérer les fichiers protégés par mot de passe"
      content: "Travaillez avec des documents cryptés ou créez des documents sécurisés protégés par un mot de passe."

    # feature loop
    - icon: "select"
      title: "Comparaisons de pages ciblées"
      content: "Sélectionnez et comparez des sections particulières ou des pages individuelles d'un document."

    # feature loop
    - icon: "speaker-notes"
      title: "Gérer la visibilité des commentaires"
      content: "Décidez de révéler ou de dissimuler des commentaires lors de l’examen du document source."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Exemples de code"
  description: "Découvrez des scénarios courants d'utilisation des fonctionnalités de GroupDocs.Comparison for Python via .NET."
  items:
    # code sample loop
    - title: "Comparaison de documents avec protection par mot de passe"
      content: |
        Pour comparer des documents [sécurisés par un mot de passe](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/), vous devez spécifier le mot de passe lors du chargement des documents :
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