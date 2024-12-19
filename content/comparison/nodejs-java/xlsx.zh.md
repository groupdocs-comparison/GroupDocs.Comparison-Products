
---
############################# Static ############################
layout: "format"
date:  2024-12-19T07:49:55
draft: false
lang: zh
format: Xlsx
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

############################# Head ############################
head_title: "比较 Node.js API 的 XLSX 个电子表格内容。"
head_description: "MS Excel 电子表格差异可以由我们的 Node.js API 检查，它会生成详细说明各种类型区别的信息报告。"

############################# Header ############################
title: "使用 Node.js via Java 比较电子表格" 
description: "使用 Node.js 中的文档处理库来识别和显示 Node.js via Java 应用程序中 MS Excel XLSX 文件中的更改。受益于快速轻松的报告生成。"
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
    title: "探索 GroupDocs.Comparison 的优势"
    link: "/comparison/nodejs-java/"
    link_title: "了解更多"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       访问详细报告，其中包含有关 GroupDocs.Comparison 提供的不同版本的 XLSX 文档的变更的丰富数据。只需几行代码，即可将 Node.js via Java 个应用程序与我们的 API 集成，无需额外努力。分析 MS Excel 个文档中页面、文本、文本样式或形状的变化。选择相应的数据并将它们合并到最终的 XLSX 文档中。使用我们的解决方案推进您的业务项目。

############################# Steps ############################
steps:
    enable: true
    title: "使用 JavaScript 中 XLSX 个文档的区别来撰写报告"
    content: |
      使用 [GroupDocs.Comparison](https://products.groupdocs.com/comparison/nodejs-java/) 和 Node.js via Java 进行 XLSX 文档比较
      
      1. 从 [NPM](https://www.npmjs.com/package/@groupdocs/groupdocs.comparison) 安装 Node.js via Java 的 GroupDocs.Comparison
      2. 调用 Comparer 构造函数时提供 XLSX 路径
      3. 包括其他 XLSX 个文件
      4. 享受生成的结果
   
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
        const comparer = new groupdocs.comparison.Comparer('first.xlsx');

        // 追加更多文件
        comparer.add('second.xlsx');
        comparer.add('third.xlsx');

        // 获取最终报告
        await comparer.compare('report_full.xlsx');

        console.log('\nDocuments compared successfully.\nCheck output.');
        
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
    title: "使用 JavaScript 进行 XLSX 个电子表格比较"
    exclude: "XLSX"
    description: "使用 GroupDocs.Comparison for Node.js via Java 轻松比较任何 MS Excel XLSX 电子表格。获得有关业务数据变化的宝贵见解。"
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