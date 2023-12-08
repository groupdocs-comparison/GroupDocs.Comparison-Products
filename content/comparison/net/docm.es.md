---
############################# Static ############################
layout: "auto-gen-comparison"
date: 2021-05-13T12:45:19+03:00
draft: false

############################# Head ############################
head_title: "Compara dos archivos DOCM en .NET | API de comparación de documentos"
head_description: "Compare y combine más de dos archivos DOCM en aplicaciones C# .NET. Recupere un resumen de diferencias en contenido, texto y estilo de DOCM archivos, imágenes y formatos de documentos."

############################# Header ############################
title: "Comparar archivos DOCM en C# .NET"
description: "API de comparación de documentos .NET para detectar los cambios entre dos versiones de archivos DOCM y exportarlos a un documento final con un resumen detallado de las diferencias entre los documentos comparados."
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
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
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-comparison-net.png"
        product: "GroupDocs.Comparison"
        platform: ".NET"

    middle:
        button: 
            # button loop
            - link: "https://apireference.groupdocs.com/comparison/net"
              text: "Referencia de API"

            # button loop
            - link: "https://github.com/groupdocs-comparison"
              text: "Ejemplos de código"

            # button loop
            - link: "https://products.groupdocs.app/comparison/family"
              text: "Demostraciones en vivo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "Precios"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/net"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: "Acerca de la API GroupDocs.Comparison for .NET"
    content: |
        [GroupDocs.Comparison for .NET](/comparison/net/) es una API .NET nativa para comparar múltiples imágenes y documentos del mismo formato. Le ayuda a detectar las diferencias dentro de párrafos, palabras, caracteres, formas e incluso los estilos de texto de los documentos comparados, fusionar los cambios y exportarlos a un documento final. Admite comparar y combinar PDF, documentos de Word, hojas de cálculo de Excel, presentaciones de PowerPoint, diagramas de Visio, correos electrónicos de Outlook, HTML, dibujos y formatos de archivos de imágenes sin utilizar ninguna biblioteca externa.

############################# Steps ############################
steps:
    enable: true
    title_left: "Pasos para comparar archivos DOCM en C#"
    content_left: |
        [GroupDocs.Comparison](/comparison/net/) facilita a los desarrolladores .NET comparar y fusionar múltiples archivos DOCM en sus aplicaciones implementando unos sencillos pasos.
        * Crear una instancia del objeto **Comparador** con la ruta o flujo del documento fuente.
        * Llame al método Agregar y especifique la ruta o secuencia del documento de destino. Repita este paso para cada documento de destino.
        * Llamar al método de comparación.
    title_right: "Requisitos del sistema"
    content_right: |
        Las API de GroupDocs.Comparison for .NET son compatibles con las principales plataformas y sistemas operativos. Antes de ejecutar el código siguiente, asegúrese de tener los siguientes requisitos previos instalados en su sistema.
        * Sistemas operativos: Microsoft Windows, Linux, MacOS
        * Entornos de desarrollo: Microsoft Visual Studio, Xamarin, MonoDevelop
        * Marcos: .NET Framework, .NET Standard, .NET Core, Mono
        * Obtenga la última versión de GroupDocs.Comparison for .NET descargada de [NuGet](https://www.nuget.org/packages/groupdocs.comparison)
    code: |
        ```cs
        // Comparar varios documentos desde el disco local
        
        using (Comparer comparer = new Comparer("source.docm"))
        {
        	comparer.Add("target1.docm");
            comparer.Add("target2.docm");
            comparer.Add("target3.docm");
            comparer.Compare("result.docm"); // Crear archivo de resultados con el nombre especificado
        }
        
        // Compara varios documentos de la secuencia
        
        using (Comparer comparer = new Comparer(File.OpenRead("source.docm")))
        {
        	comparer.Add(File.OpenRead("target1.docm"));
            comparer.Add(File.OpenRead("target2.docm"));
            comparer.Add(File.OpenRead("target3.docm"));
            comparer.Compare(File.Create("result.docm")); // Crear archivo de resultados con el nombre especificado
        }
        ```

############################# Demos ############################
demos:
    enable: true
    title: "Demostraciones en vivo de comparación de archivos DOCM"
    content: |
        Detecte diferencias entre archivos DOCM ahora mismo visitando el sitio web [GroupDocs.Comparison Live Demos](https://products.groupdocs.app/comparison/family).
        La demostración en vivo tiene los siguientes beneficios

############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-docm"
          title: "Acerca del formato de archivo DOCM"
          content: |
            Los archivos DOCM son documentos generados en Microsoft Word 2007 o superior con la capacidad de ejecutar macros. Es similar al formato de archivo DOCX, pero la capacidad de ejecutar macros lo diferencia de DOCX. Al igual que DOCX, los archivos DOCM pueden almacenar texto, imágenes, tablas, formas, gráficos y otros contenidos. La capacidad de ejecutar macros facilita el ahorro de tiempo al ejecutar una serie de comandos en forma de acciones grabadas para completar automáticamente una tarea. . Los archivos DOCM se pueden abrir y editar en Microsoft Word 2007 y superior.
          link: "https://docs.fileformat.com/image/docm/"

############################# More Formats ############################
more_formats:
    enable: true
    title: "Comparar otros formatos de archivo"
    content: |
        API de comparación de imágenes y documentos multiformato para .NET. Analiza las diferencias entre documentos del mismo formato sin utilizar ninguna herramienta externa.
    format: 
        # format loop
        - name: "Compare PDF Files"
          link: "https://products.groupdocs.com/comparison/net/pdf/"
          description: "Adobe Portable Document Format"

        # format loop
        - name: "Compare DOC Files"
          link: "https://products.groupdocs.com/comparison/net/doc/"
          description: "Microsoft Word Document"

        # format loop
        - name: "Compare DOCM Files"
          link: "https://products.groupdocs.com/comparison/net/docm/"
          description: "Microsoft Word Macro-Enabled Document"

        # format loop
        - name: "Compare DOCX Files"
          link: "https://products.groupdocs.com/comparison/net/docx/"
          description: "Microsoft Word Open XML Document"

        # format loop
        - name: "Compare DOT Files"
          link: "https://products.groupdocs.com/comparison/net/dot/"
          description: "Microsoft Word Document Template"

        # format loop
        - name: "Compare DOTM Files"
          link: "https://products.groupdocs.com/comparison/net/dotm/"
          description: "Microsoft Word Macro-Enabled Template"

        # format loop
        - name: "Compare DOTX Files"
          link: "https://products.groupdocs.com/comparison/net/dotx/"
          description: "Word Open XML Document Template"

        # format loop
        - name: "Compare RTF Files"
          link: "https://products.groupdocs.com/comparison/net/rtf/"
          description: "Rich Text File Format"

        # format loop
        - name: "Compare TXT Files"
          link: "https://products.groupdocs.com/comparison/net/txt/"
          description: "Plain Text File Format"

        # format loop
        - name: "Compare XLS Files"
          link: "https://products.groupdocs.com/comparison/net/xls/"
          description: "Microsoft Excel Binary File Format"

        # format loop
        - name: "Compare XLSX Files"
          link: "https://products.groupdocs.com/comparison/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop
        - name: "Compare XLTM Files"
          link: "https://products.groupdocs.com/comparison/net/xltm/"
          description: "Microsoft Excel macro-enabled template"

        # format loop
        - name: "Compare XLSM Files"
          link: "https://products.groupdocs.com/comparison/net/xlsm/"
          description: "Microsoft Excel Macro-Enabled Spreadsheet"

        # format loop
        - name: "Compare XLSB Files"
          link: "https://products.groupdocs.com/comparison/net/xlsb/"
          description: "Microsoft Excel Binary Spreadsheet File"

        # format loop
        - name: "Compare CSV Files"
          link: "https://products.groupdocs.com/comparison/net/csv/"
          description: "Comma Separated Values File"

        # format loop
        - name: "Compare PPT Files"
          link: "https://products.groupdocs.com/comparison/net/ppt/"
          description: "PowerPoint Presentation"

        # format loop
        - name: "Compare PPS Files"
          link: "https://products.groupdocs.com/comparison/net/pps/"
          description: "Microsoft PowerPoint Slide Show"

        # format loop
        - name: "Compare PPTX Files"
          link: "https://products.groupdocs.com/comparison/net/pptx/"
          description: "PowerPoint Open XML Presentation"

        # format loop
        - name: "Compare PPSX Files"
          link: "https://products.groupdocs.com/comparison/net/ppsx/"
          description: "PowerPoint Open XML Slide Show"

        # format loop
        - name: "Compare POT Files"
          link: "https://products.groupdocs.com/comparison/net/pot/"
          description: "Microsoft PowerPoint template"

        # format loop
        - name: "Compare POTX Files"
          link: "https://products.groupdocs.com/comparison/net/potx/"
          description: "Microsoft PowerPoint Open XML Template"

        # format loop
        - name: "Compare ODS Files"
          link: "https://products.groupdocs.com/comparison/net/ods/"
          description: "Open Document Spreadsheet"

        # format loop
        - name: "Compare ODP Files"
          link: "https://products.groupdocs.com/comparison/net/odp/"
          description: "OpenDocument Presentation File Format"

        # format loop
        - name: "Compare OTP Files"
          link: "https://products.groupdocs.com/comparison/net/otp/"
          description: "Origin Graph Template"

        # format loop
        - name: "Compare ODT Files"
          link: "https://products.groupdocs.com/comparison/net/odt/"
          description: "Open Document Text"

        # format loop
        - name: "Compare OTT Files"
          link: "https://products.groupdocs.com/comparison/net/ott/"
          description: "Open Document Template"

        # format loop
        - name: "Compare VST Files"
          link: "https://products.groupdocs.com/comparison/net/vst/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare JPEG Files"
          link: "https://products.groupdocs.com/comparison/net/jpeg/"
          description: "JPEG Image"

        # format loop
        - name: "Compare PNG Files"
          link: "https://products.groupdocs.com/comparison/net/png/"
          description: "Portable Network Graphic"

        # format loop
        - name: "Compare GIF Files"
          link: "https://products.groupdocs.com/comparison/net/gif/"
          description: "Graphical Interchange Format File"

        # format loop
        - name: "Compare BMP Files"
          link: "https://products.groupdocs.com/comparison/net/bmp/"
          description: "Bitmap File Format"

        # format loop
        - name: "Compare HTML Files"
          link: "https://products.groupdocs.com/comparison/net/html/"
          description: "Hyper Text Markup Language"

        # format loop
        - name: "Compare MHT Files"
          link: "https://products.groupdocs.com/comparison/net/mht/"
          description: "Mime HTML"

        # format loop
        - name: "Compare MHTML Files"
          link: "https://products.groupdocs.com/comparison/net/mhtml/"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop
        - name: "Compare MSG Files"
          link: "https://products.groupdocs.com/comparison/net/msg/"
          description: "Microsoft Outlook E-mail Message"

        # format loop
        - name: "Compare EML Files"
          link: "https://products.groupdocs.com/comparison/net/eml/"
          description: "E-mail Message"

        # format loop
        - name: "Compare EMLX Files"
          link: "https://products.groupdocs.com/comparison/net/emlx/"
          description: "Apple Mail E-mail File"

        # format loop
        - name: "Compare ONE Files"
          link: "https://products.groupdocs.com/comparison/net/one/"
          description: "Microsoft OneNote"

        # format loop
        - name: "Compare VSD Files"
          link: "https://products.groupdocs.com/comparison/net/vsd/"
          description: "Microsoft Visio 2003-2010 Drawing"

        # format loop
        - name: "Compare VSDX Files"
          link: "https://products.groupdocs.com/comparison/net/vsdx/"
          description: "Microsoft Visio Drawing"

        # format loop
        - name: "Compare VSS Files"
          link: "https://products.groupdocs.com/comparison/net/vss/"
          description: "Microsoft Visio 2003-2010 Stencil"

        # format loop
        - name: "Compare VST Files"
          link: "https://products.groupdocs.com/comparison/net/vst/"
          description: "Microsoft Visio 2003-2010 Template"

        # format loop
        - name: "Compare VDX Files"
          link: "https://products.groupdocs.com/comparison/net/vdx/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Compare CS Files"
          link: "https://products.groupdocs.com/comparison/net/cs/"
          description: "CSharp Language"

        # format loop
        - name: "Compare Java Files"
          link: "https://products.groupdocs.com/comparison/net/java/"
          description: "Java Language"

        # format loop
        - name: "Compare CPP Files"
          link: "https://products.groupdocs.com/comparison/net/cpp/"
          description: "C++ Language"

        # format loop
        - name: "Compare JS Files"
          link: "https://products.groupdocs.com/comparison/net/js/"
          description: "JavaScript Language"

        # format loop
        - name: "Compare PY Files"
          link: "https://products.groupdocs.com/comparison/net/py/"
          description: "Python Language"

        # format loop
        - name: "Compare RB Files"
          link: "https://products.groupdocs.com/comparison/net/rb/"
          description: "Ruby Language"

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison ofrece API de visualización de documentos para otros entornos de desarrollo populares"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for Java DOCM"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/docm/"

############################# Back to top ###############################
back_to_top:
    enable: true
---