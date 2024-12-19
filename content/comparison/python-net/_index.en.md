
---
############################# Static ############################
layout: "landing"
date: 2024-12-19T07:50:01
draft: false

lang: en
product: "Comparison"
product_tag: "comparison"
platform: "Python via .NET"
platform_tag: "python-net"

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
head_title: "Python Document Comparison Tool | Document Analysis"
head_description: "Discover the power of the Python Document Comparison Tool for thorough document analysis. Effortlessly integrates with Python for comprehensive tracking of modifications."

############################# Header ############################
title: "Compare Documents with Python: Highlight Any Differences"
description: "Utilize the GroupDocs.Comparison API to create native applications in Python with customizable comparison functionalities. Examine files, their content, and styling variations across document formats."
words:
  for: "for"

actions:
  main: "Get Your Free PyPi Download Now"
  main_link: "https://pypi.org/project/groupdocs-comparison-net/"
  alt: "Licensing"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/python-net/"
  title: "Ready to get started?"
  description: "Try GroupDocs.Comparison features for free or request a license"

release:
  title: "Version {0} released"
  notes: "See what’s new"
  downloads: "Downloads"

code:
  title: "Compare BMP images using Python"
  more: "More examples"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET/"
  install: "pip install groupdocs-comparison-net"
  content: |
    ```python {style=abap}
    def run():

        # Specify the source document
        with groupdocs.comparison.Comparer("in.bmp") as comparer:

            # Add one or more target documents
            comparer.add("target.bmp")

            # Specify comparison options
            options = new groupdocs.comparison.CompareOptions()
            options.setGenerateSummaryPage(false)

            # Compare and save result
            comparer.compare("result.bmp", options)
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison at a glance"
  description: "An API designed for comparing widely used document types such as PDFs, Microsoft Office files, HTML, emails, or images within Python applications."
  features:
    # feature loop
    - title: "Comprehensive Output Reports"
      content: "GroupDocs.Comparison detects alterations in document content (characters, words, paragraphs, tables, charts) as well as document styling changes. Users receive a detailed report highlighting the nature and count of changes."

    # feature loop
    - title: "Wide Range of File and Document Formats"
      content: "The GroupDocs.Comparison API allows you to compare documents in formats such as PDF, HTML, email, Microsoft Office Word, Excel workbooks, PowerPoint files, OneNote notes, Visio diagrams, text documents, JPEG, PNG, GIF, BMP images, among many others."

    # feature loop
    - title: "Thorough Documentation and Code Samples"
      content: "In-depth documentation and sample codes for the Comparison library across various platforms are readily available, simplifying the integration of the GroupDocs.Comparison API into your Python applications."

    # feature loop
    - title: "Select and Combine Changes into One Document"
      content: "If you possess various versions of a document, you can selectively compile changes into a single new file using the GroupDocs.Comparison library."

############################# Platforms ############################
platforms:
  enable: true
  title: "Platform independence"
  description: "GroupDocs.Comparison for Python via .NET is compatible with the following operating systems, frameworks, and package managers."
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
    GroupDocs.Comparison for Python via .NET can operate with the following [file formats](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
  title: "Capabilities of GroupDocs.Comparison for Python via .NET"
  description: "Seamlessly compare PDFs, Office documents, images, and a wide variety of other formats."

  items:
    # feature loop
    - icon: "compare"
      title: "Intuitive Document Comparison"
      content: "Examine and highlight differences between two documents."

    # feature loop
    - icon: "note-stack"
      title: "Comparison of Multiple Documents"
      content: "Inspect multiple documents for differences at the same time."

    # feature loop
    - icon: "stacks"
      title: "Extensive Format Support"
      content: "Compatible with over 50 commonly used document formats across various categories."

    # feature loop
    - icon: "rule"
      title: "Accept or Reject Changes"
      content: "Visualize changes with clarity, offering options for acceptance or rejection of edits."

    # feature loop
    - icon: "preview"
      title: "Generate Visual Previews"
      content: "Create previews of comparison outcomes in image formats."

    # feature loop
    - icon: "two-pager"
      title: "Text-based Content Comparison"
      content: "Perform line-by-line, paragraph, word, or character comparisons to highlight changes."

    # feature loop
    - icon: "format_color_text"
      title: "Formatting Changes Detection"
      content: "Identify alterations in document styles and formatting."

    # feature loop
    - icon: "folder-managed"
      title: "Customizable Metadata Handling"
      content: "Retain metadata from the source or target files, or allow users to define new metadata."

    # feature loop
    - icon: "lock"
      title: "Handle Password-Protected Files"
      content: "Work with encrypted documents, or create secured documents protected with a password."

    # feature loop
    - icon: "select"
      title: "Focused Page Comparisons"
      content: "Select and compare particular sections or individual pages of a document."

    # feature loop
    - icon: "speaker-notes"
      title: "Manage Comment Visibility"
      content: "Decide to reveal or conceal comments when examining the source document."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Code samples"
  description: "Discover common scenarios for utilizing GroupDocs.Comparison for Python via .NET functionalities."
  items:
    # code sample loop
    - title: "Comparing Documents with Password Protection"
      content: |
        To compare documents that are [secured with a password](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/), you need to specify the password when loading the documents:
        {{< landing/code title="How to compare password-protected documents.">}}
        ```python {style=abap}
        def run():

            # Load the source document and specify its password
            with groupdocs.comparison.Comparer("source.docx", new LoadOptions("1234")) as comparer:

                # Load the target document and specify its password
                comparer.add("target.docx", new LoadOptions("5678"));

                # Save comparison result to a specified file
                comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Comparing multiple PDF documents."
      content: |
        GroupDocs.Comparison allows you to [compare more than two documents](https://docs.groupdocs.com/comparison/python-net/compare-multiple-documents/). The operation is almost the same as when comparing two files. You just need to add more target files to the `comparer` class.
        {{< landing/code title="How to compare three or more documents.">}}
        ```python {style=abap}
        def run():

            # Load the source document
            with groupdocs.comparison.Comparer(source.pdf") as comparer:

                # Specify the second file for comparison
                comparer.add("target2.pdf");

                # Specify the third file for comparison
                comparer.add("target3.pdf");

                # Save comparison result to a specified file
                comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---