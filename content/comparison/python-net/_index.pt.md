
---
############################# Static ############################
layout: "landing"
date: 2024-11-19T07:50:40
draft: false

lang: pt
product: "Comparison"
product_tag: "comparison"
platform: "Python via .NET"
platform_tag: "python-net"

############################# Drop-down ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"
    # supported_platforms loop
    - title: "Java"
      tag: "java"
    # supported_platforms loop
    - title: "Node.js"
      tag: "nodejs-java"
    # supported_platforms loop
    - title: "Python"
      tag: "python-net"

############################# Head ############################
head_title: "Python Ferramenta de comparação de documentos | Análise de Documentos"
head_description: "Descubra o poder da ferramenta de comparação de documentos Python para uma análise completa de documentos. Integra-se facilmente com Python para rastreamento abrangente de modificações."

############################# Header ############################
title: "Compare documentos com Python: destaque quaisquer diferenças"
description: "Utilize a API GroupDocs.Comparison para criar aplicativos nativos em Python com funcionalidades de comparação personalizáveis. Examine arquivos, seu conteúdo e variações de estilo em formatos de documentos."
words:
  for: "pelo"

actions:
  main: "Obtenha seu PyPi grátis Baixe agora"
  main_link: "https://pypi.org/project/groupdocs-comparison-net/"
  alt: "Licenciamento"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/python-net/"
  title: "Pronto para começar?"
  description: "Experimente os GroupDocs.Comparison recursos gratuitamente ou solicite uma licença"

release:
  title: "Versão {0} lançada"
  notes: "Veja o que há de novo"
  downloads: "Downloads"

code:
  title: "Compare imagens BMP usando Python"
  more: "Mais exemplos"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET/"
  install: "pip install groupdocs-comparison-net"
  content: |
    ```python {style=abap}
    def run():

        # Especifique o documento de origem
        with groupdocs.comparison.Comparer("in.bmp") as comparer:

            # Adicione um ou mais documentos de destino
            comparer.add("target.bmp")

            # Especifique as opções de comparação
            options = new groupdocs.comparison.CompareOptions()
            options.setGenerateSummaryPage(false)

            # Comparar e salvar resultado
            comparer.compare("result.bmp", options)
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison em um piscar de olhos"
  description: "Uma API projetada para comparar tipos de documentos amplamente usados, como PDFs, arquivos do Microsoft Office, HTML, e-mails ou imagens em aplicativos Python."
  features:
    # feature loop
    - title: "Relatórios de resultados abrangentes"
      content: "GroupDocs.Comparison detecta alterações no conteúdo do documento (caracteres, palavras, parágrafos, tabelas, gráficos), bem como alterações no estilo do documento. Os usuários recebem um relatório detalhado destacando a natureza e a contagem das alterações."

    # feature loop
    - title: "Ampla variedade de formatos de arquivos e documentos"
      content: "A API GroupDocs.Comparison permite comparar documentos em formatos como PDF, HTML, e-mail, Microsoft Office Word, pastas de trabalho do Excel, arquivos do PowerPoint, notas do OneNote, diagramas do Visio, documentos de texto, JPEG, PNG, GIF, imagens BMP, entre muitos outros."

    # feature loop
    - title: "Documentação completa e exemplos de código"
      content: "Documentação detalhada e códigos de amostra para a biblioteca Comparison em várias plataformas estão prontamente disponíveis, simplificando a integração da API GroupDocs.Comparison em seus aplicativos Python."

    # feature loop
    - title: "Selecione e combine alterações em um documento"
      content: "Se você possui várias versões de um documento, você pode compilar seletivamente as alterações em um único novo arquivo usando a biblioteca GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independência da plataforma"
  description: "GroupDocs.Comparison for Python via .NET é compatível com os seguintes sistemas operacionais, estruturas e gerenciadores de pacotes."
  items:
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "macOS"
      image: "finder"      
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NPM"
      image: "npm"  
    # platform loop
    - title: "NuGet"
      image: "nuget"      
    # platform loop
    - title: "Amazon"
      image: "amazon"
    # platform loop
    - title: "Docker"
      image: "docker"
    # platform loop
    - title: "Azure"
      image: "azure"
    # platform loop
    - title: "VS Code"
      image: "vs_code"
    # platform loop
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"

############################# File formats ############################
formats:
  enable: true
  title: "Formatos de arquivo suportados"
  description: |
    GroupDocs.Comparison for Python via .NET pode operar com os seguintes [formatos de arquivo](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### formatos Microsoft Office e OpenDocument
        * **Word:** DOCX, DOC, DOCM,DOT, DOTM, DOTX, RTX, RTF, TXT
        * **Excel:** XLSX, XLS, XLT, XLTM, XLSB, XLSM
        * **PowerPoint:** PPTX, PPT, POT, POTX, PPS, PPSX
        * **Outlook:** EML, EMLX, MSG
        * **OneNote:** ONE
        * **OpenDocument:** ODT, ODP, OTP, ODS, OTT
        * **Layout de página fixo:** PDF        
    # group loop
    - color: "blue"
      content: |
        ### Imagens, gráficos e diagramas
        * **Imagens rasterizadas:** BMP, GIF, JPG, JPEG, PNG
        * **Imagem médica:** DICOM
        * **Microsoft Visio:** VSDX, VSD, VSS, VST, VDX
        * **AutoCAD Drawing:** DWG, DXF
      # group loop
    - color: "red"
      content: |
        ### Outros
        * **Texto:** TXT
        * **Linguagens de programação:** CS, Java, CPP, JS, PY, RB, PL, ASM, GROOVY, JSON, PHP, SQL, LOG, DIFF, LESS, SCALA
        * **Web:** HTM, HTML, MHT, MHTML
        * **Livros eletrônicos:** MOBI, DjVu
        * **Valores separados por delimitador:** CSV

############################# Features ############################
features:
  enable: true
  title: "Capacidades de GroupDocs.Comparison for Python via .NET"
  description: "Compare perfeitamente PDFs, documentos do Office, imagens e uma ampla variedade de outros formatos."

  items:
    # feature loop
    - icon: "compare"
      title: "Comparação intuitiva de documentos"
      content: "Examine e destaque as diferenças entre dois documentos."

    # feature loop
    - icon: "note-stack"
      title: "Comparação de vários documentos"
      content: "Inspecione vários documentos em busca de diferenças ao mesmo tempo."

    # feature loop
    - icon: "stacks"
      title: "Amplo suporte a formatos"
      content: "Compatível com mais de 50 formatos de documentos comumente usados ​​em diversas categorias."

    # feature loop
    - icon: "rule"
      title: "Aceitar ou rejeitar alterações"
      content: "Visualize as alterações com clareza, oferecendo opções de aceitação ou rejeição de edições."

    # feature loop
    - icon: "preview"
      title: "Gerar visualizações visuais"
      content: "Crie visualizações de resultados de comparação em formatos de imagem."

    # feature loop
    - icon: "two-pager"
      title: "Comparação de conteúdo baseada em texto"
      content: "Faça comparações linha por linha, parágrafo, palavra ou caractere para destacar as alterações."

    # feature loop
    - icon: "format_color_text"
      title: "Detecção de alterações de formatação"
      content: "Identifique alterações nos estilos e formatação dos documentos."

    # feature loop
    - icon: "folder-managed"
      title: "Tratamento de metadados personalizável"
      content: "Retenha os metadados dos arquivos de origem ou de destino ou permita que os usuários definam novos metadados."

    # feature loop
    - icon: "lock"
      title: "Lidar com arquivos protegidos por senha"
      content: "Trabalhe com documentos criptografados ou crie documentos seguros protegidos por senha."

    # feature loop
    - icon: "select"
      title: "Comparações de páginas focadas"
      content: "Selecione e compare seções específicas ou páginas individuais de um documento."

    # feature loop
    - icon: "speaker-notes"
      title: "Gerenciar a visibilidade dos comentários"
      content: "Decida revelar ou ocultar comentários ao examinar o documento de origem."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Amostras de código"
  description: "Descubra cenários comuns para utilizar as funcionalidades do GroupDocs.Comparison for Python via .NET."
  items:
    # code sample loop
    - title: "Comparando documentos com proteção por senha"
      content: |
        Para comparar documentos [protegidos por senha](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/), você precisa especificar a senha ao carregar os documentos:
        {{< landing/code title="Como comparar documentos protegidos por senha.">}}
        ```python {style=abap}
        def run():

            # Carregue o documento de origem e especifique sua senha
            with groupdocs.comparison.Comparer("source.docx", new LoadOptions("1234")) as comparer:

                # Carregue o documento de destino e especifique sua senha
                comparer.add("target.docx", new LoadOptions("5678"));

                # Salvar resultado da comparação em um arquivo especificado
                comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Comparando vários PDF documentos."
      content: |
        GroupDocs.Comparison permite que você [compare mais de dois documentos](https://docs.groupdocs.com/comparison/python-net/compare-multiple-documents/). A operação é quase a mesma da comparação de dois arquivos. Você só precisa adicionar mais arquivos de destino à classe `comparer`.
        {{< landing/code title="Como comparar três ou mais documentos.">}}
        ```python {style=abap}
        def run():

            # Carregue o documento de origem
            with groupdocs.comparison.Comparer(source.pdf") as comparer:

                # Especifique o segundo arquivo para comparação
                comparer.add("target2.pdf");

                # Especifique o terceiro arquivo para comparação
                comparer.add("target3.pdf");

                # Salvar resultado da comparação em um arquivo especificado
                comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---