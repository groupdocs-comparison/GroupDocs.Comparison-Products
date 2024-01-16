---
############################# Static ############################
layout: "landing"
date: 2024-01-16T13:00:43
draft: false

lang: en
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "Java Document Comparison Library | Compare Docs for Text & Style"
head_description: "Java API to compare document style & content. Compare documents of multiple formats to identify differences."

############################# Header ############################
title: "Compare & check files using Java API"
description: "Develop Java applications with a highly configurable document comparison library to compare similar document formats, including files, their content, and text style."
words:
  for: "for"

actions:
  main: "Free Maven Download"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/"
  alt: "Licensing"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/java"
  title: "Ready to get started?"
  description: "Try GroupDocs.Comparison features for free or request a license"

release:
  title: "Version {0} released"
  notes: "See what’s new"
  downloads: "Downloads"

code:
  title: "Compare DOCX files in Java"
  more: "More examples"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
  install: |
    <dependency>
      <groupId>com.groupdocs</groupId>
      <artifactId>groupdocs-comparison</artifactId>
      <version>{0}</version>
    </dependency>
  content: |
    ```java {style=abap}  
    // Specify the source document
    try (Comparer comparer = new Comparer("C:\\source.docx"))
    {    
      // Add one or more target documents
      comparer.add("C:\\target.docx");

      // Specify comparison options
      CompareOptions options = new CompareOptions();
      options.setShowRevisions(false);

      // Perform the comparison and save the resulting document
      final comparer.compare("C:\\result.docx", options);
    }    
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison at a glance"
  description: "API to compare differences between documents in Java applications"
  features:
    # feature loop
    - title: "File comparison in Java"
      content: "Detect changes between source and target files at paragraph, word, and character levels. Identify styling and formatting changes such as bold, italic, underlines, strike-throughs, font types, and more."

    # feature loop
    - title: "Vast number of supported formats"
      content: "With the GroupDocs.Comparison API, you can easily compare documents of multiple supported formats. This includes PDF, HTML, email, Microsoft Office Word documents, Excel spreadsheets, PowerPoint presentations, OneNote, Visio diagrams, texts, JPEG, PNG, GIF, and BMP images, as well as many other formats."

    # feature loop
    - title: "Apply or reject changes easily"
      content: "Every difference between the compared documents can be applied or rejected and then exported to the output document."

    # feature loop
    - title: "Comparison summary report"
      content: "Generate a summary report that lists all changes in the compared documents."

############################# Platforms ############################
platforms:
  enable: true
  title: "Platform independence"
  description: "GroupDocs.Comparison for Java supports the following operating systems, frameworks and package managers"
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
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "Maven"
      image: "maven"

############################# File formats ############################
formats:
  enable: true
  title: "Supported file formats"
  description: |
    GroupDocs.Comparison for Java supports operations with the following [file formats](https://docs.groupdocs.com/comparison/java/supported-document-formats/).
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
  title: "GroupDocs.Comparison features"
  description: "Easily compare PDF and Office documents, images and other formats"

  items:
    # feature loop
    - icon: "fas fa-columns"
      title: "Side by side comparison"
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
  description: "Some use cases of typical GroupDocs.Comparison for Java operations"
  items:
    # code sample loop
    - title: "Comparing password-protected documents."
      content: |
        To compare documents that are [protected with a password](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/), you need to specify it then loading the documents:
        {{< landing/code title="How to compare password-protected documents.">}}
        ```java {style=abap}
        // Load the source document and specify its password
        try (Comparer comparer = new Comparer("C:\\source.doc", new LoadOptions("1234")))
        {
            // Load the target document and specify its password
            comparer.add("C:\\target.docx", new LoadOptions("5678"));
        
            // Save comparison result to a specified file
            comparer.compare("C:\\result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Comparing multiple PDF documents."
      content: |
        GroupDocs.Comparison allows you to [compare more than two documents](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/). The operation is almost the same as when comparing two files. You just need to add more target files to the `comparer` class.
        {{< landing/code title="How to compare three or more documents.">}}
        ```java {style=abap}   
        // Load the source document
        try (Comparer comparer = new Comparer("C:\\source.doc") 
        {
            // Specify the second file for comparison
            comparer.add("C:\\target2.docx");

            // Specify the third file for comparison
            comparer.add("C:\\target3.docx");

            // Save comparison result to a specified file
            comparer.compare("C:\\result.docx");
        }
        ```
        {{< /landing/code >}}

---

