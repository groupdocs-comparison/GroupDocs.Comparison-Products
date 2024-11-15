
---
############################# Static ############################
layout: "landing"
date: 2024-11-14T22:58:46
draft: false

lang: es
product: "Comparison"
product_tag: "comparison"
platform: "Python via .NET"
platform_tag: "python-net"

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
head_title: "Python Herramienta de comparación de documentos | Análisis de documentos"
head_description: "Descubra el poder de la herramienta de comparación de documentos Python para un análisis exhaustivo de documentos. Se integra sin esfuerzo con Python para un seguimiento completo de las modificaciones."

############################# Header ############################
title: "Comparar documentos con Python: resaltar las diferencias"
description: "Utilice la API GroupDocs.Comparison para crear aplicaciones nativas en Python con funcionalidades de comparación personalizables. Examine archivos, su contenido y variaciones de estilo en todos los formatos de documentos."
words:
  for: "por"

actions:
  main: "Obtenga su descarga gratuita de PyPi ahora"
  main_link: "https://pypi.org/project/groupdocs-comparison-net/"
  alt: "Licencias"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/python-net/"
  title: "¿Estás listo para empezar?"
  description: "Pruebe GroupDocs.Comparison funciones de forma gratuita o solicite una licencia"

release:
  title: "Publicada la versión {0}"
  notes: "Vea qué hay de nuevo"
  downloads: "Descargas"

code:
  title: "Comparar imágenes BMP usando Python"
  more: "Más ejemplos"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET/"
  install: "pip install groupdocs-comparison-net"
  content: |
    ```python {style=abap}
    def run():

        # Especifique el documento fuente
        with groupdocs.comparison.Comparer("in.bmp") as comparer:

            # Agregar uno o más documentos de destino
            comparer.add("target.bmp")

            # Especificar las opciones de comparación
            options = new groupdocs.comparison.CompareOptions()
            options.setGenerateSummaryPage(false)

            # Comparar y guardar resultado
            comparer.compare("result.bmp", options)
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison de un vistazo"
  description: "Una API diseñada para comparar tipos de documentos ampliamente utilizados, como PDF, archivos de Microsoft Office, HTML, correos electrónicos o imágenes dentro de aplicaciones Python."
  features:
    # feature loop
    - title: "Informes de resultados completos"
      content: "GroupDocs.Comparison detecta alteraciones en el contenido del documento (caracteres, palabras, párrafos, tablas, gráficos), así como cambios de estilo en el documento. Los usuarios reciben un informe detallado que destaca la naturaleza y el recuento de los cambios."

    # feature loop
    - title: "Amplia gama de formatos de archivos y documentos"
      content: "La API GroupDocs.Comparison le permite comparar documentos en formatos como PDF, HTML, correo electrónico, Microsoft Office Word, libros de Excel, archivos de PowerPoint, notas de OneNote, diagramas de Visio, documentos de texto, imágenes JPEG, PNG, GIF, BMP. entre muchos otros."

    # feature loop
    - title: "Documentación exhaustiva y ejemplos de código"
      content: "Se encuentran disponibles documentación detallada y códigos de muestra para la biblioteca de comparación en varias plataformas, lo que simplifica la integración de la API GroupDocs.Comparison en sus aplicaciones Python."

    # feature loop
    - title: "Seleccionar y combinar cambios en un solo documento"
      content: "Si posee varias versiones de un documento, puede compilar selectivamente los cambios en un único archivo nuevo utilizando la biblioteca GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independencia de la plataforma"
  description: "GroupDocs.Comparison for Python via .NET es compatible con los siguientes sistemas operativos, marcos y administradores de paquetes."
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
    GroupDocs.Comparison for Python via .NET puede funcionar con los siguientes [formatos de archivo](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
  title: "Capacidades de GroupDocs.Comparison for Python via .NET"
  description: "Compare sin problemas archivos PDF, documentos de Office, imágenes y una amplia variedad de otros formatos."

  items:
    # feature loop
    - icon: "compare"
      title: "Comparación intuitiva de documentos"
      content: "Examinar y resaltar las diferencias entre dos documentos."

    # feature loop
    - icon: "note-stack"
      title: "Comparación de múltiples documentos"
      content: "Inspeccione varios documentos en busca de diferencias al mismo tiempo."

    # feature loop
    - icon: "stacks"
      title: "Amplio soporte de formato"
      content: "Compatible con más de 50 formatos de documentos de uso común en varias categorías."

    # feature loop
    - icon: "rule"
      title: "Aceptar o rechazar cambios"
      content: "Visualice los cambios con claridad, ofreciendo opciones para aceptar o rechazar las ediciones."

    # feature loop
    - icon: "preview"
      title: "Generar vistas previas visuales"
      content: "Cree vistas previas de los resultados de la comparación en formatos de imagen."

    # feature loop
    - icon: "two-pager"
      title: "Comparación de contenido basada en texto"
      content: "Realice comparaciones línea por línea, párrafo, palabra o carácter para resaltar los cambios."

    # feature loop
    - icon: "format_color_text"
      title: "Detección de cambios de formato"
      content: "Identificar alteraciones en los estilos y formatos de los documentos."

    # feature loop
    - icon: "folder-managed"
      title: "Manejo de metadatos personalizable"
      content: "Conserve los metadatos de los archivos de origen o de destino, o permita a los usuarios definir nuevos metadatos."

    # feature loop
    - icon: "lock"
      title: "Manejar archivos protegidos con contraseña"
      content: "Trabaje con documentos cifrados o cree documentos seguros protegidos con una contraseña."

    # feature loop
    - icon: "select"
      title: "Comparaciones de páginas enfocadas"
      content: "Seleccione y compare secciones particulares o páginas individuales de un documento."

    # feature loop
    - icon: "speaker-notes"
      title: "Administrar la visibilidad de los comentarios"
      content: "Decida revelar u ocultar comentarios al examinar el documento fuente."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Ejemplos de código"
  description: "Descubra escenarios comunes para utilizar las funcionalidades de GroupDocs.Comparison for Python via .NET."
  items:
    # code sample loop
    - title: "Comparación de documentos con protección por contraseña"
      content: |
        Para comparar documentos [protegidos con contraseña](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/), debe especificar la contraseña al cargar los documentos:
        {{< landing/code title="Cómo comparar documentos protegidos con contraseña.">}}
        ```python {style=abap}
        def run():

            # Cargue el documento fuente y especifique su contraseña
            with groupdocs.comparison.Comparer("source.docx", new LoadOptions("1234")) as comparer:

                # Cargue el documento de destino y especifique su contraseña
                comparer.add("target.docx", new LoadOptions("5678"));

                # Guardar el resultado de la comparación en un archivo especificado
                comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Comparación de varios PDF documentos."
      content: |
        GroupDocs.Comparison permite [comparar más de dos documentos](https://docs.groupdocs.com/comparison/python-net/compare-multiple-documents/). La operación es casi la misma que cuando se comparan dos archivos. Solo tiene que añadir más archivos de destino a la clase `comparer`.
        {{< landing/code title="Cómo comparar tres o más documentos.">}}
        ```python {style=abap}
        def run():

            # Cargar el documento fuente
            with groupdocs.comparison.Comparer(source.pdf") as comparer:

                # Especifique el segundo archivo para la comparación
                comparer.add("target2.pdf");

                # Especifique el tercer archivo para la comparación
                comparer.add("target3.pdf");

                # Guardar el resultado de la comparación en un archivo especificado
                comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---