
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
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
head_title: "Python API de comparação de documentos | verificador de diferenças"
head_description: "A API Python Document Comparison oferece ferramentas eficientes para comparar documentos. Integra-se perfeitamente com o Python para rastreamento instantâneo de alterações"

############################# Header ############################
title: "Compare documentos com Python: destaque quaisquer diferenças"
description: "Use a API GroupDocs.Comparison para desenvolver aplicativos Python nativos com recursos de comparação altamente configuráveis. Compare arquivos, seu conteúdo e estilos de texto entre formatos de documentos semelhantes."
words:
  for: "pelo"

actions:
  main: "Download grátis de PyPi"
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
  title: "Compare imagens BMP em Python"
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
  description: "Uma API para comparar tipos de documentos populares, como PDF, Microsoft Office, HTML, e-mails ou imagens em aplicativos Python."
  features:
    # feature loop
    - title: "Relatórios de saída detalhados"
      content: "GroupDocs.Comparison identifica alterações no conteúdo do documento (caracteres, palavras, parágrafos, tabelas, gráficos), bem como alterações no estilo do documento. Ele fornece aos usuários um relatório contendo informações detalhadas sobre as diferenças, incluindo seu número e tipo."

    # feature loop
    - title: "Suporta formatos populares de arquivos e documentos"
      content: "Com a API GroupDocs.Comparison, você pode comparar documentos com eficiência em formatos como PDF, HTML, e-mail, Microsoft Office Word, planilhas do Excel, apresentações em PowerPoint, OneNote, diagramas do Visio, arquivos de texto, JPEG, PNG, GIF, imagens BMP, e muitos outros formatos."

    # feature loop
    - title: "Documentação abrangente e exemplos"
      content: "Documentação extensa e exemplos de código para usar a biblioteca Comparison em diferentes plataformas estão disponíveis, facilitando a integração da API GroupDocs.Comparison em seu aplicativo Python."

    # feature loop
    - title: "Selecione e mescle alterações em um arquivo"
      content: "Se você tiver versões diferentes de um documento, poderá selecionar alterações específicas e compilar um novo documento usando a biblioteca GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independência da plataforma"
  description: "GroupDocs.Comparison for Python via .NET oferece suporte aos seguintes sistemas operacionais, estruturas e gerenciadores de pacotes"
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
    GroupDocs.Comparison for Python via .NET oferece suporte a operações com os seguintes [formatos de arquivo](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
  title: "Recursos do GroupDocs.Comparison for Python via .NET"
  description: "Compare facilmente documentos PDF e Office, imagens e outros formatos."

  items:
    # feature loop
    - icon: "compare"
      title: "Comparação de documentos fácil de usar"
      content: "Analise e identifique diferenças entre dois documentos."

    # feature loop
    - icon: "note-stack"
      title: "Compare vários documentos"
      content: "Analise e identifique diferenças em vários documentos simultaneamente."

    # feature loop
    - icon: "stacks"
      title: "Formatos Suportados"
      content: "Suporta mais de 50 formatos de documentos populares de várias categorias."

    # feature loop
    - icon: "rule"
      title: "Aceitar ou rejeitar alterações"
      content: "Representação visual clara das alterações identificadas, com a opção de aceitar ou rejeitar modificações."

    # feature loop
    - icon: "preview"
      title: "Gerar visualizações"
      content: "Salve os resultados da comparação como imagens."

    # feature loop
    - icon: "two-pager"
      title: "Comparação de conteúdo"
      content: "Compare o conteúdo do texto linha por linha, por parágrafos, por palavras ou por caracteres. Destaque as alterações."

    # feature loop
    - icon: "format_color_text"
      title: "Comparação de estilos"
      content: "Detecte alterações na formatação e nos estilos."

    # feature loop
    - icon: "folder-managed"
      title: "Definir metadados"
      content: "Retenha os metadados dos arquivos de origem ou de destino ou permita que sejam especificados pelos usuários."

    # feature loop
    - icon: "lock"
      title: "Proteção de senha"
      content: "Analise documentos criptografados ou proteja o documento resultante com uma senha."

    # feature loop
    - icon: "select"
      title: "Compare páginas específicas"
      content: "Carregue e compare seções ou páginas específicas de um documento."

    # feature loop
    - icon: "speaker-notes"
      title: "Exibir comentários"
      content: "Escolha ocultar ou mostrar comentários ao carregar o documento de origem."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Amostras de código"
  description: "Explore casos de uso típicos de operações GroupDocs.Comparison for Python via .NET"
  items:
    # code sample loop
    - title: "Comparando documentos protegidos por senha"
      content: |
        Para comparar documentos que estão [protegidos por senha](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/), você precisa especificar a senha ao carregar os documentos:
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