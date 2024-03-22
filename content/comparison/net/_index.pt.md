
---
############################# Static ############################
layout: "landing"
date: 2024-03-22T13:27:50
draft: false

lang: pt
product: "Comparison"
product_tag: "comparison"
platform: "Net"
platform_tag: "net"

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

############################# Head ############################
head_title: "C# .NET Software de comparação de documentos | diff checker"
head_description: "C# .NET Software para comparar o estilo e o conteúdo do documento. Compare documentos de vários formatos compatíveis para identificar alterações entre os arquivos."

############################# Header ############################
title: "Compare documentos com facilidade em suas soluções C# .NET"
description: "Crie C# aplicativos com uma API flexível de comparação de documentos que permite a comparação de arquivos por conteúdo e estilo em vários formatos de documentos."
words:
  for: "pelo"

actions:
  main: "Download grátis de NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Comparison"
  alt: "Licenciamento"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/net/"
  title: "Pronto para começar?"
  description: "Experimente os GroupDocs.Comparison recursos gratuitamente ou solicite uma licença"

release:
  title: "Versão {0} lançada"
  notes: "Veja o que há de novo"
  downloads: "Downloads"

code:
  title: "Compare DOCX arquivos em C#"
  more: "Mais exemplos"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET"
  install: "dotnet add package GroupDocs.Comparison"
  content: |
    ```csharp {style=abap}   
    // Especifique o documento de origem
    using (Comparer comparer = new Comparer("source.docx"))
    {
        // Adicione um ou mais documentos de destino
        comparer.Add("target.docx");

        // Especifique as opções de comparação
        CompareOptions options = new CompareOptions() 
        {ShowRevisions = false};

        // Comparar e salvar resultado
        comparer.Compare("result.docx", options);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison em um piscar de olhos"
  description: "API para comparar diferenças entre documentos em .NET aplicativos"
  features:
    # feature loop
    - title: "Comparação de arquivos em C#"
      content: "Detecte diferenças entre os arquivos de origem e de destino para alterações nos níveis de parágrafos, palavras e caracteres. Identifique alterações de estilo e formatação, como negrito, itálico, sublinhados, tachados, tipos de fonte etc."

    # feature loop
    - title: "Os formatos de arquivo e documento mais populares são suportados"
      content: "A API GroupDocs.Comparison permite uma comparação eficiente de documentos em uma ampla variedade de formatos, incluindo PDF, HTML, e-mails, Microsoft Office documentos (Word, Excel, PowerPoint, OneNote, Visio), vários tipos de imagem (JPEG, PNG, GIF, BMP), arquivos de texto e muito mais."

    # feature loop
    - title: "Aplique ou rejeite alterações facilmente"
      content: "Cada diferença identificada nos documentos comparados usando a API GroupDocs.Comparison pode ser aplicada ou rejeitada seletivamente, permitindo a personalização antes de exportar para o documento de saída final."

    # feature loop
    - title: "Relatório resumido de comparação"
      content: "Gere um relatório resumido das diferenças, detalhando todas as alterações encontradas nos documentos comparados e salve-o para referência."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independência da plataforma"
  description: "GroupDocs.Comparison for .NET suporta os seguintes sistemas operacionais, estruturas e gerenciadores de pacotes"
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
    - title: "VS Code"
      image: "vs_code"
    # platform loop
    - title: "ReSharper"
      image: "resharper"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NuGet"
      image: "nuget"

############################# File formats ############################
formats:
  enable: true
  title: "Formatos de arquivo suportados"
  description: |
    GroupDocs.Comparison for .NET suporta operações com os seguintes [formatos de arquivo](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
      content: "Analise e identifique diferenças entre dois documentos."

    # feature loop
    - icon: "note-stack"
      title: "Compare vários documentos"
      content: "Analise e identifique simultaneamente as diferenças em vários documentos."

    # feature loop
    - icon: "stacks"
      title: "Formatos suportados"
      content: "Compatível com mais de 50 formatos de documentos amplamente usados de várias categorias, garantindo ampla aplicabilidade."

    # feature loop
    - icon: "rule"
      title: "Aceitar ou rejeitar alterações"
      content: "Exibição visual clara das alterações detectadas, completa com opções para aceitar ou rejeitar essas modificações."

    # feature loop
    - icon: "preview"
      title: "Gere visualizações"
      content: "Capacidade de salvar os resultados da comparação como visualizações de imagens para facilitar a consulta e o compartilhamento."

    # feature loop
    - icon: "two-pager"
      title: "Comparação de conteúdo"
      content: "Faça comparações completas de texto em vários níveis, incluindo linha por linha, parágrafo, palavra e caractere, com diferenças destacadas para maior clareza."

    # feature loop
    - icon: "format_color_text"
      title: "Comparação de estilo e formatação"
      content: "Detecta e destaca alterações na formatação e no estilo do documento, garantindo uma revisão abrangente."

    # feature loop
    - icon: "folder-managed"
      title: "Configurações flexíveis de metadados"
      content: "Preserve os metadados dos arquivos de origem ou de destino ou personalize-os de acordo com as preferências do usuário."

    # feature loop
    - icon: "lock"
      title: "Proteção por senha"
      content: "Analise documentos protegidos por senha e proteja o documento de saída com criptografia de senha para maior segurança."

    # feature loop
    - icon: "select"
      title: "Comparação seletiva de páginas"
      content: "Carregue e compare seções ou páginas específicas de um documento para análise direcionada."

    # feature loop
    - icon: "speaker-notes"
      title: "Exibir comentários"
      content: "Escolha exibir ou ocultar comentários ao carregar o documento de origem, oferecendo maior controle sobre o processo de comparação."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Amostras de código"
  description: "Alguns casos de uso de operações GroupDocs.Comparison for .NET típicas"
  items:
    # code sample loop
    - title: "Comparando documentos protegidos por senha."
      content: |
        Para comparar documentos que estão [protegidos com uma senha](https://docs.groupdocs.com/comparison/net/load-password-protected-documents/), você precisa especificá-los e depois carregar os documentos:
        {{< landing/code title="Como comparar documentos protegidos por senha.">}}
        ```csharp {style=abap}
        // Carregue o documento de origem e especifique sua senha
        using(Comparer comparer = new Comparer("source.docx", new LoadOptions() {Password = "1234"}))  
        {
            // Carregue o documento de destino e especifique sua senha
            comparer.Add("target.docx", new LoadOptions() {Password = "5678"});

            // Salvar resultado da comparação em um arquivo especificado
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Comparando vários PDF documentos."
      content: |
        GroupDocs.Comparison permite que você [compare mais de dois documentos](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/). A operação é quase a mesma da comparação de dois arquivos. Você só precisa adicionar mais arquivos de destino à classe `comparer`.
        {{< landing/code title="Como comparar três ou mais documentos.">}}
        ```csharp {style=abap}   
        // Carregue o documento de origem
        using(Comparer comparer = new Comparer("source.docx") 
        {
            // Especifique o segundo arquivo para comparação
            comparer.Add("target2.docx");
            
            // Especifique o terceiro arquivo para comparação
            comparer.Add("target3.docx");
            
            // Salvar resultado da comparação em um arquivo especificado
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---
