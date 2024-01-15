<% configRef "..\\configs\\index\\index.yml" %>
---
############################# Static ############################
layout: "family"
date:  <% date "utcnow" %>
draft: false

############################# Head ############################
head_title: "<% "{index-content.head_title}" %>"
head_description: "<% "{index-content.head_description}" %>"

############################# Header ############################
title: "<% "{index-content.title}" %>"
description: | 
            "<% "{index-content.description_1}" %>"
            "<% "{index-content.description_2}" %>"
            "<% "{index-content.description_3}" %>"

############################# Supported Platforms ###############################
supported_platforms:
  enable: true 
  head_title: "<% "{index-content.supported_platforms.head_title}" %>"

  items:
    # items loop
    - link: "/comparison/net/"
      color: "blue"
      title: ".NET"
      description: "<% "{index-content.supported_platforms.net.description}" %>"
      tag: "net"

    # items loop
    - link: "/comparison/java/"
      color: "red"
      title: "Java"
      description: "<% "{index-content.supported_platforms.net.description}" %>"
      tag: "java"

    # items loop
    - link: "/comparison/nodejs-java/"
      color: "green"
      title: "Node.js"
      description: "<% "{index-content.supported_platforms.net.description}" %>"
      tag: "nodejs"

############################# Features ###############################
features:
  enable: true
  title: "<% "{index-content.features.title}" %>"
  description: "<% "{index-content.features.description}" %>"

  items:
    # items loop
    - icon: "compare"
      title: "<% "{index-content.features.feature_1.title}" %>"
      content: "<% "{index-content.features.feature_1.content}" %>"

    # items loop
    - icon: "accept"
      title: "<% "{index-content.features.feature_2.title}" %>"
      content: "<% "{index-content.features.feature_2.content}" %>"

    # items loop
    - icon: "content"
      title: "<% "{index-content.features.feature_3.title}" %>"
      content: "<% "{index-content.features.feature_3.content}" %>"

    # items loop
    - icon: "pages"
      title: "<% "{index-content.features.feature_4.title}" %>"
      content: "<% "{index-content.features.feature_4.content}" %>"

############################# Code Samples ###############################
code_samples:
  enable: true
  title: "<% "{index-content.code_samples.index_title}" %>"
  description: "<% "{index-content.code_samples.index_description}" %>"

  items:
    # items loop
    - title: "<% "{index-content.sample_index_title}" %>"
      content: "<% "{index-content.sample_index_content}" %>"
      samples:
          # samples loop
          - language: "C#"
            color: "blue"
            content: |
                    <code class="language-csharp" data-lang="csharp">
                        // <% "{index-content.code_comment_1}" %>
                        using (Comparer comparer = new Comparer("C:\\source.docx"))
                        {
                          // <% "{index-content.code_comment_2}" %>
                          comparer.Add("C:\\target.docx");

                          // <% "{index-content.code_comment_3}" %>
                          CompareOptions options = new CompareOptions() {ShowRevisions = false};

                          // <% "{index-content.code_comment_4}" %>
                          comparer.Compare("C:\\result.docx", options);
                        }                    
                    </code>

          # samples loop
          - language: "Java"
            color: "red"
            content: |
                    <code class="language-java" data-lang="java">
                        // <% "{index-content.code_comment_1}" %>
                        try (Comparer comparer = new Comparer("C:\\source.docx"))
                        {
                          // <% "{index-content.code_comment_2}" %>
                          comparer.add("C:\\target.docx");

                          // <% "{index-content.code_comment_3}" %>
                          CompareOptions options = new CompareOptions();
                          options.setShowRevisions(false);

                          // <% "{index-content.code_comment_4}" %>
                          final comparer.compare("C:\\result.docx", options);
                        }
                    </code>

          # samples loop
          - language: "TypeScript"
            color: "green"
            content: |
                    <code class="language-java" data-lang="javascript">
                        // <% "{index-content.code_comment_1}" %>
                        const comparer = new groupdocs.comparison.Comparer("C:\\source.docx");
    
                        // <% "{index-content.code_comment_2}" %>
                        comparer.add("C:\\target.docx");

                        // <% "{index-content.code_comment_3}" %>
                        const options = new groupdocs.comparison.CompareOptions();
                        options.setShowRevisions(false);

                        // <% "{index-content.code_comment_4}" %>
                        comparer.compare("C:\\result.docx", options);    
                    </code>

############################# Supported Formats ###############################
formats:
  enable: true
  title: "<% "{index-content.formats_title_index}" %>"
  description: "<% "{index-content.formats_description_index}" %>"

############################# Metrics ###############################
metrics:
  enable: true
  title: "<% "{index-content.metrics.title}" %>"
  description: "<% "{index-content.metrics.description}" %>"

  items:
    # items loop
    - number: "55+"
      title: "<% "{index-content.metrics.item_1.title}" %>"
      content: "<% "{index-content.metrics.item_1.description}" %>"

    # items loop
    - number: "780k"
      title: "<% "{index-content.metrics.item_2.title}" %>"
      content: "<% "{index-content.metrics.item_2.description}" %>"

    # items loop
    - number: "15k"
      title: "<% "{index-content.metrics.item_3.title}" %>"
      content: "<% "{index-content.metrics.item_3.description}" %>"

    # items loop
    - number: "140+"
      title: "<% "{index-content.metrics.item_4.title}" %>"
      content: "<% "{index-content.metrics.item_4.description}" %>"


############################# Customers ###############################
customers:
  enable: true
  title: "<% "{index-content.customers_title}" %>"
  description: "<% "{index-content.customers_description}" %>"

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
  title: "<% "{index-content.platforms.title}" %>"
  description: "<% "{index-content.platforms.description}" %>"
  details_link_title: "<% "{index-content.platforms.learn_more}" %>"

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
  title: "<% "{index-content.actions_title}" %>"
  description: "<% "{index-content.actions_description_index}" %>"

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
  title: "<% "{index-content.faq.title}" %>"
  description: "<% "{index-content.faq.description}" %>"

  items:
    # items loop
    - question: "<% "{index-content.faq.item_1.question}" %>"
      answer: "<% "{index-content.faq.item_1.answer}" %>"

    # items loop
    - question: "<% "{index-content.faq.item_2.question}" %>"
      answer: "<% "{index-content.faq.item_2.answer}" %>"

    # items loop
    - question: "<% "{index-content.faq.item_3.question}" %>"
      answer: "<% "{index-content.faq.item_3.answer}" %>"

############################# Cloud Links ###############################
cloud_links:
  enable: true
  title: "<% "{index-content.cloud_links.title}" %>"
  description: "<% "{index-content.cloud_links.description}" %>"
  
  items:
    # items loop
    - title: "GroupDocs.Comparison Cloud for cURL"
      content: "<% "{index-content.cloud_links.item_1.content}" %>"
      icon: "groupdocs_comparison-for-curl"
      link: "https://products.groupdocs.cloud/comparison/curl"

    # items loop
    - title: "GroupDocs.Comparison Cloud for .NET"
      content: "<% "{index-content.cloud_links.item_2.content}" %>"
      icon: "groupdocs_comparison-for-net"
      link: "https://products.groupdocs.cloud/comparison/net"

    # items loop
    - title: "GroupDocs.Comparison Cloud for Java"
      content: "<% "{index-content.cloud_links.item_3.content}" %>"
      icon: "groupdocs_comparison-for-java"
      link: "https://products.groupdocs.cloud/comparison/java"

############################# App links ###############################
app_links:
  enable: true
  title: "<% "{index-content.app_links.title}" %>"
  description: "<% "{index-content.app_links.description}" %>"

  items:
    # items loop
    - title: "GroupDocs.Comparison Total"
      content: "<% "{index-content.app_links.item_1.content}" %>"
      icon: "groupdocs_comparison-app"
      link: "https://products.groupdocs.app/comparison/total"

    # items loop
    - title: "GroupDocs.Comparison DOCX"
      content: "<% "{index-content.app_links.item_2.content}" %>"
      icon: "groupdocs_words-app"
      link: "https://products.groupdocs.app/comparison/docx"

    # items loop
    - title: "GroupDocs.Comparison PDF"
      content: "<% "{index-content.app_links.item_3.content}" %>"
      icon: "groupdocs_pdf-app"
      link: "https://products.groupdocs.app/comparison/pdf"


      


---