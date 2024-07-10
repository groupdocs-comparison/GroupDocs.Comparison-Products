
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
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
head_title: "{{زمان اجرا}} API مقایسه سند | بررسی کننده تفاوت"
head_description: "Python Document Comparison API ابزارهای کارآمدی برای مقایسه اسناد ارائه می دهد. برای ردیابی فوری تغییرات، یکپارچه با Python ادغام می شود"

############################# Header ############################
title: "مقایسه اسناد با Python: هر گونه تفاوت را برجسته کنید"
description: "از API GroupDocs.Comparison برای توسعه برنامه‌های کاربردی Python با ویژگی‌های مقایسه بسیار قابل تنظیم استفاده کنید. فایل‌ها، محتوای آن‌ها و سبک‌های متن را بین قالب‌های سند مشابه مقایسه کنید."
words:
  for: "برای"

actions:
  main: "دانلود رایگان PyPi"
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
  title: "مقایسه تصاویر BMP در Python"
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
  description: "یک API برای مقایسه انواع سند محبوب مانند PDF، Microsoft Office، HTML، ایمیل‌ها یا تصاویر در برنامه‌های Python."
  features:
    # feature loop
    - title: "گزارش های خروجی تفصیلی"
      content: "GroupDocs.Comparison تغییرات در محتوای سند (شخصیت‌ها، کلمات، پاراگراف‌ها، جداول، نمودارها) و همچنین تغییرات در سبک سند را مشخص می‌کند. گزارشی حاوی اطلاعات دقیق در مورد تفاوت ها، از جمله تعداد و نوع آنها، در اختیار کاربران قرار می دهد."

    # feature loop
    - title: "از فرمت های محبوب فایل و سند پشتیبانی می کند"
      content: "با استفاده از API GroupDocs.Comparison می‌توانید اسناد را در قالب‌هایی مانند PDF، HTML، ایمیل، Microsoft Office Word، صفحات گسترده اکسل، ارائه‌های PowerPoint، OneNote، نمودارهای Visio، فایل‌های متنی، JPEG، PNG، GIF، تصاویر BMP، به طور مؤثر مقایسه کنید. و بسیاری از فرمت های دیگر"

    # feature loop
    - title: "مستندات و مثال های جامع"
      content: "اسناد و نمونه‌های کد گسترده‌ای برای استفاده از کتابخانه مقایسه در پلتفرم‌های مختلف موجود است که ادغام API GroupDocs.Comparison را در برنامه Python آسان می‌کند."

    # feature loop
    - title: "تغییرات را در یک فایل انتخاب و ادغام کنید"
      content: "اگر نسخه‌های مختلفی از یک سند دارید، می‌توانید تغییرات خاصی را انتخاب کنید و با استفاده از کتابخانه GroupDocs.Comparison یک سند جدید را کامپایل کنید."

############################# Platforms ############################
platforms:
  enable: true
  title: "استقلال پلت فرم"
  description: "GroupDocs.Comparison for Python via .NET سیستم‌عامل‌ها، چارچوب‌ها و مدیریت بسته‌های زیر را پشتیبانی می‌کند"
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
    GroupDocs.Comparison for Python via .NET از عملیات با [قالب‌های فایل](https://docs.groupdocs.com/comparison/net/supported-document-formats/) پشتیبانی می‌کند.
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
  title: "ویژگی های GroupDocs.Comparison for Python via .NET"
  description: "اسناد، تصاویر و سایر فرمت های PDF و Office را به راحتی مقایسه کنید."

  items:
    # feature loop
    - icon: "compare"
      title: "مقایسه اسناد کاربرپسند"
      content: "تجزیه و تحلیل و شناسایی تفاوت بین دو سند."

    # feature loop
    - icon: "note-stack"
      title: "مقایسه چندین سند"
      content: "تجزیه و تحلیل و شناسایی تفاوت ها در چندین سند به طور همزمان."

    # feature loop
    - icon: "stacks"
      title: "فرمت های پشتیبانی شده"
      content: "پشتیبانی از بیش از 50 فرمت سند محبوب از دسته های مختلف."

    # feature loop
    - icon: "rule"
      title: "پذیرش یا رد تغییرات"
      content: "نمایش تصویری واضح تغییرات شناسایی شده، با گزینه پذیرش یا رد تغییرات."

    # feature loop
    - icon: "preview"
      title: "ایجاد پیش نمایش"
      content: "نتایج مقایسه را به صورت تصویر ذخیره کنید."

    # feature loop
    - icon: "two-pager"
      title: "مقایسه محتوا"
      content: "محتوای متن را خط به خط، بر اساس پاراگراف ها، کلمات یا نویسه ها مقایسه کنید. تغییرات را برجسته کنید."

    # feature loop
    - icon: "format_color_text"
      title: "مقایسه سبک"
      content: "تشخیص تغییرات در قالب بندی و سبک."

    # feature loop
    - icon: "folder-managed"
      title: "متادیتا را تنظیم کنید"
      content: "ابرداده‌ها را از فایل‌های منبع یا مقصد حفظ کنید یا اجازه دهید توسط کاربران مشخص شود."

    # feature loop
    - icon: "lock"
      title: "حفاظت از رمز عبور"
      content: "اسناد رمزگذاری شده را تجزیه و تحلیل کنید یا سند حاصل را با رمز عبور ایمن کنید."

    # feature loop
    - icon: "select"
      title: "مقایسه صفحات خاص"
      content: "بخش ها یا صفحات خاصی از یک سند را بارگیری و مقایسه کنید."

    # feature loop
    - icon: "speaker-notes"
      title: "نمایش نظرات"
      content: "هنگام بارگیری سند منبع، پنهان کردن یا نمایش نظرات را انتخاب کنید."

############################# Code samples ############################
code_samples:
  enable: true
  title: "نمونه های کد"
  description: "موارد استفاده معمولی از عملیات GroupDocs.Comparison for Python via .NET را کاوش کنید"
  items:
    # code sample loop
    - title: "مقایسه اسناد محافظت شده با رمز عبور"
      content: |
        برای مقایسه اسنادی که [با رمز عبور محافظت می‌شوند](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/)، باید رمز عبور را هنگام بارگیری اسناد مشخص کنید:
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