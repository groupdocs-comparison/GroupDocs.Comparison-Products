
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: uk
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
head_title: "Java Бібліотека порівняння документів| перевірка відмінностей"
head_description: "Власне Java програмне забезпечення для порівняння стилю та вмісту документа. Порівняйте документи різних форматів, щоб визначити відмінності."

############################# Header ############################
title: "Порівняйте та перевірте відмінності файлів за допомогою Java API"
description: "Розробляйте Java програми з високоналаштованою бібліотекою порівняння документів для порівняння подібних форматів документів, включаючи файли, їх вміст та стиль тексту."
words:
  for: "для"

actions:
  main: "Безкоштовне завантаження Maven"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/"
  alt: "Ліцензування"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/java/"
  title: "Готові розпочати роботу?"
  description: "Спробуйте GroupDocs.Comparison функцій безкоштовно або попросіть ліцензію"

release:
  title: "Випущена версія {0}"
  notes: "Подивіться, що нового"
  downloads: "Завантаження"

code:
  title: "Порівняйте DOCX файлів у Java"
  more: "Більше прикладів"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
  install: |
    <dependency>
      <groupId>com.groupdocs</groupId>
      <artifactId>groupdocs-comparison</artifactId>
      <version>{0}</version>
    </dependency>
  content: |
    ```java {style=abap}  
    // Вкажіть вихідний документ
    try (Comparer comparer = new Comparer("source.docx"))
    {    
      // Додавання одного або декількох цільових документів
      comparer.add("target.docx");

      // Вкажіть параметри порівняння
      CompareOptions options = new CompareOptions();
      options.setShowRevisions(false);

      // Порівняти та зберегти результат
      final comparer.compare("result.docx", options);
    }    
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison з першого погляду"
  description: "API для порівняння відмінностей між документами в Java програмах"
  features:
    # feature loop
    - title: "Порівняння файлів у Java"
      content: "Визначте зміни між вихідними та цільовими файлами на рівнях абзацу, слова та символів. Визначте зміни стилю та форматування, як-от жирний, курсив, підкреслення, закреслення, типи шрифтів тощо."

    # feature loop
    - title: "Величезна кількість підтримуваних форматів"
      content: "За допомогою GroupDocs.Comparison API ви можете легко порівнювати документи декількох підтримуваних форматів. Сюди входять PDF, HTML, електронна пошта, Microsoft Office Word документи, Excel електронні таблиці, PowerPoint презентації, OneNote, Visio діаграми, тексти, JPEG, PNG, GIF та BMP зображення, а також багато інших форматів."

    # feature loop
    - title: "Легко застосувати або відхиляти зміни"
      content: "Кожна різниця між порівнянними документами може бути застосована або відхилена, а потім експортована до вихідного документа."

    # feature loop
    - title: "Зведений звіт про порівняння"
      content: "Створіть зведений звіт, в якому перераховані всі зміни в порівнюваних документах."

############################# Platforms ############################
platforms:
  enable: true
  title: "Незалежність платформи"
  description: "GroupDocs.Comparison for Java підтримує наступні операційні системи, фреймворки та менеджери пакетів"
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
  title: "Підтримувані формати файлів"
  description: |
    GroupDocs.Comparison for Java підтримує операції з наступними [форматами файлів](https://docs.groupdocs.com/comparison/java/supported-document-formats/).
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
  title: "GroupDocs.Comparison особливості"
  description: "Легко порівнюйте документи PDF та Office, зображення та інші формати"

  items:
    # feature loop
    - icon: "compare"
      title: "Просте у використанні порівняння документів"
      content: "Легко аналізуйте та визначте відмінності між двома документами."

    # feature loop
    - icon: "note-stack"
      title: "Порівняння декількох документів"
      content: "Одночасно вивчайте та виділяйте відхилення між кількома документами."

    # feature loop
    - icon: "stacks"
      title: "Підтримувані формати"
      content: "Сумісність з більш ніж 50 широко використовуваними форматами документів з різних категорій."

    # feature loop
    - icon: "rule"
      title: "Прийняти або відхилити зміни"
      content: "Чітка візуалізація виявлених змін з можливостями прийняття або відхилення модифікацій."

    # feature loop
    - icon: "preview"
      title: "Створити попередній перегляд"
      content: "Можливість зберігати результати порівняння як попередній перегляд зображень."

    # feature loop
    - icon: "two-pager"
      title: "Порівняння вмісту"
      content: "Ретельне порівняння текстового вмісту на різних рівнях - включаючи рядок за рядком, абзац, слово та аналіз символів, з акцентом на зміни."

    # feature loop
    - icon: "format_color_text"
      title: "Порівняння стилю"
      content: "Можливість виявлення та виділення змін у елементах форматування та стилю."

    # feature loop
    - icon: "folder-managed"
      title: "Встановити метадані"
      content: "Можливість збереження метаданих із вихідних або цільових файлів або дозволу налаштувань метаданих, визначених користувачем."

    # feature loop
    - icon: "lock"
      title: "Захист паролем"
      content: "Полегшує аналіз захищених паролем документів та забезпечує захист паролем для отриманих документів."

    # feature loop
    - icon: "select"
      title: "Порівняйте конкретні сторінки"
      content: "Завантажуйте та порівнюйте певні розділи або сторінки документа за потребою."

    # feature loop
    - icon: "speaker-notes"
      title: "Показати коментарі"
      content: "Гнучкість відображення або приховування коментарів під час завантаження вихідного документа."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Зразки коду"
  description: "Деякі випадки використання типових GroupDocs.Comparison for Java операцій"
  items:
    # code sample loop
    - title: "Порівняння захищених паролем документів."
      content: |
        Для порівняння документів, які [захищені паролем](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/), потрібно вказати його, а потім завантажити документи:
        {{< landing/code title="Як порівняти захищені паролем документи.">}}
        ```java {style=abap}
        // Завантажте вихідний документ і вкажіть його пароль
        try (Comparer comparer = new Comparer("source.docx", new LoadOptions("1234")))
        {
            // Завантажте цільовий документ і вкажіть його пароль
            comparer.add("target.docx", new LoadOptions("5678"));
        
            // Зберегти результат порівняння у вказаний файл
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Порівняння декількох PDF документів."
      content: |
        GroupDocs.Comparison дозволяє [порівняти більше двох документів](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/). Операція практично така ж, як і при порівнянні двох файлів. Вам просто потрібно додати більше цільових файлів до класу `comparer`.
        {{< landing/code title="Як порівняти три і більше документів.">}}
        ```java {style=abap}   
        // Завантажте вихідний документ
        try (Comparer comparer = new Comparer("source.docx") 
        {
            // Вкажіть другий файл для порівняння
            comparer.add("target2.docx");

            // Вкажіть третій файл для порівняння
            comparer.add("target3.docx");

            // Зберегти результат порівняння у вказаний файл
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---

