<% configRef "..\\configs\\formats\\net_popular.yml" %>
<% include "..\\data\\format_data.md" %>

---
############################# Static ############################
layout: "format"
date:  <% date "utcnow" %>
draft: false
lang: <% lower ( get "lang") %>
format: <% get "FileformatCap" %>
product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "<% (dict "{fileformat}.head.title") %>"
head_description: "<% (dict "{fileformat}.head.description") %>"

############################# Header ############################
title: "<% (dict "{fileformat}.header.title") %>" 
description: "<% (dict "{fileformat}.header.description") %>"
subtitle: "<% "{common.header.subtitle}" %>" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "<% "{common.header.action_title}" %>"
      link: "<% get "ReleaseDownloads" %>"
      
############################# About ############################
about:
    enable: true
    title: "<% (dict "{fileformat}.about.title") %>"
    link: "/comparison/<% get "ProdCode" %>/"
    link_title: "<% "{common-content.texts.learn_more}" %>"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       <% (dict "{fileformat}.about.content") %>

############################# Steps ############################
steps:
    enable: true
    title: "<% (dict "{fileformat}.steps.title") %>"
    content: |
      <% (dict "{fileformat}.steps.content.title") %>
      
      1. <% (dict "{fileformat}.steps.content.step_1") %>
      2. <% (dict "{fileformat}.steps.content.step_2") %>
      3. <% (dict "{fileformat}.steps.content.step_3") %>
      4. <% (dict "{fileformat}.steps.content.step_4") %>
   
    code:
      platform: "net"
      copy_title: "<% (dict "common-content.format-code.copy_title") %>"
      install:
        command: "dotnet add package GroupDocs.Comparison"
        copy_tip: "<% (dict "common-content.format-code.copy_tip") %>"
        copy_done: "<% (dict "common-content.format-code.copy_done") %>"
      links:
        #  loop
        - title: "<% (dict "common-content.format-code.links.title_1") %>"
          link: "<% get "MoreLink" %>"
        #  loop
        - title: "<% (dict "common-content.format-code.links.title_2") %>"
          link: "<% get "DocsUrl" %>"
          
      content: |
        ```csharp {style=abap}

        // <% (dict "{fileformat}.steps.code.comments.comment_1") %>

        // <% (dict "{fileformat}.steps.code.comments.comment_2") %>
        using (Comparer comparer = new Comparer("source.<% get "fileformat" %>"))
        {
            // <% (dict "{fileformat}.steps.code.comments.comment_3") %>
        	comparer.Add("file_to_compare_1.<% get "fileformat" %>");
            comparer.Add("file_to_compare_2.<% get "fileformat" %>");
            comparer.Add("file_to_compare_3.<% get "fileformat" %>");

            // <% (dict "{fileformat}.steps.code.comments.comment_4") %>
            comparer.Compare("result.<% get "fileformat" %>"); 
        }
        
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "<% "{common-content.format-actions.title}" %>"
  description: "<% "{common-content.format-actions.description}" %>"
  items:
    #  loop
    - title: "<% "{common-content.format-actions.comment_1}" %>"
      link: "<% get "ReleaseDownloads" %>"
      color: "red"
        #  loop
    - title: "<% "{common-content.format-actions.comment_2}" %>"
      link: "<% get "PricesUrl" %>"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "<% (dict "{fileformat}.formats.title") %>"
    exclude: "<% get "FileFormatUp" %>"
    description: "<% (dict "{fileformat}.formats.description") %>"
<% include "..\\data\\format_others.md" %>

---