
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: pt
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

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
head_title: "Java Biblioteca de comparação de documentos | diff checker"
head_description: "Software nativo Java para comparar estilo e conteúdo de documentos. Compare documentos de vários formatos para identificar diferenças."

############################# Header ############################
title: "Compare e verifique as diferenças de arquivos usando a API Java"
description: "Desenvolva Java aplicativos com uma biblioteca de comparação de documentos altamente configurável para comparar formatos de documentos semelhantes, incluindo arquivos, seu conteúdo e estilo de texto."
words:
  for: "pelo"

actions:
  main: "Download grátis do Maven"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/"
  alt: "Licenciamento"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/java/"
  title: "Pronto para começar?"
  description: "Experimente os GroupDocs.Comparison recursos gratuitamente ou solicite uma licença"

release:
  title: "Versão {0} lançada"
  notes: "Veja o que há de novo"
  downloads: "Downloads"

code:
  title: "Compare DOCX arquivos em Java"
  more: "Mais exemplos"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
  install: |
    <dependency>
      <groupId>com.groupdocs</groupId>
      <artifactId>groupdocs-comparison</artifactId>
      <version>{0}</version>
    </dependency>
  content: |
    ```java {style=abap}  
    // Especifique o documento de origem
    try (Comparer comparer = new Comparer("source.docx"))
    {    
      // Adicione um ou mais documentos de destino
      comparer.add("target.docx");

      // Especifique as opções de comparação
      CompareOptions options = new CompareOptions();
      options.setShowRevisions(false);

      // Comparar e salvar resultado
      final comparer.compare("result.docx", options);
    }    
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison em um piscar de olhos"
  description: "API para comparar diferenças entre documentos em Java aplicativos"
  features:
    # feature loop
    - title: "Comparação de arquivos em Java"
      content: "Detecte alterações entre os arquivos de origem e de destino nos níveis de parágrafo, palavra e caractere. Identifique alterações de estilo e formatação, como negrito, itálico, sublinhados, tachados, tipos de fonte e muito mais."

    # feature loop
    - title: "Grande quantidade de formatos suportados"
      content: "Com a API GroupDocs.Comparison, você pode comparar facilmente documentos de vários formatos compatíveis. Isso inclui PDF, HTML, e-mail, Microsoft Office Word documentos, Excel planilhas, PowerPoint apresentações, OneNote, Visio diagramas, textos, JPEG, PNG, GIF e BMP imagens, além de muitos outros formatos."

    # feature loop
    - title: "Aplique ou rejeite alterações facilmente"
      content: "Todas as diferenças entre os documentos comparados podem ser aplicadas ou rejeitadas e depois exportadas para o documento de saída."

    # feature loop
    - title: "Relatório resumido de comparação"
      content: "Gere um relatório resumido que lista todas as alterações nos documentos comparados."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independência da plataforma"
  description: "GroupDocs.Comparison for Java suporta os seguintes sistemas operacionais, estruturas e gerenciadores de pacotes"
  items:
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
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "Maven"
      image: "maven"

############################# File formats ############################
formats:
  enable: true
  title: "Formatos de arquivo suportados"
  description: |
    GroupDocs.Comparison for Java suporta operações com os seguintes [formatos de arquivo](https://docs.groupdocs.com/comparison/java/supported-document-formats/).
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
  title: "GroupDocs.Comparison características"
  description: "Compare facilmente PDF e documentos, imagens e outros formatos do Office"

  items:
    # feature loop
    - icon: "compare"
      title: "Comparação de documentos fácil de usar"
      content: "Analise e identifique facilmente as diferenças entre dois documentos."

    # feature loop
    - icon: "note-stack"
      title: "Compare vários documentos"
      content: "Examine e destaque simultaneamente as variações em vários documentos."

    # feature loop
    - icon: "stacks"
      title: "Formatos suportados"
      content: "Compatibilidade com mais de 50 formatos de documentos amplamente usados de diversas categorias."

    # feature loop
    - icon: "rule"
      title: "Aceitar ou rejeitar alterações"
      content: "Visualização clara das alterações identificadas, com opções para aceitar ou rejeitar modificações."

    # feature loop
    - icon: "preview"
      title: "Gere visualizações"
      content: "Capacidade de salvar os resultados da comparação como visualizações de imagens."

    # feature loop
    - icon: "two-pager"
      title: "Comparação de conteúdo"
      content: "Comparação completa do conteúdo do texto em vários níveis, incluindo análise linha por linha, parágrafo, palavra e personagem, com ênfase nas alterações."

    # feature loop
    - icon: "format_color_text"
      title: "Comparação de estilos"
      content: "Capacidade de detectar e destacar alterações nos elementos de formatação e estilo."

    # feature loop
    - icon: "folder-managed"
      title: "Definir metadados"
      content: "Opção de reter metadados dos arquivos de origem ou de destino ou permitir configurações de metadados definidas pelo usuário."

    # feature loop
    - icon: "lock"
      title: "Proteção por senha"
      content: "Facilita a análise de documentos protegidos por senha e permite a proteção por senha para os documentos resultantes."

    # feature loop
    - icon: "select"
      title: "Compare páginas específicas"
      content: "Carregue e compare seções ou páginas específicas de um documento conforme necessário."

    # feature loop
    - icon: "speaker-notes"
      title: "Exibir comentários"
      content: "Flexibilidade para exibir ou ocultar comentários ao carregar o documento de origem."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Amostras de código"
  description: "Alguns casos de uso de operações GroupDocs.Comparison for Java típicas"
  items:
    # code sample loop
    - title: "Comparando documentos protegidos por senha."
      content: |
        Para comparar documentos que estão [protegidos com uma senha](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/), você precisa especificá-los e depois carregar os documentos:
        {{< landing/code title="Como comparar documentos protegidos por senha.">}}
        ```java {style=abap}
        // Carregue o documento de origem e especifique sua senha
        try (Comparer comparer = new Comparer("source.docx", new LoadOptions("1234")))
        {
            // Carregue o documento de destino e especifique sua senha
            comparer.add("target.docx", new LoadOptions("5678"));
        
            // Salvar resultado da comparação em um arquivo especificado
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Comparando vários PDF documentos."
      content: |
        GroupDocs.Comparison permite que você [compare mais de dois documentos](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/). A operação é quase a mesma da comparação de dois arquivos. Você só precisa adicionar mais arquivos de destino à classe `comparer`.
        {{< landing/code title="Como comparar três ou mais documentos.">}}
        ```java {style=abap}   
        // Carregue o documento de origem
        try (Comparer comparer = new Comparer("source.docx") 
        {
            // Especifique o segundo arquivo para comparação
            comparer.add("target2.docx");

            // Especifique o terceiro arquivo para comparação
            comparer.add("target3.docx");

            // Salvar resultado da comparação em um arquivo especificado
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---

