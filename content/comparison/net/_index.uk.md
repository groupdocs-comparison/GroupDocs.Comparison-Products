
---
############################# Static ############################
layout: "landing"
date: 2024-12-19T07:50:01
draft: false

lang: uk
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
head_title: "C# .NET Програмне забезпечення для порівняння документів | перевірка відмінностей"
head_description: "C# .NET Програмне забезпечення для порівняння стилю та вмісту документа. Порівняйте документи декількох підтримуваних форматів, щоб визначити зміни між файлами."

############################# Header ############################
title: "Легко порівнюйте документи у ваших C# .NET рішеннях"
description: "Створюйте C# програми за допомогою гнучкого API порівняння документів, який дозволяє порівнювати файли за вмістом та стилем у різних форматах документів."
words:
  for: "для"

actions:
  main: "Безкоштовно NuGet Завантажити"
  main_link: "https://www.nuget.org/packages/GroupDocs.Comparison"
  alt: "Ліцензування"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/net/"
  title: "Готові розпочати роботу?"
  description: "Спробуйте GroupDocs.Comparison функцій безкоштовно або попросіть ліцензію"

release:
  title: "Випущена версія {0}"
  notes: "Подивіться, що нового"
  downloads: "Завантаження"

code:
  title: "Порівняйте DOCX файлів у C#"
  more: "Більше прикладів"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET"
  install: "dotnet add package GroupDocs.Comparison"
  content: |
    ```csharp {style=abap}   
    // Вкажіть вихідний документ
    using (Comparer comparer = new Comparer("source.docx"))
    {
        // Додавання одного або декількох цільових документів
        comparer.Add("target.docx");

        // Вкажіть параметри порівняння
        CompareOptions options = new CompareOptions() 
        {ShowRevisions = false};

        // Порівняти та зберегти результат
        comparer.Compare("result.docx", options);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison з першого погляду"
  description: "API для порівняння відмінностей між документами в .NET програмах"
  features:
    # feature loop
    - title: "Порівняння файлів у C#"
      content: "Визначте відмінності між вихідними та цільовими файлами для змін на рівнях абзаців, слів та символів. Визначте зміни стилю та форматування, як-от жирний, курсив, підкреслення, крапки, типи шрифтів тощо."

    # feature loop
    - title: "Підтримуються найпопулярніші формати файлів і документів"
      content: "GroupDocs.Comparison API дозволяє ефективно порівнювати документи в широкому діапазоні форматів, включаючи PDF, HTML, електронні листи, Microsoft Office документи (Word, Excel, PowerPoint, OneNote, Visio), різні типи зображень (JPEG, PNG, GIF, BMP), текстові файли тощо."

    # feature loop
    - title: "Легко застосувати або відхиляти зміни"
      content: "Кожна відмінність, виявлена у порівнянних документах за допомогою GroupDocs.Comparison API, може бути вибірково застосована або відхилена, що дозволяє налаштовувати перед експортом до кінцевого вихідного документа."

    # feature loop
    - title: "Зведений звіт про порівняння"
      content: "Створіть зведений звіт про відмінності, деталізуючи всі зміни, знайдені в порівнюваних документах, і збережіть його для довідки."

############################# Platforms ############################
platforms:
  enable: true
  title: "Незалежність платформи"
  description: "GroupDocs.Comparison for .NET підтримує наступні операційні системи, фреймворки та менеджери пакетів"
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
  title: "Підтримувані формати файлів"
  description: |
    GroupDocs.Comparison for .NET підтримує операції з наступними [форматами файлів](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
      content: "Проаналізуйте та визначте відмінності між двома документами."

    # feature loop
    - icon: "note-stack"
      title: "Порівняння декількох документів"
      content: "Одночасно аналізуйте та визначте відмінності між кількома документами."

    # feature loop
    - icon: "stacks"
      title: "Підтримувані формати"
      content: "Сумісний з більш ніж 50 широко використовуваними форматами документів з різних категорій, забезпечуючи широке застосування."

    # feature loop
    - icon: "rule"
      title: "Прийняти або відхилити зміни"
      content: "Чітке візуальне відображення виявлених змін у комплекті з можливостями прийняття або відхилення цих модифікацій."

    # feature loop
    - icon: "preview"
      title: "Створити попередній перегляд"
      content: "Можливість зберігати результати порівняння як попередній перегляд зображень для зручного ознайомлення та обміну."

    # feature loop
    - icon: "two-pager"
      title: "Порівняння вмісту"
      content: "Проведіть ретельне порівняння тексту на різних рівнях - включаючи рядок за рядком, абзац, слово та символ - з виділеними відмінностями для кращої чіткості."

    # feature loop
    - icon: "format_color_text"
      title: "Порівняння стилів і форматування"
      content: "Визначає та виділяє зміни у форматуванні та стилі документа, забезпечуючи всебічний огляд."

    # feature loop
    - icon: "folder-managed"
      title: "Гнучкі налаштування метаданих"
      content: "Зберігати метадані з вихідних або цільових файлів або налаштовувати їх відповідно до уподобань користувача."

    # feature loop
    - icon: "lock"
      title: "Захист паролем"
      content: "Аналізуйте захищені паролем документи та захистіть вихідний документ шифруванням паролем для додаткової безпеки."

    # feature loop
    - icon: "select"
      title: "Вибіркове порівняння сторінок"
      content: "Завантажте та порівняйте конкретні розділи або сторінки документа для цільового аналізу."

    # feature loop
    - icon: "speaker-notes"
      title: "Показати коментарі"
      content: "Виберіть відображення або приховування коментарів під час завантаження вихідного документа, пропонуючи більший контроль над процесом порівняння."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Зразки коду"
  description: "Деякі випадки використання типових GroupDocs.Comparison for .NET операцій"
  items:
    # code sample loop
    - title: "Порівняння захищених паролем документів."
      content: |
        Для порівняння документів, які [захищені паролем](https://docs.groupdocs.com/comparison/net/load-password-protected-documents/), потрібно вказати його, а потім завантажити документи:
        {{< landing/code title="Як порівняти захищені паролем документи.">}}
        ```csharp {style=abap}
        // Завантажте вихідний документ і вкажіть його пароль
        using(Comparer comparer = new Comparer("source.docx", new LoadOptions() {Password = "1234"}))  
        {
            // Завантажте цільовий документ і вкажіть його пароль
            comparer.Add("target.docx", new LoadOptions() {Password = "5678"});

            // Зберегти результат порівняння у вказаний файл
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Порівняння декількох PDF документів."
      content: |
        GroupDocs.Comparison дозволяє [порівняти більше двох документів](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/). Операція практично така ж, як і при порівнянні двох файлів. Вам просто потрібно додати більше цільових файлів до класу `comparer`.
        {{< landing/code title="Як порівняти три і більше документів.">}}
        ```csharp {style=abap}   
        // Завантажте вихідний документ
        using(Comparer comparer = new Comparer("source.docx") 
        {
            // Вкажіть другий файл для порівняння
            comparer.Add("target2.docx");
            
            // Вкажіть третій файл для порівняння
            comparer.Add("target3.docx");
            
            // Зберегти результат порівняння у вказаний файл
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---
