<% configRef "..\\configs\\index\\index_net.yml" %>
<% include "..\\data\\platform_data.md" %>

---
############################# Static ############################
layout: "landing"
date: <% date "utcnow" %>
draft: false

lang: <% lower ( get "lang") %>
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
    # supported_platforms loop
    - title: "Python"
      tag: "python-net"

############################# Head ############################
head_title: "<% "{index-content-net.head_title}" %>"
head_description: "<% "{index-content-net.head_description}" %>"

############################# Header ############################
title: "<% "{index-content-net.title}" %>"
description: "<% "{index-content-net.description}" %>"
words:
  for: "<% "{index-content.words_for}" %>"

actions:
  main: "<% "{index-content-net.actions_main}" %>"
  main_link: "<% get "PackageUrl" %>"
  alt: "<% "{index-content.actions_alt}" %>"
  alt_link: "<% get "PricesUrl" %>"
  title: "<% "{index-content.actions_title}" %>"
  description: "<% "{index-content.actions_description}" %>"

release:
  title: "<% "{index-content.release_title}" %>"
  notes: "<% "{index-content.release_notes}" %>"
  downloads: "<% "{index-content.release_downloads}" %>"

code:
  title: "<% "{index-content-net.code_title}" %>"
  more: "<% "{index-content.code_more}" %>"
  more_link: "<% dict "products.net.more_link" %>"
  install: "dotnet add package GroupDocs.Comparison"
  content: |
    ```csharp {style=abap}   
    // <% "{index-content.code_comment_1}" %>
    using (Comparer comparer = new Comparer("source.docx"))
    {
        // <% "{index-content.code_comment_2}" %>
        comparer.Add("target.docx");

        // <% "{index-content.code_comment_3}" %>
        CompareOptions options = new CompareOptions() 
        {ShowRevisions = false};

        // <% "{index-content.code_comment_4}" %>
        comparer.Compare("result.docx", options);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "<% "{index-content.overview_title}" %>"
  description: "<% "{index-content-net.overview_description}" %>"
  features:
    # feature loop
    - title: "<% "{index-content-net.overview_feature_1.title}" %>"
      content: "<% "{index-content-net.overview_feature_1.description}" %>"

    # feature loop
    - title: "<% "{index-content-net.overview_feature_2.title}" %>"
      content: "<% "{index-content-net.overview_feature_2.description}" %>"

    # feature loop
    - title: "<% "{index-content-net.overview_feature_3.title}" %>"
      content: "<% "{index-content-net.overview_feature_3.description}" %>"

    # feature loop
    - title: "<% "{index-content-net.overview_feature_4.title}" %>"
      content: "<% "{index-content-net.overview_feature_4.description}" %>"

############################# Platforms ############################
platforms:
  enable: true
  title: "<% "{index-content.platforms_title}" %>"
  description: "<% "{index-content-net.platforms_description}" %>"
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
  title: "<% "{index-content.formats_title}" %>"
  description: |
    <% "{index-content-net.formats_description}" %>
  groups:
    # group loop
    - color: "green"
      content: |
        ### <% "{index-content.formats_groups.title_1}" %>
        * **Word:** DOCX, DOC, DOCM,DOT, DOTM, DOTX, RTX, RTF, TXT
        * **Excel:** XLSX, XLS, XLT, XLTM, XLSB, XLSM
        * **PowerPoint:** PPTX, PPT, POT, POTX, PPS, PPSX
        * **Outlook:** EML, EMLX, MSG
        * **OneNote:** ONE
        * **OpenDocument:** ODT, ODP, OTP, ODS, OTT
        * **<% "{index-content.formats_groups.format_fixed_page_layout}" %>:** PDF        
    # group loop
    - color: "blue"
      content: |
        ### <% "{index-content.formats_groups.title_2}" %>
        * **<% "{index-content.formats_groups.format_raster_images}" %>:** BMP, GIF, JPG, JPEG, PNG
        * **<% "{index-content.formats_groups.format_medical_imaging}" %>:** DICOM
        * **Microsoft Visio:** VSDX, VSD, VSS, VST, VDX
        * **AutoCAD Drawing:** DWG, DXF
      # group loop
    - color: "red"
      content: |
        ### <% "{index-content.formats_groups.title_3}" %>
        * **<% "{index-content.formats_groups.format_text}" %>:** TXT
        * **<% "{index-content.formats_groups.format_programming_languages}" %>:** CS, Java, CPP, JS, PY, RB, PL, ASM, GROOVY, JSON, PHP, SQL, LOG, DIFF, LESS, SCALA
        * **<% "{index-content.formats_groups.format_web}" %>:** HTM, HTML, MHT, MHTML
        * **<% "{index-content.formats_groups.format_e_books}" %>:** MOBI, DjVu
        * **<% "{index-content.formats_groups.format_delimiter_separated_values}" %>:** CSV

############################# Features ############################
features:
  enable: true
  title: "<% "{index-content-net.features.title}" %>"
  description: "<% "{index-content-net.features.description}" %>"

  items:
    # feature loop
    - icon: "compare"
      title: "<% "{index-content-net.features.feature_1.title}" %>"
      content: "<% "{index-content-net.features.feature_1.content}" %>"

    # feature loop
    - icon: "note-stack"
      title: "<% "{index-content-net.features.feature_2.title}" %>"
      content: "<% "{index-content-net.features.feature_2.content}" %>"

    # feature loop
    - icon: "stacks"
      title: "<% "{index-content-net.features.feature_3.title}" %>"
      content: "<% "{index-content-net.features.feature_3.content}" %>"

    # feature loop
    - icon: "rule"
      title: "<% "{index-content-net.features.feature_4.title}" %>"
      content: "<% "{index-content-net.features.feature_4.content}" %>"

    # feature loop
    - icon: "preview"
      title: "<% "{index-content-net.features.feature_5.title}" %>"
      content: "<% "{index-content-net.features.feature_5.content}" %>"

    # feature loop
    - icon: "two-pager"
      title: "<% "{index-content-net.features.feature_6.title}" %>"
      content: "<% "{index-content-net.features.feature_6.content}" %>"

    # feature loop
    - icon: "format_color_text"
      title: "<% "{index-content-net.features.feature_7.title}" %>"
      content: "<% "{index-content-net.features.feature_7.content}" %>"

    # feature loop
    - icon: "folder-managed"
      title: "<% "{index-content-net.features.feature_8.title}" %>"
      content: "<% "{index-content-net.features.feature_8.content}" %>"

    # feature loop
    - icon: "lock"
      title: "<% "{index-content-net.features.feature_9.title}" %>"
      content: "<% "{index-content-net.features.feature_9.content}" %>"

    # feature loop
    - icon: "select"
      title: "<% "{index-content-net.features.feature_10.title}" %>"
      content: "<% "{index-content-net.features.feature_10.content}" %>"

    # feature loop
    - icon: "speaker-notes"
      title: "<% "{index-content-net.features.feature_11.title}" %>"
      content: "<% "{index-content-net.features.feature_11.content}" %>"

############################# Code samples ############################
code_samples:
  enable: true
  title: "<% "{index-content.code_samples.title}" %>"
  description: "<% "{index-content-net.code_samples_description}" %>"
  items:
    # code sample loop
    - title: "<% "{index-content-net.code_title_sample_1}" %>"
      content: |
        <% "{index-content-net.code_samples_sample_1_content}" %>
        {{< landing/code title="<% "{index-content.code_samples.sample_1.code_title}" %>">}}
        ```csharp {style=abap}
        // <% "{index-content.code_samples.sample_1.comment_1}" %>
        using(Comparer comparer = new Comparer("source.docx", new LoadOptions() {Password = "1234"}))  
        {
            // <% "{index-content.code_samples.sample_1.comment_2}" %>
            comparer.Add("target.docx", new LoadOptions() {Password = "5678"});

            // <% "{index-content.code_samples.sample_1.comment_3}" %>
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "<% "{index-content-net.code_title_sample_2}" %>"
      content: |
        <% "{index-content-net.code_samples_sample_2_content}" %>
        {{< landing/code title="<% "{index-content.code_samples.sample_2.code_title}" %>">}}
        ```csharp {style=abap}   
        // <% "{index-content.code_samples.sample_2.comment_1}" %>
        using(Comparer comparer = new Comparer("source.docx") 
        {
            // <% "{index-content.code_samples.sample_2.comment_2}" %>
            comparer.Add("target2.docx");
            
            // <% "{index-content.code_samples.sample_2.comment_3}" %>
            comparer.Add("target3.docx");
            
            // <% "{index-content.code_samples.sample_2.comment_4}" %>
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---
