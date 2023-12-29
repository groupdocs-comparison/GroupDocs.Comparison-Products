---
############################# Static ############################
layout: "landing"
date: 2023-12-11T13:24:02
draft: false
product: "Comparison"
product_tag: "comparison"
platform: "Net"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Comparison Library | Compare Docs for Text & Style"
head_description: ".NET API to compare document style & content. Compare documents of multiple supported formats for the difference to identify changes between files."

############################# Header ############################
title: "Compare & check files using .NET API"
description: "Develop .NET applications with a highly configurable document comparison API. Compare files based on content and text style across similar document formats."
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
      CompareOptions options = new CompareOptions() {ShowRevisions = false};

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
      content: "With GroupDocs.Comparison API you can efficiently compare documents of any supported formats like PDF, HTML, e-mail, Microsoft Office Word documents, Excel spreadsheets, PowerPoint presentations, OneNote, Visio diagrams, texts, JPEG, PNG, GIF, and BMP images as well as many other formats."

    # feature loop
    - title: "Apply or reject changes easily"
      content: "Every difference between the compared documents can be applied or rejected and then exported to the output document."

    # feature loop
    - title: "Comparison summary report"
      content: "Save a differences summary report that lists all changes in compared documents."      

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
