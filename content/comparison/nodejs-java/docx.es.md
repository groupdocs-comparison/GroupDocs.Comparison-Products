
---
############################# Static ############################
layout: "format"
date:  2024-03-22T13:27:49
draft: false
lang: es
format: Docx
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

############################# Head ############################
head_title: "La API Node.js permite comparar DOCX documentos."
head_description: "La API GroupDocs.Comparison Node.js, que genera informes útiles que describen las alteraciones de los documentos, puede comprobar las diferencias de los archivos de MS Word DOCX."

############################# Header ############################
title: "Comparación de DOCX archivos con Node.js via Java" 
description: "Utilice la API de procesamiento de documentos en Node.js para detectar y revelar cualquier alteración en los archivos MS Word DOCX por parte de Node.js via Java aplicaciones. Aproveche las ventajas de la generación de informes rápida y sin esfuerzo."
subtitle: "Solución para la comparación de archivos" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Descarga gratuita de NPM"
      link: "https://releases.groupdocs.com/comparison/nodejs-java/"
      
############################# About ############################
about:
    enable: true
    title: "Funciones de la API Open GroupDocs.Comparison for Node.js via Java"
    link: "/comparison/nodejs-java/"
    link_title: "Obtenga más información"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison proporciona informes detallados que aportan datos detallados sobre los cambios en las diferentes versiones de DOCX documentos. Usa Node.js via Java junto con nuestra API añadiendo un par de líneas de código y sin otras bibliotecas. Analice las alteraciones en las páginas, el texto, los estilos de texto o las formas de los MS Word documentos. Seleccione solo los datos correctos y componga el documento final DOCX fusionándolos. Mejore sus soluciones de procesamiento de documentos con nuestro software.

############################# Steps ############################
steps:
    enable: true
    title: "Redacte un informe con DOCX distinciones de documentos en JavaScript"
    content: |
      [GroupDocs.Comparison](https://products.groupdocs.com/comparison/nodejs-java/) y Node.js via Java nos permiten comparar DOCX documentos
      
      1. Usa [NPM](https://www.npmjs.com/package/@groupdocs/groupdocs.comparison) para instalar GroupDocs.Comparison para Node.js via Java
      2. La llamada al constructor Comparer necesita la ruta DOCX
      3. Se deben proporcionar otros DOCX archivos
      4. Disfruta de los resultados
   
    code:
      platform: "net"
      copy_title: "Copiar"
      install:
        command: "npm i @groupdocs/groupdocs.comparison"
        copy_tip: "haga clic para copiar"
        copy_done: "copiado"
      links:
        #  loop
        - title: "Más ejemplos"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java"
        #  loop
        - title: "Documentación"
          link: "https://docs.groupdocs.com/comparison/nodejs-java/"
          
      content: |
        ```javascript {style=abap}

        // Revisa varios archivos para ver en qué se parecen o se diferencian

        // Crea un objeto Comparer y dale el primer archivo como entrada
        const comparer = new groupdocs.comparison.Comparer('first.docx');

        // Añadir más archivos
        comparer.add('second.docx');
        comparer.add('third.docx');

        // Obtenga el informe final
        await comparer.compare('report_full.docx');

        console.log('\nDocuments compared successfully.\nCheck output.');
        
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "¿Estás listo para empezar?"
  description: "Pruebe GroupDocs.Comparison funciones de forma gratuita o solicite una licencia"
  items:
    #  loop
    - title: "NPM descargar"
      link: "https://releases.groupdocs.com/comparison/nodejs-java/"
      color: "red"
        #  loop
    - title: "Licencias"
      link: "https://purchase.groupdocs.com/pricing/comparison/java/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Usa JavaScript para comparar DOCX documentos"
    exclude: "DOCX"
    description: "Cualquier archivo MS Word DOCX se puede comparar con GroupDocs.Comparison for Node.js via Java. Obtenga información valiosa sobre los cambios en sus documentos."
    items: 
        # format loop 1
        - name: "Compara PDF archivos"
          format: "PDF"
          link: "/comparison/nodejs-java/pdf/"
          description: "Formato de documento Adobe Portable"

        # format loop 2
        - name: "Compara DOCX archivos"
          format: "DOCX"
          link: "/comparison/nodejs-java/docx/"
          description: "Documento XML abierto de Microsoft Word"

        # format loop 3
        - name: "Compara RTF archivos"
          format: "RTF"
          link: "/comparison/nodejs-java/rtf/"
          description: "Formato de archivo de texto enriquecido"

        # format loop 4
        - name: "Compara TXT archivos"
          format: "TXT"
          link: "/comparison/nodejs-java/txt/"
          description: "Formato de archivo de texto plano"

        # format loop 5
        - name: "Compara XLSX archivos"
          format: "XLSX"
          link: "/comparison/nodejs-java/xlsx/"
          description: "Hoja de cálculo XML abierta de Microsoft Excel"

        # format loop 6
        - name: "Comparar archivos CSV"
          format: "CSV"
          link: "/comparison/nodejs-java/csv/"
          description: "Archivo de valores separados por comas"

        # format loop 7
        - name: "Compara PPTX archivos"
          format: "PPTX"
          link: "/comparison/nodejs-java/pptx/"
          description: "PowerPoint Presentación XML abierta"

        # format loop 8
        - name: "Compara ODS archivos"
          format: "ODS"
          link: "/comparison/nodejs-java/ods/"
          description: "Open Document Hoja de cálculo"

        # format loop 9
        - name: "Comparar archivos ODP"
          format: "ODP"
          link: "/comparison/nodejs-java/odp/"
          description: "OpenDocument Formato de archivo de presentación"

        # format loop 10
        - name: "Compara ODT archivos"
          format: "ODT"
          link: "/comparison/nodejs-java/odt/"
          description: "Open Document Texto"

        # format loop 11
        - name: "Compara JPEG archivos"
          format: "JPEG"
          link: "/comparison/nodejs-java/jpeg/"
          description: "JPEG Imagen"

        # format loop 12
        - name: "Compara PNG archivos"
          format: "PNG"
          link: "/comparison/nodejs-java/png/"
          description: "Portable Gráfico de red"

        # format loop 13
        - name: "Compara GIF archivos"
          format: "GIF"
          link: "/comparison/nodejs-java/gif/"
          description: "Archivo de formato de intercambio gráfico"

        # format loop 14
        - name: "Compara BMP archivos"
          format: "BMP"
          link: "/comparison/nodejs-java/bmp/"
          description: "Formato de archivo de mapa de bits"

        # format loop 15
        - name: "Comparar archivos HTML"
          format: "HTML"
          link: "/comparison/nodejs-java/html/"
          description: "Lenguaje de marcado de hipertexto"

        # format loop 16
        - name: "Compara MSG archivos"
          format: "MSG"
          link: "/comparison/nodejs-java/msg/"
          description: "Mensaje de correo electrónico de Microsoft Outlook"

        # format loop 17
        - name: "Compara ONE archivos"
          format: "ONE"
          link: "/comparison/nodejs-java/one/"
          description: "Microsoft OneNote"

        # format loop 18
        - name: "Compara VSDX archivos"
          format: "VSDX"
          link: "/comparison/nodejs-java/vsdx/"
          description: "Dibujo de Microsoft Visio"

        # format loop 19
        - name: "Comparar archivos CS"
          format: "CS"
          link: "/comparison/nodejs-java/cs/"
          description: "Lenguaje CSharp"

        # format loop 20
        - name: "Compara Java archivos"
          format: "Java"
          link: "/comparison/nodejs-java/java/"
          description: "Java Idioma"
          
        # format loop 21
        - name: "Comparar archivos CPP"
          format: "CPP"
          link: "/comparison/nodejs-java/cpp/"
          description: "Lenguaje C++"
---