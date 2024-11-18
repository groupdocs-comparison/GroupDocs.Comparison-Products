
---
############################# Static ############################
layout: "landing"
date: 2024-11-18T09:49:37
draft: false

lang: vi
product: "Comparison"
product_tag: "comparison"
platform: "Python via .NET"
platform_tag: "python-net"

############################# Drop-down ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"
    # supported_platforms loop
    - title: "Java"
      tag: "java"
    # supported_platforms loop
    - title: "Node.js"
      tag: "nodejs-java"
    # supported_platforms loop
    - title: "Python"
      tag: "python-net"

############################# Head ############################
head_title: "Python Công cụ so sánh tài liệu | Phân tích tài liệu"
head_description: "Khám phá sức mạnh của Công cụ so sánh tài liệu Python để phân tích tài liệu kỹ lưỡng. Tích hợp dễ dàng với Python để theo dõi toàn diện các sửa đổi."

############################# Header ############################
title: "So sánh tài liệu với Python: Đánh dấu bất kỳ điểm khác biệt nào"
description: "Sử dụng API GroupDocs.Comparison để tạo các ứng dụng gốc bằng Python với các chức năng so sánh có thể tùy chỉnh. Kiểm tra các tệp, nội dung của chúng và các biến thể kiểu dáng trên các định dạng tài liệu."
words:
  for: "cho"

actions:
  main: "Nhận PyPi miễn phí của bạn Tải xuống ngay bây giờ"
  main_link: "https://pypi.org/project/groupdocs-comparison-net/"
  alt: "Cấp phép"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/python-net/"
  title: "Sẵn sàng để bắt đầu?"
  description: "Dùng thử GroupDocs.Comparison tính năng miễn phí hoặc yêu cầu giấy phép"

release:
  title: "Phiên bản {0} đã phát hành"
  notes: "Xem những gì mới"
  downloads: "Tải xuống"

code:
  title: "So sánh hình ảnh BMP bằng cách sử dụng Python"
  more: "Thêm ví dụ"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET/"
  install: "pip install groupdocs-comparison-net"
  content: |
    ```python {style=abap}
    def run():

        # Chỉ định tài liệu nguồn
        with groupdocs.comparison.Comparer("in.bmp") as comparer:

            # Thêm một hoặc nhiều tài liệu mục tiêu
            comparer.add("target.bmp")

            # Chỉ định các tùy chọn so sánh
            options = new groupdocs.comparison.CompareOptions()
            options.setGenerateSummaryPage(false)

            # So sánh và lưu kết quả
            comparer.compare("result.bmp", options)
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison trong nháy mắt"
  description: "API được thiết kế để so sánh các loại tài liệu được sử dụng rộng rãi như tệp PDF, tệp Microsoft Office, HTML, email hoặc hình ảnh trong ứng dụng Python."
  features:
    # feature loop
    - title: "Báo cáo đầu ra toàn diện"
      content: "GroupDocs.Comparison phát hiện các thay đổi trong nội dung tài liệu (ký tự, từ, đoạn văn, bảng, biểu đồ) cũng như các thay đổi về kiểu dáng tài liệu. Người dùng nhận được báo cáo chi tiết nêu bật tính chất và số lượng thay đổi."

    # feature loop
    - title: "Nhiều định dạng tệp và tài liệu"
      content: "API GroupDocs.Comparison cho phép bạn so sánh các tài liệu ở các định dạng như PDF, HTML, email, Microsoft Office Word, sổ làm việc Excel, tệp PowerPoint, ghi chú OneNote, sơ đồ Visio, tài liệu văn bản, hình ảnh JPEG, PNG, GIF, BMP, trong số nhiều người khác."

    # feature loop
    - title: "Tài liệu kỹ lưỡng và mẫu mã"
      content: "Tài liệu chuyên sâu và mã mẫu cho thư viện So sánh trên nhiều nền tảng khác nhau luôn có sẵn, giúp đơn giản hóa việc tích hợp API GroupDocs.Comparison vào các ứng dụng Python của bạn."

    # feature loop
    - title: "Chọn và kết hợp các thay đổi thành một tài liệu"
      content: "Nếu bạn sở hữu nhiều phiên bản khác nhau của tài liệu, bạn có thể biên dịch có chọn lọc các thay đổi thành một tệp mới bằng thư viện GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Độc lập nền tảng"
  description: "GroupDocs.Comparison for Python via .NET tương thích với các hệ điều hành, khung và trình quản lý gói sau."
  items:
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "macOS"
      image: "finder"      
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NPM"
      image: "npm"  
    # platform loop
    - title: "NuGet"
      image: "nuget"      
    # platform loop
    - title: "Amazon"
      image: "amazon"
    # platform loop
    - title: "Docker"
      image: "docker"
    # platform loop
    - title: "Azure"
      image: "azure"
    # platform loop
    - title: "VS Code"
      image: "vs_code"
    # platform loop
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"

############################# File formats ############################
formats:
  enable: true
  title: "Định dạng tập tin được hỗ trợ"
  description: |
    GroupDocs.Comparison for Python via .NET có thể hoạt động với [định dạng tệp](https://docs.groupdocs.com/comparison/net/supported-document-formats/ sau.
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office & OpenDocument định dạng
        * **Word:** DOCX, DOC, DOCM,DOT, DOTM, DOTX, RTX, RTF, TXT
        * **Excel:** XLSX, XLS, XLT, XLTM, XLSB, XLSM
        * **PowerPoint:** PPTX, PPT, POT, POTX, PPS, PPSX
        * **Outlook:** EML, EMLX, MSG
        * **OneNote:** ONE
        * **OpenDocument:** ODT, ODP, OTP, ODS, OTT
        * **Bố cục trang cố định:** PDF        
    # group loop
    - color: "blue"
      content: |
        ### Hình ảnh, Đồ họa & Sơ đồ
        * **Hình ảnh raster:** BMP, GIF, JPG, JPEG, PNG
        * **Hình ảnh y tế:** DICOM
        * **Microsoft Visio:** VSDX, VSD, VSS, VST, VDX
        * **AutoCAD Drawing:** DWG, DXF
      # group loop
    - color: "red"
      content: |
        ### Khác
        * **Văn bản:** TXT
        * **Ngôn ngữ lập trình:** CS, Java, CPP, JS, PY, RB, PL, ASM, GROOVY, JSON, PHP, SQL, LOG, DIFF, LESS, SCALA
        * **Trang web:** HTM, HTML, MHT, MHTML
        * **Sách điện tử:** MOBI, DjVu
        * **Giá trị được phân tách bằng phân cách:** CSV

############################# Features ############################
features:
  enable: true
  title: "Khả năng của GroupDocs.Comparison for Python via .NET"
  description: "So sánh liền mạch các tệp PDF, tài liệu Office, hình ảnh và nhiều định dạng khác."

  items:
    # feature loop
    - icon: "compare"
      title: "So sánh tài liệu trực quan"
      content: "Kiểm tra và làm nổi bật sự khác biệt giữa hai tài liệu."

    # feature loop
    - icon: "note-stack"
      title: "So sánh nhiều tài liệu"
      content: "Kiểm tra nhiều tài liệu để tìm sự khác biệt cùng một lúc."

    # feature loop
    - icon: "stacks"
      title: "Hỗ trợ định dạng mở rộng"
      content: "Tương thích với hơn 50 định dạng tài liệu thường được sử dụng trên nhiều danh mục khác nhau."

    # feature loop
    - icon: "rule"
      title: "Chấp nhận hoặc từ chối thay đổi"
      content: "Trực quan hóa các thay đổi một cách rõ ràng, đưa ra các tùy chọn để chấp nhận hoặc từ chối các chỉnh sửa."

    # feature loop
    - icon: "preview"
      title: "Tạo bản xem trước trực quan"
      content: "Tạo bản xem trước kết quả so sánh ở định dạng hình ảnh."

    # feature loop
    - icon: "two-pager"
      title: "So sánh nội dung dựa trên văn bản"
      content: "Thực hiện so sánh từng dòng, đoạn, từ hoặc ký tự để làm nổi bật các thay đổi."

    # feature loop
    - icon: "format_color_text"
      title: "Phát hiện thay đổi định dạng"
      content: "Xác định những thay đổi trong phong cách và định dạng tài liệu."

    # feature loop
    - icon: "folder-managed"
      title: "Xử lý siêu dữ liệu có thể tùy chỉnh"
      content: "Giữ lại siêu dữ liệu từ tệp nguồn hoặc tệp đích hoặc cho phép người dùng xác định siêu dữ liệu mới."

    # feature loop
    - icon: "lock"
      title: "Xử lý các tệp được bảo vệ bằng mật khẩu"
      content: "Làm việc với các tài liệu được mã hóa hoặc tạo các tài liệu bảo mật được bảo vệ bằng mật khẩu."

    # feature loop
    - icon: "select"
      title: "So sánh trang tập trung"
      content: "Chọn và so sánh các phần cụ thể hoặc các trang riêng lẻ của tài liệu."

    # feature loop
    - icon: "speaker-notes"
      title: "Quản lý khả năng hiển thị bình luận"
      content: "Quyết định tiết lộ hoặc che giấu nhận xét khi kiểm tra tài liệu nguồn."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Mẫu mã"
  description: "Khám phá các tình huống phổ biến để sử dụng chức năng GroupDocs.Comparison for Python via .NET."
  items:
    # code sample loop
    - title: "So sánh tài liệu với bảo vệ bằng mật khẩu"
      content: |
        Để so sánh các tài liệu được [bảo mật bằng mật khẩu](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/), bạn cần chỉ định mật khẩu khi tải tài liệu:
        {{< landing/code title="Làm thế nào để so sánh các tài liệu được bảo vệ bằng mật khẩu.">}}
        ```python {style=abap}
        def run():

            # Tải tài liệu nguồn và chỉ định mật khẩu của nó
            with groupdocs.comparison.Comparer("source.docx", new LoadOptions("1234")) as comparer:

                # Tải tài liệu đích và chỉ định mật khẩu của nó
                comparer.add("target.docx", new LoadOptions("5678"));

                # Lưu kết quả so sánh vào một tệp được chỉ định
                comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "So sánh nhiều PDF tài liệu."
      content: |
        GroupDocs.Comparison cho phép bạn [so sánh nhiều hơn hai tài liệu](https://docs.groupdocs.com/comparison/python-net/compare-multiple-documents/). Hoạt động gần giống như khi so sánh hai tệp. Bạn chỉ cần thêm nhiều tệp mục tiêu vào lớp `comparer`.
        {{< landing/code title="Làm thế nào để so sánh ba tài liệu trở lên.">}}
        ```python {style=abap}
        def run():

            # Tải tài liệu nguồn
            with groupdocs.comparison.Comparer(source.pdf") as comparer:

                # Chỉ định tệp thứ hai để so sánh
                comparer.add("target2.pdf");

                # Chỉ định tệp thứ ba để so sánh
                comparer.add("target3.pdf");

                # Lưu kết quả so sánh vào một tệp được chỉ định
                comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---