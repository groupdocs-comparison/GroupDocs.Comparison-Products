
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: ru
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Drop-down ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"
    # supported_platforms loop
    - title: "Java"
      tag: "java"
    # supported_platforms loop
    - title: "Node.js"
      tag: "nodejs-java"
    # supported_platforms loop
    - title: "Python"
      tag: "python-net"

############################# Head ############################
head_title: "Java Библиотека сравнения документов| diff checker"
head_description: "Native Java Программное обеспечение для сравнения стиля и содержимого документов. Сравните документы разных форматов, чтобы выявить различия."

############################# Header ############################
title: "Сравните и проверьте различия между файлами с помощью API Java"
description: "Разработайте Java приложения с гибко настраиваемой библиотекой сравнения документов для сравнения аналогичных форматов документов, включая файлы, их содержимое и стиль текста."
words:
  for: "для"

actions:
  main: "Бесплатная загрузка Maven"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/"
  alt: "Лицензирование"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/java/"
  title: "Готовы начать?"
  description: "Попробуйте функции GroupDocs.Comparison бесплатно или запросите лицензию"

release:
  title: "Выпущена версия {0}"
  notes: "Узнайте, что нового"
  downloads: "Загрузки"

code:
  title: "Сравнение DOCX файлов в Java"
  more: "Больше примеров"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
  install: |
    <dependency>
      <groupId>com.groupdocs</groupId>
      <artifactId>groupdocs-comparison</artifactId>
      <version>{0}</version>
    </dependency>
  content: |
    ```java {style=abap}  
    // Укажите исходный документ
    try (Comparer comparer = new Comparer("source.docx"))
    {    
      // Добавьте один или несколько целевых документов
      comparer.add("target.docx");

      // Укажите параметры сравнения
      CompareOptions options = new CompareOptions();
      options.setShowRevisions(false);

      // Сравните файлы и сохраните результат
      final comparer.compare("result.docx", options);
    }    
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison с первого взгляда"
  description: "API для сравнения различий между документами в Java приложениях"
  features:
    # feature loop
    - title: "Сравнение файлов в Java"
      content: "Обнаруживайте изменения между исходным и целевым файлами на уровне абзацев, слов и символов. Определите изменения стиля и форматирования, такие как полужирный шрифт, курсив, подчеркивание, зачеркивание, типы шрифтов и т. д."

    # feature loop
    - title: "Большое количество поддерживаемых форматов"
      content: "С помощью API GroupDocs.Comparison вы можете легко сравнивать документы нескольких поддерживаемых форматов. Сюда входят PDF, HTML, электронная почта, Microsoft Office Word документы, Excel электронные таблицы, PowerPoint презентации, OneNote, Visio диаграммы, тексты, JPEG, PNG, GIF и BMP изображения, а также многие другие форматы."

    # feature loop
    - title: "Легко применяйте или отклоняйте изменения"
      content: "Любое различие между сравниваемыми документами может быть применено или отклонено, а затем экспортировано в выходной документ."

    # feature loop
    - title: "Сравнительный сводный отчет"
      content: "Создайте сводный отчет, в котором перечислены все изменения в сравниваемых документах."

############################# Platforms ############################
platforms:
  enable: true
  title: "Независимость платформы"
  description: "GroupDocs.Comparison for Java поддерживает следующие операционные системы, фреймворки и менеджеры пакетов"
  items:
    # platform loop
    - title: "Amazon"
      image: "amazon"
    # platform loop
    - title: "Docker"
      image: "docker"
    # platform loop
    - title: "Azure"
      image: "azure"
    # platform loop
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "Maven"
      image: "maven"

############################# File formats ############################
formats:
  enable: true
  title: "Поддерживаемые форматы файлов"
  description: |
    GroupDocs.Comparison for Java поддерживает операции со следующими [форматами файлов](https://docs.groupdocs.com/comparison/java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### форматы Microsoft Office и OpenDocument
        * **Word:** DOCX, DOC, DOCM,DOT, DOTM, DOTX, RTX, RTF, TXT
        * **Excel:** XLSX, XLS, XLT, XLTM, XLSB, XLSM
        * **PowerPoint:** PPTX, PPT, POT, POTX, PPS, PPSX
        * **Outlook:** EML, EMLX, MSG
        * **OneNote:** ONE
        * **OpenDocument:** ODT, ODP, OTP, ODS, OTT
        * **Фиксированный макет страницы:** PDF        
    # group loop
    - color: "blue"
      content: |
        ### Изображения, графика и диаграммы
        * **Растровые изображения:** BMP, GIF, JPG, JPEG, PNG
        * **Медицинская визуализация:** DICOM
        * **Microsoft Visio:** VSDX, VSD, VSS, VST, VDX
        * **AutoCAD Drawing:** DWG, DXF
      # group loop
    - color: "red"
      content: |
        ### Другой
        * **Текст:** TXT
        * **Языки программирования:** CS, Java, CPP, JS, PY, RB, PL, ASM, GROOVY, JSON, PHP, SQL, LOG, DIFF, LESS, SCALA
        * **Веб:** HTM, HTML, MHT, MHTML
        * **Электронные книги:** MOBI, DjVu
        * **Значения, разделенные разделителями:** CSV

############################# Features ############################
features:
  enable: true
  title: "Характеристики GroupDocs.Comparison"
  description: "Сравнивайте PDF и офисные документы, изображения и другие форматы с легкостью"

  items:
    # feature loop
    - icon: "compare"
      title: "Простое в использовании сравнение документов"
      content: "Анализируйте и выявляйте различия между двумя документами."

    # feature loop
    - icon: "note-stack"
      title: "Сравнение нескольких документов"
      content: "Одновременно анализируйте и выделяйте различия в нескольких документах."

    # feature loop
    - icon: "stacks"
      title: "Поддерживаемые форматы"
      content: "Совместимость с более чем 50 широко используемыми форматами документов из разных категорий."

    # feature loop
    - icon: "rule"
      title: "Принятие или отклонение изменений"
      content: "Четкая визуализация выявленных изменений с возможностью принятия или отклонения изменений."

    # feature loop
    - icon: "preview"
      title: "Создание предварительных просмотров"
      content: "Возможность сохранения результатов сравнения в виде предварительного просмотра изображений."

    # feature loop
    - icon: "two-pager"
      title: "Сравнение контента"
      content: "Тщательное сравнение текстового содержимого на разных уровнях, включая построчный анализ, анализ абзацев, слов и символов с акцентом на изменения."

    # feature loop
    - icon: "format_color_text"
      title: "Сравнение стилей"
      content: "Возможность обнаруживать и выделять изменения в элементах форматирования и стиля."

    # feature loop
    - icon: "folder-managed"
      title: "Настройка метаданных"
      content: "Возможность сохранить метаданные из исходных или целевых файлов или разрешить пользовательские настройки метаданных."

    # feature loop
    - icon: "lock"
      title: "Защита паролем"
      content: "Упрощает анализ документов, защищенных паролем, и обеспечивает защиту полученных документов паролем."

    # feature loop
    - icon: "select"
      title: "Сравнение определенных страниц"
      content: "При необходимости загрузите и сравните определенные разделы или страницы документа."

    # feature loop
    - icon: "speaker-notes"
      title: "Отображение комментариев"
      content: "Возможность отображать или скрывать комментарии при загрузке исходного документа."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Образцы кода"
  description: "Некоторые варианты использования типичных операций GroupDocs.Comparison for Java"
  items:
    # code sample loop
    - title: "Сравнение документов, защищенных паролем."
      content: |
        Чтобы [сравнить документы, защищенные паролем](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/), вам необходимо указать его при загрузке документов:
        {{< landing/code title="Как сравнить документы, защищенные паролем.">}}
        ```java {style=abap}
        // Загрузить исходный документ и укажите его пароль
        try (Comparer comparer = new Comparer("source.docx", new LoadOptions("1234")))
        {
            // Загрузить целевой документ и укажите его пароль
            comparer.add("target.docx", new LoadOptions("5678"));
        
            // Сохранить результат сравнения в указанном файле
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Сравнение нескольких PDF документов."
      content: |
        GroupDocs.Comparison позволяет [сравнивать более двух документов](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/). Операция почти такая же, как и при сравнении двух файлов. Вам просто нужно добавить больше целевых файлов в класс `comparer`.
        {{< landing/code title="Как сравнить три или более документов.">}}
        ```java {style=abap}   
        // Загрузить исходный документ
        try (Comparer comparer = new Comparer("source.docx") 
        {
            // Задать второй файл для сравнения
            comparer.add("target2.docx");

            // Задать третий файл для сравнения
            comparer.add("target3.docx");

            // Сохранить результат сравнения в указанном файле
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---

