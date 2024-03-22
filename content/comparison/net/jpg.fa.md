
---
############################# Static ############################
layout: "format"
date:  2024-03-22T13:27:44
draft: false
lang: fa
format: Jpg
product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "GroupDocs.Comparison for .NET API برای مقایسه JPG"
head_description: "API GroupDocs.Comparison for .NET امکان جمع آوری داده ها در مورد تمایز در JPG تصاویر و ادغام آن در C# .NET برنامه ها را فراهم می کند."

############################# Header ############################
title: "مقایسه تغییرات در JPG تصاویر با .NET تکنولوژی" 
description: "به سرعت و به راحتی داده ها را در مورد تغییرات در JPG فایل ها با استفاده از GroupDocs.Comparison for .NET API جمع آوری و گزارش دهید. راه حل های اصلی کسب و کار C#، ASP .NET، VB .NET و .NET را با نرم افزار ما برای به دست آوردن بینش ارزشمند بهبود ببخشید."
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
    title: "کاوش در ویژگی های GroupDocs.Comparison for .NET API"
    link: "/comparison/net/"
    link_title: "بیشتر بدانید"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       API GroupDocs.Comparison for .NET قابلیت های گسترده ای را برای مقایسه JPG تصاویر ارائه می دهد و گزارش هایی حاوی تمایز در تصاویر انتخاب شده را تولید می کند. نرم افزار ما بدون نیاز به کتابخانه های اضافی به طور یکپارچه در C# پروژه ادغام می شود و به شما امکان می دهد با کمترین کد به اهداف خود برسید.

############################# Steps ############################
steps:
    enable: true
    title: "مقایسه JPG تصاویر با استفاده از C#"
    content: |
      مدیریت محتوای فایل JPG با [GroupDocs.Comparison](https://products.groupdocs.com/comparison/net/)
      
      1. GroupDocs.Comparison for .NET را از [Nuget](https://www.nuget.org/packages/GroupDocs.Comparison) بدست آورید و آن را در پروژه خود ادغام کنید
      2. شیء Comparer را نمونه سازی کنید و مسیر تصویر JPG را مشخص کنید
      3. تصویر JPG دیگری را برای تجزیه و تحلیل اضافه کنید
      4. گزارش ذخیره شده در دیسک محلی را مرور کنید
   
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

        // یک گزارش با جزئیات تفاوت در JPG تصاویر ایجاد کنید

        // مسیر اصلی فایل را به سازنده Comparer ارائه دهید
        using (Comparer comparer = new Comparer("source.jpg"))
        {
            // مسیرها را برای تصاویر اضافی JPG مشخص کنید
        	comparer.Add("file_to_compare_1.jpg");
            comparer.Add("file_to_compare_2.jpg");
            comparer.Add("file_to_compare_3.jpg");

            // گزارش حاصل را در یک فایل ذخیره کنید
            comparer.Compare("result.jpg"); 
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
    title: "JPG مقایسه تصویر با .NET"
    exclude: "JPG"
    description: "به راحتی تغییرات در JPG فایل را با استفاده از راه حل GroupDocs.Comparison for .NET تجزیه و تحلیل کنید."
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