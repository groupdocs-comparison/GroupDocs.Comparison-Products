
---
############################# Static ############################
layout: "format"
date:  2024-03-21T15:26:23
draft: false
lang: pt
format: Docx
product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "Compare MS Word DOCX via C# e .NET"
head_description: "comparação de DOCX por GroupDocs.Comparison for .NET. Relatório detalhado com alterações destacadas entre DOCX documentos. Use nossa API junto com C#."

############################# Header ############################
title: "MS Word DOCX comparação com C# .NET aplicativos" 
description: "A API .NET projetada para comparação de documentos encontra e relata quaisquer diferenças em MS Word arquivos. Crie aplicativos baseados em C#, ASP .NET, VB .NET ou .NET Core para obter vantagens. Obtenha relatórios detalhados adicionando algumas linhas de código."
subtitle: "Solução de comparação de documentos" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Download gratuito de Nuget"
      link: "https://releases.groupdocs.com/comparison/net/"
      
############################# About ############################
about:
    enable: true
    title: "Examine os recursos da API GroupDocs.Comparison for .NET"
    link: "/comparison/net/"
    link_title: "Saiba mais"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       Revele alterações em seus DOCX documentos com um relatório conveniente em seus .NET projetos. Além disso, obtenha informações sobre estilos, formas e outros conteúdos e mescle DOCX arquivos em um novo. As vantagens das GroupDocs.Comparison for .NET APIs podem ser trazidas para seus projetos com apenas algumas linhas de código. Use nosso software sem desenvolvedores terceirizados.

############################# Steps ############################
steps:
    enable: true
    title: "MS Word DOCX relatórios de comparação via .NET e C#"
    content: |
      Crie um relatório de distinções para DOCX arquivos usando [GroupDocs.Comparison](https://products.groupdocs.com/comparison/net/)
      
      1. Baixe o pacote GroupDocs.Comparison for .NET de [Nuget](https://www.nuget.org/packages/GroupDocs.Comparison) e instale-o
      2. Instancie o objeto Comparer passando o caminho para DOCX
      3. Adicionar DOCX arquivos à comparação
      4. Obtenha um relatório com informações sobre distinções
   
    code:
      platform: "net"
      copy_title: "Copiar"
      install:
        command: "dotnet add package GroupDocs.Comparison"
        copy_tip: "clique para copiar"
        copy_done: "copiado"
      links:
        #  loop
        - title: "Mais exemplos"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET"
        #  loop
        - title: "Documentação"
          link: "https://docs.groupdocs.com/comparison/net/"
          
      content: |
        ```csharp {style=abap}

        // Relatório de alterações de arquivos DOCX

        // Instanciate Comparer para processamento de documentos
        using (Comparer comparer = new Comparer("source.docx"))
        {
            // Adicione pelo menos um arquivo para comparação
        	comparer.Add("file_to_compare_1.docx");
            comparer.Add("file_to_compare_2.docx");
            comparer.Add("file_to_compare_3.docx");

            // Analise o resultado
            comparer.Compare("result.docx"); 
        }
        
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "Pronto para começar?"
  description: "Experimente os GroupDocs.Comparison recursos gratuitamente ou solicite uma licença"
  items:
    #  loop
    - title: "Nuget baixar"
      link: "https://releases.groupdocs.com/comparison/net/"
      color: "red"
        #  loop
    - title: "Licenciamento"
      link: "https://purchase.groupdocs.com/pricing/comparison/net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Comparação de DOCX por C# aplicativos"
    exclude: "DOCX"
    description: "GroupDocs.Comparison for .NET vantagens para controlar versões de formatos de arquivos populares. Colete MS Word informações de documentos de forma rápida e fácil."
    items: 
        # format loop 1
        - name: "Comparar arquivos PDF"
          format: "PDF"
          link: "/comparison/net/pdf/"
          description: "Formato de documento Adobe Portable"

        # format loop 2
        - name: "Comparar arquivos DOCX"
          format: "DOCX"
          link: "/comparison/net/docx/"
          description: "Documento XML aberto da Microsoft Word"

        # format loop 3
        - name: "Comparar arquivos RTF"
          format: "RTF"
          link: "/comparison/net/rtf/"
          description: "Formato de arquivo Rich Text"

        # format loop 4
        - name: "Comparar arquivos TXT"
          format: "TXT"
          link: "/comparison/net/txt/"
          description: "Formato de arquivo de texto sem formatação"

        # format loop 5
        - name: "Comparar arquivos XLSX"
          format: "XLSX"
          link: "/comparison/net/xlsx/"
          description: "Planilha Microsoft Excel Open XML"

        # format loop 6
        - name: "Compare arquivos CSV"
          format: "CSV"
          link: "/comparison/net/csv/"
          description: "Arquivo de valores separados por vírgula"

        # format loop 7
        - name: "Comparar arquivos PPTX"
          format: "PPTX"
          link: "/comparison/net/pptx/"
          description: "PowerPoint Apresentação XML aberta"

        # format loop 8
        - name: "Comparar arquivos ODS"
          format: "ODS"
          link: "/comparison/net/ods/"
          description: "Open Document Planilha"

        # format loop 9
        - name: "Compare arquivos ODP"
          format: "ODP"
          link: "/comparison/net/odp/"
          description: "OpenDocument Formato de arquivo de apresentação"

        # format loop 10
        - name: "Comparar arquivos ODT"
          format: "ODT"
          link: "/comparison/net/odt/"
          description: "Open Document Texto"

        # format loop 11
        - name: "Comparar arquivos JPEG"
          format: "JPEG"
          link: "/comparison/net/jpeg/"
          description: "JPEG Imagem"

        # format loop 12
        - name: "Comparar arquivos PNG"
          format: "PNG"
          link: "/comparison/net/png/"
          description: "Portable Gráfico de rede"

        # format loop 13
        - name: "Comparar arquivos GIF"
          format: "GIF"
          link: "/comparison/net/gif/"
          description: "Arquivo de formato de intercâmbio gráfico"

        # format loop 14
        - name: "Comparar arquivos BMP"
          format: "BMP"
          link: "/comparison/net/bmp/"
          description: "Formato de arquivo de bitmap"

        # format loop 15
        - name: "Compare arquivos HTML"
          format: "HTML"
          link: "/comparison/net/html/"
          description: "Linguagem de marcação de hipertexto"

        # format loop 16
        - name: "Comparar arquivos MSG"
          format: "MSG"
          link: "/comparison/net/msg/"
          description: "Mensagem de e-mail Microsoft Outlook"

        # format loop 17
        - name: "Comparar arquivos ONE"
          format: "ONE"
          link: "/comparison/net/one/"
          description: "Microsoft OneNote"

        # format loop 18
        - name: "Comparar arquivos VSDX"
          format: "VSDX"
          link: "/comparison/net/vsdx/"
          description: "Desenho da Microsoft Visio"

        # format loop 19
        - name: "Compare arquivos CS"
          format: "CS"
          link: "/comparison/net/cs/"
          description: "Linguagem CSharp"

        # format loop 20
        - name: "Comparar arquivos Java"
          format: "Java"
          link: "/comparison/net/java/"
          description: "Java Idioma"
          
        # format loop 21
        - name: "Compare arquivos CPP"
          format: "CPP"
          link: "/comparison/net/cpp/"
          description: "Linguagem C++"
---