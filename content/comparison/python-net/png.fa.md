
---
############################# Static ############################
layout: "format"
date:  2024-10-01T13:42:45
draft: false
lang: fa
format: Png
product: "Comparison"
product_tag: "comparison"
platform: "Python via .NET"
platform_tag: "python-net"

############################# Head ############################
head_title: "API Python برای مقایسه تصاویر PNG"
head_description: "کتابخانه GroupDocs.Comparison for Python via .NET گزارش های دقیقی تولید می کند که تفاوت ها را در تصاویر PNG برجسته می کند."

############################# Header ############################
title: "تصاویر PNG در برنامه های Python را با پایتون مقایسه کنید" 
description: "از API Python برای شناسایی تغییرات فایل‌های PNG در برنامه‌های Python خود استفاده کنید. گزارش های جامع را به سرعت و به راحتی دریافت کنید."
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
    title: "قابلیت های GroupDocs.Comparison for Python via .NET API را کشف کنید"
    link: "/comparison/python-net/"
    link_title: "بیشتر بدانید"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       گزارش های دقیقی در مورد تفاوت بین نسخه های مختلف تصاویر PNG به طور مستقیم در برنامه های Python خود ایجاد کنید—بدون نیاز به نرم افزار شخص ثالث. از تمام تغییرات در تصاویر PNG خود مطلع باشید.

############################# Steps ############################
steps:
    enable: true
    title: "نحوه تولید گزارش مقایسه برای تصاویر PNG در Python"
    content: |
      تغییرات فایل های PNG را با استفاده از [GroupDocs.Comparison](https://products.groupdocs.com/comparison/python-net/) ردیابی کنید و به راحتی گزارش ایجاد کنید.
      
      1. بسته GroupDocs.Comparison را از طریق [PyPi](https://pypi.org/project/groupdocs-comparison-net/) نصب کنید.
      2. یک شی Comparer ایجاد کنید و مسیر اولین فایل PNG را ارائه دهید.
      3. یک یا چند فایل PNG را برای مقایسه اضافه کنید.
      4. یک گزارش مفصل که همه تفاوت ها را نشان می دهد بازیابی کنید.
   
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
            with groupdocs.comparison.Comparer("first.png") as comparer:

                # برای مقایسه فایل های اضافی اضافه کنید.
                comparer.add('second.png')
                comparer.add('third.png')

                # گزارش مقایسه نهایی را بازیابی کنید.
                comparer.compare('report_full.png')

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
    title: "مقایسه تصاویر در فرمت های محبوب مانند PNG"
    exclude: "PNG"
    description: "از GroupDocs.Comparison for Python via .NET برای شناسایی تفاوت‌های بین تصاویر PNG و ایجاد گزارش‌های دقیق برای پیگیری تغییرات مهم استفاده کنید."
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