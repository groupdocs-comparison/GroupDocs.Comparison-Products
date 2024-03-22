
---
############################# Static ############################
layout: "format"
date:  2024-03-22T13:27:49
draft: false
lang: fa
format: Pdf
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

############################# Head ############################
head_title: "کتابخانه JavaScript برای بررسی تفاوت ها در PDF s."
head_description: "نرم افزار GroupDocs.Comparison Node.js گزارش های جامعی را با جزئیات تفاوت ها در PDF اسناد تولید می کند."

############################# Header ############################
title: "PDF مقایسه اسناد برای Node.js via Java" 
description: "از API مقایسه اسناد ما در Node.js برای تشخیص و نمایش تفاوت در PDF s در برنامه های کاربردی JavaScript استفاده کنید. از دریافت سریع و بدون زحمت گزارش های دقیق بهره مند شوید."
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
    title: "بررسی ویژگی های کتابخانه GroupDocs.Comparison for Node.js via Java"
    link: "/comparison/nodejs-java/"
    link_title: "بیشتر بدانید"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       گزارش های دقیق در مورد هرگونه تفاوت در PDF اسناد را در .NET برنامه های خود دریافت کنید. از GroupDocs.Comparison for Node.js via Java با اضافه کردن چند خط کد بدون هیچ نرم افزار اضافی یا هر کتابخانه خارجی دیگر استفاده کنید. هر گونه تغییر در پاراگراف ها، کلمات، کاراکترها، اشکال و سبک های متن در فایل های PDF خود را کنترل کنید. ادغام تغییرات از بسیاری از نسخه های سند به نتیجه PDF نیز در دسترس است. اسناد را به سرعت و بدون تلاش اضافی پردازش کنید.

############################# Steps ############################
steps:
    enable: true
    title: "دریافت گزارش در مورد تمایز PDF در JavaScript"
    content: |
      ردیابی تغییرات اسناد PDF با گزارش های تشکیل شده با [GroupDocs.Comparison](https://products.groupdocs.com/comparison/nodejs-java/)
      
      1. از [NPM](https://www.npmjs.com/package/@groupdocs/groupdocs.comparison) برای نصب GroupDocs.Comparison برای Node.js via Java استفاده کنید
      2. سازنده Comparer را با PDF مسیر فایل فراخوانی کنید
      3. یک PDF دیگر ارائه دهید تا آن را با اولین مقایسه کنید
      4. یک گزارش نهایی در مورد تفاوت فایل ها را بازیابی کنید
   
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
        const comparer = new groupdocs.comparison.Comparer('first.pdf');

        // افزودن فایل های بیشتر
        comparer.add('second.pdf');
        comparer.add('third.pdf');

        // گزارش نهایی را دریافت کنید
        await comparer.compare('report_full.pdf');

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
    title: "مقایسه فرمت های محبوب فایل مانند PDF با استفاده از JavaScript"
    exclude: "PDF"
    description: "فایل های PDF شما را می توان با Node.js API ما به سرعت مقایسه کرد. با گزارش های دقیق، تغییر سند را بدون زحمت کنترل کنید."
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