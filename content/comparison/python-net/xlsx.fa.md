
---
############################# Static ############################
layout: "format"
date:  2024-10-01T13:42:45
draft: false
lang: fa
format: Xlsx
product: "Comparison"
product_tag: "comparison"
platform: "Python via .NET"
platform_tag: "python-net"

############################# Head ############################
head_title: "محتوای صفحه گسترده XLSX را با API Python مقایسه کنید"
head_description: "با استفاده از API Python ما، که گزارش‌های مفصلی را ایجاد می‌کند که تمام تمایزات را برجسته می‌کند، به راحتی تفاوت‌ها را در صفحات گسترده MS Excel بررسی کنید."

############################# Header ############################
title: "مقایسه صفحه گسترده XLSX در برنامه های کاربردی Python via .NET" 
description: "برای شناسایی و برجسته کردن تغییرات فایل‌های MS Excel XLSX در برنامه‌های Python via .NET از کتابخانه پردازش اسناد Python استفاده کنید. گزارشات را به سرعت و به راحتی تولید کنید."
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
    title: "مزایای GroupDocs.Comparison را کشف کنید"
    link: "/comparison/python-net/"
    link_title: "بیشتر بدانید"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       با استفاده از GroupDocs.Comparison گزارش‌های جامعی ایجاد کنید که داده‌های دقیقی را در مورد تغییرات در نسخه‌های مختلف فایل‌های XLSX ارائه می‌کند. تنها با چند خط کد، می‌توانید بدون نیاز به ابزارهای اضافی، API را در برنامه‌های Python via .NET خود یکپارچه ادغام کنید. تفاوت در برگه‌ها، متن، سبک‌ها یا شکل‌ها را در فایل‌های MS Excel تجزیه و تحلیل کنید و تغییرات را در یک سند نهایی XLSX ادغام کنید. با راه حل های قدرتمند ما، گردش کار کسب و کار خود را ارتقا دهید.

############################# Steps ############################
steps:
    enable: true
    title: "نحوه مقایسه فایل های XLSX در Python"
    content: |
      از [GroupDocs.Comparison](https://products.groupdocs.com/comparison/python-net/) و Python via .NET برای مقایسه اسناد XLSX استفاده کنید
      
      1. نصب GroupDocs.Comparison برای Python via .NET از [PyPi](https://pypi.org/project/groupdocs-comparison-net/)
      2. شی Comparer را نمونه سازی کنید و مسیر اولین فایل XLSX را ارائه دهید
      3. فایل های XLSX اضافی را برای مقایسه اضافه کنید
      4. نتایج مقایسه را ایجاد و بررسی کنید
   
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
            with groupdocs.comparison.Comparer("first.xlsx") as comparer:

                # برای مقایسه فایل های اضافی اضافه کنید.
                comparer.add('second.xlsx')
                comparer.add('third.xlsx')

                # گزارش مقایسه نهایی را بازیابی کنید.
                comparer.compare('report_full.xlsx')

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
    title: "مقایسه صفحات گسترده XLSX با Python"
    exclude: "XLSX"
    description: "به راحتی صفحات گسترده MS Excel XLSX را با استفاده از API GroupDocs.Comparison for Python via .NET مقایسه کنید. با گزارش های دقیق ما، بینش عمیقی در مورد تغییرات در داده های کسب و کار خود به دست آورید."
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