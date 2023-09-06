---
############################# Static ############################
layout: "auto-gen-comparison"
date: 2021-05-13T12:45:19+03:00
draft: false

############################# Head ############################
head_title: "API de comparación Java HTM: compare archivos HTM en busca de diferencias"
head_description: "Compare y combine archivos HTM en aplicaciones Java, J2EE, J2SE. Analice el resumen de diferencias en contenido, texto y estilo de HTM archivos, imágenes y formatos de documentos."

############################# Header ############################
title: "Comparar archivos HTM en Java"
description: "Realice una comparación línea por línea entre más de dos archivos HTM en Java. Recupere una lista de diferencias y guarde los archivos comparados en un solo documento."
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
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
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-comparison-java.png"
        product: "GroupDocs.Comparison"
        platform: "Java"

    middle:
        button: 
            # button loop
            - link: "https://apireference.groupdocs.com/comparison/java"
              text: "Referencia de API"

            # button loop
            - link: "https://github.com/groupdocs-comparison"
              text: "Ejemplos de código"

            # button loop
            - link: "https://products.groupdocs.app/comparison/family"
              text: "Demostraciones en vivo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/java"
              text: "Precios"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/java"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: "Acerca de la API GroupDocs.Comparison for Java"
    content: |
        Mejore sus aplicaciones Java con funciones de comparación de imágenes y documentos utilizando la API [GroupDocs.Comparison for Java](/comparison/java/). Le ayuda a identificar las diferencias dentro de párrafos, palabras, caracteres, formas, incluso los estilos de texto de los documentos comparados del mismo formato, permite fusionar los cambios y exportarlos a un documento final. Admite comparar y fusionar una amplia gama de documentos, incluidos PDF, Word, hojas de cálculo de Excel, presentaciones de PowerPoint, diagramas de Visio, correos electrónicos de Outlook, HTML, dibujos y formatos de archivos de imágenes sin utilizar ninguna biblioteca externa.

############################# Steps ############################
steps:
    enable: true
    title_left: "Pasos para comparar archivos HTM en Java"
    content_left: |
        [GroupDocs.Comparison](/comparison/java/) facilita a los desarrolladores de Java comparar archivos HTM dentro de sus aplicaciones utilizando unas pocas líneas de código.
        * Crear una instancia del objeto **Comparador** con la ruta o flujo del documento fuente.
        * Llame al método add y especifique la ruta o secuencia del documento de destino.
        * Llame al método de comparación.
    title_right: "Requisitos del sistema"
    content_right: |
        Las API de GroupDocs.Comparison for Java son compatibles con las principales plataformas y sistemas operativos. Antes de ejecutar el código siguiente, asegúrese de tener los siguientes requisitos previos instalados en su sistema.
        * Sistemas operativos: Microsoft Windows, Linux, MacOS
        * Entornos de desarrollo: NetBeans, Intellij IDEA, Eclipse etc
        * Entorno de ejecución Java: J2SE 6.0 y superior
        * Obtenga la última versión de GroupDocs.Comparison for Java de [Maven](https://repository.groupdocs.com/webapp/#/artifacts/browse/tree/General/repo/com/groupdocs/groupdocs-comparison)
    code: |
        ```java
        // Comparar documentos del archivo local
        
        try (Comparer comparer = new Comparer("C:\\source.htm")) {
            comparer.add("C:\\target.htm");
            comparer.compare("C:\\result.htm"); // Crear archivo de resultados con el nombre especificado
        }
        
        // Comparar documentos de la secuencia
        
        try (Comparer comparer = new Comparer(new FileInputStream("C:\\source.htm"))) {
            comparer.add(new FileInputStream("C:\\target.htm"));
            comparer.compare(new FileOutputStream("C:\\result.htm")); // Crear archivo de resultados con el nombre especificado
        }
        ```

############################# Demos ############################
demos:
    enable: true
    title: "Demostraciones en vivo para comparar archivos HTM"
    content: |
        Compare archivos HTM ahora mismo visitando el sitio web [GroupDocs.Comparison Live Demos](https://products.groupdocs.app/comparison/family).
        La demostración en vivo tiene los siguientes beneficios

############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-htm"
          title: "Acerca del formato de archivo HTM"
          content: |
            Los archivos con extensión HTM representan un lenguaje de marcado de hipertexto para crear páginas web que se mostrarán en navegadores web como Google Chrome, Internet Explorer, Firefox y muchos otros. Define las marcas para crear páginas estáticas que se publicarán en la World Wide Web (WWW) para que otros puedan acceder a ellas. Estas marcas indican a los navegadores cómo mostrar el contenido de una página web. Dichas páginas pueden contener texto sin formato, imágenes, hipervínculos a otras páginas, vídeos y otra información multimedia. Cuando se publica una página web, puedes echar un vistazo al código de marcado detrás de ella viendo la fuente de la página. Los navegadores modernos permiten inspeccionar cada sección de una página web donde se elabora cada subdivisión o elemento de marcado en la fuente HTM.
          link: "https://docs.fileformat.com/image/htm/"

############################# More Formats ############################
more_formats:
    enable: true
    title: "Comparar otros formatos de archivo"
    content: |
        API de comparación de documentos e imágenes multiformato para Java. Compare algunos de los formatos de archivo populares a continuación sin ningún software externo.
    format: 
        # format loop
        - name: "Compare PDF Files"
          link: "https://products.groupdocs.com/comparison/java/pdf/"
          description: "Adobe Portable Document Format"

        # format loop
        - name: "Compare DOC Files"
          link: "https://products.groupdocs.com/comparison/java/doc/"
          description: "Microsoft Word Document"

        # format loop
        - name: "Compare DOCM Files"
          link: "https://products.groupdocs.com/comparison/java/docm/"
          description: "Microsoft Word Macro-Enabled Document"

        # format loop
        - name: "Compare DOCX Files"
          link: "https://products.groupdocs.com/comparison/java/docx/"
          description: "Microsoft Word Open XML Document"

        # format loop
        - name: "Compare DOT Files"
          link: "https://products.groupdocs.com/comparison/java/dot/"
          description: "Microsoft Word Document Template"

        # format loop
        - name: "Compare DOTM Files"
          link: "https://products.groupdocs.com/comparison/java/dotm/"
          description: "Microsoft Word Macro-Enabled Template"

        # format loop
        - name: "Compare DOTX Files"
          link: "https://products.groupdocs.com/comparison/java/dotx/"
          description: "Word Open XML Document Template"

        # format loop
        - name: "Compare RTF Files"
          link: "https://products.groupdocs.com/comparison/java/rtf/"
          description: "Rich Text File Format"

        # format loop
        - name: "Compare TXT Files"
          link: "https://products.groupdocs.com/comparison/java/txt/"
          description: "Plain Text File Format"

        # format loop
        - name: "Compare XLS Files"
          link: "https://products.groupdocs.com/comparison/java/xls/"
          description: "Microsoft Excel Binary File Format"

        # format loop
        - name: "Compare XLSX Files"
          link: "https://products.groupdocs.com/comparison/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop
        - name: "Compare XLTM Files"
          link: "https://products.groupdocs.com/comparison/java/xltm/"
          description: "Microsoft Excel macro-enabled template"

        # format loop
        - name: "Compare XLSM Files"
          link: "https://products.groupdocs.com/comparison/java/xlsm/"
          description: "Microsoft Excel Macro-Enabled Spreadsheet"

        # format loop
        - name: "Compare XLSB Files"
          link: "https://products.groupdocs.com/comparison/java/xlsb/"
          description: "Microsoft Excel Binary Spreadsheet File"

        # format loop
        - name: "Compare CSV Files"
          link: "https://products.groupdocs.com/comparison/java/csv/"
          description: "Comma Separated Values File"

        # format loop
        - name: "Compare PPT Files"
          link: "https://products.groupdocs.com/comparison/java/ppt/"
          description: "PowerPoint Presentation"

        # format loop
        - name: "Compare PPS Files"
          link: "https://products.groupdocs.com/comparison/java/pps/"
          description: "Microsoft PowerPoint Slide Show"

        # format loop
        - name: "Compare PPTX Files"
          link: "https://products.groupdocs.com/comparison/java/pptx/"
          description: "PowerPoint Open XML Presentation"

        # format loop
        - name: "Compare PPSX Files"
          link: "https://products.groupdocs.com/comparison/java/ppsx/"
          description: "PowerPoint Open XML Slide Show"

        # format loop
        - name: "Compare POT Files"
          link: "https://products.groupdocs.com/comparison/java/pot/"
          description: "Microsoft PowerPoint template"

        # format loop
        - name: "Compare POTX Files"
          link: "https://products.groupdocs.com/comparison/java/potx/"
          description: "Microsoft PowerPoint Open XML Template"

        # format loop
        - name: "Compare ODS Files"
          link: "https://products.groupdocs.com/comparison/java/ods/"
          description: "Open Document Spreadsheet"

        # format loop
        - name: "Compare ODP Files"
          link: "https://products.groupdocs.com/comparison/java/odp/"
          description: "OpenDocument Presentation File Format"

        # format loop
        - name: "Compare OTP Files"
          link: "https://products.groupdocs.com/comparison/java/otp/"
          description: "Origin Graph Template"

        # format loop
        - name: "Compare ODT Files"
          link: "https://products.groupdocs.com/comparison/java/odt/"
          description: "Open Document Text"

        # format loop
        - name: "Compare OTT Files"
          link: "https://products.groupdocs.com/comparison/java/ott/"
          description: "Open Document Template"

        # format loop
        - name: "Compare VST Files"
          link: "https://products.groupdocs.com/comparison/java/vst/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare JPEG Files"
          link: "https://products.groupdocs.com/comparison/java/jpeg/"
          description: "JPEG Image"

        # format loop
        - name: "Compare PNG Files"
          link: "https://products.groupdocs.com/comparison/java/png/"
          description: "Portable Network Graphic"

        # format loop
        - name: "Compare GIF Files"
          link: "https://products.groupdocs.com/comparison/java/gif/"
          description: "Graphical Interchange Format File"

        # format loop
        - name: "Compare BMP Files"
          link: "https://products.groupdocs.com/comparison/java/bmp/"
          description: "Bitmap File Format"

        # format loop
        - name: "Compare HTML Files"
          link: "https://products.groupdocs.com/comparison/java/html/"
          description: "Hyper Text Markup Language"

        # format loop
        - name: "Compare MHT Files"
          link: "https://products.groupdocs.com/comparison/java/mht/"
          description: "Mime HTML"

        # format loop
        - name: "Compare MHTML Files"
          link: "https://products.groupdocs.com/comparison/java/mhtml/"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop
        - name: "Compare MSG Files"
          link: "https://products.groupdocs.com/comparison/java/msg/"
          description: "Microsoft Outlook E-mail Message"

        # format loop
        - name: "Compare EML Files"
          link: "https://products.groupdocs.com/comparison/java/eml/"
          description: "E-mail Message"

        # format loop
        - name: "Compare EMLX Files"
          link: "https://products.groupdocs.com/comparison/java/emlx/"
          description: "Apple Mail E-mail File"

        # format loop
        - name: "Compare ONE Files"
          link: "https://products.groupdocs.com/comparison/java/one/"
          description: "Microsoft OneNote"

        # format loop
        - name: "Compare VSD Files"
          link: "https://products.groupdocs.com/comparison/java/vsd/"
          description: "Microsoft Visio 2003-2010 Drawing"

        # format loop
        - name: "Compare VSDX Files"
          link: "https://products.groupdocs.com/comparison/java/vsdx/"
          description: "Microsoft Visio Drawing"

        # format loop
        - name: "Compare VSS Files"
          link: "https://products.groupdocs.com/comparison/java/vss/"
          description: "Microsoft Visio 2003-2010 Stencil"

        # format loop
        - name: "Compare VST Files"
          link: "https://products.groupdocs.com/comparison/java/vst/"
          description: "Microsoft Visio 2003-2010 Template"

        # format loop
        - name: "Compare VDX Files"
          link: "https://products.groupdocs.com/comparison/java/vdx/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare CS Files"
          link: "https://products.groupdocs.com/comparison/java/cs/"
          description: "CSharp Language"

        # format loop
        - name: "Compare Java Files"
          link: "https://products.groupdocs.com/comparison/java/java/"
          description: "Java Language"

        # format loop
        - name: "Compare CPP Files"
          link: "https://products.groupdocs.com/comparison/java/cpp/"
          description: "C++ Language"

        # format loop
        - name: "Compare JS Files"
          link: "https://products.groupdocs.com/comparison/java/js/"
          description: "JavaScript Language"

        # format loop
        - name: "Compare PY Files"
          link: "https://products.groupdocs.com/comparison/java/py/"
          description: "Python Language"

        # format loop
        - name: "Compare RB Files"
          link: "https://products.groupdocs.com/comparison/java/rb/"
          description: "Ruby Language"

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison ofrece API de visualización de documentos para otros entornos de desarrollo populares"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for .NET HTM"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
          product: "GroupDocs.Comparison"
          platform: ".NET"
          link: "/comparison/net/htm/"

############################# Back to top ###############################
back_to_top:
    enable: true
---
