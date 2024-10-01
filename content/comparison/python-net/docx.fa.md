
---
############################# Static ############################
layout: "format"
date:  2024-10-01T13:42:45
draft: false
lang: fa
format: Docx
product: "Comparison"
product_tag: "comparison"
platform: "Python via .NET"
platform_tag: "python-net"

############################# Head ############################
head_title: "اسناد DOCX را با استفاده از API Python مقایسه کنید"
head_description: "با استفاده از API GroupDocs.Comparison برای Python به راحتی تفاوت های موجود در فایل های MS Word DOCX را ردیابی کنید. ایجاد گزارش های دقیق برای برجسته کردن تغییرات بین اسناد."

############################# Header ############################
title: "مقایسه فایل‌های DOCX در Python via .NET" 
description: "برای شناسایی و نمایش سریع هرگونه تغییر در فایل‌های MS Word DOCX، از API پردازش اسناد ما در Python استفاده کنید. از تولید گزارش سریع و بدون دردسر در برنامه های Python via .NET خود بهره مند شوید."
subtitle: "راه حل مقایسه فایل" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "از PyPi به صورت رایگان دانلود کنید"
      link: "https://releases.groupdocs.com/comparison/python-net/"
      
############################# About ############################
about:
    enable: true
    title: "ویژگی های GroupDocs.Comparison for Python via .NET را کشف کنید"
    link: "/comparison/python-net/"
    link_title: "بیشتر بدانید"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison گزارش های جامعی را ارائه می دهد که تغییرات در نسخه های مختلف اسناد DOCX را برجسته می کند. تنها با چند خط کد، Python via .NET و API ما را در گردش کار خود بدون نیاز به هیچ کتابخانه اضافی ادغام کنید. تشخیص تغییرات در صفحات، متن، سبک های متن، یا اشکال در اسناد MS Word. حتی می توانید تغییرات را برای ایجاد یک سند نهایی DOCX ادغام کنید. قابلیت های پردازش اسناد خود را با API قدرتمند ما افزایش دهید.

############################# Steps ############################
steps:
    enable: true
    title: "ایجاد گزارش های مقایسه DOCX در Python"
    content: |
      برای مقایسه فایل‌های DOCX از [GroupDocs.Comparison](https://products.groupdocs.com/comparison/python-net/) با Python via .NET استفاده کنید.
      
      1. GroupDocs.Comparison را برای Python via .NET از طریق [PyPi](https://pypi.org/project/groupdocs-comparison-net/) نصب کنید.
      2. یک نمونه Comparer ایجاد کنید و مسیر اولین فایل DOCX را مشخص کنید.
      3. فایل های DOCX اضافی را برای مقایسه اضافه کنید.
      4. گزارش تولید شده را بررسی کنید و به نتایج دسترسی پیدا کنید.
   
    code:
      platform: "python-net"
      copy_title: "کپی کردن"
      install:
        command: "pip install groupdocs-comparison-net"
        copy_tip: "برای کپی کلیک کنید"
        copy_done: "کپی شده"
      links:
        #  loop
        - title: "نمونه های بیشتر"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET/"
        #  loop
        - title: "مستندات"
          link: "https://docs.groupdocs.com/comparison/python-net/"
          
      content: |
        ```python {style=abap}
        def run():

            # چندین فایل را با هم مقایسه کنید تا شباهت ها و تفاوت ها را ببینید.

            # Comparer را راه اندازی کنید و اولین فایل را بارگذاری کنید.
            with groupdocs.comparison.Comparer("first.docx") as comparer:

                # برای مقایسه فایل های اضافی اضافه کنید.
                comparer.add('second.docx')
                comparer.add('third.docx')

                # گزارش مقایسه نهایی را بازیابی کنید.
                comparer.compare('report_full.docx')

                print("\nDocuments compared successfully.\nCheck output.")
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "آماده شروع هستید؟"
  description: "ویژگی های GroupDocs.Comparison را به صورت رایگان امتحان کنید یا مجوز درخواست کنید"
  items:
    #  loop
    - title: "PyPi دانلود"
      link: "https://releases.groupdocs.com/comparison/python-net/"
      color: "red"
        #  loop
    - title: "صدور مجوز"
      link: "https://purchase.groupdocs.com/pricing/comparison/python-net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "مقایسه اسناد DOCX با استفاده از Python"
    exclude: "DOCX"
    description: "به راحتی هر فایل MS Word DOCX را با GroupDocs.Comparison for Python via .NET مقایسه کنید و اطلاعات ارزشمندی در مورد تغییرات سند دریافت کنید."
    items: 
        # format loop 1
        - name: "مقایسه فایل های PDF"
          format: "PDF"
          link: "/comparison/python-net/pdf/"
          description: "ادوبی Portable فرمت سند"

        # format loop 2
        - name: "مقایسه فایل های DOCX"
          format: "DOCX"
          link: "/comparison/python-net/docx/"
          description: "مایکروسافت Word سند XML باز"

        # format loop 3
        - name: "مقایسه RTF فایل ها"
          format: "RTF"
          link: "/comparison/python-net/rtf/"
          description: "فرمت فایل متنی غنی"

        # format loop 4
        - name: "مقایسه TXT فایل ها"
          format: "TXT"
          link: "/comparison/python-net/txt/"
          description: "فرمت فایل متن ساده"

        # format loop 5
        - name: "مقایسه فایل های XLSX"
          format: "XLSX"
          link: "/comparison/python-net/xlsx/"
          description: "مایکروسافت Excel صفحه گسترده XML باز"

        # format loop 6
        - name: "مقایسه فایل های CSV"
          format: "CSV"
          link: "/comparison/python-net/csv/"
          description: "فایل مقادیر جدا شده با کاما"

        # format loop 7
        - name: "مقایسه فایل های PPTX"
          format: "PPTX"
          link: "/comparison/python-net/pptx/"
          description: "PowerPoint ارائه اکس‌ام‌ال باز"

        # format loop 8
        - name: "مقایسه فایل های ODS"
          format: "ODS"
          link: "/comparison/python-net/ods/"
          description: "Open Document صفحه گسترده"

        # format loop 9
        - name: "مقایسه فایل های ODP"
          format: "ODP"
          link: "/comparison/python-net/odp/"
          description: "OpenDocument فرمت فایل ارائه"

        # format loop 10
        - name: "مقایسه ODT فایل ها"
          format: "ODT"
          link: "/comparison/python-net/odt/"
          description: "Open Document متن"

        # format loop 11
        - name: "مقایسه فایل های JPEG"
          format: "JPEG"
          link: "/comparison/python-net/jpeg/"
          description: "JPEG تصویر"

        # format loop 12
        - name: "مقایسه فایل های PNG"
          format: "PNG"
          link: "/comparison/python-net/png/"
          description: "Portable گرافیک شبکه"

        # format loop 13
        - name: "مقایسه فایل های GIF"
          format: "GIF"
          link: "/comparison/python-net/gif/"
          description: "فایل فرمت تبادل گرافیکی"

        # format loop 14
        - name: "مقایسه فایل های BMP"
          format: "BMP"
          link: "/comparison/python-net/bmp/"
          description: "فرمت فایل بیت مپ"

        # format loop 15
        - name: "مقایسه فایل های HTML"
          format: "HTML"
          link: "/comparison/python-net/html/"
          description: "زبان نشانه گذاری هایپر متن"

        # format loop 16
        - name: "مقایسه فایل های MSG"
          format: "MSG"
          link: "/comparison/python-net/msg/"
          description: "پیام ایمیل مایکروسافت Outlook"

        # format loop 17
        - name: "مقایسه ONE فایل ها"
          format: "ONE"
          link: "/comparison/python-net/one/"
          description: "مایکروسافت OneNote"

        # format loop 18
        - name: "مقایسه VSDX فایل ها"
          format: "VSDX"
          link: "/comparison/python-net/vsdx/"
          description: "مایکروسافت Visio نقاشی"

        # format loop 19
        - name: "مقایسه فایل های CS"
          format: "CS"
          link: "/comparison/python-net/cs/"
          description: "زبان سی شارپ"

        # format loop 20
        - name: "مقایسه Java فایل ها"
          format: "Java"
          link: "/comparison/python-net/java/"
          description: "Java زبان"
          
        # format loop 21
        - name: "مقایسه فایل های CPP"
          format: "CPP"
          link: "/comparison/python-net/cpp/"
          description: "زبان سی++"
---