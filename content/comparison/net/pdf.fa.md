
---
############################# Static ############################
layout: "format"
date:  2024-03-22T13:27:44
draft: false
lang: fa
format: Pdf
product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "بررسی PDF اسناد مختلف در C# .NET"
head_description: "مقایسه و ادغام بیش از دو فایل PDF در C# .NET برنامه ها. خلاصه تفاوت ها را در محتوا، متن و سبک PDF فایل بازیابی کنید."

############################# Header ############################
title: "مقایسه PDF اسناد در C# .NET برنامه" 
description: ".NET API مقایسه اسناد برای شناسایی و نمایش تفاوت در PDF s در برنامه های کاربردی مبتنی بر C#، ASP .NET، VB .NET و .NET Core. بدون زحمت گزارش های دقیق را برای یک تجربه یکپارچه دریافت کنید."
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
       گزارش های دقیق در مورد تفاوت ها را در PDF اسناد در .NET برنامه های خود دریافت کنید. PDF متمایز را با یک فایل جدید با همان فرمت ادغام کنید. از GroupDocs.Comparison for .NET API ها با اضافه کردن چند خط کد استفاده کنید. پردازش PDF s و سایر فرمت ها بدون نرم افزار شخص ثالث.

############################# Steps ############################
steps:
    enable: true
    title: "نحوه مقایسه PDF s با استفاده از C#"
    content: |
      دریافت گزارش در مورد تفاوت در بسیاری از فایل های PDF با استفاده از [GroupDocs.Comparison](https://products.groupdocs.com/comparison/net/)
      
      1. GroupDocs.Comparison for .NET را از [Nuget](https://www.nuget.org/packages/GroupDocs.Comparison) دریافت کنید و آن را نصب کنید
      2. ایجاد نمونه Comparer کاملاً جدید با مسیر فایل PDF
      3. افزودن دیگر PDF به مقایسه
      4. نتیجه شامل گزارشی در مورد تمایز در هر دو PDF s
   
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

        // تهیه گزارش تمایز PDF

        // مقایسه نمونه‌ای با مسیر به یک فایل اول
        using (Comparer comparer = new Comparer("source.pdf"))
        {
            // یک یا چند PDF s را به مقایسه اضافه کنید
        	comparer.Add("file_to_compare_1.pdf");
            comparer.Add("file_to_compare_2.pdf");
            comparer.Add("file_to_compare_3.pdf");

            // گزارش نتایج مورد تجزیه و تحلیل
            comparer.Compare("result.pdf"); 
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
    title: "PDF s را با استفاده از C# مقایسه کنید و گزارش کامل دریافت کنید"
    exclude: "PDF"
    description: ".NET C# نرم افزار برای مقایسه PDF اسناد. در مورد هرگونه تغییر در اسناد خود به راحتی مطلع باشید."
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