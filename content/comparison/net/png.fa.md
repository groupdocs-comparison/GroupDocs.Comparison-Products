
---
############################# Static ############################
layout: "format"
date:  2024-03-22T13:27:44
draft: false
lang: fa
format: Png
product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "PNG بررسی تفاوت ها توسط GroupDocs.Comparison for .NET"
head_description: "GroupDocs.Comparison for .NET اجازه می دهد تا گزارش هایی درباره تمایز در PNG تصاویر برای برنامه های کاربردی بر اساس C# و .NET تولید کنید"

############################# Header ############################
title: "مقایسه PNG تصاویر از طریق C# .NET برنامه های کاربردی" 
description: "GroupDocs.Comparison for .NET API هر گونه تفاوت بین PNG فایل ها را به سرعت و به راحتی جستجو می کند. برای به دست آوردن گزارش های مقایسه، برنامه های کاربردی C#، ASP .NET، VB .NET و .NET را بهبود ببخشید."
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
    title: "کشف GroupDocs.Comparison for .NET ویژگی های API"
    link: "/comparison/net/"
    link_title: "بیشتر بدانید"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison for .NET API برای مقایسه چندین PNG تصویر و تهیه گزارش های پیچیده در مورد هر گونه تمایز در چنین تصاویری طراحی شده است. ممکن است بدون نصب نرم افزار شخص ثالث در .NET برنامه های شما استفاده شود. از GroupDocs.Comparison for .NET با اضافه کردن چند خط کد با بسیاری از ویژگی های مفید خارج از جعبه استفاده کنید.

############################# Steps ############################
steps:
    enable: true
    title: "نحوه مقایسه PNG تصاویر توسط C#"
    content: |
      گزارش ساخت تفاوت ها را در PNG تصاویر توسط [GroupDocs.Comparison](https://products.groupdocs.com/comparison/net/) توصیف می کند
      
      1. دانلود و نصب GroupDocs.Comparison for .NET از [Nuget](https://www.nuget.org/packages/GroupDocs.Comparison)
      2. شیء Comparer Instantiate که مسیر را به تصویر PNG ارائه می دهد
      3. PNG فایل های دیگر را برای مقایسه درگیر کنید
      4. دریافت گزارش نهایی که تغییرات تصاویر را نشان می دهد
   
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

        // ایجاد گزارش در مورد تغییرات در PNG تصاویر

        // Create Comparer با اشاره به اولین فایل
        using (Comparer comparer = new Comparer("source.png"))
        {
            // تصاویر دیگر را در فرآیند مقایسه درگیر کنید
        	comparer.Add("file_to_compare_1.png");
            comparer.Add("file_to_compare_2.png");
            comparer.Add("file_to_compare_3.png");

            // از گزارش حاصل لذت ببرید
            comparer.Compare("result.png"); 
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
    title: "مقایسه PNG تصاویر توسط C# و .NET"
    exclude: "PNG"
    description: ".NET API برای مقایسه تصاویر PNG. اطلاعات مربوط به هرگونه تغییر در فایل ها را بدون تلاش اضافی دریافت کنید."
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