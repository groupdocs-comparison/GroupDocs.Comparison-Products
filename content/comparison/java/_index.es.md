---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "API de comparación de documentos Java | Comparar texto y estilo de PDF Word Excel HTML"
head_description: "API de comparación de documentos Java para comparar y fusionar Word Excel PPTX OpenOffice, Web, PDF, AutoCAD y otros formatos de archivo. Compare documentos con seguimiento de cambios."

############################# Header ############################
title: "API de Java para comparar archivos"
description: "Cree aplicaciones Java para comparar eficazmente el contenido de los archivos en busca de diferencias en todos los formatos de archivos de imágenes y documentos estándar."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Descargue prueba gratis"
    link: "https://downloads.groupdocs.com/comparison/java"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Comparison for Java"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
        product: "GroupDocs.Comparison"
        platform: "Java"

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
            - link: "https://purchase.groupdocs.com/pricing/comparison/java"
              text: "Precios"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    example_image: "/comparison/comparison-example.png"
    content: |
      
    more_overview:
      # more_overview_loop
      - title: "¿Qué es GroupDocs.Comparison for Java"
        content: "GroupDocs.Comparison for Java es la API más flexible y fácil de usar para ayudarle a desarrollar aplicaciones de comparación de documentos en el entorno Java. El verificador de diferencias y la API de combinación de documentos le permiten detectar cambios y diferencias en el contenido, así como en el estilo del texto, entre formatos de documentos similares."

      # more_overview_loop
      - title: "Formatos admitidos"
        content: "La biblioteca GroupDocs.Comparison admite la detección de diferencias tanto en el contenido como en el estilo del texto entre formatos populares de imágenes y documentos, como PDF, HTML, correo electrónico Outlook, documentos de Microsoft Office Word, hojas de cálculo de Excel, presentaciones de PowerPoint, Onenote, diagramas de Visio, textos, png. , imágenes gif y bmp, así como cientos de otros formatos."
        
      # more_overview_loop
      - title: "Capacidades de comparación"
        content: "La comparación se puede realizar para detectar cambios en el contenido de palabras, párrafos, tablas o gráficos y sus estilos, y le proporcionará un documento de comparación que enumera un resumen de las diferencias, su número y tipo de pertenencia. GroupDocs.Comparison for Java puede extraer fácilmente información básica sobre el documento fuente, comparar y guardar documentos simples, cifrados y protegidos con contraseña de varios formatos a través de un archivo o flujo de datos."
        
      # more_overview_loop
      - title: "Documentación y ejemplos"
        content: "Ya existe mucha documentación sobre el uso de la biblioteca de comparación en diferentes plataformas con ejemplos de código, por lo que no tiene que pensar mucho en cómo trabajar con GroupDocs.Comparison para la API Java en su aplicación."
        
      # more_overview_loop
      - title: "Compatibilidad"
        content: "GroupDocs.Comparison for Java no requiere la instalación de ningún software externo en el sistema. Es compatible con todas las versiones de Java y admite sistemas operativos populares (Windows, Linux, MacOS) capaces de ejecutar el entorno de ejecución Java."
    examples:
      enable: true
      
    more_feature:
      # more_feature_loop
      - title: "Compare documentos fácilmente usando la API de Java"
        content: |
          A través de la API GroupDocs.Comparison for Java puede comparar fácilmente documentos de formatos admitidos para encontrar diferencias entre ellos. El siguiente ejemplo muestra cómo comparar dos documentos de Microsoft Word usando Java:
          
          ```java
          try (Comparer comparer = new Comparer("D:\\source.pdf")) {
              comparer.add("D:\\target.pdf");
              comparer.compare("D:\\result.pdf");
          }
          ```
      # more_feature_loop
      - title: "Especificar nivel de detalle de comparación"
        content: "GroupDocs.Comparison for Java le permite comparar documentos en tres niveles de profundidad. Puede configurar la intensidad de la comparación para que sea baja (compare el texto palabra por palabra con una precisión para la cuadrícula de imágenes = 50), media (compare el texto carácter por carácter con una precisión para la cuadrícula de imágenes = 100) o alta (compare el texto carácter por carácter con precisión para las imágenes). cuadrícula = 150)."

      # more_feature_loop
      - title: "Comparar estilo de texto"
        content: "Junto con el contenido del documento, la API GroupDocs.Comparison for Java también permite comparar el estilo del texto.

        El nombre de la fuente, el tamaño, el color, el estilo (negrita, cursiva, subrayado, versalitas e hipervínculos) y, si corresponde, el color inferior, también se pueden comparar para comprobar la diferencia entre los documentos comparados, mientras se comparan las palabras y los caracteres.  

        Para comparar párrafos, también se pueden comparar la alineación, la sangría (sangría izquierda, sangría derecha), el espaciado (espacio después, espacio antes), la sangría de la primera línea y el interlineado.  

        De manera similar, cuando corresponda, también se pueden comparar otras secciones de una página a través de la API GroupDocs.Comparison for Java. Las secciones incluyen la distancia del pie de página, los márgenes de la página (izquierdo, derecho, superior e inferior), la altura de la página, la orientación de la página, el color del borde y el ancho de la línea."
      
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          A continuación se muestra una descripción general de GroupDocs.Comparison for Java:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Descripción general"
          content: |
            * Comparar contenidos y estilos
            * Obtener resumen comparativo
            * Aceptar/Rechazar cambios en Word
            * Fusionar y comparar 3 archivos de Word
            * Soporte para transmisiones
            * Detección de tipo de archivo a través de Stream
            * Comparar archivos protegidos
            * Comparar archivos cifrados
            * Guardar comparación como imagen
            * Comparar página específica en Word
            * Comparar marca de agua en PDF
            * Aplicar/Descartar cambios
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison for Java admite todos los [formatos de archivos de documentos](https://docs.groupdocs.com/comparison/java/supported-document-formats/) populares, incluidos: Microsoft Office, imágenes, diagramas y muchos otros. .
        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** [DOC](https://products.groupdocs.com/comparison/java/doc/), [DOCX](https://products.groupdocs.com/comparison/java/docx/), [DOCM](https://products.groupdocs.com/comparison/java/docm/), [DOT](https://products.groupdocs.com/comparison/java/dot/), [DOTX](https://products.groupdocs.com/comparison/java/dotx/), [DOTM](https://products.groupdocs.com/comparison/java/dotm/), [RTF](https://products.groupdocs.com/comparison/java/rtf/), [TXT](https://products.groupdocs.com/comparison/java/txt/)
                * **Excel:** [XLS](https://products.groupdocs.com/comparison/java/xls/), [XLSX](https://products.groupdocs.com/comparison/java/xlsx/), [XLSM](https://products.groupdocs.com/comparison/java/xlsm/), [XLSB](https://products.groupdocs.com/comparison/java/xlsb/), [XLTM](https://products.groupdocs.com/comparison/java/xltm/), [XLT](https://products.groupdocs.com/comparison/java/xlt/), [XLTM](https://products.groupdocs.com/comparison/java/xltm/), [XLTX](https://products.groupdocs.com/comparison/java/xltx/), [XLAM](https://products.groupdocs.com/comparison/java/xlam/), [SXC](https://products.groupdocs.com/comparison/java/sxc/), [SpreadsheetML](https://products.groupdocs.com/comparison/java/xml/)
                * **PowerPoint:** [PPT](https://products.groupdocs.com/comparison/java/ppt/), [PPTX](https://products.groupdocs.com/comparison/java/pptx/), [PPS](https://products.groupdocs.com/comparison/java/pps/), [PPSX](https://products.groupdocs.com/comparison/java/ppsx/), [PPSM](https://products.groupdocs.com/comparison/java/ppsm/), [POT](https://products.groupdocs.com/comparison/java/pot/), [POTM](https://products.groupdocs.com/comparison/java/potm/), [POTX](https://products.groupdocs.com/comparison/java/potx/), [PPTM](https://products.groupdocs.com/comparison/java/pptm/)
                * **Visio:** [VSD](https://products.groupdocs.com/comparison/java/vsd/), [VDX](https://products.groupdocs.com/comparison/java/vdx/), [VSS](https://products.groupdocs.com/comparison/java/vss/), [VSSX](https://products.groupdocs.com/comparison/java/vssx/), [VSX](https://products.groupdocs.com/comparison/java/vsx/), [VST](https://products.groupdocs.com/comparison/java/vst/), [VSTX](https://products.groupdocs.com/comparison/java/vstx/), [VTX](https://products.groupdocs.com/comparison/java/vtx/), [VSDX](https://products.groupdocs.com/comparison/java/vsdx/), [VDW](https://products.groupdocs.com/comparison/java/vdw/), [VSTM](https://products.groupdocs.com/comparison/java/vstm/), [VSSM](https://products.groupdocs.com/comparison/java/vssm/), [VSDM](https://products.groupdocs.com/comparison/java/vsdm/)
                * **Outlook:** [MSG](https://products.groupdocs.com/comparison/java/msg/), [EML](https://products.groupdocs.com/comparison/java/eml/), [EMLX](https://products.groupdocs.com/comparison/java/emlx/), [PST](https://products.groupdocs.com/comparison/java/pst/), [OST](https://products.groupdocs.com/comparison/java/ost/)
                * **OneNote:** [ONE](https://products.groupdocs.com/comparison/java/one/)

        right:
          enable: true
          table:
            # table loop
            - title: "Otros formatos"
              content: |
                * **Lenguajes de programación**: [CS](https://products.groupdocs.com/comparison/java/cs/), [Java](https://products.groupdocs.com/comparison/java/java/), [CPP](https://products.groupdocs.com/comparison/java/cpp/), [JS](https://products.groupdocs.com/comparison/java/js/), [PY](https://products.groupdocs.com/comparison/java/py/), [RB](https://products.groupdocs.com/comparison/java/rb/), [PL](https://products.groupdocs.com/comparison/java/pl/), [ASM](https://products.groupdocs.com/comparison/java/asm/), [GROOVY](https://products.groupdocs.com/comparison/java/groovy/), [JSON](https://products.groupdocs.com/comparison/java/json/), [PHP](https://products.groupdocs.com/comparison/java/php/), [SQL](https://products.groupdocs.com/comparison/java/sql/), [LOG](https://products.groupdocs.com/comparison/java/log/), [DIFF](https://products.groupdocs.com/comparison/java/diff/), [LESS](https://products.groupdocs.com/comparison/java/less/), [SCALA](https://products.groupdocs.com/comparison/java/scala/)
                * **OpenDocument**: [ODT](https://products.groupdocs.com/comparison/java/odt/), [OTT](https://products.groupdocs.com/comparison/java/ott/), [ODS](https://products.groupdocs.com/comparison/java/ods/), [ODP](https://products.groupdocs.com/comparison/java/odp/), [OTP](https://products.groupdocs.com/comparison/java/otp/)
                * **Portable**: [PDF](https://products.groupdocs.com/comparison/java/pdf/), [MOBI](https://products.groupdocs.com/comparison/java/mobi/)
                * **AutoCAD**: [DXF](https://products.groupdocs.com/comparison/java/dxf/), [DWG](https://products.groupdocs.com/comparison/java/dwg/)
                * **Email**: [EML](https://products.groupdocs.com/comparison/java/eml/), [EMLX](https://products.groupdocs.com/comparison/java/emlx/), [MSG](https://products.groupdocs.com/comparison/java/msg/)
                * **Images**: [JPEG](https://products.groupdocs.com/comparison/java/jpeg/), [BMP](https://products.groupdocs.com/comparison/java/bmp/), [PNG](https://products.groupdocs.com/comparison/java/png/), [GIF](https://products.groupdocs.com/comparison/java/gif/), [DCM](https://products.groupdocs.com/comparison/java/dcm/), [DICOM](https://products.groupdocs.com/comparison/java/dicom/), [DjVu](https://products.groupdocs.com/comparison/java/djvu/)
                * **Web**: [HTM](https://products.groupdocs.com/comparison/java/htm/), [HTML](https://products.groupdocs.com/comparison/java/html/), [MHTML](https://products.groupdocs.com/comparison/java/mhtml/)
                * **Text**: [TXT](https://products.groupdocs.com/comparison/java/txt/)

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Comparison for Java admite los siguientes sistemas operativos, marcos y administradores de paquetes:
      
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Sistemas operativos"
              content: |
                * Microsoft Windows Desktop
                * Microsoft Windows Server
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "Marcos soportados"
              content: |
                * Java 7 (1.7) o mas alto

        right:
          enable: true
          table:
            
            # table loop
            - icon: "fas fa-cogs"
              title: "Entornos de desarrollo"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse
            # table loop
            - icon: "fas fa-tools"
              title: "Construir herramienta de automatización"
              content: |
                * Maven

############################# Features ############################
features:
    enable: true
    title: "Funciones de GroupDocs.Comparison for Java"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "[Compare e identifique cambios tanto en el contenido como en el estilo del texto](https://docs.groupdocs.com/comparison/java/compare-documents/)"

      # feature loop
      - icon: "fas fa-eye"
        content: "[Guardar lista de comparación resumida sobre documentos comparados](https://docs.groupdocs.com/comparison/java/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-bolt"
        content: "[Comparar páginas específicas de documentos de Word](https://docs.groupdocs.com/comparison/java/accept-or-reject-detected-changes/)"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "[Combine hasta 3 archivos de Microsoft Word para compararlos con soporte para “Seguimiento de cambios”](https://docs.groupdocs.com/comparison/java/compare-multiple-documents-with-specific-compare-settings/)"

      # feature loop
      - icon: "fas fa-code"
        content: "[Detecte fácilmente qué cambios provienen de qué documento durante la comparación](https://docs.groupdocs.com/comparison/java/get-list-of-changes/)"

      # feature loop
      - icon: "fas fa-cloud"
        content: "[Soporte para leer documentos de origen y enviar documentos resultantes a través de Streams](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "[Detectar el tipo de formato de archivo mientras se obtiene de la secuencia](https://docs.groupdocs.com/comparison/java/get-file-info/)"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "[Comparar documentos protegidos por contraseña](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/)"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "[Guardar el resultado de la comparación como imagen](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-border-all"
        content: "[Compara diferentes formatos de archivo como imagen](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-wrench"
        content: "[Comparar marcas de agua en documentos PDF](https://docs.groupdocs.com/comparison/java/how-to-spot-photos-differences-in-java-or-kotlin/)"

      # feature loop
      - icon: "fas fa-columns"
        content: "[Compare documentos de un archivo o secuencia y envíe el documento resultante mediante secuencia o archivo](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-file-word"
        content: "[Aceptar o descartar cambios después de comparar archivos Word, PDF o Excel](https://docs.groupdocs.com/comparison/java/accept-or-reject-detected-changes/)"

      # feature loop
      - icon: "fas fa-envelope"
        content: "[Comparar documentos cifrados mediante archivo o secuencia](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-print"
        content: "[Opción de licencia medida para operaciones de comparación](https://docs.groupdocs.com/comparison/java/evaluation-limitations-and-licensing-of-groupdocs-comparison/)"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "[Resalte texto para cambios marcados al comparar documentos PDF, Word, Excel, PowerPoint y Note](https://docs.groupdocs.com/comparison/java/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-lock"
        content: "[Calcule las coordenadas correctas de los cambios en PDF, diapositivas y diagramas de PowerPoint](https://docs.groupdocs.com/comparison/java/get-changes-coordinates/)"

      # feature loop
      - icon: "fas fa-file-code"
        content: "[Compare varios (más de dos) documentos PDF, Excel, OneNote, diagramas, correos electrónicos y de texto](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/)"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "[Comparar encabezado y pie de página de formatos de archivo admitidos](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "[Compare documentos y guarde páginas de documentos de diferentes formatos como imágenes](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"


############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison ofrece API de visualización de documentos para otros entornos de desarrollo populares"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
          product: "GroupDocs.Comparison"
          platform: ".NET"
          link: "/comparison/net/"

############################# Back to top ###############################
back_to_top:
  enable: true
---