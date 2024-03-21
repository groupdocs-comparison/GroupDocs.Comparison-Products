
---
############################# Static ############################
layout: "landing"
date: 2024-03-21T15:26:29
draft: false

lang: fa
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

############################# Head ############################
head_title: "Java کتابخانه مقایسه اسناد | چک کننده تفاوت"
head_description: "نرم افزار بومی Java برای مقایسه سبک و محتوا سند. اسناد با فرمت های مختلف را برای شناسایی تفاوت ها مقایسه کنید."

############################# Header ############################
title: "مقایسه و بررسی تفاوت فایل با استفاده از Java API"
description: "Java برنامه را با یک کتابخانه مقایسه اسناد بسیار قابل تنظیم برای مقایسه فرمت های سند مشابه، از جمله فایل ها، محتوای آنها و سبک متن توسعه دهید."
words:
  for: "برای"

actions:
  main: "دانلود رایگان Maven"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/"
  alt: "صدور مجوز"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/java/"
  title: "آماده شروع هستید؟"
  description: "ویژگی های GroupDocs.Comparison را به صورت رایگان امتحان کنید یا مجوز درخواست کنید"

release:
  title: "نسخه {0} منتشر شد"
  notes: "چیزهای جدید را ببینید"
  downloads: "دانلودها"

code:
  title: "مقایسه DOCX فایل ها در Java"
  more: "نمونه های بیشتر"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
  install: |
    <dependency>
      <groupId>com.groupdocs</groupId>
      <artifactId>groupdocs-comparison</artifactId>
      <version>{0}</version>
    </dependency>
  content: |
    ```java {style=abap}  
    // سند منبع را مشخص کنید
    try (Comparer comparer = new Comparer("source.docx"))
    {    
      // اضافه کردن یک یا چند سند هدف
      comparer.add("target.docx");

      // گزینه های مقایسه را مشخص کنید
      CompareOptions options = new CompareOptions();
      options.setShowRevisions(false);

      // مقایسه را انجام دهید و سند حاصل را ذخیره کنید
      final comparer.compare("result.docx", options);
    }    
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison در یک نگاه"
  description: "API برای مقایسه تفاوت بین اسناد در Java برنامه"
  features:
    # feature loop
    - title: "مقایسه فایل در Java"
      content: "تغییرات بین فایل های منبع و هدف را در سطح پاراگراف، کلمه و کاراکتر تشخیص دهید. تغییرات سبک و قالب بندی مانند پررنگ، ایتالیک، اشعه کشی، تکرار، انواع فونت و موارد دیگر را شناسایی کنید."

    # feature loop
    - title: "تعداد زیادی از فرمت های پشتیبانی شده"
      content: "با GroupDocs.Comparison API، شما به راحتی می توانید اسناد چندین فرمت پشتیبانی شده را مقایسه کنید. این شامل PDF، HTML، ایمیل، Microsoft Office Word اسناد، Excel صفحات گسترده، PowerPoint ارائه، OneNote، Visio نمودار، متون، JPEG، PNG، GIF، و BMP، و همچنین بسیاری از فرمت های دیگر است."

    # feature loop
    - title: "اعمال یا رد تغییرات به راحتی"
      content: "هر تفاوت بین اسناد مقایسه شده را می توان اعمال یا رد کرد و سپس به سند خروجی صادر کرد."

    # feature loop
    - title: "گزارش خلاصه مقایسه"
      content: "یک گزارش خلاصه ایجاد کنید که تمام تغییرات در اسناد مقایسه شده را فهرست می کند."

############################# Platforms ############################
platforms:
  enable: true
  title: "استقلال پلت فرم"
  description: "GroupDocs.Comparison for Java از سیستم عامل ها، چارچوب ها و مدیران بسته زیر پشتیبانی می کند"
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
  title: "فرمت های فایل پشتیبانی شده"
  description: |
    GroupDocs.Comparison for Java از عملیات با [فرمت های فایل] زیر پشتیبانی می کند (https://docs.groupdocs.com/comparison/java/supported-document-formats/).
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
  title: "GroupDocs.Comparison ویژگی ها"
  description: "به راحتی PDF و اسناد، تصاویر و سایر فرمت ها را با آفیس مقایسه کنید"

  items:
    # feature loop
    - icon: "compare"
      title: "مقایسه اسناد آسان برای استفاده"
      content: "به راحتی تفاوت های بین دو سند را تجزیه و تحلیل و مشخص کنید."

    # feature loop
    - icon: "note-stack"
      title: "مقایسه چندین اسناد"
      content: "به طور همزمان واریانس ها را در چندین سند بررسی و برجسته کنید."

    # feature loop
    - icon: "stacks"
      title: "فرمت های پشتیبانی شده"
      content: "سازگاری با بیش از 50 فرمت سند پرکاربرد از دسته های مختلف."

    # feature loop
    - icon: "rule"
      title: "پذیرش یا رد تغییرات"
      content: "تجسم واضح تغییرات شناسایی شده، با گزینه هایی برای پذیرش یا رد تغییرات."

    # feature loop
    - icon: "preview"
      title: "تولید پیش نمایش ها"
      content: "قابلیت ذخیره نتایج مقایسه به عنوان پیش نمایش تصویر."

    # feature loop
    - icon: "two-pager"
      title: "مقایسه محتوا"
      content: "مقایسه کامل محتوای متن در سطوح مختلف - از جمله خط به خط، پاراگراف، کلمه و تجزیه و تحلیل شخصیت، با تأکید بر تغییرات."

    # feature loop
    - icon: "format_color_text"
      title: "مقایسه سبک"
      content: "توانایی تشخیص و برجسته کردن تغییرات در عناصر قالب بندی و سبک."

    # feature loop
    - icon: "folder-managed"
      title: "تنظیم فراداده"
      content: "گزینه ای برای حفظ ابرداده از فایل های منبع یا هدف، یا اجازه دادن تنظیمات فراداده تعریف شده توسط کاربر."

    # feature loop
    - icon: "lock"
      title: "محافظت از رمز عبور"
      content: "تجزیه و تحلیل اسناد محافظت شده با رمز عبور را تسهیل می کند و محافظت از رمز عبور را برای اسناد حاصل فعال می کند."

    # feature loop
    - icon: "select"
      title: "مقایسه صفحات خاص"
      content: "بخش ها یا صفحات خاصی از یک سند را در صورت لزوم بارگیری و مقایسه کنید."

    # feature loop
    - icon: "speaker-notes"
      title: "نمایش نظرات"
      content: "انعطاف پذیری برای نمایش یا پنهان کردن نظرات هنگام بارگیری سند منبع."

############################# Code samples ############################
code_samples:
  enable: true
  title: "نمونه های کد"
  description: "برخی از موارد استفاده از عملیات معمولی GroupDocs.Comparison for Java"
  items:
    # code sample loop
    - title: "مقایسه اسناد محافظت شده با رمز عبور"
      content: |
        برای مقایسه اسنادی که [با رمز عبور محافظت شده اند](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/)، باید آن را مشخص کنید و سپس اسناد را بارگیری کنید:
        {{< landing/code title="نحوه مقایسه اسناد محافظت شده با رمز عبور">}}
        ```java {style=abap}
        // سند منبع را بارگیری کنید و رمز عبور آن را مشخص کنید
        try (Comparer comparer = new Comparer("source.docx", new LoadOptions("1234")))
        {
            // سند هدف را بارگیری کنید و رمز عبور آن را مشخص کنید
            comparer.add("target.docx", new LoadOptions("5678"));
        
            // نتیجه مقایسه را در یک فایل مشخص ذخیره کنید
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "مقایسه چندین PDF اسناد."
      content: |
        GroupDocs.Comparison به شما اجازه می دهد [بیش از دو سند را مقایسه کنید](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/). عملیات تقریبا همانند مقایسه دو فایل است. شما فقط باید فایل های هدف بیشتری را به کلاس `comparer` اضافه کنید.
        {{< landing/code title="چگونه سه یا چند سند را مقایسه کنیم.">}}
        ```java {style=abap}   
        // سند منبع را بارگیری کنید
        try (Comparer comparer = new Comparer("source.docx") 
        {
            // فایل دوم را برای مقایسه مشخص کنید
            comparer.add("target2.docx");

            // فایل سوم را برای مقایسه مشخص کنید
            comparer.add("target3.docx");

            // نتیجه مقایسه را در یک فایل مشخص ذخیره کنید
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---

