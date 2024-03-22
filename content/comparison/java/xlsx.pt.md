
---
############################# Static ############################
layout: "format"
date:  2024-03-22T13:27:40
draft: false
lang: pt
format: Xlsx
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "GroupDocs.Comparison for Java para a comparação XLSX."
head_description: "A API GroupDocs.Comparison oferece a recuperação de relatórios detalhando as variações em XLSX documentos. Compatível com ambientes Java, J2EE e J2SE."

############################# Header ############################
title: "Java aplicativos para detectar alterações em XLSX planilhas" 
description: "A API GroupDocs.Comparison Java permite a comparação de XLSX planilhas em aplicativos Java, J2EE ou J2SE."
subtitle: "Estrutura de verificação de diferenças de documentos"  

header_actions:
  enable: true
  items:
    #  loop
    - title: "Download gratuito de Maven"
      link: "https://releases.groupdocs.com/comparison/java/"
      
############################# About ############################
about:
    enable: true
    title: "Explore as vantagens da API GroupDocs.Comparison for Java"
    link: "/comparison/java/"
    link_title: "Saiba mais"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       A API GroupDocs.Comparison for Java facilita a comparação de XLSX planilhas, gerando relatórios sobre as diferenças encontradas em textos, parágrafos, formas, estilos e outros elementos. Além disso, ele suporta a mesclagem de alterações de vários arquivos originais sem a necessidade de bibliotecas externas. Melhore seus Java projetos com o mínimo de integração de código.

############################# Steps ############################
steps:
    enable: true
    title: "Use Java para comparar vários XLSX arquivos"
    content: |
      Use [GroupDocs.Comparison](https://products.groupdocs.com/comparison/java/) para analisar MS Excel planilhas
      
      1. Instale o pacote de [Maven](https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/)
      2. Instancie o Comparador com a primeira planilha XLSX como parâmetro
      3. Inclua XLSX planilhas adicionais para comparação
      4. Desfrute de um relatório abrangente
   
    code:
      platform: "net"
      copy_title: "Copiar"
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
        copy_tip: "clique para copiar"
        copy_done: "copiado"
      links:
        #  loop
        - title: "Mais exemplos"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
        #  loop
        - title: "Documentação"
          link: "https://docs.groupdocs.com/comparison/java/"
          
      content: |
        ```java {style=abap}

        // Verifique se há diferenças ou semelhanças nos arquivos do seu disco rígido

        // Crie um objeto Comparer especificando o arquivo inicial
        try (Comparer comparer = new Comparer("main.xlsx") 
        {
            // Inclua arquivos adicionais para comparação
        	comparer.add("version1.xlsx");
            comparer.add("version2.xlsx");
            comparer.add("version3.xlsx");

            // Obtenha o relatório com o nome especificado como resultado
            final Path resultPath = comparer.compare("full_report.xlsx"); 

            System.out.println("\nDocuments compared successfully.");
        }
        
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "Pronto para começar?"
  description: "Experimente os GroupDocs.Comparison recursos gratuitamente ou solicite uma licença"
  items:
    #  loop
    - title: "Maven baixar"
      link: "https://releases.groupdocs.com/comparison/java/"
      color: "red"
        #  loop
    - title: "Licenciamento"
      link: "https://purchase.groupdocs.com/pricing/comparison/java/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Gerencie alterações em XLSX planilhas usando Java"
    exclude: "XLSX"
    description: "A biblioteca GroupDocs.Comparison Java permite que os usuários monitorem diferentes versões de XLSX planilhas por meio de relatórios detalhados e precisos que são facilmente compostos."
    items: 
        # format loop 1
        - name: "Comparar arquivos PDF"
          format: "PDF"
          link: "/comparison/java/pdf/"
          description: "Formato de documento Adobe Portable"

        # format loop 2
        - name: "Comparar arquivos DOCX"
          format: "DOCX"
          link: "/comparison/java/docx/"
          description: "Documento XML aberto da Microsoft Word"

        # format loop 3
        - name: "Comparar arquivos RTF"
          format: "RTF"
          link: "/comparison/java/rtf/"
          description: "Formato de arquivo Rich Text"

        # format loop 4
        - name: "Comparar arquivos TXT"
          format: "TXT"
          link: "/comparison/java/txt/"
          description: "Formato de arquivo de texto sem formatação"

        # format loop 5
        - name: "Comparar arquivos XLSX"
          format: "XLSX"
          link: "/comparison/java/xlsx/"
          description: "Planilha Microsoft Excel Open XML"

        # format loop 6
        - name: "Compare arquivos CSV"
          format: "CSV"
          link: "/comparison/java/csv/"
          description: "Arquivo de valores separados por vírgula"

        # format loop 7
        - name: "Comparar arquivos PPTX"
          format: "PPTX"
          link: "/comparison/java/pptx/"
          description: "PowerPoint Apresentação XML aberta"

        # format loop 8
        - name: "Comparar arquivos ODS"
          format: "ODS"
          link: "/comparison/java/ods/"
          description: "Open Document Planilha"

        # format loop 9
        - name: "Compare arquivos ODP"
          format: "ODP"
          link: "/comparison/java/odp/"
          description: "OpenDocument Formato de arquivo de apresentação"

        # format loop 10
        - name: "Comparar arquivos ODT"
          format: "ODT"
          link: "/comparison/java/odt/"
          description: "Open Document Texto"

        # format loop 11
        - name: "Comparar arquivos JPEG"
          format: "JPEG"
          link: "/comparison/java/jpeg/"
          description: "JPEG Imagem"

        # format loop 12
        - name: "Comparar arquivos PNG"
          format: "PNG"
          link: "/comparison/java/png/"
          description: "Portable Gráfico de rede"

        # format loop 13
        - name: "Comparar arquivos GIF"
          format: "GIF"
          link: "/comparison/java/gif/"
          description: "Arquivo de formato de intercâmbio gráfico"

        # format loop 14
        - name: "Comparar arquivos BMP"
          format: "BMP"
          link: "/comparison/java/bmp/"
          description: "Formato de arquivo de bitmap"

        # format loop 15
        - name: "Compare arquivos HTML"
          format: "HTML"
          link: "/comparison/java/html/"
          description: "Linguagem de marcação de hipertexto"

        # format loop 16
        - name: "Comparar arquivos MSG"
          format: "MSG"
          link: "/comparison/java/msg/"
          description: "Mensagem de e-mail Microsoft Outlook"

        # format loop 17
        - name: "Comparar arquivos ONE"
          format: "ONE"
          link: "/comparison/java/one/"
          description: "Microsoft OneNote"

        # format loop 18
        - name: "Comparar arquivos VSDX"
          format: "VSDX"
          link: "/comparison/java/vsdx/"
          description: "Desenho da Microsoft Visio"

        # format loop 19
        - name: "Compare arquivos CS"
          format: "CS"
          link: "/comparison/java/cs/"
          description: "Linguagem CSharp"

        # format loop 20
        - name: "Comparar arquivos Java"
          format: "Java"
          link: "/comparison/java/java/"
          description: "Java Idioma"
          
        # format loop 21
        - name: "Compare arquivos CPP"
          format: "CPP"
          link: "/comparison/java/cpp/"
          description: "Linguagem C++"
---