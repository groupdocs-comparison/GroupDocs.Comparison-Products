
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: uk
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
head_title: "Node.js API порівняння документів | перевірка відмінностей"
head_description: "API порівняння документів Node.js пропонує ефективні інструменти для порівняння документів. Плавно інтегрується з Node.js для відстеження змін у режимі реального часу"

############################# Header ############################
title: "Порівняйте документи з Node.js: виділіть будь-які відмінності"
description: "Використовуйте GroupDocs.Comparison API для розробки власних Java програм скриптів з високоналаштованими функціями порівняння. Порівняйте файли, їх вміст та стиль тексту між подібними форматами документів."
words:
  for: "для"

actions:
  main: "Безкоштовне завантаження NPM"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.comparison"
  alt: "Ліцензування"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/nodejs-java/"
  title: "Готові розпочати роботу?"
  description: "Спробуйте GroupDocs.Comparison функцій безкоштовно або попросіть ліцензію"

release:
  title: "Випущена версія {0}"
  notes: "Подивіться, що нового"
  downloads: "Завантаження"

code:
  title: "Порівняння BMP зображень у Java скрипті"
  more: "Більше прикладів"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.comparison"
  content: |
    ```javascript {style=abap}

    // Вкажіть вихідний документ
    const comparer = new Comparer("source.bmp");

    // Додавання одного або декількох цільових документів
    comparer.add("target.bmp");

    // Вкажіть параметри порівняння
    const options = new groupdocs.comparison.CompareOptions();
    options.setGenerateSummaryPage(false);

    // Порівняти та зберегти результат
    await comparer.compare("result.bmp", options);
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison з першого погляду"
  description: "API для порівняння різних типів документів, таких як PDF, Microsoft Office, HTML, електронні листи або зображення в Node.js програмах"
  features:
    # feature loop
    - title: "Детальні звіти про виведення"
      content: "GroupDocs.Comparison визначає зміни у змісті документа (символи, слова, абзаци, таблиці, діаграми), а також зміни стилю документа. Він надає клієнтам отриманий звіт, який містить багату інформацію про відмінності, їх кількість та тип."

    # feature loop
    - title: "Підтримуються найпопулярніші формати файлів і документів"
      content: "За допомогою GroupDocs.Comparison API ви можете ефективно порівнювати документи будь-яких підтримуваних форматів, таких як PDF, HTML, електронна пошта, Microsoft Office Word документи, Excel електронні таблиці, PowerPoint презентації, OneNote, Visio діаграми, тексти, JPEG, PNG, GIF та BMP зображення, а також багато інших форматів."

    # feature loop
    - title: "Документація та приклади"
      content: "Вже є багато документації щодо використання бібліотеки порівняння на різних платформах з прикладами коду, тому вам не доведеться сильно думати про те, як працювати з GroupDocs.Comparison API у вашому додатку Node.js."

    # feature loop
    - title: "Виберіть зміни та об'єднайте їх в один файл"
      content: "Якщо у вас є різні версії одного документа, ви можете вибрати лише бажані зміни та компілювати новий документ за допомогою бібліотеки GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Незалежність платформи"
  description: "GroupDocs.Comparison for Node.js via Java підтримує наступні операційні системи, фреймворки та менеджери пакетів"
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
    GroupDocs.Comparison for Node.js via Java підтримує операції з наступними [форматами файлів](https://docs.groupdocs.com/comparison/nodejs-java/supported-document-formats/).
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
  title: "GroupDocs.Comparison for Node.js via Java особливості"
  description: "Легко порівнюйте документи PDF та Office, зображення та інші формати"

  items:
    # feature loop
    - icon: "compare"
      title: "Просте у використанні порівняння документів"
      content: "Проаналізуйте та визначте відмінності в двох документах."

    # feature loop
    - icon: "note-stack"
      title: "Порівняння декількох документів"
      content: "Аналізуйте та виявляйте відмінності в декількох документах одночасно."

    # feature loop
    - icon: "stacks"
      title: "Підтримувані формати"
      content: "Підтримує понад 50 популярних форматів документів з різних категорій."

    # feature loop
    - icon: "rule"
      title: "Прийняти або відхилити зміни"
      content: "Чітке візуальне представлення виявлених змін, що надає можливість прийняти або відхилити модифікації."

    # feature loop
    - icon: "preview"
      title: "Створити попередній перегляд"
      content: "Збережіть результати порівняння як зображення."

    # feature loop
    - icon: "two-pager"
      title: "Порівняння вмісту"
      content: "Порівняйте вміст тексту рядок за рядком, за абзацами, за словами, за символами. Виділіть зміни."

    # feature loop
    - icon: "format_color_text"
      title: "Порівняння стилю"
      content: "Виявлення змін форматування та стилів."

    # feature loop
    - icon: "folder-managed"
      title: "Встановити метадані"
      content: "Зберігати метадані з вихідних або цільових файлів або дозволити їх вказувати користувачами."

    # feature loop
    - icon: "lock"
      title: "Захист паролем"
      content: "Проаналізуйте зашифровані документи або закріпіть отриманий документ паролем."

    # feature loop
    - icon: "select"
      title: "Порівняйте конкретні сторінки"
      content: "Завантажте лише окремі розділи або сторінки документа."

    # feature loop
    - icon: "speaker-notes"
      title: "Показати коментарі"
      content: "Під час завантаження вихідного документа ви можете вибрати, приховувати чи показувати коментарі."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Зразки коду"
  description: "Деякі випадки використання типових GroupDocs.Comparison for Node.js via Java операцій"
  items:
    # code sample loop
    - title: "Порівняння захищених паролем документів."
      content: |
        Для порівняння документів, які [захищені паролем](https://docs.groupdocs.com/comparison/nodejs-java/load-password-protected-documents/), потрібно вказати його, а потім завантажити документи:
        {{< landing/code title="Як порівняти захищені паролем документи.">}}
        ```javascript {style=abap}

        import { Comparer, LoadOptions } from '@groupdocs/groupdocs.comparison'

        // Завантажте вихідний документ і вкажіть його пароль
        const comparer = new Comparer("source.docx", new LoadOptions("1234"));

        // Завантажте цільовий документ і вкажіть його пароль
        comparer.add("target.docx", new LoadOptions("5678"));

        // Зберегти результат порівняння у вказаний файл
        comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Порівняння декількох PDF документів."
      content: |
        GroupDocs.Comparison дозволяє [порівняти більше двох документів](https://docs.groupdocs.com/comparison/nodejs-java/compare-multiple-documents/). Операція практично така ж, як і при порівнянні двох файлів. Вам просто потрібно додати більше цільових файлів до класу `comparer`.
        {{< landing/code title="Як порівняти три і більше документів.">}}
        ```javascript {style=abap}
        import { Comparer } from '@groupdocs/groupdocs.comparison'

        // Завантажте вихідний документ
        const comparer = new Comparer(source.pdf");

        // Вкажіть другий файл для порівняння
        comparer.add("target2.pdf");

        // Вкажіть третій файл для порівняння
        comparer.add("target3.pdf");

        // Зберегти результат порівняння у вказаний файл
        comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---