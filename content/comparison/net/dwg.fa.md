
---
############################# Static ############################
layout: "format"
date:  2024-03-21T15:26:19
draft: false
lang: fa
format: Dwg
product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "مقایسه فایل های DWG با نرم افزار مقایسه C#"
head_description: "مقایسه و ادغام DWG فایل ها در C# .NET برنامه ها. خلاصه تفاوت ها را در محتوا، متن و سبک بازیابی کنید."

############################# Header ############################
title: "مقایسه DWG در C# .NET" 
description: ".NET API مقایسه اسناد را برای بررسی اختلافات بین دو نسخه از DWG فایل ها و صادرات به یک سند نهایی با خلاصه مفصلی از تفاوت بین اسناد مقایسه شده."
subtitle: "راه حل مقایسه اسناد" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "دانلود رایگان Nuget"
      link: "https://releases.groupdocs.com/comparison/net/"
      
############################# About ############################
about:
    enable: true
    title: "مزایای GroupDocs.Comparison for .NET API را کشف کنید"
    link: "/comparison/net/"
    link_title: "بیشتر بدانید"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison for .NET یک API بومی .NET است که برای مقایسه چندین تصویر و اسناد با همان فرمت طراحی شده است. به تشخیص تفاوت در پاراگراف ها، کلمات، کاراکترها، اشکال و حتی سبک های متن اسناد مقایسه شده کمک می کند. با توانایی ادغام این تغییرات و صادرات به یک سند نهایی، از مقایسه و ادغام PDF s، Word سند، Excel صفحه گسترده، PowerPoint ارائه، Visio نمودار، Outlook ایمیل، HTML، نقشه ها و قالب های مختلف فایل تصویری پشتیبانی می کند - همه بدون نیاز به کتابخانه های خارجی.

############################# Steps ############################
steps:
    enable: true
    title: "نحوه مقایسه چندین فایل DWG با استفاده از C#"
    content: |
      امکان استفاده از [GroupDocs.Comparison](https://products.groupdocs.com/comparison/net/) برای دریافت گزارش در مورد تفاوت در بسیاری از فایل های DWG وجود دارد.
      
      1. GroupDocs.Comparison for .NET را از [Nuget](https://www.nuget.org/packages/GroupDocs.Comparison) با استفاده از مدیر بسته مورد علاقه خود نصب کنید
      2. یک نمونه از کلاس Comparer را با مسیر کامل به فایل اولیه DWG ارائه دهید
      3. حداقل یک DWG دیگر را به مقایسه اضافه کنید
      4. یک گزارش نهایی با تفاوت های دقیق توصیف شده دریافت کنید
   
    code:
      platform: "net"
      copy_title: "کپی کردن"
      install:
        command: "dotnet add package GroupDocs.Comparison"
        copy_tip: "برای کپی کلیک کنید"
        copy_done: "کپی شده"
      links:
        #  loop
        - title: "نمونه های بیشتر"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET"
        #  loop
        - title: "مستندات"
          link: "https://docs.groupdocs.com/comparison/net/"
          
      content: |
        ```csharp {style=abap}

        // مقایسه چندین اسناد از دیسک محلی

        // Comparer Instantiate که اولین فایل را ارائه می دهد
        using (Comparer comparer = new Comparer("main_document.dwg"))
        {
            // اضافه کردن فایل های دیگر
        	comparer.Add("modified_1.dwg");
            comparer.Add("modified_2.dwg");

            // دریافت فایل نتیجه با نام مشخص شده
            comparer.Compare("report.dwg"); 
        }
        
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "آماده شروع هستید؟"
  description: "ویژگی های GroupDocs.Comparison را به صورت رایگان امتحان کنید یا مجوز درخواست کنید"
  items:
    #  loop
    - title: "Nuget دانلود"
      link: "https://releases.groupdocs.com/comparison/net/"
      color: "red"
        #  loop
    - title: "صدور مجوز"
      link: "https://purchase.groupdocs.com/pricing/comparison/net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "مقایسه فرمت های محبوب فایل با استفاده از C#"
    exclude: "DWG"
    description: ".NET API برای مقایسه فرمت های سند. در مورد تغییرات در مدارک خود بدون تلاش اضافی در مورد پردازش آنها مطلع باشید."
    items: 
        # format loop 1
        - name: "مقایسه فایل های PDF"
          format: "PDF"
          link: "/comparison/net/pdf/"
          description: "ادوبی Portable فرمت سند"

        # format loop 2
        - name: "مقایسه فایل های DOCX"
          format: "DOCX"
          link: "/comparison/net/docx/"
          description: "مایکروسافت Word سند XML باز"

        # format loop 3
        - name: "مقایسه RTF فایل ها"
          format: "RTF"
          link: "/comparison/net/rtf/"
          description: "فرمت فایل متنی غنی"

        # format loop 4
        - name: "مقایسه TXT فایل ها"
          format: "TXT"
          link: "/comparison/net/txt/"
          description: "فرمت فایل متن ساده"

        # format loop 5
        - name: "مقایسه فایل های XLSX"
          format: "XLSX"
          link: "/comparison/net/xlsx/"
          description: "مایکروسافت Excel صفحه گسترده XML باز"

        # format loop 6
        - name: "مقایسه فایل های CSV"
          format: "CSV"
          link: "/comparison/net/csv/"
          description: "فایل مقادیر جدا شده با کاما"

        # format loop 7
        - name: "مقایسه فایل های PPTX"
          format: "PPTX"
          link: "/comparison/net/pptx/"
          description: "PowerPoint ارائه اکس‌ام‌ال باز"

        # format loop 8
        - name: "مقایسه فایل های ODS"
          format: "ODS"
          link: "/comparison/net/ods/"
          description: "Open Document صفحه گسترده"

        # format loop 9
        - name: "مقایسه فایل های ODP"
          format: "ODP"
          link: "/comparison/net/odp/"
          description: "OpenDocument فرمت فایل ارائه"

        # format loop 10
        - name: "مقایسه ODT فایل ها"
          format: "ODT"
          link: "/comparison/net/odt/"
          description: "Open Document متن"

        # format loop 11
        - name: "مقایسه فایل های JPEG"
          format: "JPEG"
          link: "/comparison/net/jpeg/"
          description: "JPEG تصویر"

        # format loop 12
        - name: "مقایسه فایل های PNG"
          format: "PNG"
          link: "/comparison/net/png/"
          description: "Portable گرافیک شبکه"

        # format loop 13
        - name: "مقایسه فایل های GIF"
          format: "GIF"
          link: "/comparison/net/gif/"
          description: "فایل فرمت تبادل گرافیکی"

        # format loop 14
        - name: "مقایسه فایل های BMP"
          format: "BMP"
          link: "/comparison/net/bmp/"
          description: "فرمت فایل بیت مپ"

        # format loop 15
        - name: "مقایسه فایل های HTML"
          format: "HTML"
          link: "/comparison/net/html/"
          description: "زبان نشانه گذاری هایپر متن"

        # format loop 16
        - name: "مقایسه فایل های MSG"
          format: "MSG"
          link: "/comparison/net/msg/"
          description: "پیام ایمیل مایکروسافت Outlook"

        # format loop 17
        - name: "مقایسه ONE فایل ها"
          format: "ONE"
          link: "/comparison/net/one/"
          description: "مایکروسافت OneNote"

        # format loop 18
        - name: "مقایسه VSDX فایل ها"
          format: "VSDX"
          link: "/comparison/net/vsdx/"
          description: "مایکروسافت Visio نقاشی"

        # format loop 19
        - name: "مقایسه فایل های CS"
          format: "CS"
          link: "/comparison/net/cs/"
          description: "زبان سی شارپ"

        # format loop 20
        - name: "مقایسه Java فایل ها"
          format: "Java"
          link: "/comparison/net/java/"
          description: "Java زبان"
          
        # format loop 21
        - name: "مقایسه فایل های CPP"
          format: "CPP"
          link: "/comparison/net/cpp/"
          description: "زبان سی++"
---