
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
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
head_title: "Python API сравнения документов | проверка различий"
head_description: "API сравнения документов Python предлагает эффективные инструменты для сравнения документов. Полная интеграция с Python для мгновенного отслеживания изменений."

############################# Header ############################
title: "Сравните документы с Python: выделите любые различия"
description: "Используйте API GroupDocs.Comparison для разработки собственных приложений Python с гибко настраиваемыми функциями сравнения. Сравнивайте файлы, их содержимое и стили текста в документах схожих форматов."
words:
  for: "для"

actions:
  main: "Бесплатная загрузка PyPi"
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
  title: "Сравните изображения BMP в Python"
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
  description: "API для сравнения популярных типов документов, таких как PDF, Microsoft Office, HTML, электронные письма или изображения, в приложениях Python."
  features:
    # feature loop
    - title: "Подробные отчеты о результатах"
      content: "GroupDocs.Comparison идентифицирует изменения в содержимом документа (символы, слова, абзацы, таблицы, диаграммы), а также изменения в стиле документа. Он предоставляет пользователям отчет, содержащий подробную информацию о различиях, включая их количество и тип."

    # feature loop
    - title: "Поддерживает популярные форматы файлов и документов."
      content: "С помощью API GroupDocs.Comparison вы можете эффективно сравнивать документы в таких форматах, как PDF, HTML, электронная почта, Microsoft Office Word, электронные таблицы Excel, презентации PowerPoint, OneNote, диаграммы Visio, текстовые файлы, изображения JPEG, PNG, GIF, BMP и т. д. и многие другие форматы."

    # feature loop
    - title: "Комплексная документация и примеры"
      content: "Доступна обширная документация и примеры кода для использования библиотеки сравнения на разных платформах, что упрощает интеграцию API GroupDocs.Comparison в ваше приложение Python."

    # feature loop
    - title: "Выбрать и объединить изменения в один файл"
      content: "Если у вас есть разные версии документа, вы можете выбрать определенные изменения и скомпилировать новый документ с помощью библиотеки GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Независимость платформы"
  description: "GroupDocs.Comparison for Python via .NET поддерживает следующие операционные системы, платформы и менеджеры пакетов."
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
    GroupDocs.Comparison for Python via .NET поддерживает операции со следующими [форматами файлов](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
  title: "Функции GroupDocs.Comparison for Python via .NET"
  description: "Легко сравнивайте документы PDF и Office, изображения и другие форматы."

  items:
    # feature loop
    - icon: "compare"
      title: "Удобное сравнение документов"
      content: "Проанализируйте и определите различия между двумя документами."

    # feature loop
    - icon: "note-stack"
      title: "Сравнить несколько документов"
      content: "Анализируйте и выявляйте различия в нескольких документах одновременно."

    # feature loop
    - icon: "stacks"
      title: "Поддерживаемые форматы"
      content: "Поддерживает более 50 популярных форматов документов из различных категорий."

    # feature loop
    - icon: "rule"
      title: "Принять или отклонить изменения"
      content: "Четкое визуальное представление выявленных изменений с возможностью принять или отклонить изменения."

    # feature loop
    - icon: "preview"
      title: "Создание превью"
      content: "Сохраните результаты сравнения в виде изображений."

    # feature loop
    - icon: "two-pager"
      title: "Сравнение контента"
      content: "Сравнивайте текстовое содержимое построчно, по абзацам, по словам или по символам. Подчеркните изменения."

    # feature loop
    - icon: "format_color_text"
      title: "Сравнение стилей"
      content: "Обнаружение изменений в форматировании и стилях."

    # feature loop
    - icon: "folder-managed"
      title: "Установить метаданные"
      content: "Сохраняйте метаданные из исходного или целевого файлов или позволяйте пользователям указывать их."

    # feature loop
    - icon: "lock"
      title: "Защита паролем"
      content: "Анализируйте зашифрованные документы или защитите полученный документ паролем."

    # feature loop
    - icon: "select"
      title: "Сравнить отдельные страницы"
      content: "Загрузите и сравните определенные разделы или страницы документа."

    # feature loop
    - icon: "speaker-notes"
      title: "Отображение комментариев"
      content: "Выберите, скрыть или показать комментарии при загрузке исходного документа."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Образцы кода"
  description: "Изучите типичные варианты использования операций GroupDocs.Comparison for Python via .NET."
  items:
    # code sample loop
    - title: "Сравнение документов, защищенных паролем"
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