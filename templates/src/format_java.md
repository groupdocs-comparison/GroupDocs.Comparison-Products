<% configRef "..\\configs\\formats\\java.yml" %>
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
platform: "Java"
platform_tag: "java"

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
    link: "/comparison/<% get "ProductCode" %>/"
    link_title: "<% "{common.about.link_title}" %>"
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
      copy_title: "<% "{common.steps.code.copy_title}" %>"
      install:
        command: "dotnet add package GroupDocs.Comparison"
        copy_tip: "<% "{common.steps.code.copy_tip}" %>"
        copy_done: "<% "{common.steps.code.copy_done}" %>"
      links:
        #  loop
        - title: "<% "{common.steps.code.links.title_1}" %>"
          link: "<% get "MoreLink" %>"
        #  loop
        - title: "<% "{common.steps.code.links.title_2}" %>"
          link: "<% get "DocsLink" %>"
          
      content: |
        ```csharp {style=abap}

        // <% "{common.steps.code.comments.comment_1}" %>

        // <% "{common.steps.code.comments.comment_2}" %>
        using (Comparer comparer = new Comparer("source.<% get "fileformat" %>"))
        {
            // <% "{common.steps.code.comments.comment_3}" %>
        	comparer.Add("target1.<% get "fileformat" %>");
            comparer.Add("target2.<% get "fileformat" %>");
            comparer.Add("target3.<% get "fileformat" %>");

            // <% "{common.steps.code.comments.comment_4}" %>
            comparer.Compare("result.<% get "fileformat" %>"); 
        }
        
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "<% "{common.actions.title}" %>"
  description: "<% "{common.actions.description}" %>"
  items:
    #  loop
    - title: "<% "{common.actions.items.comment_1}" %>"
      link: "<% get "ReleaseDownloads" %>"
      color: "red"
        #  loop
    - title: "<% "{common.actions.items.comment_2}" %>"
      link: "<% get "PricesLink" %>"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "<% "{common.formats.title}" %>"
    exclude: "<% get "FileFormatUp" %>"
    description: "<% "{common.formats.description}" %>"
<% include "..\\data\\format_others.md" %>

---