
---
############################# Static ############################
layout: "format"
date:  2024-03-22T13:27:45
draft: false
lang: ru
format: Jpeg
product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "API GroupDocs.Comparison for .NET для сравнения JPEG файлов"
head_description: "GroupDocs.Comparison for .NET представляет собой мощный API для сбора данных о различиях на JPEG изображениях для использования в C# и .NET"

############################# Header ############################
title: "Сравнение изменений на JPEG изображениях с технологиями .NET" 
description: "Быстрый и простой сбор и представление в виде отчета данных об изменениях в JPEG файлах, предоставляемых API GroupDocs.Comparison for .NET. Наше программное обеспечение может расширить возможности бизнес-решений на основе C#, ASP .NET, VB .NET и .NET Core для получения полезных данных."
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
       API GroupDocs.Comparison for .NET предоставляет широкие функциональные возможности для сравнения JPEG изображений. Полученные отчеты содержат данные о любых различиях на выбранных изображениях. Использование нашего программного обеспечения в ваших C# проектах не требует использования других библиотек. Просто добавьте несколько строк кода и получите мощный инструмент для достижения ваших целей.

############################# Steps ############################
steps:
    enable: true
    title: "Как сравнить JPEG изображения в C#"
    content: |
      Сравнивайте содержимое JPEG файлов с помощью [GroupDocs.Comparison](https://products.groupdocs.com/comparison/net/)
      
      1. Получите GroupDocs.Comparison for .NET из [Nuget](https://www.nuget.org/packages/GroupDocs.Comparison) и добавьте в проект
      2. Используйте конструктор объектов Comparer, и задайте путь к изображению JPEG
      3. Задайте другое JPEG изображение для анализа
      4. Получите отчет сравнения, сохраненный на локальном диске
   
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

        // Составьте отчет о различиях в JPEG изображениях

        // Передача пути к основному файлу конструктору Comparer
        using (Comparer comparer = new Comparer("source.jpeg"))
        {
            // Указание пути к другим JPEG изображениям
        	comparer.Add("file_to_compare_1.jpeg");
            comparer.Add("file_to_compare_2.jpeg");
            comparer.Add("file_to_compare_3.jpeg");

            // Созранение полученного отчета в файл
            comparer.Compare("result.jpeg"); 
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
    title: "Сравнение JPEG изображений с C# .NET"
    exclude: "JPEG"
    description: "Анализируйте информацию о любых изменениях в файлах JPEG с помощью продукта GroupDocs.Comparison for .NET."
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