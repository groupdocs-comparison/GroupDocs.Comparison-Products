
---
############################# Static ############################
layout: "format"
date:  2024-10-01T13:42:45
draft: false
lang: zh
format: Docx
product: "Comparison"
product_tag: "comparison"
platform: "Python via .NET"
platform_tag: "python-net"

############################# Head ############################
head_title: "使用 Python API 比较 DOCX 文档"
head_description: "使用 Python 的 GroupDocs.Comparison API 轻松跟踪 MS Word DOCX 文件中的差异。生成详细报告以突出显示文档之间的更改。"

############################# Header ############################
title: "比较 Python via .NET 中的 DOCX 文件" 
description: "在 Python 中使用我们的文档处理 API 来快速识别和显示 MS Word DOCX 文件中的任何更改。从您的 Python via .NET 应用程序中快速、轻松地生成报告中受益。"
subtitle: "文件对比解决方案" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "从 PyPi 免费下载"
      link: "https://releases.groupdocs.com/comparison/python-net/"
      
############################# About ############################
about:
    enable: true
    title: "探索 GroupDocs.Comparison for Python via .NET 的功能"
    link: "/comparison/python-net/"
    link_title: "了解更多"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison 提供全面的报告，突出显示不同版本的 DOCX 文档中的更改。只需几行代码，即可将 Python via .NET 和我们的 API 集成到您的工作流程中，而无需任何其他库。检测 MS Word 文档中页面、文本、文本样式或形状的更改。您甚至可以合并更改以创建最终的 DOCX 文档。通过我们强大的 API 增强您的文档处理能力。

############################# Steps ############################
steps:
    enable: true
    title: "在 Python 中生成 DOCX 比较报告"
    content: |
      使用 [GroupDocs.Comparison](https://products.groupdocs.com/comparison/python-net/) 和 Python via .NET 来比较 DOCX 文件。
      
      1. 通过 [PyPi](https://pypi.org/project/groupdocs-comparison-net/) 安装 Python via .NET 的 GroupDocs.Comparison。
      2. 创建一个 Comparer 实例并指定第一个 DOCX 文件的路径。
      3. 添加其他 DOCX 文件以进行比较。
      4. 查看生成的报告并访问结果。
   
    code:
      platform: "python-net"
      copy_title: "复制"
      install:
        command: "pip install groupdocs-comparison-net"
        copy_tip: "点击复制"
        copy_done: "复制的"
      links:
        #  loop
        - title: "更多例子"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET/"
        #  loop
        - title: "文档"
          link: "https://docs.groupdocs.com/comparison/python-net/"
          
      content: |
        ```python {style=abap}
        def run():

            # 比较多个文件以查看相似点和差异。

            # 初始化比较器并加载第一个文件。
            with groupdocs.comparison.Comparer("first.docx") as comparer:

                # 添加其他文件进行比较。
                comparer.add('second.docx')
                comparer.add('third.docx')

                # 检索最终的比较报告。
                comparer.compare('report_full.docx')

                print("\nDocuments compared successfully.\nCheck output.")
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "准备好开始了吗？"
  description: "免费试用 GroupDocs.Comparison 项功能或申请许可证"
  items:
    #  loop
    - title: "PyPi 下载"
      link: "https://releases.groupdocs.com/comparison/python-net/"
      color: "red"
        #  loop
    - title: "许可"
      link: "https://purchase.groupdocs.com/pricing/comparison/python-net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "使用 Python 比较 DOCX 文档"
    exclude: "DOCX"
    description: "轻松将任何 MS Word DOCX 文件与 GroupDocs.Comparison for Python via .NET 进行比较，并获得有关文档更改的宝贵见解。"
    items: 
        # format loop 1
        - name: "比较 PDF 个文件"
          format: "PDF"
          link: "/comparison/python-net/pdf/"
          description: "Adobe Portable 文档格式"

        # format loop 2
        - name: "比较 DOCX 个文件"
          format: "DOCX"
          link: "/comparison/python-net/docx/"
          description: "微软 Word 打开 XML 文档"

        # format loop 3
        - name: "比较 RTF 个文件"
          format: "RTF"
          link: "/comparison/python-net/rtf/"
          description: "富文本文件格式"

        # format loop 4
        - name: "比较 TXT 个文件"
          format: "TXT"
          link: "/comparison/python-net/txt/"
          description: "纯文本文件格式"

        # format loop 5
        - name: "比较 XLSX 个文件"
          format: "XLSX"
          link: "/comparison/python-net/xlsx/"
          description: "微软 Excel 打开 XML 电子表格"

        # format loop 6
        - name: "比较 CSV 文件"
          format: "CSV"
          link: "/comparison/python-net/csv/"
          description: "逗号分隔值文件"

        # format loop 7
        - name: "比较 PPTX 个文件"
          format: "PPTX"
          link: "/comparison/python-net/pptx/"
          description: "PowerPoint 打开 XML 演示文稿"

        # format loop 8
        - name: "比较 ODS 个文件"
          format: "ODS"
          link: "/comparison/python-net/ods/"
          description: "Open Document 电子表格"

        # format loop 9
        - name: "比较 ODP 文件"
          format: "ODP"
          link: "/comparison/python-net/odp/"
          description: "OpenDocument 演示文件格式"

        # format loop 10
        - name: "比较 ODT 个文件"
          format: "ODT"
          link: "/comparison/python-net/odt/"
          description: "Open Document 文本"

        # format loop 11
        - name: "比较 JPEG 个文件"
          format: "JPEG"
          link: "/comparison/python-net/jpeg/"
          description: "JPEG 图片"

        # format loop 12
        - name: "比较 PNG 个文件"
          format: "PNG"
          link: "/comparison/python-net/png/"
          description: "Portable 网络图形"

        # format loop 13
        - name: "比较 GIF 个文件"
          format: "GIF"
          link: "/comparison/python-net/gif/"
          description: "图形交换格式文件"

        # format loop 14
        - name: "比较 BMP 个文件"
          format: "BMP"
          link: "/comparison/python-net/bmp/"
          description: "位图文件格式"

        # format loop 15
        - name: "比较 HTML 文件"
          format: "HTML"
          link: "/comparison/python-net/html/"
          description: "超文本标记语言"

        # format loop 16
        - name: "比较 MSG 个文件"
          format: "MSG"
          link: "/comparison/python-net/msg/"
          description: "微软 Outlook 电子邮件"

        # format loop 17
        - name: "比较 ONE 个文件"
          format: "ONE"
          link: "/comparison/python-net/one/"
          description: "微软 OneNote"

        # format loop 18
        - name: "比较 VSDX 个文件"
          format: "VSDX"
          link: "/comparison/python-net/vsdx/"
          description: "微软 Visio 绘图"

        # format loop 19
        - name: "比较 CS 文件"
          format: "CS"
          link: "/comparison/python-net/cs/"
          description: "cSharp 语言"

        # format loop 20
        - name: "比较 Java 个文件"
          format: "Java"
          link: "/comparison/python-net/java/"
          description: "Java 语言"
          
        # format loop 21
        - name: "比较 CPP 文件"
          format: "CPP"
          link: "/comparison/python-net/cpp/"
          description: "C++ 语言"
---