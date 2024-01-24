
---
############################# Static ############################
layout: "format"
date:  2024-01-24T17:58:26
draft: false
lang: en
format: Pdf
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

############################# Head ############################
head_title: "Compare PDFs with Node.js using the Comparison API in JavaScript"
head_description: "Perform PDF file comparisons within Node.js applications using the Comparison API. Analyze variations in content, text, style, images, and document formats, and receive a detailed summary of differences."

############################# Header ############################
title: "PDF files Comparison for C# .NET applications" 
description: ".NET documents comparing API for getting and display info about any distinctions in PDF files at applications based on C#, ASP.NET, VB.NET & .NET Core. Enjoy getting detailed reports quickly and easily."
subtitle: "Document comparing solution" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Free Nuget download"
      link: "https://releases.groupdocs.com/comparison/nodejs-java/"
      
############################# About ############################
about:
    enable: true
    title: "Discover GroupDocs.Comparison for .NET API"
    link: "/comparison/nodejs-java/"
    link_title: "Learn more"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       Get detailed reports about differences at documents of popular formats at your .NET applications. Use GroupDocs.Comparison for .NET APIs by adding a couple lines of code. Developers can easily display PDF, Word Processing, Excel Spreadsheet, Presentation, Visio, Project, Outlook and many other popular document formats in HTML5, image or PDF modes. The document rendering is fast, identical to the original source file, and it does not require installing additional software or any other external libraries.

############################# Steps ############################
steps:
    enable: true
    title: "How to compare multiple PDF files using C#"
    content: |
      It is possible to use <a href='https://products.groupdocs.com/comparison/net/'>GroupDocs.Comparison</a> for getting report about differences in many PDF files.
      
      1. Install <a href='https://www.nuget.org/packages/groupdocs.comparison'>GroupDocs.Comparison for .NET</a> using your favorite package manager.
      2. Provide an instance of Comparer class with full path to first PDF file.
      3. Append at least one other PDF to Comparer.
      4. Get a final report with precisely described differences.
   
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
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java"
        #  loop
        - title: "Documentation"
          link: "https://docs.groupdocs.com/comparison/nodejs-java/"
          
      content: |
        ```csharp {style=abap}

        // Compare multiple documents from local disk

        // Instantiate Comparer providing a first file
        using (Comparer comparer = new Comparer("source.pdf"))
        {
            // Add other files
        	comparer.Add("target1.pdf");
            comparer.Add("target2.pdf");
            comparer.Add("target3.pdf");

            // Get result file with the specified name
            comparer.Compare("result.pdf"); 
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
      link: "https://releases.groupdocs.com/comparison/nodejs-java/"
      color: "red"
        #  loop
    - title: "Licensing"
      link: "https://purchase.groupdocs.com/pricing/comparison/java/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Compare popular file formats using C#"
    exclude: "PDF"
    description: ".NET API for document formats comparison. Stay well-informed about changes at your documents processing them without extra efforts."
    items: 
        # format loop 1
        - name: "Compare PDF Files"
          format: "PDF"
          link: "/comparison/nodejs-java/pdf/"
          description: "Adobe Portable Document Format"

        # format loop 2
        - name: "Compare DOCX Files"
          format: "DOCX"
          link: "/comparison/nodejs-java/docx/"
          description: "Microsoft Word Open XML Document"

        # format loop 3
        - name: "Compare RTF Files"
          format: "RTF"
          link: "/comparison/nodejs-java/rtf/"
          description: "Rich Text File Format"

        # format loop 4
        - name: "Compare TXT Files"
          format: "TXT"
          link: "/comparison/nodejs-java/txt/"
          description: "Plain Text File Format"

        # format loop 5
        - name: "Compare XLSX Files"
          format: "XLSX"
          link: "/comparison/nodejs-java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop 6
        - name: "Compare CSV Files"
          format: "CSV"
          link: "/comparison/nodejs-java/csv/"
          description: "Comma Separated Values File"

        # format loop 7
        - name: "Compare PPTX Files"
          format: "PPTX"
          link: "/comparison/nodejs-java/pptx/"
          description: "PowerPoint Open XML Presentation"

        # format loop 8
        - name: "Compare ODS Files"
          format: "ODS"
          link: "/comparison/nodejs-java/ods/"
          description: "Open Document Spreadsheet"

        # format loop 9
        - name: "Compare ODP Files"
          format: "ODP"
          link: "/comparison/nodejs-java/odp/"
          description: "OpenDocument Presentation File Format"

        # format loop 10
        - name: "Compare ODT Files"
          format: "ODT"
          link: "/comparison/nodejs-java/odt/"
          description: "Open Document Text"

        # format loop 11
        - name: "Compare JPEG Files"
          format: "JPEG"
          link: "/comparison/nodejs-java/jpeg/"
          description: "JPEG Image"

        # format loop 12
        - name: "Compare PNG Files"
          format: "PNG"
          link: "/comparison/nodejs-java/png/"
          description: "Portable Network Graphic"

        # format loop 13
        - name: "Compare GIF Files"
          format: "GIF"
          link: "/comparison/nodejs-java/gif/"
          description: "Graphical Interchange Format File"

        # format loop 14
        - name: "Compare BMP Files"
          format: "BMP"
          link: "/comparison/nodejs-java/bmp/"
          description: "Bitmap File Format"

        # format loop 15
        - name: "Compare HTML Files"
          format: "HTML"
          link: "/comparison/nodejs-java/html/"
          description: "Hyper Text Markup Language"

        # format loop 16
        - name: "Compare MSG Files"
          format: "MSG"
          link: "/comparison/nodejs-java/msg/"
          description: "Microsoft Outlook E-mail Message"

        # format loop 17
        - name: "Compare ONE Files"
          format: "ONE"
          link: "/comparison/nodejs-java/one/"
          description: "Microsoft OneNote"

        # format loop 18
        - name: "Compare VSDX Files"
          format: "VSDX"
          link: "/comparison/nodejs-java/vsdx/"
          description: "Microsoft Visio Drawing"

        # format loop 19
        - name: "Compare CS Files"
          format: "CS"
          link: "/comparison/nodejs-java/cs/"
          description: "CSharp Language"

        # format loop 20
        - name: "Compare Java Files"
          format: "Java"
          link: "/comparison/nodejs-java/java/"
          description: "Java Language"
          
        # format loop 21
        - name: "Compare CPP Files"
          format: "CPP"
          link: "/comparison/nodejs-java/cpp/"
          description: "C++ Language"
---