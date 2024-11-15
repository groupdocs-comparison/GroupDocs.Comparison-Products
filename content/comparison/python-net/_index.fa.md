
---
############################# Static ############################
layout: "landing"
date: 2024-11-14T22:58:46
draft: false

lang: fa
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
head_title: "Python ابزار مقایسه اسناد | تجزیه و تحلیل اسناد"
head_description: "برای تجزیه و تحلیل کامل اسناد، قدرت ابزار مقایسه اسناد Python را کشف کنید. برای ردیابی جامع تغییرات، بدون زحمت با Python ادغام می شود."

############################# Header ############################
title: "مقایسه اسناد با Python: هر گونه تفاوت را برجسته کنید"
description: "از API GroupDocs.Comparison برای ایجاد برنامه های بومی در پایتون با قابلیت های مقایسه قابل تنظیم استفاده کنید. فایل‌ها، محتوای آن‌ها و تغییرات سبک در قالب‌های سند را بررسی کنید."
words:
  for: "برای"

actions:
  main: "اکنون دانلود رایگان PyPi خود را دریافت کنید"
  main_link: "https://pypi.org/project/groupdocs-comparison-net/"
  alt: "صدور مجوز"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/python-net/"
  title: "آماده شروع هستید؟"
  description: "ویژگی های GroupDocs.Comparison را به صورت رایگان امتحان کنید یا مجوز درخواست کنید"

release:
  title: "نسخه {0} منتشر شد"
  notes: "چیزهای جدید را ببینید"
  downloads: "دانلودها"

code:
  title: "مقایسه تصاویر BMP با استفاده از Python"
  more: "نمونه های بیشتر"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET/"
  install: "pip install groupdocs-comparison-net"
  content: |
    ```python {style=abap}
    def run():

        # سند منبع را مشخص کنید
        with groupdocs.comparison.Comparer("in.bmp") as comparer:

            # اضافه کردن یک یا چند سند هدف
            comparer.add("target.bmp")

            # گزینه های مقایسه را مشخص کنید
            options = new groupdocs.comparison.CompareOptions()
            options.setGenerateSummaryPage(false)

            # مقایسه و ذخیره نتیجه
            comparer.compare("result.bmp", options)
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison در یک نگاه"
  description: "یک API طراحی شده برای مقایسه انواع اسناد پرکاربرد مانند PDF، فایل‌های Microsoft Office، HTML، ایمیل‌ها یا تصاویر در برنامه‌های Python."
  features:
    # feature loop
    - title: "گزارشات خروجی جامع"
      content: "GroupDocs.Comparison تغییرات در محتوای سند (نویسه‌ها، کلمات، پاراگراف‌ها، جداول، نمودارها) و همچنین تغییرات سبک سند را تشخیص می‌دهد. کاربران گزارش مفصلی دریافت می کنند که ماهیت و تعداد تغییرات را برجسته می کند."

    # feature loop
    - title: "طیف گسترده ای از فرمت های فایل و سند"
      content: "API GroupDocs.Comparison به شما امکان می‌دهد اسناد را در قالب‌هایی مانند PDF، HTML، ایمیل، Microsoft Office Word، کتاب‌های کار اکسل، فایل‌های PowerPoint، یادداشت‌های OneNote، نمودارهای Visio، اسناد متنی، JPEG، PNG، GIF، تصاویر BMP، مقایسه کنید. در میان بسیاری دیگر."

    # feature loop
    - title: "اسناد کامل و نمونه کد"
      content: "اسناد عمیق و کدهای نمونه برای کتابخانه مقایسه در پلتفرم های مختلف به راحتی در دسترس هستند و ادغام GroupDocs.Comparison API را در برنامه های پایتون شما ساده می کند."

    # feature loop
    - title: "تغییرات را در یک سند انتخاب و ترکیب کنید"
      content: "اگر نسخه‌های مختلفی از یک سند دارید، می‌توانید با استفاده از کتابخانه GroupDocs.Comparison تغییرات را به صورت انتخابی در یک فایل جدید کامپایل کنید."

############################# Platforms ############################
platforms:
  enable: true
  title: "استقلال پلت فرم"
  description: "GroupDocs.Comparison for Python via .NET با سیستم‌عامل‌ها، چارچوب‌ها و مدیران بسته‌های زیر سازگار است."
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
    GroupDocs.Comparison for Python via .NET می‌تواند با [فرمت‌های فایل] زیر (https://docs.groupdocs.com/comparison/net/supported-document-formats/) کار کند.
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
  title: "قابلیت های GroupDocs.Comparison for Python via .NET"
  description: "فایل‌های PDF، اسناد آفیس، تصاویر و طیف گسترده‌ای از فرمت‌های دیگر را به‌طور یکپارچه مقایسه کنید."

  items:
    # feature loop
    - icon: "compare"
      title: "مقایسه اسناد بصری"
      content: "تفاوت بین دو سند را بررسی و برجسته کنید."

    # feature loop
    - icon: "note-stack"
      title: "مقایسه اسناد چندگانه"
      content: "چندین سند را برای تفاوت ها به طور همزمان بررسی کنید."

    # feature loop
    - icon: "stacks"
      title: "پشتیبانی فرمت گسترده"
      content: "سازگار با بیش از 50 فرمت سند رایج در دسته های مختلف."

    # feature loop
    - icon: "rule"
      title: "پذیرش یا رد تغییرات"
      content: "تغییرات را با وضوح تجسم کنید، گزینه هایی برای پذیرش یا رد ویرایش ها ارائه دهید."

    # feature loop
    - icon: "preview"
      title: "ایجاد پیش نمایش های بصری"
      content: "پیش نمایش نتایج مقایسه را در قالب های تصویر ایجاد کنید."

    # feature loop
    - icon: "two-pager"
      title: "مقایسه محتوای مبتنی بر متن"
      content: "برای برجسته کردن تغییرات، مقایسه خط به خط، پاراگراف، کلمه یا کاراکتر را انجام دهید."

    # feature loop
    - icon: "format_color_text"
      title: "تشخیص تغییرات قالب بندی"
      content: "تغییرات در سبک سند و قالب بندی را شناسایی کنید."

    # feature loop
    - icon: "folder-managed"
      title: "مدیریت فراداده قابل تنظیم"
      content: "ابرداده‌ها را از فایل‌های منبع یا هدف حفظ کنید، یا به کاربران اجازه دهید تا ابرداده‌های جدیدی را تعریف کنند."

    # feature loop
    - icon: "lock"
      title: "فایل های محافظت شده با رمز عبور را مدیریت کنید"
      content: "با اسناد رمزگذاری شده کار کنید یا اسناد ایمن و محافظت شده با رمز عبور ایجاد کنید."

    # feature loop
    - icon: "select"
      title: "مقایسه صفحات متمرکز"
      content: "بخش های خاص یا صفحات جداگانه یک سند را انتخاب و مقایسه کنید."

    # feature loop
    - icon: "speaker-notes"
      title: "مشاهده دیدگاه را مدیریت کنید"
      content: "هنگام بررسی سند منبع، تصمیم بگیرید که نظرات را آشکار یا پنهان کنید."

############################# Code samples ############################
code_samples:
  enable: true
  title: "نمونه های کد"
  description: "سناریوهای رایج برای استفاده از عملکردهای GroupDocs.Comparison for Python via .NET را کشف کنید."
  items:
    # code sample loop
    - title: "مقایسه اسناد با محافظت از رمز عبور"
      content: |
        برای مقایسه اسنادی که [با رمز عبور ایمن هستند] (https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/)، باید رمز عبور را هنگام بارگیری اسناد مشخص کنید:
        {{< landing/code title="نحوه مقایسه اسناد محافظت شده با رمز عبور">}}
        ```python {style=abap}
        def run():

            # سند منبع را بارگیری کنید و رمز عبور آن را مشخص کنید
            with groupdocs.comparison.Comparer("source.docx", new LoadOptions("1234")) as comparer:

                # سند هدف را بارگیری کنید و رمز عبور آن را مشخص کنید
                comparer.add("target.docx", new LoadOptions("5678"));

                # نتیجه مقایسه را در یک فایل مشخص ذخیره کنید
                comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "مقایسه چندین PDF اسناد."
      content: |
        GroupDocs.Comparison به شما اجازه می دهد [بیش از دو سند را مقایسه کنید](https://docs.groupdocs.com/comparison/python-net/compare-multiple-documents/). عملیات تقریبا همانند مقایسه دو فایل است. شما فقط باید فایل های هدف بیشتری را به کلاس `comparer` اضافه کنید.
        {{< landing/code title="چگونه سه یا چند سند را مقایسه کنیم.">}}
        ```python {style=abap}
        def run():

            # سند منبع را بارگیری کنید
            with groupdocs.comparison.Comparer(source.pdf") as comparer:

                # فایل دوم را برای مقایسه مشخص کنید
                comparer.add("target2.pdf");

                # فایل سوم را برای مقایسه مشخص کنید
                comparer.add("target3.pdf");

                # نتیجه مقایسه را در یک فایل مشخص ذخیره کنید
                comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---