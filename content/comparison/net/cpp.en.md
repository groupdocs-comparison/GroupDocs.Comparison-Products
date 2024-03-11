
---
############################# Static ############################
layout: "format"
date:  2024-03-11T15:35:00
draft: false
lang: en
format: Cpp
product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "Compare CPP files with C# Comparison Software"
head_description: "Compare and merge CPP files in C# .NET applications. Retrieve differences summary in content, text & style."

############################# Header ############################
title: "Compare CPP in C# .NET" 
description: ".NET documents comparison API to check for diffs between two versions of CPP files and export to a final document with a detailed summary of the differences between the compared documents."
subtitle: "Document comparison solution" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Free Nuget download"
      link: "https://releases.groupdocs.com/comparison/net/"
      
############################# About ############################
about:
    enable: true
    title: "Discover GroupDocs.Comparison for .NET API advantages"
    link: "/comparison/net/"
    link_title: "Learn more"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison for .NET is a native .NET API designed for comparing multiple images and documents of the same format. It aids in detecting differences within paragraphs, words, characters, shapes, and even the text styles of the compared documents. With the ability to merge these changes and export to a final document, it supports comparison and merging of PDFs, Word documents, Excel spreadsheets, PowerPoint presentations, Visio diagrams, Outlook emails, HTML, drawings, and various image file formats—all without the need for any external libraries.

############################# Steps ############################
steps:
    enable: true
    title: "How to compare multiple CPP files using C#"
    content: |
      It is possible to use [GroupDocs.Comparison](https://products.groupdocs.com/comparison/net/) for getting report about differences in many CPP files.
      
      1. Install GroupDocs.Comparison for .NET from [Nuget](https://www.nuget.org/packages/GroupDocs.Comparison) using your favorite package manager
      2. Provide an instance of Comparer class with full path to initial CPP file
      3. Append at least one other CPP to Comparer
      4. Get a final report with precisely described differences
   
    code:
      platform: "net"
      copy_title: "Copy"
      install:
        command: "dotnet add package GroupDocs.Comparison"
        copy_tip: "click to copy"
        copy_done: "copied"
      links:
        #  loop
        - title: "More examples"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET"
        #  loop
        - title: "Documentation"
          link: "https://docs.groupdocs.com/comparison/net/"
          
      content: |
        ```csharp {style=abap}

        // Compare multiple documents from local disk

        // Instantiate Comparer providing a first file
        using (Comparer comparer = new Comparer("main_document.cpp"))
        {
            // Add other files
        	comparer.Add("modified_1.cpp");
            comparer.Add("modified_2.cpp");

            // Get result file with the specified name
            comparer.Compare("report.cpp"); 
        }
        
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "Ready to get started?"
  description: "Try GroupDocs.Comparison features for free or request a license"
  items:
    #  loop
    - title: "Nuget download"
      link: "https://releases.groupdocs.com/comparison/net/"
      color: "red"
        #  loop
    - title: "Licensing"
      link: "https://purchase.groupdocs.com/pricing/comparison/net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Compare popular file formats using C#"
    exclude: "CPP"
    description: ".NET API for document formats comparison. Stay well-informed about changes at your documents processing them without extra efforts."
    items: 
        # format loop 1
        - name: "Compare PDF Files"
          format: "PDF"
          link: "/comparison/net/pdf/"
          description: "Adobe Portable Document Format"

        # format loop 2
        - name: "Compare DOCX Files"
          format: "DOCX"
          link: "/comparison/net/docx/"
          description: "Microsoft Word Open XML Document"

        # format loop 3
        - name: "Compare RTF Files"
          format: "RTF"
          link: "/comparison/net/rtf/"
          description: "Rich Text File Format"

        # format loop 4
        - name: "Compare TXT Files"
          format: "TXT"
          link: "/comparison/net/txt/"
          description: "Plain Text File Format"

        # format loop 5
        - name: "Compare XLSX Files"
          format: "XLSX"
          link: "/comparison/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop 6
        - name: "Compare CSV Files"
          format: "CSV"
          link: "/comparison/net/csv/"
          description: "Comma Separated Values File"

        # format loop 7
        - name: "Compare PPTX Files"
          format: "PPTX"
          link: "/comparison/net/pptx/"
          description: "PowerPoint Open XML Presentation"

        # format loop 8
        - name: "Compare ODS Files"
          format: "ODS"
          link: "/comparison/net/ods/"
          description: "Open Document Spreadsheet"

        # format loop 9
        - name: "Compare ODP Files"
          format: "ODP"
          link: "/comparison/net/odp/"
          description: "OpenDocument Presentation File Format"

        # format loop 10
        - name: "Compare ODT Files"
          format: "ODT"
          link: "/comparison/net/odt/"
          description: "Open Document Text"

        # format loop 11
        - name: "Compare JPEG Files"
          format: "JPEG"
          link: "/comparison/net/jpeg/"
          description: "JPEG Image"

        # format loop 12
        - name: "Compare PNG Files"
          format: "PNG"
          link: "/comparison/net/png/"
          description: "Portable Network Graphic"

        # format loop 13
        - name: "Compare GIF Files"
          format: "GIF"
          link: "/comparison/net/gif/"
          description: "Graphical Interchange Format File"

        # format loop 14
        - name: "Compare BMP Files"
          format: "BMP"
          link: "/comparison/net/bmp/"
          description: "Bitmap File Format"

        # format loop 15
        - name: "Compare HTML Files"
          format: "HTML"
          link: "/comparison/net/html/"
          description: "Hyper Text Markup Language"

        # format loop 16
        - name: "Compare MSG Files"
          format: "MSG"
          link: "/comparison/net/msg/"
          description: "Microsoft Outlook E-mail Message"

        # format loop 17
        - name: "Compare ONE Files"
          format: "ONE"
          link: "/comparison/net/one/"
          description: "Microsoft OneNote"

        # format loop 18
        - name: "Compare VSDX Files"
          format: "VSDX"
          link: "/comparison/net/vsdx/"
          description: "Microsoft Visio Drawing"

        # format loop 19
        - name: "Compare CS Files"
          format: "CS"
          link: "/comparison/net/cs/"
          description: "CSharp Language"

        # format loop 20
        - name: "Compare Java Files"
          format: "Java"
          link: "/comparison/net/java/"
          description: "Java Language"
          
        # format loop 21
        - name: "Compare CPP Files"
          format: "CPP"
          link: "/comparison/net/cpp/"
          description: "C++ Language"
---