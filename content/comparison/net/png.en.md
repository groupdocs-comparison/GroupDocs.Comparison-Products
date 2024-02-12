
---
############################# Static ############################
layout: "format"
date:  2024-02-12T14:32:53
draft: false
lang: en
format: Png
product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "PNG images differences checking by GroupDocs.Comparison for .NET API"
head_description: "GroupDocs.Comparison for .NET allows us to generate precise reports about distinctions at PNG images for applications based on C#, ASP.NET, VB.NET, or .NET Core"

############################# Header ############################
title: "Compare PNG images via C# .NET applications" 
description: "GroupDocs.Comparison for .NET API searches for any differences among PNG files quickly and easily. Improve C#, ASP.NET, VB.NET, and .NET Core applications in order to obtain comparison reports."
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
    title: "Uncover GroupDocs.Comparison for .NET API features"
    link: "/comparison/net/"
    link_title: "Learn more"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison for .NET API designed for comparing multiple PNG images and composing sophisticated reports about any distinctions at such images. It might be used at your .NET applications without installing any third-party software. Use GroupDocs.Comparison for .NET by adding a couple lines of code with many useful features out of the box.

############################# Steps ############################
steps:
    enable: true
    title: "How to compare PNG pictures by C#"
    content: |
      Construct report describes differences in PNG pictures by [GroupDocs.Comparison](https://products.groupdocs.com/comparison/net/)
      
      1. Download and install GroupDocs.Comparison for .NET from [Nuget](https://www.nuget.org/packages/GroupDocs.Comparison)
      2. Instantiate Comparer object providing path to PNG image
      3. Involve other PNG files to be compared
      4. Get final reports showing images alterations
   
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

        // Construct report about changes in PNG images

        // Create Comparer pointing to the first file
        using (Comparer comparer = new Comparer("source.png"))
        {
            // Involve other pictures to comparison process
        	comparer.Add("file_to_compare_1.png");
            comparer.Add("file_to_compare_2.png");
            comparer.Add("file_to_compare_3.png");

            // Enjoy the resulting report
            comparer.Compare("result.png"); 
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
    title: "Compare PNG images by C# and .NET"
    exclude: "PNG"
    description: ".NET API for PNG images comparison. Get information about any alterations in files without extra efforts."
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