---
############################# Static ############################
layout: "family"
date:  2024-01-15T14:25:32
draft: false

############################# Head ############################
head_title: "Comparison Solution | On Premise APIs and Free App - GroupDocs"
head_description: "The API to compare document content and styles across multiple formats."

############################# Header ############################
title: "Comparison Solution for Documents"
description: | 
            "The API to compare document content and styles across multiple formats."
            "Identify and highlight changes between documents."
            "Highly configurable comparison settings."

############################# Supported Platforms ###############################
supported_platforms:
  enable: true 
  head_title: "Choose your platform"

  items:
    # items loop
    - link: "/comparison/net/"
      color: "blue"
      title: ".NET"
      description: "GroupDocs.Comparison for .NET"
      tag: "net"

    # items loop
    - link: "/comparison/java/"
      color: "red"
      title: "Java"
      description: "GroupDocs.Comparison for .NET"
      tag: "java"

    # items loop
    - link: "/comparison/nodejs-java/"
      color: "green"
      title: "Node.js"
      description: "GroupDocs.Comparison for .NET"
      tag: "nodejs"

############################# Features ###############################
features:
  enable: true
  title: "GroupDocs.Comparison at a glance"
  description: "API to compare differences between documents."

  items:
    # items loop
    - icon: "compare"
      title: "Side by side comparison"
      content: "Detect and identify differences between two or more documents."

    # items loop
    - icon: "accept"
      title: "Accept or reject changes"
      content: "Visual separation of detected changes with the ability to accept or reject modifications."

    # items loop
    - icon: "content"
      title: "Compare content and styling"
      content: "Compare text contents, as well as changes in formatting and style."

    # items loop
    - icon: "pages"
      title: "Compare specific pages"
      content: "Load just the particular sections or pages of the document to be compared."

############################# Code Samples ###############################
code_samples:
  enable: true
  title: "Practical code showcase"
  description: "Some use cases of typical GroupDocs.Comparison operations."

  items:
    # items loop
    - title: "Comparing two files"
      content: "To compare two files you need to load the source and target documents and then call the `compare` method. Additionally, you can specify comparison options."
      samples:
          # samples loop
          - language: "C#"
            color: "blue"
            content: |
                    <code class="language-csharp" data-lang="csharp">
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
                    </code>

          # samples loop
          - language: "Java"
            color: "red"
            content: |
                    <code class="language-java" data-lang="java">
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
                    </code>

          # samples loop
          - language: "TypeScript"
            color: "green"
            content: |
                    <code class="language-java" data-lang="javascript">
                        // Specify the source document
                        const comparer = new groupdocs.comparison.Comparer("C:\\source.docx");
    
                        // Add one or more target documents
                        comparer.add("C:\\target.docx");

                        // Specify comparison options
                        const options = new groupdocs.comparison.CompareOptions();
                        options.setShowRevisions(false);

                        // Perform the comparison and save the resulting document
                        comparer.compare("C:\\result.docx", options);    
                    </code>

############################# Supported Formats ###############################
formats:
  enable: true
  title: "55+ file formats supported"
  description: "GroupDocs.Comparison supports operations with a wide range of document formats."

############################# Metrics ###############################
metrics:
  enable: true
  title: "In-depth metrics and statistical insights"
  description: "Dive into a detailed breakdown of our key figures, providing comprehensive metrics and statistical insights into our achievements, impact, and growth."

  items:
    # items loop
    - number: "55+"
      title: "Supported formats"
      content: "Each library supports processing more than 50 of most popular file and document formats."

    # items loop
    - number: "780k"
      title: "NuGet downloads"
      content: "GroupDocs.Comparison for .NET has more than 274K downloads from the NuGet package manager."

    # items loop
    - number: "15k"
      title: "Maven downloads"
      content: "GroupDocs.Comparison for Java has more than 15K downloads from our Maven repository."

    # items loop
    - number: "140+"
      title: "Happy customers"
      content: "Our libraries are used by both small individual developers as well as by leading companies all over the world."


############################# Customers ###############################
customers:
  enable: true
  title: "Our happy customers"
  description: "GroupDocs libraries are employed by globally renowned and distinguished brands across the world."

  items:
    # items loop
    - title: "BenQ Corporation"
      logo: "benq"
      
    # items loop
    - title: "Nasdaq Stock Market"
      logo: "nasdaq"
      
    # items loop
    - title: "AT&T Inc."
      logo: "att"
      
    # items loop
    - title: "Customer logo AstraZeneca"
      logo: "astrazeneca"
      
    # items loop
    - title: "Central Bank of Argentina"
      logo: "argentinacentralbank"
      
    # items loop
    - title: "Roche Holding AG"
      logo: "roche"
      
    # items loop
    - title: "Capita"
      logo: "capita"
      
    # items loop
    - title: "Axa S.A."
      logo: "axa"
      
    # items loop
    - title: "Instructure Inc."
      logo: "instructure"
      
    # items loop
    - title: "Wipro"
      logo: "wipro"


############################# Supported Platforms ###############################
supported_platforms:
  enable: true
  title: "Platform independence"
  description: "GroupDocs.Comparison library supports the following operating systems and frameworks:"
  details_link_title: "Learn more"

  items:
    # items loop
    - title: ".NET"
      color: "blue"
      features_link: "https://docs.groupdocs.com/comparison/net/system-requirements/"
      features:
          # features loop
          - rows: "4"
            content: |
                    .NET Framework 4.6.2 or higher
                    .NET Core 2.0 or higher
                    .NET 6.0 or higher
      
          # features loop
          - rows: "1"
            content: |
                    Windows, Linux, Mac OS
      
          # features loop
          - rows: "3"
            content: |
                    Microsoft Visual Studio
                    JetBrains Rider
      
          # features loop
          - rows: "1"
            content: |
                    55+ file formats
      

    # items loop
    - title: "Java"
      color: "red"
      features_link: "https://docs.groupdocs.com/comparison/java/system-requirements/"
      features:
          # features loop
          - rows: "4"
            content: |
                    Java 8 or higher
                    Kotlin
      
          # features loop
          - rows: "1"
            content: |
                    Windows, Linux, Mac OS
      
          # features loop
          - rows: "3"
            content: |
                    IntelliJ IDEA
                    Eclipse
                    NetBeans
      
          # features loop
          - rows: "1"
            content: |
                    50+ file formats

    # items loop
    - title: "Node.js"
      color: "green"
      features_link: "https://docs.groupdocs.com/comparison/nodejs-java/system-requirements/"
      features:
          # features loop
          - rows: "4"
            content: |
                    Java 8 or higher
                    Kotlin
      
          # features loop
          - rows: "1"
            content: |
                    Windows, Linux, Mac OS
      
          # features loop
          - rows: "3"
            content: |
                    Atom
                    Sublime
                    Visual Studio Code
                    Any other text editor
      
          # features loop
          - rows: "1"
            content: |
                    50+ file formats

############################# Actions ###############################
actions:
  enable: true
  title: "Ready to get started?"
  description: "Try GroupDocs.Comparison features for free on your platform"

  items:
    # items loop
    - title: ".NET"
      color: "blue"
      link: "/comparison/net/"

    # items loop
    - title: "Java"
      color: "red"
      link: "/comparison/java/"

    # items loop
    - title: "Node.js"
      color: "green"
      link: "/comparison/nodejs-java/"      

############################# FAQ ###############################
faq:
  enable: true
  title: "Frequently asked questions"
  description: "Answers to most commonly asked questions."

  items:
    # items loop
    - question: "Does the GroupDocs.Comparison library need any other third-party software to manipulate documents?"
      answer: "GroupDocs.Comparison does not require any external software to be installed such as Adobe Acrobat, Microsoft Office, or any other."

    # items loop
    - question: "Can I try the GroupDocs.Comparison library before purchasing it?"
      answer: "Yes, you can try GroupDocs.Comparison without buying a license. Once installed without a license, the library works in trial mode. In this mode, trial badges are added to the resultant document, and it is trimmed to the first 3 pages. If you wish to test GroupDocs.Comparison without the limitations of the trial version, you can also request a 30-day temporary license. For more details, see "

    # items loop
    - question: "What licenses do you have?"
      answer: "We offer several license types to fit the needs of particular developers or companies. License types depend on the number of developers, the number of developer site locations, and whether you need to deliver our SDK/API to your end customers. Alternatively, you can choose Metered licenses based on monthly usage of the product. Learn more at "

############################# Cloud Links ###############################
cloud_links:
  enable: true
  title: "GroupDocs.Comparison low code APIs"
  description: "Accelerate documents merging in any type of application with our cloud-based REST API."
  
  items:
    # items loop
    - title: "GroupDocs.Comparison Cloud for cURL"
      content: "Work with cURL RESTful document comparison API to compare Word, Excel, PowerPoint and other popular file formats."
      icon: "groupdocs_comparison-for-curl"
      link: "https://products.groupdocs.cloud/comparison/curl"

    # items loop
    - title: "GroupDocs.Comparison Cloud for .NET"
      content: "Add powerful document comparison capabilities in .NET applications using Cloud SDK for .NET. Compare DOCX, XLSX, PPTX and more."
      icon: "groupdocs_comparison-for-net"
      link: "https://products.groupdocs.cloud/comparison/net"

    # items loop
    - title: "GroupDocs.Comparison Cloud for Java"
      content: "Add high fidelity document comparison features to your java applications with specially designed document comparison SDK for Java."
      icon: "groupdocs_comparison-for-java"
      link: "https://products.groupdocs.cloud/comparison/java"

############################# App links ###############################
app_links:
  enable: true
  title: "GroupDocs.Comparison NoCode apps"
  description: "Online application allowing you to compare 50+ popular file formats in browser."

  items:
    # items loop
    - title: "GroupDocs.Comparison Total"
      content: "Online diff tool to compare two documents from any device."
      icon: "groupdocs_comparison-app"
      link: "https://products.groupdocs.app/comparison/total"

    # items loop
    - title: "GroupDocs.Comparison DOCX"
      content: "Compare DOCX files online."
      icon: "groupdocs_words-app"
      link: "https://products.groupdocs.app/comparison/docx"

    # items loop
    - title: "GroupDocs.Comparison PDF"
      content: "Diff PDF documents online using PDF comparison app."
      icon: "groupdocs_pdf-app"
      link: "https://products.groupdocs.app/comparison/pdf"


      


---