
---
############################# Static ############################
layout: "format"
date:  2024-10-01T13:42:44
draft: false
lang: en
format: Pdf
product: "Comparison"
product_tag: "comparison"
platform: "Python via .NET"
platform_tag: "python-net"

############################# Head ############################
head_title: "Compare PDFs via Python library"
head_description: "The GroupDocs.Comparison software for Python generates in-depth reports highlighting differences in PDF documents."

############################# Header ############################
title: "PDF comparison for Python via .NET" 
description: "Leverage our document comparison API in Python to easily identify and display differences in PDF files within Python applications. Get detailed reports quickly and efficiently."
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
    title: "Key features of the GroupDocs.Comparison for Python via .NET Library"
    link: "/comparison/python-net/"
    link_title: "Learn more"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       Generate detailed reports on any differences within PDF documents directly in your Python applications. With just a few lines of code, use GroupDocs.Comparison for Python via .NET without the need for any extra software or libraries. Monitor changes in paragraphs, words, characters, shapes, and text styles within your PDFs. You can also merge changes from multiple document versions into a single result. Process documents quickly and easily, without hassle.

############################# Steps ############################
steps:
    enable: true
    title: "How to get PDF difference reports in Python"
    content: |
      Track changes in PDF documents with reports generated using [GroupDocs.Comparison](https://products.groupdocs.com/comparison/python-net/).
      
      1. Install GroupDocs.Comparison for Python via .NET via [PyPi](https://pypi.org/project/groupdocs-comparison-net/).
      2. Create a Comparer instance and provide the path to the first PDF file.
      3. Add a second PDF file for comparison.
      4. Retrieve the final report detailing the differences between the files.
   
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
            with groupdocs.comparison.Comparer("first.pdf") as comparer:

                # Add additional files for comparison.
                comparer.add('second.pdf')
                comparer.add('third.pdf')

                # Retrieve the final comparison report.
                comparer.compare('report_full.pdf')

                print("\nDocuments compared successfully.\nCheck output.")
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
    title: "Compare common formats like PDF with Python"
    exclude: "PDF"
    description: "Our Python API allows quick and efficient comparison of PDF files. Easily track changes with detailed reports."
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