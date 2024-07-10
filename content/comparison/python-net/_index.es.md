
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
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
head_title: "Python API de comparación de documentos | comprobador de diferencias"
head_description: "La API de comparación de documentos Python ofrece herramientas eficientes para comparar documentos. Se integra perfectamente con Python para un seguimiento instantáneo de los cambios"

############################# Header ############################
title: "Comparar documentos con Python: resaltar las diferencias"
description: "Utilice la API GroupDocs.Comparison para desarrollar aplicaciones Python nativas con funciones de comparación altamente configurables. Compare archivos, su contenido y estilos de texto entre formatos de documentos similares."
words:
  for: "por"

actions:
  main: "Descarga gratuita de PyPi"
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
  title: "Comparar imágenes BMP en Python"
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
  description: "Una API para comparar tipos de documentos populares como PDF, Microsoft Office, HTML, correos electrónicos o imágenes dentro de aplicaciones Python."
  features:
    # feature loop
    - title: "Informes de salida detallados"
      content: "GroupDocs.Comparison identifica cambios en el contenido del documento (caracteres, palabras, párrafos, tablas, gráficos), así como cambios en el estilo del documento. Proporciona a los usuarios un informe que contiene información detallada sobre las diferencias, incluido su número y tipo."

    # feature loop
    - title: "Admite formatos populares de archivos y documentos"
      content: "Con la API GroupDocs.Comparison, puede comparar de manera eficiente documentos en formatos como PDF, HTML, correo electrónico, Microsoft Office Word, hojas de cálculo de Excel, presentaciones de PowerPoint, OneNote, diagramas de Visio, archivos de texto, imágenes JPEG, PNG, GIF, BMP. y muchos otros formatos."

    # feature loop
    - title: "Documentación completa y ejemplos"
      content: "Hay disponible una amplia documentación y ejemplos de código para usar la biblioteca de comparación en diferentes plataformas, lo que facilita la integración de la API GroupDocs.Comparison en su aplicación Python."

    # feature loop
    - title: "Seleccionar y fusionar cambios en un solo archivo"
      content: "Si tiene diferentes versiones de un documento, puede seleccionar cambios específicos y compilar un nuevo documento usando la biblioteca GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independencia de la plataforma"
  description: "GroupDocs.Comparison for Python via .NET admite los siguientes sistemas operativos, marcos y administradores de paquetes"
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
    GroupDocs.Comparison for Python via .NET admite operaciones con los siguientes [formatos de archivo](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
  title: "Funciones de GroupDocs.Comparison for Python via .NET"
  description: "Compare fácilmente documentos, imágenes y otros formatos PDF y Office."

  items:
    # feature loop
    - icon: "compare"
      title: "Comparación de documentos fácil de usar"
      content: "Analizar e identificar diferencias entre dos documentos."

    # feature loop
    - icon: "note-stack"
      title: "Comparar varios documentos"
      content: "Analice e identifique diferencias dentro de múltiples documentos simultáneamente."

    # feature loop
    - icon: "stacks"
      title: "Formatos admitidos"
      content: "Admite más de 50 formatos de documentos populares de varias categorías."

    # feature loop
    - icon: "rule"
      title: "Aceptar o rechazar cambios"
      content: "Representación visual clara de los cambios identificados, con la opción de aceptar o rechazar modificaciones."

    # feature loop
    - icon: "preview"
      title: "Generar vistas previas"
      content: "Guarde los resultados de la comparación como imágenes."

    # feature loop
    - icon: "two-pager"
      title: "Comparación de contenido"
      content: "Compare el contenido del texto línea por línea, por párrafos, por palabras o por caracteres. Resalte los cambios."

    # feature loop
    - icon: "format_color_text"
      title: "Comparación de estilos"
      content: "Detectar cambios de formato y estilos."

    # feature loop
    - icon: "folder-managed"
      title: "Establecer metadatos"
      content: "Conserve los metadatos de los archivos de origen o de destino, o permita que los usuarios los especifiquen."

    # feature loop
    - icon: "lock"
      title: "Protección de contraseña"
      content: "Analice documentos cifrados o proteja el documento resultante con una contraseña."

    # feature loop
    - icon: "select"
      title: "Comparar páginas específicas"
      content: "Cargue y compare secciones o páginas específicas de un documento."

    # feature loop
    - icon: "speaker-notes"
      title: "Mostrar comentarios"
      content: "Elija ocultar o mostrar comentarios al cargar el documento fuente."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Ejemplos de código"
  description: "Explore casos de uso típicos de operaciones GroupDocs.Comparison for Python via .NET"
  items:
    # code sample loop
    - title: "Comparación de documentos protegidos con contraseña"
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