
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: pt
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

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
head_title: "Node.js API de comparação de documentos | diff checker"
head_description: "A API de comparação de documentos Node.js oferece ferramentas eficientes para comparação de documentos. Integra-se perfeitamente com Node.js para rastreamento de alterações em tempo real"

############################# Header ############################
title: "Compare documentos com Node.js: destaque todas as diferenças"
description: "Use a API GroupDocs.Comparison para desenvolver aplicativos de script nativos Java com recursos de comparação altamente configuráveis. Compare arquivos, seu conteúdo e estilo de texto entre formatos de documentos semelhantes."
words:
  for: "pelo"

actions:
  main: "Download gratuito do NPM"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.comparison"
  alt: "Licenciamento"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/nodejs-java/"
  title: "Pronto para começar?"
  description: "Experimente os GroupDocs.Comparison recursos gratuitamente ou solicite uma licença"

release:
  title: "Versão {0} lançada"
  notes: "Veja o que há de novo"
  downloads: "Downloads"

code:
  title: "Compare BMP imagens em Java Script"
  more: "Mais exemplos"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.comparison"
  content: |
    ```javascript {style=abap}

    // Especifique o documento de origem
    const comparer = new Comparer("source.bmp");

    // Adicione um ou mais documentos de destino
    comparer.add("target.bmp");

    // Especifique as opções de comparação
    const options = new groupdocs.comparison.CompareOptions();
    options.setGenerateSummaryPage(false);

    // Comparar e salvar resultado
    await comparer.compare("result.bmp", options);
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison em um piscar de olhos"
  description: "API para comparar vários tipos de documentos, como PDF, Microsoft Office, HTML, e-mails ou imagens em Node.js aplicativos"
  features:
    # feature loop
    - title: "Relatórios de saída detalhados"
      content: "GroupDocs.Comparison identifica mudanças no conteúdo do documento (caracteres, palavras, parágrafos, tabelas, gráficos), bem como mudanças no estilo do documento. Ele fornece aos clientes um relatório resultante que contém informações valiosas sobre diferenças, seu número e tipo."

    # feature loop
    - title: "Os formatos de arquivo e documento mais populares são suportados"
      content: "Com a API GroupDocs.Comparison, você pode comparar com eficiência documentos de qualquer formato compatível, como PDF, HTML, e-mail, Microsoft Office Word documentos, Excel planilhas, PowerPoint apresentações, OneNote, Visio diagramas, textos, JPEG, PNG, GIF e BMP imagens, além de muitos outros formatos."

    # feature loop
    - title: "Documentação e exemplos"
      content: "Já existe muita documentação sobre o uso da biblioteca de comparação em diferentes plataformas com exemplos de código, então você não precisa pensar muito sobre como trabalhar com a API GroupDocs.Comparison em seu aplicativo Node.js."

    # feature loop
    - title: "Selecione as alterações e mescle-as em um arquivo"
      content: "Se você tiver versões diferentes de um documento, é possível selecionar somente as alterações desejadas e compilar um novo documento usando a biblioteca GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independência da plataforma"
  description: "GroupDocs.Comparison for Node.js via Java suporta os seguintes sistemas operacionais, estruturas e gerenciadores de pacotes"
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
    GroupDocs.Comparison for Node.js via Java suporta operações com os seguintes [formatos de arquivo](https://docs.groupdocs.com/comparison/nodejs-java/supported-document-formats/).
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
  title: "GroupDocs.Comparison for Node.js via Java características"
  description: "Compare facilmente PDF e documentos, imagens e outros formatos do Office"

  items:
    # feature loop
    - icon: "compare"
      title: "Comparação de documentos fácil de usar"
      content: "Analise e identifique diferenças em dois documentos."

    # feature loop
    - icon: "note-stack"
      title: "Compare vários documentos"
      content: "Analise e identifique diferenças em vários documentos simultaneamente."

    # feature loop
    - icon: "stacks"
      title: "Formatos suportados"
      content: "Suporta mais de 50 formatos de documentos populares de várias categorias."

    # feature loop
    - icon: "rule"
      title: "Aceitar ou rejeitar alterações"
      content: "Representação visual clara das alterações identificadas, oferecendo a opção de aceitar ou rejeitar modificações."

    # feature loop
    - icon: "preview"
      title: "Gere visualizações"
      content: "Salve os resultados da comparação como imagens."

    # feature loop
    - icon: "two-pager"
      title: "Comparação de conteúdo"
      content: "Compare o conteúdo do texto linha por linha, por parágrafos, por palavras, por caracteres. Destaque as mudanças."

    # feature loop
    - icon: "format_color_text"
      title: "Comparação de estilos"
      content: "Detecte mudanças na formatação e nos estilos."

    # feature loop
    - icon: "folder-managed"
      title: "Definir metadados"
      content: "Mantenha os metadados dos arquivos de origem ou de destino ou permita que eles sejam especificados pelos usuários."

    # feature loop
    - icon: "lock"
      title: "Proteção por senha"
      content: "Analise os documentos criptografados ou proteja o documento resultante com uma senha."

    # feature loop
    - icon: "select"
      title: "Compare páginas específicas"
      content: "Carregue apenas as seções ou páginas específicas do documento."

    # feature loop
    - icon: "speaker-notes"
      title: "Exibir comentários"
      content: "Ao carregar o documento de origem, você pode escolher se deseja ocultar ou mostrar comentários."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Amostras de código"
  description: "Alguns casos de uso de operações GroupDocs.Comparison for Node.js via Java típicas"
  items:
    # code sample loop
    - title: "Comparando documentos protegidos por senha."
      content: |
        Para comparar documentos que estão [protegidos com uma senha](https://docs.groupdocs.com/comparison/nodejs-java/load-password-protected-documents/), você precisa especificá-los e depois carregar os documentos:
        {{< landing/code title="Como comparar documentos protegidos por senha.">}}
        ```javascript {style=abap}

        import { Comparer, LoadOptions } from '@groupdocs/groupdocs.comparison'

        // Carregue o documento de origem e especifique sua senha
        const comparer = new Comparer("source.docx", new LoadOptions("1234"));

        // Carregue o documento de destino e especifique sua senha
        comparer.add("target.docx", new LoadOptions("5678"));

        // Salvar resultado da comparação em um arquivo especificado
        comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Comparando vários PDF documentos."
      content: |
        GroupDocs.Comparison permite que você [compare mais de dois documentos](https://docs.groupdocs.com/comparison/nodejs-java/compare-multiple-documents/). A operação é quase a mesma da comparação de dois arquivos. Você só precisa adicionar mais arquivos de destino à classe `comparer`.
        {{< landing/code title="Como comparar três ou mais documentos.">}}
        ```javascript {style=abap}
        import { Comparer } from '@groupdocs/groupdocs.comparison'

        // Carregue o documento de origem
        const comparer = new Comparer(source.pdf");

        // Especifique o segundo arquivo para comparação
        comparer.add("target2.pdf");

        // Especifique o terceiro arquivo para comparação
        comparer.add("target3.pdf");

        // Salvar resultado da comparação em um arquivo especificado
        comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---