
---
############################# Static ############################
layout: "format"
date:  2024-12-19T07:49:55
draft: false
lang: fa
format: Xlsx
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

############################# Head ############################
head_title: "محتوای صفحات گسترده XLSX را با Node.js API مقایسه کنید."
head_description: "تفاوت های صفحات گسترده MS Excel را می توان با Node.js API بررسی کرد، که گزارش های آموزنده ای را با جزئیات انواع مختلف تمایز تولید می کند."

############################# Header ############################
title: "مقایسه صفحات گسترده XLSX با استفاده از Node.js via Java" 
description: "از کتابخانه پردازش سند در Node.js برای شناسایی و افشای تغییرات در MS Excel XLSX فایل در Node.js via Java برنامه استفاده کنید. از تولید سریع و بدون زحمت گزارش بهره مند شوید."
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
    title: "مزایای GroupDocs.Comparison را کشف کنید"
    link: "/comparison/nodejs-java/"
    link_title: "بیشتر بدانید"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       به گزارش های دقیق حاوی داده های غنی در مورد تغییرات در نسخه های مختلف XLSX اسناد ارائه شده توسط GroupDocs.Comparison دسترسی پیدا کنید. Node.js via Java برنامه را با API ما فقط با استفاده از چند خط کد، بدون تلاش اضافی ادغام کنید. تغییرات در صفحات، متن، سبک های متن یا اشکال در MS Excel سند را تجزیه و تحلیل کنید. داده های مناسب را انتخاب کنید و آنها را در یک سند نهایی XLSX ادغام کنید. پروژه های تجاری خود را با راه حل های ما پیشرفت کنید.

############################# Steps ############################
steps:
    enable: true
    title: "گزارش را با XLSX تمایز اسناد در JavaScript تهیه کنید"
    content: |
      از [GroupDocs.Comparison](https://products.groupdocs.com/comparison/nodejs-java/) و Node.js via Java برای مقایسه سند XLSX استفاده کنید
      
      1. GroupDocs.Comparison را برای Node.js via Java از [NPM](https://www.npmjs.com/package/@groupdocs/groupdocs.comparison) نصب کنید
      2. هنگام فراخوانی سازنده Comparer، مسیر XLSX را ارائه دهید
      3. شامل فایل های اضافی XLSX
      4. از نتایج تولید شده لذت ببرید
   
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
        const comparer = new groupdocs.comparison.Comparer('first.xlsx');

        // افزودن فایل های بیشتر
        comparer.add('second.xlsx');
        comparer.add('third.xlsx');

        // گزارش نهایی را دریافت کنید
        await comparer.compare('report_full.xlsx');

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
      link: "https://purchase.groupdocs.com/pricing/comparison/nodejs-java/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "از JavaScript برای مقایسه صفحات گسترده XLSX استفاده کنید"
    exclude: "XLSX"
    description: "هر صفحه گسترده MS Excel XLSX را به راحتی با استفاده از GroupDocs.Comparison for Node.js via Java مقایسه کنید. بینش ارزشمندی در مورد تغییرات در داده های کسب و کار خود بدست آورید."
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