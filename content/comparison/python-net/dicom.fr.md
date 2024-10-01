
---
############################# Static ############################
layout: "format"
date:  2024-10-01T13:42:41
draft: false
lang: fr
format: Dicom
product: "Comparison"
product_tag: "comparison"
platform: "Python via .NET"
platform_tag: "python-net"

############################# Head ############################
head_title: "Comparez DICOM avec la bibliothèque Python"
head_description: "Avec GroupDocs.Comparison for Python via .NET, générez des rapports de comparaison détaillés pour les applications Python."

############################# Header ############################
title: "Comparez DICOM dans Python" 
description: "GroupDocs.Comparison est une bibliothèque basée sur Python qui vous permet de comparer et d'identifier facilement les différences dans les fichiers DICOM. Boostez l’efficacité de votre solution dans les tâches de comparaison de documents avec cet outil puissant."
subtitle: "Solution de comparaison de fichiers" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Téléchargez gratuitement depuis PyPi"
      link: "https://releases.groupdocs.com/comparison/python-net/"
      
############################# About ############################
about:
    enable: true
    title: "Découvrez les fonctionnalités de GroupDocs.Comparison for Python via .NET"
    link: "/comparison/python-net/"
    link_title: "En savoir plus"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison for Python via .NET est une API conçue pour comparer des images et des documents au même format. Il détecte les différences de paragraphes, de mots, de caractères, de formes et de styles de texte entre les fichiers comparés. Vous pouvez fusionner ces modifications et les enregistrer dans un document final. Il prend en charge une variété de formats, notamment les PDF, les documents Word, les feuilles de calcul Excel, les présentations PowerPoint, les diagrammes Visio, les e-mails Outlook, les fichiers HTML, les dessins et plusieurs formats d'image, le tout sans nécessiter de logiciel supplémentaire.

############################# Steps ############################
steps:
    enable: true
    title: "Comment comparer DICOM à l'aide de Python"
    content: |
      Utilisez [GroupDocs.Comparison](https://products.groupdocs.com/comparison/python-net/) pour comparer les fichiers DICOM et générer des rapports de différences détaillés.
      
      1. Installez GroupDocs.Comparison for Python via .NET via [PyPi](https://pypi.org/project/groupdocs-comparison-net/).
      2. Créez un objet Comparer et chargez le premier fichier DICOM.
      3. Ajoutez le deuxième fichier DICOM au comparateur.
      4. Générez un rapport complet décrivant toutes les différences détectées.
   
    code:
      platform: "python-net"
      copy_title: "Copier"
      install:
        command: "pip install groupdocs-comparison-net"
        copy_tip: "cliquez pour copier"
        copy_done: "copié"
      links:
        #  loop
        - title: "Plus d'exemples"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET/"
        #  loop
        - title: "Documentation"
          link: "https://docs.groupdocs.com/comparison/python-net/"
          
      content: |
        ```python {style=abap}
        def run():

            # Comparez plusieurs fichiers pour voir les similitudes et les différences.

            # Initialisez le comparateur et chargez le premier fichier.
            with groupdocs.comparison.Comparer("source.dicom") as comparer:

                # Ajoutez des fichiers supplémentaires à des fins de comparaison.
                comparer.add('file_v1.dicom')
                comparer.add('file_2023.dicom')

                # Récupérez le rapport de comparaison final.
                comparer.compare('report_new.dicom')

                print("\nFiles are compared.\nCheck result.")
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "Prêt à démarrer ?"
  description: "Essayez GroupDocs.Comparison fonctionnalités gratuitement ou demandez une licence"
  items:
    #  loop
    - title: "PyPi télécharger"
      link: "https://releases.groupdocs.com/comparison/python-net/"
      color: "red"
        #  loop
    - title: "Licences"
      link: "https://purchase.groupdocs.com/pricing/comparison/python-net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Comparez les formats de documents populaires avec Python"
    exclude: "DICOM"
    description: "Notre API Python vous permet de comparer sans effort des documents dans un large éventail de formats, vous permettant ainsi de suivre facilement les modifications et les différences des documents."
    items: 
        # format loop 1
        - name: "Comparer PDF fichiers"
          format: "PDF"
          link: "/comparison/python-net/pdf/"
          description: "Format de document Adobe Portable"

        # format loop 2
        - name: "Comparer DOCX fichiers"
          format: "DOCX"
          link: "/comparison/python-net/docx/"
          description: "Microsoft Word Ouvrir un document XML"

        # format loop 3
        - name: "Comparer RTF fichiers"
          format: "RTF"
          link: "/comparison/python-net/rtf/"
          description: "Format de fichier RTF"

        # format loop 4
        - name: "Comparer TXT fichiers"
          format: "TXT"
          link: "/comparison/python-net/txt/"
          description: "Format de fichier texte brut"

        # format loop 5
        - name: "Comparer XLSX fichiers"
          format: "XLSX"
          link: "/comparison/python-net/xlsx/"
          description: "Feuille de calcul Microsoft Excel Open XML"

        # format loop 6
        - name: "Comparez les fichiers CSV"
          format: "CSV"
          link: "/comparison/python-net/csv/"
          description: "Fichier de valeurs séparées par des virgules"

        # format loop 7
        - name: "Comparer PPTX fichiers"
          format: "PPTX"
          link: "/comparison/python-net/pptx/"
          description: "PowerPoint Présentation Open XML"

        # format loop 8
        - name: "Comparer ODS fichiers"
          format: "ODS"
          link: "/comparison/python-net/ods/"
          description: "Open Document Feuille de calcul"

        # format loop 9
        - name: "Comparez les fichiers ODP"
          format: "ODP"
          link: "/comparison/python-net/odp/"
          description: "OpenDocument Format de fichier de présentation"

        # format loop 10
        - name: "Comparer ODT fichiers"
          format: "ODT"
          link: "/comparison/python-net/odt/"
          description: "Open Document Texte"

        # format loop 11
        - name: "Comparer JPEG fichiers"
          format: "JPEG"
          link: "/comparison/python-net/jpeg/"
          description: "JPEG Photo"

        # format loop 12
        - name: "Comparer PNG fichiers"
          format: "PNG"
          link: "/comparison/python-net/png/"
          description: "Portable Graphique du réseau"

        # format loop 13
        - name: "Comparer GIF fichiers"
          format: "GIF"
          link: "/comparison/python-net/gif/"
          description: "Fichier de format d'échange graphique"

        # format loop 14
        - name: "Comparer BMP fichiers"
          format: "BMP"
          link: "/comparison/python-net/bmp/"
          description: "Format de fichier bitmap"

        # format loop 15
        - name: "Comparer des fichiers HTML"
          format: "HTML"
          link: "/comparison/python-net/html/"
          description: "Langage de balisage Hyper Text"

        # format loop 16
        - name: "Comparer MSG fichiers"
          format: "MSG"
          link: "/comparison/python-net/msg/"
          description: "Message électronique Microsoft Outlook"

        # format loop 17
        - name: "Comparer ONE fichiers"
          format: "ONE"
          link: "/comparison/python-net/one/"
          description: "Microsoft OneNote"

        # format loop 18
        - name: "Comparer VSDX fichiers"
          format: "VSDX"
          link: "/comparison/python-net/vsdx/"
          description: "Dessin Microsoft Visio"

        # format loop 19
        - name: "Comparez les fichiers CS"
          format: "CS"
          link: "/comparison/python-net/cs/"
          description: "Langage CSharp"

        # format loop 20
        - name: "Comparer Java fichiers"
          format: "Java"
          link: "/comparison/python-net/java/"
          description: "Java Langue"
          
        # format loop 21
        - name: "Comparez les fichiers CPP"
          format: "CPP"
          link: "/comparison/python-net/cpp/"
          description: "Langage C++"
---