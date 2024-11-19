
---
############################# Static ############################
layout: "format"
date:  2024-11-19T07:50:38
draft: false
lang: zh
format: Docx
product: "Comparison"
product_tag: "comparison"
platform: "Python via .NET"
platform_tag: "python-net"

############################# Head ############################
head_title: "使用 Python API 轻松比较 DOCX 文件"
head_description: "使用 Python 的 GroupDocs.Comparison API 跟踪和分析 MS Word DOCX 文档中的差异，生成概述更改的综合报告。"

############################# Header ############################
title: "Python via .NET 的 DOCX 比较" 
description: "利用 Python 中的文档处理 API 快速识别和总结 MS Word DOCX 文件中的更改。在您的应用程序中享受无缝的报告生成。"
subtitle: "高级文件比较工具" 

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
       GroupDocs.Comparison 提供对 DOCX 文档不同版本之间的变化的广泛见解。只需几行代码，您就可以将 Python via .NET 和我们的 API 集成到您的工作流程中，无需额外的库。确定 Word 文档中内容、文本样式和布局的更改。您甚至可以合并变体以创建更新的 DOCX 文件。使用我们强大的 API 提升您的文档管理流程。

############################# Steps ############################
steps:
    enable: true
    title: "使用 Python 创建 DOCX 比较报告"
    content: |
      利用 [GroupDocs.Comparison](https://products.groupdocs.com/comparison/python-net/) 和 Python via .NET 来评估 DOCX 文件差异。
      
      1. 通过 [PyPi](https://pypi.org/project/groupdocs-comparison-net/) 获取 Python via .NET 的 GroupDocs.Comparison。
      2. 设置 Comparer 实例并将路径指向初始 DOCX 文件。
      3. 根据需要添加更多 DOCX 文件以进行比较分析。
      4. 评估生成的报告并检查您的发现。
   
    code:
      platform: "python-net"
      copy_title: "复制"
      result_enable: true
      result_link: "/examples/comparison/comparison_result.docx"
      result_title: "示例结果文件"
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
    title: "将任何 DOCX 文档与 Python 进行比较"
    exclude: "DOCX"
    description: "利用 GroupDocs.Comparison for Python via .NET 分析任何 MS Word DOCX 文件，获得有关文档修订的宝贵知识。"
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