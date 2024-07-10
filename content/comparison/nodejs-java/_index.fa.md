
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: fa
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
head_title: "Node.js API مقایسه اسناد | چک کننده تفاوت"
head_description: "Node.js API مقایسه اسناد ابزارهای کارآمدی برای مقایسه اسناد ارائه می دهد. یکپارچه با Node.js برای ردیابی تغییرات در زمان واقعی ادغام می شود"

############################# Header ############################
title: "مقایسه اسناد با Node.js: هر گونه تفاوت را برجسته کنید"
description: "از GroupDocs.Comparison API برای توسعه برنامه های اسکریپت بومی Java با ویژگی های مقایسه بسیار قابل تنظیم استفاده کنید. فایل ها، محتوای آنها و سبک متن را بین فرمت های سند مشابه مقایسه کنید."
words:
  for: "برای"

actions:
  main: "دانلود رایگان NPM"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.comparison"
  alt: "صدور مجوز"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/nodejs-java/"
  title: "آماده شروع هستید؟"
  description: "ویژگی های GroupDocs.Comparison را به صورت رایگان امتحان کنید یا مجوز درخواست کنید"

release:
  title: "نسخه {0} منتشر شد"
  notes: "چیزهای جدید را ببینید"
  downloads: "دانلودها"

code:
  title: "مقایسه BMP تصاویر در Java اسکریپت"
  more: "نمونه های بیشتر"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.comparison"
  content: |
    ```javascript {style=abap}

    // سند منبع را مشخص کنید
    const comparer = new Comparer("source.bmp");

    // اضافه کردن یک یا چند سند هدف
    comparer.add("target.bmp");

    // گزینه های مقایسه را مشخص کنید
    const options = new groupdocs.comparison.CompareOptions();
    options.setGenerateSummaryPage(false);

    // مقایسه و ذخیره نتیجه
    await comparer.compare("result.bmp", options);
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison در یک نگاه"
  description: "API برای مقایسه انواع مختلف اسناد مانند PDF، Microsoft Office، HTML، ایمیل یا تصاویر در Node.js برنامه"
  features:
    # feature loop
    - title: "گزارش های خروجی دقیق"
      content: "GroupDocs.Comparison تغییرات در محتوای سند (کاراکترها، کلمات، پاراگرافها، جداول، نمودارها) و همچنین تغییرات در سبک سند را شناسایی می کند. این گزارش حاصل را به مشتریان ارائه می دهد که حاوی اطلاعات غنی در مورد تفاوت ها، تعداد و نوع آنها است."

    # feature loop
    - title: "محبوب ترین فرمت های فایل و سند پشتیبانی می شوند"
      content: "با GroupDocs.Comparison API می توانید اسناد هر فرمت پشتیبانی شده مانند PDF، HTML، ایمیل، Microsoft Office Word اسناد، Excel صفحه گسترده، PowerPoint ارائه، OneNote، Visio نمودارها، متون، JPEG، PNG، GIF و BMP و همچنین بسیاری از فرمت های دیگر را مقایسه کنید."

    # feature loop
    - title: "مستندات و نمونه ها"
      content: "در حال حاضر مستندات زیادی در مورد استفاده از کتابخانه مقایسه در سیستم عامل های مختلف با نمونه های کد وجود دارد، بنابراین لازم نیست در مورد چگونگی کار با GroupDocs.Comparison API در برنامه Node.js خود فکر کنید."

    # feature loop
    - title: "تغییرات را انتخاب کنید و آنها را در یک فایل ادغام کنید"
      content: "اگر نسخه های مختلفی از یک سند داشته باشید، می توانید فقط تغییرات مورد نظر را انتخاب کنید و سند جدید را با استفاده از کتابخانه GroupDocs.Comparison کامپایل کنید."

############################# Platforms ############################
platforms:
  enable: true
  title: "استقلال پلت فرم"
  description: "GroupDocs.Comparison for Node.js via Java از سیستم عامل ها، چارچوب ها و مدیران بسته زیر پشتیبانی می کند"
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
  title: "فرمت های فایل پشتیبانی شده"
  description: |
    GroupDocs.Comparison for Node.js via Java از عملیات با [ زیر پشتیبانی می کند فرمت های فایل](https://docs.groupdocs.com/comparison/nodejs-java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### فرمت های Microsoft Office و OpenDocument
        * **Word:** DOCX, DOC, DOCM,DOT, DOTM, DOTX, RTX, RTF, TXT
        * **Excel:** XLSX, XLS, XLT, XLTM, XLSB, XLSM
        * **PowerPoint:** PPTX, PPT, POT, POTX, PPS, PPSX
        * **Outlook:** EML, EMLX, MSG
        * **OneNote:** ONE
        * **OpenDocument:** ODT, ODP, OTP, ODS, OTT
        * **چیدمان صفحه ثابت:** PDF        
    # group loop
    - color: "blue"
      content: |
        ### تصاویر، گرافیک و نمودارها
        * **تصاویر راستری:** BMP, GIF, JPG, JPEG, PNG
        * **تصویربرداری پزشکی:** DICOM
        * **Microsoft Visio:** VSDX, VSD, VSS, VST, VDX
        * **AutoCAD Drawing:** DWG, DXF
      # group loop
    - color: "red"
      content: |
        ### دیگر
        * **متن:** TXT
        * **زبان‌های برنامه‌نویسی:** CS, Java, CPP, JS, PY, RB, PL, ASM, GROOVY, JSON, PHP, SQL, LOG, DIFF, LESS, SCALA
        * **وب:** HTM, HTML, MHT, MHTML
        * **کتابهای الکترونیکی:** MOBI, DjVu
        * **مقادیر جدا شده با محدود کننده:** CSV

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Comparison for Node.js via Java ویژگی ها"
  description: "به راحتی PDF و اسناد، تصاویر و سایر فرمت ها را با آفیس مقایسه کنید"

  items:
    # feature loop
    - icon: "compare"
      title: "مقایسه اسناد آسان برای استفاده"
      content: "تفاوت ها را در دو سند تجزیه و تحلیل و شناسایی کنید."

    # feature loop
    - icon: "note-stack"
      title: "مقایسه چندین اسناد"
      content: "تفاوت ها را در چندین سند به طور همزمان تجزیه و تحلیل و شناسایی کنید."

    # feature loop
    - icon: "stacks"
      title: "فرمت های پشتیبانی شده"
      content: "پشتیبانی از بیش از 50 فرمت سند محبوب از دسته های مختلف."

    # feature loop
    - icon: "rule"
      title: "پذیرش یا رد تغییرات"
      content: "نمایش بصری واضح تغییرات شناسایی شده، ارائه گزینه پذیرش یا رد تغییرات."

    # feature loop
    - icon: "preview"
      title: "تولید پیش نمایش ها"
      content: "نتایج مقایسه را به عنوان تصاویر ذخیره کنید."

    # feature loop
    - icon: "two-pager"
      title: "مقایسه محتوا"
      content: "محتوای متن را خط به خط، بر اساس پاراگراف، بر اساس کلمات، بر اساس کاراکترها مقایسه کنید. تغییرات را برجسته کنید."

    # feature loop
    - icon: "format_color_text"
      title: "مقایسه سبک"
      content: "تشخیص تغییرات در قالب بندی و سبک."

    # feature loop
    - icon: "folder-managed"
      title: "تنظیم فراداده"
      content: "فراداده را از فایل های منبع یا هدف نگه دارید یا اجازه دهید توسط کاربران مشخص شود."

    # feature loop
    - icon: "lock"
      title: "محافظت از رمز عبور"
      content: "اسناد رمزگذاری شده را تجزیه و تحلیل کنید یا سند حاصل را با یک رمز عبور ایمن کنید."

    # feature loop
    - icon: "select"
      title: "مقایسه صفحات خاص"
      content: "فقط بخش ها یا صفحات خاص سند را بارگیری کنید."

    # feature loop
    - icon: "speaker-notes"
      title: "نمایش نظرات"
      content: "هنگام بارگیری سند منبع می توانید انتخاب کنید که نظرات را پنهان کنید یا نمایش دهید."

############################# Code samples ############################
code_samples:
  enable: true
  title: "نمونه های کد"
  description: "برخی از موارد استفاده از عملیات معمولی GroupDocs.Comparison for Node.js via Java"
  items:
    # code sample loop
    - title: "مقایسه اسناد محافظت شده با رمز عبور"
      content: |
        برای مقایسه اسنادی که [با رمز عبور محافظت شده اند](https://docs.groupdocs.com/comparison/nodejs-java/load-password-protected-documents/)، باید آن را مشخص کنید و سپس اسناد را بارگیری کنید:
        {{< landing/code title="نحوه مقایسه اسناد محافظت شده با رمز عبور">}}
        ```javascript {style=abap}

        import { Comparer, LoadOptions } from '@groupdocs/groupdocs.comparison'

        // سند منبع را بارگیری کنید و رمز عبور آن را مشخص کنید
        const comparer = new Comparer("source.docx", new LoadOptions("1234"));

        // سند هدف را بارگیری کنید و رمز عبور آن را مشخص کنید
        comparer.add("target.docx", new LoadOptions("5678"));

        // نتیجه مقایسه را در یک فایل مشخص ذخیره کنید
        comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "مقایسه چندین PDF اسناد."
      content: |
        GroupDocs.Comparison به شما اجازه می دهد [بیش از دو سند را مقایسه کنید](https://docs.groupdocs.com/comparison/nodejs-java/compare-multiple-documents/). عملیات تقریبا همانند مقایسه دو فایل است. شما فقط باید فایل های هدف بیشتری را به کلاس `comparer` اضافه کنید.
        {{< landing/code title="چگونه سه یا چند سند را مقایسه کنیم.">}}
        ```javascript {style=abap}
        import { Comparer } from '@groupdocs/groupdocs.comparison'

        // سند منبع را بارگیری کنید
        const comparer = new Comparer(source.pdf");

        // فایل دوم را برای مقایسه مشخص کنید
        comparer.add("target2.pdf");

        // فایل سوم را برای مقایسه مشخص کنید
        comparer.add("target3.pdf");

        // نتیجه مقایسه را در یک فایل مشخص ذخیره کنید
        comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---