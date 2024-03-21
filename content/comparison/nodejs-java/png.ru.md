
---
############################# Static ############################
layout: "format"
date:  2024-03-21T15:26:29
draft: false
lang: ru
format: Png
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

############################# Head ############################
head_title: "API JavaScript для сравнения PNG изображений."
head_description: "Библиотека GroupDocs.Comparison for Node.js via Java представляет подробные отчеты о различиях на изображениях в формате PNG."

############################# Header ############################
title: "PNG сравнение изображений Node.js приложений через Java" 
description: "Воспользуйтесь преимуществами API Node.js для отслеживания изменений в PNG файлах в JavaScript приложениях. Простое и быстрое получение подробных отчетов."
subtitle: "Решение для сравнения файлов" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Скачать бесплатно NPM"
      link: "https://releases.groupdocs.com/comparison/nodejs-java/"
      
############################# About ############################
about:
    enable: true
    title: "Откройте возможности API GroupDocs.Comparison for Node.js via Java"
    link: "/comparison/nodejs-java/"
    link_title: "Узнайте больше"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       Составляйте полные отчеты о любых изменениях в различных версиях PNG документов вашими JavaScript приложениями. Нет необходимости в стороннем программном обеспечении. Будьте в курсе любых изменений в версиях вашего изображения PNG.

############################# Steps ############################
steps:
    enable: true
    title: "Составьте PNG отчетов о различиях изображений в JavaScript"
    content: |
      Отслеживайте изменения PNG документов, используя отчеты, предоставленные [GroupDocs.Comparison](https://products.groupdocs.com/comparison/nodejs-java/)
      
      1. Установите пакет GroupDocs.Comparison с помощью [NPM](https://www.npmjs.com/package/@groupdocs/groupdocs.comparison)
      2. Используйте конструктор класса Comparer с путем к PNG
      3. Добавьте несколько PNG s для сравнения
      4. Получите отчет, содержащий информацию о различиях
   
    code:
      platform: "net"
      copy_title: "Копировать"
      install:
        command: "npm i @groupdocs/groupdocs.comparison"
        copy_tip: "нажмите, чтобы скопировать"
        copy_done: "скопировал"
      links:
        #  loop
        - title: "Больше примеров"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java"
        #  loop
        - title: "Документация"
          link: "https://docs.groupdocs.com/comparison/nodejs-java/"
          
      content: |
        ```javascript {style=abap}

        // Проверьте несколько файлов, чтобы увидеть, насколько они похожи или отличаются

        // Создайте объект Comparer и передайте ему первый файл в качестве входных данных
        const comparer = new groupdocs.comparison.Comparer('first.png');

        // Добавить больше файлов
        comparer.add('second.png');
        comparer.add('third.png');

        // Получите окончательный отчет
        await comparer.compare('report_full.png');

        console.log('\nDocuments compared successfully.\nCheck output.');
        
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "Готовы начать?"
  description: "Попробуйте функции GroupDocs.Comparison бесплатно или запросите лицензию"
  items:
    #  loop
    - title: "NPM скачать"
      link: "https://releases.groupdocs.com/comparison/nodejs-java/"
      color: "red"
        #  loop
    - title: "Лицензирование"
      link: "https://purchase.groupdocs.com/pricing/comparison/java/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Сопоставляйте изображения в популярных форматах, таких как PNG, используя JavaScript"
    exclude: "PNG"
    description: "Используйте GroupDocs.Comparison for Node.js via Java, чтобы получить информацию о PNG различиях между изображениями. Подробные отчеты помогут вам быть в курсе любых изменений важных данных."
    items: 
        # format loop 1
        - name: "Сравните PDF файлы"
          format: "PDF"
          link: "/comparison/nodejs-java/pdf/"
          description: "Формат документа Adobe Portable"

        # format loop 2
        - name: "Сравните DOCX файлы"
          format: "DOCX"
          link: "/comparison/nodejs-java/docx/"
          description: "Открыть XML-документ Microsoft Word"

        # format loop 3
        - name: "Сравните RTF файлы"
          format: "RTF"
          link: "/comparison/nodejs-java/rtf/"
          description: "Формат файла с расширенным текстовым форматом"

        # format loop 4
        - name: "Сравните TXT файлы"
          format: "TXT"
          link: "/comparison/nodejs-java/txt/"
          description: "Формат файла в виде простого текста"

        # format loop 5
        - name: "Сравните XLSX файлы"
          format: "XLSX"
          link: "/comparison/nodejs-java/xlsx/"
          description: "Открытая электронная таблица XML от Майкрософт Excel"

        # format loop 6
        - name: "Сравните CSV-файлы"
          format: "CSV"
          link: "/comparison/nodejs-java/csv/"
          description: "Файл значений, разделенных запятыми"

        # format loop 7
        - name: "Сравните PPTX файлы"
          format: "PPTX"
          link: "/comparison/nodejs-java/pptx/"
          description: "PowerPoint Открытая презентация XML"

        # format loop 8
        - name: "Сравните ODS файлы"
          format: "ODS"
          link: "/comparison/nodejs-java/ods/"
          description: "Open Document Электронная таблица"

        # format loop 9
        - name: "Сравните файлы ODP"
          format: "ODP"
          link: "/comparison/nodejs-java/odp/"
          description: "OpenDocument Формат файла презентации"

        # format loop 10
        - name: "Сравните файлы ODT"
          format: "ODT"
          link: "/comparison/nodejs-java/odt/"
          description: "Open Document Текст"

        # format loop 11
        - name: "Сравните файлы JPEG"
          format: "JPEG"
          link: "/comparison/nodejs-java/jpeg/"
          description: "JPEG Изображение"

        # format loop 12
        - name: "Сравните PNG файлы"
          format: "PNG"
          link: "/comparison/nodejs-java/png/"
          description: "Portable Сетевая графика"

        # format loop 13
        - name: "Сравните GIF файлы"
          format: "GIF"
          link: "/comparison/nodejs-java/gif/"
          description: "Файл формата графического обмена"

        # format loop 14
        - name: "Сравните BMP файлы"
          format: "BMP"
          link: "/comparison/nodejs-java/bmp/"
          description: "Формат растрового файла"

        # format loop 15
        - name: "Сравнение HTML-файлов"
          format: "HTML"
          link: "/comparison/nodejs-java/html/"
          description: "Язык гипертекстовой разметки"

        # format loop 16
        - name: "Сравните MSG файлы"
          format: "MSG"
          link: "/comparison/nodejs-java/msg/"
          description: "Сообщение электронной почты Microsoft Outlook"

        # format loop 17
        - name: "Сравните ONE файлы"
          format: "ONE"
          link: "/comparison/nodejs-java/one/"
          description: "Майкрософт OneNote"

        # format loop 18
        - name: "Сравните VSDX файлы"
          format: "VSDX"
          link: "/comparison/nodejs-java/vsdx/"
          description: "Чертеж Майкрософт Visio"

        # format loop 19
        - name: "Сравните файлы CS"
          format: "CS"
          link: "/comparison/nodejs-java/cs/"
          description: "Язык программирования CSharp"

        # format loop 20
        - name: "Сравните Java файлы"
          format: "Java"
          link: "/comparison/nodejs-java/java/"
          description: "Java Язык"
          
        # format loop 21
        - name: "Сравнение файлов CPP"
          format: "CPP"
          link: "/comparison/nodejs-java/cpp/"
          description: "Язык C++"
---