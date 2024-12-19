
---
############################# Static ############################
layout: "format"
date:  2024-12-19T07:49:54
draft: false
lang: zh
format: Log
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

############################# Head ############################
head_title: "使用 JavaScript 库比较 LOG。"
head_description: "GroupDocs.Comparison for Node.js via Java 提供软件来为 Node.js 个应用程序生成详细的差异检查报告。"

############################# Header ############################
title: "比较您在 Node.js 中的 LOG 个文件" 
description: "基于 Node.js 的文档比较库提供了收集和显示有关 LOG 文件中任何区别的数据的机会。使用 GroupDocs.Comparison 提高解决方案在文件比较任务中的生产力。"
subtitle: "文件比较解决方案" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "免费 NPM 下载"
      link: "https://releases.groupdocs.com/comparison/nodejs-java/"
      
############################# About ############################
about:
    enable: true
    title: "探索 GroupDocs.Comparison for Node.js via Java 的特点"
    link: "/comparison/nodejs-java/"
    link_title: "了解更多"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison for Node.js via Java 是一个 API，可帮助比较相同格式的图片和文档。它可以发现比较文档之间的段落、文字、字符、形状和文本样式的差异。您可以合并这些更改并将其另存为最终文档。它可以很好地处理 PDF、Word 个文档、Excel 张页面、PowerPoint 张幻灯片、Visio 张图表、Outlook 封电子邮件、HTML、绘图和各种图像类型，所有这些都无需额外的工具。

############################# Steps ############################
steps:
    enable: true
    title: "如何使用 Node.js 执行 LOG 个文件比较。"
    content: |
      可以使用 LOG 文件使用 [GroupDocs.Comparison](https://products.groupdocs.com/comparison/nodejs-java/) 来获取有关许多 LOG 文件差异的报告
      
      1. 使用 [NPM](https://www.npmjs.com/package/@groupdocs/groupdocs.comparison) 安装 GroupDocs.Comparison for Node.js via Java
      2. 实例化比较器并以 LOG 格式提供第一个文件的路径
      3. 将另一个 LOG 文件添加到 Comparer
      4. 获取一份准确描述差异的清晰报告
   
    code:
      platform: "net"
      copy_title: "复制"
      install:
        command: "npm i @groupdocs/groupdocs.comparison"
        copy_tip: "点击复制"
        copy_done: "复制的"
      links:
        #  loop
        - title: "更多例子"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java"
        #  loop
        - title: "文档"
          link: "https://docs.groupdocs.com/comparison/nodejs-java/"
          
      content: |
        ```javascript {style=abap}

        // 检查多个文件以查看它们有何相似或不同之处

        // 创建 Comparer 对象并将第一个文件作为输入
        const comparer = new groupdocs.comparison.Comparer('source.log');

        // 追加更多文件
        comparer.add('file_v1.log');
        comparer.add('file_2023.log');

        // 获取最终报告
        await comparer.compare('report_new.log');

        console.log('\nFiles are compared.\nCheck result.');

        ```            

############################# Actions ############################

actions:
  enable: true
  title: "准备好开始了吗？"
  description: "免费试用 GroupDocs.Comparison 项功能或申请许可证"
  items:
    #  loop
    - title: "NPM 下载"
      link: "https://releases.groupdocs.com/comparison/nodejs-java/"
      color: "red"
        #  loop
    - title: "许可"
      link: "https://purchase.groupdocs.com/pricing/comparison/nodejs-java/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "通过 JavaScript 比较常用文档类型"
    exclude: "LOG"
    description: "我们的 Node.js API 使您能够比较不同格式的文档。使用我们的工具进行处理，轻松跟踪文档更改。"
    items: 
        # format loop 1
        - name: "比较 PDF 个文件"
          format: "PDF"
          link: "/comparison/nodejs-java/pdf/"
          description: "Adobe Portable 文档格式"

        # format loop 2
        - name: "比较 DOCX 个文件"
          format: "DOCX"
          link: "/comparison/nodejs-java/docx/"
          description: "微软 Word 打开 XML 文档"

        # format loop 3
        - name: "比较 RTF 个文件"
          format: "RTF"
          link: "/comparison/nodejs-java/rtf/"
          description: "富文本文件格式"

        # format loop 4
        - name: "比较 TXT 个文件"
          format: "TXT"
          link: "/comparison/nodejs-java/txt/"
          description: "纯文本文件格式"

        # format loop 5
        - name: "比较 XLSX 个文件"
          format: "XLSX"
          link: "/comparison/nodejs-java/xlsx/"
          description: "微软 Excel 打开 XML 电子表格"

        # format loop 6
        - name: "比较 CSV 文件"
          format: "CSV"
          link: "/comparison/nodejs-java/csv/"
          description: "逗号分隔值文件"

        # format loop 7
        - name: "比较 PPTX 个文件"
          format: "PPTX"
          link: "/comparison/nodejs-java/pptx/"
          description: "PowerPoint 打开 XML 演示文稿"

        # format loop 8
        - name: "比较 ODS 个文件"
          format: "ODS"
          link: "/comparison/nodejs-java/ods/"
          description: "Open Document 电子表格"

        # format loop 9
        - name: "比较 ODP 文件"
          format: "ODP"
          link: "/comparison/nodejs-java/odp/"
          description: "OpenDocument 演示文件格式"

        # format loop 10
        - name: "比较 ODT 个文件"
          format: "ODT"
          link: "/comparison/nodejs-java/odt/"
          description: "Open Document 文本"

        # format loop 11
        - name: "比较 JPEG 个文件"
          format: "JPEG"
          link: "/comparison/nodejs-java/jpeg/"
          description: "JPEG 图片"

        # format loop 12
        - name: "比较 PNG 个文件"
          format: "PNG"
          link: "/comparison/nodejs-java/png/"
          description: "Portable 网络图形"

        # format loop 13
        - name: "比较 GIF 个文件"
          format: "GIF"
          link: "/comparison/nodejs-java/gif/"
          description: "图形交换格式文件"

        # format loop 14
        - name: "比较 BMP 个文件"
          format: "BMP"
          link: "/comparison/nodejs-java/bmp/"
          description: "位图文件格式"

        # format loop 15
        - name: "比较 HTML 文件"
          format: "HTML"
          link: "/comparison/nodejs-java/html/"
          description: "超文本标记语言"

        # format loop 16
        - name: "比较 MSG 个文件"
          format: "MSG"
          link: "/comparison/nodejs-java/msg/"
          description: "微软 Outlook 电子邮件"

        # format loop 17
        - name: "比较 ONE 个文件"
          format: "ONE"
          link: "/comparison/nodejs-java/one/"
          description: "微软 OneNote"

        # format loop 18
        - name: "比较 VSDX 个文件"
          format: "VSDX"
          link: "/comparison/nodejs-java/vsdx/"
          description: "微软 Visio 绘图"

        # format loop 19
        - name: "比较 CS 文件"
          format: "CS"
          link: "/comparison/nodejs-java/cs/"
          description: "cSharp 语言"

        # format loop 20
        - name: "比较 Java 个文件"
          format: "Java"
          link: "/comparison/nodejs-java/java/"
          description: "Java 语言"
          
        # format loop 21
        - name: "比较 CPP 文件"
          format: "CPP"
          link: "/comparison/nodejs-java/cpp/"
          description: "C++ 语言"
---