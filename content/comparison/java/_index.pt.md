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
head_title: "API de comparação de documentos Java | Comparar texto e estilo de PDF Word Excel HTML"
head_description: "API de comparação de documentos Java para comparar e mesclar Word Excel PPTX OpenOffice, Web, PDF, AutoCAD e outros formatos de arquivo. Compare documentos com alterações de controle."

############################# Header ############################
title: "API Java para comparar arquivos"
description: "Crie aplicativos Java para comparar efetivamente o conteúdo dos arquivos quanto às diferenças em todos os formatos padrão de documento e arquivo de imagem."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Baixar Teste Gratuito"
    link: "https://downloads.groupdocs.com/comparison/java"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Comparison para Java"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
        product: "GroupDocs.Comparison"
        platform: "Java"

    middle:
        button:
            # loop de botão
            - link: "#overview"
              text: "Visão geral"

            # loop de botão
            - link: "#features"
              text: "Características"

            # loop de botão
            - link: "#support"
              text: "Suporte"

            # loop de botão
            - link: "https://products.groupdocs.app/comparison"
              text: "Demonstração ao vivo"

            # loop de botão
            - link: "https://purchase.groupdocs.com/pricing/comparison/java"
              text: "Preços"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    example_image: "/comparison/comparison-example.png"
    content: |
      
    more_overview:
      # more_overview_loop
      - title: "O que é GroupDocs.Сomparison"
        content: "GroupDocs.Comparison for Java é a API mais flexível e fácil de usar para ajudá-lo a desenvolver aplicativos de comparação de documentos no ambiente Java. O verificador de diferenças e a API de mesclagem de documentos permitem que você detecte alterações e diferenças no conteúdo, bem como em estilo de texto entre formatos de documento semelhantes."

      # more_overview_loop
      - title: "Formatos suportados"
        content: "A biblioteca GroupDocs.Comparison suporta a detecção de diferenças em conteúdo e estilo de texto entre formatos populares de imagens e documentos, como PDF, HTML, e-mail do Outlook, documentos do Microsoft Office Word, planilhas do Excel, apresentações do PowerPoint, OneNote, diagramas do Visio, textos, imagens png, gif e bmp, bem como uma centena de outros formatos."
        
      # more_overview_loop
      - title: "Capacidade de comparação"
        content: "A comparação pode ser realizada para detectar alterações no conteúdo de palavras, parágrafos, tabelas ou gráficos e seus estilos, e fornecerá um documento de comparação que lista um resumo das diferenças, seu número e tipo pertencente. GroupDocs.Comparison para Java pode facilmente extrair informações básicas sobre o documento de origem, comparar e salvar documentos simples, protegidos por senha e criptografados de vários formatos por meio de um arquivo ou fluxo de dados."
        
      # more_overview_loop
      - title: "Documentação e Exemplos"
        content: "Já existe muita documentação sobre como usar a biblioteca Comparison em diferentes plataformas com exemplos de código, então você não precisa pensar muito sobre como trabalhar com GroupDocs.Comparison for Java API em seu aplicativo."
        
      # more_overview_loop
      - title: "Compatibilidade"
        content: "GroupDocs.Comparison for Java não requer a instalação de nenhum software externo no sistema. É compatível com todas as versões do Java e suporta sistemas operacionais populares (Windows, Linux, MacOS) capazes de executar o Java Runtime Environment."
    examples:
      enable: true
      
    more_feature:
      # more_feature_loop
      - title: "Compare facilmente documentos usando a API Java"
        content: |
          Por meio do GroupDocs.Comparison para Java API, você pode facilmente comparar documentos de formatos suportados para encontrar diferenças entre eles. O exemplo a seguir mostra como comparar dois documentos do Microsoft Word usando Java:
          
          ```java
          try (Comparer comparer = new Comparer("D:\\source.pdf")) {
              comparer.add("D:\\target.pdf");
              comparer.compare("D:\\result.pdf");
          }
          ```
      # more_feature_loop
      - title: "Especificar o nível de detalhe da comparação"
        content: "GroupDocs.Comparison for Java permite comparar documentos em três níveis de profundidade. Você pode definir a intensidade da comparação como baixa (comparar texto palavra por palavra com precisão para grade de imagem = 50), média (comparar texto caractere por caractere com precisão para grade de imagem = 100) ou alto (compare caractere de texto por caractere com precisão para grade de imagem = 150)."

      # more_feature_loop
      - title: "Comparar estilo de texto"
        content: "Juntamente com o conteúdo do documento, GroupDocs.Comparison para API Java também permite comparar o estilo do texto.

        Nome da fonte, tamanho, cor, estilo (negrito, itálico, sublinhado, versalete e hiperlinks) e, se aplicável, sob a cor também podem ser comparados para verificar a diferença entre os documentos comparados, enquanto palavras e caracteres estão sendo comparados.

        Para comparação de parágrafo, alinhamento, recuo (recuo à esquerda, recuo à direita), espaçamento (espaço depois, espaço antes), recuo da primeira linha e espaçamento entre linhas também podem ser comparados.

        Da mesma forma, sempre que aplicável, outras seções de uma página também podem ser comparadas por meio do GroupDocs.Comparison for Java API. As seções incluem distância do rodapé, margens da página (esquerda, direita, superior e inferior), altura da página, orientação da página, cor da borda e largura da linha."
      
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          A seguir está uma visão geral do GroupDocs.Comparison para Java:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Visão geral"
          content: |
            * Comparar conteúdos e estilos
            * Obter resumo de comparação
            * Aceitar/Rejeitar Alterações no Word
            * Mesclar e comparar 3 arquivos do Word
            * Suporte para fluxos
            * Detecção de tipo de arquivo via Stream
            * Comparar arquivos protegidos
            * Comparar arquivos criptografados
            * Salvar comparação como imagem
            * Comparar página específica no Word
            * Comparar marca d'água em PDF
            * Aplicar/Descartar Alterações
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison for Java oferece suporte a todos os [formatos de arquivo de documento](https://docs.groupdocs.com/comparison/java/supported-document-formats/) populares, incluindo: Microsoft Office, imagens, diagramas e muitos outros .
        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** [DOC](https://products.groupdocs.com/comparison/java/doc/), [DOCX](https://products.groupdocs.com/comparison/java/docx/), [DOCM](https://products.groupdocs.com/comparison/java/docm/), [DOT](https://products.groupdocs.com/comparison/java/dot/), [DOTX](https://products.groupdocs.com/comparison/java/dotx/), [DOTM](https://products.groupdocs.com/comparison/java/dotm/), [RTF](https://products.groupdocs.com/comparison/java/rtf/), [TXT](https://products.groupdocs.com/comparison/java/txt/)
                * **Excel:** [XLS](https://products.groupdocs.com/comparison/java/xls/), [XLSX](https://products.groupdocs.com/comparison/java/xlsx/), [XLSM](https://products.groupdocs.com/comparison/java/xlsm/), [XLSB](https://products.groupdocs.com/comparison/java/xlsb/), [XLTM](https://products.groupdocs.com/comparison/java/xltm/), [XLT](https://products.groupdocs.com/comparison/java/xlt/), [XLTM](https://products.groupdocs.com/comparison/java/xltm/), [XLTX](https://products.groupdocs.com/comparison/java/xltx/), [XLAM](https://products.groupdocs.com/comparison/java/xlam/), [SXC](https://products.groupdocs.com/comparison/java/sxc/), [SpreadsheetML](https://products.groupdocs.com/comparison/java/xml/)
                * **PowerPoint:** [PPT](https://products.groupdocs.com/comparison/java/ppt/), [PPTX](https://products.groupdocs.com/comparison/java/pptx/), [PPS](https://products.groupdocs.com/comparison/java/pps/), [PPSX](https://products.groupdocs.com/comparison/java/ppsx/), [PPSM](https://products.groupdocs.com/comparison/java/ppsm/), [POT](https://products.groupdocs.com/comparison/java/pot/), [POTM](https://products.groupdocs.com/comparison/java/potm/), [POTX](https://products.groupdocs.com/comparison/java/potx/), [PPTM](https://products.groupdocs.com/comparison/java/pptm/)
                * **Visio:** [VSD](https://products.groupdocs.com/comparison/java/vsd/), [VDX](https://products.groupdocs.com/comparison/java/vdx/), [VSS](https://products.groupdocs.com/comparison/java/vss/), [VSSX](https://products.groupdocs.com/comparison/java/vssx/), [VSX](https://products.groupdocs.com/comparison/java/vsx/), [VST](https://products.groupdocs.com/comparison/java/vst/), [VSTX](https://products.groupdocs.com/comparison/java/vstx/), [VTX](https://products.groupdocs.com/comparison/java/vtx/), [VSDX](https://products.groupdocs.com/comparison/java/vsdx/), [VDW](https://products.groupdocs.com/comparison/java/vdw/), [VSTM](https://products.groupdocs.com/comparison/java/vstm/), [VSSM](https://products.groupdocs.com/comparison/java/vssm/), [VSDM](https://products.groupdocs.com/comparison/java/vsdm/)
                * **Outlook:** [MSG](https://products.groupdocs.com/comparison/java/msg/), [EML](https://products.groupdocs.com/comparison/java/eml/), [EMLX](https://products.groupdocs.com/comparison/java/emlx/), [PST](https://products.groupdocs.com/comparison/java/pst/), [OST](https://products.groupdocs.com/comparison/java/ost/)
                * **OneNote:** [ONE](https://products.groupdocs.com/comparison/java/one/)

        right:
          enable: true
          table:
            # table loop
            - title: "Outros formatos"
              content: |
                * **Programming Languages**: [CS](https://products.groupdocs.com/comparison/java/cs/), [Java](https://products.groupdocs.com/comparison/java/java/), [CPP](https://products.groupdocs.com/comparison/java/cpp/), [JS](https://products.groupdocs.com/comparison/java/js/), [PY](https://products.groupdocs.com/comparison/java/py/), [RB](https://products.groupdocs.com/comparison/java/rb/), [PL](https://products.groupdocs.com/comparison/java/pl/), [ASM](https://products.groupdocs.com/comparison/java/asm/), [GROOVY](https://products.groupdocs.com/comparison/java/groovy/), [JSON](https://products.groupdocs.com/comparison/java/json/), [PHP](https://products.groupdocs.com/comparison/java/php/), [SQL](https://products.groupdocs.com/comparison/java/sql/), [LOG](https://products.groupdocs.com/comparison/java/log/), [DIFF](https://products.groupdocs.com/comparison/java/diff/), [LESS](https://products.groupdocs.com/comparison/java/less/), [SCALA](https://products.groupdocs.com/comparison/java/scala/)
                * **OpenDocument**: [ODT](https://products.groupdocs.com/comparison/java/odt/), [OTT](https://products.groupdocs.com/comparison/java/ott/), [ODS](https://products.groupdocs.com/comparison/java/ods/), [ODP](https://products.groupdocs.com/comparison/java/odp/), [OTP](https://products.groupdocs.com/comparison/java/otp/)
                * **Portable**: [PDF](https://products.groupdocs.com/comparison/java/pdf/), [MOBI](https://products.groupdocs.com/comparison/java/mobi/)
                * **AutoCAD**: [DXF](https://products.groupdocs.com/comparison/java/dxf/), [DWG](https://products.groupdocs.com/comparison/java/dwg/)
                * **Email**: [EML](https://products.groupdocs.com/comparison/java/eml/), [EMLX](https://products.groupdocs.com/comparison/java/emlx/), [MSG](https://products.groupdocs.com/comparison/java/msg/)
                * **Images**: [JPEG](https://products.groupdocs.com/comparison/java/jpeg/), [BMP](https://products.groupdocs.com/comparison/java/bmp/), [PNG](https://products.groupdocs.com/comparison/java/png/), [GIF](https://products.groupdocs.com/comparison/java/gif/), [DCM](https://products.groupdocs.com/comparison/java/dcm/), [DICOM](https://products.groupdocs.com/comparison/java/dicom/), [DjVu](https://products.groupdocs.com/comparison/java/djvu/)
                * **Web**: [HTM](https://products.groupdocs.com/comparison/java/htm/), [HTML](https://products.groupdocs.com/comparison/java/html/), [MHTML](https://products.groupdocs.com/comparison/java/mhtml/)
                * **Text**: [TXT](https://products.groupdocs.com/comparison/java/txt/)

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Comparison for Java oferece suporte aos seguintes sistemas operacionais, estruturas e gerenciadores de pacotes:
      
        left:
          enable: true
          table:
            # loop de tabela
            - icon: "fab fa-windows"
              title: "Sistemas Operacionais"
              content: |
                * Microsoft Windows Desktop
                * Microsoft Windows Server
                * Linux
                * MacOS

            # loop de tabela
            - icon: "fas fa-code"
              title: "Estruturas suportadas"
              content: |
                * Java 7 (1.7) e superior

        right:
          enable: true
          table:
            # loop de tabela
            - icon: "fas fa-cogs"
              title: "Ambientes de Desenvolvimento"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse
            # loop de tabela
            - icon: "fas fa-tools"
              title: "Ferramenta de Automação de Construção"
              content: |
                * Maven

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Сomparison para recursos Java"

    feature:
      # loop de recursos
      - icon: "fas fa-copy"
        content: "[Compare e identifique alterações no conteúdo e no estilo de texto](https://docs.groupdocs.com/comparison/java/compare-documents/)"

      # loop de recursos
      - icon: "fas fa-eye"
        content: "[Salvar lista de comparação resumida sobre documentos comparados](https://docs.groupdocs.com/comparison/java/get-extended-information-on-the-summary-page/)"

      # loop de recursos
      - icon: "fas fa-bolt"
        content: "[Comparar páginas específicas de documentos do Word](https://docs.groupdocs.com/comparison/java/accept-or-reject-detected-changes/)"
      
      # loop de recursos
      - icon: "fas fa-file-powerpoint"
        content: "[Mescle até 3 arquivos do Microsoft Word para comparar com suporte para “Rastrear alterações”](https://docs.groupdocs.com/comparison/java/compare-multiple-documents-with-specific-compare-settings/ )"

      # loop de recursos
      - icon: "fas fa-code"
        content: "[Identifique facilmente quais alterações vêm de qual documento durante a comparação](https://docs.groupdocs.com/comparison/java/get-list-of-changes/)"

      # loop de recursos
      - icon: "fas fa-cloud"
        content: "[Suporte para ler documentos de origem e enviar documentos resultantes por meio de fluxos](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # loop de recursos
      - icon: "fas fa-remove-format"
        content: "[Detectar tipo de formato de arquivo durante a busca do fluxo](https://docs.groupdocs.com/comparison/java/get-file-info/)"

      # loop de recursos
      - icon: "fas fa-comment-slash"
        content: "[Comparar documentos protegidos por senha](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/)"

      # loop de recursos
      - icon: "fas fa-location-arrow"
        content: "[Salvar resultado da comparação como imagem](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"

      # loop de recursos
      - icon: "fas fa-border-all"
        content: "[Comparar diferentes formatos de arquivo como imagem](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"

      # loop de recursos
      - icon: "fas fa-wrench"
        content: "[Comparar marcas d'água em documentos PDF](https://docs.groupdocs.com/comparison/java/how-to-spot-photos-differences-in-java-or-kotlin/)"

      # loop de recursos
      - icon: "fas fa-columns"
        content: "[Comparar documentos de arquivo ou fluxo e enviar documento de resultado por meio de fluxo ou arquivo](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # loop de recursos
      - icon: "fas fa-file-word"
        content: "[Aceitar ou descartar alterações após comparação de arquivos Word, PDF ou Excel](https://docs.groupdocs.com/comparison/java/accept-or-reject-detected-changes/)"

      # loop de recursos
      - icon: "fas fa-envelope"
        content: "[Comparar documentos criptografados via arquivo ou fluxo](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # loop de recursos
      - icon: "fas fa-print"
        content: "[Opção de licenciamento medido para operações de comparação](https://docs.groupdocs.com/comparison/java/evaluation-limitations-and-licensing-of-groupdocs-comparison/)"

      # loop de recursos
      - icon: "fas fa-file-archive"
        content: "[Destacar texto para alterações marcadas ao comparar documentos PDF, Word, Excel, PowerPoint e notas](https://docs.groupdocs.com/comparison/java/customize-changes-styles/)"

      # loop de recursos
      - icon: "fas fa-lock"
        content: "[Calcular as coordenadas corretas das alterações em PDF, slides e diagramas do PowerPoint](https://docs.groupdocs.com/comparison/java/get-changes-coordinates/)"

      # loop de recursos
      - icon: "fas fa-file-code"
        content: "[Comparar vários (mais de dois) PDF, Excel, OneNote, diagrama, e-mail e documentos de texto](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/)"
      
      # loop de recursos
      - icon: "fas fa-fill-drip"
        content: "[Compare Cabeçalho e Rodapé de Formatos de Arquivo Suportados](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # loop de recursos
      - icon: "fas fa-file-excel"
        content: "[Comparar documentos e salvar páginas de documentos de diferentes formatos como imagens](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison oferece APIs de visualização de documentos para outros ambientes de desenvolvimento populares"

    solution:
        # ciclo de solução
        - img_alt: "GroupDocs.Сomparison para .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
          product: "GroupDocs.Comparison"
          platform: ".NET"
          link: "/comparison/net/"

############################# Back to top ###############################
back_to_top:
  enable: true
---