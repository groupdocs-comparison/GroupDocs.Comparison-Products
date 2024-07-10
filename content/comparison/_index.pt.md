
---
############################# Static ############################
layout: "family"
date:  2024-07-10T18:47:13
draft: false

product: "Comparison"
product_tag: "comparison"

lang: pt

############################# Head ############################
head_title: "Biblioteca de comparação de documentos Python C# Java Node.js | verificador de diferenças"
head_description: "GroupDocs Biblioteca de comparação de documentos nativa para C# .NET Java e Node.js. Verifique as diferenças entre os arquivos dos formatos suportados."

############################# Header ############################
title: "Compare as diferenças entre os tipos de arquivo populares"
description: |
  API robusta para comparação de documentos em vários formatos de arquivo.

  Identifique e destaque as diferenças de conteúdo com o mínimo esforço de codificação.

  Destaque as diferenças visíveis e descubra as alterações nas propriedades ocultas.

############################# Supported Platforms ###############################
supported_platforms:
  enable: true
  head_title: "Escolha sua plataforma"
  title: "Independência da plataforma"
  description: "A biblioteca GroupDocs.Comparison suporta os seguintes sistemas operacionais e estruturas:"
  details_link_title: "Saiba mais"

  items:
    # items loop
    - title: ".NET"
      description: GroupDocs.Comparison pelo .NET 
      color: "blue"
      tag: "net"
      link: "/comparison/net/"
      features_link: "https://docs.groupdocs.com/comparison/net/system-requirements/"
      features:
          # features loop
          - rows: "4"
            content: |
                    .NET Framework 4.6.2 or higher <br> .NET Core 2.0 or higher <br> .NET 6.0 or higher
      
          # features loop
          - rows: "1"
            content: |
                    Windows <br> Linux <br> Mac OS
      
          # features loop
          - rows: "3"
            content: |
                    Microsoft Visual Studio <br> JetBrains Rider
      
          # features loop
          - rows: "1"
            content: |
                    50+ file formats
      

    # items loop
    - title: "Java"
      description: GroupDocs.Comparison pelo Java
      color: "red"
      tag: "java"
      link: "/comparison/java/"
      features_link: "https://docs.groupdocs.com/comparison/java/system-requirements/"
      features:
          # features loop
          - rows: "4"
            content: |
                    Java 8 or higher <br> Kotlin
      
          # features loop
          - rows: "1"
            content: |
                    Windows <br> Linux <br> Mac OS
      
          # features loop
          - rows: "3"
            content: |
                    IntelliJ IDEA <br> Eclipse <br> NetBeans
      
          # features loop
          - rows: "1"
            content: |
                    50+ file formats

    # items loop
    - title: "Node.js"
      description: GroupDocs.Comparison pelo Node.js
      color: "green"
      tag: "nodejs-java"
      link: "/comparison/nodejs-java/"
      features_link: "https://docs.groupdocs.com/comparison/nodejs-java/system-requirements/"
      features:
          # features loop
          - rows: "4"
            content: |
                    Node.js 16+ and J2SE 8.0 (1.8)+
      
          # features loop
          - rows: "1"
            content: |
                    Windows <br> Linux <br> Mac OS
      
          # features loop
          - rows: "3"
            content: |
                    Atom <br> Visual Studio Code <br> Qualquer outro editor de texto
      
          # features loop
          - rows: "1"
            content: |
                    50+ file formats

    # items loop
    - title: "Python"
      description: GroupDocs.Comparison Python
      color: "yellow"
      tag: "python-net"
      link: "/comparison/python-net/"
      features_link: "https://docs.groupdocs.com/comparison/net/system-requirements/"
      features:
          # features loop
          - rows: "4"
            content: |
                    Python 3.9+ and .Net 6+
      
          # features loop
          - rows: "1"
            content: |
                    Windows <br> Linux <br> Mac OS
      
          # features loop
          - rows: "3"
            content: |
                    IDLE <br> PyCharm <br> Visual Studio Code
      
          # features loop
          - rows: "1"
            content: |
                    50+ file formats

############################# Features ###############################
features:
  enable: true
  title: "Principais características de GroupDocs.Comparison"
  description: "API para comparar e diferenciar a visualização em PDF, Word, Excel, arquivos de código-fonte e muito mais."

  items:
    # items loop
    - icon: "analize"
      title: "Resultado intuitivo de visualização de diferenças"
      content: "Analise as alterações facilmente com as diferenças destacadas em um relatório de documento único."

    # items loop
    - icon: "merge"
      title: "Processo eficiente de revisão de mudanças"
      content: "Aceite ou rejeite mudanças com modificações visualmente distintas para facilitar a tomada de decisões."

    # items loop
    - icon: "styles"
      title: "Compare conteúdo e estilo"
      content: "Compare o conteúdo do texto, bem como as mudanças na formatação e no estilo."

    # items loop
    - icon: "pages"
      title: "Compare páginas específicas"
      content: "Carregue apenas as seções ou páginas específicas do documento a serem comparadas."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Mostra prática de código"
  description: "Alguns casos de uso de operações GroupDocs.Comparison típicas."
  items:
    # code sample loop
    - title: "Comparando dois arquivos"
      content: |
       Para comparar dois documentos, comece carregando os arquivos de origem e de destino e, em seguida, aplique o método `compare`. Você tem a flexibilidade de escolher configurações de comparação específicas para uma análise mais personalizada.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Especifique o documento de origem
            using (Comparer comparer = new Comparer("source.docx"))
            {
                // Adicione um ou mais documentos de destino
                comparer.Add(target.docx");

                // Especifique as opções de comparação
                CompareOptions options = new CompareOptions() {ShowRevisions = false};
                // Comparar e salvar resultado
                comparer.Compare("result.docx", options);
            }
            ```
        - language: "Java"
          color: "red"
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
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Especifique o documento de origem
            const comparer = new groupdocs.comparison.Comparer("source.docx");

            // Adicione um ou mais documentos de destino
            comparer.add("target.docx");

            // Especifique as opções de comparação
            const options = new groupdocs.comparison.CompareOptions();
            options.setShowRevisions(false);

            // Comparar e salvar resultado
            comparer.compare("result.docx", options);
            ```
        - language: "Python"
          color: "yellow"
          content: |
            ```python {style=abap}  
            def run():

                # Especifique o documento de origem
                with groupdocs.comparison.Comparer("source.docx") as comparer:

                    # Adicione um ou mais documentos de destino
                    comparer.add("target.docx")

                    # Especifique as opções de comparação
                    options = new groupdocs.comparison.CompareOptions()
                    options.setShowRevisions(false)

                    # Comparar e salvar resultado
                    comparer.compare("result.docx", options)
            ```


############################# Supported Formats ###############################
formats:
  enable: true
  title: "Mais de 50 formatos de arquivo suportados"
  description: "GroupDocs.Comparison permite operações de comparação em várias famílias de formatos."

############################# Metrics ###############################
metrics:
  enable: true
  title: "Métricas detalhadas e insights estatísticos"
  description: "Explore uma análise completa de nossos principais números, oferecendo métricas abrangentes e informações estatísticas sobre nossas realizações, influência e expansão."

  items:
    # items loop
    - number: "50+"
      title: "Formatos suportados"
      content: "A API acomoda mais de 50 dos formatos de arquivo e documento mais usados."

    # items loop
    - number: "800k"
      title: "NuGet downloads"
      content: "GroupDocs.Comparison para .NET recebeu mais de 800 mil downloads por meio do gerenciador de pacotes NuGet."

    # items loop
    - number: "15k"
      title: "Downloads do Maven"
      content: "GroupDocs.Comparison para Java acumulou mais de 15 mil downloads do nosso repositório Maven."

    # items loop
    - number: "140+"
      title: "Clientes satisfeitos"
      content: "Nossas bibliotecas são adotadas tanto por desenvolvedores individuais quanto por empresas de primeira linha em todo o mundo"


############################# Customers ###############################
customers:
  enable: true
  title: "Nossos clientes satisfeitos"
  description: "GroupDocs bibliotecas são empregadas por marcas mundialmente renomadas e ilustres em todo o mundo."

  items:
    # items loop
    - title: "BenQ Corporation"
      logo: "benq"
      
    # items loop
    - title: "Nasdaq Stock Market"
      logo: "nasdaq"
      
    # items loop
    - title: "AT&T Inc."
      logo: "att"
      
    # items loop
    - title: "Customer logo AstraZeneca"
      logo: "astrazeneca"
      
    # items loop
    - title: "Central Bank of Argentina"
      logo: "argentinacentralbank"
      
    # items loop
    - title: "Roche Holding AG"
      logo: "roche"
      
    # items loop
    - title: "Capita"
      logo: "capita"
      
    # items loop
    - title: "Axa S.A."
      logo: "axa"
      
    # items loop
    - title: "Instructure Inc."
      logo: "instructure"
      
    # items loop
    - title: "Wipro"
      logo: "wipro"


############################# Actions ###############################
actions:
  enable: true
  title: "Pronto para começar?"
  description: "Experimente os GroupDocs.Comparison recursos gratuitamente em sua plataforma"

  items:
    # items loop
    - title: ".NET"
      color: "blue"
      link: "/comparison/net/"

    # items loop
    - title: "Java"
      color: "red"
      link: "/comparison/java/"

    # items loop
    - title: "Node.js"
      color: "green"
      link: "/comparison/nodejs-java/"      

############################# FAQ ###############################
faq:
  enable: true
  title: "Perguntas frequentes"
  description: "Respostas às perguntas mais frequentes."

  items:
    # items loop
    - question: "A biblioteca GroupDocs.Comparison precisa de algum outro software de terceiros para manipular documentos?"
      answer: "O GroupDocs.Comparison não requer a instalação de nenhum software externo, como o Adobe Acrobat, Microsoft Office ou qualquer outro."

    # items loop
    - question: "Posso experimentar a biblioteca GroupDocs.Comparison antes de comprá-la?"
      answer: "Sim, você pode tentar GroupDocs.Comparison sem comprar uma licença. Uma vez instalada sem uma licença, a biblioteca funciona no modo de teste. Nesse modo, os emblemas de teste são adicionados ao documento resultante e ele é cortado nas primeiras 3 páginas. Se quiser testar GroupDocs.Comparison sem as limitações da versão de teste, você também pode solicitar uma licença temporária de 30 dias. Para obter mais detalhes, consulte [licença temporária](https://purchase.groupdocs.com/temporary-license/)."

    # items loop
    - question: "Quais licenças você tem?"
      answer: "Oferecemos vários tipos de licença para atender às necessidades de desenvolvedores ou empresas específicas. Os tipos de licença dependem do número de desenvolvedores, do número de locais dos sites dos desenvolvedores e da necessidade de entregar nosso SDK/API aos seus clientes finais. Como alternativa, você pode escolher licenças limitadas com base no uso mensal do produto. Saiba mais em [pricing](https://purchase.groupdocs.com/pricing/comparison/net/)."

############################# Cloud Links ###############################
cloud_links:
  enable: true
  title: "GroupDocs.Comparison APIs de baixo código"
  description: "Incorpore recursos de comparação de documentos em qualquer aplicativo usando nossa API REST baseada em nuvem."
  
  items:
    # items loop
    - title: "GroupDocs.Comparison Cloud for cURL"
      content: "Trabalhe com a API completa de comparação de documentos cURL REST para comparar Word, Excel, PowerPoint e outros formatos de arquivo populares."
      icon: "groupdocs_comparison-for-curl"
      link: "https://products.groupdocs.cloud/comparison/curl"

    # items loop
    - title: "GroupDocs.Comparison Cloud for .NET"
      content: "Adicione recursos poderosos de comparação de documentos em .NET aplicativos usando o Cloud SDK para .NET. Compare DOCX, XLSX, PPTX e muito mais."
      icon: "groupdocs_comparison-for-net"
      link: "https://products.groupdocs.cloud/comparison/net"

    # items loop
    - title: "GroupDocs.Comparison Cloud for Java"
      content: "Adicione recursos de comparação de documentos de alta fidelidade aos seus aplicativos java com o SDK de comparação de documentos especialmente projetado para Java."
      icon: "groupdocs_comparison-for-java"
      link: "https://products.groupdocs.cloud/comparison/java"

############################# App links ###############################
app_links:
  enable: true
  title: "GroupDocs.Comparison aplicativos NoCode"
  description: "Aplicativo baseado na web que permite realizar comparações em mais de 50 formatos de arquivo populares diretamente no seu navegador."

  items:
    # items loop
    - title: "GroupDocs.Comparison Total"
      content: "Ferramenta de comparação online para comparar dois documentos de qualquer dispositivo."
      icon: "groupdocs_comparison-app"
      link: "https://products.groupdocs.app/comparison/total"

    # items loop
    - title: "GroupDocs.Comparison DOCX"
      content: "Compare DOCX arquivos online."
      icon: "groupdocs_words-app"
      link: "https://products.groupdocs.app/comparison/docx"

    # items loop
    - title: "GroupDocs.Comparison PDF"
      content: "Difere PDF documentos online usando o aplicativo de comparação PDF."
      icon: "groupdocs_pdf-app"
      link: "https://products.groupdocs.app/comparison/pdf"


      


---