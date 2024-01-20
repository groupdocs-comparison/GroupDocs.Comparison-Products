
---
############################# Static ############################
layout: "format"
date:  2024-01-19T15:25:57
draft: false
lang: en
format: Dxf
product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET DXF Comparison API - compare documents using C# .NET"
head_description: "GroupDocs.Comparison for .NET provides the API to get detailed documents comparison reports in any type of C#, ASP.NET, VB.NET & .NET Core applications."

############################# Header ############################
title: "DXF files Comparison for C# .NET applications" 
description: ".NET documents comparing API for getting and display info about any distinctions in DXF files at applications based on C#, ASP.NET, VB.NET & .NET Core. Enjoy getting detailed reports quickly and easily."
subtitle: "Document comparing solution" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Free Nuget download"
      link: "https://releases.groupdocs.com/comparison/net/"
      
############################# About ############################
about:
    enable: true
    title: "Discover GroupDocs.Comparison for .NET API"
    link: "/comparison/net/"
    link_title: "Learn more"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       Get detailed reports about differences at documents of popular formats at your .NET applications. Use GroupDocs.Comparison for .NET APIs by adding a couple lines of code. Developers can easily display DXF, Word Processing, Excel Spreadsheet, Presentation, Visio, Project, Outlook and many other popular document formats in HTML5, image or PDF modes. The document rendering is fast, identical to the original source file, and it does not require installing additional software or any other external libraries.

############################# Steps ############################
steps:
    enable: true
    title: "How to compare multiple DXF files using C#"
    content: |
      It is possible to use <a href='https://products.groupdocs.com/comparison/net/'>GroupDocs.Comparison</a> for getting report about differences in many DXF files.
      
      1. Install <a href='https://www.nuget.org/packages/groupdocs.comparison'>GroupDocs.Comparison for .NET</a> using your favorite package manager.
      2. Provide an instance of Comparer class with full path to first DXF file.
      3. Append at least one other DXF to Comparer.
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
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET"
        #  loop
        - title: "Documentation"
          link: "https://docs.groupdocs.com/comparison/net/"
          
      content: |
        ```csharp {style=abap}

        // Compare multiple documents from local disk

        // Instantiate Comparer providing a first file
        using (Comparer comparer = new Comparer("source.dxf"))
        {
            // Add other files
        	comparer.Add("target1.dxf");
            comparer.Add("target2.dxf");
            comparer.Add("target3.dxf");

            // Get result file with the specified name
            comparer.Compare("result.dxf"); 
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
    exclude: "DXF"
    description: ".NET API for document formats comparison. Stay well-informed about changes at your documents processing them without extra efforts."
    items: 
        # format loop 1
        - name: "Compare PDF Files"
          format: "PDF"
          link: "/comparison/net/pdf/"
          description: "Adobe Portable Document Format"

        # format loop 2
        - name: "Compare DOC Files"
          format: "DOC"
          link: "/comparison/net/doc/"
          description: "Microsoft Word Document"

        # format loop 3
        - name: "Compare DOCM Files"
          format: "DOCM"
          link: "/comparison/net/docm/"
          description: "Microsoft Word Macro-Enabled Document"

        # format loop 4
        - name: "Compare DOCX Files"
          format: "DOCX"
          link: "/comparison/net/docx/"
          description: "Microsoft Word Open XML Document"

        # format loop 5
        - name: "Compare DOT Files"
          format: "DOT"
          link: "/comparison/net/dot/"
          description: "Microsoft Word Document Template"

        # format loop 6
        - name: "Compare DOTM Files"
          format: "DOTM"
          link: "/comparison/net/dotm/"
          description: "Microsoft Word Macro-Enabled Template"

        # format loop 7
        - name: "Compare DOTX Files"
          format: "DOTX"
          link: "/comparison/net/dotx/"
          description: "Word Open XML Document Template"

        # format loop 8
        - name: "Compare RTF Files"
          format: "RTF"
          link: "/comparison/net/rtf/"
          description: "Rich Text File Format"

        # format loop 9
        - name: "Compare TXT Files"
          format: "TXT"
          link: "/comparison/net/txt/"
          description: "Plain Text File Format"

        # format loop 10
        - name: "Compare XLS Files"
          format: "XLS"
          link: "/comparison/net/xls/"
          description: "Microsoft Excel Binary File Format"

        # format loop 11
        - name: "Compare XLSX Files"
          format: "XLSX"
          link: "/comparison/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop 12
        - name: "Compare XLTM Files"
          format: "XLTM"
          link: "/comparison/net/xltm/"
          description: "Microsoft Excel macro-enabled template"

        # format loop 13
        - name: "Compare XLSM Files"
          format: "XLSM"
          link: "/comparison/net/xlsm/"
          description: "Microsoft Excel Macro-Enabled Spreadsheet"

        # format loop 14
        - name: "Compare XLSB Files"
          format: "XLSB"
          link: "/comparison/net/xlsb/"
          description: "Microsoft Excel Binary Spreadsheet File"

        # format loop 15
        - name: "Compare CSV Files"
          format: "CSV"
          link: "/comparison/net/csv/"
          description: "Comma Separated Values File"

        # format loop 16
        - name: "Compare PPT Files"
          format: "PPT"
          link: "/comparison/net/ppt/"
          description: "PowerPoint Presentation"

        # format loop 17
        - name: "Compare PPS Files"
          format: "PPS"
          link: "/comparison/net/pps/"
          description: "Microsoft PowerPoint Slide Show"

        # format loop 18
        - name: "Compare PPTX Files"
          format: "PPTX"
          link: "/comparison/net/pptx/"
          description: "PowerPoint Open XML Presentation"

        # format loop 19
        - name: "Compare PPSX Files"
          format: "PPSX"
          link: "/comparison/net/ppsx/"
          description: "PowerPoint Open XML Slide Show"

        # format loop 20
        - name: "Compare POT Files"
          format: "POT"
          link: "/comparison/net/pot/"
          description: "Microsoft PowerPoint template"

        # format loop 21
        - name: "Compare POTX Files"
          format: "POTX"
          link: "/comparison/net/potx/"
          description: "Microsoft PowerPoint Open XML Template"

        # format loop 22
        - name: "Compare ODS Files"
          format: "ODS"
          link: "/comparison/net/ods/"
          description: "Open Document Spreadsheet"

        # format loop 23
        - name: "Compare ODP Files"
          format: "ODP"
          link: "/comparison/net/odp/"
          description: "OpenDocument Presentation File Format"

        # format loop 24
        - name: "Compare OTP Files"
          format: "OTP"
          link: "/comparison/net/otp/"
          description: "Origin Graph Template"

        # format loop 25
        - name: "Compare ODT Files"
          format: "ODT"
          link: "/comparison/net/odt/"
          description: "Open Document Text"

        # format loop 26
        - name: "Compare OTT Files"
          format: "OTT"
          link: "/comparison/net/ott/"
          description: "Open Document Template"

        # format loop 27
        - name: "Compare VST Files"
          format: "VST"
          link: "/comparison/net/vst/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop 28
        - name: "Compare JPEG Files"
          format: "JPEG"
          link: "/comparison/net/jpeg/"
          description: "JPEG Image"

        # format loop 29
        - name: "Compare PNG Files"
          format: "PNG"
          link: "/comparison/net/png/"
          description: "Portable Network Graphic"

        # format loop 30
        - name: "Compare GIF Files"
          format: "GIF"
          link: "/comparison/net/gif/"
          description: "Graphical Interchange Format File"

        # format loop 31
        - name: "Compare BMP Files"
          format: "BMP"
          link: "/comparison/net/bmp/"
          description: "Bitmap File Format"

        # format loop 32
        - name: "Compare HTML Files"
          format: "HTML"
          link: "/comparison/net/html/"
          description: "Hyper Text Markup Language"

        # format loop 33
        - name: "Compare MHT Files"
          format: "MHT"
          link: "/comparison/net/mht/"
          description: "Mime HTML"

        # format loop 34
        - name: "Compare MHTML Files"
          format: "MHTML"
          link: "/comparison/net/mhtml/"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop 35
        - name: "Compare MSG Files"
          format: "MSG"
          link: "/comparison/net/msg/"
          description: "Microsoft Outlook E-mail Message"

        # format loop 36
        - name: "Compare EML Files"
          format: "EML"
          link: "/comparison/net/eml/"
          description: "E-mail Message"

        # format loop 37
        - name: "Compare EMLX Files"
          format: "EMLX"
          link: "/comparison/net/emlx/"
          description: "Apple Mail E-mail File"

        # format loop 38
        - name: "Compare ONE Files"
          format: "ONE"
          link: "/comparison/net/one/"
          description: "Microsoft OneNote"

        # format loop 39
        - name: "Compare VSD Files"
          format: "VSD"
          link: "/comparison/net/vsd/"
          description: "Microsoft Visio 2003-2010 Drawing"

        # format loop 40
        - name: "Compare VSDX Files"
          format: "VSDX"
          link: "/comparison/net/vsdx/"
          description: "Microsoft Visio Drawing"

        # format loop 41
        - name: "Compare VSS Files"
          format: "VSS"
          link: "/comparison/net/vss/"
          description: "Microsoft Visio 2003-2010 Stencil"

        # format loop 42
        - name: "Compare VST Files"
          format: "VST"
          link: "/comparison/net/vst/"
          description: "Microsoft Visio 2003-2010 Template"

        # format loop 43
        - name: "Compare VDX Files"
          format: "VDX"
          link: "/comparison/net/vdx/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop 44
        - name: "Compare CS Files"
          format: "CS"
          link: "/comparison/net/cs/"
          description: "CSharp Language"

        # format loop 45
        - name: "Compare Java Files"
          format: "Java"
          link: "/comparison/net/java/"
          description: "Java Language"
          
        # format loop 46
        - name: "Compare CPP Files"
          format: "CPP"
          link: "/comparison/net/cpp/"
          description: "C++ Language"

        # format loop 47
        - name: "Compare JS Files"
          format: "JS"
          link: "/comparison/net/js/"
          description: "JavaScript Language"

        # format loop 48
        - name: "Compare PY Files"
          format: "PY"
          link: "/comparison/net/py/"
          description: "Python Language"

        # format loop 49
        - name: "Compare RB Files"
          format: "RB"
          link: "/comparison/net/rb/"
          description: "Ruby Language"



---