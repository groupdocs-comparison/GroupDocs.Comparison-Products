
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
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
head_title: "Python API порівняння документів | перевірка відмінностей"
head_description: "Python Document Comparison API пропонує ефективні інструменти для порівняння документів. Бездоганно інтегрується з Python для миттєвого відстеження змін"

############################# Header ############################
title: "Порівняйте документи з Python: виділіть будь-які відмінності"
description: "Використовуйте API GroupDocs.Comparison для розробки нативних програм Python із функціями порівняння, які можна налаштувати. Порівнюйте файли, їхній вміст і стилі тексту між подібними форматами документів."
words:
  for: "для"

actions:
  main: "Безкоштовне завантаження PyPi"
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
  title: "Порівняйте зображення BMP у Python"
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
  description: "API для порівняння популярних типів документів, таких як PDF, Microsoft Office, HTML, електронні листи чи зображення в програмах Python."
  features:
    # feature loop
    - title: "Детальні звіти про результати"
      content: "GroupDocs.Comparison визначає зміни у вмісті документа (символи, слова, абзаци, таблиці, діаграми), а також зміни в стилі документа. Він надає користувачам звіт із детальною інформацією про відмінності, включаючи їх кількість і тип."

    # feature loop
    - title: "Підтримує популярні формати файлів і документів"
      content: "За допомогою API GroupDocs.Comparison ви можете ефективно порівнювати документи у таких форматах, як PDF, HTML, електронна пошта, Microsoft Office Word, електронні таблиці Excel, презентації PowerPoint, OneNote, діаграми Visio, текстові файли, JPEG, PNG, GIF, зображення BMP, та багато інших форматів."

    # feature loop
    - title: "Вичерпна документація та приклади"
      content: "Доступна розширена документація та приклади коду для використання бібліотеки порівняння на різних платформах, що полегшує інтеграцію API GroupDocs.Comparison у вашу програму Python."

    # feature loop
    - title: "Виберіть і об’єднайте зміни в один файл"
      content: "Якщо у вас є різні версії документа, ви можете вибрати певні зміни та скомпілювати новий документ за допомогою бібліотеки GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Незалежність платформи"
  description: "GroupDocs.Comparison for Python via .NET підтримує такі операційні системи, фреймворки та менеджери пакетів"
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
    GroupDocs.Comparison for Python via .NET підтримує операції з такими [форматами файлів](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
  title: "Функції GroupDocs.Comparison for Python via .NET"
  description: "Легко порівнюйте документи PDF і Office, зображення та інші формати."

  items:
    # feature loop
    - icon: "compare"
      title: "Зручне порівняння документів"
      content: "Проаналізуйте та визначте відмінності між двома документами."

    # feature loop
    - icon: "note-stack"
      title: "Порівняйте кілька документів"
      content: "Аналізуйте та виявляйте відмінності в кількох документах одночасно."

    # feature loop
    - icon: "stacks"
      title: "Підтримувані формати"
      content: "Підтримує більше 50 популярних форматів документів з різних категорій."

    # feature loop
    - icon: "rule"
      title: "Прийняти або відхилити зміни"
      content: "Чітке візуальне представлення виявлених змін із можливістю прийняти або відхилити зміни."

    # feature loop
    - icon: "preview"
      title: "Створення попередніх переглядів"
      content: "Збережіть результати порівняння як зображення."

    # feature loop
    - icon: "two-pager"
      title: "Порівняння вмісту"
      content: "Порівнюйте текстовий вміст рядок за рядком, за абзацами, словами чи символами. Виділіть зміни."

    # feature loop
    - icon: "format_color_text"
      title: "Порівняння стилів"
      content: "Виявлення змін у форматуванні та стилях."

    # feature loop
    - icon: "folder-managed"
      title: "Встановити метадані"
      content: "Зберігайте метадані з вихідного чи цільового файлів або дозволяйте користувачам вказувати їх."

    # feature loop
    - icon: "lock"
      title: "Захист паролем"
      content: "Аналізуйте зашифровані документи або захищайте отриманий документ паролем."

    # feature loop
    - icon: "select"
      title: "Порівняти конкретні сторінки"
      content: "Завантажте та порівняйте окремі розділи або сторінки документа."

    # feature loop
    - icon: "speaker-notes"
      title: "Показати коментарі"
      content: "Виберіть приховати або показати коментарі під час завантаження вихідного документа."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Зразки коду"
  description: "Дослідіть типові випадки використання операцій GroupDocs.Comparison for Python via .NET"
  items:
    # code sample loop
    - title: "Порівняння документів, захищених паролем"
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