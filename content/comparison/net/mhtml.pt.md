---
############################# Static ############################
layout: "auto-gen-comparison"
date: 2021-05-13T12:45:19+03:00
draft: false

############################# Head ############################
head_title: "Compare dois arquivos MHTML em .NET | APIs de comparação de documentos"
head_description: "Compare e mescle mais de dois arquivos MHTML em aplicativos C# .NET. Recupere resumos de diferenças em conteúdo, texto e estilo de MHTML arquivos, imagens e formatos de documentos."

############################# Header ############################
title: "Compare arquivos MHTML em C# .NET"
description: "API de comparação de documentos .NET para detectar as alterações entre duas versões de arquivos MHTML e exportar para um documento final com um resumo detalhado das diferenças entre os documentos comparados."
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Baixe a avaliação gratuita"
    link: "https://downloads.groupdocs.com/comparison/net"

############################# SubMenu ############################
submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Comparison for .NET"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-comparison-net.png"
        product: "GroupDocs.Comparison"
        platform: ".NET"

    middle:
        button: 
            # button loop
            - link: "https://apireference.groupdocs.com/comparison/net"
              text: "Referência de API"

            # button loop
            - link: "https://github.com/groupdocs-comparison"
              text: "Exemplos de código"

            # button loop
            - link: "https://products.groupdocs.app/comparison/family"
              text: "Demonstrações ao vivo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "Preços"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/net"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: "Sobre a API GroupDocs.Comparison for .NET"
    content: |
        [GroupDocs.Comparison for .NET](/comparison/net/) é uma API .NET nativa para comparar várias imagens e documentos do mesmo formato. Ele ajuda a detectar diferenças em parágrafos, palavras, caracteres, formas e até mesmo nos estilos de texto dos documentos comparados, mesclar as alterações e exportar para um documento final. Ele suporta comparação e mesclagem de PDF, documentos do Word, planilhas do Excel, apresentações do PowerPoint, diagramas do Visio, e-mails do Outlook, HTML, desenhos e formatos de arquivo de imagem sem usar qualquer biblioteca externa.

############################# Steps ############################
steps:
    enable: true
    title_left: "Etapas para comparar arquivos MHTML em C#"
    content_left: |
        [GroupDocs.Comparison](/comparison/net/) torna mais fácil para os desenvolvedores .NET comparar e mesclar vários arquivos MHTML em seus aplicativos, implementando algumas etapas fáceis.
        * Instancie o objeto **Comparador** com o caminho ou fluxo do documento de origem.
        * Chame o método Add e especifique o caminho ou fluxo do documento de destino. Repita esta etapa para cada documento de destino.
        * Chame o método Comparar.
    title_right: "Requisitos de sistema"
    content_right: |
        As APIs do GroupDocs.Comparison for .NET são compatíveis com todas as principais plataformas e sistemas operacionais. Antes de executar o código abaixo, certifique-se de ter os seguintes pré-requisitos instalados em seu sistema.
        * Sistemas Operacionais: Microsoft Windows, Linux, MacOS
        * Ambientes de desenvolvimento: Microsoft Visual Studio, Xamarin, MonoDevelop
        * Estruturas: .NET Framework, .NET Standard, .NET Core, Mono
        * Obtenha a versão mais recente do GroupDocs.Comparison for .NET baixada do [NuGet](https://www.nuget.org/packages/groupdocs.comparison)
    code: |
        ```cs
        // Compare vários documentos do disco local
        
        using (Comparer comparer = new Comparer("source.mhtml"))
        {
        	comparer.Add("target1.mhtml");
            comparer.Add("target2.mhtml");
            comparer.Add("target3.mhtml");
            comparer.Compare("result.mhtml"); // Crie um arquivo de resultado com o nome especificado
        }
        
        // Compare vários documentos do fluxo
        
        using (Comparer comparer = new Comparer(File.OpenRead("source.mhtml")))
        {
        	comparer.Add(File.OpenRead("target1.mhtml"));
            comparer.Add(File.OpenRead("target2.mhtml"));
            comparer.Add(File.OpenRead("target3.mhtml"));
            comparer.Compare(File.Create("result.mhtml")); // Crie um arquivo de resultado com o nome especificado
        }
        ```

############################# Demos ############################
demos:
    enable: true
    title: "Demonstrações ao vivo de comparação de arquivos MHTML"
    content: |
        Detecte diferenças entre arquivos MHTML agora mesmo visitando o site [GroupDocs.Comparison Live Demos](https://products.groupdocs.app/comparison/family).
        A demonstração ao vivo tem os seguintes benefícios

############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-mhtml"
          title: "Sobre o formato de arquivo MHTML"
          content: |
            Arquivos com extensão MHTML representam um formato de arquivo de página da web que pode ser criado por vários aplicativos diferentes. O formato é conhecido como formato de arquivo porque salva o código HTML da web e os recursos associados em um único arquivo. Esses recursos incluem qualquer coisa vinculada à página da web, como imagens, miniaplicativos, animações, arquivos de áudio e assim por diante. Os arquivos MHTML podem ser abertos em vários aplicativos, como Internet Explorer e Microsoft Word. O Microsoft Windows usa o formato de arquivo MHTML para registrar cenários de problemas observados durante o uso de qualquer aplicativo no Windows que levante problemas. O formato de arquivo MHTML codifica o conteúdo da página semelhante às especificações definidas em message/rfc822, que são especificações relacionadas a e-mail em texto simples. As especificações reais do formato são detalhadas pela RFC 2557.
          link: "https://docs.fileformat.com/image/mhtml/"

############################# More Formats ############################
more_formats:
    enable: true
    title: "Comparando outros formatos de arquivo"
    content: |
        API de comparação de documentos e imagens em vários formatos para .NET. Analise as diferenças entre documentos do mesmo formato sem utilizar nenhuma ferramenta externa.
    format: 
        # format loop
        - name: "Compare PDF Files"
          link: "https://products.groupdocs.com/comparison/net/pdf/"
          description: "Adobe Portable Document Format"

        # format loop
        - name: "Compare DOC Files"
          link: "https://products.groupdocs.com/comparison/net/doc/"
          description: "Microsoft Word Document"

        # format loop
        - name: "Compare DOCM Files"
          link: "https://products.groupdocs.com/comparison/net/docm/"
          description: "Microsoft Word Macro-Enabled Document"

        # format loop
        - name: "Compare DOCX Files"
          link: "https://products.groupdocs.com/comparison/net/docx/"
          description: "Microsoft Word Open XML Document"

        # format loop
        - name: "Compare DOT Files"
          link: "https://products.groupdocs.com/comparison/net/dot/"
          description: "Microsoft Word Document Template"

        # format loop
        - name: "Compare DOTM Files"
          link: "https://products.groupdocs.com/comparison/net/dotm/"
          description: "Microsoft Word Macro-Enabled Template"

        # format loop
        - name: "Compare DOTX Files"
          link: "https://products.groupdocs.com/comparison/net/dotx/"
          description: "Word Open XML Document Template"

        # format loop
        - name: "Compare RTF Files"
          link: "https://products.groupdocs.com/comparison/net/rtf/"
          description: "Rich Text File Format"

        # format loop
        - name: "Compare TXT Files"
          link: "https://products.groupdocs.com/comparison/net/txt/"
          description: "Plain Text File Format"

        # format loop
        - name: "Compare XLS Files"
          link: "https://products.groupdocs.com/comparison/net/xls/"
          description: "Microsoft Excel Binary File Format"

        # format loop
        - name: "Compare XLSX Files"
          link: "https://products.groupdocs.com/comparison/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop
        - name: "Compare XLTM Files"
          link: "https://products.groupdocs.com/comparison/net/xltm/"
          description: "Microsoft Excel macro-enabled template"

        # format loop
        - name: "Compare XLSM Files"
          link: "https://products.groupdocs.com/comparison/net/xlsm/"
          description: "Microsoft Excel Macro-Enabled Spreadsheet"

        # format loop
        - name: "Compare XLSB Files"
          link: "https://products.groupdocs.com/comparison/net/xlsb/"
          description: "Microsoft Excel Binary Spreadsheet File"

        # format loop
        - name: "Compare CSV Files"
          link: "https://products.groupdocs.com/comparison/net/csv/"
          description: "Comma Separated Values File"

        # format loop
        - name: "Compare PPT Files"
          link: "https://products.groupdocs.com/comparison/net/ppt/"
          description: "PowerPoint Presentation"

        # format loop
        - name: "Compare PPS Files"
          link: "https://products.groupdocs.com/comparison/net/pps/"
          description: "Microsoft PowerPoint Slide Show"

        # format loop
        - name: "Compare PPTX Files"
          link: "https://products.groupdocs.com/comparison/net/pptx/"
          description: "PowerPoint Open XML Presentation"

        # format loop
        - name: "Compare PPSX Files"
          link: "https://products.groupdocs.com/comparison/net/ppsx/"
          description: "PowerPoint Open XML Slide Show"

        # format loop
        - name: "Compare POT Files"
          link: "https://products.groupdocs.com/comparison/net/pot/"
          description: "Microsoft PowerPoint template"

        # format loop
        - name: "Compare POTX Files"
          link: "https://products.groupdocs.com/comparison/net/potx/"
          description: "Microsoft PowerPoint Open XML Template"

        # format loop
        - name: "Compare ODS Files"
          link: "https://products.groupdocs.com/comparison/net/ods/"
          description: "Open Document Spreadsheet"

        # format loop
        - name: "Compare ODP Files"
          link: "https://products.groupdocs.com/comparison/net/odp/"
          description: "OpenDocument Presentation File Format"

        # format loop
        - name: "Compare OTP Files"
          link: "https://products.groupdocs.com/comparison/net/otp/"
          description: "Origin Graph Template"

        # format loop
        - name: "Compare ODT Files"
          link: "https://products.groupdocs.com/comparison/net/odt/"
          description: "Open Document Text"

        # format loop
        - name: "Compare OTT Files"
          link: "https://products.groupdocs.com/comparison/net/ott/"
          description: "Open Document Template"

        # format loop
        - name: "Compare VST Files"
          link: "https://products.groupdocs.com/comparison/net/vst/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare JPEG Files"
          link: "https://products.groupdocs.com/comparison/net/jpeg/"
          description: "JPEG Image"

        # format loop
        - name: "Compare PNG Files"
          link: "https://products.groupdocs.com/comparison/net/png/"
          description: "Portable Network Graphic"

        # format loop
        - name: "Compare GIF Files"
          link: "https://products.groupdocs.com/comparison/net/gif/"
          description: "Graphical Interchange Format File"

        # format loop
        - name: "Compare BMP Files"
          link: "https://products.groupdocs.com/comparison/net/bmp/"
          description: "Bitmap File Format"

        # format loop
        - name: "Compare HTML Files"
          link: "https://products.groupdocs.com/comparison/net/html/"
          description: "Hyper Text Markup Language"

        # format loop
        - name: "Compare MHT Files"
          link: "https://products.groupdocs.com/comparison/net/mht/"
          description: "Mime HTML"

        # format loop
        - name: "Compare MHTML Files"
          link: "https://products.groupdocs.com/comparison/net/mhtml/"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop
        - name: "Compare MSG Files"
          link: "https://products.groupdocs.com/comparison/net/msg/"
          description: "Microsoft Outlook E-mail Message"

        # format loop
        - name: "Compare EML Files"
          link: "https://products.groupdocs.com/comparison/net/eml/"
          description: "E-mail Message"

        # format loop
        - name: "Compare EMLX Files"
          link: "https://products.groupdocs.com/comparison/net/emlx/"
          description: "Apple Mail E-mail File"

        # format loop
        - name: "Compare ONE Files"
          link: "https://products.groupdocs.com/comparison/net/one/"
          description: "Microsoft OneNote"

        # format loop
        - name: "Compare VSD Files"
          link: "https://products.groupdocs.com/comparison/net/vsd/"
          description: "Microsoft Visio 2003-2010 Drawing"

        # format loop
        - name: "Compare VSDX Files"
          link: "https://products.groupdocs.com/comparison/net/vsdx/"
          description: "Microsoft Visio Drawing"

        # format loop
        - name: "Compare VSS Files"
          link: "https://products.groupdocs.com/comparison/net/vss/"
          description: "Microsoft Visio 2003-2010 Stencil"

        # format loop
        - name: "Compare VST Files"
          link: "https://products.groupdocs.com/comparison/net/vst/"
          description: "Microsoft Visio 2003-2010 Template"

        # format loop
        - name: "Compare VDX Files"
          link: "https://products.groupdocs.com/comparison/net/vdx/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare CS Files"
          link: "https://products.groupdocs.com/comparison/net/cs/"
          description: "CSharp Language"

        # format loop
        - name: "Compare Java Files"
          link: "https://products.groupdocs.com/comparison/net/java/"
          description: "Java Language"

        # format loop
        - name: "Compare CPP Files"
          link: "https://products.groupdocs.com/comparison/net/cpp/"
          description: "C++ Language"

        # format loop
        - name: "Compare JS Files"
          link: "https://products.groupdocs.com/comparison/net/js/"
          description: "JavaScript Language"

        # format loop
        - name: "Compare PY Files"
          link: "https://products.groupdocs.com/comparison/net/py/"
          description: "Python Language"

        # format loop
        - name: "Compare RB Files"
          link: "https://products.groupdocs.com/comparison/net/rb/"
          description: "Ruby Language"

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison oferece APIs de visualização de documentos para outros ambientes de desenvolvimento populares"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for Java MHTML"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/mhtml/"

############################# Back to top ###############################
back_to_top:
    enable: true
---
