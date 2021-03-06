---
############################# Static ############################
layout: "auto-gen-comparison"
date: 2021-05-13T12:45:21+03:00
draft: false
############################# Head ############################
head_title: "Сравните два файла HTML в .NET | API сравнения документов"
head_description: "Сравнивайте и объединяйте более двух (HTML-файлов) в приложениях C# .NET. Извлекайте сводку различий в содержимом, тексте и стиле HTML-файлов, изображений и форматов документов."
############################# Header ############################
title: "Сравните HTML-файлы в C# .NET"
description: ".NET API для сравнения документов для обнаружения изменений между двумя версиями HTML-файлов и экспорта в окончательный документ с подробным описанием различий между сравниваемыми документами."
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
              text: "Живые демонстрации"
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
    title: "О GroupDocs.Comparison для .NET API"
    content: |
        [GroupDocs.Comparison for .NET](/ru/comparison/net/) — это собственный API .NET для сравнения нескольких изображений и документов одного формата. Он помогает обнаруживать различия в абзацах, словах, символах, формах и даже стилях текста сравниваемых документов, объединять изменения и экспортировать их в окончательный документ. Он поддерживает сравнение и объединение PDF, документов Word, электронных таблиц Excel, презентаций PowerPoint, диаграмм Visio, электронных писем Outlook, HTML, рисунков и форматов файлов изображений без использования какой-либо внешней библиотеки.
############################# Steps ############################
steps:
    enable: true
    title_left: "Шаги для сравнения файлов HTML в C#"
    content_left: |
        [GroupDocs.Comparison](/ru/comparison/net/) позволяет разработчикам .NET легко сравнивать и объединять несколько файлов HTML в своих приложениях, выполняя несколько простых шагов.
        * Создание экземпляра объекта Comparer с путем или потоком исходного документа.
        * Вызовите метод Add и укажите путь к целевому документу или поток. Повторите этот шаг для каждого целевого документа.
        * Метод сравнения вызовов.
    title_right: "Системные Требования"
    content_right: |
        API GroupDocs.Comparison для .NET поддерживаются на всех основных платформах и операционных системах. Перед выполнением приведенного ниже кода убедитесь, что в вашей системе установлены следующие предварительные компоненты.
        * Операционные системы: Microsoft Windows, Linux, MacOS
        * Среды разработки: Microsoft Visual Studio, Xamarin, MonoDevelop
        * Фреймворки: .NET Framework, .NET Standard, .NET Core, Mono
        * Получите последнюю версию GroupDocs.Comparison для .NET, загруженную с [NuGet](https://www.nuget.org/packages/groupdocs.comparison).
    code: |
        ```cs
        // Сравните несколько документов с локального диска
        using (Comparer comparer = new Comparer("source.html")
        {
        	comparer.Add("target1.html");
            comparer.Add("target2.html");
            comparer.Add("target3.html");
            comparer.Compare("result.html"); // Создать результирующий файл с указанным именем
        }
        // Сравните несколько документов из потока
        using (Comparer comparer = new Comparer(File.OpenRead("source.html"))
        {
        	comparer.Add(File.OpenRead("target1.html"));
            comparer.Add(File.OpenRead("target2.html"));
            comparer.Add(File.OpenRead("target3.html"));
            comparer.Compare(File.Create("result.html")); // Создать результирующий файл с указанным именем
        }
        ```
############################# Demos ############################
demos:
    enable: true
    title: "Живые демонстрации сравнения файлов HTML"
    content: |
        Обнаружьте различия между файлами HTML прямо сейчас, посетив [живые демонстрации](https://products.groupdocs.app/comparison/family). 
        Живая демонстрация имеет следующие преимущества
############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-html"
          title: "О формате файла HTML"
          content: |
            HTML (Hyper Text Markup Language) — это расширение для веб-страниц, созданных для отображения в браузерах. HTML, известный как язык Интернета, развивался с учетом новых требований к информации, которая должна отображаться как часть веб-страниц. Последний вариант известен как HTML 5, что дает большую гибкость для работы с языком. HTML-страницы либо принимаются с сервера, на котором они размещены, либо также могут быть загружены из локальной системы. Каждая HTML-страница состоит из HTML-элементов, таких как формы, текст, изображения, анимация, ссылки и т. д. Эти элементы представлены такими тегами, как img, a, p и некоторыми другими, где каждый тег имеет начало и конец. Он также может встраивать приложения, написанные на языках сценариев, таких как JavaScript и таблицы стилей (CSS), для общего представления макета.
          link: "https://docs.fileformat.com/web/html/"
############################# More Formats ############################
more_formats:
    enable: true
    title: "Сравнение других форматов файлов"
    content: |
        API сравнения мультиформатных документов и изображений для .NET. Анализируйте различия между документами одного формата без использования каких-либо внешних инструментов.
    format: 
        # format loop
        - name: "Сравнить файлы PDF"
          link: "/comparison/net/pdf/"
          description: "Adobe Portable Document Format"
        # format loop
        - name: "Сравнить файлы DOC"
          link: "/comparison/net/doc/"
          description: "Документ Microsoft Word"
        # format loop
        - name: "Сравнить файлы DOCM"
          link: "/comparison/net/docm/"
          description: "Документ Microsoft Word с поддержкой макросов"
        # format loop
        - name: "Сравнить файлы DOCX"
          link: "/comparison/net/docx/"
          description: "Документ Microsoft Word с открытым XML"
        # format loop
        - name: "Сравнить файлы DOT"
          link: "/comparison/net/dot/"
          description: "Шаблон документа Microsoft Word"
        # format loop
        - name: "Сравнить файлы DOTM"
          link: "/comparison/net/dotm/"
          description: "Шаблон Microsoft Word с поддержкой макросов"
        # format loop
        - name: "Сравнить файлы DOTX"
          link: "/comparison/net/dotx/"
          description: "Шаблон документа Word Open XML"
        # format loop
        - name: "Сравнить файлы RTF"
          link: "/comparison/net/rtf/"
          description: "Расширенный текстовый формат файла"
        # format loop
        - name: "Сравнить файлы TXT"
          link: "/comparison/net/txt/"
          description: "Формат обычного текстового файла"
        # format loop
        - name: "Сравнить файлы XLS"
          link: "/comparison/net/xls/"
          description: "Формат двоичного файла Microsoft Excel"
        # format loop
        - name: "Сравнить файлы XLSX"
          link: "/comparison/net/xlsx/"
          description: "Электронная таблица Microsoft Excel Open XML"
        # format loop
        - name: "Сравнить файлы XLTM"
          link: "/comparison/net/xltm/"
          description: "Шаблон Microsoft Excel с поддержкой макросов"
        # format loop
        - name: "Сравнить файлы XLSM"
          link: "/comparison/net/xlsm/"
          description: "Электронная таблица Microsoft Excel с поддержкой макросов"
        # format loop
        - name: "Сравнить файлы XLSB"
          link: "/comparison/net/xlsb/"
          description: "Двоичный файл электронной таблицы Microsoft Excel"
        # format loop
        - name: "Сравнить файлы CSV"
          link: "/comparison/net/csv/"
          description: "Файл значений, разделенных запятыми"
        # format loop
        - name: "Сравнить файлы PPT"
          link: "/comparison/net/ppt/"
          description: "Презентация PowerPoint"
        # format loop
        - name: "Сравнить файлы PPS"
          link: "/comparison/net/pps/"
          description: "Слайд-шоу Microsoft PowerPoint"
        # format loop
        - name: "Сравнить файлы PPTX"
          link: "/comparison/net/pptx/"
          description: "Презентация PowerPoint Open XML"
        # format loop
        - name: "Сравнить файлы PPSX"
          link: "/comparison/net/ppsx/"
          description: "Слайд-шоу PowerPoint Open XML"
        # format loop
        - name: "Сравнить файлы POT"
          link: "/comparison/net/pot/"
          description: "Шаблон Microsoft PowerPoint"
        # format loop
        - name: "Сравнить файлы POTX"
          link: "/comparison/net/potx/"
          description: "Открытый XML-шаблон Microsoft PowerPoint"
        # format loop
        - name: "Сравнить файлы ODS"
          link: "/comparison/net/ods/"
          description: "Открыть электронную таблицу документов"
        # format loop
        - name: "Сравнить файлы ODP"
          link: "/comparison/net/odp/"
          description: "Формат файла презентации OpenDocument"
        # format loop
        - name: "Сравнить файлы OTP"
          link: "/comparison/net/otp/"
          description: "Шаблон графика происхождения"
        # format loop
        - name: "Сравнить файлы ODT"
          link: "/comparison/net/odt/"
          description: "Открыть текст документа"
        # format loop
        - name: "Сравнить файлы OTT"
          link: "/comparison/net/ott/"
          description: "Открыть шаблон документа"
        # format loop
        - name: "Сравнить файлы VST"
          link: "/comparison/net/vst/"
          description: "Microsoft Visio 2003-2010 XML-чертеж"
        # format loop
        - name: "Сравнить файлы TIFF"
          link: "/comparison/net/tiff/"
          description: "Формат файла изображения с тегами"
        # format loop
        - name: "Сравнить файлы JPEG"
          link: "/comparison/net/jpeg/"
          description: "Изображение в формате JPEG"
        # format loop
        - name: "Сравнить файлы PNG"
          link: "/comparison/net/png/"
          description: "Портативная сетевая графика"
        # format loop
        - name: "Сравнить файлы GIF"
          link: "/comparison/net/gif/"
          description: "Графический файл формата обмена"
        # format loop
        - name: "Сравнить файлы BMP"
          link: "/comparison/net/bmp/"
          description: "Формат растрового файла"
        # format loop
        - name: "Сравнить файлы MHT"
          link: "/comparison/net/mht/"
          description: "HTML-пантомима"
        # format loop
        - name: "Сравнить файлы MHTML"
          link: "/comparison/net/mhtml/"
          description: "MIME-инкапсуляция совокупного HTML"
        # format loop
        - name: "Сравнить файлы MSG"
          link: "/comparison/net/msg/"
          description: "Сообщение электронной почты Microsoft Outlook"
        # format loop
        - name: "Сравнить файлы EML"
          link: "/comparison/net/eml/"
          description: "Сообщение электронной почты"
        # format loop
        - name: "Сравнить файлы EMLX"
          link: "/comparison/net/emlx/"
          description: "Файл электронной почты Apple Mail"
        # format loop
        - name: "Сравнить файлы ONE"
          link: "/comparison/net/one/"
          description: "Майкрософт OneNote"
        # format loop
        - name: "Сравнить файлы VSD"
          link: "/comparison/net/vsd/"
          description: "Чертеж Microsoft Visio 2003-2010"
        # format loop
        - name: "Сравнить файлы VSDX"
          link: "/comparison/net/vsdx/"
          description: "Рисование Microsoft Visio"
        # format loop
        - name: "Сравнить файлы VSS"
          link: "/comparison/net/vss/"
          description: "Трафарет Microsoft Visio 2003-2010"
        # format loop
        - name: "Сравнить файлы VST"
          link: "/comparison/net/vst/"
          description: "Шаблон Microsoft Visio 2003-2010"
        # format loop
        - name: "Сравнить файлы VDX"
          link: "/comparison/net/vdx/"
          description: "Microsoft Visio 2003-2010 XML-чертеж"
        # format loop
        - name: "Сравнить файлы CS"
          link: "/comparison/net/cs/"
          description: "Язык CSharp"
        # format loop
        - name: "Сравнить файлы Java"
          link: "/comparison/net/java/"
          description: "Язык Java"
        # format loop
        - name: "Сравнить файлы CPP"
          link: "/comparison/net/cpp/"
          description: "Язык С++"
        # format loop
        - name: "Сравнить файлы JS"
          link: "/comparison/net/js/"
          description: "Язык JavaScript"
        # format loop
        - name: "Сравнить файлы PY"
          link: "/comparison/net/py/"
          description: "Язык Python"
        # format loop
        - name: "Сравнить файлы RB"
          link: "/comparison/net/rb/"
          description: "Рубиновый язык"
############################# Back to top ###############################
back_to_top:
    enable: true
---
