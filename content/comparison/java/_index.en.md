
---
############################# Static ############################
layout: "landing"
date: 2024-12-19T07:50:01
draft: false

lang: en
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

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
    # supported_platforms loop
    - title: "Python"
      tag: "python-net"

############################# Head ############################
head_title: "Java Document Comparison Library| diff checker"
head_description: "Native Java Software to compare document style & content. Compare documents of multiple formats to identify differences."

############################# Header ############################
title: "Compare and check file differences using Java API"
description: "Develop Java applications with a highly configurable document comparison library to compare similar document formats, including files, their content, and text style."
words:
  for: "for"

actions:
  main: "Free Maven Download"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/"
  alt: "Licensing"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/java/"
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
    try (Comparer comparer = new Comparer("source.docx"))
    {    
      // Add one or more target documents
      comparer.add("target.docx");

      // Specify comparison options
      CompareOptions options = new CompareOptions();
      options.setShowRevisions(false);

      // Compare and save result
      final comparer.compare("result.docx", options);
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
        * **Word:** DOCX, DOC, DOCM,DOT, DOTM, DOTX, RTX, RTF, TXT
        * **Excel:** XLSX, XLS, XLT, XLTM, XLSB, XLSM
        * **PowerPoint:** PPTX, PPT, POT, POTX, PPS, PPSX
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
    - icon: "compare"
      title: "Easy to use document comparison"
      content: "Easily analyze and pinpoint differences between two documents."

    # feature loop
    - icon: "note-stack"
      title: "Compare multiple documents"
      content: "Simultaneously examine and highlight variances across multiple documents."

    # feature loop
    - icon: "stacks"
      title: "Supported formats"
      content: "Compatibility with over 50 widely-used document formats from diverse categories."

    # feature loop
    - icon: "rule"
      title: "Accept or reject changes"
      content: "Clear visualization of identified changes, with options to accept or reject modifications."

    # feature loop
    - icon: "preview"
      title: "Generate previews"
      content: "Capability to save comparison results as image previews."

    # feature loop
    - icon: "two-pager"
      title: "Content comparison"
      content: "Thorough comparison of text content on various levels - including line-by-line, paragraph, word, and character analysis, with emphasis on alterations."

    # feature loop
    - icon: "format_color_text"
      title: "Style comparison"
      content: "Ability to detect and highlight alterations in formatting and style elements."

    # feature loop
    - icon: "folder-managed"
      title: "Set metadata"
      content: "Option to retain metadata from source or target files, or permit user-defined metadata settings."

    # feature loop
    - icon: "lock"
      title: "Password protection"
      content: "Facilitates analysis of password-protected documents and enables password protection for the resultant documents."

    # feature loop
    - icon: "select"
      title: "Compare specific pages"
      content: "Load and compare specific sections or pages of a document as required."

    # feature loop
    - icon: "speaker-notes"
      title: "Display comments"
      content: "Flexibility to display or conceal comments when loading the source document."

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
        try (Comparer comparer = new Comparer("source.docx", new LoadOptions("1234")))
        {
            // Load the target document and specify its password
            comparer.add("target.docx", new LoadOptions("5678"));
        
            // Save comparison result to a specified file
            comparer.compare("result.docx");
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
        try (Comparer comparer = new Comparer("source.docx") 
        {
            // Specify the second file for comparison
            comparer.add("target2.docx");

            // Specify the third file for comparison
            comparer.add("target3.docx");

            // Save comparison result to a specified file
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---

