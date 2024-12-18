<% configRef "..\\configs\\formats\\net.yml" %>
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
head_title: "<% "{common.head.title}" %>"
head_description: "<% "{common.head.description}" %>"

############################# Header ############################
title: "<% "{common.header.title}" %>" 
description: "<% "{common.header.description}" %>"
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
    title: "<% "{common.about.title}" %>"
    link: "/comparison/<% get "ProdCode" %>/"
    link_title: "<% "{common-content.texts.learn_more}" %>"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       <% "{common.about.content}" %>

############################# Steps ############################
steps:
    enable: true
    title: "<% "{common.steps.title}" %>"
    content: |
      <% "{common.steps.content.title}" %>
      
      1. <% "{common.steps.content.step_1}" %>
      2. <% "{common.steps.content.step_2}" %>
      3. <% "{common.steps.content.step_3}" %>
      4. <% "{common.steps.content.step_4}" %>
   
    code:
      platform: "net"
      copy_title: "<% "{common-content.format-code.copy_title}" %>"
      result_enable: true
      result_link: "/examples/comparison/comparison_result.pdf"
      result_title: "<% "{common-content.format-code.result_title}" %>"
      install:
        command: "dotnet add package GroupDocs.Comparison"
        copy_tip: "<% "{common-content.format-code.copy_tip}" %>"
        copy_done: "<% "{common-content.format-code.copy_done}" %>"
      links:
        #  loop
        - title: "<% "{common-content.format-code.links.title_1}" %>"
          link: "<% get "MoreLink" %>"
        #  loop
        - title: "<% "{common-content.format-code.links.title_2}" %>"
          link: "<% get "DocsUrl" %>"
          
      content: |
        ```csharp {style=abap}

        // <% "{common.steps.code.comments.comment_1}" %>

        // <% "{common.steps.code.comments.comment_2}" %>
        using (Comparer comparer = new Comparer("main_document.<% get "fileformat" %>"))
        {
            // <% "{common.steps.code.comments.comment_3}" %>
        	comparer.Add("modified_1.<% get "fileformat" %>");
            comparer.Add("modified_2.<% get "fileformat" %>");

            // <% "{common.steps.code.comments.comment_4}" %>
            comparer.Compare("report.<% get "fileformat" %>"); 
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
    title: "<% "{common.formats.title}" %>"
    exclude: "<% get "FileFormatUp" %>"
    description: "<% "{common.formats.description}" %>"
<% include "..\\data\\format_others.md" %>

---