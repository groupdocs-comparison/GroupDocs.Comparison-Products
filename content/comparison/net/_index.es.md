
---
############################# Static ############################
layout: "landing"
date: 2024-03-22T13:27:50
draft: false

lang: es
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
head_title: "C# .NET Software de comparación de documentos | diff checker"
head_description: "C# .NET Software para comparar el estilo y el contenido de los documentos. Compare documentos de varios formatos compatibles para identificar los cambios entre los archivos."

############################# Header ############################
title: "Compare documentos con facilidad en sus soluciones C# .NET"
description: "Cree C# aplicaciones con una API de comparación de documentos flexible que permite la comparación de archivos por contenido y estilo en varios formatos de documentos."
words:
  for: "por"

actions:
  main: "Descarga gratuita de NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Comparison"
  alt: "Licencias"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/net/"
  title: "¿Estás listo para empezar?"
  description: "Pruebe GroupDocs.Comparison funciones de forma gratuita o solicite una licencia"

release:
  title: "Publicada la versión {0}"
  notes: "Vea qué hay de nuevo"
  downloads: "Descargas"

code:
  title: "Compara DOCX archivos en C#"
  more: "Más ejemplos"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET"
  install: "dotnet add package GroupDocs.Comparison"
  content: |
    ```csharp {style=abap}   
    // Especifique el documento fuente
    using (Comparer comparer = new Comparer("source.docx"))
    {
        // Agregar uno o más documentos de destino
        comparer.Add("target.docx");

        // Especificar las opciones de comparación
        CompareOptions options = new CompareOptions() 
        {ShowRevisions = false};

        // Comparar y guardar resultado
        comparer.Compare("result.docx", options);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison de un vistazo"
  description: "API para comparar las diferencias entre documentos en .NET aplicaciones"
  features:
    # feature loop
    - title: "Comparación de archivos en C#"
      content: "Detecte las diferencias entre los archivos de origen y destino para ver los cambios a nivel de párrafos, palabras y caracteres. Identifique los cambios de estilo y formato, como negrita, cursiva, subrayados, tachados, tipos de fuente, etc."

    # feature loop
    - title: "Se admiten los formatos de archivos y documentos más populares"
      content: "La API GroupDocs.Comparison permite una comparación eficiente de documentos en una amplia gama de formatos, incluidos PDF, HTML, correos electrónicos, Microsoft Office documentos (Word, Excel, PowerPoint, OneNote, Visio), varios tipos de imágenes (JPEG, PNG, GIF, BMP), archivos de texto y más."

    # feature loop
    - title: "Aplica o rechaza cambios fácilmente"
      content: "Cada diferencia identificada en los documentos comparados mediante la API GroupDocs.Comparison se puede aplicar o rechazar de forma selectiva, lo que permite la personalización antes de exportarla al documento final."

    # feature loop
    - title: "Informe resumido de comparación"
      content: "Genere un informe resumido de las diferencias, detallando todos los cambios encontrados en los documentos comparados, y guárdelo como referencia."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independencia de la plataforma"
  description: "GroupDocs.Comparison for .NET es compatible con los siguientes sistemas operativos, marcos y gestores de paquetes"
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
  title: "Formatos de archivo compatibles"
  description: |
    GroupDocs.Comparison for .NET admite operaciones con los siguientes [formatos de archivo](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
      content: "Analice e identifique las diferencias entre dos documentos."

    # feature loop
    - icon: "note-stack"
      title: "Comparar varios documentos"
      content: "Analice e identifique simultáneamente las diferencias entre varios documentos."

    # feature loop
    - icon: "stacks"
      title: "Formatos compatibles"
      content: "Compatible con más de 50 formatos de documentos ampliamente utilizados de varias categorías, lo que garantiza una amplia aplicabilidad."

    # feature loop
    - icon: "rule"
      title: "Aceptar o rechazar los cambios"
      content: "Visualización clara de los cambios detectados, con opciones para aceptar o rechazar estas modificaciones."

    # feature loop
    - icon: "preview"
      title: "Generar vistas previas"
      content: "Posibilidad de guardar los resultados de la comparación como vistas previas de imágenes para consultarlos y compartirlos fácilmente."

    # feature loop
    - icon: "two-pager"
      title: "Comparación de contenido"
      content: "Realice comparaciones minuciosas del texto en varios niveles (línea por línea, párrafo, palabra y carácter) resaltando las diferencias para una mayor claridad."

    # feature loop
    - icon: "format_color_text"
      title: "Comparación de estilos y formatos"
      content: "Detecta y resalta las alteraciones en el formato y el estilo de los documentos, lo que garantiza una revisión exhaustiva."

    # feature loop
    - icon: "folder-managed"
      title: "Configuración de metadatos flexible"
      content: "Conserva los metadatos de los archivos de origen o destino, o personalízalos según las preferencias del usuario."

    # feature loop
    - icon: "lock"
      title: "Protección mediante contraseña"
      content: "Analice los documentos protegidos con contraseña y proteja el documento de salida con el cifrado de contraseña para mayor seguridad."

    # feature loop
    - icon: "select"
      title: "Comparación selectiva de páginas"
      content: "Cargue y compare secciones o páginas específicas de un documento para un análisis específico."

    # feature loop
    - icon: "speaker-notes"
      title: "Mostrar comentarios"
      content: "Elija mostrar u ocultar los comentarios al cargar el documento fuente, lo que ofrece un mayor control sobre el proceso de comparación."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Ejemplos de código"
  description: "Algunos casos de uso de operaciones típicas de GroupDocs.Comparison for .NET"
  items:
    # code sample loop
    - title: "Comparación de documentos protegidos con contraseña."
      content: |
        Para comparar documentos que están [protegidos con contraseña](https://docs.groupdocs.com/comparison/net/load-password-protected-documents/), debe especificarlo y luego cargar los documentos:
        {{< landing/code title="Cómo comparar documentos protegidos con contraseña.">}}
        ```csharp {style=abap}
        // Cargue el documento fuente y especifique su contraseña
        using(Comparer comparer = new Comparer("source.docx", new LoadOptions() {Password = "1234"}))  
        {
            // Cargue el documento de destino y especifique su contraseña
            comparer.Add("target.docx", new LoadOptions() {Password = "5678"});

            // Guardar el resultado de la comparación en un archivo especificado
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Comparación de varios PDF documentos."
      content: |
        GroupDocs.Comparison permite [comparar más de dos documentos](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/). La operación es casi la misma que cuando se comparan dos archivos. Solo tiene que añadir más archivos de destino a la clase `comparer`.
        {{< landing/code title="Cómo comparar tres o más documentos.">}}
        ```csharp {style=abap}   
        // Cargar el documento fuente
        using(Comparer comparer = new Comparer("source.docx") 
        {
            // Especifique el segundo archivo para la comparación
            comparer.Add("target2.docx");
            
            // Especifique el tercer archivo para la comparación
            comparer.Add("target3.docx");
            
            // Guardar el resultado de la comparación en un archivo especificado
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---
