
---
############################# Static ############################
layout: "format"
date:  2024-03-21T15:26:23
draft: false
lang: ru
format: Xlsx
product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "Сравнение электронных таблиц MS Excel"
head_description: "API GroupDocs.Comparison for .NET упрощает проверку различий и анализ XLSX электронных таблиц. Поддерживается C# .NET."

############################# Header ############################
title: "Используйте технологии C# для сравнения XLSX электронных таблиц" 
description: "API .NET, созданный для сравнения различных типов документов, выявляет различия в файлах MS Excel и сообщает о них. Создавайте приложения, используя C#, ASP .NET, VB .NET или .NET Core, чтобы использовать их преимущества. Получайте подробные отчеты при минимальной реализации кода."
subtitle: "Решение для сравнения документов" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Скачать бесплатно Nuget"
      link: "https://releases.groupdocs.com/comparison/net/"
      
############################# About ############################
about:
    enable: true
    title: "Изучите возможности API GroupDocs.Comparison for .NET"
    link: "/comparison/net/"
    link_title: "Узнайте больше"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       Обнаруживайте изменения в электронных таблицах XLSX с помощью удобной отчетности по вашим .NET проектам. Кроме того, получайте информацию о стилях, фигурах и другом содержимом и объединяйте электронные таблицы XSLX в новый документ. Интегрируйте GroupDocs.Comparison for .NET API в свои проекты, используя всего несколько строк кода. Используйте наше программное обеспечение без участия сторонних разработчиков.

############################# Steps ############################
steps:
    enable: true
    title: "Создайте сравнительные отчеты MS Excel XLSX, используя C#"
    content: |
      Создайте отчет о различиях для XLSX файлов, используя [GroupDocs.Comparison](https://products.groupdocs.com/comparison/net/)
      
      1. Загрузите и установите пакет GroupDocs.Comparison for .NET из [Nuget](https://www.nuget.org/packages/GroupDocs.Comparison)
      2. Создайте экземпляр объекта Comparer, указав путь к файлу XLSX
      3. Включите XLSX таблицы для сравнения
      4. Получите сравнительный отчет, содержащий информацию о различиях
   
    code:
      platform: "net"
      copy_title: "Копировать"
      install:
        command: "dotnet add package GroupDocs.Comparison"
        copy_tip: "нажмите, чтобы скопировать"
        copy_done: "скопировал"
      links:
        #  loop
        - title: "Больше примеров"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET"
        #  loop
        - title: "Документация"
          link: "https://docs.groupdocs.com/comparison/net/"
          
      content: |
        ```csharp {style=abap}

        // Создайте отчет об изменениях в XLSX файлах

        // Создайте экземпляр объекта Comparer для обработки электронных таблиц
        using (Comparer comparer = new Comparer("source.xlsx"))
        {
            // Включите хотя бы один файл для сравнения
        	comparer.Add("file_to_compare_1.xlsx");
            comparer.Add("file_to_compare_2.xlsx");
            comparer.Add("file_to_compare_3.xlsx");

            // Проанализируйте результат сравнения
            comparer.Compare("result.xlsx"); 
        }
        
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "Готовы начать?"
  description: "Попробуйте функции GroupDocs.Comparison бесплатно или запросите лицензию"
  items:
    #  loop
    - title: "Nuget скачать"
      link: "https://releases.groupdocs.com/comparison/net/"
      color: "red"
        #  loop
    - title: "Лицензирование"
      link: "https://purchase.groupdocs.com/pricing/comparison/net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Сравнение MS Excel электронных таблиц для C# приложений"
    exclude: "XLSX"
    description: "Изучите преимущества GroupDocs.Comparison for .NET для управления версиями XLSX документов. Быстро и легко собирайте информацию из MS Excel электронных таблиц для дальнейшего анализа."
    items: 
        # format loop 1
        - name: "Сравните PDF файлы"
          format: "PDF"
          link: "/comparison/net/pdf/"
          description: "Формат документа Adobe Portable"

        # format loop 2
        - name: "Сравните DOCX файлы"
          format: "DOCX"
          link: "/comparison/net/docx/"
          description: "Открыть XML-документ Microsoft Word"

        # format loop 3
        - name: "Сравните RTF файлы"
          format: "RTF"
          link: "/comparison/net/rtf/"
          description: "Формат файла с расширенным текстовым форматом"

        # format loop 4
        - name: "Сравните TXT файлы"
          format: "TXT"
          link: "/comparison/net/txt/"
          description: "Формат файла в виде простого текста"

        # format loop 5
        - name: "Сравните XLSX файлы"
          format: "XLSX"
          link: "/comparison/net/xlsx/"
          description: "Открытая электронная таблица XML от Майкрософт Excel"

        # format loop 6
        - name: "Сравните CSV-файлы"
          format: "CSV"
          link: "/comparison/net/csv/"
          description: "Файл значений, разделенных запятыми"

        # format loop 7
        - name: "Сравните PPTX файлы"
          format: "PPTX"
          link: "/comparison/net/pptx/"
          description: "PowerPoint Открытая презентация XML"

        # format loop 8
        - name: "Сравните ODS файлы"
          format: "ODS"
          link: "/comparison/net/ods/"
          description: "Open Document Электронная таблица"

        # format loop 9
        - name: "Сравните файлы ODP"
          format: "ODP"
          link: "/comparison/net/odp/"
          description: "OpenDocument Формат файла презентации"

        # format loop 10
        - name: "Сравните файлы ODT"
          format: "ODT"
          link: "/comparison/net/odt/"
          description: "Open Document Текст"

        # format loop 11
        - name: "Сравните файлы JPEG"
          format: "JPEG"
          link: "/comparison/net/jpeg/"
          description: "JPEG Изображение"

        # format loop 12
        - name: "Сравните PNG файлы"
          format: "PNG"
          link: "/comparison/net/png/"
          description: "Portable Сетевая графика"

        # format loop 13
        - name: "Сравните GIF файлы"
          format: "GIF"
          link: "/comparison/net/gif/"
          description: "Файл формата графического обмена"

        # format loop 14
        - name: "Сравните BMP файлы"
          format: "BMP"
          link: "/comparison/net/bmp/"
          description: "Формат растрового файла"

        # format loop 15
        - name: "Сравнение HTML-файлов"
          format: "HTML"
          link: "/comparison/net/html/"
          description: "Язык гипертекстовой разметки"

        # format loop 16
        - name: "Сравните MSG файлы"
          format: "MSG"
          link: "/comparison/net/msg/"
          description: "Сообщение электронной почты Microsoft Outlook"

        # format loop 17
        - name: "Сравните ONE файлы"
          format: "ONE"
          link: "/comparison/net/one/"
          description: "Майкрософт OneNote"

        # format loop 18
        - name: "Сравните VSDX файлы"
          format: "VSDX"
          link: "/comparison/net/vsdx/"
          description: "Чертеж Майкрософт Visio"

        # format loop 19
        - name: "Сравните файлы CS"
          format: "CS"
          link: "/comparison/net/cs/"
          description: "Язык программирования CSharp"

        # format loop 20
        - name: "Сравните Java файлы"
          format: "Java"
          link: "/comparison/net/java/"
          description: "Java Язык"
          
        # format loop 21
        - name: "Сравнение файлов CPP"
          format: "CPP"
          link: "/comparison/net/cpp/"
          description: "Язык C++"
---