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
head_title: "API сравнения документов Java | Сравните текст и стиль PDF Word Excel HTML"
head_description: "API сравнения документов Java для сравнения и объединения файлов Word Excel PPTX OpenOffice, Web, PDF, AutoCAD и других форматов. Сравнивайте документы с отслеживанием изменений."

############################# Header ############################
title: "Java API для сравнения файлов"
description: "Создавайте приложения Java для эффективного сравнения содержимого файлов на предмет различий во всех стандартных форматах документов и изображений."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Скачать бесплатную пробную версию"
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
            - link: "https://purchase.groupdocs.com/pricing/comparison/java"
              text: "Цены"

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
      - title: "Что такое GroupDocs.Comparison for Java"
        content: "GroupDocs.Comparison for Java — это наиболее гибкий и простой в использовании API, который поможет вам разрабатывать приложения для сравнения документов в среде Java. Средство проверки различий и API слияния документов позволяют обнаруживать изменения и различия в содержании, а также в стиле текста между схожими форматами документов."

      # more_overview_loop
      - title: "Поддерживаемые форматы"
        content: "Библиотека GroupDocs.Comparison поддерживает обнаружение различий как в содержимом, так и в стиле текста между популярными форматами изображений и документов, такими как PDF, HTML, электронная почта Outlook, документы Microsoft Office Word, электронные таблицы Excel, презентации PowerPoint, OneNote, диаграммы Visio, тексты, png , gif и bmp изображения, а также сотни других форматов."
        
      # more_overview_loop
      - title: "Возможности сравнения"
        content: "Сравнение может быть выполнено для обнаружения изменений в содержании слов, абзацев, таблиц или диаграмм и их стилей и предоставит вам документ сравнения, в котором перечислены сводные различия, их количество и типологическая принадлежность. GroupDocs.Comparison for Java может легко извлекать основную информацию об исходном документе, сравнивать и сохранять простые, защищенные паролем и зашифрованные документы различных форматов через файл или поток данных."
        
      # more_overview_loop
      - title: "Документация и примеры"
        content: "Уже есть много документации по использованию библиотеки Comparison на разных платформах с примерами кода, поэтому вам не придется долго думать, как работать с GroupDocs.Comparison для API Java в вашем приложении."
        
      # more_overview_loop
      - title: "Совместимость"
        content: "GroupDocs.Comparison for Java не требует установки какого-либо внешнего программного обеспечения в системе. Он совместим со всеми версиями Java и поддерживает популярные операционные системы (Windows, Linux, MacOS), поддерживающие среду выполнения Java."
    examples:
      enable: true
      
    more_feature:
      # more_feature_loop
      - title: "Легко сравнивайте документы с помощью Java API"
        content: |
          С помощью API GroupDocs.Comparison for Java вы можете легко сравнивать документы поддерживаемых форматов, чтобы находить различия между ними. В следующем примере показано, как сравнить два документа Microsoft Word с помощью Java:
          
          ```java
          try (Comparer comparer = new Comparer("D:\\source.pdf")) {
              comparer.add("D:\\target.pdf");
              comparer.compare("D:\\result.pdf");
          }
          ```
      # more_feature_loop
      - title: "Укажите уровень детализации сравнения"
        content: "GroupDocs.Comparison for Java позволяет сравнивать документы на трех уровнях. Вы можете установить низкую интенсивность сравнения (сравнивать текст пословно с точностью для сетки изображения = 50), среднюю (сравнивать текст посимвольно с точностью для сетки изображения = 100) или высокую (сравнивать текст посимвольно с точностью для изображения). сетка = 150)."

      # more_feature_loop
      - title: "Сравнить стиль текста"
        content: "Помимо содержимого документа, API GroupDocs.Comparison for Java также позволяет сравнивать стиль текста.

        Название шрифта, размер, цвет, стиль (жирный, курсив, подчеркивание, маленькие прописные буквы и гиперссылки) и, если применимо, нижний цвет также можно сравнить, чтобы проверить разницу между сравниваемыми документами при сравнении слов и символов.  

        Для сравнения абзацев также можно сравнить выравнивание, отступ (отступ слева, отступ справа), интервал (пробел после, пробел перед), отступ первой строки и межстрочный интервал.  

        Аналогичным образом, где это применимо, другие разделы страницы также можно сравнивать через API GroupDocs.Comparison for Java. Разделы включают расстояние нижнего колонтитула, поля страницы (слева, справа, сверху и снизу), высоту страницы, ориентацию страницы, цвет границы и ширину линии."
      
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Ниже приведен обзор GroupDocs.Comparison for Java:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Обзор"
          content: |
            * Сравните содержание и стили
            * Получить сравнительную сводку
            * Принять/отклонить изменения в Word
            * Объединить и сравнить файлы из 3 слов
            * Поддержка потоков
            * Обнаружение типа файла через поток
            * Сравнить защищенные файлы
            * Сравнить зашифрованные файлы
            * Сохранить сравнение как изображение
            * Сравнить конкретную страницу в Word
            * Сравнить водяные знаки в PDF
            * Применить/отменить изменения
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison for Java поддерживает все популярные [форматы файлов документов](https://docs.groupdocs.com/comparison/java/supported-document-formats/), включая: Microsoft Office, изображения, диаграммы и многое другое. .
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
            - title: "Другие форматы"
              content: |
                * **Языки программирования**: [CS](https://products.groupdocs.com/comparison/java/cs/), [Java](https://products.groupdocs.com/comparison/java/java/), [CPP](https://products.groupdocs.com/comparison/java/cpp/), [JS](https://products.groupdocs.com/comparison/java/js/), [PY](https://products.groupdocs.com/comparison/java/py/), [RB](https://products.groupdocs.com/comparison/java/rb/), [PL](https://products.groupdocs.com/comparison/java/pl/), [ASM](https://products.groupdocs.com/comparison/java/asm/), [GROOVY](https://products.groupdocs.com/comparison/java/groovy/), [JSON](https://products.groupdocs.com/comparison/java/json/), [PHP](https://products.groupdocs.com/comparison/java/php/), [SQL](https://products.groupdocs.com/comparison/java/sql/), [LOG](https://products.groupdocs.com/comparison/java/log/), [DIFF](https://products.groupdocs.com/comparison/java/diff/), [LESS](https://products.groupdocs.com/comparison/java/less/), [SCALA](https://products.groupdocs.com/comparison/java/scala/)
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
          GroupDocs.Comparison for Java поддерживает следующие операционные системы, платформы и менеджеры пакетов:
      
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Операционные системы"
              content: |
                * Microsoft Windows Desktop
                * Microsoft Windows Server
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "Поддерживаемые платформы"
              content: |
                * Java 7 (1.7) или выше

        right:
          enable: true
          table:
            
            # table loop
            - icon: "fas fa-cogs"
              title: "Среды разработки"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse
            # table loop
            - icon: "fas fa-tools"
              title: "Инструмент автоматизации сборки"
              content: |
                * Maven

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Comparison for Java Возможности"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "[Сравните и определите изменения как в содержании, так и в стиле текста](https://docs.groupdocs.com/comparison/java/compare-documents/)"

      # feature loop
      - icon: "fas fa-eye"
        content: "[Сохранить сводный список сравнения сравниваемых документов](https://docs.groupdocs.com/comparison/java/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-bolt"
        content: "[Сравнение определенных страниц документов Word](https://docs.groupdocs.com/comparison/java/accept-or-reject-detected-changes/)"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "[Объедините до 3 файлов Microsoft Word для сравнения с поддержкой «Отслеживать изменения»](https://docs.groupdocs.com/comparison/java/compare-multiple-documents-with-specific-compare-settings/)"

      # feature loop
      - icon: "fas fa-code"
        content: "[Легко определить, какие изменения происходят из какого документа во время сравнения](https://docs.groupdocs.com/comparison/java/get-list-of-changes/)"

      # feature loop
      - icon: "fas fa-cloud"
        content: "[Поддержка чтения исходных документов и отправки результирующего документа через потоки.](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "[Определить тип формата файла при выборке из потока](https://docs.groupdocs.com/comparison/java/get-file-info/)"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "[Сравнить документы, защищенные паролем](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/)"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "[Сохранить результат сравнения как изображение](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-border-all"
        content: "[Сравните различные форматы файлов как изображения](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-wrench"
        content: "[Сравните водяные знаки в PDF-документах](https://docs.groupdocs.com/comparison/java/how-to-spot-photos-differences-in-java-or-kotlin/)"

      # feature loop
      - icon: "fas fa-columns"
        content: "[Сравнить документы из файла или потока и отправить результирующий документ через поток или файл](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-file-word"
        content: "[Принять или отменить изменения после сравнения файлов Word, PDF или Excel](https://docs.groupdocs.com/comparison/java/accept-or-reject-detected-changes/)"

      # feature loop
      - icon: "fas fa-envelope"
        content: "[Сравнить зашифрованные документы через файл или поток](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-print"
        content: "[Вариант дозированного лицензирования для операций сравнения](https://docs.groupdocs.com/comparison/java/evaluation-limitations-and-licensing-of-groupdocs-comparison/)"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "[Выделение текста для отмеченных изменений при сравнении документов PDF, Word, Excel, PowerPoint и Note](https://docs.groupdocs.com/comparison/java/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-lock"
        content: "[Рассчитать правильные координаты изменений в PDF, слайдах и диаграммах PowerPoint](https://docs.groupdocs.com/comparison/java/get-changes-coordinates/)"

      # feature loop
      - icon: "fas fa-file-code"
        content: "[Сравнение нескольких (более двух) PDF-документов, Excel, OneNote, диаграмм, электронных писем и текстовых документов](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/)"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "[Сравните верхний и нижний колонтитулы поддерживаемых форматов файлов](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "[Сравнивайте документы и сохраняйте страницы документов разных форматов в виде изображений](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"


############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison предлагает API-интерфейсы просмотра документов для других популярных сред разработки."

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