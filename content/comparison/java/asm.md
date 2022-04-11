---
############################# Static ############################
layout: "auto-gen"
date: 2021-05-13T12:45:11+03:00
draft: false

############################# Head ############################
head_title: "Java ASM Comparison API - Compare ASM Files for Differences"
head_description: "Compare and merge ASM files in Java, J2EE, J2SE applications. Analyse differences summary in content, text &amp; style of ASM files, images and document formats."

############################# Header ############################
title: "Compare ASM Files in Java"
description: "Perform a line-by-line comparison between more than two ASM files in Java. Retrieve a list of differences and save the compared files to a single document."
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Free Trial"
    link: "https://downloads.groupdocs.com/comparison/java"

############################# SubMenu ############################
submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Comparison for Java"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-comparison-java.png"
        product: "GroupDocs.Comparison"
        platform: "Java"

    middle:
        button:

            # button loop
            - link: "https://apireference.groupdocs.com/comparison/java"
              text: "API Reference"

            # button loop
            - link: "https://github.com/groupdocs-comparison"
              text: "Code Examples"

            # button loop
            - link: "https://products.groupdocs.app/comparison/family"
              text: "Live Demos"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/java"
              text: "Pricing"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/java"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: "About GroupDocs.Comparison for Java API"
    content: |
        Empower your Java applications with images and documents comparison features using [GroupDocs.Comparison for Java](/comparison/java/) API. It helps you identify the differences within paragraphs, words, characters, shapes, even the text styles of the compared documents of same format, allows merging the changes and export to a final document. It supports comparing and merging a wide range of documents including PDF, Word, Excel worksheets, PowerPoint presentations, Visio diagrams, Outlook emails, HTML, drawings and image file formats without using any external library.

############################# Steps ############################
steps:
    enable: true
    title_left: "Steps for Comparing ASM Files in Java"
    content_left: |
        [GroupDocs.Comparison](/comparison/java/) makes it easy for Java developers to compare ASM files within their applications using a few lines of code.

        *   Instantiate **Comparer** object with source document path or stream.
        *   Call add method and specify target document path or stream.
        *   Call compare method.
        
    title_right: "System Requirements"
    content_right: |
        GroupDocs.Comparison for Java APIs are supported on all major platforms and operating systems. Before executing the code below, please make sure that you have the following prerequisites installed on your system.

        *   Operating Systems: Microsoft Windows, Linux, MacOS
        *   Development Environment: NetBeans, Intellij IDEA, Eclipse etc
        *   Java Runtime Environment: J2SE 6.0 and above
        *   Get the latest version of GroupDocs.Comparison for Java from [Maven](https://repository.groupdocs.com/webapp/#/artifacts/browse/tree/General/repo/com/groupdocs/groupdocs-comparison)
        
    code: |
        ```java
        // Compare documents from local file
        
        try (Comparer comparer = new Comparer("C:\\source.asm")) {
            comparer.add("C:\\target.asm");
            comparer.compare("C:\\result.asm");
        }
        
        // Compare documents from stream
        
        try (Comparer comparer = new Comparer(new FileInputStream("C:\\source.asm"))) {
            comparer.add(new FileInputStream("C:\\target.asm"));
            comparer.compare(new FileOutputStream("C:\\result.asm"));
        }
        ```
        
############################# Demos ############################
demos:
    enable: true
    title: "Live Demos to Compare ASM Files"
    content: |
        Compare ASM files right now by visiting [GroupDocs.Comparison Live Demos](https://products.groupdocs.app/comparison/family) website.  
        The live demo has the following benefits
        


############################# More Formats ############################
more_formats:
    enable: true
    title: "Compare Other File Formats"
    content: |
        Multi format images & documents comparison API for Java. Compare some of the popular file formats below without any external software.
    format: 
        # format loop
        - name: "Compare PDF Files"
          link: "/comparison/java/pdf/"
          description: "Adobe Portable Document Format"

        # format loop
        - name: "Compare DOC Files"
          link: "/comparison/java/doc/"
          description: "Microsoft Word Document"

        # format loop
        - name: "Compare DOCM Files"
          link: "/comparison/java/docm/"
          description: "Microsoft Word Macro-Enabled Document"

        # format loop
        - name: "Compare DOCX Files"
          link: "/comparison/java/docx/"
          description: "Microsoft Word Open XML Document"

        # format loop
        - name: "Compare DOT Files"
          link: "/comparison/java/dot/"
          description: "Microsoft Word Document Template"

        # format loop
        - name: "Compare DOTM Files"
          link: "/comparison/java/dotm/"
          description: "Microsoft Word Macro-Enabled Template"

        # format loop
        - name: "Compare DOTX Files"
          link: "/comparison/java/dotx/"
          description: "Word Open XML Document Template"

        # format loop
        - name: "Compare RTF Files"
          link: "/comparison/java/rtf/"
          description: "Rich Text File Format"

        # format loop
        - name: "Compare TXT Files"
          link: "/comparison/java/txt/"
          description: "Plain Text File Format"

        # format loop
        - name: "Compare XLS Files"
          link: "/comparison/java/xls/"
          description: "Microsoft Excel Binary File Format"

        # format loop
        - name: "Compare XLSX Files"
          link: "/comparison/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop
        - name: "Compare XLTM Files"
          link: "/comparison/java/xltm/"
          description: "Microsoft Excel macro-enabled template"

        # format loop
        - name: "Compare XLSM Files"
          link: "/comparison/java/xlsm/"
          description: "Microsoft Excel Macro-Enabled Spreadsheet"

        # format loop
        - name: "Compare XLSB Files"
          link: "/comparison/java/xlsb/"
          description: "Microsoft Excel Binary Spreadsheet File"

        # format loop
        - name: "Compare CSV Files"
          link: "/comparison/java/csv/"
          description: "Comma Separated Values File"

        # format loop
        - name: "Compare PPT Files"
          link: "/comparison/java/ppt/"
          description: "PowerPoint Presentation"

        # format loop
        - name: "Compare PPS Files"
          link: "/comparison/java/pps/"
          description: "Microsoft PowerPoint Slide Show"

        # format loop
        - name: "Compare PPTX Files"
          link: "/comparison/java/pptx/"
          description: "PowerPoint Open XML Presentation"

        # format loop
        - name: "Compare PPSX Files"
          link: "/comparison/java/ppsx/"
          description: "PowerPoint Open XML Slide Show"

        # format loop
        - name: "Compare POT Files"
          link: "/comparison/java/pot/"
          description: "Microsoft PowerPoint template"

        # format loop
        - name: "Compare POTX Files"
          link: "/comparison/java/potx/"
          description: "Microsoft PowerPoint Open XML Template"

        # format loop
        - name: "Compare ODS Files"
          link: "/comparison/java/ods/"
          description: "Open Document Spreadsheet"

        # format loop
        - name: "Compare ODP Files"
          link: "/comparison/java/odp/"
          description: "OpenDocument Presentation File Format"

        # format loop
        - name: "Compare OTP Files"
          link: "/comparison/java/otp/"
          description: "Origin Graph Template"

        # format loop
        - name: "Compare ODT Files"
          link: "/comparison/java/odt/"
          description: "Open Document Text"

        # format loop
        - name: "Compare OTT Files"
          link: "/comparison/java/ott/"
          description: "Open Document Template"

        # format loop
        - name: "Compare VST Files"
          link: "/comparison/java/vst/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare TIFF Files"
          link: "/comparison/java/tiff/"
          description: "Tagged Image File Format"

        # format loop
        - name: "Compare JPEG Files"
          link: "/comparison/java/jpeg/"
          description: "JPEG Image"

        # format loop
        - name: "Compare PNG Files"
          link: "/comparison/java/png/"
          description: "Portable Network Graphic"

        # format loop
        - name: "Compare GIF Files"
          link: "/comparison/java/gif/"
          description: "Graphical Interchange Format File"

        # format loop
        - name: "Compare BMP Files"
          link: "/comparison/java/bmp/"
          description: "Bitmap File Format"

        # format loop
        - name: "Compare HTML Files"
          link: "/comparison/java/html/"
          description: "Hyper Text Markup Language"

        # format loop
        - name: "Compare MHT Files"
          link: "/comparison/java/mht/"
          description: "Mime HTML"

        # format loop
        - name: "Compare MHTML Files"
          link: "/comparison/java/mhtml/"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop
        - name: "Compare MSG Files"
          link: "/comparison/java/msg/"
          description: "Microsoft Outlook E-mail Message"

        # format loop
        - name: "Compare EML Files"
          link: "/comparison/java/eml/"
          description: "E-mail Message"

        # format loop
        - name: "Compare EMLX Files"
          link: "/comparison/java/emlx/"
          description: "Apple Mail E-mail File"

        # format loop
        - name: "Compare ONE Files"
          link: "/comparison/java/one/"
          description: "Microsoft OneNote"

        # format loop
        - name: "Compare VSD Files"
          link: "/comparison/java/vsd/"
          description: "Microsoft Visio 2003-2010 Drawing"

        # format loop
        - name: "Compare VSDX Files"
          link: "/comparison/java/vsdx/"
          description: "Microsoft Visio Drawing"

        # format loop
        - name: "Compare VSS Files"
          link: "/comparison/java/vss/"
          description: "Microsoft Visio 2003-2010 Stencil"

        # format loop
        - name: "Compare VST Files"
          link: "/comparison/java/vst/"
          description: "Microsoft Visio 2003-2010 Template"

        # format loop
        - name: "Compare VDX Files"
          link: "/comparison/java/vdx/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare CS Files"
          link: "/comparison/java/cs/"
          description: "CSharp Language"

        # format loop
        - name: "Compare Java Files"
          link: "/comparison/java/java/"
          description: "Java Language"

        # format loop
        - name: "Compare CPP Files"
          link: "/comparison/java/cpp/"
          description: "C++ Language"

        # format loop
        - name: "Compare JS Files"
          link: "/comparison/java/js/"
          description: "JavaScript Language"

        # format loop
        - name: "Compare PY Files"
          link: "/comparison/java/py/"
          description: "Python Language"

        # format loop
        - name: "Compare RB Files"
          link: "/comparison/java/rb/"
          description: "Ruby Language"


############################# Back to top ###############################
back_to_top:
    enable: true
---
