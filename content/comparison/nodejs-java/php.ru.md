
---
############################# Static ############################
layout: "format"
date:  2024-03-22T13:27:48
draft: false
lang: ru
format: Php
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

############################# Head ############################
head_title: "Сравните PHP с помощью библиотеки JavaScript."
head_description: "GroupDocs.Comparison for Node.js via Java - библиотека для создания подробных отчетов о различиях в файлах PHP для Node.js приложений."

############################# Header ############################
title: "Сравнение ваших PHP файлов в Node.js" 
description: "Библиотека сравнения документов на основе Node.js позволяет собирать и отображать данные о любых различиях в файлах PHP. Повысьте производительность своих решений при выполнении задач сравнения файлов с помощью GroupDocs.Comparison."
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
    title: "Изучите особенности GroupDocs.Comparison for Node.js via Java"
    link: "/comparison/nodejs-java/"
    link_title: "Узнайте больше"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison for Node.js via Java — это API, который помогает сравнивать изображения и документы в одном формате. Он может находить различия в абзацах, словах, символах, фигурах и стилях текста в сравниваемых документах. Можно объединить эти изменения и сохранить их как окончательный документ. Он отлично работает с PDF документами, Word документами, Excel листами, PowerPoint слайдами, Visio диаграммами, Outlook электронными письмами, HTML, рисунками и различными типами изображений — и все это без дополнительных инструментов.

############################# Steps ############################
steps:
    enable: true
    title: "Как выполнить сравнение файлов PHP с помощью Node.js."
    content: |
      Всего несколько шагов достаточно для получения отчета о сравнении PHP файлов с помощью [GroupDocs.Comparison](https://products.groupdocs.com/comparison/nodejs-java/)
      
      1. Установите GroupDocs.Comparison for Node.js via Java, используя [NPM](https://www.npmjs.com/package/@groupdocs/groupdocs.comparison)
      2. Создайте экземпляр Comparer и укажите путь к первому из файлов в формате PHP
      3. Добавьте еще один файл PHP в Comparer
      4. Получите отчет с точным описанием различий
   
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

        // Сравните несколько файлов, чтобы увидеть, насколько они похожи или отличаются

        // Создание объекта Comparer и передача ему первого файла в качестве входных данных
        const comparer = new groupdocs.comparison.Comparer('source.php');

        // Добавление еще файлов для сравнения
        comparer.add('file_v1.php');
        comparer.add('file_2023.php');

        // Получение окончательного отчета
        await comparer.compare('report_new.php');

        console.log('\nFiles are compared.\nCheck result.');

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
    title: "Сравните популярные типы документов с помощью JavaScript"
    exclude: "PHP"
    description: "Наш API Node.js позволяет сравнивать документы в разных форматах. Отслеживайте изменения в документах, обрабатывая их с помощью нашего простого и мощного API."
    items: 
        # format loop 1
        - name: "Сравнение PDF файлов"
          format: "PDF"
          link: "/comparison/nodejs-java/pdf/"
          description: "Формат документа Adobe Portable"

        # format loop 2
        - name: "Сравнение DOCX файлов"
          format: "DOCX"
          link: "/comparison/nodejs-java/docx/"
          description: "Microsoft Word Open XML документ"

        # format loop 3
        - name: "Сравнение RTF файлов"
          format: "RTF"
          link: "/comparison/nodejs-java/rtf/"
          description: "Формат файла с расширенным текстовым форматом"

        # format loop 4
        - name: "Сравнение TXT файлов"
          format: "TXT"
          link: "/comparison/nodejs-java/txt/"
          description: "Формат файла в виде простого текста"

        # format loop 5
        - name: "Сравнение XLSX файлов"
          format: "XLSX"
          link: "/comparison/nodejs-java/xlsx/"
          description: "Открытая электронная таблица XML от Майкрософт Excel"

        # format loop 6
        - name: "Сравнение CSV-файлов"
          format: "CSV"
          link: "/comparison/nodejs-java/csv/"
          description: "Файл значений, разделенных запятыми"

        # format loop 7
        - name: "Сравнение PPTX файлов"
          format: "PPTX"
          link: "/comparison/nodejs-java/pptx/"
          description: "PowerPoint Открытая презентация XML"

        # format loop 8
        - name: "Сравнение ODS файлов"
          format: "ODS"
          link: "/comparison/nodejs-java/ods/"
          description: "Open Document Электронная таблица"

        # format loop 9
        - name: "Сравнение файлов ODP"
          format: "ODP"
          link: "/comparison/nodejs-java/odp/"
          description: "OpenDocument Формат файла презентации"

        # format loop 10
        - name: "Сравнение файлов ODT"
          format: "ODT"
          link: "/comparison/nodejs-java/odt/"
          description: "Open Document Текст"

        # format loop 11
        - name: "Сравнение файлов JPEG"
          format: "JPEG"
          link: "/comparison/nodejs-java/jpeg/"
          description: "JPEG Изображение"

        # format loop 12
        - name: "Сравнение PNG файлов"
          format: "PNG"
          link: "/comparison/nodejs-java/png/"
          description: "Portable Сетевая графика"

        # format loop 13
        - name: "Сравнение GIF файлов"
          format: "GIF"
          link: "/comparison/nodejs-java/gif/"
          description: "Файл формата графического обмена"

        # format loop 14
        - name: "Сравнение BMP файлов"
          format: "BMP"
          link: "/comparison/nodejs-java/bmp/"
          description: "Формат растрового файла"

        # format loop 15
        - name: "Сравнение HTML-файлов"
          format: "HTML"
          link: "/comparison/nodejs-java/html/"
          description: "Язык гипертекстовой разметки"

        # format loop 16
        - name: "Сравнение MSG файлов"
          format: "MSG"
          link: "/comparison/nodejs-java/msg/"
          description: "Сообщение электронной почты Microsoft Outlook"

        # format loop 17
        - name: "Сравнение ONE файлов"
          format: "ONE"
          link: "/comparison/nodejs-java/one/"
          description: "Майкрософт OneNote"

        # format loop 18
        - name: "Сравнение VSDX файлов"
          format: "VSDX"
          link: "/comparison/nodejs-java/vsdx/"
          description: "Чертеж Майкрософт Visio"

        # format loop 19
        - name: "Сравнение файлов CS"
          format: "CS"
          link: "/comparison/nodejs-java/cs/"
          description: "Язык программирования CSharp"

        # format loop 20
        - name: "Сравнение Java файлов"
          format: "Java"
          link: "/comparison/nodejs-java/java/"
          description: "Файлы кода на языке Java"
          
        # format loop 21
        - name: "Сравнение файлов CPP"
          format: "CPP"
          link: "/comparison/nodejs-java/cpp/"
          description: "Файлы кода на языке C++"
---