
---
############################# Static ############################
layout: "format"
date:  2024-01-29T20:57:18
draft: false
lang: en
format: Pdf
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

############################# Head ############################
head_title: "Use JavaScript with the Comparison Node.js API to compare PDF documents."
head_description: "The GroupDocs.Comparison Node.js API generates comprehensive reports detailing differences in PDF documents."

############################# Header ############################
title: "PDF documents comparison for Node.js via Java" 
description: "Utilize our document comparison API in Node.js to detect and showcase differences in PDFs within JavaScript-powered applications. Benefit from swiftly and effortlessly obtaining detailed reports."
subtitle: "Solution for comparing documents" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Free download from NPM"
      link: "https://releases.groupdocs.com/comparison/nodejs-java/"
      
############################# About ############################
about:
    enable: true
    title: "Explore GroupDocs.Comparison for Node.js via Java API features"
    link: "/comparison/nodejs-java/"
    link_title: "Learn more"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       Get detailed reports about differences at documents of popular formats at your .NET applications. Use GroupDocs.Comparison for Node.js via Java APIs by adding a couple lines of code. Developers can easily display PDF, Word Processing, Excel Spreadsheet, Presentation, Visio, Project, Outlook and many other popular document formats in HTML5, image or PDF modes. The document rendering is fast, identical to the original source file, and it does not require installing additional software or any other external libraries.

############################# Steps ############################
steps:
    enable: true
    title: "Getting report about PDFs distinctions in JavaScript"
    content: |
      Track PDF documents changes by reports composed with [GroupDocs.Comparison](https://products.groupdocs.com/comparison/nodejs-java/)
      
      1. Use [NPM](https://www.npmjs.com/package/@groupdocs/groupdocs.comparison) to install GroupDocs.Comparison for Node.js via Java
      2. Call Comparer constructor with PDF file path
      3. Provide another PDF to compare it to first one
      4. Retrieve a final report about files differences
   
    code:
      platform: "net"
      copy_title: "Copy"
      install:
        command: "npm i @groupdocs/groupdocs.comparison"
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

        // Getting report about changes in PDF files

        // Construct Comparer instance with a first file
        using (Comparer comparer = new Comparer("source.pdf"))
        {
            // Add other file or files
        	comparer.Add("target1.pdf");
            comparer.Add("target2.pdf");
            comparer.Add("target3.pdf");

            // Save report to specified path
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
    - title: "NPM download"
      link: "https://releases.groupdocs.com/comparison/nodejs-java/"
      color: "red"
        #  loop
    - title: "Licensing"
      link: "https://purchase.groupdocs.com/pricing/comparison/java/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Compare popular file formats like PDF using JavaScript"
    exclude: "PDF"
    description: "Your PDF files could be compared by our Node.js API quickly. Control document changes effortlessly with detailed reports."
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