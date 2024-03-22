
---
############################# Static ############################
layout: "format"
date:  2024-03-22T13:27:45
draft: false
lang: ru
format: Xlsx
product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "Сравнение электронных таблиц MS Excel"
head_description: "API GroupDocs.Comparison for .NET упрощает просмотр различий и анализ XLSX электронных таблиц. Поддерживается C# .NET."

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
       Просматривайте изменения в электронных таблицах XLSX с помощью удобного отчета в ваших .NET проектах. Кроме того, получайте информацию о стилях, фигурах и другом содержимом и объединяйте электронные таблицы XSLX в новый документ. Интегрируйте GroupDocs.Comparison for .NET API в свои проекты, используя всего несколько строк кода. Используйте наше программное обеспечение без использования сторонних библиотек.

############################# Steps ############################
steps:
    enable: true
    title: "Создавайте сравнительные отчеты MS Excel XLSX, используя C#"
    content: |
      Создайте отчет о различиях для XLSX файлов, используя [GroupDocs.Comparison](https://products.groupdocs.com/comparison/net/)
      
      1. Загрузите и установите пакет GroupDocs.Comparison for .NET из [Nuget](https://www.nuget.org/packages/GroupDocs.Comparison)
      2. Создайте экземпляр объекта Comparer, указав путь к файлу XLSX
      3. Добавьте XLSX таблицы для сравнения
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

        // Создание экземпляра объекта Comparer для обработки электронных таблиц
        using (Comparer comparer = new Comparer("source.xlsx"))
        {
            // Включение хотя бы одного файла для сравнения
        	comparer.Add("file_to_compare_1.xlsx");
            comparer.Add("file_to_compare_2.xlsx");
            comparer.Add("file_to_compare_3.xlsx");

            // Получение результата сравнения
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
    title: "Сравнение MS Excel электронных таблиц в C# приложениях"
    exclude: "XLSX"
    description: "Изучите преимущества GroupDocs.Comparison for .NET для управления версиями XLSX документов. Быстро и легко собирайте информацию из MS Excel электронных таблиц для дальнейшего анализа."
    items: 
        # format loop 1
        - name: "Сравнение PDF файлов"
          format: "PDF"
          link: "/comparison/net/pdf/"
          description: "Формат документа Adobe Portable"

        # format loop 2
        - name: "Сравнение DOCX файлов"
          format: "DOCX"
          link: "/comparison/net/docx/"
          description: "Microsoft Word Open XML документ"

        # format loop 3
        - name: "Сравнение RTF файлов"
          format: "RTF"
          link: "/comparison/net/rtf/"
          description: "Формат файла с расширенным текстовым форматом"

        # format loop 4
        - name: "Сравнение TXT файлов"
          format: "TXT"
          link: "/comparison/net/txt/"
          description: "Формат файла в виде простого текста"

        # format loop 5
        - name: "Сравнение XLSX файлов"
          format: "XLSX"
          link: "/comparison/net/xlsx/"
          description: "Открытая электронная таблица XML от Майкрософт Excel"

        # format loop 6
        - name: "Сравнение CSV-файлов"
          format: "CSV"
          link: "/comparison/net/csv/"
          description: "Файл значений, разделенных запятыми"

        # format loop 7
        - name: "Сравнение PPTX файлов"
          format: "PPTX"
          link: "/comparison/net/pptx/"
          description: "PowerPoint Открытая презентация XML"

        # format loop 8
        - name: "Сравнение ODS файлов"
          format: "ODS"
          link: "/comparison/net/ods/"
          description: "Open Document Электронная таблица"

        # format loop 9
        - name: "Сравнение файлов ODP"
          format: "ODP"
          link: "/comparison/net/odp/"
          description: "OpenDocument Формат файла презентации"

        # format loop 10
        - name: "Сравнение файлов ODT"
          format: "ODT"
          link: "/comparison/net/odt/"
          description: "Open Document Текст"

        # format loop 11
        - name: "Сравнение файлов JPEG"
          format: "JPEG"
          link: "/comparison/net/jpeg/"
          description: "JPEG Изображение"

        # format loop 12
        - name: "Сравнение PNG файлов"
          format: "PNG"
          link: "/comparison/net/png/"
          description: "Portable Сетевая графика"

        # format loop 13
        - name: "Сравнение GIF файлов"
          format: "GIF"
          link: "/comparison/net/gif/"
          description: "Файл формата графического обмена"

        # format loop 14
        - name: "Сравнение BMP файлов"
          format: "BMP"
          link: "/comparison/net/bmp/"
          description: "Формат растрового файла"

        # format loop 15
        - name: "Сравнение HTML-файлов"
          format: "HTML"
          link: "/comparison/net/html/"
          description: "Язык гипертекстовой разметки"

        # format loop 16
        - name: "Сравнение MSG файлов"
          format: "MSG"
          link: "/comparison/net/msg/"
          description: "Сообщение электронной почты Microsoft Outlook"

        # format loop 17
        - name: "Сравнение ONE файлов"
          format: "ONE"
          link: "/comparison/net/one/"
          description: "Майкрософт OneNote"

        # format loop 18
        - name: "Сравнение VSDX файлов"
          format: "VSDX"
          link: "/comparison/net/vsdx/"
          description: "Чертеж Майкрософт Visio"

        # format loop 19
        - name: "Сравнение файлов CS"
          format: "CS"
          link: "/comparison/net/cs/"
          description: "Язык программирования CSharp"

        # format loop 20
        - name: "Сравнение Java файлов"
          format: "Java"
          link: "/comparison/net/java/"
          description: "Файлы кода на языке Java"
          
        # format loop 21
        - name: "Сравнение файлов CPP"
          format: "CPP"
          link: "/comparison/net/cpp/"
          description: "Файлы кода на языке C++"
---