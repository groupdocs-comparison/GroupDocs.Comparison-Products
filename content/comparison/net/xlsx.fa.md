
---
############################# Static ############################
layout: "format"
date:  2024-03-22T13:27:44
draft: false
lang: fa
format: Xlsx
product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "MS Excel مقایسه صفحه گسترده"
head_description: "GroupDocs.Comparison for .NET API چک کردن اختلافات و تجزیه و تحلیل XLSX صفحات گسترده را تسهیل می کند. C# .NET پشتیبانی می شود."

############################# Header ############################
title: "استفاده از تکنولوژی های C# برای مقایسه صفحات گسترده XLSX" 
description: "API .NET، که برای مقایسه انواع مختلف سند ساخته شده است، تفاوت ها را در MS Excel فایل شناسایی و گزارش می دهد. برنامه های کاربردی را با استفاده از C#، ASP .NET، VB .NET یا .NET Core بسازید تا از مزایای آن استفاده کنید. گزارش های دقیق را با حداقل پیاده سازی کد دریافت کنید."
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
    title: "ویژگی های API GroupDocs.Comparison for .NET را کشف کنید"
    link: "/comparison/net/"
    link_title: "بیشتر بدانید"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       تغییرات در صفحات گسترده XLSX خود را با گزارش مناسب در .NET پروژه های خود تشخیص دهید. علاوه بر این، اطلاعات مربوط به سبک ها، اشکال و سایر محتوا را بازیابی کنید و صفحات گسترده XSLX را در یک سند جدید ادغام کنید. GroupDocs.Comparison for .NET API را فقط با چند خط کد در پروژه های خود ادغام کنید. از نرم افزار ما بدون نیاز به توسعه دهندگان شخص ثالث استفاده کنید.

############################# Steps ############################
steps:
    enable: true
    title: "تولید MS Excel XLSX گزارش مقایسه با استفاده از C#"
    content: |
      یک گزارش تمایز برای فایل های XLSX با استفاده از [GroupDocs.Comparison](https://products.groupdocs.com/comparison/net/) ایجاد کنید
      
      1. بسته GroupDocs.Comparison for .NET را از [Nuget](https://www.nuget.org/packages/GroupDocs.Comparison) بارگیری و نصب کنید
      2. با ارائه مسیر فایل XLSX، شیء Comparer را نمونه سازی کنید
      3. شامل XLSX صفحات گسترده برای مقایسه
      4. گزارش مقایسه حاوی اطلاعات تمایز را بازیابی کنید
   
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

        // یک گزارش در مورد تغییرات در XLSX فایل ایجاد کنید

        // نمونه سازی شی Comparer برای پردازش صفحات گسترده
        using (Comparer comparer = new Comparer("source.xlsx"))
        {
            // حداقل یک فایل را برای مقایسه قرار دهید
        	comparer.Add("file_to_compare_1.xlsx");
            comparer.Add("file_to_compare_2.xlsx");
            comparer.Add("file_to_compare_3.xlsx");

            // نتیجه مقایسه را تجزیه و تحلیل کنید
            comparer.Compare("result.xlsx"); 
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
    title: "مقایسه صفحات گسترده MS Excel برای C# برنامه"
    exclude: "XLSX"
    description: "مزایای GroupDocs.Comparison for .NET را برای کنترل نسخه های XLSX اسناد بررسی کنید. به سرعت و به راحتی اطلاعات را از MS Excel صفحه گسترده برای تجزیه و تحلیل بیشتر جمع آوری کنید."
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