---
############################# Static ############################
layout: "landing"
date: 2024-01-29T20:57:18
draft: false

lang: en
product: "Comparison"
product_tag: "comparison"
platform: "Net"
platform_tag: "net"

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
head_title: ".NET Document Comparison Library | Compare Docs for Text & Style"
head_description: ".NET API to compare document style & content. Compare documents of multiple supported formats for the difference to identify changes between files."

############################# Header ############################
title: "Compare documents with ease in your .NET solutions"
description: "Build .NET applications with a flexible document comparison API that enables file comparison by content and style across various document formats."
words:
  for: "for"

actions:
  main: "Free NuGet Download"
  main_link: "https://www.nuget.org/packages/GroupDocs.Comparison"
  alt: "Licensing"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/net"
  title: "Ready to get started?"
  description: "Try GroupDocs.Comparison features for free or request a license"

release:
  title: "Version {0} released"
  notes: "See what’s new"
  downloads: "Downloads"

code:
  title: "Compare DOCX files in C#"
  more: "More examples"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET"
  install: "dotnet add package GroupDocs.Comparison"
  content: |
    ```csharp {style=abap}   
    // Specify the source document
    using (Comparer comparer = new Comparer("C:\\source.docx"))
    {
        // Add one or more target documents
        comparer.Add("C:\\target.docx");

        // Specify comparison options
        CompareOptions options = new CompareOptions() 
        {ShowRevisions = false};

        // Perform the comparison and save the resulting document
        comparer.Compare("C:\\result.docx", options);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison at a glance"
  description: "API to compare differences between documents in .NET applications"
  features:
    # feature loop
    - title: "File comparison in C#"
      content: "Detect differences between source and target files for changes at paragraphs, words, and character levels. Identify styling and formatting changes like bold, italic, underlines, strike-troughs, font types, etc."

    # feature loop
    - title: "Most popular file and document formats are supported"
      content: "GroupDocs.Comparison API allows for efficient document comparison across a wide range of formats, including PDF, HTML, emails, Microsoft Office documents (Word, Excel, PowerPoint, OneNote, Visio), various image types (JPEG, PNG, GIF, BMP), text files, and more."

    # feature loop
    - title: "Apply or reject changes easily"
      content: "Each difference identified in the compared documents using the GroupDocs.Comparison API can be selectively applied or rejected, enabling customization before exporting to the final output document."

    # feature loop
    - title: "Comparison summary report"
      content: "Generate a summary report of differences, detailing all the changes found in the compared documents, and save it for reference."

############################# Platforms ############################
platforms:
  enable: true
  title: "Platform independence"
  description: "GroupDocs.Comparison for .NET supports the following operating systems, frameworks and package managers"
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
    GroupDocs.Comparison for .NET supports operations with the following [file formats](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
      title: "Easy to use document comparison"
      content: "Aanalyze and identify differences between two documents."

    # feature loop
    - icon: "fas fa-border-all"
      title: "Compare multiple documents"
      content: "Simultaneously analyze and identify differences across multiple documents."

    # feature loop
    - icon: "complex"
      title: "Supported formats"
      content: "Compatible with over 50 widely-used document formats from various categories, ensuring broad applicability."

    # feature loop
    - icon: "adjustment"
      title: "Accept or reject changes"
      content: "Сlear visual display of detected changes, complete with options to either accept or reject these modifications."

    # feature loop
    - icon: "fas fa-eye"
      title: "Generate previews"
      content: "Ability to save comparison results as image previews for easy reference and sharing."

    # feature loop
    - icon: "fas fa-comment-slash"
      title: "Content comparison"
      content: "Conduct thorough text comparisons at various levels - including line-by-line, paragraph, word, and character - with highlighted differences for better clarity."

    # feature loop
    - icon: "fas fa-remove-format"
      title: "Style and formatting comparison"
      content: "Detects and highlights alterations in document formatting and style, ensuring comprehensive review."

    # feature loop
    - icon: "fas fa-wrench"
      title: "Flexible metadata settings"
      content: "Preserve metadata from source or target files, or customize it according to user preferences."

    # feature loop
    - icon: "fas fa-lock"
      title: "Password protection"
      content: "Analyze password-protected documents and secure the output document with password encryption for added security."

    # feature loop
    - icon: "fas fa-copy"
      title: "Selective page comparison"
      content: "Load and compare specific sections or pages of a document for targeted analysis."

    # feature loop
    - icon: "fas fa-envelope"
      title: "Display comments"
      content: "Choose to display or hide comments when loading the source document, offering greater control over the comparison process."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Code samples"
  description: "Some use cases of typical GroupDocs.Comparison for .NET operations"
  items:
    # code sample loop
    - title: "Comparing password-protected documents."
      content: |
        To compare documents that are [protected with a password](https://docs.groupdocs.com/comparison/net/load-password-protected-documents/), you need to specify it then loading the documents:
        {{< landing/code title="How to compare password-protected documents.">}}
        ```csharp {style=abap}
        // Load the source document and specify its password
        using(Comparer comparer = new Comparer("C:\\source.doc", new LoadOptions() {Password = "1234"}))  
        {
            // Load the target document and specify its password
            comparer.Add("C:\\target.docx", new LoadOptions() {Password = "5678"});

            // Save comparison result to a specified file
            comparer.Compare("C:\\result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Comparing multiple PDF documents."
      content: |
        GroupDocs.Comparison allows you to [compare more than two documents](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/). The operation is almost the same as when comparing two files. You just need to add more target files to the `comparer` class.
        {{< landing/code title="How to compare three or more documents.">}}
        ```csharp {style=abap}   
        // Load the source document
        using(Comparer comparer = new Comparer("C:\\source.doc") 
        {
            // Specify the second file for comparison
            comparer.Add("C:\\target2.docx");
            
            // Specify the third file for comparison
            comparer.Add("C:\\target3.docx");
            
            // Save comparison result to a specified file
            comparer.Compare("C:\\result.docx");
        }
        ```
        {{< /landing/code >}}

---
