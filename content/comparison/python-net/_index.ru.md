
---
############################# Static ############################
layout: "landing"
date: 2024-12-19T07:50:02
draft: false

lang: ru
product: "Comparison"
product_tag: "comparison"
platform: "Python via .NET"
platform_tag: "python-net"

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
head_title: "Python Инструмент сравнения документов | Анализ документов"
head_description: "Откройте для себя возможности инструмента Python Document Comparison Tool для тщательного анализа документов. Легко интегрируется с Python для всестороннего отслеживания изменений."

############################# Header ############################
title: "Сравните документы с Python: выделите любые различия"
description: "Используйте API GroupDocs.Comparison для создания собственных приложений на Python с настраиваемыми функциями сравнения. Изучите файлы, их содержимое и варианты стилей в разных форматах документов."
words:
  for: "для"

actions:
  main: "Получите бесплатную загрузку PyPi прямо сейчас"
  main_link: "https://pypi.org/project/groupdocs-comparison-net/"
  alt: "Лицензирование"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/python-net/"
  title: "Готовы начать?"
  description: "Попробуйте функции GroupDocs.Comparison бесплатно или запросите лицензию"

release:
  title: "Выпущена версия {0}"
  notes: "Узнайте, что нового"
  downloads: "Загрузки"

code:
  title: "Сравните изображения BMP с помощью Python"
  more: "Больше примеров"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET/"
  install: "pip install groupdocs-comparison-net"
  content: |
    ```python {style=abap}
    def run():

        # Укажите исходный документ
        with groupdocs.comparison.Comparer("in.bmp") as comparer:

            # Добавьте один или несколько целевых документов
            comparer.add("target.bmp")

            # Укажите параметры сравнения
            options = new groupdocs.comparison.CompareOptions()
            options.setGenerateSummaryPage(false)

            # Сравните файлы и сохраните результат
            comparer.compare("result.bmp", options)
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison с первого взгляда"
  description: "API, предназначенный для сравнения широко используемых типов документов, таких как PDF-файлы, файлы Microsoft Office, HTML, электронные письма или изображения, в приложениях Python."
  features:
    # feature loop
    - title: "Комплексные выходные отчеты"
      content: "GroupDocs.Comparison обнаруживает изменения в содержимом документа (символы, слова, абзацы, таблицы, диаграммы), а также изменения стиля документа. Пользователи получают подробный отчет с описанием характера и количества изменений."

    # feature loop
    - title: "Широкий выбор форматов файлов и документов"
      content: "API GroupDocs.Comparison позволяет сравнивать документы в таких форматах, как PDF, HTML, электронная почта, Microsoft Office Word, книги Excel, файлы PowerPoint, заметки OneNote, диаграммы Visio, текстовые документы, изображения JPEG, PNG, GIF, BMP и т. д. среди многих других."

    # feature loop
    - title: "Подробная документация и примеры кода"
      content: "Подробная документация и примеры кода для библиотеки сравнения на различных платформах легко доступны, что упрощает интеграцию API GroupDocs.Comparison в ваши приложения Python."

    # feature loop
    - title: "Выберите и объедините изменения в один документ"
      content: "Если у вас есть разные версии документа, вы можете выборочно скомпилировать изменения в один новый файл с помощью библиотеки GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Независимость платформы"
  description: "GroupDocs.Comparison for Python via .NET совместим со следующими операционными системами, платформами и менеджерами пакетов."
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
    GroupDocs.Comparison for Python via .NET может работать со следующими [форматами файлов](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
  title: "Возможности GroupDocs.Comparison for Python via .NET"
  description: "Легко сравнивайте PDF-файлы, документы Office, изображения и множество других форматов."

  items:
    # feature loop
    - icon: "compare"
      title: "Интуитивное сравнение документов"
      content: "Изучите и выделите различия между двумя документами."

    # feature loop
    - icon: "note-stack"
      title: "Сравнение нескольких документов"
      content: "Одновременно проверяйте несколько документов на наличие различий."

    # feature loop
    - icon: "stacks"
      title: "Расширенная поддержка форматов"
      content: "Совместим с более чем 50 широко используемыми форматами документов различных категорий."

    # feature loop
    - icon: "rule"
      title: "Принять или отклонить изменения"
      content: "Ясно визуализируйте изменения, предлагая варианты принятия или отклонения изменений."

    # feature loop
    - icon: "preview"
      title: "Создание визуальных превью"
      content: "Создавайте предварительные просмотры результатов сравнения в форматах изображений."

    # feature loop
    - icon: "two-pager"
      title: "Сравнение текстового контента"
      content: "Выполняйте сравнение строк, абзацев, слов или символов, чтобы выделить изменения."

    # feature loop
    - icon: "format_color_text"
      title: "Обнаружение изменений форматирования"
      content: "Выявление изменений в стилях и форматировании документа."

    # feature loop
    - icon: "folder-managed"
      title: "Настраиваемая обработка метаданных"
      content: "Сохраняйте метаданные из исходных или целевых файлов или позволяйте пользователям определять новые метаданные."

    # feature loop
    - icon: "lock"
      title: "Обработка файлов, защищенных паролем"
      content: "Работайте с зашифрованными документами или создавайте защищенные документы, защищенные паролем."

    # feature loop
    - icon: "select"
      title: "Целенаправленное сравнение страниц"
      content: "Выбирайте и сравнивайте отдельные разделы или отдельные страницы документа."

    # feature loop
    - icon: "speaker-notes"
      title: "Управление видимостью комментариев"
      content: "Решите, раскрывать или скрывать комментарии при изучении исходного документа."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Образцы кода"
  description: "Ознакомьтесь с распространенными сценариями использования функций GroupDocs.Comparison for Python via .NET."
  items:
    # code sample loop
    - title: "Сравнение документов с защитой паролем"
      content: |
        Для сравнения документов, [защищенных паролем](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/), при загрузке документов необходимо указать пароль:
        {{< landing/code title="Как сравнить документы, защищенные паролем.">}}
        ```python {style=abap}
        def run():

            # Загрузить исходный документ и укажите его пароль
            with groupdocs.comparison.Comparer("source.docx", new LoadOptions("1234")) as comparer:

                # Загрузить целевой документ и укажите его пароль
                comparer.add("target.docx", new LoadOptions("5678"));

                # Сохранить результат сравнения в указанном файле
                comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Сравнение нескольких PDF документов."
      content: |
        GroupDocs.Comparison позволяет [сравнивать более двух документов](https://docs.groupdocs.com/comparison/python-net/compare-multiple-documents/). Операция почти такая же, как и при сравнении двух файлов. Вам просто нужно добавить больше целевых файлов в класс `comparer`.
        {{< landing/code title="Как сравнить три или более документов.">}}
        ```python {style=abap}
        def run():

            # Загрузить исходный документ
            with groupdocs.comparison.Comparer(source.pdf") as comparer:

                # Задать второй файл для сравнения
                comparer.add("target2.pdf");

                # Задать третий файл для сравнения
                comparer.add("target3.pdf");

                # Сохранить результат сравнения в указанном файле
                comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---