
---
############################# Static ############################
layout: "format"
date:  2024-10-01T13:42:39
draft: false
lang: en
format: Mhtml
product: "Comparison"
product_tag: "comparison"
platform: "Python via .NET"
platform_tag: "python-net"

############################# Head ############################
head_title: "Compare MHTML with Python Library"
head_description: "With GroupDocs.Comparison for Python via .NET, generate detailed comparison reports for Python applications."

############################# Header ############################
title: "Compare MHTML in Python" 
description: "GroupDocs.Comparison is a Python-based library that allows you to easily compare and identify differences in MHTML files. Boost your solution’s efficiency in document comparison tasks with this powerful tool."
subtitle: "File comparison solution" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Download from PyPi for free"
      link: "https://releases.groupdocs.com/comparison/python-net/"
      
############################# About ############################
about:
    enable: true
    title: "Discover the features of GroupDocs.Comparison for Python via .NET"
    link: "/comparison/python-net/"
    link_title: "Learn more"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison for Python via .NET is an API designed for comparing images and documents in the same format. It detects differences in paragraphs, words, characters, shapes, and text styles between the compared files. You can merge these changes and save them into a final document. It supports a variety of formats including PDFs, Word documents, Excel spreadsheets, PowerPoint presentations, Visio diagrams, Outlook emails, HTML files, drawings, and multiple image formats—all without requiring any additional software.

############################# Steps ############################
steps:
    enable: true
    title: "How to compare MHTML using Python"
    content: |
      Use [GroupDocs.Comparison](https://products.groupdocs.com/comparison/python-net/) to compare MHTML files and generate detailed difference reports.
      
      1. Install GroupDocs.Comparison for Python via .NET via [PyPi](https://pypi.org/project/groupdocs-comparison-net/).
      2. Create a Comparer object and load the first MHTML file.
      3. Add the second MHTML file to the Comparer.
      4. Generate a comprehensive report outlining all detected differences.
   
    code:
      platform: "python-net"
      copy_title: "Copy"
      install:
        command: "pip install groupdocs-comparison-net"
        copy_tip: "click to copy"
        copy_done: "copied"
      links:
        #  loop
        - title: "More examples"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET/"
        #  loop
        - title: "Documentation"
          link: "https://docs.groupdocs.com/comparison/python-net/"
          
      content: |
        ```python {style=abap}
        def run():

            # Compare multiple files to see similarities and differences.

            # Initialize the Comparer and load the first file.
            with groupdocs.comparison.Comparer("source.mhtml") as comparer:

                # Add additional files for comparison.
                comparer.add('file_v1.mhtml')
                comparer.add('file_2023.mhtml')

                # Retrieve the final comparison report.
                comparer.compare('report_new.mhtml')

                print("\nFiles are compared.\nCheck result.")
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "Ready to get started?"
  description: "Try GroupDocs.Comparison features for free or request a license"
  items:
    #  loop
    - title: "PyPi download"
      link: "https://releases.groupdocs.com/comparison/python-net/"
      color: "red"
        #  loop
    - title: "Licensing"
      link: "https://purchase.groupdocs.com/pricing/comparison/python-net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Compare popular document formats with Python"
    exclude: "MHTML"
    description: "Our Python API lets you effortlessly compare documents in a wide range of formats, enabling you to track document changes and differences with ease."
    items: 
        # format loop 1
        - name: "Compare PDF Files"
          format: "PDF"
          link: "/comparison/python-net/pdf/"
          description: "Adobe Portable Document Format"

        # format loop 2
        - name: "Compare DOCX Files"
          format: "DOCX"
          link: "/comparison/python-net/docx/"
          description: "Microsoft Word Open XML Document"

        # format loop 3
        - name: "Compare RTF Files"
          format: "RTF"
          link: "/comparison/python-net/rtf/"
          description: "Rich Text File Format"

        # format loop 4
        - name: "Compare TXT Files"
          format: "TXT"
          link: "/comparison/python-net/txt/"
          description: "Plain Text File Format"

        # format loop 5
        - name: "Compare XLSX Files"
          format: "XLSX"
          link: "/comparison/python-net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop 6
        - name: "Compare CSV Files"
          format: "CSV"
          link: "/comparison/python-net/csv/"
          description: "Comma Separated Values File"

        # format loop 7
        - name: "Compare PPTX Files"
          format: "PPTX"
          link: "/comparison/python-net/pptx/"
          description: "PowerPoint Open XML Presentation"

        # format loop 8
        - name: "Compare ODS Files"
          format: "ODS"
          link: "/comparison/python-net/ods/"
          description: "Open Document Spreadsheet"

        # format loop 9
        - name: "Compare ODP Files"
          format: "ODP"
          link: "/comparison/python-net/odp/"
          description: "OpenDocument Presentation File Format"

        # format loop 10
        - name: "Compare ODT Files"
          format: "ODT"
          link: "/comparison/python-net/odt/"
          description: "Open Document Text"

        # format loop 11
        - name: "Compare JPEG Files"
          format: "JPEG"
          link: "/comparison/python-net/jpeg/"
          description: "JPEG Image"

        # format loop 12
        - name: "Compare PNG Files"
          format: "PNG"
          link: "/comparison/python-net/png/"
          description: "Portable Network Graphic"

        # format loop 13
        - name: "Compare GIF Files"
          format: "GIF"
          link: "/comparison/python-net/gif/"
          description: "Graphical Interchange Format File"

        # format loop 14
        - name: "Compare BMP Files"
          format: "BMP"
          link: "/comparison/python-net/bmp/"
          description: "Bitmap File Format"

        # format loop 15
        - name: "Compare HTML Files"
          format: "HTML"
          link: "/comparison/python-net/html/"
          description: "Hyper Text Markup Language"

        # format loop 16
        - name: "Compare MSG Files"
          format: "MSG"
          link: "/comparison/python-net/msg/"
          description: "Microsoft Outlook E-mail Message"

        # format loop 17
        - name: "Compare ONE Files"
          format: "ONE"
          link: "/comparison/python-net/one/"
          description: "Microsoft OneNote"

        # format loop 18
        - name: "Compare VSDX Files"
          format: "VSDX"
          link: "/comparison/python-net/vsdx/"
          description: "Microsoft Visio Drawing"

        # format loop 19
        - name: "Compare CS Files"
          format: "CS"
          link: "/comparison/python-net/cs/"
          description: "CSharp Language"

        # format loop 20
        - name: "Compare Java Files"
          format: "Java"
          link: "/comparison/python-net/java/"
          description: "Java Language"
          
        # format loop 21
        - name: "Compare CPP Files"
          format: "CPP"
          link: "/comparison/python-net/cpp/"
          description: "C++ Language"
---