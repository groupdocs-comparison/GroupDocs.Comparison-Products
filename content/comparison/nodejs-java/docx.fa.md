
---
############################# Static ############################
layout: "format"
date:  2024-03-21T15:26:29
draft: false
lang: fa
format: Docx
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

############################# Head ############################
head_title: "Node.js API امکان مقایسه DOCX اسناد را فراهم می کند."
head_description: "MS Word DOCX تفاوت فایل ها ممکن است توسط GroupDocs.Comparison Node.js API بررسی شود که گزارش های مفیدی را توصیف تغییرات اسناد تولید می کند."

############################# Header ############################
title: "مقایسه DOCX فایل ها با Node.js via Java" 
description: "از API پردازش سند در Node.js برای شناسایی و آشکار کردن هرگونه تغییر در MS Word DOCX فایل توسط Node.js via Java برنامه ها استفاده کنید. از تولید گزارش های سریع و بدون زحمت استفاده کنید."
subtitle: "راه حل برای مقایسه فایل ها" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "دانلود رایگان NPM"
      link: "https://releases.groupdocs.com/comparison/nodejs-java/"
      
############################# About ############################
about:
    enable: true
    title: "ویژگی های API GroupDocs.Comparison for Node.js via Java را باز کنید"
    link: "/comparison/nodejs-java/"
    link_title: "بیشتر بدانید"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       گزارش‌های مفصلی که داده‌های غنی دربارهٔ تغییرات در نسخه‌های مختلف DOCX اسناد را به ارمغان می‌آورند، توسط GroupDocs.Comparison ارائه می‌شوند. از Node.js via Java همراه با API ما با اضافه کردن چند خط کد و بدون کتابخانه های دیگر استفاده کنید. تغییرات در صفحات، متن، سبک های متن یا اشکال در MS Word سند را تجزیه و تحلیل کنید. فقط داده های درست را انتخاب کرده و سند نهایی DOCX را با ادغام بنویسید. با نرم افزار ما در راه حل های پردازش اسناد خود پیشرفت کنید.

############################# Steps ############################
steps:
    enable: true
    title: "گزارش را با DOCX تمایز اسناد در JavaScript تهیه کنید"
    content: |
      [GroupDocs.Comparison](https://products.groupdocs.com/comparison/nodejs-java/) و Node.js via Java به ما اجازه می دهد تا DOCX اسناد را مقایسه کنیم
      
      1. از [NPM](https://www.npmjs.com/package/@groupdocs/groupdocs.comparison) برای نصب GroupDocs.Comparison برای Node.js via Java استفاده کنید
      2. فراخوانی سازنده Comparer به DOCX مسیر نیاز دارد
      3. سایر فایل های DOCX باید ارائه شوند
      4. از نتایج لذت ببرید
   
    code:
      platform: "net"
      copy_title: "کپی کردن"
      install:
        command: "npm i @groupdocs/groupdocs.comparison"
        copy_tip: "برای کپی کلیک کنید"
        copy_done: "کپی شده"
      links:
        #  loop
        - title: "نمونه های بیشتر"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java"
        #  loop
        - title: "مستندات"
          link: "https://docs.groupdocs.com/comparison/nodejs-java/"
          
      content: |
        ```javascript {style=abap}

        // چندین فایل را بررسی کنید تا ببینید چطور مشابه یا متفاوت هستند

        // یک شیء Comparer ایجاد کنید و اولین فایل را به عنوان ورودی به آن بدهید
        const comparer = new groupdocs.comparison.Comparer('first.docx');

        // افزودن فایل های بیشتر
        comparer.add('second.docx');
        comparer.add('third.docx');

        // گزارش نهایی را دریافت کنید
        await comparer.compare('report_full.docx');

        console.log('\nDocuments compared successfully.\nCheck output.');
        
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "آماده شروع هستید؟"
  description: "ویژگی های GroupDocs.Comparison را به صورت رایگان امتحان کنید یا مجوز درخواست کنید"
  items:
    #  loop
    - title: "NPM دانلود"
      link: "https://releases.groupdocs.com/comparison/nodejs-java/"
      color: "red"
        #  loop
    - title: "صدور مجوز"
      link: "https://purchase.groupdocs.com/pricing/comparison/java/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "از JavaScript برای مقایسه DOCX اسناد استفاده کنید"
    exclude: "DOCX"
    description: "هر فایل MS Word DOCX ممکن است با GroupDocs.Comparison for Node.js via Java مقایسه شود. اطلاعات ارزشمندی را در مورد تغییرات در اسناد خود بگذارید."
    items: 
        # format loop 1
        - name: "مقایسه فایل های PDF"
          format: "PDF"
          link: "/comparison/nodejs-java/pdf/"
          description: "ادوبی Portable فرمت سند"

        # format loop 2
        - name: "مقایسه فایل های DOCX"
          format: "DOCX"
          link: "/comparison/nodejs-java/docx/"
          description: "مایکروسافت Word سند XML باز"

        # format loop 3
        - name: "مقایسه RTF فایل ها"
          format: "RTF"
          link: "/comparison/nodejs-java/rtf/"
          description: "فرمت فایل متنی غنی"

        # format loop 4
        - name: "مقایسه TXT فایل ها"
          format: "TXT"
          link: "/comparison/nodejs-java/txt/"
          description: "فرمت فایل متن ساده"

        # format loop 5
        - name: "مقایسه فایل های XLSX"
          format: "XLSX"
          link: "/comparison/nodejs-java/xlsx/"
          description: "مایکروسافت Excel صفحه گسترده XML باز"

        # format loop 6
        - name: "مقایسه فایل های CSV"
          format: "CSV"
          link: "/comparison/nodejs-java/csv/"
          description: "فایل مقادیر جدا شده با کاما"

        # format loop 7
        - name: "مقایسه فایل های PPTX"
          format: "PPTX"
          link: "/comparison/nodejs-java/pptx/"
          description: "PowerPoint ارائه اکس‌ام‌ال باز"

        # format loop 8
        - name: "مقایسه فایل های ODS"
          format: "ODS"
          link: "/comparison/nodejs-java/ods/"
          description: "Open Document صفحه گسترده"

        # format loop 9
        - name: "مقایسه فایل های ODP"
          format: "ODP"
          link: "/comparison/nodejs-java/odp/"
          description: "OpenDocument فرمت فایل ارائه"

        # format loop 10
        - name: "مقایسه ODT فایل ها"
          format: "ODT"
          link: "/comparison/nodejs-java/odt/"
          description: "Open Document متن"

        # format loop 11
        - name: "مقایسه فایل های JPEG"
          format: "JPEG"
          link: "/comparison/nodejs-java/jpeg/"
          description: "JPEG تصویر"

        # format loop 12
        - name: "مقایسه فایل های PNG"
          format: "PNG"
          link: "/comparison/nodejs-java/png/"
          description: "Portable گرافیک شبکه"

        # format loop 13
        - name: "مقایسه فایل های GIF"
          format: "GIF"
          link: "/comparison/nodejs-java/gif/"
          description: "فایل فرمت تبادل گرافیکی"

        # format loop 14
        - name: "مقایسه فایل های BMP"
          format: "BMP"
          link: "/comparison/nodejs-java/bmp/"
          description: "فرمت فایل بیت مپ"

        # format loop 15
        - name: "مقایسه فایل های HTML"
          format: "HTML"
          link: "/comparison/nodejs-java/html/"
          description: "زبان نشانه گذاری هایپر متن"

        # format loop 16
        - name: "مقایسه فایل های MSG"
          format: "MSG"
          link: "/comparison/nodejs-java/msg/"
          description: "پیام ایمیل مایکروسافت Outlook"

        # format loop 17
        - name: "مقایسه ONE فایل ها"
          format: "ONE"
          link: "/comparison/nodejs-java/one/"
          description: "مایکروسافت OneNote"

        # format loop 18
        - name: "مقایسه VSDX فایل ها"
          format: "VSDX"
          link: "/comparison/nodejs-java/vsdx/"
          description: "مایکروسافت Visio نقاشی"

        # format loop 19
        - name: "مقایسه فایل های CS"
          format: "CS"
          link: "/comparison/nodejs-java/cs/"
          description: "زبان سی شارپ"

        # format loop 20
        - name: "مقایسه Java فایل ها"
          format: "Java"
          link: "/comparison/nodejs-java/java/"
          description: "Java زبان"
          
        # format loop 21
        - name: "مقایسه فایل های CPP"
          format: "CPP"
          link: "/comparison/nodejs-java/cpp/"
          description: "زبان سی++"
---