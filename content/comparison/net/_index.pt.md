---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "API de comparação de documentos C# .NET | Comparar e mesclar PDF Word Excel Web e texto"
head_description: "API de comparação de documentos C# .NET. Compare e mescle PDF Word DOC DOCX, planilha do Excel, PPT, PPTX, HTML, EMLX MSG, VSDX, DXF DWG e formatos de arquivo de imagem."

############################# Header ############################
title: "API .NET para comparar arquivos"
description: "Desenvolva aplicativos usando a API de comparação de documentos .NET para verificar e comparar arquivos em busca de diferenças de conteúdo e estilo."
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
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
        product: "GroupDocs.Comparison"
        platform: ".NET"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "Visão geral"

            # button loop
            - link: "#features"
              text: "Características"

            # button loop
            - link: "#support"
              text: "Apoiar"

            # button loop
            - link: "https://products.groupdocs.app/comparison"
              text: "Demonstração ao vivo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "Preços"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    example_image: "/comparison/comparison-example.webp"
    content: |
      
    more_overview:
      # more_overview_loop
      - title: "O que é GroupDocs.Comparison for .NET"
        content: "A API GroupDocs.Comparison for .NET é uma solução rápida e confiável, pronta para uso na criação de aplicativos para pesquisar e destacar diferenças entre documentos do mesmo ou de diferentes formatos em C#, ASP.NET ou outras tecnologias relacionadas à plataforma de software .NET."

      # more_overview_loop
      - title: "Formatos Suportados"
        content: "A biblioteca GroupDocs.Comparison suporta a detecção de diferenças no conteúdo e no estilo de texto entre formatos populares de imagens e documentos, como PDF, HTML, Outlook por e-mail, documentos do Microsoft Office Word, planilhas do Excel, apresentações em PowerPoint, OneNote, diagramas do Visio, textos, png , imagens gif e bmp, bem como uma centena de outros formatos."
        
      # more_overview_loop
      - title: "Capacidades de comparação"
        content: "A comparação pode ser realizada para detectar alterações no conteúdo de palavras, parágrafos, tabelas ou gráficos e seus estilos, e fornecerá um documento de comparação que lista um resumo das diferenças, seu número e tipo de pertença. GroupDocs.Comparison for .NET pode extrair facilmente informações básicas sobre o documento de origem, comparar e salvar documentos simples, protegidos por senha e criptografados de vários formatos por meio de um arquivo ou fluxo de dados."
        
      # more_overview_loop
      - title: "Documentação e exemplos"
        content: "Já existe muita documentação sobre o uso da biblioteca Comparison em diferentes plataformas com exemplos de código, então você não precisa pensar muito sobre como trabalhar com GroupDocs.Comparison for .NET API em seu aplicativo."
        
      # more_overview_loop
      - title: "Compatibilidade"
        content: "Você pode usar GroupDocs.Comparison for .NET para criar aplicativos em qualquer ambiente de desenvolvimento orientado à plataforma .NET. É compatível com todas as linguagens baseadas em .NET e oferece suporte a sistemas operacionais populares (Windows, Linux, MacOS) nos quais você pode instalar estruturas Mono ou .NET (incluindo .NET Core)."
    examples:
      enable: true
      
    more_feature:
      # more_feature_loop
      - title: "Compare facilmente documentos usando a API .NET"
        content: |
          A API GroupDocs.Comparison for .NET oferece uma maneira fácil e eficiente de comparar seus arquivos. A seguir está um exemplo que mostra como comparar dois documentos DOCX usando C#:  

          ```cs
          // Arquivos de origem e de destino a serem comparados
          string source = @"source.docx";
          string target = @"target.docx";
          Comparer comparer = new Comparer();
          // Compare dois documentos
          ICompareResult result = comparer.Compare(source, target, new ComparisonSettings());
          ```
      # more_feature_loop
      - title: "Escolha o nível de detalhe para comparação"
        content: "Com GroupDocs.Comparison for .NET você pode especificar até que ponto deseja que os documentos sejam comparados. Você pode escolher entre baixo (comparar texto palavra por palavra com precisão para grade de imagem = 50), médio (comparar texto caractere por caractere com precisão para grade de imagem = 100) ou alto (comparar texto caractere por caractere com precisão para grade de imagem = 150)."

      # more_feature_loop
      - title: "Suporte para comparação de estilos de texto"
        content: |
          GroupDocs.Comparison for .NET oferece recurso para comparar estilos de texto.  

          Enquanto palavras e caracteres de documentos estão sendo comparados, o nome da fonte, o tamanho da fonte, a cor da fonte, o estilo da fonte (negrito, itálico, sublinhado, versalete, hiperlink) e a cor do sublinhado (se aplicável) podem ser comparados para encontrar diferenças.  

          Ao comparar parágrafos, você pode comparar estilos como alinhamento de parágrafo, recuo (recuo à esquerda, recuo à direita), espaçamento de parágrafo (espaço depois, espaço antes), recuo da primeira linha e espaçamento entre linhas.  

          GroupDocs.Comparison for .NET também oferece suporte à comparação de outras seções de uma página, quando aplicável, como distância do rodapé, altura e orientação da página, margens (esquerda, direita, superior e inferior), largura da linha da borda e cor da borda.  
      
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          A seguir está uma visão geral do GroupDocs.Comparison for .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Visão geral"
          content: |
            * Comparação de documentos
            * Comparação de arquivos HTML
            * Comparação de PDFs
            * Comparação de diagramas
            * Compare o conteúdo do arquivo
            * Compare estilos de texto
      
      ## TAB TWO ##
      tab_two:
        description: |
          O GroupDocs.Comparison for .NET é compatível com todos os [formatos de arquivo de documentos](https://docs.groupdocs.com/comparison/net/supported-document-formats/) populares, incluindo: Microsoft Office, PDF, imagens e muitos outros .
        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** [DOC](https://products.groupdocs.com/comparison/net/doc/), [DOCX](https://products.groupdocs.com/comparison/net/docx/), [DOCM](https://products.groupdocs.com/comparison/net/docm/), [DOT](https://products.groupdocs.com/comparison/net/dot/), [DOTX](https://products.groupdocs.com/comparison/net/dotx/), [DOTM](https://products.groupdocs.com/comparison/net/dotm/), [RTF](https://products.groupdocs.com/comparison/net/rtf/), [TXT](https://products.groupdocs.com/comparison/net/txt/)
                * **Excel:** [XLS](https://products.groupdocs.com/comparison/net/xls/), [XLSX](https://products.groupdocs.com/comparison/net/xlsx/), [XLSM](https://products.groupdocs.com/comparison/net/xlsm/), [XLSB](https://products.groupdocs.com/comparison/net/xlsb/), [XLTM](https://products.groupdocs.com/comparison/net/xltm/), [XLT](https://products.groupdocs.com/comparison/net/xlt/), [XLTM](https://products.groupdocs.com/comparison/net/xltm/), [XLTX](https://products.groupdocs.com/comparison/net/xltx/), [XLAM](https://products.groupdocs.com/comparison/net/xlam/), [SXC](https://products.groupdocs.com/comparison/net/sxc/), [SpreadsheetML](https://products.groupdocs.com/comparison/net/xml/)
                * **PowerPoint:** [PPT](https://products.groupdocs.com/comparison/net/ppt/), [PPTX](https://products.groupdocs.com/comparison/net/pptx/), [PPS](https://products.groupdocs.com/comparison/net/pps/), [PPSX](https://products.groupdocs.com/comparison/net/ppsx/), [PPSM](https://products.groupdocs.com/comparison/net/ppsm/), [POT](https://products.groupdocs.com/comparison/net/pot/), [POTM](https://products.groupdocs.com/comparison/net/potm/), [POTX](https://products.groupdocs.com/comparison/net/potx/), [PPTM](https://products.groupdocs.com/comparison/net/pptm/)
                * **Visio:** [VSD](https://products.groupdocs.com/comparison/net/vsd/), [VDX](https://products.groupdocs.com/comparison/net/vdx/), [VSS](https://products.groupdocs.com/comparison/net/vss/), [VSSX](https://products.groupdocs.com/comparison/net/vssx/), [VSX](https://products.groupdocs.com/comparison/net/vsx/), [VST](https://products.groupdocs.com/comparison/net/vst/), [VSTX](https://products.groupdocs.com/comparison/net/vstx/), [VTX](https://products.groupdocs.com/comparison/net/vtx/), [VSDX](https://products.groupdocs.com/comparison/net/vsdx/), [VDW](https://products.groupdocs.com/comparison/net/vdw/), [VSTM](https://products.groupdocs.com/comparison/net/vstm/), [VSSM](https://products.groupdocs.com/comparison/net/vssm/), [VSDM](https://products.groupdocs.com/comparison/net/vsdm/)
                * **Outlook:** [MSG](https://products.groupdocs.com/comparison/net/msg/), [EML](https://products.groupdocs.com/comparison/net/eml/), [EMLX](https://products.groupdocs.com/comparison/net/emlx/), [PST](https://products.groupdocs.com/comparison/net/pst/), [OST](https://products.groupdocs.com/comparison/net/ost/)
                * **OneNote:** [ONE](https://products.groupdocs.com/comparison/net/one/)

        right:
          enable: true
          table:
            # table loop
            - title: "Outros formatos"
              content: |
                * **Linguagens de programação**: [CS](https://products.groupdocs.com/comparison/net/cs/), [Java](https://products.groupdocs.com/comparison/net/java/), [CPP](https://products.groupdocs.com/comparison/net/cpp/), [JS](https://products.groupdocs.com/comparison/net/js/), [PY](https://products.groupdocs.com/comparison/net/py/), [RB](https://products.groupdocs.com/comparison/net/rb/), [PL](https://products.groupdocs.com/comparison/net/pl/), [ASM](https://products.groupdocs.com/comparison/net/asm/), [GROOVY](https://products.groupdocs.com/comparison/net/groovy/), [JSON](https://products.groupdocs.com/comparison/net/json/), [PHP](https://products.groupdocs.com/comparison/net/php/), [SQL](https://products.groupdocs.com/comparison/net/sql/), [LOG](https://products.groupdocs.com/comparison/net/log/), [DIFF](https://products.groupdocs.com/comparison/net/diff/), [LESS](https://products.groupdocs.com/comparison/net/less/), [SCALA](https://products.groupdocs.com/comparison/net/scala/)
                * **OpenDocument**: [ODT](https://products.groupdocs.com/comparison/net/odt/), [OTT](https://products.groupdocs.com/comparison/net/ott/), [ODS](https://products.groupdocs.com/comparison/net/ods/), [ODP](https://products.groupdocs.com/comparison/net/odp/), [OTP](https://products.groupdocs.com/comparison/net/otp/)
                * **Portable**: [PDF](https://products.groupdocs.com/comparison/net/pdf/), [MOBI](https://products.groupdocs.com/comparison/net/mobi/)
                * **AutoCAD**: [DXF](https://products.groupdocs.com/comparison/net/dxf/), [DWG](https://products.groupdocs.com/comparison/net/dwg/)
                * **Email**: [EML](https://products.groupdocs.com/comparison/net/eml/), [EMLX](https://products.groupdocs.com/comparison/net/emlx/), [MSG](https://products.groupdocs.com/comparison/net/msg/)
                * **Images**: [JPEG](https://products.groupdocs.com/comparison/net/jpeg/), [BMP](https://products.groupdocs.com/comparison/net/bmp/), [PNG](https://products.groupdocs.com/comparison/net/png/), [GIF](https://products.groupdocs.com/comparison/net/gif/), [DCM](https://products.groupdocs.com/comparison/net/dcm/), [DICOM](https://products.groupdocs.com/comparison/net/dicom/), [DjVu](https://products.groupdocs.com/comparison/net/djvu/)
                * **Web**: [HTM](https://products.groupdocs.com/comparison/net/htm/), [HTML](https://products.groupdocs.com/comparison/net/html/), [MHTML](https://products.groupdocs.com/comparison/net/mhtml/)
                * **Text**: [TXT](https://products.groupdocs.com/comparison/net/txt/)

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Comparison for .NET oferece suporte aos seguintes sistemas operacionais, estruturas e gerenciadores de pacotes:
      
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Sistemas operacionais"
              content: |
                * Windows Desktop
                * Windows Server
                * Windows Azure
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "Estruturas suportadas"
              content: |
                * .NET Framework 2.0 ou mais alto
                * Mono Framework 1.2 ou mais alto
                * .NET Standard 2.0
                * .NET Core 2.0

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Gerenciador de pacotes"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Ambientes de desenvolvimento"
              content: |
                * Microsoft Visual Studio
                * Xamarin.Android
                * Xamarin.IOS
                * Xamarin.Mac
                * MonoDevelop

############################# Features ############################
features:
    enable: true
    title: "Recursos do GroupDocs.Comparison for .NET"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "[Identifique diferenças no conteúdo e nos estilos de fonte](https://docs.groupdocs.com/comparison/net/compare-documents/)"

      # feature loop
      - icon: "fas fa-eye"
        content: "[Salve um relatório resumido de todas as diferenças encontradas após a comparação de arquivos](https://docs.groupdocs.com/comparison/net/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-bolt"
        content: "[Aplicar ou rejeitar alterações após analisar diferenças e exportar o arquivo resultante](https://docs.groupdocs.com/comparison/net/accept-or-reject-detected-changes/)"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "[Suporte para a funcionalidade “Rastrear alterações” do Microsoft Word ao comparar arquivos do Word](https://docs.groupdocs.com/comparison/net/show-revisions/)"

      # feature loop
      - icon: "fas fa-code"
        content: "[Identifique exclusivamente alterações provenientes de cada documento que está sendo comparado](https://docs.groupdocs.com/comparison/net/get-list-of-changes/)"

      # feature loop
      - icon: "fas fa-cloud"
        content: "[Ler e enviar documentos via Streams](https://docs.groupdocs.com/comparison/net/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "[Licenciamento medido – Faturamento de acordo com o uso da API](https://docs.groupdocs.com/comparison/net/licensing-and-evaluation-limitations/)"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "[Compare vários documentos de origem com um único documento de destino](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/)"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "[Compare páginas específicas de arquivos do Word entre si – aceite ou rejeite todas as alterações em um único documento do Word](https://docs.groupdocs.com/comparison/net/accept-or-reject-detected-changes/)"

      # feature loop
      - icon: "fas fa-border-all"
        content: "[Mesclar até 3 documentos do Word e comparar fórmulas usadas em arquivos do Word](https://docs.groupdocs.com/comparison/net/how-to-merge-source-code-files/)"

      # feature loop
      - icon: "fas fa-wrench"
        content: "[Obtenha informações sobre documentos do filePath](https://docs.groupdocs.com/comparison/net/get-file-info/)"

      # feature loop
      - icon: "fas fa-columns"
        content: "[Salvar o resultado da comparação HTML como imagens](https://docs.groupdocs.com/comparison/net/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-file-word"
        content: "[Opção para mostrar ou ocultar conteúdo excluído](https://docs.groupdocs.com/comparison/net/show-gap-lines/)"

      # feature loop
      - icon: "fas fa-envelope"
        content: "[Opção para ativar ou desativar a comparação de estilos de documentos](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fas fa-print"
        content: "[Especifique strings para marcar itens inseridos, excluídos e com alteração de estilo no documento de comparação](https://docs.groupdocs.com/comparison/net/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "[Especifique o separador de palavras e a cor da fonte para estilizar o texto comparado](https://docs.groupdocs.com/comparison/net/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-lock"
        content: "[Calcule as coordenadas corretas de alterações em PDF, Word, slides e diagramas de PowerPoint](https://docs.groupdocs.com/comparison/net/get-changes-coordinates/)"

      # feature loop
      - icon: "fas fa-file-code"
        content: "[Compare arquivos protegidos por senha](https://docs.groupdocs.com/comparison/net/how-to-compare-password-protected-files/)"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "[Compare títulos de gráficos em planilhas – Gere gráfico nos arquivos de células resultantes](https://docs.groupdocs.com/comparison/net/how-to-compare-spreadsheet-or-tables/)"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "[Dimensionar automaticamente as formas automáticas no arquivo resultante do documento de células](https://docs.groupdocs.com/comparison/net/how-to-compare-spreadsheet-or-tables/)"

      # feature loop
      - icon: "fas fa-heading"
        content: "[Acesse a página de resumo detalhado para detectar alterações entre arquivos de documentos de origem e de destino](https://docs.groupdocs.com/comparison/net/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "[Compare os arquivos de linguagem de programação e script mais populares](https://docs.groupdocs.com/comparison/net/get-supported-document-formats/)"

      # feature loop
      - icon: "fas fa-cube"
        content: "[Compare vários (mais de dois) documentos PDF, Word, Excel, Diagrama, Email, Texto e OneNote](https://docs.groupdocs.com/comparison/net/compare-multiple-documents-with-specific-compare-settings/)"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "[Compare o cabeçalho e o rodapé dos formatos de arquivo suportados](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "[Compare marcadores, variáveis ​​e propriedades personalizadas de formatos de documentos do Word](https://docs.groupdocs.com/comparison/net/compare-bookmarks-in-word/)"

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison oferece APIs de visualização de documentos para outros ambientes de desenvolvimento populares"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for Java"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---