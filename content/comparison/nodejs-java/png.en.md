
---
############################# Static ############################
layout: "format"
date:  2024-03-21T15:26:29
draft: false
lang: en
format: Png
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

############################# Head ############################
head_title: "JavaScript API for comparing PNG images."
head_description: "GroupDocs.Comparison for Node.js via Java library represents detailed reports about distinctions in images in PNG format."

############################# Header ############################
title: "PNG images comparison Node.js applications via Java" 
description: "Take advantages of using Node.js API to track changes at PNG files at JavaScript applications. Obtaining detailed reports effortlessly and swiftly."
subtitle: "Solution for files comparing" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Free NPM download"
      link: "https://releases.groupdocs.com/comparison/nodejs-java/"
      
############################# About ############################
about:
    enable: true
    title: "Open GroupDocs.Comparison for Node.js via Java API possibilities"
    link: "/comparison/nodejs-java/"
    link_title: "Learn more"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       Compose full reports about any changes in different versions of PNG documents by your JavaScript applications. No need in any third-party software. Be well-informed about any alterations in versions of your PNG image.

############################# Steps ############################
steps:
    enable: true
    title: "Compose PNG images distinctions reports in JavaScript"
    content: |
      Track PNG documents alterations using reports provided by [GroupDocs.Comparison](https://products.groupdocs.com/comparison/nodejs-java/)
      
      1. Install GroupDocs.Comparison package via [NPM](https://www.npmjs.com/package/@groupdocs/groupdocs.comparison)
      2. Use Comparer class constructor with path to PNG
      3. Add a few PNGs to comparison
      4. Get a report containing info about differences
   
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
        ```javascript {style=abap}

        // Check multiple files to see how they are similar or different

        // Create a Comparer object and give it the first file as input
        const comparer = new groupdocs.comparison.Comparer('first.png');

        // Append more files
        comparer.add('second.png');
        comparer.add('third.png');

        // Fetch the final report
        await comparer.compare('report_full.png');

        console.log('\nDocuments compared successfully.\nCheck output.');
        
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
    title: "Match images in popular formats like PNG using JavaScript"
    exclude: "PNG"
    description: "Use GroupDocs.Comparison for Node.js via Java in order to get information about PNG pictures differences. Detailed reports helps you to be informed about any changes at important data."
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