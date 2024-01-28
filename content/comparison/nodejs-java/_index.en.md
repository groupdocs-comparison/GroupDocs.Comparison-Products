---
############################# Static ############################
layout: "landing"
date: 2024-01-28T21:09:59
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
head_description: "Node.js documents style & content comparison API. Compare documents of multiple supported formats for the difference to identify changes between files."

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
  description: "Try GroupDocs.Comparison features for free, or request a license"

release:
  title: "Version {0} released"
  notes: "See what’s new"
  downloads: "Downloads"
  link: "https://releases.groupdocs.com/comparison/nodejs-java/"

code:
  title: "Compare BMP images in JavaScript"
  more: "More examples"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.comparison"
  content: |
    ```javascript {style=abap}

    // Instantiate Comparer
    let comparer = new Comparer("C:\\source.bmp");

    // Set up another file for comparison
    comparer.add("C:\\target.bmp");

    // Save comparison result to specified file
    comparer.compare("C:\\result.pdf"); 
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison at a glance"
  description: "API to compare various types of documents such as PDF, Microsoft Office, HTML, e-mails, or images within Node.js applications"
  features:
    # feature loop
    - title: "Detailed output reports"
      content: "GroupDocs.Comparison identifies changes in document content (characters, words, paragraphs, tables, charts), as well as, changes in document style. It provides customers with a resulting report that contains rich information about differences, their number, and type."

    # feature loop
    - title: "Most popular file and document formats are supported"
      content: "With GroupDocs.Comparison API you can efficiently compare documents of any supported formats like PDF, HTML, e-mail, Microsoft Office Word documents, Excel spreadsheets, PowerPoint presentations, OneNote, Visio diagrams, texts, JPEG, PNG, GIF, and BMP images as well as many other formats."

    # feature loop
    - title: "Documentation and examples"
      content: "There is already a lot of documentation on using Comparison library on different platforms with code examples, so you don’t have to think hard about how to work with GroupDocs.Comparison API in your Node.js application."

############################# Platforms ############################
platforms:
  enable: true
  title: "Platform independence"
  description: "GroupDocs.Comparison for Node.js supports the following operating systems, frameworks and package managers"
  items:
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "macOS"
      image: "finder"      
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NPM"
      image: "npm"  
    # platform loop
    - title: "NuGet"
      image: "nuget"      
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
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"

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
        ### Microsoft Office & OpenDocument formats
        * **Word:** DOC, DOCM, DOCX, DOT, DOTM, DOTX, RTX, RTF, TXT
        * **Excel:** XLS, XLT, XLSX, XLTM, XLSB, XLSM, XLSX
        * **PowerPoint:** POT, POTX, PPS, PPSX, PPTX, PPT        
        * **Outlook:** EML, EMLX, MSG
        * **OneNote:** ONE
        * **OpenDocument:** ODT, ODP, OTP, ODS, OTT
        * **Fixed Page Layout:** PDF  
    # group loop
    - color: "blue"
      content: |
        ### Images, Graphics & Diagrams
        * **Raster images:** BMP, GIF, JPG, JPEG, PNG
        * **Medical Imaging:** DICOM
        * **Microsoft Visio:** VSDX, VSD, VSS, VST, VDX
        * **AutoCAD Drawing:** DWG, DXF
      # group loop
    - color: "red"
      content: |
        ### Other
        * **Text:** TXT
        * **Programming Languages:** CS, Java, CPP, JS, PY, RB, PL, ASM, GROOVY, JSON, PHP, SQL, LOG, DIFF, LESS, SCALA
        * **Web:** HTM, HTML, MHT, MHTML
        * **e-Books:** MOBI, DjVu
        * **Delimiter-Separated Values:** CSV

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Comparison for Node.js features"
  description: "Easily compare PDF and Office documents, images and other formats"

  items:
    # feature loop
    - icon: "fas fa-columns"
      title: "Easy to use document comparison"
      content: "Analyze and identify differences within two documents."

    # feature loop
    - icon: "fas fa-border-all"
      title: "Compare multiple documents"
      content: "Analyze and identify differences within multiple documents simultaneously."

    # feature loop
    - icon: "complex"
      title: "Supported formats"
      content: "Supports more than 50 popular document formats from various categories."

    # feature loop
    - icon: "adjustment"
      title: "Accept or reject changes"
      content: "Clear visual representation of identified changes, providing the option to accept or reject modifications."

    # feature loop
    - icon: "fas fa-eye"
      title: "Generate previews"
      content: "Save the results of the comparison as images."

    # feature loop
    - icon: "fas fa-comment-slash"
      title: "Content comparison"
      content: "Compare text content line-by-line, by paragraphs, by words, by characters. Highlight the changes."

    # feature loop
    - icon: "fas fa-remove-format"
      title: "Style comparison"
      content: "Detect changes in formatting and styles."

    # feature loop
    - icon: "fas fa-wrench"
      title: "Set metadata"
      content: "Keep metadata from either the source or target files or allow it to be specified by users."

    # feature loop
    - icon: "fas fa-lock"
      title: "Password protection"
      content: "Analyze the encrypted documents, or secure the resulting document with a password."

    # feature loop
    - icon: "fas fa-copy"
      title: "Compare specific pages"
      content: "Load just the particular sections or pages of the document."

    # feature loop
    - icon: "fas fa-envelope"
      title: "Display comments"
      content: "When loading the source document you can choose whether to hide or show comments."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Code samples"
  description: "Some use cases of typical GroupDocs.Comparison for Node.js via Java operations"
  items:
    # code sample loop
    - title: "Comparing password-protected documents."
      content: |
        To compare documents that are protected with a password, you need to specify it then loading the documents:
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}
        import { Comparer, LoadOptions } from '@groupdocs/groupdocs.comparison'

        // Instantiate Comparer
        const comparer = new Comparer("C:\\source.doc", new LoadOptions("1234"));

        // Specify another file for comparison
        comparer.add("C:\\target.doc", new LoadOptions("5678"));

        // Save comparison result to a specified file
        comparer.compare("C:\\result.pdf");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Comparing multiple PDF documents."
      content: |
        GroupDocs.Comparison allows you to compare more than two documents. The operation is almost the same as when comparing two files. You just need to add more target files to the `comparer` class.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}
        import { Comparer } from '@groupdocs/groupdocs.comparison'

        // Instantiate Comparer
        const comparer = new Comparer("C:\\source.pdf");

        // Specify the second file for comparison
        comparer.add("C:\\target2.pdf");

        // Specify the third file for comparison
        comparer.add("C:\\target3.pdf");

        // Save comparison result to a specified file
        comparer.compare("C:\\result.pdf");
        ```
        {{< /landing/code >}}

---
