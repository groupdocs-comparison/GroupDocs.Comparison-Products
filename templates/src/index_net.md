<% configRef "..\\configs\\index\\index_net.yml" %>
---
############################# Static ############################
layout: "landing"
date: <% date "utcnow" %>
draft: false
product: "Comparison"
product_tag: "comparison"
platform: "Net"
platform_tag: "net"

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
  main_link: "<% dict "products.net.main_link" %>"
  alt: "<% "{index-content.actions_alt}" %>"
  alt_link: "<% dict "products.net.alt_link" %>"
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
    using (Comparer comparer = new Comparer("C:\\source.docx"))
    {
        // <% "{index-content.code_comment_2}" %>
        comparer.Add("C:\\target.docx");

        // <% "{index-content.code_comment_3}" %>
        CompareOptions options = new CompareOptions() {ShowRevisions = false};

        // <% "{index-content.code_comment_4}" %>
        comparer.Compare("C:\\result.docx", options);
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
        * **Word:** DOC, DOCM, DOCX, DOT, DOTM, DOTX, RTX, RTF, TXT
        * **Excel:** XLS, XLT, XLSX, XLTM, XLSB, XLSM, XLSX
        * **PowerPoint:** POT, POTX, PPS, PPSX, PPTX, PPT        
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
    - icon: "fas fa-columns"
      title: "<% "{index-content-net.features.feature_1.title}" %>"
      content: "<% "{index-content-net.features.feature_1.content}" %>"

    # feature loop
    - icon: "fas fa-border-all"
      title: "<% "{index-content-net.features.feature_2.title}" %>"
      content: "<% "{index-content-net.features.feature_2.content}" %>"

    # feature loop
    - icon: "complex"
      title: "<% "{index-content-net.features.feature_3.title}" %>"
      content: "<% "{index-content-net.features.feature_3.content}" %>"

    # feature loop
    - icon: "adjustment"
      title: "<% "{index-content-net.features.feature_4.title}" %>"
      content: "<% "{index-content-net.features.feature_4.content}" %>"

    # feature loop
    - icon: "fas fa-eye"
      title: "<% "{index-content-net.features.feature_5.title}" %>"
      content: "<% "{index-content-net.features.feature_5.content}" %>"

    # feature loop
    - icon: "fas fa-comment-slash"
      title: "<% "{index-content-net.features.feature_6.title}" %>"
      content: "<% "{index-content-net.features.feature_6.content}" %>"

    # feature loop
    - icon: "fas fa-remove-format"
      title: "<% "{index-content-net.features.feature_7.title}" %>"
      content: "<% "{index-content-net.features.feature_7.content}" %>"

    # feature loop
    - icon: "fas fa-wrench"
      title: "<% "{index-content-net.features.feature_8.title}" %>"
      content: "<% "{index-content-net.features.feature_8.content}" %>"

    # feature loop
    - icon: "fas fa-lock"
      title: "<% "{index-content-net.features.feature_9.title}" %>"
      content: "<% "{index-content-net.features.feature_9.content}" %>"

    # feature loop
    - icon: "fas fa-copy"
      title: "<% "{index-content-net.features.feature_10.title}" %>"
      content: "<% "{index-content-net.features.feature_10.content}" %>"

    # feature loop
    - icon: "fas fa-envelope"
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
        using(Comparer comparer = new Comparer("C:\\source.doc", new LoadOptions() {Password = "1234"}))  
        {
            // <% "{index-content.code_samples.sample_1.comment_2}" %>
            comparer.Add("C:\\target.docx", new LoadOptions() {Password = "5678"});

            // <% "{index-content.code_samples.sample_1.comment_3}" %>
            comparer.Compare("C:\\result.docx");
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
        using(Comparer comparer = new Comparer("C:\\source.doc") 
        {
            // <% "{index-content.code_samples.sample_2.comment_2}" %>
            comparer.Add("C:\\target2.docx");
            
            // <% "{index-content.code_samples.sample_2.comment_3}" %>
            comparer.Add("C:\\target3.docx");
            
            // <% "{index-content.code_samples.sample_2.comment_4}" %>
            comparer.Compare("C:\\result.docx");
        }
        ```
        {{< /landing/code >}}

---