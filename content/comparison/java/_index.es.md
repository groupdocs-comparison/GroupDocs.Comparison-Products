
---
############################# Static ############################
layout: "landing"
date: 2024-03-21T15:26:29
draft: false

lang: es
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

############################# Head ############################
head_title: "Java Biblioteca de comparación de documentos| diff checker"
head_description: "Software nativo Java para comparar el estilo y el contenido de los documentos. Compare documentos de varios formatos para identificar las diferencias."

############################# Header ############################
title: "Compare y compruebe las diferencias de archivos con la API Java"
description: "Desarrolle Java aplicaciones con una biblioteca de comparación de documentos altamente configurable para comparar formatos de documentos similares, incluidos los archivos, su contenido y el estilo del texto."
words:
  for: "por"

actions:
  main: "Descarga gratuita de Maven"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/"
  alt: "Licencias"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/java/"
  title: "¿Estás listo para empezar?"
  description: "Pruebe GroupDocs.Comparison funciones de forma gratuita o solicite una licencia"

release:
  title: "Publicada la versión {0}"
  notes: "Vea qué hay de nuevo"
  downloads: "Descargas"

code:
  title: "Compara DOCX archivos en Java"
  more: "Más ejemplos"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
  install: |
    <dependency>
      <groupId>com.groupdocs</groupId>
      <artifactId>groupdocs-comparison</artifactId>
      <version>{0}</version>
    </dependency>
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

      // Realice la comparación y guarde el documento resultante
      final comparer.compare("result.docx", options);
    }    
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison de un vistazo"
  description: "API para comparar las diferencias entre documentos en Java aplicaciones"
  features:
    # feature loop
    - title: "Comparación de archivos en Java"
      content: "Detecta cambios entre los archivos de origen y destino a nivel de párrafo, palabra y carácter. Identifique los cambios de estilo y formato, como negrita, cursiva, subrayados, tachados, tipos de fuente, etc."

    # feature loop
    - title: "Gran cantidad de formatos compatibles"
      content: "Con la API GroupDocs.Comparison, puede comparar fácilmente documentos de varios formatos compatibles. Esto incluye PDF, HTML, correo electrónico, Microsoft Office Word documentos, Excel hojas de cálculo, PowerPoint presentaciones, OneNote, Visio diagramas, textos, JPEG, PNG, GIF y BMP imágenes, así como muchos otros formatos."

    # feature loop
    - title: "Aplica o rechaza cambios fácilmente"
      content: "Todas las diferencias entre los documentos comparados se pueden aplicar o rechazar y, a continuación, exportar al documento de salida."

    # feature loop
    - title: "Informe resumido de comparación"
      content: "Genere un informe resumido que enumere todos los cambios en los documentos comparados."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independencia de la plataforma"
  description: "GroupDocs.Comparison for Java es compatible con los siguientes sistemas operativos, marcos y gestores de paquetes"
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
  title: "Formatos de archivo compatibles"
  description: |
    GroupDocs.Comparison for Java admite operaciones con los siguientes [formatos de archivo](https://docs.groupdocs.com/comparison/java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Formatos Microsoft Office y OpenDocument
        * **Word:** DOCX, DOC, DOCM,DOT, DOTM, DOTX, RTX, RTF, TXT
        * **Excel:** XLSX, XLS, XLT, XLTM, XLSB, XLSM
        * **PowerPoint:** PPTX, PPT, POT, POTX, PPS, PPSX
        * **Outlook:** EML, EMLX, MSG
        * **OneNote:** ONE
        * **OpenDocument:** ODT, ODP, OTP, ODS, OTT
        * **Diseño de página fijo:** PDF        
    # group loop
    - color: "blue"
      content: |
        ### Imágenes, gráficos y diagramas
        * **Imágenes rasterizadas:** BMP, GIF, JPG, JPEG, PNG
        * **Imagenología médica:** DICOM
        * **Microsoft Visio:** VSDX, VSD, VSS, VST, VDX
        * **AutoCAD Drawing:** DWG, DXF
      # group loop
    - color: "red"
      content: |
        ### Otros
        * **Texto:** TXT
        * **Lenguajes de programación:** CS, Java, CPP, JS, PY, RB, PL, ASM, GROOVY, JSON, PHP, SQL, LOG, DIFF, LESS, SCALA
        * **Web:** HTM, HTML, MHT, MHTML
        * **Libros electrónicos:** MOBI, DjVu
        * **Valores separados por delimitadores:** CSV

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Comparison características"
  description: "Compara fácilmente documentos, imágenes y otros formatos de PDF y Office"

  items:
    # feature loop
    - icon: "compare"
      title: "Comparación de documentos fácil de usar"
      content: "Analice y señale fácilmente las diferencias entre dos documentos."

    # feature loop
    - icon: "note-stack"
      title: "Comparar varios documentos"
      content: "Examine y resalte simultáneamente las variaciones en varios documentos."

    # feature loop
    - icon: "stacks"
      title: "Formatos compatibles"
      content: "Compatibilidad con más de 50 formatos de documentos ampliamente utilizados de diversas categorías."

    # feature loop
    - icon: "rule"
      title: "Aceptar o rechazar los cambios"
      content: "Visualización clara de los cambios identificados, con opciones para aceptar o rechazar modificaciones."

    # feature loop
    - icon: "preview"
      title: "Generar vistas previas"
      content: "Capacidad para guardar los resultados de la comparación como vistas previas de imágenes."

    # feature loop
    - icon: "two-pager"
      title: "Comparación de contenido"
      content: "Comparación exhaustiva del contenido del texto en varios niveles, incluido el análisis línea por línea, párrafo, palabra y carácter, con énfasis en las alteraciones."

    # feature loop
    - icon: "format_color_text"
      title: "Comparación de estilos"
      content: "Capacidad para detectar y resaltar alteraciones en los elementos de formato y estilo."

    # feature loop
    - icon: "folder-managed"
      title: "Definir metadatos"
      content: "Opción para conservar los metadatos de los archivos de origen o destino, o permitir la configuración de metadatos definida por el usuario."

    # feature loop
    - icon: "lock"
      title: "Protección mediante contraseña"
      content: "Facilita el análisis de los documentos protegidos con contraseña y permite la protección con contraseña de los documentos resultantes."

    # feature loop
    - icon: "select"
      title: "Comparar páginas específicas"
      content: "Cargue y compare secciones o páginas específicas de un documento según sea necesario."

    # feature loop
    - icon: "speaker-notes"
      title: "Mostrar comentarios"
      content: "Flexibilidad para mostrar u ocultar comentarios al cargar el documento fuente."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Ejemplos de código"
  description: "Algunos casos de uso de operaciones típicas de GroupDocs.Comparison for Java"
  items:
    # code sample loop
    - title: "Comparación de documentos protegidos con contraseña."
      content: |
        Para comparar documentos que están [protegidos con contraseña](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/), debe especificarlo y luego cargar los documentos:
        {{< landing/code title="Cómo comparar documentos protegidos con contraseña.">}}
        ```java {style=abap}
        // Cargue el documento fuente y especifique su contraseña
        try (Comparer comparer = new Comparer("source.docx", new LoadOptions("1234")))
        {
            // Cargue el documento de destino y especifique su contraseña
            comparer.add("target.docx", new LoadOptions("5678"));
        
            // Guardar el resultado de la comparación en un archivo especificado
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Comparación de varios PDF documentos."
      content: |
        GroupDocs.Comparison permite [comparar más de dos documentos](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/). La operación es casi la misma que cuando se comparan dos archivos. Solo tiene que añadir más archivos de destino a la clase `comparer`.
        {{< landing/code title="Cómo comparar tres o más documentos.">}}
        ```java {style=abap}   
        // Cargar el documento fuente
        try (Comparer comparer = new Comparer("source.docx") 
        {
            // Especifique el segundo archivo para la comparación
            comparer.add("target2.docx");

            // Especifique el tercer archivo para la comparación
            comparer.add("target3.docx");

            // Guardar el resultado de la comparación en un archivo especificado
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---

