
---
############################# Static ############################
layout: "format"
date:  2024-12-19T07:49:50
draft: false
lang: en
format: Xlsx
product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "MS Excel spreadsheet comparison"
head_description: "The GroupDocs.Comparison for .NET API facilitates checking diffs and analysis of XLSX spreadsheets. C# .NET supported."

############################# Header ############################
title: "Utilize C# technologies for comparing XLSX spreadsheets" 
description: "The .NET API, crafted for various document types comparison, identifies and reports distinctions within MS Excel files. Build applications using C#, ASP.NET, VB.NET, or .NET Core to leverage its advantages. Get detailed reports with minimal code implementation."
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
    title: "Explore the features of GroupDocs.Comparison for .NET API"
    link: "/comparison/net/"
    link_title: "Learn more"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       Detect changes in your XLSX spreadsheets with convenient reporting in your .NET projects. Additionally, retrieve information about styles, shapes, and other content, and merge XSLX spreadsheets into a new document. Integrate GroupDocs.Comparison for .NET APIs into your projects with just a few lines of code. Use our software without the need for third-party developers.

############################# Steps ############################
steps:
    enable: true
    title: "Generate MS Excel XLSX comparison reports using C#"
    content: |
      Create a distinctions report for XLSX files using [GroupDocs.Comparison](https://products.groupdocs.com/comparison/net/)
      
      1. Download and install the GroupDocs.Comparison for .NET package from [Nuget](https://www.nuget.org/packages/GroupDocs.Comparison)
      2. Instantiate the Comparer object by providing the XLSX file path
      3. Include XLSX spreadsheets for comparison
      4. Retrieve the comparison report containing distinctions information
   
    code:
      platform: "net"
      copy_title: "Copy"
      result_enable: true
      result_link: "/examples/comparison/comparison_result.pdf"
      result_title: "Sample result file"
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

        // Generate a report on alterations in XLSX files

        // Instantiate the Comparer object for spreadsheets processing
        using (Comparer comparer = new Comparer("source.xlsx"))
        {
            // Include at least one file for comparison
        	comparer.Add("file_to_compare_1.xlsx");
            comparer.Add("file_to_compare_2.xlsx");
            comparer.Add("file_to_compare_3.xlsx");

            // Analyze the comparison result
            comparer.Compare("result.xlsx"); 
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
    title: "Comparison of MS Excel spreadsheets for C# applications"
    exclude: "XLSX"
    description: "Explore the advantages of GroupDocs.Comparison for .NET for controlling versions of XLSX documents. Quickly and easily gather information from MS Excel spreadsheets for further analysis."
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