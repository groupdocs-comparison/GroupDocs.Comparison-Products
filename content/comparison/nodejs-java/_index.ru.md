
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: ru
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

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
head_title: "Node.js API сравнения документов | средство проверки различий"
head_description: "API сравнения документов Node.js предлагает эффективные инструменты для сравнения документов. Легко интегрируется с Node.js для отслеживания изменений в реальном времени"

############################# Header ############################
title: "Сравнивайте документы в Node.js решениях с подсветкой различий"
description: "Используйте API GroupDocs.Comparison для разработки нативных Java Script-приложений с настраиваемыми функциями сравнения. Сравнивайте файлы, их содержимое и стиль текста в аналогичных форматах документов."
words:
  for: "для"

actions:
  main: "Бесплатная загрузка NPM"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.comparison"
  alt: "Лицензирование"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/nodejs-java/"
  title: "Готовы начать?"
  description: "Попробуйте функции GroupDocs.Comparison бесплатно или запросите лицензию"

release:
  title: "Выпущена версия {0}"
  notes: "Узнайте, что нового"
  downloads: "Загрузки"

code:
  title: "Сравнение BMP изображений в скрипте Java"
  more: "Больше примеров"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.comparison"
  content: |
    ```javascript {style=abap}

    // Укажите исходный документ
    const comparer = new Comparer("source.bmp");

    // Добавьте один или несколько целевых документов
    comparer.add("target.bmp");

    // Укажите параметры сравнения
    const options = new groupdocs.comparison.CompareOptions();
    options.setGenerateSummaryPage(false);

    // Сравните файлы и сохраните результат
    await comparer.compare("result.bmp", options);
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison с первого взгляда"
  description: "API для сравнения различных типов документов, таких как PDF, Microsoft Office, HTML, электронные письма или изображения в Node.js приложениях"
  features:
    # feature loop
    - title: "Подробные выходные отчеты"
      content: "GroupDocs.Comparison определяет изменения в содержимом документа (символы, слова, абзацы, таблицы, диаграммы), а также изменения стиля документа. Он предоставляет клиентам итоговый отчет, содержащий подробную информацию о различиях, их количестве и типах."

    # feature loop
    - title: "Поддерживаются самые популярные форматы файлов и документов"
      content: "С помощью GroupDocs.Comparison API вы можете эффективно сравнивать документы любых поддерживаемых форматов, таких как PDF, HTML, электронная почта, Microsoft Office Word документы, Excel электронные таблицы, PowerPoint презентации, OneNote, Visio диаграммы, тексты, JPEG, PNG, GIF и BMP изображения, а также многие другие форматы."

    # feature loop
    - title: "Документация и примеры"
      content: "Мы предоставляем исчерпывающую документацию по использованию библиотеки Comparison на разных платформах с примерами кода, поэтому вам не придется долго думать о том, как работать с API GroupDocs.Comparison в приложении Node.js."

    # feature loop
    - title: "Выберите изменения и объедините их в один файл"
      content: "Если у вас разные версии одного документа, можно выбрать только нужные изменения и скомпилировать новый документ с помощью библиотеки GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Независимость платформы"
  description: "GroupDocs.Comparison for Node.js via Java поддерживает следующие операционные системы, фреймворки и менеджеры пакетов"
  items:
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "macOS"
      image: "finder"      
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NPM"
      image: "npm"  
    # platform loop
    - title: "NuGet"
      image: "nuget"      
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
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"

############################# File formats ############################
formats:
  enable: true
  title: "Поддерживаемые форматы файлов"
  description: |
    GroupDocs.Comparison for Node.js via Java поддерживает операции со следующими [форматами файлов](https://docs.groupdocs.com/comparison/nodejs-java/supported-document-formats/).
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
  title: "Характеристики GroupDocs.Comparison for Node.js via Java"
  description: "Сравнивайте PDF и офисные документы, изображения и другие форматы с легкостью"

  items:
    # feature loop
    - icon: "compare"
      title: "Простое в использовании сравнение документов"
      content: "Анализируйте и определяйте различия в двух документах."

    # feature loop
    - icon: "note-stack"
      title: "Сравнение нескольких документов"
      content: "Анализируйте и выявляйте различия в нескольких документах одновременно."

    # feature loop
    - icon: "stacks"
      title: "Поддерживаемые форматы"
      content: "Поддерживается более 50 популярных форматов документов из различных категорий."

    # feature loop
    - icon: "rule"
      title: "Принятие или отклонение изменений"
      content: "Четкое визуальное представление идентифицированных изменений с возможностью принятия или отклонения изменений."

    # feature loop
    - icon: "preview"
      title: "Создание предварительных просмотров"
      content: "Сохраняйте результаты сравнения в виде изображений."

    # feature loop
    - icon: "two-pager"
      title: "Сравнение контента"
      content: "Сравнивайте текстовое содержимое построчно, по абзацам, по словам, по символам. Выделите изменения."

    # feature loop
    - icon: "format_color_text"
      title: "Сравнение стилей"
      content: "Просматривайте изменения в форматировании и стилях."

    # feature loop
    - icon: "folder-managed"
      title: "Настройка метаданных"
      content: "Сохраните метаданные из исходного или целевого файлов или разрешите пользователям указывать их."

    # feature loop
    - icon: "lock"
      title: "Защита паролем"
      content: "Анализируйте зашифрованные документы или защитите полученный документ паролем."

    # feature loop
    - icon: "select"
      title: "Сравнение определенных страниц"
      content: "Загрузите только определенные разделы или страницы документа."

    # feature loop
    - icon: "speaker-notes"
      title: "Отображение комментариев"
      content: "При загрузке исходного документа вы можете выбрать, скрыть или показать комментарии."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Образцы кода"
  description: "Некоторые варианты использования GroupDocs.Comparison for Node.js via Java"
  items:
    # code sample loop
    - title: "Сравнение документов, защищенных паролем."
      content: |
        Чтобы [сравнить документы, защищенные паролем](https://docs.groupdocs.com/comparison/nodejs-java/load-password-protected-documents/), вам необходимо указать его при загрузке документов:
        {{< landing/code title="Как сравнить документы, защищенные паролем.">}}
        ```javascript {style=abap}

        import { Comparer, LoadOptions } from '@groupdocs/groupdocs.comparison'

        // Загрузить исходный документ и укажите его пароль
        const comparer = new Comparer("source.docx", new LoadOptions("1234"));

        // Загрузить целевой документ и укажите его пароль
        comparer.add("target.docx", new LoadOptions("5678"));

        // Сохранить результат сравнения в указанном файле
        comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Сравнение нескольких PDF документов."
      content: |
        GroupDocs.Comparison позволяет [сравнивать более двух документов](https://docs.groupdocs.com/comparison/nodejs-java/compare-multiple-documents/). Операция почти такая же, как и при сравнении двух файлов. Вам просто нужно добавить больше целевых файлов в класс `comparer`.
        {{< landing/code title="Как сравнить три или более документов.">}}
        ```javascript {style=abap}
        import { Comparer } from '@groupdocs/groupdocs.comparison'

        // Загрузить исходный документ
        const comparer = new Comparer(source.pdf");

        // Задать второй файл для сравнения
        comparer.add("target2.pdf");

        // Задать третий файл для сравнения
        comparer.add("target3.pdf");

        // Сохранить результат сравнения в указанном файле
        comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---