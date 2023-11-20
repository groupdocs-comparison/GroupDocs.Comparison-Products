---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: en
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

############################# Drop-down ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"
    # supported_platforms loop
    - title: "Java"
      tag: "java"
    # supported_platforms loop
    - title: "Node.js"
      tag: "nodejs-java" 


############################# Head ############################
head_title: "Node.js Document Comparison Library | Compare Docs for Text & Style"
head_description: "Node.js documents style & content comparison API. Compare many document formats for difference to identify changes among compared files of supported formats."

############################# Header ############################
title: "Node.js API to compare popular file formats"
description: "Document Comparison library to develop native JavaScript applications with highly configurable comparison features. Compare files, their content & text style between similar document formats."
words:
  for: "for"

actions:
  main: "Free NPM Download"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.comparison"
  alt: "Licensing"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/nodejs-java"
  title: "Ready to get started?"
  description: "Try GroupDocs.Comparison features for free or request a license"

release:
  title: "Version {0}&nbsp;released"
  notes: "See what’s new"
  downloads: "Downloads"
  link: "https://releases.groupdocs.com/comparison/nodejs-java/release-notes/latest/"

code:
  title: "Render PDF files in JavaScript"
  more: "More examples"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.comparison"
  content: |
    ```javascript {style=abap}   

    // Instantiate Comparer
    let comparer = new Comparer("C:\\source.bmp"); 

    //Set up another file for comparison
    comparer.add("C:\\target.bmp");

    //Save comparison result to specified file
    comparer.compare("C:\\result.bmp"); 

    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison at a glance"
  description: "API to compare various types of documents such as PDF, Microsoft Office, HTML, e-mail Outlook in Node.js applications"
  features:
      # feature loop
    - title: "Detailed output reports"
      content: "GroupDocs.Comparison allows to detect changes in the content of words, paragraphs, tables or charts and their styles. It provides customers with a result document that contains rich information about differences, their number and type belonging."

    # feature loop
    - title: "Most popular file and document formats are supported"
      content: "With GroupDocs.Comparison API you can efficiently compare documents of any supported formats like PDF, HTML, e-mail Outlook, Microsoft Office Word documents, Excel spreadsheets, PowerPoint presentations, OneNote, Visio diagrams, texts, png, gif and bmp images as well as a hundred of other formats."

    # feature loop
    - title: "Documentation and Examples"
      content: "There is already a lot of documentation on using Comparison library on different platforms with code examples, so you don’t have to think hard about how to work with GroupDocs.Comparison for .NET API in your application."


############################# Platforms ############################
platforms:
  enable: true
  title: "Platform independence"
  description: "GroupDocs.Comparison for Node.js supports the following operating systems, frameworks and package managers"
  items:
    # platform loop
    - title: "Amazon"
      image: "amazon"
    # platform loop
    - title: "Docker"
      image: "docker"
    # platform loop
    - title: "Azure"
      image: "azure"
    # platform loop
    - title: "VS Code"
      image: "vs_code"
    # platform loop
    - title: "ReSharper"
      image: "resharper"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NuGet"
      image: "nuget"

############################# File formats ############################
formats:
  enable: true
  title: "Supported file formats"
  description: |
    GroupDocs.Comparison for Node.js via Java supports operations with the following [file formats](https://docs.groupdocs.com/comparison/nodejs-java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument and text formats
        * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
        * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX
        * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM        
        * **Project:** MPP, MPT, MPX
        * **Outlook:** MSG, EML, EMLX, PST, OST
        * **OneNote:** ONE
        * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG
        * **Fixed Page Layout:** PDF, TEX, XPS, OXPS
        * **e-Books:** EPUB, MOBI, DjVu
        * **Delimiter-Separated Values:** CSV, TSV
    # group loop
    - color: "blue"
      content: |
        ### Images, Graphics & Diagrams
        * **Raster images:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
        * **Windows Icon:** ICO
        * **Scalable Vector Graphics:** SVG, CDR, CMX, IGS, SVGZ        
        * **Adobe Photoshop:** PSD, PSB        
        * **Stereo Lithography (3D Printing):** STL        
        * **Medical Imaging:** DICOM
        * **Plotter Documents:** PLT, HPG
        * **Autodesk Design Web Formats:** DWF, DWG
        * **AutoCAD Drawing:** DWT, IFC, STL, CF2        
      # group loop
    - color: "red"
      content: |
        ### Other        
        * **Web:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Archives:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Other:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Comparison features"
  description: "Seamlessly compare convert PDF, Office Documents, images and other"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "View documents in HTML"
      content: "Convert document of any type into a HTML document with CSS and SVG, which can be displayed in any modern web-browser."

    # feature loop
    - icon: "rasterize"
      title: "Rasterize documents"
      content: "Rasterize any supportable document format to the raster image, with adjustable image format and compression quality."

    # feature loop
    - icon: "sourcecode"
      title: "Render and highlight programming codes"
      content: "Support of all popular programming, scripting, and markup languages, with ability to parse and highlight their syntax."

    # feature loop
    - icon: "convertpdf"
      title: "Convert to PDF"
      content: "Document of any supportable format can be easily converted and saved to the PDF with adjustable options."

    # feature loop
    - icon: "transform"
      title: "Apply transformations"
      content: "Output document can be transformed during rendering - pages can be rotated and/or rearranged, and text watermark may be placed atop of them."

    # feature loop
    - icon: "adjustment"
      title: "HTML output adjustment"
      content: "Output HTML documents, generated by the GroupDocs.Viewer, can be tuned very finely: it is allowed to save to the stream or file, with external or embedded resources, callbacks and so on."

    # feature loop
    - icon: "complex"
      title: "Support of complex document structures"
      content: "GroupDocs.Viewer supports not only the single documents, but also files, which internally contain a list or hierarchical structure of documents, like email messages with attachments, ZIP archives with internal files within folders, multi-page TIFF images, and so on."

    # feature loop
    - icon: "optimization"
      title: "Optimization options"
      content: "GroupDocs.Viewer contains an adjustable cache subsystem, which can fasten the loading time by using the cached versions of the documents. Also a set of different options for different formats allows to exclude some unnecessary parts or aspects of documents from the rendering (fonts, hidded worksheets, email attachments) to optimize the overall performance"

    # feature loop
    - icon: "passwordprotected"
      title: "Support of password-protected documents"
      content: "GroupDocs.Viewer allows to open the encrypted documents of different types: PDF, WordProcessing, Spreadsheet, Presentation, and other, by specifying a password in the loading options."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Code samples"
  description: "Some use cases of typical GroupDocs.Viewer for Node.js via Java operations"
  items:
    # code sample loop
    - title: "Render DOCX to HTML"
      content: |
        The `HtmlViewOptions` class properties allow you to control the conversion process, more on that [here](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-html/). For instance, you can embed all external resources in the output HTML file, minify the output file, and optimize it for printing.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}
        import { Viewer, HtmlViewOptions } from '@groupdocs/groupdocs.viewer'

        //Set output HTML options, one file per page
        const viewOptions = HtmlViewOptions.forEmbeddedResources()

        // Instantiate Viewer
        const viewer = new Viewer("resume.docx")

        // Render PDF to HTML with embedded resources
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Export PPTX to PDF"
      content: |
        Create a `PdfViewOptions` class instance and pass it to the `Viewer.view` method to convert a PowerPoint PPTX file to PDF. The `PdfViewOptions` class properties allow you to control the conversion process. For instance, you can protect the output PDF file, reorder its pages, and specify the quality of document images. Refer to the [following documentation section](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-pdf/) for details.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}   
        import { Viewer, PdfViewOptions } from '@groupdocs/groupdocs.viewer'

        //Set output PDF options
        const viewOptions = new PdfViewOptions("presentation.pdf")

        // Instantiate Viewer
        const viewer = new Viewer("presentation.pptx")

        // Render PDF to HTML with embedded resources
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs products reviews"
# description: "Don't just take our word for it. See what other developers say about our APIs"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Excellent service and excellent products. They were extremely helpful and responsive during the GroupDocs.Viewer for .NET implementation process, can’t recommend them highly enough."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "After implementing and using GroupDocs.Viewer for .NET in the project it looks to be working very well. I have tested with a lot of documents and so far so good. Everything I’ve thrown at it renders nicely and looks just as good as it would in a PDF viewer or MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---
