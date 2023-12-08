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
head_title: "API сравнения документов C# .NET | Сравнить и объединить PDF-файлы, Word Excel, Интернет и текст"
head_description: "API сравнения документов C# .NET. Сравнивайте и объединяйте PDF Word DOC DOCX, электронные таблицы Excel, PPT, PPTX, HTML, EMLX MSG, VSDX, DXF DWG и форматы файлов изображений."

############################# Header ############################
title: ".NET API для сравнения файлов"
description: "Разрабатывайте приложения с использованием API сравнения документов .NET для проверки и сравнения файлов на предмет различий в содержимом и стиле."
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
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
        product: "GroupDocs.Comparison"
        platform: ".NET"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "Обзор"

            # button loop
            - link: "#features"
              text: "Функции"

            # button loop
            - link: "#support"
              text: "Поддерживать"

            # button loop
            - link: "https://products.groupdocs.app/comparison"
              text: "Живая демонстрация"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "Цены"

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
      - title: "Что такое GroupDocs.Comparison for .NET"
        content: "API GroupDocs.Comparison for .NET — быстрое и надежное решение, готовое к использованию при создании приложений для поиска и выделения различий между документами одного или разных форматов на C#, ASP.NET или других технологиях, связанных с программной платформой .NET."

      # more_overview_loop
      - title: "Поддерживаемые форматы"
        content: "Библиотека GroupDocs.Comparison поддерживает обнаружение различий как в содержимом, так и в стиле текста между популярными форматами изображений и документов, такими как PDF, HTML, электронная почта Outlook, документы Microsoft Office Word, электронные таблицы Excel, презентации PowerPoint, OneNote, диаграммы Visio, тексты, png , gif и bmp изображения, а также сотни других форматов."
        
      # more_overview_loop
      - title: "Возможности сравнения"
        content: "Сравнение может быть выполнено для обнаружения изменений в содержании слов, абзацев, таблиц или диаграмм и их стилей и предоставит вам документ сравнения, в котором перечислены сводные различия, их количество и типологическая принадлежность. GroupDocs.Comparison for .NET может легко извлекать основную информацию об исходном документе, сравнивать и сохранять простые, защищенные паролем и зашифрованные документы различных форматов через файл или поток данных."
        
      # more_overview_loop
      - title: "Документация и примеры"
        content: "Уже есть много документации по использованию библиотеки Comparison на разных платформах с примерами кода, поэтому вам не придется долго думать, как работать с GroupDocs.Comparison для API .NET в вашем приложении."
        
      # more_overview_loop
      - title: "Совместимость"
        content: "Вы можете использовать GroupDocs.Comparison for .NET для создания приложений в любой среде разработки, ориентированной на платформу .NET. Он совместим со всеми языками на основе .NET и поддерживает популярные операционные системы (Windows, Linux, MacOS), на которые вы можете установить платформы Mono или .NET (включая .NET Core)."
    examples:
      enable: true
      
    more_feature:
      # more_feature_loop
      - title: "Легко сравнивайте документы с помощью .NET API"
        content: |
          API GroupDocs.Comparison for .NET предоставляет вам простой и эффективный способ сравнения файлов. Ниже приведен пример, показывающий, как сравнить два документа DOCX с помощью C#:  

          ```cs
          // Исходный и целевой файлы для сравнения
          string source = @"source.docx";
          string target = @"target.docx";
          Comparer comparer = new Comparer();
          // Сравните два документа
          ICompareResult result = comparer.Compare(source, target, new ComparisonSettings());
          ```
      # more_feature_loop
      - title: "Выберите уровень детализации для сравнения"
        content: "С помощью GroupDocs.Comparison for .NET вы можете указать степень сравнения документов. Вы можете выбрать низкий (сравнивать текст пословно с точностью для сетки изображения = 50), средний (сравнивать текст посимвольно с точностью для сетки изображения = 100) или высокий (сравнивать текст посимвольно с точностью для сетки изображения = 100). 150)."

      # more_feature_loop
      - title: "Поддержка сравнения стилей текста"
        content: |
          GroupDocs.Comparison for .NET предлагает функцию сравнения стилей текста.  

          Во время сравнения слов и символов документов можно сравнивать имя шрифта, размер шрифта, цвет шрифта, стиль шрифта (жирный, курсив, подчеркивание, прописные буквы, гиперссылка) и цвет подчеркивания (если применимо), чтобы найти различия.  

          При сравнении абзацев вы можете сравнивать такие стили, как выравнивание абзаца, отступ (отступ слева и справа), интервал между абзацами (пробел после, пробел перед), отступ первой строки и межстрочный интервал.  

          GroupDocs.Comparison for .NET также поддерживает сравнение других разделов страницы, где это применимо, таких как расстояние от нижнего колонтитула, высота и ориентация страницы, поля (слева, справа, сверху и снизу), ширина линии границы и цвет границы.  
      
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Ниже приведен обзор GroupDocs.Comparison for .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Обзор"
          content: |
            * Сравнение документов
            * Сравнение HTML-файлов
            * PDF-сравнение
            * Сравнение диаграмм
            * Сравнить содержимое файла
            * Сравнение стилей текста
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison for .NET поддерживает все популярные [форматы файлов документов](https://docs.groupdocs.com/comparison/net/supported-document-formats/), включая: Microsoft Office, PDF, изображения и многие другие. .
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
            - title: "Другие форматы"
              content: |
                * **Языки программирования**: [CS](https://products.groupdocs.com/comparison/net/cs/), [Java](https://products.groupdocs.com/comparison/net/java/), [CPP](https://products.groupdocs.com/comparison/net/cpp/), [JS](https://products.groupdocs.com/comparison/net/js/), [PY](https://products.groupdocs.com/comparison/net/py/), [RB](https://products.groupdocs.com/comparison/net/rb/), [PL](https://products.groupdocs.com/comparison/net/pl/), [ASM](https://products.groupdocs.com/comparison/net/asm/), [GROOVY](https://products.groupdocs.com/comparison/net/groovy/), [JSON](https://products.groupdocs.com/comparison/net/json/), [PHP](https://products.groupdocs.com/comparison/net/php/), [SQL](https://products.groupdocs.com/comparison/net/sql/), [LOG](https://products.groupdocs.com/comparison/net/log/), [DIFF](https://products.groupdocs.com/comparison/net/diff/), [LESS](https://products.groupdocs.com/comparison/net/less/), [SCALA](https://products.groupdocs.com/comparison/net/scala/)
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
          GroupDocs.Comparison for .NET поддерживает следующие операционные системы, платформы и менеджеры пакетов:
      
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Операционные системы"
              content: |
                * Windows Desktop
                * Windows Server
                * Windows Azure
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "Поддерживаемые платформы"
              content: |
                * .NET Framework 2.0 или выше
                * Mono Framework 1.2 или выше
                * .NET Standard 2.0
                * .NET Core 2.0

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Менеджер пакетов"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Среды разработки"
              content: |
                * Microsoft Visual Studio
                * Xamarin.Android
                * Xamarin.IOS
                * Xamarin.Mac
                * MonoDevelop

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Comparison for .NET Возможности"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "[Определите различия в контенте и стилях шрифтов](https://docs.groupdocs.com/comparison/net/compare-documents/)"

      # feature loop
      - icon: "fas fa-eye"
        content: "[Сохраните сводный отчет обо всех различиях, обнаруженных после сравнения файлов.](https://docs.groupdocs.com/comparison/net/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-bolt"
        content: "[Применить или отклонить изменения после анализа различий и экспортировать результирующий файл](https://docs.groupdocs.com/comparison/net/accept-or-reject-detected-changes/)"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "[Поддержка функции Microsoft Word «Отслеживание изменений» при сравнении файлов Word](https://docs.groupdocs.com/comparison/net/show-revisions/)"

      # feature loop
      - icon: "fas fa-code"
        content: "[Уникально выявляйте изменения, происходящие в каждом сравниваемом документе](https://docs.groupdocs.com/comparison/net/get-list-of-changes/)"

      # feature loop
      - icon: "fas fa-cloud"
        content: "[Чтение и отправка документов через потоки](https://docs.groupdocs.com/comparison/net/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "[Лицензирование по счетчику: выставление счетов в зависимости от использования API](https://docs.groupdocs.com/comparison/net/licensing-and-evaluation-limitations/)"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "[Сравните несколько исходных документов с одним целевым документом](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/)"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "[Сравнить определенные страницы файлов Word друг с другом — принять или отклонить все изменения в одном документе Word.](https://docs.groupdocs.com/comparison/net/accept-or-reject-detected-changes/)"

      # feature loop
      - icon: "fas fa-border-all"
        content: "[Объедините до 3 документов Word и сравните формулы, используемые в файлах Word.](https://docs.groupdocs.com/comparison/net/how-to-merge-source-code-files/)"

      # feature loop
      - icon: "fas fa-wrench"
        content: "[Получить информацию о документах из filePath](https://docs.groupdocs.com/comparison/net/get-file-info/)"

      # feature loop
      - icon: "fas fa-columns"
        content: "[Сохранить результат сравнения HTML в виде изображений](https://docs.groupdocs.com/comparison/net/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-file-word"
        content: "[Возможность показать или скрыть удаленный контент](https://docs.groupdocs.com/comparison/net/show-gap-lines/)"

      # feature loop
      - icon: "fas fa-envelope"
        content: "[Возможность включить или выключить сравнение стилей документов.](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fas fa-print"
        content: "[Укажите строки для пометки вставленных, удаленных элементов и элементов изменения стиля в документе сравнения](https://docs.groupdocs.com/comparison/net/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "[Укажите разделитель слов и цвет шрифта для стилизации сравниваемого текста](https://docs.groupdocs.com/comparison/net/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-lock"
        content: "[Рассчитать правильные координаты изменений в PDF, Word, слайдах и диаграммах PowerPoint](https://docs.groupdocs.com/comparison/net/get-changes-coordinates/)"

      # feature loop
      - icon: "fas fa-file-code"
        content: "[Сравнить файлы, защищенные паролем](https://docs.groupdocs.com/comparison/net/how-to-compare-password-protected-files/)"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "[Сравните заголовки диаграмм в электронных таблицах – создайте диаграмму в полученных файлах ячеек.](https://docs.groupdocs.com/comparison/net/how-to-compare-spreadsheet-or-tables/)"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "[Автоматически изменять размер автофигур в результирующем файле документа Cells.](https://docs.groupdocs.com/comparison/net/how-to-compare-spreadsheet-or-tables/)"

      # feature loop
      - icon: "fas fa-heading"
        content: "[Доступ к странице подробной сводки для обнаружения изменений между исходными и целевыми файлами документов](https://docs.groupdocs.com/comparison/net/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "[Сравните самые популярные файлы языков программирования и сценариев](https://docs.groupdocs.com/comparison/net/get-supported-document-formats/)"

      # feature loop
      - icon: "fas fa-cube"
        content: "[Сравнение нескольких (более двух) документов PDF, Word, Excel, диаграмм, электронной почты, текстовых документов и документов OneNote.](https://docs.groupdocs.com/comparison/net/compare-multiple-documents-with-specific-compare-settings/)"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "[Сравните верхний и нижний колонтитулы поддерживаемых форматов файлов](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "[Сравните закладки, переменные и пользовательские свойства форматов документов Word](https://docs.groupdocs.com/comparison/net/compare-bookmarks-in-word/)"

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison предлагает API-интерфейсы просмотра документов для других популярных сред разработки."

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