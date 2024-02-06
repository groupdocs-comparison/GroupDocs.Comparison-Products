<% configRef "..\\configs\\index\\index_nodejs.yml" %>
---
############################# Static ############################
layout: "landing"
date: <% date "utcnow" %>
draft: false

lang: <% lower ( get "lang") %>
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

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
head_title: "<% "{index-content-nodejs-java.head_title}" %>"
head_description: "<% "{index-content-nodejs-java.head_description}" %>"

############################# Header ############################
title: "<% "{index-content-nodejs-java.title}" %>"
description: "<% "{index-content-nodejs-java.description}" %>"
words:
  for: "<% "{index-content-nodejs-java.words_for}" %>"

actions:
  main: "<% "{index-content-nodejs-java.actions_main}" %>"
  main_link: "<% dict "products.nodejs-java.main_link" %>"
  alt: "<% "{index-content-nodejs-java.actions_alt}" %>"
  alt_link: "<% dict "products.nodejs-java.alt_link" %>"
  title: "<% "{index-content-nodejs-java.actions_title}" %>"
  description: "<% "{index-content-nodejs-java.actions_description}" %>"

release:
  title: "<% "{index-content-nodejs-java.release_title}" %>"
  notes: "<% "{index-content-nodejs-java.release_notes}" %>"
  downloads: "<% "{index-content-nodejs-java.release_downloads}" %>"
  link: "<% "{products.nodejs-java.release_downloads}" %>"

code:
  title: "<% "{index-content-nodejs-java.code_title}" %>"
  more: "<% "{index-content-nodejs-java.code_more}" %>"
  more_link: "<% dict "products.nodejs-java.more_link" %>"
  install: "npm i @groupdocs/groupdocs.comparison"
  content: |
    ```javascript {style=abap}

    // <% "{index-content-nodejs-java.code_comment_1}" %>
    let comparer = new Comparer("source.bmp");

    // <% "{index-content-nodejs-java.code_comment_2}" %>
    comparer.add("target.bmp");

    // <% "{index-content-nodejs-java.code_comment_3}" %>
    comparer.compare("result.bmp"); 
    ```

############################# Overview ############################
overview:
  enable: true
  title: "<% "{index-content-nodejs-java.overview_title}" %>"
  description: "<% "{index-content-nodejs-java.overview_description}" %>"
  features:
    # feature loop
    - title: "<% "{index-content-nodejs-java.overview_feature_1.title}" %>"
      content: "<% "{index-content-nodejs-java.overview_feature_1.description}" %>"

    # feature loop
    - title: "<% "{index-content-nodejs-java.overview_feature_2.title}" %>"
      content: "<% "{index-content-nodejs-java.overview_feature_2.description}" %>"

    # feature loop
    - title: "<% "{index-content-nodejs-java.overview_feature_3.title}" %>"
      content: "<% "{index-content-nodejs-java.overview_feature_3.description}" %>"

############################# Platforms ############################
platforms:
  enable: true
  title: "<% "{index-content-nodejs-java.platforms_title}" %>"
  description: "<% "{index-content-nodejs-java.platforms_description}" %>"
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
  title: "<% "{index-content-nodejs-java.formats_title}" %>"
  description: |
    <% "{index-content-nodejs-java.formats_description}" %>
  groups:
    # group loop
    - color: "green"
      content: |
        ### <% "{index-content-nodejs-java.formats_groups.title_1}" %>
        * **Word:** DOC, DOCM, DOCX, DOT, DOTM, DOTX, RTX, RTF, TXT
        * **Excel:** XLS, XLT, XLSX, XLTM, XLSB, XLSM, XLSX
        * **PowerPoint:** POT, POTX, PPS, PPSX, PPTX, PPT        
        * **Outlook:** EML, EMLX, MSG
        * **OneNote:** ONE
        * **OpenDocument:** ODT, ODP, OTP, ODS, OTT
        * **<% "{index-content-nodejs-java.formats_groups.format_1_7}" %>:** PDF  
    # group loop
    - color: "blue"
      content: |
        ### <% "{index-content-nodejs-java.formats_groups.title_2}" %>
        * **<% "{index-content-nodejs-java.formats_groups.format_2_1}" %>:** BMP, GIF, JPG, JPEG, PNG
        * **<% "{index-content-nodejs-java.formats_groups.format_2_2}" %>:** DICOM
        * **Microsoft Visio:** VSDX, VSD, VSS, VST, VDX
        * **<% "{index-content-nodejs-java.formats_groups.format_2_4}" %>:** DWG, DXF
      # group loop
    - color: "red"
      content: |
        ### <% "{index-content-nodejs-java.formats_groups.title_3}" %>
        * **<% "{index-content-nodejs-java.formats_groups.format_3_1}" %>:** TXT
        * **<% "{index-content-nodejs-java.formats_groups.format_3_2}" %>:** CS, Java, CPP, JS, PY, RB, PL, ASM, GROOVY, JSON, PHP, SQL, LOG, DIFF, LESS, SCALA
        * **<% "{index-content-nodejs-java.formats_groups.format_3_3}" %>:** HTM, HTML, MHT, MHTML
        * **<% "{index-content-nodejs-java.formats_groups.format_3_4}" %>:** MOBI, DjVu
        * **<% "{index-content-nodejs-java.formats_groups.format_3_5}" %>:** CSV

############################# Features ############################
features:
  enable: true
  title: "<% "{index-content-nodejs-java.features.title}" %>"
  description: "<% "{index-content-nodejs-java.features.description}" %>"

  items:
    # feature loop
    - icon: "compare"
      title: "<% "{index-content-nodejs-java.features.feature_1.title}" %>"
      content: "<% "{index-content-nodejs-java.features.feature_1.content}" %>"

    # feature loop
    - icon: "note-stack"
      title: "<% "{index-content-nodejs-java.features.feature_2.title}" %>"
      content: "<% "{index-content-nodejs-java.features.feature_2.content}" %>"

    # feature loop
    - icon: "stacks"
      title: "<% "{index-content-nodejs-java.features.feature_3.title}" %>"
      content: "<% "{index-content-nodejs-java.features.feature_3.content}" %>"

    # feature loop
    - icon: "rule"
      title: "<% "{index-content-nodejs-java.features.feature_4.title}" %>"
      content: "<% "{index-content-nodejs-java.features.feature_4.content}" %>"

    # feature loop
    - icon: "preview"
      title: "<% "{index-content-nodejs-java.features.feature_5.title}" %>"
      content: "<% "{index-content-nodejs-java.features.feature_5.content}" %>"

    # feature loop
    - icon: "two-pager"
      title: "<% "{index-content-nodejs-java.features.feature_6.title}" %>"
      content: "<% "{index-content-nodejs-java.features.feature_6.content}" %>"

    # feature loop
    - icon: "format_color_text"
      title: "<% "{index-content-nodejs-java.features.feature_7.title}" %>"
      content: "<% "{index-content-nodejs-java.features.feature_7.content}" %>"

    # feature loop
    - icon: "folder-managed"
      title: "<% "{index-content-nodejs-java.features.feature_8.title}" %>"
      content: "<% "{index-content-nodejs-java.features.feature_8.content}" %>"

    # feature loop
    - icon: "lock"
      title: "<% "{index-content-nodejs-java.features.feature_9.title}" %>"
      content: "<% "{index-content-nodejs-java.features.feature_9.content}" %>"

    # feature loop
    - icon: "select"
      title: "<% "{index-content-nodejs-java.features.feature_10.title}" %>"
      content: "<% "{index-content-nodejs-java.features.feature_10.content}" %>"

    # feature loop
    - icon: "speaker-notes"
      title: "<% "{index-content-nodejs-java.features.feature_11.title}" %>"
      content: "<% "{index-content-nodejs-java.features.feature_11.content}" %>"

############################# Code samples ############################
code_samples:
  enable: true
  title: "<% "{index-content-nodejs-java.code_samples.title}" %>"
  description: "<% "{index-content-nodejs-java.code_samples.description}" %>"
  items:
    # code sample loop
    - title: "<% "{index-content-nodejs-java.code_samples.sample_1.title}" %>"
      content: |
        <% "{index-content-nodejs-java.code_samples.sample_1.content}" %>
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}
        import { Comparer, LoadOptions } from '@groupdocs/groupdocs.comparison'

        // <% "{index-content-nodejs-java.code_samples.sample_1.comment_1}" %>
        const comparer = new Comparer("source.doc", new LoadOptions("1234"));

        // <% "{index-content-nodejs-java.code_samples.sample_1.comment_2}" %>
        comparer.add("target.doc", new LoadOptions("5678"));

        // <% "{index-content-nodejs-java.code_samples.sample_1.comment_3}" %>
        comparer.compare("result.doc");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "<% "{index-content-nodejs-java.code_samples.sample_2.title}" %>"
      content: |
        <% "{index-content-nodejs-java.code_samples.sample_2.content}" %>
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}
        import { Comparer } from '@groupdocs/groupdocs.comparison'

        // <% "{index-content-nodejs-java.code_samples.sample_2.comment_1}" %>
        const comparer = new Comparer(source.pdf");

        // <% "{index-content-nodejs-java.code_samples.sample_2.comment_2}" %>
        comparer.add("target2.pdf");

        // <% "{index-content-nodejs-java.code_samples.sample_2.comment_3}" %>
        comparer.add("target3.pdf");

        // <% "{index-content-nodejs-java.code_samples.sample_2.comment_4}" %>
        comparer.compare("result.pdf");
        ```
        {{< /landing/code >}}

---
