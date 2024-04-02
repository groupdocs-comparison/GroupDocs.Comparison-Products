
---
############################# Static ############################
layout: "landing"
date: 2024-04-02T14:08:51
draft: false

lang: es
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

############################# Head ############################
head_title: "Node.js API de comparación de documentos | diff checker"
head_description: "La API de comparación de documentos Node.js ofrece herramientas eficaces para la comparación de documentos. Se integra perfectamente con Node.js para realizar un seguimiento de los cambios en tiempo real"

############################# Header ############################
title: "Compare documentos con Node.js: resalte cualquier diferencia"
description: "Utilice la API GroupDocs.Comparison para desarrollar aplicaciones de script Java nativas con funciones de comparación altamente configurables. Compare archivos, su contenido y estilo de texto entre formatos de documentos similares."
words:
  for: "por"

actions:
  main: "Descarga gratuita de NPM"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.comparison"
  alt: "Licencias"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/nodejs-java/"
  title: "¿Estás listo para empezar?"
  description: "Pruebe GroupDocs.Comparison funciones de forma gratuita o solicite una licencia"

release:
  title: "Publicada la versión {0}"
  notes: "Vea qué hay de nuevo"
  downloads: "Descargas"

code:
  title: "Compara BMP imágenes en Java Script"
  more: "Más ejemplos"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.comparison"
  content: |
    ```javascript {style=abap}

    // Especifique el documento fuente
    const comparer = new Comparer("source.bmp");

    // Agregar uno o más documentos de destino
    comparer.add("target.bmp");

    // Especificar las opciones de comparación
    const options = new groupdocs.comparison.CompareOptions();
    options.setGenerateSummaryPage(false);

    // Comparar y guardar resultado
    await comparer.compare(outputFileName, options);
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison de un vistazo"
  description: "API para comparar varios tipos de documentos, como PDF, Microsoft Office, HTML, correos electrónicos o imágenes en Node.js aplicaciones"
  features:
    # feature loop
    - title: "Informes de salida detallados"
      content: "GroupDocs.Comparison identifica los cambios en el contenido del documento (caracteres, palabras, párrafos, tablas, gráficos), así como los cambios en el estilo del documento. Proporciona a los clientes un informe resultante que contiene información completa sobre las diferencias, su número y tipo."

    # feature loop
    - title: "Se admiten los formatos de archivos y documentos más populares"
      content: "Con la API GroupDocs.Comparison, puede comparar de manera eficiente documentos de cualquier formato compatible, como PDF, HTML, correo electrónico, Microsoft Office Word documentos, Excel hojas de cálculo, PowerPoint presentaciones, OneNote, Visio diagramas, textos, JPEG, PNG, GIF y BMP imágenes, así como muchos otros formatos."

    # feature loop
    - title: "Documentación y ejemplos"
      content: "Ya hay mucha documentación sobre el uso de la biblioteca Comparison en diferentes plataformas con ejemplos de código, por lo que no tienes que pensar mucho en cómo trabajar con la API GroupDocs.Comparison en tu aplicación Node.js."

    # feature loop
    - title: "Selecciona los cambios y combínalos en un solo archivo"
      content: "Si tiene diferentes versiones de un documento, es posible seleccionar solo los cambios deseados y compilar un nuevo documento utilizando la biblioteca GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independencia de la plataforma"
  description: "GroupDocs.Comparison for Node.js via Java es compatible con los siguientes sistemas operativos, marcos y gestores de paquetes"
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
  title: "Formatos de archivo compatibles"
  description: |
    GroupDocs.Comparison for Node.js via Java admite operaciones con los siguientes [formatos de archivo](https://docs.groupdocs.com/comparison/nodejs-java/supported-document-formats/).
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
  title: "GroupDocs.Comparison for Node.js via Java características"
  description: "Compara fácilmente documentos, imágenes y otros formatos de PDF y Office"

  items:
    # feature loop
    - icon: "compare"
      title: "Comparación de documentos fácil de usar"
      content: "Analice e identifique las diferencias entre dos documentos."

    # feature loop
    - icon: "note-stack"
      title: "Comparar varios documentos"
      content: "Analice e identifique las diferencias en varios documentos simultáneamente."

    # feature loop
    - icon: "stacks"
      title: "Formatos compatibles"
      content: "Soporta más de 50 formatos de documentos populares de varias categorías."

    # feature loop
    - icon: "rule"
      title: "Aceptar o rechazar los cambios"
      content: "Representación visual clara de los cambios identificados, que brinda la opción de aceptar o rechazar las modificaciones."

    # feature loop
    - icon: "preview"
      title: "Generar vistas previas"
      content: "Guarde los resultados de la comparación como imágenes."

    # feature loop
    - icon: "two-pager"
      title: "Comparación de contenido"
      content: "Compare el contenido del texto línea por línea, por párrafos, por palabras, por caracteres. Resalta los cambios."

    # feature loop
    - icon: "format_color_text"
      title: "Comparación de estilos"
      content: "Detecta cambios en el formato y los estilos."

    # feature loop
    - icon: "folder-managed"
      title: "Definir metadatos"
      content: "Guarde los metadatos de los archivos de origen o de destino o permita que los usuarios los especifiquen."

    # feature loop
    - icon: "lock"
      title: "Protección mediante contraseña"
      content: "Analice los documentos cifrados o proteja el documento resultante con una contraseña."

    # feature loop
    - icon: "select"
      title: "Comparar páginas específicas"
      content: "Cargue solo las secciones o páginas específicas del documento."

    # feature loop
    - icon: "speaker-notes"
      title: "Mostrar comentarios"
      content: "Al cargar el documento fuente, puede elegir si desea ocultar o mostrar los comentarios."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Ejemplos de código"
  description: "Algunos casos de uso de operaciones típicas de GroupDocs.Comparison for Node.js via Java"
  items:
    # code sample loop
    - title: "Comparación de documentos protegidos con contraseña."
      content: |
        Para comparar documentos que están [protegidos con contraseña](https://docs.groupdocs.com/comparison/nodejs-java/load-password-protected-documents/), debe especificarlo y luego cargar los documentos:
        {{< landing/code title="Cómo comparar documentos protegidos con contraseña.">}}
        ```javascript {style=abap}

        import { Comparer, LoadOptions } from '@groupdocs/groupdocs.comparison'

        // Cargue el documento fuente y especifique su contraseña
        const comparer = new Comparer("source.docx", new LoadOptions("1234"));

        // Cargue el documento de destino y especifique su contraseña
        comparer.add("target.docx", new LoadOptions("5678"));

        // Guardar el resultado de la comparación en un archivo especificado
        comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Comparación de varios PDF documentos."
      content: |
        GroupDocs.Comparison permite [comparar más de dos documentos](https://docs.groupdocs.com/comparison/nodejs-java/compare-multiple-documents/). La operación es casi la misma que cuando se comparan dos archivos. Solo tiene que añadir más archivos de destino a la clase `comparer`.
        {{< landing/code title="Cómo comparar tres o más documentos.">}}
        ```javascript {style=abap}
        import { Comparer } from '@groupdocs/groupdocs.comparison'

        // Cargar el documento fuente
        const comparer = new Comparer(source.pdf");

        // Especifique el segundo archivo para la comparación
        comparer.add("target2.pdf");

        // Especifique el tercer archivo para la comparación
        comparer.add("target3.pdf");

        // Guardar el resultado de la comparación en un archivo especificado
        comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---