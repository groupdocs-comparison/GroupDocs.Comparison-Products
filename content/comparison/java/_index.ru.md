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
head_description: "Java Сравнение документов API для сравнения и объединения файлов Word Excel PPTX OpenOffice, Web, PDF, AutoCAD и других форматов. Сравнивайте документы с отслеживанием изменений."

############################# Header ############################
title: "Java API для сравнения и объединения документов"
description: "Создавайте приложения Java для эффективного сравнения содержимого и стиля текста для проверки различий во всех стандартных отраслевых форматах файлов документов и изображений.."
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
        image: "/border/groupdocs-comparison-java.svg"
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
              text: "Support"

            # button loop
            - link: "https://products.groupdocs.app/comparison"
              text: "Live Demo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/java"
              text: "Pricing"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# Обзор ############################
overview:
    enable: true
    content: |
      GroupDocs.Comparison for Java — наиболее гибкий и простой в использовании API, помогающий разрабатывать приложения для сравнения документов в среде Java. Средство проверки различий и API слияния документов позволяют обнаруживать изменения и различия в содержании, а также в стиле текста между похожими форматами документов. Он поддерживает сравнение всех стандартных форматов документов, таких как PDF, HTML, Microsoft Office Word, электронные таблицы Excel, презентации PowerPoint, электронные письма Outlook, диаграммы Visio, OpenDocument, AutoCAD и изображения. С помощью функции отслеживания изменений сводка различий между исходным и целевым документом будет представлена в комплексном сравнительном документе. GroupDocs.Comparison for Java API позволяет извлекать и сохранять простые, защищенные паролем, а также зашифрованные документы как в файле, так и в потоке.
        
      GroupDocs.Comparison for Java не требует установки в системе какого-либо внешнего программного обеспечения. Он совместим со всеми версиями Java и поддерживает популярные операционные системы (Windows, линукс, MacOS), способные запускать среду выполнения Java.

    tabs:
      enable: true     
      
      ## TAB ONE ##
      tab_one:
        description: |
          Ниже приводится обзор GroupDocs.Comparison для Java:

        right:
          enable: true
          icon: "fab fa-html5"
          title: "Обзор"
          content: |
            * Сравните содержимое и стили
            * Получить сводку сравнения
            * Принять/отклонить изменения в Word
            * Объединить и сравнить 3 файла Word
            * Поддержка потоков
            * Определение типа файла через поток
            * Сравните защищенные файлы
            * Сравните зашифрованные файлы
            * Сохранить сравнение как изображение
            * Сравните определенную страницу в Word
            * Сравните водяной знак в PDF
            * Применить/отменить изменения
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison для Java поддерживает все популярные [форматы файлов документов](https://docs.groupdocs.com/comparison/java/supported-document-formats/), включая: Microsoft Office, изображения, диаграммы и многие другие.

        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
                * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX, XLAM, SXC, SpreadsheetML
                * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM
                * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
                * **Outlook:** MSG, EML, EMLX, PST, OST
                * **OneNote:** ONE

        right:
          enable: true
          table:
            # table loop
            - title: "Другие форматы"
              content: |
                * **Языки программирования**: CS, Java, CPP, JS, PY, RB, PL, ASM, GROOVY, JSON, ActionScript, PHP, SQL, LOG, DIFF, LESS, SCALA
                * **OpenDocument**: ODT, OTT, ODS, ODP, OTP
                * **Портативный**: PDF, MOBI
                * **AutoCAD**: DXF, DWG
                * **Электронная почта**: EML, EMLX, MSG
                * **Изображения**: JPEG, BMP, PNG, GIF, DCM, DICOM, DjVu
                * **Интернет**: HTM, HTML, MHTML
                * **Текст**: TXT

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Comparison for Java поддерживает следующие Операционные системы, Frameworks & Менеджер пакетовs:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Операционные системы"
              content: |
                * Рабочий стол Microsoft Windows
                * Сервер Microsoft Windows
                * линукс
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "Поддерживаемые платформы"
              content: |
                * Java 7 (1.7) и выше

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-cogs"
              title: "Среды разработки"
              content: |
                * NetBeans
                * IntelliJ ИДЕЯ
                * Затмение
            # table loop
            - icon: "fas fa-tools"
              title: "Инструмент автоматизации сборки"
              content: |
                * Мавен

############################# Функции ############################
features:
    enable: true
    title: "GroupDocs.Comparison для функций Java"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Сравните и определите изменения как в содержании, так и в стиле текста"

      # feature loop
      - icon: "fas fa-eye"
        content: "Сохранить сводный список сравнения сравниваемых документов"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Сравните определенные страницы документов Word"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Объединяйте до 3 файлов Microsoft Word для сравнения с поддержкой функции «Отслеживание изменений»."

      # feature loop
      - icon: "fas fa-code"
        content: "Легко определить, какие изменения происходят из какого документа во время сравнения"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Поддержка чтения исходных документов и отправки результирующего документа через потоки"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Определить тип формата файла при извлечении из потока"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Сравните документы, защищенные паролем"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Сохранить результат сравнения как изображение"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Сравните различные форматы файлов в виде изображения"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Сравните водяные знаки в документах PDF"

      # feature loop
      - icon: "fas fa-columns"
        content: "Сравните документы из файла или потока и отправьте результирующий документ через поток или файл"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Принять или отменить изменения после сравнения файлов Word, PDF или Excel"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Сравните зашифрованные документы через файл или поток"

      # feature loop
      - icon: "fas fa-print"
        content: "Вариант лицензирования по счетчику для операций сравнения"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Выделение текста для отмеченных изменений при сравнении документов PDF, Word, Excel, PowerPoint и Note"

      # feature loop
      - icon: "fas fa-lock"
        content: "Расчет правильных координат изменений в PDF, слайдах и диаграммах PowerPoint"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Сравните несколько (более двух) PDF, Excel, OneNote, диаграмм, электронных писем и текстовых документов"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Сравните верхний и нижний колонтитулы поддерживаемых форматов файлов"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Сравните документы и сохраните страницы документов разных форматов в виде изображений"

    more_feature:
      # more_feature_loop
      - title: "Легко сравнивайте документы с помощью Java API"
        content: |
          С помощью GroupDocs.Comparison for Java API вы можете легко сравнивать документы поддерживаемых форматов, чтобы найти различия между ними. В следующем примере показано, как сравнить два документа Microsoft Word с помощью Java:
          
          ```java
          try (Comparer comparer = new Comparer("D:\\source.pdf")) {
              comparer.add("D:\\target.pdf");
              comparer.compare("D:\\result.pdf");
          }
          ```
      # more_feature_loop
      - title: "Укажите уровень детализации сравнения"
        content: "GroupDocs.Comparison для Java позволяет сравнивать документы на трех уровнях глубины. Вы можете установить низкую интенсивность сравнения (сравнивать текст пословно с точностью для сетки изображения = 50), среднюю (сравнивать текст посимвольно с точностью для сетки изображения = 100) или высокую (сравнивать текст посимвольно с точностью для изображения). сетка = 150)."

      # more_feature_loop
      - title: "Сравнить стиль текста"
        content: |
            Помимо содержимого документа, GroupDocs.Comparison for Java API позволяет также сравнивать стиль текста. Имя шрифта, размер, цвет, стиль (полужирный, курсив, подчеркивание, капитель и гиперссылки) и, если применимо, нижний цвет также можно сравнить, чтобы проверить разницу между сравниваемыми документами, в то время как слова и символы сравниваются. Для сравнения абзацев также можно сравнить выравнивание, отступ (левый отступ, правый отступ), интервалы (пробел после, пробел перед), отступ первой строки и межстрочный интервал. Точно так же, где это применимо, другие разделы страницы также можно сравнивать с помощью API GroupDocs.Comparison для Java. Разделы включают расстояние нижнего колонтитула, поля страницы (левое, правое, верхнее и нижнее), высоту страницы, ориентацию страницы, цвет границы и ширину строки».

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison предлагает API для просмотра документов для других популярных сред разработки."

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for .NET"
          image: "/border/groupdocs-comparison-net.svg"
          product: "GroupDocs.Comparison"
          platform: ".NET"
          link: "/comparison/net/"

############################# Back to top ###############################
back_to_top:
  enable: true
---
