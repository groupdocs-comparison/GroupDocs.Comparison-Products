---
############################# Static ############################
layout: "auto-gen-comparison"
date: 2021-05-13T12:45:21+03:00
draft: false

############################# Head ############################
head_title: "Compare two JPEG files in .NET | Document Comparison APIs"
head_description: "Compare and merge more than two (JPEG files in C# .NET applications. Retrieve differences summary in content, text &amp; style of JPEG files, images and document formats."

############################# Header ############################
title: "Compare JPEG Files in C# .NET"
description: ".NET documents comparison API to detect the changes between two versions of JPEG files and export to a final document with a detailed summary of the differences between the compared documents."
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Free Trial"
    link: "https://downloads.groupdocs.com/comparison/net"

############################# SubMenu ############################
submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Comparison for .NET"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-comparison-net.png"
        product: "GroupDocs.Comparison"
        platform: ".NET"

    middle:
        button:

            # button loop
            - link: "https://apireference.groupdocs.com/comparison/net"
              text: "API Reference"

            # button loop
            - link: "https://github.com/groupdocs-comparison"
              text: "Code Examples"

            # button loop
            - link: "https://products.groupdocs.app/comparison/family"
              text: "Live Demos"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "Pricing"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/net"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: "About GroupDocs.Comparison for .NET API"
    content: |
        [GroupDocs.Comparison for .NET](/comparison/net/) is a native .NET API for comparing multiple images and documents of the same format. It helps you detect the differences within paragraphs, words, characters, shapes, even the text styles of the compared documents, merge the changes and export to a final document. It supports comparing and merging PDF, Word documents, Excel spreadsheets, PowerPoint presentations, Visio diagrams, Outlook emails, HTML, drawings and image file formats without using any external library.

############################# Steps ############################
steps:
    enable: true
    title_left: "Steps for Comparing JPEG Files in C#"
    content_left: |
        [GroupDocs.Comparison](/comparison/net/) makes it easy for .NET developers to compare & merge multiple JPEG files in their applications by implementing a few easy steps.

        *   Instantiate **Comparer** object with source document path or stream.
        *   Call Add method and specify target document path or stream. Repeat this step for every target document.
        *   Call Compare method.
        
    title_right: "System Requirements"
    content_right: |
        GroupDocs.Comparison for .NET APIs are supported on all major platforms and operating systems. Before executing the code below, please make sure that you have the following prerequisites installed on your system.

        *   Operating Systems: Microsoft Windows, Linux, MacOS
        *   Development Environments: Microsoft Visual Studio, Xamarin, MonoDevelop
        *   Frameworks: .NET Framework, .NET Standard, .NET Core, Mono
        *   Get the latest version of GroupDocs.Comparison for .NET downloaded from [NuGet](https://www.nuget.org/packages/groupdocs.comparison)
        
    code: |
        ```cs
        // Compare multiple documents from local disk
        
        using (Comparer comparer = new Comparer("source.jpeg")
        {
        	comparer.Add("target1.jpeg");
            comparer.Add("target2.jpeg");
            comparer.Add("target3.jpeg");
            comparer.Compare("result.jpeg"); // Create result file with the specified name
        }
        
        // Compare multiple documents from stream
        
        using (Comparer comparer = new Comparer(File.OpenRead("source.jpeg"))
        {
        	comparer.Add(File.OpenRead("target1.jpeg"));
            comparer.Add(File.OpenRead("target2.jpeg"));
            comparer.Add(File.OpenRead("target3.jpeg"));
            comparer.Compare(File.Create("result.jpeg")); // Create result file with the specified name
        }
        ```
        
############################# Demos ############################
demos:
    enable: true
    title: "Live Demos of Comparing JPEG Files"
    content: |
        Detect differences between JPEG files right now by visiting [GroupDocs.Comparison Live Demos](https://products.groupdocs.app/comparison/family) website.  
        The live demo has the following benefits
        
############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-jpeg"
          title: "About JPEG File Format"
          content: |
            A JPEG is a type of image format that is saved using the method of lossy compression. The output image, as result of compression, is a trade-off between storage size and image quality. Users can adjust the compression level to achieve the desired quality level while at the same time reduce the storage size. Image quality is negligibly affected if 10:1 compression is applied to the image. The higher the compression value, the higher the degradation in image quality. JPEG image file format was standardized by the Joint Photographic Experts Group and, hence, the name JPEG. The format has been the choice of storing and transmitting photographic images on the web. Almost all Operating systems now have viewers that support visualization of JPEG images, which are often stored with JPG extension as well. Even the web browsers support visualization of JPEG images.

          link: "https://docs.fileformat.com/image/jpeg/"

############################# More Formats ############################
more_formats:
    enable: true
    title: "Comparing Other File Formats"
    content: |
        Multi format documents and images comparison API for .NET. Analyse the differences between documents of the same format without using any external tool.
    format: 
        # format loop
        - name: "Compare PDF Files"
          link: "https://products.groupdocs.com/comparison/net/pdf/"
          description: "Adobe Portable Document Format"

        # format loop
        - name: "Compare DOC Files"
          link: "https://products.groupdocs.com/comparison/net/doc/"
          description: "Microsoft Word Document"

        # format loop
        - name: "Compare DOCM Files"
          link: "https://products.groupdocs.com/comparison/net/docm/"
          description: "Microsoft Word Macro-Enabled Document"

        # format loop
        - name: "Compare DOCX Files"
          link: "https://products.groupdocs.com/comparison/net/docx/"
          description: "Microsoft Word Open XML Document"

        # format loop
        - name: "Compare DOT Files"
          link: "https://products.groupdocs.com/comparison/net/dot/"
          description: "Microsoft Word Document Template"

        # format loop
        - name: "Compare DOTM Files"
          link: "https://products.groupdocs.com/comparison/net/dotm/"
          description: "Microsoft Word Macro-Enabled Template"

        # format loop
        - name: "Compare DOTX Files"
          link: "https://products.groupdocs.com/comparison/net/dotx/"
          description: "Word Open XML Document Template"

        # format loop
        - name: "Compare RTF Files"
          link: "https://products.groupdocs.com/comparison/net/rtf/"
          description: "Rich Text File Format"

        # format loop
        - name: "Compare TXT Files"
          link: "https://products.groupdocs.com/comparison/net/txt/"
          description: "Plain Text File Format"

        # format loop
        - name: "Compare XLS Files"
          link: "https://products.groupdocs.com/comparison/net/xls/"
          description: "Microsoft Excel Binary File Format"

        # format loop
        - name: "Compare XLSX Files"
          link: "https://products.groupdocs.com/comparison/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop
        - name: "Compare XLTM Files"
          link: "https://products.groupdocs.com/comparison/net/xltm/"
          description: "Microsoft Excel macro-enabled template"

        # format loop
        - name: "Compare XLSM Files"
          link: "https://products.groupdocs.com/comparison/net/xlsm/"
          description: "Microsoft Excel Macro-Enabled Spreadsheet"

        # format loop
        - name: "Compare XLSB Files"
          link: "https://products.groupdocs.com/comparison/net/xlsb/"
          description: "Microsoft Excel Binary Spreadsheet File"

        # format loop
        - name: "Compare CSV Files"
          link: "https://products.groupdocs.com/comparison/net/csv/"
          description: "Comma Separated Values File"

        # format loop
        - name: "Compare PPT Files"
          link: "https://products.groupdocs.com/comparison/net/ppt/"
          description: "PowerPoint Presentation"

        # format loop
        - name: "Compare PPS Files"
          link: "https://products.groupdocs.com/comparison/net/pps/"
          description: "Microsoft PowerPoint Slide Show"

        # format loop
        - name: "Compare PPTX Files"
          link: "https://products.groupdocs.com/comparison/net/pptx/"
          description: "PowerPoint Open XML Presentation"

        # format loop
        - name: "Compare PPSX Files"
          link: "https://products.groupdocs.com/comparison/net/ppsx/"
          description: "PowerPoint Open XML Slide Show"

        # format loop
        - name: "Compare POT Files"
          link: "https://products.groupdocs.com/comparison/net/pot/"
          description: "Microsoft PowerPoint template"

        # format loop
        - name: "Compare POTX Files"
          link: "https://products.groupdocs.com/comparison/net/potx/"
          description: "Microsoft PowerPoint Open XML Template"

        # format loop
        - name: "Compare ODS Files"
          link: "https://products.groupdocs.com/comparison/net/ods/"
          description: "Open Document Spreadsheet"

        # format loop
        - name: "Compare ODP Files"
          link: "https://products.groupdocs.com/comparison/net/odp/"
          description: "OpenDocument Presentation File Format"

        # format loop
        - name: "Compare OTP Files"
          link: "https://products.groupdocs.com/comparison/net/otp/"
          description: "Origin Graph Template"

        # format loop
        - name: "Compare ODT Files"
          link: "https://products.groupdocs.com/comparison/net/odt/"
          description: "Open Document Text"

        # format loop
        - name: "Compare OTT Files"
          link: "https://products.groupdocs.com/comparison/net/ott/"
          description: "Open Document Template"

        # format loop
        - name: "Compare VST Files"
          link: "https://products.groupdocs.com/comparison/net/vst/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare PNG Files"
          link: "https://products.groupdocs.com/comparison/net/png/"
          description: "Portable Network Graphic"

        # format loop
        - name: "Compare GIF Files"
          link: "https://products.groupdocs.com/comparison/net/gif/"
          description: "Graphical Interchange Format File"

        # format loop
        - name: "Compare BMP Files"
          link: "https://products.groupdocs.com/comparison/net/bmp/"
          description: "Bitmap File Format"

        # format loop
        - name: "Compare HTML Files"
          link: "https://products.groupdocs.com/comparison/net/html/"
          description: "Hyper Text Markup Language"

        # format loop
        - name: "Compare MHT Files"
          link: "https://products.groupdocs.com/comparison/net/mht/"
          description: "Mime HTML"

        # format loop
        - name: "Compare MHTML Files"
          link: "https://products.groupdocs.com/comparison/net/mhtml/"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop
        - name: "Compare MSG Files"
          link: "https://products.groupdocs.com/comparison/net/msg/"
          description: "Microsoft Outlook E-mail Message"

        # format loop
        - name: "Compare EML Files"
          link: "https://products.groupdocs.com/comparison/net/eml/"
          description: "E-mail Message"

        # format loop
        - name: "Compare EMLX Files"
          link: "https://products.groupdocs.com/comparison/net/emlx/"
          description: "Apple Mail E-mail File"

        # format loop
        - name: "Compare ONE Files"
          link: "https://products.groupdocs.com/comparison/net/one/"
          description: "Microsoft OneNote"

        # format loop
        - name: "Compare VSD Files"
          link: "https://products.groupdocs.com/comparison/net/vsd/"
          description: "Microsoft Visio 2003-2010 Drawing"

        # format loop
        - name: "Compare VSDX Files"
          link: "https://products.groupdocs.com/comparison/net/vsdx/"
          description: "Microsoft Visio Drawing"

        # format loop
        - name: "Compare VSS Files"
          link: "https://products.groupdocs.com/comparison/net/vss/"
          description: "Microsoft Visio 2003-2010 Stencil"

        # format loop
        - name: "Compare VST Files"
          link: "https://products.groupdocs.com/comparison/net/vst/"
          description: "Microsoft Visio 2003-2010 Template"

        # format loop
        - name: "Compare VDX Files"
          link: "https://products.groupdocs.com/comparison/net/vdx/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare CS Files"
          link: "https://products.groupdocs.com/comparison/net/cs/"
          description: "CSharp Language"

        # format loop
        - name: "Compare Java Files"
          link: "https://products.groupdocs.com/comparison/net/java/"
          description: "Java Language"

        # format loop
        - name: "Compare CPP Files"
          link: "https://products.groupdocs.com/comparison/net/cpp/"
          description: "C++ Language"

        # format loop
        - name: "Compare JS Files"
          link: "https://products.groupdocs.com/comparison/net/js/"
          description: "JavaScript Language"

        # format loop
        - name: "Compare PY Files"
          link: "https://products.groupdocs.com/comparison/net/py/"
          description: "Python Language"

        # format loop
        - name: "Compare RB Files"
          link: "https://products.groupdocs.com/comparison/net/rb/"
          description: "Ruby Language"

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison offers document viewing APIs for other popular formats"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for Java JPEG"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/jpeg/"

############################# Back to top ###############################
back_to_top:
    enable: true
---
