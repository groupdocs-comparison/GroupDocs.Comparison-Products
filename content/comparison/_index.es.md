
---
############################# Static ############################
layout: "family"
date:  2024-07-08T16:47:36
draft: false

product: "Comparison"
product_tag: "comparison"

lang: es

############################# Head ############################
head_title: "Biblioteca de comparación de documentos de C# Java y Node.js | diff checker"
head_description: "GroupDocs Biblioteca de comparación de documentos nativa de C# .NET Java y Node.js. Compruebe si hay diferencias entre los archivos de los formatos compatibles."

############################# Header ############################
title: "Compare las diferencias entre los tipos de archivos populares"
description: |
  API sólida para la comparación de documentos en varios formatos de archivo.

  Identifique y resalte las diferencias de contenido con un mínimo esfuerzo de codificación.

  Resalta las diferencias visibles y descubre los cambios en las propiedades ocultas.

############################# Supported Platforms ###############################
supported_platforms:
  enable: true
  head_title: "Elige tu plataforma"
  title: "Independencia de la plataforma"
  description: "La biblioteca GroupDocs.Comparison admite los siguientes sistemas operativos y marcos:"
  details_link_title: "Obtenga más información"

  items:
    # items loop
    - title: ".NET"
      description: GroupDocs.Comparison por .NET 
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
      description: GroupDocs.Comparison por Java
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
      description: GroupDocs.Comparison por Node.js
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
                    Atom <br> Visual Studio Code <br> Cualquier otro editor de texto
      
          # features loop
          - rows: "1"
            content: |
                    50+ file formats

############################# Features ###############################
features:
  enable: true
  title: "Características principales de GroupDocs.Comparison"
  description: "API para comparar y diferenciar la visualización en archivos de código fuente de PDF, Word, Excel, etc."

  items:
    # items loop
    - icon: "analize"
      title: "Resultado intuitivo de la vista diferencial"
      content: "Analice los cambios fácilmente con las diferencias destacadas en un informe de un solo documento."

    # items loop
    - icon: "merge"
      title: "Proceso eficiente de revisión de cambios"
      content: "Acepte o rechace los cambios con modificaciones visualmente distintas para facilitar la toma de decisiones."

    # items loop
    - icon: "styles"
      title: "Compara el contenido y el estilo"
      content: "Compare el contenido del texto, así como los cambios de formato y estilo."

    # items loop
    - icon: "pages"
      title: "Comparar páginas específicas"
      content: "Cargue solo las secciones o páginas particulares del documento que desea comparar."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Práctico escaparate de código"
  description: "Algunos casos de uso de operaciones típicas de GroupDocs.Comparison."
  items:
    # code sample loop
    - title: "Comparación de dos archivos"
      content: |
       Para comparar dos documentos, comience cargando los archivos de origen y de destino y, a continuación, aplique el método `comparar`. Tiene la flexibilidad de elegir ajustes de comparación específicos para un análisis más personalizado.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Especifique el documento fuente
            using (Comparer comparer = new Comparer("source.docx"))
            {
                // Agregar uno o más documentos de destino
                comparer.Add(target.docx");

                // Especificar las opciones de comparación
                CompareOptions options = new CompareOptions() {ShowRevisions = false};
                // Comparar y guardar resultado
                comparer.Compare("result.docx", options);
            }
            ```
        - language: "Java"
          color: "red"
          content: |
            ```java {style=abap}   
            // Especifique el documento fuente
            try (Comparer comparer = new Comparer("source.docx"))
            {
                // Agregar uno o más documentos de destino
                comparer.add("target.docx");

                // Especificar las opciones de comparación
                CompareOptions options = new CompareOptions();
                options.setShowRevisions(false);

                // Comparar y guardar resultado
                final comparer.compare("result.docx", options);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Especifique el documento fuente
            const comparer = new groupdocs.comparison.Comparer("source.docx");

            // Agregar uno o más documentos de destino
            comparer.add("target.docx");

            // Especificar las opciones de comparación
            const options = new groupdocs.comparison.CompareOptions();
            options.setShowRevisions(false);

            // Comparar y guardar resultado
            comparer.compare("result.docx", options);
            ```


############################# Supported Formats ###############################
formats:
  enable: true
  title: "Compatible con más de 50 formatos de archivo"
  description: "GroupDocs.Comparison permite realizar operaciones de comparación dentro de varias familias de formatos."

############################# Metrics ###############################
metrics:
  enable: true
  title: "Métricas detalladas e información estadística"
  description: "Explore un análisis exhaustivo de nuestras cifras clave, que ofrece métricas e información estadística exhaustivas sobre nuestros logros, influencia y expansión."

  items:
    # items loop
    - number: "50+"
      title: "Formatos compatibles"
      content: "La API admite más de 50 de los formatos de archivos y documentos más utilizados."

    # items loop
    - number: "800k"
      title: "NuGet descargas"
      content: "GroupDocs.Comparison for .NET ha recibido más de 800 000 descargas a través del administrador de paquetes NuGet."

    # items loop
    - number: "15k"
      title: "Descargas de Maven"
      content: "GroupDocs.Comparison for Java ha acumulado más de 15 000 descargas desde nuestro repositorio de Maven."

    # items loop
    - number: "140+"
      title: "Clientes satisfechos"
      content: "Nuestras bibliotecas son adoptadas tanto por desarrolladores individuales como por empresas de primer nivel en todo el mundo"


############################# Customers ###############################
customers:
  enable: true
  title: "Nuestros clientes satisfechos"
  description: "GroupDocs bibliotecas son empleadas por marcas reconocidas y distinguidas de todo el mundo."

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
  title: "¿Estás listo para empezar?"
  description: "Prueba GroupDocs.Comparison funciones gratis en tu plataforma"

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
  title: "Preguntas frecuentes"
  description: "Respuestas a las preguntas más frecuentes."

  items:
    # items loop
    - question: "¿La biblioteca GroupDocs.Comparison necesita algún otro software de terceros para manipular los documentos?"
      answer: "GroupDocs.Comparison no requiere la instalación de ningún software externo, como Adobe Acrobat, Microsoft Office o cualquier otro."

    # items loop
    - question: "¿Puedo probar la biblioteca GroupDocs.Comparison antes de comprarla?"
      answer: "Sí, puedes probar GroupDocs.Comparison sin comprar una licencia. Una vez instalada sin licencia, la biblioteca funciona en modo de prueba. En este modo, las insignias de prueba se añaden al documento resultante y se recortan hasta quedar en las 3 primeras páginas. Si desea probar GroupDocs.Comparison sin las limitaciones de la versión de prueba, también puede solicitar una licencia temporal de 30 días. Para obtener más información, consulta [licencia temporal](https://purchase.groupdocs.com/temporary-license/)."

    # items loop
    - question: "¿Qué licencias tiene?"
      answer: "Ofrecemos varios tipos de licencias que se adaptan a las necesidades de determinados desarrolladores o empresas. Los tipos de licencia dependen del número de desarrolladores, del número de ubicaciones de los sitios web de los desarrolladores y de si necesitas ofrecer nuestro SDK/API a tus clientes finales. Como alternativa, puedes elegir las licencias con límite en función del uso mensual del producto. Obtén más información en [pricing](https://purchase.groupdocs.com/pricing/comparison/net/)."

############################# Cloud Links ###############################
cloud_links:
  enable: true
  title: "GroupDocs.Comparison API de bajo código"
  description: "Incorpore funciones de comparación de documentos en cualquier aplicación mediante nuestra API REST basada en la nube."
  
  items:
    # items loop
    - title: "GroupDocs.Comparison Cloud for cURL"
      content: "Trabaje con la API completa de comparación de documentos cURL REST para comparar Word, Excel, PowerPoint y otros formatos de archivo populares."
      icon: "groupdocs_comparison-for-curl"
      link: "https://products.groupdocs.cloud/comparison/curl"

    # items loop
    - title: "GroupDocs.Comparison Cloud for .NET"
      content: "Añade potentes funciones de comparación de documentos en .NET aplicaciones con el SDK de Cloud para .NET. Compara DOCX, XLSX, PPTX y más."
      icon: "groupdocs_comparison-for-net"
      link: "https://products.groupdocs.cloud/comparison/net"

    # items loop
    - title: "GroupDocs.Comparison Cloud for Java"
      content: "Añada funciones de comparación de documentos de alta fidelidad a sus aplicaciones java con un SDK de comparación de documentos especialmente diseñado para Java."
      icon: "groupdocs_comparison-for-java"
      link: "https://products.groupdocs.cloud/comparison/java"

############################# App links ###############################
app_links:
  enable: true
  title: "GroupDocs.Comparison Aplicaciones sin código"
  description: "Aplicación basada en la web que le permite realizar comparaciones entre más de 50 formatos de archivo populares directamente en su navegador."

  items:
    # items loop
    - title: "GroupDocs.Comparison Total"
      content: "Herramienta de diferenciación en línea para comparar dos documentos desde cualquier dispositivo."
      icon: "groupdocs_comparison-app"
      link: "https://products.groupdocs.app/comparison/total"

    # items loop
    - title: "GroupDocs.Comparison DOCX"
      content: "Compara DOCX archivos en línea."
      icon: "groupdocs_words-app"
      link: "https://products.groupdocs.app/comparison/docx"

    # items loop
    - title: "GroupDocs.Comparison PDF"
      content: "Compare PDF documentos en línea usando la aplicación de comparación PDF."
      icon: "groupdocs_pdf-app"
      link: "https://products.groupdocs.app/comparison/pdf"


      


---