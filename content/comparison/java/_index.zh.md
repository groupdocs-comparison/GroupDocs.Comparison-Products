---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "Java 文档比较 API |比较 PDF Word Excel HTML 的文本和样式"
head_description: "Java 文档比较 API 用于比较和合并 Word Excel PPTX OpenOffice、Web、PDF、AutoCAD 和其他文件格式。将文档与跟踪更改进行比较."

############################# Header ############################
title: "用于比较和合并文档的 Java API"
description: "构建 Java 应用程序以有效地比较内容和文本样式，以检查所有行业标准文档和图像文件格式的差异."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "下载免费试用版"
    link: "https://downloads.groupdocs.com/comparison/java"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Comparison for Java"
        image: "/border/groupdocs-comparison-java.svg"
        product: "GroupDocs.Comparison"
        platform: "Java"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "概述"

            # button loop
            - link: "#features"
              text: "特征"

            # button loop
            - link: "#support"
              text: "Support"

            # button loop
            - link: "https://products.groupdocs.app/comparison"
              text: "Live Demo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/java"
              text: "价钱"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# 概述 ############################
overview:
    enable: true
    content: |
      GroupDocs.Comparison for Java 是最灵活和易于使用的 API，有助于在 Java 环境中开发文档比较应用程序。差异检查器和文档合并 API 使您能够检测相似文档格式之间的内容变化和差异以及文本样式。它支持比较所有行业标准文档格式，例如 PDF、HTML、微软办公软件 Word、Excel 电子表格、PowerPoint 演示文稿、Outlook 电子邮件、Visio 图表、OpenDocument、AutoCAD 和图像。使用更改跟踪功能，源文档和目标文档之间的差异摘要将呈现在一个全面的比较文档中。 GroupDocs.Comparison for Java API 允许通过文件和流获取和保存简单的、受密码保护的以及加密的文档。  
        
      GroupDocs.Comparison for Java 不需要在系统上安装任何外部软件。它与所有 Java 版本兼容，并支持能够运行 Java 运行时的流行操作系统（Windows、Linux、MacOS）。
    tabs:
      enable: true     
      
      ## TAB ONE ##
      tab_one:
        description: |
          以下是 Java 的 GroupDocs.Comparison 概述：

        right:
          enable: true
          icon: "fab fa-html5"
          title: "概述"
          content: |
            * 比较内容和样式
            * 获取比较摘要
            * 接受/拒绝 Word 中的更改
            * 合并和比较 3 个 Word 文件
            * 支持流
            * 通过流进行文件类型检测
            * 比较受保护的文件
            * 比较加密文件
            * 将比较另存为图像
            * 比较 Word 中的特定页面
            * 比较 PDF 中的水印
            * 应用/放弃更改
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison for Java 支持所有流行的 [文档文件格式](https://docs.groupdocs.com/comparison/java/supported-document-formats/)，包括：微软办公软件、图像、图表等。

        left:
          enable: true
          table:
            # table loop
            - title: "微软办公软件"
              content: |
                * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
                * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX, XLAM, SXC, SpreadsheetML
                * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM
                * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
                * **Outlook:** MSG, EML, EMLX, PST, OST
                * **OneNote:** ONE

        right:
          enable: true
          table:
            # table loop
            - title: "其他格式"
              content: |
                * **Языки программирования**: CS, Java, CPP, JS, PY, RB, PL, ASM, GROOVY, JSON, ActionScript, PHP, SQL, LOG, DIFF, LESS, SCALA
                * **OpenDocument**: ODT, OTT, ODS, ODP, OTP
                * **Портативный**: PDF, MOBI
                * **AutoCAD**: DXF, DWG
                * **Электронная почта**: EML, EMLX, MSG
                * **Изображения**: JPEG, BMP, PNG, GIF, DCM, DICOM, DjVu
                * **Интернет**: HTM, HTML, MHTML
                * **Текст**: TXT

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Comparison for Java 支持以下框架、框架和管理器:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "操作系统"
              content: |
                * Microsoft Windows Desktop
                * Microsoft Windows Server
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "支持的框架"
              content: |
                * Java 7 (1.7) 及更高版本

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-cogs"
              title: "开发环境"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse
            # table loop
            - icon: "fas fa-tools"
              title: "构建自动化工具"
              content: |
                * Maven

############################# 特征 ############################
features:
    enable: true
    title: "GroupDocs.Java 特性比较"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "比较和识别内容和文本样式的变化"

      # feature loop
      - icon: "fas fa-eye"
        content: "保存比较文档的汇总比较列表"

      # feature loop
      - icon: "fas fa-bolt"
        content: "比较 Word 文档的特定页面"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "合并多达 3 个 Microsoft Word 文件以比较支持“跟踪更改”"

      # feature loop
      - icon: "fas fa-code"
        content: "在比较期间轻松发现哪些更改来自哪个文档"

      # feature loop
      - icon: "fas fa-cloud"
        content: "支持读取源文档并通过流发送结果文档"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "从流中获取时检测文件格式的类型"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "比较受密码保护的文档"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "将比较结果另存为图像"

      # feature loop
      - icon: "fas fa-border-all"
        content: "比较不同的文件格式作为图像"

      # feature loop
      - icon: "fas fa-wrench"
        content: "比较 PDF 文档中的水印"

      # feature loop
      - icon: "fas fa-columns"
        content: "比较文件或流中的文档并通过流或文件发送结果文档"

      # feature loop
      - icon: "fas fa-file-word"
        content: "比较 Word、PDF 或 Excel 文件后接受或放弃更改"

      # feature loop
      - icon: "fas fa-envelope"
        content: "通过文件或流比较加密文档"

      # feature loop
      - icon: "fas fa-print"
        content: "比较操作的计量许可选项"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "比较 PDF、Word、Excel、PowerPoint 和 Note 文档时突出显示标记更改的文本"

      # feature loop
      - icon: "fas fa-lock"
        content: "计算 PDF、PowerPoint 幻灯片和图表中更改的正确坐标"

      # feature loop
      - icon: "fas fa-file-code"
        content: "比较多个（两个以上）PDF、Excel、OneNote、图表、电子邮件和文本文档"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "比较支持的文件格式的页眉和页脚"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "比较文档并将不同格式的文档页面保存为图像"

    more_feature:
      # more_feature_loop
      - title: "使用 Java API 轻松比较文档"
        content: |
          通过 GroupDocs.Comparison for Java API，您可以轻松比较支持格式的文档以发现它们之间的差异。以下示例显示了如何使用 Java 比较两个 Microsoft Word 文档：
          
          ```java
          try (Comparer comparer = new Comparer("D:\\source.pdf")) {
              comparer.add("D:\\target.pdf");
              comparer.compare("D:\\result.pdf");
          }
          ```
      # more_feature_loop
      - title: "指定比较详细级别"
        content: "GroupDocs.Comparison for Java 允许您在三个层次上比较文档。您可以将比较强度设置为低（逐字比较文本，成像网格的精度 = 50）、中（逐个字符比较文本，成像网格的精度 = 100）或高（逐个字符比较文本，成像精度网格 = 150)."

      # more_feature_loop
      - title: "比较文本样式"
        content: |
            除了文档内容，Java API 的 GroupDocs.Comparison 还允许比较文本样式. 字体名称、大小、颜色、样式（粗体、斜体、下划线、小型大写字母和超链接）以及如果适用的话，还可以比较底色以检查比较文档之间的差异，同时比较单词和字符。对于段落比较，还可以比较对齐方式、缩进（左缩进、右缩进）、间距（后空格、前空格）、首行缩进和行距。同样，只要适用，页面的其他部分也可以通过 GroupDocs.Comparison for Java API 进行比较。这些部分包括页脚距离、页边距（左、右、上、下）、页面高度、页面方向、边框颜色和线宽

############################# Support ############################

support:
    enable: true

############################# Solutions ############################

solutions:
    enable: true
    title: "GroupDocs.Comparison 为其他流行的开发环境提供文档查看 API"

    solution:
        - img_alt: "GroupDocs.Comparison for .NET"
          image: "/border/groupdocs-comparison-net.svg"
          product: "GroupDocs.Comparison"
          platform: ".NET"
          link: "/comparison/net/"

############################# Back to top ###############################
back_to_top:
  enable: true
---