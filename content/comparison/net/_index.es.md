---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "API de comparación de documentos de C# .NET | Comparar y combinar PDF Word Excel Web y texto"
head_description: "API de comparación de documentos C# .NET. Compare y fusione PDF Word DOC DOCX, hoja de cálculo de Excel, PPT, PPTX, HTML, EMLX MSG, VSDX, DXF DWG y formatos de archivo de imagen."

############################# Header ############################
title: ".NET API para comparar y fusionar documentos"
description: "Desarrolle aplicaciones .NET utilizando la API de comparación de documentos para comparar y verificar las diferencias en contenido y estilo entre documentos del mismo formato."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Descargue prueba gratis"
    link: "https://downloads.groupdocs.com/comparison/net"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Comparison for .NET"
        image: "/border/groupdocs-comparison-net.svg"
        product: "GroupDocs.Comparison"
        platform: ".NET"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "Visión de conjunto"

            # button loop
            - link: "#features"
              text: "Características"

            # button loop
            - link: "#support"
              text: "Support"

            # button loop
            - link: "https://products.groupdocs.app/comparison"
              text: "Live Demo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "Precios"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Visión de conjunto ############################
overview:
    enable: true
    content: |
      GroupDocs.Comparison for .NET API is a fast and reliable solution to build difference checker applications among documents of same format in C#, ASP.NET or other .NET related technologies. The .NET compare library supports checking differences in both, content as well as the text style of popular image and document formats such as PDF, HTML, Outlook email, oficina de Microsoft Word documents, Excel spreadsheets, PowerPoint presentations, OneNote, Visio diagrams, text and images. The comparison can be done to detect content changes for words, paragraphs and characters while providing a comparison document that lists summary of differences. GroupDocs.Comparison for .NET API can easily extract basic information of source document. It can also fetch, compare and save simple, password enables, as well as encrypted documents via file or stream.  
        
      GroupDocs.Comparison for .NET se puede utilizar para desarrollar aplicaciones en cualquier entorno de desarrollo que se dirija a la plataforma .NET. Es compatible con todos los lenguajes basados en .NET y es compatible con los sistemas operativos más populares (Windows, Linux, MacOS) donde se pueden instalar marcos Mono o .NET (incluido .NET Core).

    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          A continuación se muestra una descripción general de GroupDocs.Comparison para .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Visión de conjunto"
          content: |
            * Comparación de documentos
            * Comparación de archivos HTML
            * Comparación de PDF
            * Comparación de diagramas
            * Comparar contenido de archivo
            * Comparar estilo de textos
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison para .NET es compatible con todos los [formatos de archivo de documentos] populares (https://docs.groupdocs.com/comparison/net/supported-document-formats/), incluidos: oficina de Microsoft, PDF, imágenes y muchos otros.

        left:
          enable: true
          table:
            # table loop
            - title: "oficina de Microsoft"
              content: |
                * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
                * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX, XLAM, SXC, SpreadsheetML
                * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM
                * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
                * **Outlook:** MSG, EML, EMLX, PST, OST
                * **OneNote:** ONE

        right:
          enable: true
          table:
            # table loop
            - title: "Otros formatos"
              content: |
                * **Lenguajes de programación**: CS, Java, CPP, JS, PY, RB, PL, ASM, GROOVY, JSON, ActionScript, PHP, SQL, LOG, DIFF, LESS, SCALA
                * **Documento abierto**: ODT, OTT, ODS, ODP, OTP
                * **Portátil**: PDF, MOBI
                * **AutoCAD**: DXF, DWG
                * **Correo electrónico**: EML, EMLX, MSG
                * **Imágenes**: JPEG, BMP, PNG, GIF, DCM, DICOM, DjVu
                * **Web**: HTM, HTML, MHTML
                * **Texto**: TXT

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Comparison para .NET es compatible con los siguientes sistemas operativos, marcos y administrador de paquetes:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Sistemas operativos"
              content: |
                * Windows Desktop
                * Windows Server
                * Windows Azure
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "Marcos compatibles"
              content: |
                * .NET Framework 2.0 o superior
                * Mono Framework 1.2 o superior
                * .NET estándar 2.0
                * .NET Core 2.0

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Gerente de empaquetación"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Entornos de desarrollo"
              content: |
                * Microsoft Visual Studio
                * Xamarin.Android
                * Xamarin.IOS
                * Xamarin.Mac
                * MonoDevelop

############################# Características ############################
features:
    enable: true
    title: "GroupDocs. Comparación para características de .NET"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Identificar las diferencias en el contenido y los estilos de fuente"

      # feature loop
      - icon: "fas fa-eye"
        content: "Guarde un informe resumido de todas las diferencias encontradas después de la comparación de archivos"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Aplicar o rechazar cambios después de analizar las diferencias y exportar el archivo resultante"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Compatibilidad con la funcionalidad de \"Control de cambios\" de Microsoft Word al comparar archivos de Word"

      # feature loop
      - icon: "fas fa-code"
        content: "Únicamente detectar cambios provenientes de cada documento que se compara"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Leer y enviar documentos a través de flujos"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Licencias medidas: facturación según el uso de la API"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Comparar varios documentos de origen con un único documento de destino"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Compare páginas específicas de archivos de Word entre sí: acepte o rechace todos los cambios en un solo documento de Word"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Combinar hasta 3 documentos de Word y comparar fórmulas utilizadas en archivos de Word"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Obtener información sobre documentos de filePath"

      # feature loop
      - icon: "fas fa-columns"
        content: "Guardar el resultado de la comparación HTML como imágenes"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Opción para mostrar u ocultar contenido eliminado"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Opción para activar o desactivar la comparación de estilos de documentos"

      # feature loop
      - icon: "fas fa-print"
        content: "Especificar cadenas para marcar elementos insertados, eliminados y de cambio de estilo en el documento de comparación"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Especifique el separador de palabras y el color de fuente para estilizar el texto comparado"

      # feature loop
      - icon: "fas fa-lock"
        content: "Calcule las coordenadas correctas de los cambios en PDF, Word, diapositivas y diagramas de PowerPoint"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Comparar archivos protegidos con contraseña"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Comparar títulos de gráficos en hojas de cálculo: generar gráficos en los archivos de celdas resultantes"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Autodimensionar las formas automáticas en el archivo resultante del documento de celdas"

      # feature loop
      - icon: "fas fa-heading"
        content: "Acceda a la página de resumen detallado para detectar cambios entre los archivos de documentos de origen y de destino"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Compare los archivos de lenguaje de secuencias de comandos y programación más populares"

      # feature loop
      - icon: "fas fa-cube"
        content: "Compare múltiples (más de dos) documentos PDF, Word, Excel, diagramas, correo electrónico, texto y OneNote"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Comparar encabezado y pie de página de formatos de archivo admitidos"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Compare marcadores, variables y propiedades personalizadas de formatos de documentos de Word"

    more_feature:
      # more_feature_loop
      - title: "Compare documentos fácilmente usando la API de .NET"
        content: |
          GroupDocs.Comparison for .NET API le brinda una manera fácil y eficiente de comparar sus archivos. El siguiente es un ejemplo que muestra cómo comparar dos documentos DOCX usando C#:

          ```cs
          string source = @"source.docx";
          string target = @"target.docx";
          Comparer comparer = new Comparer();

          ICompareResult result = comparer.Compare(source, target, new ComparisonSettings());
          ```
      # more_feature_loop
      - title: "Elija el nivel de detalle para la comparación"
        content: "Con GroupDocs.Comparison for .NET puede especificar hasta qué punto desea que se comparen los documentos. Puede elegir entre, bajo (comparar texto palabra por palabra con precisión para cuadrícula de imágenes = 50), medio (comparar texto carácter por carácter con precisión para cuadrícula de imágenes = 100) o alto (comparar texto carácter por carácter con precisión para cuadrícula de imágenes = 150)."

      # more_feature_loop
      - title: "Compatibilidad con la comparación de estilos de texto"
        content: |
          GroupDocs.Comparison para .NET ofrece una función para comparar el estilo de texto.

          Mientras se comparan las palabras y los caracteres de los documentos, se pueden comparar el nombre de la fuente, el tamaño de la fuente, el color de la fuente, el estilo de la fuente (negrita, cursiva, subrayado, versalitas, hipervínculo) y el color del subrayado (si corresponde) para encontrar diferencias.

          Al comparar párrafos, puede comparar estilos como alineación de párrafo, sangría (sangría izquierda, sangría derecha), espaciado de párrafo (espacio después, espacio antes), sangría de primera línea y espacio entre líneas.

          GroupDocs.Comparison para .NET también admite la comparación de otras secciones de una página, cuando corresponda, como la distancia del pie de página, la altura y la orientación de la página, los márgenes (izquierdo, derecho, superior e inferior), el ancho de la línea del borde y el color del borde.

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison ofrece API de visualización de documentos para otros entornos de desarrollo populares"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for Java"
          image: "/border/groupdocs-comparison-java.svg"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---