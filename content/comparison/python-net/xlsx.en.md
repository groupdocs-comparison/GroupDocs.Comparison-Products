
---
############################# Static ############################
layout: "format"
date:  2024-10-01T13:42:44
draft: false
lang: en
format: Xlsx
product: "Comparison"
product_tag: "comparison"
platform: "Python via .NET"
platform_tag: "python-net"

############################# Head ############################
head_title: "Compare XLSX spreadsheet content with the Python API"
head_description: "Easily check differences in MS Excel spreadsheets using our Python API, which generates detailed reports highlighting all distinctions."

############################# Header ############################
title: "XLSX spreadsheet comparison in Python via .NET applications" 
description: "Use the Python document processing library to detect and highlight changes in MS Excel XLSX files within Python via .NET applications. Generate reports quickly and easily."
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
    title: "Discover the benefits of GroupDocs.Comparison"
    link: "/comparison/python-net/"
    link_title: "Learn more"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       Generate comprehensive reports that provide detailed data on changes across various versions of XLSX files using GroupDocs.Comparison. With just a few lines of code, you can seamlessly integrate the API into your Python via .NET applications, without needing additional tools. Analyze differences in sheets, text, styles, or shapes within MS Excel files, and merge the changes into a final XLSX document. Elevate your business workflows with our powerful solutions.

############################# Steps ############################
steps:
    enable: true
    title: "How to compare XLSX files in Python"
    content: |
      Utilize [GroupDocs.Comparison](https://products.groupdocs.com/comparison/python-net/) and Python via .NET to compare XLSX documents
      
      1. Install GroupDocs.Comparison for Python via .NET from [PyPi](https://pypi.org/project/groupdocs-comparison-net/)
      2. Instantiate the Comparer object and provide the path to the first XLSX file
      3. Add additional XLSX files for comparison
      4. Generate and review the comparison results
   
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
            with groupdocs.comparison.Comparer("first.xlsx") as comparer:

                # Add additional files for comparison.
                comparer.add('second.xlsx')
                comparer.add('third.xlsx')

                # Retrieve the final comparison report.
                comparer.compare('report_full.xlsx')

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
    title: "Compare XLSX spreadsheets with Python"
    exclude: "XLSX"
    description: "Easily compare MS Excel XLSX spreadsheets using the GroupDocs.Comparison for Python via .NET API. Gain deep insights into changes in your business data with our detailed reports."
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