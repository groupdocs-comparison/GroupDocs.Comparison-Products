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
head_title: "API de comparación de documentos C# .NET | Comparar y fusionar PDF Word Excel Web y texto"
head_description: "API de comparación de documentos C# .NET. Compare y combine PDF Word DOC DOCX, hoja de cálculo de Excel, PPT, PPTX, HTML, EMLX MSG, VSDX, DXF DWG y formatos de archivos de imagen."

############################# Header ############################
title: "API .NET para comparar archivos"
description: "Desarrolle aplicaciones utilizando la API de comparación de documentos .NET para verificar y comparar archivos en busca de diferencias en contenido y estilo."
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
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
        product: "GroupDocs.Comparison"
        platform: ".NET"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "Descripción general"

            # button loop
            - link: "#features"
              text: "Características"

            # button loop
            - link: "#support"
              text: "Apoyo"

            # button loop
            - link: "https://products.groupdocs.app/comparison"
              text: "Demo en vivo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "Precios"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    example_image: "/comparison/comparison-example.webp"
    content: |
      
    more_overview:
      # more_overview_loop
      - title: "¿Qué es GroupDocs.Comparison for .NET"
        content: "GroupDocs.Comparison for .NET API es una solución rápida y confiable lista para usar al crear aplicaciones para buscar y resaltar diferencias entre documentos del mismo o diferente formato en C#, ASP.NET u otras tecnologías relacionadas con la plataforma de software .NET."

      # more_overview_loop
      - title: "Formatos admitidos"
        content: "La biblioteca GroupDocs.Comparison admite la detección de diferencias tanto en el contenido como en el estilo del texto entre formatos populares de imágenes y documentos, como PDF, HTML, correo electrónico Outlook, documentos de Microsoft Office Word, hojas de cálculo de Excel, presentaciones de PowerPoint, Onenote, diagramas de Visio, textos, png. , imágenes gif y bmp, así como cientos de otros formatos."
        
      # more_overview_loop
      - title: "Capacidades de comparación"
        content: "La comparación se puede realizar para detectar cambios en el contenido de palabras, párrafos, tablas o gráficos y sus estilos, y le proporcionará un documento de comparación que enumera un resumen de las diferencias, su número y tipo de pertenencia. GroupDocs.Comparison for .NET puede extraer fácilmente información básica sobre el documento fuente, comparar y guardar documentos simples, cifrados y protegidos con contraseña de varios formatos a través de un archivo o flujo de datos."
        
      # more_overview_loop
      - title: "Documentación y ejemplos"
        content: "Ya existe mucha documentación sobre el uso de la biblioteca de comparación en diferentes plataformas con ejemplos de código, por lo que no tiene que pensar mucho en cómo trabajar con GroupDocs.Comparison para la API .NET en su aplicación."
        
      # more_overview_loop
      - title: "Compatibilidad"
        content: "Puede utilizar GroupDocs.Comparison for .NET para crear aplicaciones en cualquier entorno de desarrollo orientado a la plataforma .NET. Es compatible con todos los lenguajes basados ​​en .NET y admite sistemas operativos populares (Windows, Linux, MacOS) en los que puede instalar marcos Mono o .NET (incluido .NET Core)."
    examples:
      enable: true
      
    more_feature:
      # more_feature_loop
      - title: "Compare documentos fácilmente utilizando la API .NET"
        content: |
          La API GroupDocs.Comparison for .NET le proporciona una manera fácil y eficiente de comparar sus archivos. A continuación se muestra un ejemplo que muestra cómo comparar dos documentos DOCX usando C#:  

          ```cs
          // Archivos de origen y de destino que se compararán
          string source = @"source.docx";
          string target = @"target.docx";
          Comparer comparer = new Comparer();
          // Comparar dos documentos
          ICompareResult result = comparer.Compare(source, target, new ComparisonSettings());
          ```
      # more_feature_loop
      - title: "Elija el nivel de detalle para comparar"
        content: "Con GroupDocs.Comparison for .NET puede especificar hasta qué punto desea que se comparen los documentos. Puede elegir entre bajo (compare el texto palabra por palabra con una precisión para la cuadrícula de imágenes = 50), medio (compare el texto carácter por carácter con una precisión para la cuadrícula de imágenes = 100) o alto (compare el texto carácter por carácter con una precisión para la cuadrícula de imágenes = 150)."

      # more_feature_loop
      - title: "Soporte para comparación de estilos de texto"
        content: |
          GroupDocs.Comparison for .NET ofrece una función para comparar estilos de texto.  

          Mientras se comparan las palabras y los caracteres de los documentos, se pueden comparar el nombre de la fuente, el tamaño de la fuente, el color de la fuente, el estilo de la fuente (negrita, cursiva, subrayado, versalitas, hipervínculo) y el color del subrayado (si corresponde) para encontrar diferencias.  

          Al comparar párrafos, puede comparar estilos como alineación de párrafo, sangría (sangría izquierda, sangría derecha), espaciado de párrafo (espacio después, espacio antes), sangría de primera línea y espaciado entre líneas.  

          GroupDocs.Comparison for .NET también admite la comparación de otras secciones de una página, cuando corresponda, como la distancia del pie de página, la altura y orientación de la página, los márgenes (izquierdo, derecho, superior e inferior), el ancho de la línea del borde y el color del borde.  
      
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          A continuación se muestra una descripción general de GroupDocs.Comparison for .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Descripción general"
          content: |
            * Comparación de documentos
            * Comparación de archivos HTML
            * Comparación de PDF
            * Comparación de diagramas
            * Comparar el contenido del archivo
            * Comparar estilos de texto
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison for .NET admite todos los [formatos de archivos de documentos](https://docs.groupdocs.com/comparison/net/supported-document-formats/) populares, incluidos: Microsoft Office, PDF, imágenes y muchos otros. .
        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** [DOC](https://products.groupdocs.com/comparison/net/doc/), [DOCX](https://products.groupdocs.com/comparison/net/docx/), [DOCM](https://products.groupdocs.com/comparison/net/docm/), [DOT](https://products.groupdocs.com/comparison/net/dot/), [DOTX](https://products.groupdocs.com/comparison/net/dotx/), [DOTM](https://products.groupdocs.com/comparison/net/dotm/), [RTF](https://products.groupdocs.com/comparison/net/rtf/), [TXT](https://products.groupdocs.com/comparison/net/txt/)
                * **Excel:** [XLS](https://products.groupdocs.com/comparison/net/xls/), [XLSX](https://products.groupdocs.com/comparison/net/xlsx/), [XLSM](https://products.groupdocs.com/comparison/net/xlsm/), [XLSB](https://products.groupdocs.com/comparison/net/xlsb/), [XLTM](https://products.groupdocs.com/comparison/net/xltm/), [XLT](https://products.groupdocs.com/comparison/net/xlt/), [XLTM](https://products.groupdocs.com/comparison/net/xltm/), [XLTX](https://products.groupdocs.com/comparison/net/xltx/), [XLAM](https://products.groupdocs.com/comparison/net/xlam/), [SXC](https://products.groupdocs.com/comparison/net/sxc/), [SpreadsheetML](https://products.groupdocs.com/comparison/net/xml/)
                * **PowerPoint:** [PPT](https://products.groupdocs.com/comparison/net/ppt/), [PPTX](https://products.groupdocs.com/comparison/net/pptx/), [PPS](https://products.groupdocs.com/comparison/net/pps/), [PPSX](https://products.groupdocs.com/comparison/net/ppsx/), [PPSM](https://products.groupdocs.com/comparison/net/ppsm/), [POT](https://products.groupdocs.com/comparison/net/pot/), [POTM](https://products.groupdocs.com/comparison/net/potm/), [POTX](https://products.groupdocs.com/comparison/net/potx/), [PPTM](https://products.groupdocs.com/comparison/net/pptm/)
                * **Visio:** [VSD](https://products.groupdocs.com/comparison/net/vsd/), [VDX](https://products.groupdocs.com/comparison/net/vdx/), [VSS](https://products.groupdocs.com/comparison/net/vss/), [VSSX](https://products.groupdocs.com/comparison/net/vssx/), [VSX](https://products.groupdocs.com/comparison/net/vsx/), [VST](https://products.groupdocs.com/comparison/net/vst/), [VSTX](https://products.groupdocs.com/comparison/net/vstx/), [VTX](https://products.groupdocs.com/comparison/net/vtx/), [VSDX](https://products.groupdocs.com/comparison/net/vsdx/), [VDW](https://products.groupdocs.com/comparison/net/vdw/), [VSTM](https://products.groupdocs.com/comparison/net/vstm/), [VSSM](https://products.groupdocs.com/comparison/net/vssm/), [VSDM](https://products.groupdocs.com/comparison/net/vsdm/)
                * **Outlook:** [MSG](https://products.groupdocs.com/comparison/net/msg/), [EML](https://products.groupdocs.com/comparison/net/eml/), [EMLX](https://products.groupdocs.com/comparison/net/emlx/), [PST](https://products.groupdocs.com/comparison/net/pst/), [OST](https://products.groupdocs.com/comparison/net/ost/)
                * **OneNote:** [ONE](https://products.groupdocs.com/comparison/net/one/)

        right:
          enable: true
          table:
            # table loop
            - title: "Otros formatos"
              content: |
                * **Lenguajes de programación**: [CS](https://products.groupdocs.com/comparison/net/cs/), [Java](https://products.groupdocs.com/comparison/net/java/), [CPP](https://products.groupdocs.com/comparison/net/cpp/), [JS](https://products.groupdocs.com/comparison/net/js/), [PY](https://products.groupdocs.com/comparison/net/py/), [RB](https://products.groupdocs.com/comparison/net/rb/), [PL](https://products.groupdocs.com/comparison/net/pl/), [ASM](https://products.groupdocs.com/comparison/net/asm/), [GROOVY](https://products.groupdocs.com/comparison/net/groovy/), [JSON](https://products.groupdocs.com/comparison/net/json/), [PHP](https://products.groupdocs.com/comparison/net/php/), [SQL](https://products.groupdocs.com/comparison/net/sql/), [LOG](https://products.groupdocs.com/comparison/net/log/), [DIFF](https://products.groupdocs.com/comparison/net/diff/), [LESS](https://products.groupdocs.com/comparison/net/less/), [SCALA](https://products.groupdocs.com/comparison/net/scala/)
                * **OpenDocument**: [ODT](https://products.groupdocs.com/comparison/net/odt/), [OTT](https://products.groupdocs.com/comparison/net/ott/), [ODS](https://products.groupdocs.com/comparison/net/ods/), [ODP](https://products.groupdocs.com/comparison/net/odp/), [OTP](https://products.groupdocs.com/comparison/net/otp/)
                * **Portable**: [PDF](https://products.groupdocs.com/comparison/net/pdf/), [MOBI](https://products.groupdocs.com/comparison/net/mobi/)
                * **AutoCAD**: [DXF](https://products.groupdocs.com/comparison/net/dxf/), [DWG](https://products.groupdocs.com/comparison/net/dwg/)
                * **Email**: [EML](https://products.groupdocs.com/comparison/net/eml/), [EMLX](https://products.groupdocs.com/comparison/net/emlx/), [MSG](https://products.groupdocs.com/comparison/net/msg/)
                * **Images**: [JPEG](https://products.groupdocs.com/comparison/net/jpeg/), [BMP](https://products.groupdocs.com/comparison/net/bmp/), [PNG](https://products.groupdocs.com/comparison/net/png/), [GIF](https://products.groupdocs.com/comparison/net/gif/), [DCM](https://products.groupdocs.com/comparison/net/dcm/), [DICOM](https://products.groupdocs.com/comparison/net/dicom/), [DjVu](https://products.groupdocs.com/comparison/net/djvu/)
                * **Web**: [HTM](https://products.groupdocs.com/comparison/net/htm/), [HTML](https://products.groupdocs.com/comparison/net/html/), [MHTML](https://products.groupdocs.com/comparison/net/mhtml/)
                * **Text**: [TXT](https://products.groupdocs.com/comparison/net/txt/)

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Comparison for .NET admite los siguientes sistemas operativos, marcos y administradores de paquetes:
      
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
              title: "Marcos soportados"
              content: |
                * .NET Framework 2.0 o mas alto
                * Mono Framework 1.2 o mas alto
                * .NET Standard 2.0
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

############################# Features ############################
features:
    enable: true
    title: "Funciones de GroupDocs.Comparison for .NET"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "[Identificar diferencias en contenido y estilos de fuente](https://docs.groupdocs.com/comparison/net/compare-documents/)"

      # feature loop
      - icon: "fas fa-eye"
        content: "[Guarde un informe resumido de todas las diferencias encontradas después de la comparación de archivos](https://docs.groupdocs.com/comparison/net/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-bolt"
        content: "[Aplicar o rechazar cambios después de analizar las diferencias y exportar el archivo resultante](https://docs.groupdocs.com/comparison/net/accept-or-reject-detected-changes/)"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "[Compatibilidad con la funcionalidad “Seguimiento de cambios” de Microsoft Word al comparar archivos de Word](https://docs.groupdocs.com/comparison/net/show-revisions/)"

      # feature loop
      - icon: "fas fa-code"
        content: "[Detecte de forma única los cambios provenientes de cada documento que se compara](https://docs.groupdocs.com/comparison/net/get-list-of-changes/)"

      # feature loop
      - icon: "fas fa-cloud"
        content: "[Leer y enviar documentos a través de Streams](https://docs.groupdocs.com/comparison/net/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "[Licencias medidas: facturación según el uso de API](https://docs.groupdocs.com/comparison/net/licensing-and-evaluation-limitations/)"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "[Compare varios documentos de origen con un único documento de destino](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/)"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "[Compare páginas específicas de archivos de Word entre sí: acepte o rechace todos los cambios en un solo documento de Word](https://docs.groupdocs.com/comparison/net/accept-or-reject-detected-changes/)"

      # feature loop
      - icon: "fas fa-border-all"
        content: "[Fusione hasta 3 documentos de Word y compare fórmulas utilizadas en archivos de Word](https://docs.groupdocs.com/comparison/net/how-to-merge-source-code-files/)"

      # feature loop
      - icon: "fas fa-wrench"
        content: "[Obtener información sobre documentos de filePath](https://docs.groupdocs.com/comparison/net/get-file-info/)"

      # feature loop
      - icon: "fas fa-columns"
        content: "[Guardar el resultado de la comparación HTML como imágenes](https://docs.groupdocs.com/comparison/net/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-file-word"
        content: "[Opción para mostrar u ocultar contenido eliminado](https://docs.groupdocs.com/comparison/net/show-gap-lines/)"

      # feature loop
      - icon: "fas fa-envelope"
        content: "[Opción para activar o desactivar la comparación de estilos de documentos](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fas fa-print"
        content: "[Especificar cadenas para marcar elementos insertados, eliminados y con cambio de estilo en el documento de comparación](https://docs.groupdocs.com/comparison/net/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "[Especifique el separador de palabras y el color de fuente para estilizar el texto comparado](https://docs.groupdocs.com/comparison/net/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-lock"
        content: "[Calcule las coordenadas correctas de los cambios en PDF, Word, diapositivas y diagramas de PowerPoint](https://docs.groupdocs.com/comparison/net/get-changes-coordinates/)"

      # feature loop
      - icon: "fas fa-file-code"
        content: "[Comparar archivos protegidos con contraseña](https://docs.groupdocs.com/comparison/net/how-to-compare-password-protected-files/)"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "[Comparar títulos de gráficos en hojas de cálculo: generar gráficos en los archivos de celdas resultantes](https://docs.groupdocs.com/comparison/net/how-to-compare-spreadsheet-or-tables/)"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "[Tamaño automático de las formas automáticas en el archivo resultante del documento de celdas](https://docs.groupdocs.com/comparison/net/how-to-compare-spreadsheet-or-tables/)"

      # feature loop
      - icon: "fas fa-heading"
        content: "[Acceda a la página de resumen detallada para detectar cambios entre los archivos de documentos de origen y de destino](https://docs.groupdocs.com/comparison/net/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "[Compare los archivos de lenguajes de programación y scripting más populares](https://docs.groupdocs.com/comparison/net/get-supported-document-formats/)"

      # feature loop
      - icon: "fas fa-cube"
        content: "[Compare varios (más de dos) documentos PDF, Word, Excel, diagramas, correos electrónicos, texto y OneNote](https://docs.groupdocs.com/comparison/net/compare-multiple-documents-with-specific-compare-settings/)"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "[Comparar encabezado y pie de página de formatos de archivo admitidos](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "[Compara marcadores, variables y propiedades personalizadas de formatos de documentos de Word](https://docs.groupdocs.com/comparison/net/compare-bookmarks-in-word/)"

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
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---