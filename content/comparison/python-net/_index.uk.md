
---
############################# Static ############################
layout: "landing"
date: 2024-11-19T07:50:40
draft: false

lang: uk
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
head_title: "Python Інструмент порівняння документів | Аналіз документів"
head_description: "Відкрийте для себе потужність Інструмента порівняння документів Python для ретельного аналізу документів. Легко інтегрується з Python для комплексного відстеження змін."

############################# Header ############################
title: "Порівняйте документи з Python: виділіть будь-які відмінності"
description: "Використовуйте API GroupDocs.Comparison для створення власних програм на Python із настроюваними функціями порівняння. Перегляньте файли, їх вміст і варіації стилів у різних форматах документів."
words:
  for: "для"

actions:
  main: "Отримайте безкоштовно PyPi, завантажте зараз"
  main_link: "https://pypi.org/project/groupdocs-comparison-net/"
  alt: "Ліцензування"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/python-net/"
  title: "Готові розпочати роботу?"
  description: "Спробуйте GroupDocs.Comparison функцій безкоштовно або попросіть ліцензію"

release:
  title: "Випущена версія {0}"
  notes: "Подивіться, що нового"
  downloads: "Завантаження"

code:
  title: "Порівняйте зображення BMP за допомогою Python"
  more: "Більше прикладів"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET/"
  install: "pip install groupdocs-comparison-net"
  content: |
    ```python {style=abap}
    def run():

        # Вкажіть вихідний документ
        with groupdocs.comparison.Comparer("in.bmp") as comparer:

            # Додавання одного або декількох цільових документів
            comparer.add("target.bmp")

            # Вкажіть параметри порівняння
            options = new groupdocs.comparison.CompareOptions()
            options.setGenerateSummaryPage(false)

            # Порівняти та зберегти результат
            comparer.compare("result.bmp", options)
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison з першого погляду"
  description: "API, призначений для порівняння широко використовуваних типів документів, таких як PDF-файли, файли Microsoft Office, HTML, електронні листи або зображення в програмах Python."
  features:
    # feature loop
    - title: "Комплексні звіти про результати"
      content: "GroupDocs.Comparison виявляє зміни у вмісті документа (символи, слова, абзаци, таблиці, діаграми), а також зміни стилю документа. Користувачі отримують детальний звіт із підкресленням характеру та кількості змін."

    # feature loop
    - title: "Широкий вибір форматів файлів і документів"
      content: "API GroupDocs.Comparison дозволяє порівнювати документи в таких форматах, як PDF, HTML, електронна пошта, Microsoft Office Word, книги Excel, файли PowerPoint, нотатки OneNote, діаграми Visio, текстові документи, JPEG, PNG, GIF, зображення BMP, серед багатьох інших."

    # feature loop
    - title: "Ретельна документація та зразки коду"
      content: "Поглиблена документація та приклади кодів для бібліотеки порівняння на різних платформах легко доступні, що спрощує інтеграцію API GroupDocs.Comparison у ваші програми Python."

    # feature loop
    - title: "Виберіть і об’єднайте зміни в один документ"
      content: "Якщо у вас є різні версії документа, ви можете вибірково скомпілювати зміни в один новий файл за допомогою бібліотеки GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Незалежність платформи"
  description: "GroupDocs.Comparison for Python via .NET сумісний із такими операційними системами, фреймворками та менеджерами пакетів."
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
  title: "Підтримувані формати файлів"
  description: |
    GroupDocs.Comparison for Python via .NET може працювати з такими [форматами файлів](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office & OpenDocument формати
        * **Word:** DOCX, DOC, DOCM,DOT, DOTM, DOTX, RTX, RTF, TXT
        * **Excel:** XLSX, XLS, XLT, XLTM, XLSB, XLSM
        * **PowerPoint:** PPTX, PPT, POT, POTX, PPS, PPSX
        * **Outlook:** EML, EMLX, MSG
        * **OneNote:** ONE
        * **OpenDocument:** ODT, ODP, OTP, ODS, OTT
        * **Фіксований макет сторінки:** PDF        
    # group loop
    - color: "blue"
      content: |
        ### Зображення, графіка та діаграми
        * **Растрові зображення:** BMP, GIF, JPG, JPEG, PNG
        * **Медична візуалізація:** DICOM
        * **Microsoft Visio:** VSDX, VSD, VSS, VST, VDX
        * **AutoCAD Drawing:** DWG, DXF
      # group loop
    - color: "red"
      content: |
        ### Інше
        * **Текст:** TXT
        * **Мови програмування:** CS, Java, CPP, JS, PY, RB, PL, ASM, GROOVY, JSON, PHP, SQL, LOG, DIFF, LESS, SCALA
        * **Веб:** HTM, HTML, MHT, MHTML
        * **Електронні книги:** MOBI, DjVu
        * **Значення, розділені роздільниками:** CSV

############################# Features ############################
features:
  enable: true
  title: "Можливості GroupDocs.Comparison for Python via .NET"
  description: "Легко порівнюйте PDF-файли, документи Office, зображення та широкий спектр інших форматів."

  items:
    # feature loop
    - icon: "compare"
      title: "Інтуїтивне порівняння документів"
      content: "Вивчіть і виділіть відмінності між двома документами."

    # feature loop
    - icon: "note-stack"
      title: "Порівняння кількох документів"
      content: "Перевірте кілька документів на наявність відмінностей одночасно."

    # feature loop
    - icon: "stacks"
      title: "Широка підтримка форматів"
      content: "Сумісний із понад 50 широко використовуваними форматами документів у різних категоріях."

    # feature loop
    - icon: "rule"
      title: "Прийняти або відхилити зміни"
      content: "Чітко візуалізуйте зміни, пропонуючи варіанти прийняття або відхилення редагувань."

    # feature loop
    - icon: "preview"
      title: "Створення візуальних попередніх переглядів"
      content: "Створіть попередній перегляд результатів порівняння у форматах зображень."

    # feature loop
    - icon: "two-pager"
      title: "Порівняння текстового вмісту"
      content: "Виконуйте порівняння рядків, абзаців, слів або символів, щоб виділити зміни."

    # feature loop
    - icon: "format_color_text"
      title: "Виявлення змін форматування"
      content: "Визначте зміни в стилях і форматуванні документів."

    # feature loop
    - icon: "folder-managed"
      title: "Настроювана обробка метаданих"
      content: "Зберігайте метадані з вихідних або цільових файлів або дозволяйте користувачам визначати нові метадані."

    # feature loop
    - icon: "lock"
      title: "Робота з файлами, захищеними паролем"
      content: "Працюйте із зашифрованими документами або створюйте захищені документи, захищені паролем."

    # feature loop
    - icon: "select"
      title: "Цілеспрямовані порівняння сторінок"
      content: "Виберіть і порівняйте окремі розділи або окремі сторінки документа."

    # feature loop
    - icon: "speaker-notes"
      title: "Керування видимістю коментарів"
      content: "Вирішіть відкрити або приховати коментарі під час вивчення вихідного документа."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Зразки коду"
  description: "Відкрийте для себе типові сценарії використання функцій GroupDocs.Comparison for Python via .NET."
  items:
    # code sample loop
    - title: "Порівняння документів із захистом паролем"
      content: |
        Щоб порівняти документи, [захищені паролем](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/), потрібно вказати пароль під час завантаження документів:
        {{< landing/code title="Як порівняти захищені паролем документи.">}}
        ```python {style=abap}
        def run():

            # Завантажте вихідний документ і вкажіть його пароль
            with groupdocs.comparison.Comparer("source.docx", new LoadOptions("1234")) as comparer:

                # Завантажте цільовий документ і вкажіть його пароль
                comparer.add("target.docx", new LoadOptions("5678"));

                # Зберегти результат порівняння у вказаний файл
                comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Порівняння декількох PDF документів."
      content: |
        GroupDocs.Comparison дозволяє [порівняти більше двох документів](https://docs.groupdocs.com/comparison/python-net/compare-multiple-documents/). Операція практично така ж, як і при порівнянні двох файлів. Вам просто потрібно додати більше цільових файлів до класу `comparer`.
        {{< landing/code title="Як порівняти три і більше документів.">}}
        ```python {style=abap}
        def run():

            # Завантажте вихідний документ
            with groupdocs.comparison.Comparer(source.pdf") as comparer:

                # Вкажіть другий файл для порівняння
                comparer.add("target2.pdf");

                # Вкажіть третій файл для порівняння
                comparer.add("target3.pdf");

                # Зберегти результат порівняння у вказаний файл
                comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---