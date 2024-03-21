
---
############################# Static ############################
layout: "format"
date:  2024-03-21T15:26:18
draft: false
lang: zh
format: Docx
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "DOCX 文档差异检查的解决方案。"
head_description: "GroupDocs.Comparison API 提供的机会使我们能够检索包含有关 DOCX 文档中区别信息的报告。"

############################# Header ############################
title: "Java 个用于在 DOCX 个文档中搜索区别的应用程序" 
description: "GroupDocs.Comparison 提供的 Java 库比较了支持 Java、J2EE 或 J2SE 的应用程序中的任何 DOCX 个文档。"
subtitle: "文件差异检查框架"  

header_actions:
  enable: true
  items:
    #  loop
    - title: "免费 Maven 下载"
      link: "https://releases.groupdocs.com/comparison/java/"
      
############################# About ############################
about:
    enable: true
    title: "探索 GroupDocs.Comparison for Java API 的优势"
    link: "/comparison/java/"
    link_title: "了解更多"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       DOCX 文档比较由 GroupDocs.Comparison for Java API 支持，该API可撰写包含有关各种区别的数据的报告。正在分析段落中的文本、形状和样式以及其他数据。此外，可以编写一个 DOCX 个合并初始文件的变更。无需在任何外部库中使用。添加几行代码即可改进您的 Java 项目。

############################# Steps ############################
steps:
    enable: true
    title: "使用 Java 比较多个 DOCX 个文件"
    content: |
      使用 [GroupDocs.Comparison](https://products.groupdocs.com/comparison/java/) 比较 MS Word 个文档
      
      1. 从 [Maven](https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/) 安装我们的解决方案
      2. 必须使用第一个 DOCX 个文档作为参数来创建比较器
      3. 任何比较都需要多个 DOCX 份文档
      4. 生成的报告提供了有用的数据
   
    code:
      platform: "net"
      copy_title: "复制"
      install:
        command: |
          <dependencies>
            <dependency>
              <groupId>com.groupdocs</groupId>
              <artifactId>groupdocs-comparison</artifactId>
              <version>{0}</version>
            </dependency>
          </dependencies>

          <repositories>
            <repository>
              <id>repository.groupdocs.com</id>
              <name>GroupDocs Repository</name>
              <url>https://repository.groupdocs.com/repo/</url>
            </repository>
          </repositories>
        copy_tip: "点击复制"
        copy_done: "复制的"
      links:
        #  loop
        - title: "更多例子"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
        #  loop
        - title: "文档"
          link: "https://docs.groupdocs.com/comparison/java/"
          
      content: |
        ```java {style=abap}

        // 检查硬盘中的文件是否存在差异或相似之处

        // 通过指定初始文件创建 Comparer 对象
        try (Comparer comparer = new Comparer("main.docx") 
        {
            // 添加其他文件进行比较
        	comparer.add("version1.docx");
            comparer.add("version2.docx");
            comparer.add("version3.docx");

            // 获取以指定名称作为结果的报告
            final Path resultPath = comparer.compare("full_report.docx"); 

            System.out.println("\nDocuments compared successfully.");
        }
        
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "准备好开始了吗？"
  description: "免费试用 GroupDocs.Comparison 项功能或申请许可证"
  items:
    #  loop
    - title: "Maven 下载"
      link: "https://releases.groupdocs.com/comparison/java/"
      color: "red"
        #  loop
    - title: "许可"
      link: "https://purchase.groupdocs.com/pricing/comparison/java/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "使用 Java 控制 DOCX 个文件的任何更改"
    exclude: "DOCX"
    description: "GroupDocs.Comparison Java API 允许用户通过易于处理的精确而详细的报告来控制 DOCX 个文档版本。"
    items: 
        # format loop 1
        - name: "比较 PDF 个文件"
          format: "PDF"
          link: "/comparison/java/pdf/"
          description: "Adobe Portable 文档格式"

        # format loop 2
        - name: "比较 DOCX 个文件"
          format: "DOCX"
          link: "/comparison/java/docx/"
          description: "微软 Word 打开 XML 文档"

        # format loop 3
        - name: "比较 RTF 个文件"
          format: "RTF"
          link: "/comparison/java/rtf/"
          description: "富文本文件格式"

        # format loop 4
        - name: "比较 TXT 个文件"
          format: "TXT"
          link: "/comparison/java/txt/"
          description: "纯文本文件格式"

        # format loop 5
        - name: "比较 XLSX 个文件"
          format: "XLSX"
          link: "/comparison/java/xlsx/"
          description: "微软 Excel 打开 XML 电子表格"

        # format loop 6
        - name: "比较 CSV 文件"
          format: "CSV"
          link: "/comparison/java/csv/"
          description: "逗号分隔值文件"

        # format loop 7
        - name: "比较 PPTX 个文件"
          format: "PPTX"
          link: "/comparison/java/pptx/"
          description: "PowerPoint 打开 XML 演示文稿"

        # format loop 8
        - name: "比较 ODS 个文件"
          format: "ODS"
          link: "/comparison/java/ods/"
          description: "Open Document 电子表格"

        # format loop 9
        - name: "比较 ODP 文件"
          format: "ODP"
          link: "/comparison/java/odp/"
          description: "OpenDocument 演示文件格式"

        # format loop 10
        - name: "比较 ODT 个文件"
          format: "ODT"
          link: "/comparison/java/odt/"
          description: "Open Document 文本"

        # format loop 11
        - name: "比较 JPEG 个文件"
          format: "JPEG"
          link: "/comparison/java/jpeg/"
          description: "JPEG 图片"

        # format loop 12
        - name: "比较 PNG 个文件"
          format: "PNG"
          link: "/comparison/java/png/"
          description: "Portable 网络图形"

        # format loop 13
        - name: "比较 GIF 个文件"
          format: "GIF"
          link: "/comparison/java/gif/"
          description: "图形交换格式文件"

        # format loop 14
        - name: "比较 BMP 个文件"
          format: "BMP"
          link: "/comparison/java/bmp/"
          description: "位图文件格式"

        # format loop 15
        - name: "比较 HTML 文件"
          format: "HTML"
          link: "/comparison/java/html/"
          description: "超文本标记语言"

        # format loop 16
        - name: "比较 MSG 个文件"
          format: "MSG"
          link: "/comparison/java/msg/"
          description: "微软 Outlook 电子邮件"

        # format loop 17
        - name: "比较 ONE 个文件"
          format: "ONE"
          link: "/comparison/java/one/"
          description: "微软 OneNote"

        # format loop 18
        - name: "比较 VSDX 个文件"
          format: "VSDX"
          link: "/comparison/java/vsdx/"
          description: "微软 Visio 绘图"

        # format loop 19
        - name: "比较 CS 文件"
          format: "CS"
          link: "/comparison/java/cs/"
          description: "cSharp 语言"

        # format loop 20
        - name: "比较 Java 个文件"
          format: "Java"
          link: "/comparison/java/java/"
          description: "Java 语言"
          
        # format loop 21
        - name: "比较 CPP 文件"
          format: "CPP"
          link: "/comparison/java/cpp/"
          description: "C++ 语言"
---