
---
############################# Static ############################
layout: "format"
date:  2024-03-22T13:27:35
draft: false
lang: en
format: Gif
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "Java GIF Comparison API - Check GIF Files for Differences"
head_description: "Compare GIF files in Java, J2EE, J2SE applications. Analyze differences summary in content, text & style."

############################# Header ############################
title: "Compare GIF Files in Java" 
description: "Perform content comparison between more than two GIF files in Java. Retrieve a list of differences and save the compared files to a single document."
subtitle: "Documents differences checking framework" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Free Maven download"
      link: "https://releases.groupdocs.com/comparison/java/"
      
############################# About ############################
about:
    enable: true
    title: "Explore the capabilities of GroupDocs.Comparison for Java library"
    link: "/comparison/java/"
    link_title: "Learn more"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison for Java is an intrinsic Java software crafted for comparing multiple images and documents sharing the same format. It assists in identifying variations within paragraphs, words, characters, shapes, and even text styles among the compared documents. With the capability to merge these alterations and export to a final document, it facilitates the comparison and merging of PDFs, Word documents, Excel spreadsheets, PowerPoint presentations, Visio diagrams, Outlook emails, HTML, drawings, and various image file formats—eliminating the necessity for any external libraries.

############################# Steps ############################
steps:
    enable: true
    title: "How to compare several GIF documents using Java"
    content: |
      Use [GroupDocs.Comparison](https://products.groupdocs.com/comparison/java/) to compare multiple GIF files and generate a report detailing their differences
      
      1. Use your preferred package manager to install GroupDocs.Comparison for Java from [Maven](https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/)
      2. Create an instance of the Comparer class setting path to one of GIF files
      3. Add at least one additional GIF to the Comparer instance
      4. Receive a detailed final report outlining the exact differences
   
    code:
      platform: "net"
      copy_title: "Copy"
      install:
        command: |
          <dependencies>
            <dependency>
              <groupId>com.groupdocs</groupId>
              <artifactId>groupdocs-comparison</artifactId>
              <version>{0}</version>
            </dependency>
          </dependencies>

          <repositories>
            <repository>
              <id>repository.groupdocs.com</id>
              <name>GroupDocs Repository</name>
              <url>https://repository.groupdocs.com/repo/</url>
            </repository>
          </repositories>
        copy_tip: "click to copy"
        copy_done: "copied"
      links:
        #  loop
        - title: "More examples"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
        #  loop
        - title: "Documentation"
          link: "https://docs.groupdocs.com/comparison/java/"
          
      content: |
        ```java {style=abap}

        // Check files from your hard drive for differences or similarities

        // Create a Comparer object by specifying the initial file
        try (Comparer comparer = new Comparer("source.gif") 
        {
            // Include additional files to comparing
        	comparer.add("target1.gif");
            comparer.add("target2.gif");

            // Get the report with the specified name as the result
            final Path resultPath = comparer.compare("result.gif"); 

            System.out.println("\nDocuments compared successfully.");
        }
        
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "Ready to get started?"
  description: "Try GroupDocs.Comparison features for free or request a license"
  items:
    #  loop
    - title: "Maven download"
      link: "https://releases.groupdocs.com/comparison/java/"
      color: "red"
        #  loop
    - title: "Licensing"
      link: "https://purchase.groupdocs.com/pricing/comparison/java/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Compare various documents using Java"
    exclude: "GIF"
    description: "Our Java solutions allows you to compare documents of various formats. Stay updated on document changes by processing them effortlessly."
    items: 
        # format loop 1
        - name: "Compare PDF Files"
          format: "PDF"
          link: "/comparison/java/pdf/"
          description: "Adobe Portable Document Format"

        # format loop 2
        - name: "Compare DOCX Files"
          format: "DOCX"
          link: "/comparison/java/docx/"
          description: "Microsoft Word Open XML Document"

        # format loop 3
        - name: "Compare RTF Files"
          format: "RTF"
          link: "/comparison/java/rtf/"
          description: "Rich Text File Format"

        # format loop 4
        - name: "Compare TXT Files"
          format: "TXT"
          link: "/comparison/java/txt/"
          description: "Plain Text File Format"

        # format loop 5
        - name: "Compare XLSX Files"
          format: "XLSX"
          link: "/comparison/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop 6
        - name: "Compare CSV Files"
          format: "CSV"
          link: "/comparison/java/csv/"
          description: "Comma Separated Values File"

        # format loop 7
        - name: "Compare PPTX Files"
          format: "PPTX"
          link: "/comparison/java/pptx/"
          description: "PowerPoint Open XML Presentation"

        # format loop 8
        - name: "Compare ODS Files"
          format: "ODS"
          link: "/comparison/java/ods/"
          description: "Open Document Spreadsheet"

        # format loop 9
        - name: "Compare ODP Files"
          format: "ODP"
          link: "/comparison/java/odp/"
          description: "OpenDocument Presentation File Format"

        # format loop 10
        - name: "Compare ODT Files"
          format: "ODT"
          link: "/comparison/java/odt/"
          description: "Open Document Text"

        # format loop 11
        - name: "Compare JPEG Files"
          format: "JPEG"
          link: "/comparison/java/jpeg/"
          description: "JPEG Image"

        # format loop 12
        - name: "Compare PNG Files"
          format: "PNG"
          link: "/comparison/java/png/"
          description: "Portable Network Graphic"

        # format loop 13
        - name: "Compare GIF Files"
          format: "GIF"
          link: "/comparison/java/gif/"
          description: "Graphical Interchange Format File"

        # format loop 14
        - name: "Compare BMP Files"
          format: "BMP"
          link: "/comparison/java/bmp/"
          description: "Bitmap File Format"

        # format loop 15
        - name: "Compare HTML Files"
          format: "HTML"
          link: "/comparison/java/html/"
          description: "Hyper Text Markup Language"

        # format loop 16
        - name: "Compare MSG Files"
          format: "MSG"
          link: "/comparison/java/msg/"
          description: "Microsoft Outlook E-mail Message"

        # format loop 17
        - name: "Compare ONE Files"
          format: "ONE"
          link: "/comparison/java/one/"
          description: "Microsoft OneNote"

        # format loop 18
        - name: "Compare VSDX Files"
          format: "VSDX"
          link: "/comparison/java/vsdx/"
          description: "Microsoft Visio Drawing"

        # format loop 19
        - name: "Compare CS Files"
          format: "CS"
          link: "/comparison/java/cs/"
          description: "CSharp Language"

        # format loop 20
        - name: "Compare Java Files"
          format: "Java"
          link: "/comparison/java/java/"
          description: "Java Language"
          
        # format loop 21
        - name: "Compare CPP Files"
          format: "CPP"
          link: "/comparison/java/cpp/"
          description: "C++ Language"
---