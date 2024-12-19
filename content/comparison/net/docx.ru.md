
---
############################# Static ############################
layout: "format"
date:  2024-12-19T07:49:50
draft: false
lang: ru
format: Docx
product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "Сравните MS Word DOCX с C# и .NET"
head_description: "Сравнение DOCX с помощью GroupDocs.Comparison for .NET. Подробный отчет с выделенными изменениями между DOCX документами. Используйте наш API вместе с C#."

############################# Header ############################
title: "Сравнение MS Word DOCX с приложениями C# .NET" 
description: "API .NET, предназначенный для сравнения документов, обнаруживает и сообщает о любых различиях в файлах MS Word. Создавайте приложения на основе C#, ASP .NET, VB .NET или .NET Core, чтобы получить преимущества. Получайте подробные отчеты, добавляя несколько строк кода."
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
       Просматривайте изменения в своих DOCX документах с помощью удобного отчета по вашим .NET проектам. Кроме того, получайте информацию о стилях, фигурах и другом содержимом и объединяйте DOCX файлы в новый. Преимущества GroupDocs.Comparison for .NET API можно привнести в ваши проекты всего за пару строк кода. Используйте наше программное обеспечение без сторонних разработчиков.

############################# Steps ############################
steps:
    enable: true
    title: "Сравнительные отчеты файлов MS Word DOCX с помощью .NET и C#"
    content: |
      Составьте отчет о различиях для DOCX файлов, используя [GroupDocs.Comparison](https://products.groupdocs.com/comparison/net/)
      
      1. Загрузите пакет GroupDocs.Comparison for .NET с сайта [Nuget](https://www.nuget.org/packages/GroupDocs.Comparison) и установите его
      2. Создайте экземпляр объекта Comparer и передайте путь к DOCX
      3. Добавьте DOCX файлы для сравнения
      4. Получите отчет с информацией о различиях
   
    code:
      platform: "net"
      copy_title: "Копировать"
      result_enable: true
      result_link: "/examples/comparison/comparison_result.pdf"
      result_title: "Пример результата"
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

        // Отчет об изменениях в файлах DOCX

        // Создание Comparer для обработки документов
        using (Comparer comparer = new Comparer("source.docx"))
        {
            // Добавление хотя бы один файл для сравнения
        	comparer.Add("file_to_compare_1.docx");
            comparer.Add("file_to_compare_2.docx");
            comparer.Add("file_to_compare_3.docx");

            // Получение результата
            comparer.Compare("result.docx"); 
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
    title: "Сравнение DOCX с C# приложениями"
    exclude: "DOCX"
    description: "GroupDocs.Comparison for .NET преимущества контрольных версий популярных форматов файлов. Быстро и легко собирайте информацию о MS Word документах."
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