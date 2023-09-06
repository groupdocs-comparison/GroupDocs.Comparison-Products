---
############################# Static ############################
layout: "auto-gen-comparison"
date: 2021-05-13T12:45:19+03:00
draft: false

############################# Head ############################
head_title: "Сравните два файла DJVU в .NET | API-интерфейсы сравнения документов"
head_description: "Сравнивайте и объединяйте более двух файлов DJVU в приложениях C# .NET. Получите сводную информацию о различиях в содержании, тексте и стиле файлов, изображений и форматов документов DJVU."

############################# Header ############################
title: "Сравнить файлы DJVU в C# .NET"
description: "API сравнения документов .NET для обнаружения изменений между двумя версиями файлов DJVU и экспорта в окончательный документ с подробным описанием различий между сравниваемыми документами."
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Скачать бесплатную пробную версию"
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
              text: "Справочник по API"

            # button loop
            - link: "https://github.com/groupdocs-comparison"
              text: "Примеры кода"

            # button loop
            - link: "https://products.groupdocs.app/comparison/family"
              text: "Живые Демо"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "Цены"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/net"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: "Об API GroupDocs.Comparison for .NET"
    content: |
        [GroupDocs.Comparison for .NET](/comparison/net/) — это собственный API .NET для сравнения нескольких изображений и документов одного и того же формата. Он помогает обнаружить различия в абзацах, словах, символах, фигурах и даже в стилях текста сравниваемых документов, объединить изменения и экспортировать их в окончательный документ. Он поддерживает сравнение и объединение PDF-файлов, документов Word, электронных таблиц Excel, презентаций PowerPoint, диаграмм Visio, электронных писем Outlook, HTML, рисунков и форматов файлов изображений без использования какой-либо внешней библиотеки.

############################# Steps ############################
steps:
    enable: true
    title_left: "Действия по сравнению файлов DJVU в C#"
    content_left: |
        [GroupDocs.Comparison](/comparison/net/) позволяет разработчикам .NET сравнивать и объединять несколько файлов DJVU в своих приложениях, выполнив несколько простых шагов.
        * Создайте экземпляр объекта **Comparer** с путем или потоком исходного документа.
        * Вызовите метод Add и укажите путь или поток целевого документа. Повторите этот шаг для каждого целевого документа.
        * Вызов метода сравнения.
    title_right: "Системные Требования"
    content_right: |
        API GroupDocs.Comparison for .NET поддерживаются на всех основных платформах и операционных системах. Прежде чем выполнять приведенный ниже код, убедитесь, что в вашей системе установлены следующие необходимые компоненты.
        * Операционные системы: Microsoft Windows, Linux, MacOS.
        * Среды разработки: Microsoft Visual Studio, Xamarin, MonoDevelop
        * Платформы: .NET Framework, .NET Standard, .NET Core, Mono.
        * Загрузите последнюю версию GroupDocs.Comparison for .NET с сайта [NuGet](https://www.nuget.org/packages/groupdocs.comparison).
    code: |
        ```cs
        // Сравнить несколько документов с локального диска
        
        using (Comparer comparer = new Comparer("source.djvu"))
        {
        	comparer.Add("target1.djvu");
            comparer.Add("target2.djvu");
            comparer.Add("target3.djvu");
            comparer.Compare("result.djvu"); // Создать файл результатов с указанным именем
        }
        
        // Сравнить несколько документов из потока
        
        using (Comparer comparer = new Comparer(File.OpenRead("source.djvu")))
        {
        	comparer.Add(File.OpenRead("target1.djvu"));
            comparer.Add(File.OpenRead("target2.djvu"));
            comparer.Add(File.OpenRead("target3.djvu"));
            comparer.Compare(File.Create("result.djvu")); // Создать файл результатов с указанным именем
        }
        ```

############################# Demos ############################
demos:
    enable: true
    title: "Живые демонстрации сравнения файлов DJVU"
    content: |
        Обнаружьте различия между файлами DJVU прямо сейчас, посетив веб-сайт [GroupDocs.Comparison Live Demos](https://products.groupdocs.app/comparison/family).
        Живая демонстрация имеет следующие преимущества

############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-djvu"
          title: "О формате файла DJVU"
          content: |
            DjVu, произносится как «дежавю», представляет собой формат графических файлов, предназначенный для отсканированных документов и книг, особенно тех, которые содержат комбинацию текста, рисунков, изображений и фотографий. Он был разработан AT&T Labs. Он использует несколько методов, таких как разделение слоев изображения на текст и фоновые изображения, прогрессивную загрузку, арифметическое кодирование и сжатие с потерями для битональных изображений. Поскольку файл DJVU может содержать сжатые, но высококачественные цветные изображения, фотографии, текст и рисунки и поэтому может быть сохранен в меньшем пространстве, он используется в Интернете в качестве электронных книг, руководств, газет, древних документов и т. д.
          link: "https://docs.fileformat.com/image/djvu/"

############################# More Formats ############################
more_formats:
    enable: true
    title: "Сравнение других форматов файлов"
    content: |
        API сравнения многоформатных документов и изображений для .NET. Анализируйте различия между документами одного и того же формата без использования каких-либо внешних инструментов.
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
    title: "GroupDocs.Comparison предлагает API-интерфейсы просмотра документов для других популярных сред разработки."

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for Java DJVU"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/djvu/"

############################# Back to top ###############################
back_to_top:
    enable: true
---
