
---
############################# Static ############################
layout: "format"
date:  2024-03-21T15:26:17
draft: false
lang: fa
format: Jpg
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "JPG تصاویر را با GroupDocs.Comparison for Java تجزیه و تحلیل کنید."
head_description: "GroupDocs.Comparison for Java API گزارش های مفید برای JPG تصاویر تولید می کند. پشتیبانی از Java، J2EE و J2SE."

############################# Header ############################
title: "تغییرات در JPG فایل را از طریق راه حل Java ما تجزیه و تحلیل کنید" 
description: "برنامه های Java، J2EE یا J2SE با استفاده از GroupDocs.Comparison API قادر به تولید گزارش های دقیق JPG هستند."
subtitle: "چارچوب بررسی تفاوت اسناد"  

header_actions:
  enable: true
  items:
    #  loop
    - title: "دانلود رایگان Maven"
      link: "https://releases.groupdocs.com/comparison/java/"
      
############################# About ############################
about:
    enable: true
    title: "کاوش در GroupDocs.Comparison for Java API"
    link: "/comparison/java/"
    link_title: "بیشتر بدانید"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       راه حل بومی Java، GroupDocs.Comparison، گزارش های مفصلی در مورد JPG تغییرات ایجاد می کند. پشتیبانی از فرمت های تصویر محبوب برای مقایسه و پردازش بیشتر.

############################# Steps ############################
steps:
    enable: true
    title: "مقایسه فایل های JPG با استفاده از Java"
    content: |
      بازیابی JPG داده های تفاوت با [GroupDocs.Comparison](https://products.groupdocs.com/comparison/java/)
      
      1. قابلیت محصول خود را با افزودن GroupDocs.Comparison for Java از [Maven](https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/) افزایش دهید
      2. ایجاد نمونه Comparer با مسیر JPG
      3. اضافه کردن تصاویر JPG دیگر به پردازش
      4. گزارش حاصل را بدست آورید
   
    code:
      platform: "net"
      copy_title: "کپی کردن"
      install:
        command: |
          <dependencies>
            <dependency>
              <groupId>com.groupdocs</groupId>
              <artifactId>groupdocs-comparison</artifactId>
              <version>{0}</version>
            </dependency>
          </dependencies>

          <repositories>
            <repository>
              <id>repository.groupdocs.com</id>
              <name>GroupDocs Repository</name>
              <url>https://repository.groupdocs.com/repo/</url>
            </repository>
          </repositories>
        copy_tip: "برای کپی کلیک کنید"
        copy_done: "کپی شده"
      links:
        #  loop
        - title: "نمونه های بیشتر"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
        #  loop
        - title: "مستندات"
          link: "https://docs.groupdocs.com/comparison/java/"
          
      content: |
        ```java {style=abap}

        // فایل ها را از هارد دیسک خود برای تفاوت یا شباهت ها بررسی کنید

        // ایجاد یک شی Comparer با مشخص کردن فایل اولیه
        try (Comparer comparer = new Comparer("main.jpg") 
        {
            // اضافه کردن فایل های اضافی برای مقایسه
        	comparer.add("version1.jpg");
            comparer.add("version2.jpg");
            comparer.add("version3.jpg");

            // گزارش را با نام مشخص شده به عنوان نتیجه دریافت کنید
            final Path resultPath = comparer.compare("full_report.jpg"); 

            System.out.println("\nDocuments compared successfully.");
        }
        
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "آماده شروع هستید؟"
  description: "ویژگی های GroupDocs.Comparison را به صورت رایگان امتحان کنید یا مجوز درخواست کنید"
  items:
    #  loop
    - title: "Maven دانلود"
      link: "https://releases.groupdocs.com/comparison/java/"
      color: "red"
        #  loop
    - title: "صدور مجوز"
      link: "https://purchase.groupdocs.com/pricing/comparison/java/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "ردیابی هرگونه تغییر در نسخه های مختلف JPG تصاویر با استفاده از Java"
    exclude: "JPG"
    description: "تغییرات در JPG تصاویر را با GroupDocs.Comparison for Java تشخیص دهید. فرآیندهای کسب و کار را با گزارش های دقیق ارتقا دهید."
    items: 
        # format loop 1
        - name: "مقایسه فایل های PDF"
          format: "PDF"
          link: "/comparison/java/pdf/"
          description: "ادوبی Portable فرمت سند"

        # format loop 2
        - name: "مقایسه فایل های DOCX"
          format: "DOCX"
          link: "/comparison/java/docx/"
          description: "مایکروسافت Word سند XML باز"

        # format loop 3
        - name: "مقایسه RTF فایل ها"
          format: "RTF"
          link: "/comparison/java/rtf/"
          description: "فرمت فایل متنی غنی"

        # format loop 4
        - name: "مقایسه TXT فایل ها"
          format: "TXT"
          link: "/comparison/java/txt/"
          description: "فرمت فایل متن ساده"

        # format loop 5
        - name: "مقایسه فایل های XLSX"
          format: "XLSX"
          link: "/comparison/java/xlsx/"
          description: "مایکروسافت Excel صفحه گسترده XML باز"

        # format loop 6
        - name: "مقایسه فایل های CSV"
          format: "CSV"
          link: "/comparison/java/csv/"
          description: "فایل مقادیر جدا شده با کاما"

        # format loop 7
        - name: "مقایسه فایل های PPTX"
          format: "PPTX"
          link: "/comparison/java/pptx/"
          description: "PowerPoint ارائه اکس‌ام‌ال باز"

        # format loop 8
        - name: "مقایسه فایل های ODS"
          format: "ODS"
          link: "/comparison/java/ods/"
          description: "Open Document صفحه گسترده"

        # format loop 9
        - name: "مقایسه فایل های ODP"
          format: "ODP"
          link: "/comparison/java/odp/"
          description: "OpenDocument فرمت فایل ارائه"

        # format loop 10
        - name: "مقایسه ODT فایل ها"
          format: "ODT"
          link: "/comparison/java/odt/"
          description: "Open Document متن"

        # format loop 11
        - name: "مقایسه فایل های JPEG"
          format: "JPEG"
          link: "/comparison/java/jpeg/"
          description: "JPEG تصویر"

        # format loop 12
        - name: "مقایسه فایل های PNG"
          format: "PNG"
          link: "/comparison/java/png/"
          description: "Portable گرافیک شبکه"

        # format loop 13
        - name: "مقایسه فایل های GIF"
          format: "GIF"
          link: "/comparison/java/gif/"
          description: "فایل فرمت تبادل گرافیکی"

        # format loop 14
        - name: "مقایسه فایل های BMP"
          format: "BMP"
          link: "/comparison/java/bmp/"
          description: "فرمت فایل بیت مپ"

        # format loop 15
        - name: "مقایسه فایل های HTML"
          format: "HTML"
          link: "/comparison/java/html/"
          description: "زبان نشانه گذاری هایپر متن"

        # format loop 16
        - name: "مقایسه فایل های MSG"
          format: "MSG"
          link: "/comparison/java/msg/"
          description: "پیام ایمیل مایکروسافت Outlook"

        # format loop 17
        - name: "مقایسه ONE فایل ها"
          format: "ONE"
          link: "/comparison/java/one/"
          description: "مایکروسافت OneNote"

        # format loop 18
        - name: "مقایسه VSDX فایل ها"
          format: "VSDX"
          link: "/comparison/java/vsdx/"
          description: "مایکروسافت Visio نقاشی"

        # format loop 19
        - name: "مقایسه فایل های CS"
          format: "CS"
          link: "/comparison/java/cs/"
          description: "زبان سی شارپ"

        # format loop 20
        - name: "مقایسه Java فایل ها"
          format: "Java"
          link: "/comparison/java/java/"
          description: "Java زبان"
          
        # format loop 21
        - name: "مقایسه فایل های CPP"
          format: "CPP"
          link: "/comparison/java/cpp/"
          description: "زبان سی++"
---