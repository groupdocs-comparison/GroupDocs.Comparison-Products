
---
############################# Static ############################
layout: "family"
date:  2024-12-19T07:50:00
draft: false

product: "Comparison"
product_tag: "comparison"

lang: zh

############################# Head ############################
head_title: "C# Java Node.js Python 文档比较库 |差异检查器"
head_description: "GroupDocs 原生于 C# .NET Java 和 Node.js 的文档比较库。检查支持格式的文件之间是否存在差异。"

############################# Header ############################
title: "比较常用文件类型的差异"
description: |
  强大的 API，用于比较各种文件格式的文档。

  以最少的编码工作量识别和突出内容差异。

  突出显示明显差异并发现隐藏属性的变化。

############################# Supported Platforms ###############################
supported_platforms:
  enable: true
  head_title: "选择您的平台"
  title: "平台独立性"
  description: "GroupDocs.Comparison 库支持以下操作系统和框架："
  details_link_title: "了解更多"

  items:
    # items loop
    - title: ".NET"
      description: GroupDocs.Comparison 为了 .NET 
      color: "blue"
      tag: "net"
      link: "/comparison/net/"
      features_link: "https://docs.groupdocs.com/comparison/net/system-requirements/"
      features:
          # features loop
          - rows: "4"
            content: |
                    .NET Framework 4.6.2 or higher <br> .NET Core 2.0 or higher <br> .NET 6.0 or higher
      
          # features loop
          - rows: "1"
            content: |
                    Windows <br> Linux <br> Mac OS
      
          # features loop
          - rows: "3"
            content: |
                    Microsoft Visual Studio <br> JetBrains Rider
      
          # features loop
          - rows: "1"
            content: |
                    50+ file formats
      

    # items loop
    - title: "Java"
      description: GroupDocs.Comparison 为了 Java
      color: "red"
      tag: "java"
      link: "/comparison/java/"
      features_link: "https://docs.groupdocs.com/comparison/java/system-requirements/"
      features:
          # features loop
          - rows: "4"
            content: |
                    Java 8 or higher <br> Kotlin
      
          # features loop
          - rows: "1"
            content: |
                    Windows <br> Linux <br> Mac OS
      
          # features loop
          - rows: "3"
            content: |
                    IntelliJ IDEA <br> Eclipse <br> NetBeans
      
          # features loop
          - rows: "1"
            content: |
                    50+ file formats

    # items loop
    - title: "Node.js"
      description: GroupDocs.Comparison 为了 Node.js
      color: "green"
      tag: "nodejs-java"
      link: "/comparison/nodejs-java/"
      features_link: "https://docs.groupdocs.com/comparison/nodejs-java/system-requirements/"
      features:
          # features loop
          - rows: "4"
            content: |
                    Node.js 16+ and J2SE 8.0 (1.8)+
      
          # features loop
          - rows: "1"
            content: |
                    Windows <br> Linux <br> Mac OS
      
          # features loop
          - rows: "3"
            content: |
                    Atom <br> Visual Studio Code <br> 任何其他文本编辑器
      
          # features loop
          - rows: "1"
            content: |
                    50+ file formats

    # items loop
    - title: "Python"
      description: GroupDocs.Comparison Python
      color: "yellow"
      tag: "python-net"
      link: "/comparison/python-net/"
      features_link: "https://docs.groupdocs.com/comparison/net/system-requirements/"
      features:
          # features loop
          - rows: "4"
            content: |
                    Python 3.9+ and .Net 6+
      
          # features loop
          - rows: "1"
            content: |
                    Windows <br> Linux <br> Mac OS
      
          # features loop
          - rows: "3"
            content: |
                    IDLE <br> PyCharm <br> Visual Studio Code
      
          # features loop
          - rows: "1"
            content: |
                    50+ file formats

############################# Features ###############################
features:
  enable: true
  title: "GroupDocs.Comparison 的主要特征"
  description: "用于对 PDF、Word、Excel、源代码文件等进行比较和差异查看的 API。"

  items:
    # items loop
    - icon: "analize"
      title: "直观的差异视图结果"
      content: "在单文档报告中突出显示差异，轻松分析变化。"

    # items loop
    - icon: "merge"
      title: "高效的变更审查流程"
      content: "接受或拒绝具有视觉差异修改的更改，以便于决策。"

    # items loop
    - icon: "styles"
      title: "比较内容和样式"
      content: "比较文本内容以及格式和样式的变化。"

    # items loop
    - icon: "pages"
      title: "比较特定页面"
      content: "仅加载要比较的文档的特定部分或页面。"

############################# Code samples ############################
code_samples:
  enable: true
  title: "实用代码展示"
  description: "典型 GroupDocs.Comparison 操作的一些用例。"
  items:
    # code sample loop
    - title: "比较两个文件"
      content: |
       要比较两个文档，首先加载源文件和目标文件，然后应用 “比较” 方法。您可以灵活地选择特定的比较设置，以进行更加量身定制的分析。
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // 指定源文档
            using (Comparer comparer = new Comparer("source.docx"))
            {
                // 添加一个或多个目标文档
                comparer.Add(target.docx");

                // 指定比较选项
                CompareOptions options = new CompareOptions() {ShowRevisions = false};
                // 比较并保存结果
                comparer.Compare("result.docx", options);
            }
            ```
        - language: "Java"
          color: "red"
          content: |
            ```java {style=abap}   
            // 指定源文档
            try (Comparer comparer = new Comparer("source.docx"))
            {
                // 添加一个或多个目标文档
                comparer.add("target.docx");

                // 指定比较选项
                CompareOptions options = new CompareOptions();
                options.setShowRevisions(false);

                // 比较并保存结果
                final comparer.compare("result.docx", options);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // 指定源文档
            const comparer = new groupdocs.comparison.Comparer("source.docx");

            // 添加一个或多个目标文档
            comparer.add("target.docx");

            // 指定比较选项
            const options = new groupdocs.comparison.CompareOptions();
            options.setShowRevisions(false);

            // 比较并保存结果
            comparer.compare("result.docx", options);
            ```
        - language: "Python"
          color: "yellow"
          content: |
            ```python {style=abap}  
            def run():

                # 指定源文档
                with groupdocs.comparison.Comparer("source.docx") as comparer:

                    # 添加一个或多个目标文档
                    comparer.add("target.docx")

                    # 指定比较选项
                    options = new groupdocs.comparison.CompareOptions()
                    options.setShowRevisions(false)

                    # 比较并保存结果
                    comparer.compare("result.docx", options)
            ```


############################# Supported Formats ###############################
formats:
  enable: true
  title: "支持 50 多种文件格式"
  description: "GroupDocs.Comparison 支持在各种格式系列中进行比较操作。"

############################# Metrics ###############################
metrics:
  enable: true
  title: "详细的指标和统计见解"
  description: "深入分析我们的关键数据，为我们的成就、影响力和扩张提供全面的指标和统计见解。"

  items:
    # items loop
    - number: "50+"
      title: "支持的格式"
      content: "该 API 可容纳 50 多种最广泛使用的文件和文档格式。"

    # items loop
    - number: "800k"
      title: "NuGet 次下载"
      content: ".NET 的 GroupDocs.Comparison 已通过 NuGet 软件包管理器获得了超过80万次的下载量。"

    # items loop
    - number: "15k"
      title: "Maven 下载"
      content: "Java 的 GroupDocs.Comparison 已从我们的 Maven 存储库中累积了超过 1.5 万次的下载量。"

    # items loop
    - number: "140+"
      title: "快乐的顾客"
      content: "我们的库被全球个人开发人员和顶级公司所采用"


############################# Customers ###############################
customers:
  enable: true
  title: "我们满意的客户"
  description: "GroupDocs 个图书馆由全球知名和杰出品牌使用。"

  items:
    # items loop
    - title: "BenQ Corporation"
      logo: "benq"
      
    # items loop
    - title: "Nasdaq Stock Market"
      logo: "nasdaq"
      
    # items loop
    - title: "AT&T Inc."
      logo: "att"
      
    # items loop
    - title: "Customer logo AstraZeneca"
      logo: "astrazeneca"
      
    # items loop
    - title: "Central Bank of Argentina"
      logo: "argentinacentralbank"
      
    # items loop
    - title: "Roche Holding AG"
      logo: "roche"
      
    # items loop
    - title: "Capita"
      logo: "capita"
      
    # items loop
    - title: "Axa S.A."
      logo: "axa"
      
    # items loop
    - title: "Instructure Inc."
      logo: "instructure"
      
    # items loop
    - title: "Wipro"
      logo: "wipro"


############################# Actions ###############################
actions:
  enable: true
  title: "准备好开始了吗？"
  description: "在您的平台上免费试用 GroupDocs.Comparison 项功能"

  items:
    # items loop
    - title: ".NET"
      color: "blue"
      link: "/comparison/net/"

    # items loop
    - title: "Java"
      color: "red"
      link: "/comparison/java/"

    # items loop
    - title: "Node.js"
      color: "green"
      link: "/comparison/nodejs-java/"      

############################# FAQ ###############################
faq:
  enable: true
  title: "经常问的问题"
  description: "最常见问题的答案。"

  items:
    # items loop
    - question: "GroupDocs.Comparison 库是否需要任何其他第三方软件来操作文档？"
      answer: "GroupDocs.Comparison 不需要安装任何外部软件，例如 Adobe Acrobat、Microsoft Office 或任何其他软件。"

    # items loop
    - question: "我可以在购买之前试用 GroupDocs.Comparison 库吗？"
      answer: "是的，您无需购买许可证即可试用 GroupDocs.Comparison。在没有许可证的情况下安装后，该库将以试用模式运行。在此模式下，试用徽章将添加到生成的文档中，并将其修剪到前 3 页。如果您希望在不受试用版限制的情况下测试 GroupDocs.Comparison，也可以申请 30 天的临时许可证。有关更多详细信息，请参阅 [临时许可证](https://purchase.groupdocs.com/temporary-license/)。"

    # items loop
    - question: "你有哪些许可证？"
      answer: "我们提供多种许可证类型，以满足特定开发人员或公司的需求。许可证类型取决于开发人员的数量、开发者站点的数量以及您是否需要向最终客户提供我们的 SDK/API。或者，您可以根据产品的每月使用量选择计量许可证。要了解更多信息，请访问 [定价](https://purchase.groupdocs.com/pricing/comparison/net/)。"

############################# Cloud Links ###############################
cloud_links:
  enable: true
  title: "GroupDocs.Comparison 低代码 API"
  description: "使用我们基于云的 REST API 将文档比较功能整合到任何应用程序中。"
  
  items:
    # items loop
    - title: "GroupDocs.Comparison Cloud for cURL"
      content: "使用 cURL REST 完整文档比较 API 来比较 Word、Excel、PowerPoint 和其他流行的文件格式。"
      icon: "groupdocs_comparison-for-curl"
      link: "https://products.groupdocs.cloud/comparison/curl"

    # items loop
    - title: "GroupDocs.Comparison Cloud for .NET"
      content: "使用适用于 .NET 的 Cloud SDK 在 .NET 应用程序中添加强大的文档比较功能。比较 DOCX、XLSX、PPTX 等。"
      icon: "groupdocs_comparison-for-net"
      link: "https://products.groupdocs.cloud/comparison/net"

    # items loop
    - title: "GroupDocs.Comparison Cloud for Java"
      content: "使用专为 Java 设计的文档比较 SDK 向您的 Java 应用程序添加高保真文档比较功能。"
      icon: "groupdocs_comparison-for-java"
      link: "https://products.groupdocs.cloud/comparison/java"

############################# App links ###############################
app_links:
  enable: true
  title: "GroupDocs.Comparison NoCode 应用程序"
  description: "基于 Web 的应用程序，使您能够直接在浏览器中比较 50 多种常用文件格式。"

  items:
    # items loop
    - title: "GroupDocs.Comparison Total"
      content: "在线差异工具，用于比较来自任何设备的两个文档。"
      icon: "groupdocs_comparison-app"
      link: "https://products.groupdocs.app/comparison/total"

    # items loop
    - title: "GroupDocs.Comparison DOCX"
      content: "在线比较 DOCX 个文件。"
      icon: "groupdocs_words-app"
      link: "https://products.groupdocs.app/comparison/docx"

    # items loop
    - title: "GroupDocs.Comparison PDF"
      content: "使用 PDF 比较应用程序在线比较 PDF 个文档。"
      icon: "groupdocs_pdf-app"
      link: "https://products.groupdocs.app/comparison/pdf"


      


---