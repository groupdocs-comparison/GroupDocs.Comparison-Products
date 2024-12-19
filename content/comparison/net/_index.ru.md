
---
############################# Static ############################
layout: "landing"
date: 2024-12-19T07:50:01
draft: false

lang: ru
product: "Comparison"
product_tag: "comparison"
platform: "Net"
platform_tag: "net"

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
head_title: "C# .NET решение для сравнения документов | diff checker"
head_description: "C# .NET библиотека для сравнения документов: как содержимого документа так и стилей. Сравнивайте документы множества форматов и просматривайте различия между файлами."

############################# Header ############################
title: "Cравнивайте документы легко и быстро в своих решениях C# .NET"
description: "Создавайте C# приложения с помощью нашего гибкого API сравнения документов, который позволяет сравнивать файлы различных форматов документов по содержимому и стилю."
words:
  for: "для"

actions:
  main: "Скачать бесплатно на NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Comparison"
  alt: "Лицензирование"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/net/"
  title: "Готовы начать?"
  description: "Попробуйте функции GroupDocs.Comparison бесплатно или запросите лицензию"

release:
  title: "Выпущена версия {0}"
  notes: "Узнайте, что нового"
  downloads: "Загрузки"

code:
  title: "Сравнение DOCX файлов в C#"
  more: "Больше примеров"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET"
  install: "dotnet add package GroupDocs.Comparison"
  content: |
    ```csharp {style=abap}   
    // Укажите исходный документ
    using (Comparer comparer = new Comparer("source.docx"))
    {
        // Добавьте один или несколько целевых документов
        comparer.Add("target.docx");

        // Укажите параметры сравнения
        CompareOptions options = new CompareOptions() 
        {ShowRevisions = false};

        // Сравните файлы и сохраните результат
        comparer.Compare("result.docx", options);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison с первого взгляда"
  description: "API для сравнения различий между документами в .NET приложениях"
  features:
    # feature loop
    - title: "Сравнение файлов в C#"
      content: "Выявляйте различия между исходным и целевым файлами на предмет изменений на уровне абзацев, слов и символов. Определите изменения стиля и форматирования, такие как полужирный шрифт, курсив, подчеркивание, зачеркивание, типы шрифтов и т. д."

    # feature loop
    - title: "Поддерживаются самые популярные форматы файлов и документов"
      content: "API GroupDocs.Comparison позволяет эффективно сравнивать документы в самых разных форматах, включая PDF, HTML, электронные письма, Microsoft Office документы (Word, Excel, PowerPoint, OneNote, Visio), различные типы изображений (JPEG, PNG, GIF, BMP), текстовые файлы и многое другое."

    # feature loop
    - title: "Применяйте или отклоняйте изменения с легкостью"
      content: "Каждое различие, выявленное в сравниваемых документах с помощью API GroupDocs.Comparison, можно выборочно применить или отклонить, что позволяет настроить его перед экспортом в конечный выходной документ."

    # feature loop
    - title: "Сравнительный сводный отчет"
      content: "Создайте сводный отчет о различиях с подробным описанием всех изменений, обнаруженных в сравниваемых документах, и сохраните его для справки."

############################# Platforms ############################
platforms:
  enable: true
  title: "Независимость платформы"
  description: "GroupDocs.Comparison for .NET поддерживает следующие операционные системы, фреймворки и менеджеры пакетов"
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
    - title: "VS Code"
      image: "vs_code"
    # platform loop
    - title: "ReSharper"
      image: "resharper"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NuGet"
      image: "nuget"

############################# File formats ############################
formats:
  enable: true
  title: "Поддерживаемые форматы файлов"
  description: |
    GroupDocs.Comparison for .NET поддерживает операции со следующими [форматами файлов](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
  description: "Сравнивайте PDF и офисные документы, изображения и другие форматы с высокой эффективностью"

  items:
    # feature loop
    - icon: "compare"
      title: "Простое в использовании сравнение документов"
      content: "Анализируйте и определяйте различия между двумя документами."

    # feature loop
    - icon: "note-stack"
      title: "Сравнение нескольких документов"
      content: "Одновременно анализируйте и выявляйте различия в нескольких документах."

    # feature loop
    - icon: "stacks"
      title: "Поддерживаемые форматы"
      content: "Совместим с более чем 50 широко используемыми форматами документов из различных категорий, обеспечивая широкую применимость."

    # feature loop
    - icon: "rule"
      title: "Принятие или отклонение изменений"
      content: "Четкое визуальное отображение обнаруженных изменений с возможностью их принятия или отклонения."

    # feature loop
    - icon: "preview"
      title: "Создание предварительных просмотров"
      content: "Возможность сохранять результаты сравнения в виде предварительного просмотра изображений для удобного использования и обмена ими."

    # feature loop
    - icon: "two-pager"
      title: "Сравнение контента"
      content: "Проводите тщательное сравнение текста на разных уровнях, включая построчное сравнение текста, абзаца, слова и символов, с выделенными различиями для большей ясности."

    # feature loop
    - icon: "format_color_text"
      title: "Сравнение стилей и форматирования"
      content: "Обнаруживает и выделяет изменения в форматировании и стиле документов, обеспечивая всесторонний анализ."

    # feature loop
    - icon: "folder-managed"
      title: "Гибкие настройки метаданных"
      content: "Сохраняйте метаданные из исходных или целевых файлов или настраивайте их в соответствии с предпочтениями пользователя."

    # feature loop
    - icon: "lock"
      title: "Защита паролем"
      content: "Анализируйте документы, защищенные паролем, и защитите выходной документ с помощью шифрования паролем для дополнительной безопасности."

    # feature loop
    - icon: "select"
      title: "Выборочное сравнение страниц"
      content: "Загрузите и сравните определенные разделы или страницы документа для целенаправленного анализа."

    # feature loop
    - icon: "speaker-notes"
      title: "Отображение комментариев"
      content: "Выберите отображение или скрытие комментариев при загрузке исходного документа, что позволит лучше контролировать процесс сравнения."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Образцы кода"
  description: "Некоторые варианты использования типичных операций GroupDocs.Comparison for .NET"
  items:
    # code sample loop
    - title: "Сравнение документов, защищенных паролем."
      content: |
        Чтобы [сравнить документы, защищенные паролем](https://docs.groupdocs.com/comparison/net/load-password-protected-documents/), вам необходимо указать его при загрузке документов:
        {{< landing/code title="Как сравнить документы, защищенные паролем.">}}
        ```csharp {style=abap}
        // Загрузить исходный документ и укажите его пароль
        using(Comparer comparer = new Comparer("source.docx", new LoadOptions() {Password = "1234"}))  
        {
            // Загрузить целевой документ и укажите его пароль
            comparer.Add("target.docx", new LoadOptions() {Password = "5678"});

            // Сохранить результат сравнения в указанном файле
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Сравнение нескольких PDF документов."
      content: |
        GroupDocs.Comparison позволяет [сравнивать более двух документов](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/). Операция почти такая же, как и при сравнении двух файлов. Вам просто нужно добавить больше целевых файлов в класс `comparer`.
        {{< landing/code title="Как сравнить три или более документов.">}}
        ```csharp {style=abap}   
        // Загрузить исходный документ
        using(Comparer comparer = new Comparer("source.docx") 
        {
            // Задать второй файл для сравнения
            comparer.Add("target2.docx");
            
            // Задать третий файл для сравнения
            comparer.Add("target3.docx");
            
            // Сохранить результат сравнения в указанном файле
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---
