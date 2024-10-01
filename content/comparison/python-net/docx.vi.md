
---
############################# Static ############################
layout: "format"
date:  2024-10-01T13:42:45
draft: false
lang: vi
format: Docx
product: "Comparison"
product_tag: "comparison"
platform: "Python via .NET"
platform_tag: "python-net"

############################# Head ############################
head_title: "So sánh các tài liệu DOCX bằng API Python"
head_description: "Dễ dàng theo dõi sự khác biệt trong tệp MS Word DOCX bằng API GroupDocs.Comparison cho Python. Tạo báo cáo chi tiết để làm nổi bật những thay đổi giữa các tài liệu."

############################# Header ############################
title: "So sánh các tệp DOCX trong Python via .NET" 
description: "Sử dụng API xử lý tài liệu của chúng tôi trong Python để nhanh chóng xác định và hiển thị mọi thay đổi trong tệp MS Word DOCX. Hưởng lợi từ việc tạo báo cáo nhanh chóng, không rắc rối trong ứng dụng Python via .NET của bạn."
subtitle: "Giải pháp so sánh tập tin" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Tải xuống miễn phí từ PyPi"
      link: "https://releases.groupdocs.com/comparison/python-net/"
      
############################# About ############################
about:
    enable: true
    title: "Khám phá các tính năng của GroupDocs.Comparison for Python via .NET"
    link: "/comparison/python-net/"
    link_title: "Tìm hiểu thêm"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison cung cấp các báo cáo toàn diện nêu bật những thay đổi trong các phiên bản khác nhau của tài liệu DOCX. Chỉ với một vài dòng mã, hãy tích hợp Python via .NET và API của chúng tôi vào quy trình làm việc của bạn mà không cần bất kỳ thư viện bổ sung nào. Phát hiện các thay đổi về trang, văn bản, kiểu văn bản hoặc hình dạng trong tài liệu MS Word. Bạn thậm chí có thể hợp nhất các thay đổi để tạo tài liệu DOCX cuối cùng. Nâng cao khả năng xử lý tài liệu của bạn với API mạnh mẽ của chúng tôi.

############################# Steps ############################
steps:
    enable: true
    title: "Tạo báo cáo so sánh DOCX trong Python"
    content: |
      Sử dụng [GroupDocs.Comparison](https://products.groupdocs.com/comparison/python-net/) với Python via .NET để so sánh các tệp DOCX.
      
      1. Cài đặt GroupDocs.Comparison cho Python via .NET qua [PyPi](https://pypi.org/project/groupdocs-comparison-net/).
      2. Tạo một phiên bản Comparer và chỉ định đường dẫn đến tệp DOCX đầu tiên.
      3. Thêm file DOCX bổ sung để so sánh.
      4. Xem lại báo cáo đã tạo và truy cập kết quả.
   
    code:
      platform: "python-net"
      copy_title: "Sao chép"
      install:
        command: "pip install groupdocs-comparison-net"
        copy_tip: "bấm để sao chép"
        copy_done: "sao chép"
      links:
        #  loop
        - title: "Thêm ví dụ"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET/"
        #  loop
        - title: "Tài liệu"
          link: "https://docs.groupdocs.com/comparison/python-net/"
          
      content: |
        ```python {style=abap}
        def run():

            # So sánh nhiều file để thấy điểm tương đồng và khác biệt.

            # Khởi tạo Trình so sánh và tải tệp đầu tiên.
            with groupdocs.comparison.Comparer("first.docx") as comparer:

                # Thêm các tập tin bổ sung để so sánh.
                comparer.add('second.docx')
                comparer.add('third.docx')

                # Truy xuất báo cáo so sánh cuối cùng.
                comparer.compare('report_full.docx')

                print("\nDocuments compared successfully.\nCheck output.")
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "Sẵn sàng để bắt đầu?"
  description: "Dùng thử GroupDocs.Comparison tính năng miễn phí hoặc yêu cầu giấy phép"
  items:
    #  loop
    - title: "PyPi tải về"
      link: "https://releases.groupdocs.com/comparison/python-net/"
      color: "red"
        #  loop
    - title: "Cấp phép"
      link: "https://purchase.groupdocs.com/pricing/comparison/python-net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "So sánh các tài liệu DOCX sử dụng Python"
    exclude: "DOCX"
    description: "Dễ dàng so sánh bất kỳ tệp MS Word DOCX nào với GroupDocs.Comparison for Python via .NET và nhận được thông tin chi tiết có giá trị về những thay đổi trong tài liệu."
    items: 
        # format loop 1
        - name: "So sánh tập tin PDF"
          format: "PDF"
          link: "/comparison/python-net/pdf/"
          description: "Định dạng tài liệu Adobe Portable"

        # format loop 2
        - name: "So sánh tập tin DOCX"
          format: "DOCX"
          link: "/comparison/python-net/docx/"
          description: "Microsoft Word Tài liệu XML mở"

        # format loop 3
        - name: "So sánh tập tin RTF"
          format: "RTF"
          link: "/comparison/python-net/rtf/"
          description: "Định dạng tệp văn bản phong phú"

        # format loop 4
        - name: "So sánh tập tin TXT"
          format: "TXT"
          link: "/comparison/python-net/txt/"
          description: "Định dạng tệp văn bản thuần túy"

        # format loop 5
        - name: "So sánh tập tin XLSX"
          format: "XLSX"
          link: "/comparison/python-net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop 6
        - name: "So sánh các tập tin CSV"
          format: "CSV"
          link: "/comparison/python-net/csv/"
          description: "Tệp giá trị được phân tách bằng dấu phẩy"

        # format loop 7
        - name: "So sánh tập tin PPTX"
          format: "PPTX"
          link: "/comparison/python-net/pptx/"
          description: "PowerPoint Bản trình bày XML mở"

        # format loop 8
        - name: "So sánh tập tin ODS"
          format: "ODS"
          link: "/comparison/python-net/ods/"
          description: "Open Document Bảng tính"

        # format loop 9
        - name: "So sánh các tập tin ODP"
          format: "ODP"
          link: "/comparison/python-net/odp/"
          description: "OpenDocument Định dạng tập tin trình bày"

        # format loop 10
        - name: "So sánh tập tin ODT"
          format: "ODT"
          link: "/comparison/python-net/odt/"
          description: "Open Document Văn bản"

        # format loop 11
        - name: "So sánh tập tin JPEG"
          format: "JPEG"
          link: "/comparison/python-net/jpeg/"
          description: "JPEG Hình ảnh"

        # format loop 12
        - name: "So sánh tập tin PNG"
          format: "PNG"
          link: "/comparison/python-net/png/"
          description: "Portable Đồ họa mạng"

        # format loop 13
        - name: "So sánh tập tin GIF"
          format: "GIF"
          link: "/comparison/python-net/gif/"
          description: "Tệp định dạng trao đổi đồ họa"

        # format loop 14
        - name: "So sánh tập tin BMP"
          format: "BMP"
          link: "/comparison/python-net/bmp/"
          description: "Định dạng tệp bitmap"

        # format loop 15
        - name: "So sánh các tập tin HTML"
          format: "HTML"
          link: "/comparison/python-net/html/"
          description: "Ngôn ngữ đánh dấu siêu văn bản"

        # format loop 16
        - name: "So sánh tập tin MSG"
          format: "MSG"
          link: "/comparison/python-net/msg/"
          description: "Thư điện tử Microsoft Outlook"

        # format loop 17
        - name: "So sánh tập tin ONE"
          format: "ONE"
          link: "/comparison/python-net/one/"
          description: "Microsoft OneNote"

        # format loop 18
        - name: "So sánh tập tin VSDX"
          format: "VSDX"
          link: "/comparison/python-net/vsdx/"
          description: "Microsoft Visio Bản vẽ"

        # format loop 19
        - name: "So sánh các tập tin CS"
          format: "CS"
          link: "/comparison/python-net/cs/"
          description: "Ngôn ngữ CSharp"

        # format loop 20
        - name: "So sánh tập tin Java"
          format: "Java"
          link: "/comparison/python-net/java/"
          description: "Java Ngôn ngữ"
          
        # format loop 21
        - name: "So sánh các tập tin CPP"
          format: "CPP"
          link: "/comparison/python-net/cpp/"
          description: "Ngôn ngữ C++"
---