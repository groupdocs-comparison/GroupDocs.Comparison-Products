
---
############################# Static ############################
layout: "format"
date:  2024-10-01T13:42:44
draft: false
lang: es
format: Xlsx
product: "Comparison"
product_tag: "comparison"
platform: "Python via .NET"
platform_tag: "python-net"

############################# Head ############################
head_title: "Compare el contenido de la hoja de cálculo XLSX con la API Python"
head_description: "Verifique fácilmente las diferencias en las hojas de cálculo de MS Excel utilizando nuestra API Python, que genera informes detallados que resaltan todas las distinciones."

############################# Header ############################
title: "Comparación de hojas de cálculo XLSX en aplicaciones Python via .NET" 
description: "Utilice la biblioteca de procesamiento de documentos Python para detectar y resaltar cambios en archivos MS Excel XLSX dentro de las aplicaciones Python via .NET. Genere informes de forma rápida y sencilla."
subtitle: "Solución de comparación de archivos" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Descarga desde PyPi gratis"
      link: "https://releases.groupdocs.com/comparison/python-net/"
      
############################# About ############################
about:
    enable: true
    title: "Descubra los beneficios de GroupDocs.Comparison"
    link: "/comparison/python-net/"
    link_title: "Obtenga más información"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       Genere informes completos que proporcionen datos detallados sobre los cambios en varias versiones de archivos XLSX usando GroupDocs.Comparison. Con solo unas pocas líneas de código, puede integrar perfectamente la API en sus aplicaciones Python via .NET, sin necesidad de herramientas adicionales. Analice diferencias en hojas, texto, estilos o formas dentro de archivos de MS Excel y combine los cambios en un documento XLSX final. Mejore los flujos de trabajo de su negocio con nuestras poderosas soluciones.

############################# Steps ############################
steps:
    enable: true
    title: "Cómo comparar archivos XLSX en Python"
    content: |
      Utilice [GroupDocs.Comparison](https://products.groupdocs.com/comparison/python-net/) y Python via .NET para comparar documentos XLSX
      
      1. Instale GroupDocs.Comparison para Python via .NET desde [PyPi](https://pypi.org/project/groupdocs-comparison-net/)
      2. Cree una instancia del objeto Comparador y proporcione la ruta al primer archivo XLSX
      3. Agregue archivos XLSX adicionales para comparar
      4. Generar y revisar los resultados de la comparación.
   
    code:
      platform: "python-net"
      copy_title: "Copiar"
      install:
        command: "pip install groupdocs-comparison-net"
        copy_tip: "haga clic para copiar"
        copy_done: "copiado"
      links:
        #  loop
        - title: "Más ejemplos"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET/"
        #  loop
        - title: "Documentación"
          link: "https://docs.groupdocs.com/comparison/python-net/"
          
      content: |
        ```python {style=abap}
        def run():

            # Compare varios archivos para ver similitudes y diferencias.

            # Inicialice el comparador y cargue el primer archivo.
            with groupdocs.comparison.Comparer("first.xlsx") as comparer:

                # Agregue archivos adicionales para comparar.
                comparer.add('second.xlsx')
                comparer.add('third.xlsx')

                # Recupera el informe de comparación final.
                comparer.compare('report_full.xlsx')

                print("\nDocuments compared successfully.\nCheck output.")
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "¿Estás listo para empezar?"
  description: "Pruebe GroupDocs.Comparison funciones de forma gratuita o solicite una licencia"
  items:
    #  loop
    - title: "PyPi descargar"
      link: "https://releases.groupdocs.com/comparison/python-net/"
      color: "red"
        #  loop
    - title: "Licencias"
      link: "https://purchase.groupdocs.com/pricing/comparison/python-net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Comparar hojas de cálculo XLSX con Python"
    exclude: "XLSX"
    description: "Compare fácilmente hojas de cálculo de MS Excel XLSX utilizando la API GroupDocs.Comparison for Python via .NET. Obtenga información detallada sobre los cambios en los datos de su negocio con nuestros informes detallados."
    items: 
        # format loop 1
        - name: "Compara PDF archivos"
          format: "PDF"
          link: "/comparison/python-net/pdf/"
          description: "Formato de documento Adobe Portable"

        # format loop 2
        - name: "Compara DOCX archivos"
          format: "DOCX"
          link: "/comparison/python-net/docx/"
          description: "Documento XML abierto de Microsoft Word"

        # format loop 3
        - name: "Compara RTF archivos"
          format: "RTF"
          link: "/comparison/python-net/rtf/"
          description: "Formato de archivo de texto enriquecido"

        # format loop 4
        - name: "Compara TXT archivos"
          format: "TXT"
          link: "/comparison/python-net/txt/"
          description: "Formato de archivo de texto plano"

        # format loop 5
        - name: "Compara XLSX archivos"
          format: "XLSX"
          link: "/comparison/python-net/xlsx/"
          description: "Hoja de cálculo XML abierta de Microsoft Excel"

        # format loop 6
        - name: "Comparar archivos CSV"
          format: "CSV"
          link: "/comparison/python-net/csv/"
          description: "Archivo de valores separados por comas"

        # format loop 7
        - name: "Compara PPTX archivos"
          format: "PPTX"
          link: "/comparison/python-net/pptx/"
          description: "PowerPoint Presentación XML abierta"

        # format loop 8
        - name: "Compara ODS archivos"
          format: "ODS"
          link: "/comparison/python-net/ods/"
          description: "Open Document Hoja de cálculo"

        # format loop 9
        - name: "Comparar archivos ODP"
          format: "ODP"
          link: "/comparison/python-net/odp/"
          description: "OpenDocument Formato de archivo de presentación"

        # format loop 10
        - name: "Compara ODT archivos"
          format: "ODT"
          link: "/comparison/python-net/odt/"
          description: "Open Document Texto"

        # format loop 11
        - name: "Compara JPEG archivos"
          format: "JPEG"
          link: "/comparison/python-net/jpeg/"
          description: "JPEG Imagen"

        # format loop 12
        - name: "Compara PNG archivos"
          format: "PNG"
          link: "/comparison/python-net/png/"
          description: "Portable Gráfico de red"

        # format loop 13
        - name: "Compara GIF archivos"
          format: "GIF"
          link: "/comparison/python-net/gif/"
          description: "Archivo de formato de intercambio gráfico"

        # format loop 14
        - name: "Compara BMP archivos"
          format: "BMP"
          link: "/comparison/python-net/bmp/"
          description: "Formato de archivo de mapa de bits"

        # format loop 15
        - name: "Comparar archivos HTML"
          format: "HTML"
          link: "/comparison/python-net/html/"
          description: "Lenguaje de marcado de hipertexto"

        # format loop 16
        - name: "Compara MSG archivos"
          format: "MSG"
          link: "/comparison/python-net/msg/"
          description: "Mensaje de correo electrónico de Microsoft Outlook"

        # format loop 17
        - name: "Compara ONE archivos"
          format: "ONE"
          link: "/comparison/python-net/one/"
          description: "Microsoft OneNote"

        # format loop 18
        - name: "Compara VSDX archivos"
          format: "VSDX"
          link: "/comparison/python-net/vsdx/"
          description: "Dibujo de Microsoft Visio"

        # format loop 19
        - name: "Comparar archivos CS"
          format: "CS"
          link: "/comparison/python-net/cs/"
          description: "Lenguaje CSharp"

        # format loop 20
        - name: "Compara Java archivos"
          format: "Java"
          link: "/comparison/python-net/java/"
          description: "Java Idioma"
          
        # format loop 21
        - name: "Comparar archivos CPP"
          format: "CPP"
          link: "/comparison/python-net/cpp/"
          description: "Lenguaje C++"
---