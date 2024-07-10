
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: fa
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
head_title: "C# .NET نرم افزار مقایسه اسناد | چک کننده تفاوت"
head_description: "C# .NET نرم افزار برای مقایسه سبک سند و محتوا. اسناد چندین فرمت پشتیبانی شده را برای شناسایی تغییرات بین فایل ها مقایسه کنید."

############################# Header ############################
title: "اسناد را با سهولت در راه حل های C# .NET خود مقایسه کنید"
description: "C# برنامه را با API مقایسه اسناد انعطاف پذیر بسازید که مقایسه فایل ها را بر اساس محتوا و سبک در فرمت های مختلف سند امکان پذیر می کند."
words:
  for: "برای"

actions:
  main: "دانلود رایگان NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Comparison"
  alt: "صدور مجوز"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/net/"
  title: "آماده شروع هستید؟"
  description: "ویژگی های GroupDocs.Comparison را به صورت رایگان امتحان کنید یا مجوز درخواست کنید"

release:
  title: "نسخه {0} منتشر شد"
  notes: "چیزهای جدید را ببینید"
  downloads: "دانلودها"

code:
  title: "مقایسه DOCX فایل ها در C#"
  more: "نمونه های بیشتر"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET"
  install: "dotnet add package GroupDocs.Comparison"
  content: |
    ```csharp {style=abap}   
    // سند منبع را مشخص کنید
    using (Comparer comparer = new Comparer("source.docx"))
    {
        // اضافه کردن یک یا چند سند هدف
        comparer.Add("target.docx");

        // گزینه های مقایسه را مشخص کنید
        CompareOptions options = new CompareOptions() 
        {ShowRevisions = false};

        // مقایسه و ذخیره نتیجه
        comparer.Compare("result.docx", options);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison در یک نگاه"
  description: "API برای مقایسه تفاوت بین اسناد در .NET برنامه"
  features:
    # feature loop
    - title: "مقایسه فایل در C#"
      content: "تفاوت بین فایل های منبع و هدف را برای تغییرات در پاراگراف ها، کلمات و سطح کاراکتر شناسایی کنید. تغییرات سبک و قالب بندی مانند پررنگ، ایتالیک، زیرنویس، ضریب خط، انواع فونت و غیره را شناسایی کنید."

    # feature loop
    - title: "محبوب ترین فرمت های فایل و سند پشتیبانی می شوند"
      content: "GroupDocs.Comparison API امکان مقایسه سند کارآمد در طیف گسترده ای از فرمت ها، از جمله PDF، HTML، ایمیل، Microsoft Office اسناد (Word، Excel، PowerPoint، OneNote، Visio)، انواع مختلف تصویر (JPEG، PNG، GIF، BMP)، فایل های متنی و موارد دیگر را فراهم می کند."

    # feature loop
    - title: "اعمال یا رد تغییرات به راحتی"
      content: "هر تفاوت شناسایی شده در اسناد مقایسه شده با استفاده از GroupDocs.Comparison API می تواند به طور انتخابی اعمال شود یا رد شود و سفارشی سازی را قبل از صادرات به سند خروجی نهایی امکان پذیر می کند."

    # feature loop
    - title: "گزارش خلاصه مقایسه"
      content: "یک گزارش خلاصه از تفاوت ها، با جزئیات تمام تغییرات موجود در اسناد مقایسه شده تهیه کنید و آن را برای مرجع ذخیره کنید."

############################# Platforms ############################
platforms:
  enable: true
  title: "استقلال پلت فرم"
  description: "GroupDocs.Comparison for .NET از سیستم عامل ها، چارچوب ها و مدیران بسته زیر پشتیبانی می کند"
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
  title: "فرمت های فایل پشتیبانی شده"
  description: |
    GroupDocs.Comparison for .NET از عملیات با [ زیر پشتیبانی می کند فرمت های فایل](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
      content: "تجزیه و تحلیل و شناسایی تفاوت بین دو سند."

    # feature loop
    - icon: "note-stack"
      title: "مقایسه چندین اسناد"
      content: "به طور همزمان تفاوت ها را بین چندین سند تجزیه و تحلیل و شناسایی کنید."

    # feature loop
    - icon: "stacks"
      title: "فرمت های پشتیبانی شده"
      content: "سازگار با بیش از 50 فرمت سند پرکاربرد از دسته های مختلف، و کاربرد گسترده را تضمین می کند."

    # feature loop
    - icon: "rule"
      title: "پذیرش یا رد تغییرات"
      content: "نمایش بصری تغییرات شناسایی شده را پاک کنید، همراه با گزینه هایی برای پذیرش یا رد این تغییرات."

    # feature loop
    - icon: "preview"
      title: "تولید پیش نمایش ها"
      content: "امکان ذخیره نتایج مقایسه به عنوان پیش نمایش تصویر برای مرجع آسان و به اشتراک گذاری."

    # feature loop
    - icon: "two-pager"
      title: "مقایسه محتوا"
      content: "مقایسه کامل متن را در سطوح مختلف - از جمله خط به خط، پاراگراف، کلمه و شخصیت - با تفاوت های برجسته برای وضوح بهتر انجام دهید."

    # feature loop
    - icon: "format_color_text"
      title: "مقایسه سبک و قالب بندی"
      content: "تغییرات در قالب بندی و سبک سند را تشخیص داده و برجسته می کند و بررسی جامع را تضمین می کند."

    # feature loop
    - icon: "folder-managed"
      title: "تنظیمات ابرداده انعطاف"
      content: "فراداده را از فایل های منبع یا هدف حفظ کنید یا آن را با توجه به ترجیحات کاربر سفارشی کنید."

    # feature loop
    - icon: "lock"
      title: "محافظت از رمز عبور"
      content: "اسناد محافظت شده با رمز عبور را تجزیه و تحلیل کنید و سند خروجی را با رمزگذاری رمز عبور برای امنیت بیشتر ایمن کنید."

    # feature loop
    - icon: "select"
      title: "مقایسه صفحه انتخابی"
      content: "بخش ها یا صفحات خاصی از یک سند را برای تجزیه و تحلیل هدفمند بارگیری و مقایسه کنید."

    # feature loop
    - icon: "speaker-notes"
      title: "نمایش نظرات"
      content: "هنگام بارگذاری سند منبع، نمایش یا پنهان کردن نظرات را انتخاب کنید و کنترل بیشتری بر روند مقایسه را ارائه دهید."

############################# Code samples ############################
code_samples:
  enable: true
  title: "نمونه های کد"
  description: "برخی از موارد استفاده از عملیات معمولی GroupDocs.Comparison for .NET"
  items:
    # code sample loop
    - title: "مقایسه اسناد محافظت شده با رمز عبور"
      content: |
        برای مقایسه اسنادی که [با رمز عبور محافظت شده اند](https://docs.groupdocs.com/comparison/net/load-password-protected-documents/)، باید آن را مشخص کنید و سپس اسناد را بارگیری کنید:
        {{< landing/code title="نحوه مقایسه اسناد محافظت شده با رمز عبور">}}
        ```csharp {style=abap}
        // سند منبع را بارگیری کنید و رمز عبور آن را مشخص کنید
        using(Comparer comparer = new Comparer("source.docx", new LoadOptions() {Password = "1234"}))  
        {
            // سند هدف را بارگیری کنید و رمز عبور آن را مشخص کنید
            comparer.Add("target.docx", new LoadOptions() {Password = "5678"});

            // نتیجه مقایسه را در یک فایل مشخص ذخیره کنید
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "مقایسه چندین PDF اسناد."
      content: |
        GroupDocs.Comparison به شما اجازه می دهد [بیش از دو سند را مقایسه کنید](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/). عملیات تقریبا همانند مقایسه دو فایل است. شما فقط باید فایل های هدف بیشتری را به کلاس `comparer` اضافه کنید.
        {{< landing/code title="چگونه سه یا چند سند را مقایسه کنیم.">}}
        ```csharp {style=abap}   
        // سند منبع را بارگیری کنید
        using(Comparer comparer = new Comparer("source.docx") 
        {
            // فایل دوم را برای مقایسه مشخص کنید
            comparer.Add("target2.docx");
            
            // فایل سوم را برای مقایسه مشخص کنید
            comparer.Add("target3.docx");
            
            // نتیجه مقایسه را در یک فایل مشخص ذخیره کنید
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---
