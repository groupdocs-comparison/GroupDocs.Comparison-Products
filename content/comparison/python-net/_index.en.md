
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
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
head_title: "Python Document Comparison API | diff checker"
head_description: "The Python Document Comparison API offers efficient tools for comparing documents. Seamlessly integrates with Python for instant change tracking"

############################# Header ############################
title: "Compare Documents with Python: Highlight Any Differences"
description: "Use the GroupDocs.Comparison API to develop native Python applications with highly configurable comparison features. Compare files, their content, and text styles between similar document formats."
words:
  for: "for"

actions:
  main: "Free PyPi Download"
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
  title: "Compare BMP images in Python"
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
  description: "An API to compare popular document types such as PDF, Microsoft Office, HTML, emails, or images within Python applications."
  features:
    # feature loop
    - title: "Detailed Output Reports"
      content: "GroupDocs.Comparison identifies changes in document content (characters, words, paragraphs, tables, charts) as well as changes in document style. It provides users with a report containing detailed information about differences, including their number and type."

    # feature loop
    - title: "Supports Popular File and Document Formats"
      content: "With the GroupDocs.Comparison API, you can efficiently compare documents in formats like PDF, HTML, email, Microsoft Office Word, Excel spreadsheets, PowerPoint presentations, OneNote, Visio diagrams, text files, JPEG, PNG, GIF, BMP images, and many other formats."

    # feature loop
    - title: "Comprehensive Documentation and Examples"
      content: "Extensive documentation and code examples for using the Comparison library on different platforms are available, making it easy to integrate GroupDocs.Comparison API into your Python application."

    # feature loop
    - title: "Select and Merge Changes into One File"
      content: "If you have different versions of a document, you can select specific changes and compile a new document using the GroupDocs.Comparison library."

############################# Platforms ############################
platforms:
  enable: true
  title: "Platform independence"
  description: "GroupDocs.Comparison for Python via .NET supports the following operating systems, frameworks, and package managers"
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
    GroupDocs.Comparison for Python via .NET supports operations with the following [file formats](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
  title: "GroupDocs.Comparison for Python via .NET Features"
  description: "Easily compare PDF and Office documents, images, and other formats."

  items:
    # feature loop
    - icon: "compare"
      title: "User-Friendly Document Comparison"
      content: "Analyze and identify differences between two documents."

    # feature loop
    - icon: "note-stack"
      title: "Compare Multiple Documents"
      content: "Analyze and identify differences within multiple documents simultaneously."

    # feature loop
    - icon: "stacks"
      title: "Supported Formats"
      content: "Supports more than 50 popular document formats from various categories."

    # feature loop
    - icon: "rule"
      title: "Accept or Reject Changes"
      content: "Clear visual representation of identified changes, with the option to accept or reject modifications."

    # feature loop
    - icon: "preview"
      title: "Generate Previews"
      content: "Save the comparison results as images."

    # feature loop
    - icon: "two-pager"
      title: "Content Comparison"
      content: "Compare text content line-by-line, by paragraphs, by words, or by characters. Highlight the changes."

    # feature loop
    - icon: "format_color_text"
      title: "Style Comparison"
      content: "Detect changes in formatting and styles."

    # feature loop
    - icon: "folder-managed"
      title: "Set Metadata"
      content: "Retain metadata from either the source or target files, or allow it to be specified by users."

    # feature loop
    - icon: "lock"
      title: "Password Protection"
      content: "Analyze encrypted documents, or secure the resulting document with a password."

    # feature loop
    - icon: "select"
      title: "Compare Specific Pages"
      content: "Load and compare specific sections or pages of a document."

    # feature loop
    - icon: "speaker-notes"
      title: "Display Comments"
      content: "Choose to hide or show comments when loading the source document."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Code samples"
  description: "Explore typical use cases of GroupDocs.Comparison for Python via .NET operations"
  items:
    # code sample loop
    - title: "Comparing Password-Protected Documents"
      content: |
        To compare documents that are [protected with a password](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/), you need to specify the password when loading the documents:
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