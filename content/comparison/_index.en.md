
---
############################# Static ############################
layout: "family"
date:  2024-03-11T15:35:01
draft: false

product: "Comparison"
product_tag: "comparison"

lang: en

############################# Head ############################
head_title: "C# Java & Node.js Document Comparison Library | diff checker"
head_description: "GroupDocs Document Comparison Library native to C# .NET Java & Node.js. Check for differences among files of supported formats."

############################# Header ############################
title: "Compare Differences Across Popular File Types"
description: |
  Robust API for document comparison across various file formats.

  Identify and highlight content differences with minimal coding effort.

  Highlight visible differences and uncover changes in hidden properties.

############################# Supported Platforms ###############################
supported_platforms:
  enable: true
  head_title: "Choose your platform"
  title: "Platform independence"
  description: "GroupDocs.Comparison library supports the following operating systems and frameworks:"
  details_link_title: "Learn more"

  items:
    # items loop
    - title: ".NET"
      description: GroupDocs.Comparison for .NET 
      color: "blue"
      tag: "net"
      link: "/comparison/net/"
      features_link: "https://docs.groupdocs.com/comparison/net/system-requirements/"
      features:
          # features loop
          - rows: "4"
            content: |
                    .NET Framework 4.6.2 or higher <br> .NET Core 2.0 or higher <br> .NET 6.0 or higher
      
          # features loop
          - rows: "1"
            content: |
                    Windows <br> Linux <br> Mac OS
      
          # features loop
          - rows: "3"
            content: |
                    Microsoft Visual Studio <br> JetBrains Rider
      
          # features loop
          - rows: "1"
            content: |
                    50+ file formats
      

    # items loop
    - title: "Java"
      description: GroupDocs.Comparison for Java
      color: "red"
      tag: "java"
      link: "/comparison/java/"
      features_link: "https://docs.groupdocs.com/comparison/java/system-requirements/"
      features:
          # features loop
          - rows: "4"
            content: |
                    Java 8 or higher <br> Kotlin
      
          # features loop
          - rows: "1"
            content: |
                    Windows <br> Linux <br> Mac OS
      
          # features loop
          - rows: "3"
            content: |
                    IntelliJ IDEA <br> Eclipse <br> NetBeans
      
          # features loop
          - rows: "1"
            content: |
                    50+ file formats

    # items loop
    - title: "Node.js"
      description: GroupDocs.Comparison for Node.js
      color: "green"
      tag: "nodejs-java"
      link: "/comparison/nodejs-java/"
      features_link: "https://docs.groupdocs.com/comparison/nodejs-java/system-requirements/"
      features:
          # features loop
          - rows: "4"
            content: |
                    Node.js 16+ and J2SE 8.0 (1.8)+
      
          # features loop
          - rows: "1"
            content: |
                    Windows <br> Linux <br> Mac OS
      
          # features loop
          - rows: "3"
            content: |
                    Atom <br> Visual Studio Code <br> Any other text editor
      
          # features loop
          - rows: "1"
            content: |
                    50+ file formats

############################# Features ###############################
features:
  enable: true
  title: "Key Features of GroupDocs.Comparison"
  description: "API for comparing and diff viewing across PDF, Word, Excel, source code files, and more."

  items:
    # items loop
    - icon: "analize"
      title: "Intuitive diff view result"
      content: "Analyze changes easily with highlighted differences in a single-document report."

    # items loop
    - icon: "merge"
      title: "Efficient change review process"
      content: "Accept or reject changes with visually distinct modifications for easy decision-making."

    # items loop
    - icon: "styles"
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
      content: "To compare two documents, start by loading both the source and target files, and then apply the `compare` method. You have the flexibility to choose specific comparison settings for a more tailored analysis."
      samples:
          # samples loop
          - language: "C#"
            color: "blue"
            content: |
                    <code class="language-csharp" data-lang="csharp">
                        // Specify the source document

                        using (Comparer comparer = new Comparer("source.docx"))
                        {
                          // Add one or more target documents
                          comparer.Add(target.docx");

                          // Specify comparison options
                          CompareOptions options = new CompareOptions() {ShowRevisions = false};

                          // Perform the comparison and save the resulting document
                          comparer.Compare("result.docx", options);
                        }                    
                    </code>

          # samples loop
          - language: "Java"
            color: "red"
            content: |
                    <code class="language-java" data-lang="java">
                        // Specify the source document

                        try (Comparer comparer = new Comparer("source.docx"))
                        {
                          // Add one or more target documents
                          comparer.add("target.docx");

                          // Specify comparison options
                          CompareOptions options = new CompareOptions();
                          options.setShowRevisions(false);

                          // Perform the comparison and save the resulting document
                          final comparer.compare("result.docx", options);
                        }
                    </code>

          # samples loop
          - language: "TypeScript"
            color: "green"
            content: |
                    <code class="language-java" data-lang="javascript">
                        // Specify the source document

                        const comparer = new groupdocs.comparison.Comparer("source.docx");
    
                        // Add one or more target documents
                        comparer.add("target.docx");

                        // Specify comparison options
                        const options = new groupdocs.comparison.CompareOptions();
                        options.setShowRevisions(false);

                        // Perform the comparison and save the resulting document
                        comparer.compare("result.docx", options);    
                    </code>

############################# Supported Formats ###############################
formats:
  enable: true
  title: "50+ file formats supported"
  description: "GroupDocs.Comparison enables comparison operations within various format families."

############################# Metrics ###############################
metrics:
  enable: true
  title: "Detailed metrics and statistical insights"
  description: "Explore a thorough analysis of our key figures, offering comprehensive metrics and statistical insights into our accomplishments, influence, and expansion."

  items:
    # items loop
    - number: "50+"
      title: "Supported formats"
      content: "The API accommodates more than 50 of the most widely used file and document formats."

    # items loop
    - number: "800k"
      title: "NuGet downloads"
      content: "GroupDocs.Comparison for .NET has received over 800K downloads through the NuGet package manager."

    # items loop
    - number: "15k"
      title: "Maven downloads"
      content: "GroupDocs.Comparison for Java has accumulated over 15K downloads from our Maven repository."

    # items loop
    - number: "140+"
      title: "Happy customers"
      content: "Our libraries see adoption by both individual developers and top-tier companies worldwide"


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
      answer: "Yes, you can try GroupDocs.Comparison without buying a license. Once installed without a license, the library works in trial mode. In this mode, trial badges are added to the resultant document, and it is trimmed to the first 3 pages. If you wish to test GroupDocs.Comparison without the limitations of the trial version, you can also request a 30-day temporary license. For more details, see [temporary license](https://purchase.groupdocs.com/temporary-license/)."

    # items loop
    - question: "What licenses do you have?"
      answer: "We offer several license types to fit the needs of particular developers or companies. License types depend on the number of developers, the number of developer site locations, and whether you need to deliver our SDK/API to your end customers. Alternatively, you can choose Metered licenses based on monthly usage of the product. Learn more at [pricing](https://purchase.groupdocs.com/pricing/comparison/net/)."

############################# Cloud Links ###############################
cloud_links:
  enable: true
  title: "GroupDocs.Comparison low code APIs"
  description: "Incorporate document comparison capabilities into any application using our cloud-based REST API."
  
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
  description: "Web-based application that enables you to perform comparisons across more than 50 popular file formats directly in your browser."

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