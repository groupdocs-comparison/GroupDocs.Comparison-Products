
---
############################# Static ############################
layout: "format"
date:  2024-03-22T13:27:38
draft: false
lang: ru
format: Htm
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "Java HTM API для сравнения документов и файлов"
head_description: "Сравнение HTM файлов в приложениях Java, J2EE, J2SE. Проанализируйте сводку различий в содержании, тексте и стиле."

############################# Header ############################
title: "Сравнение HTM файлов в Java" 
description: "Сравнивайте содержимое HTM файлов в Java. Работайте со списком различий и сохраняйте сравниваемые файлы в одном документе."
subtitle: "Система проверки различий в документах" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Скачать бесплатно в Maven"
      link: "https://releases.groupdocs.com/comparison/java/"
      
############################# About ############################
about:
    enable: true
    title: "Изучите возможности библиотеки GroupDocs.Comparison for Java"
    link: "/comparison/java/"
    link_title: "Узнайте больше"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison for Java — это встроенное программное обеспечение Java, предназначенное для сравнения нескольких изображений и документов одного формата. Оно помогает выявлять различия в абзацах, словах, символах, фигурах и даже стилях текста в сравниваемых документах. Благодаря возможности объединять эти изменения и экспортировать их в окончательный документ, оно облегчает сравнение и объединение PDF документов, Word электронных таблиц, PowerPoint презентаций, Visio диаграмм, Outlook электронных писем, HTML, рисунков и различных форматов файлов изображений, устраняя необходимость во внешних библиотеках.

############################# Steps ############################
steps:
    enable: true
    title: "Как сравнить несколько HTM документов с помощью Java"
    content: |
      Используйте [GroupDocs.Comparison](https://products.groupdocs.com/comparison/java/) для сравнения нескольких HTM файлов и создания отчета с подробным описанием их различий
      
      1. Используйте предпочтительный менеджер пакетов для установки GroupDocs.Comparison for Java из [Maven](https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/)
      2. Создайте экземпляр класса Comparer, задав путь к одному из HTM файлов
      3. Добавьте хотя бы один дополнительный HTM к экземпляру Comparer
      4. Получите подробный итоговый отчет с точным описанием различий
   
    code:
      platform: "net"
      copy_title: "Копировать"
      install:
        command: |
          <dependencies>
            <dependency>
              <groupId>com.groupdocs</groupId>
              <artifactId>groupdocs-comparison</artifactId>
              <version>{0}</version>
            </dependency>
          </dependencies>

          <repositories>
            <repository>
              <id>repository.groupdocs.com</id>
              <name>GroupDocs Repository</name>
              <url>https://repository.groupdocs.com/repo/</url>
            </repository>
          </repositories>
        copy_tip: "нажмите, чтобы скопировать"
        copy_done: "скопировал"
      links:
        #  loop
        - title: "Больше примеров"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
        #  loop
        - title: "Документация"
          link: "https://docs.groupdocs.com/comparison/java/"
          
      content: |
        ```java {style=abap}

        // Проверьте файлы с жесткого диска на наличие различий или сходств

        // Создайте объект Comparer, указав исходный файл
        try (Comparer comparer = new Comparer("source.htm") 
        {
            // Включите дополнительные файлы для сравнения
        	comparer.add("target1.htm");
            comparer.add("target2.htm");

            // В результате получите отчет с указанным именем
            final Path resultPath = comparer.compare("result.htm"); 

            System.out.println("\nDocuments compared successfully.");
        }
        
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "Готовы начать?"
  description: "Попробуйте функции GroupDocs.Comparison бесплатно или запросите лицензию"
  items:
    #  loop
    - title: "Maven скачать"
      link: "https://releases.groupdocs.com/comparison/java/"
      color: "red"
        #  loop
    - title: "Лицензирование"
      link: "https://purchase.groupdocs.com/pricing/comparison/java/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Сравнивайте различные документы, используя Java"
    exclude: "HTM"
    description: "Наши решения Java позволяют сравнивать документы различных форматов. Будьте в курсе изменений в документах и просматривайте результаты в удобном представлении."
    items: 
        # format loop 1
        - name: "Сравнение PDF файлов"
          format: "PDF"
          link: "/comparison/java/pdf/"
          description: "Формат документа Adobe Portable"

        # format loop 2
        - name: "Сравнение DOCX файлов"
          format: "DOCX"
          link: "/comparison/java/docx/"
          description: "Microsoft Word Open XML документ"

        # format loop 3
        - name: "Сравнение RTF файлов"
          format: "RTF"
          link: "/comparison/java/rtf/"
          description: "Формат файла с расширенным текстовым форматом"

        # format loop 4
        - name: "Сравнение TXT файлов"
          format: "TXT"
          link: "/comparison/java/txt/"
          description: "Формат файла в виде простого текста"

        # format loop 5
        - name: "Сравнение XLSX файлов"
          format: "XLSX"
          link: "/comparison/java/xlsx/"
          description: "Открытая электронная таблица XML от Майкрософт Excel"

        # format loop 6
        - name: "Сравнение CSV-файлов"
          format: "CSV"
          link: "/comparison/java/csv/"
          description: "Файл значений, разделенных запятыми"

        # format loop 7
        - name: "Сравнение PPTX файлов"
          format: "PPTX"
          link: "/comparison/java/pptx/"
          description: "PowerPoint Открытая презентация XML"

        # format loop 8
        - name: "Сравнение ODS файлов"
          format: "ODS"
          link: "/comparison/java/ods/"
          description: "Open Document Электронная таблица"

        # format loop 9
        - name: "Сравнение файлов ODP"
          format: "ODP"
          link: "/comparison/java/odp/"
          description: "OpenDocument Формат файла презентации"

        # format loop 10
        - name: "Сравнение файлов ODT"
          format: "ODT"
          link: "/comparison/java/odt/"
          description: "Open Document Текст"

        # format loop 11
        - name: "Сравнение файлов JPEG"
          format: "JPEG"
          link: "/comparison/java/jpeg/"
          description: "JPEG Изображение"

        # format loop 12
        - name: "Сравнение PNG файлов"
          format: "PNG"
          link: "/comparison/java/png/"
          description: "Portable Сетевая графика"

        # format loop 13
        - name: "Сравнение GIF файлов"
          format: "GIF"
          link: "/comparison/java/gif/"
          description: "Файл формата графического обмена"

        # format loop 14
        - name: "Сравнение BMP файлов"
          format: "BMP"
          link: "/comparison/java/bmp/"
          description: "Формат растрового файла"

        # format loop 15
        - name: "Сравнение HTML-файлов"
          format: "HTML"
          link: "/comparison/java/html/"
          description: "Язык гипертекстовой разметки"

        # format loop 16
        - name: "Сравнение MSG файлов"
          format: "MSG"
          link: "/comparison/java/msg/"
          description: "Сообщение электронной почты Microsoft Outlook"

        # format loop 17
        - name: "Сравнение ONE файлов"
          format: "ONE"
          link: "/comparison/java/one/"
          description: "Майкрософт OneNote"

        # format loop 18
        - name: "Сравнение VSDX файлов"
          format: "VSDX"
          link: "/comparison/java/vsdx/"
          description: "Чертеж Майкрософт Visio"

        # format loop 19
        - name: "Сравнение файлов CS"
          format: "CS"
          link: "/comparison/java/cs/"
          description: "Язык программирования CSharp"

        # format loop 20
        - name: "Сравнение Java файлов"
          format: "Java"
          link: "/comparison/java/java/"
          description: "Файлы кода на языке Java"
          
        # format loop 21
        - name: "Сравнение файлов CPP"
          format: "CPP"
          link: "/comparison/java/cpp/"
          description: "Файлы кода на языке C++"
---