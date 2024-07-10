
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
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
head_title: "API so sánh tài liệu Python | trình kiểm tra khác biệt"
head_description: "API so sánh tài liệu Python cung cấp các công cụ hiệu quả để so sánh tài liệu. Tích hợp liền mạch với Python để theo dõi thay đổi tức thì"

############################# Header ############################
title: "So sánh tài liệu với Python: Đánh dấu bất kỳ điểm khác biệt nào"
description: "Sử dụng API GroupDocs.Comparison để phát triển các ứng dụng Python gốc với các tính năng so sánh có cấu hình cao. So sánh các tệp, nội dung và kiểu văn bản của chúng giữa các định dạng tài liệu tương tự."
words:
  for: "cho"

actions:
  main: "Tải xuống PyPi miễn phí"
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
  title: "So sánh hình ảnh BMP trong Python"
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
  description: "API để so sánh các loại tài liệu phổ biến như PDF, Microsoft Office, HTML, email hoặc hình ảnh trong ứng dụng Python."
  features:
    # feature loop
    - title: "Báo cáo đầu ra chi tiết"
      content: "GroupDocs.Comparison xác định những thay đổi trong nội dung tài liệu (ký tự, từ, đoạn văn, bảng, biểu đồ) cũng như những thay đổi về kiểu dáng tài liệu. Nó cung cấp cho người dùng một báo cáo chứa thông tin chi tiết về sự khác biệt, bao gồm số lượng và loại của chúng."

    # feature loop
    - title: "Hỗ trợ các định dạng tệp và tài liệu phổ biến"
      content: "Với API GroupDocs.Comparison, bạn có thể so sánh hiệu quả các tài liệu ở các định dạng như PDF, HTML, email, Microsoft Office Word, bảng tính Excel, bản trình bày PowerPoint, OneNote, sơ đồ Visio, tệp văn bản, hình ảnh JPEG, PNG, GIF, BMP, và nhiều định dạng khác."

    # feature loop
    - title: "Tài liệu và ví dụ toàn diện"
      content: "Hiện có sẵn tài liệu mở rộng và ví dụ về mã để sử dụng thư viện So sánh trên các nền tảng khác nhau, giúp bạn dễ dàng tích hợp API GroupDocs.Comparison vào ứng dụng Python của mình."

    # feature loop
    - title: "Chọn và hợp nhất các thay đổi thành một tệp"
      content: "Nếu bạn có các phiên bản khác nhau của tài liệu, bạn có thể chọn các thay đổi cụ thể và biên dịch tài liệu mới bằng thư viện GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Độc lập nền tảng"
  description: "GroupDocs.Comparison for Python via .NET hỗ trợ các hệ điều hành, khung và trình quản lý gói sau"
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
    GroupDocs.Comparison for Python via .NET hỗ trợ các thao tác với [định dạng tệp sau](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
  title: "Tính năng của GroupDocs.Comparison for Python via .NET"
  description: "Dễ dàng so sánh các tài liệu, hình ảnh PDF và Office cũng như các định dạng khác."

  items:
    # feature loop
    - icon: "compare"
      title: "So sánh tài liệu thân thiện với người dùng"
      content: "Phân tích và xác định sự khác biệt giữa hai tài liệu."

    # feature loop
    - icon: "note-stack"
      title: "So sánh nhiều tài liệu"
      content: "Phân tích và xác định sự khác biệt trong nhiều tài liệu cùng một lúc."

    # feature loop
    - icon: "stacks"
      title: "Các định dạng được hỗ trợ"
      content: "Hỗ trợ hơn 50 định dạng tài liệu phổ biến từ nhiều danh mục khác nhau."

    # feature loop
    - icon: "rule"
      title: "Chấp nhận hoặc từ chối thay đổi"
      content: "Trình bày trực quan rõ ràng về các thay đổi đã xác định, với tùy chọn chấp nhận hoặc từ chối sửa đổi."

    # feature loop
    - icon: "preview"
      title: "Tạo bản xem trước"
      content: "Lưu kết quả so sánh dưới dạng hình ảnh."

    # feature loop
    - icon: "two-pager"
      title: "So sánh nội dung"
      content: "So sánh nội dung văn bản theo từng dòng, theo đoạn văn, theo từ hoặc theo ký tự. Làm nổi bật những thay đổi."

    # feature loop
    - icon: "format_color_text"
      title: "So sánh phong cách"
      content: "Phát hiện những thay đổi về định dạng và kiểu dáng."

    # feature loop
    - icon: "folder-managed"
      title: "Đặt siêu dữ liệu"
      content: "Giữ lại siêu dữ liệu từ tệp nguồn hoặc tệp đích hoặc cho phép người dùng chỉ định siêu dữ liệu."

    # feature loop
    - icon: "lock"
      title: "Mật khẩu bảo vệ"
      content: "Phân tích tài liệu được mã hóa hoặc bảo mật tài liệu kết quả bằng mật khẩu."

    # feature loop
    - icon: "select"
      title: "So sánh các trang cụ thể"
      content: "Tải và so sánh các phần hoặc trang cụ thể của tài liệu."

    # feature loop
    - icon: "speaker-notes"
      title: "Hiển thị bình luận"
      content: "Chọn ẩn hoặc hiển thị nhận xét khi tải tài liệu nguồn."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Mẫu mã"
  description: "Khám phá các trường hợp sử dụng điển hình của thao tác GroupDocs.Comparison for Python via .NET"
  items:
    # code sample loop
    - title: "So sánh các tài liệu được bảo vệ bằng mật khẩu"
      content: |
        Để so sánh các tài liệu được [bảo vệ bằng mật khẩu](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/), bạn cần chỉ định mật khẩu khi tải tài liệu:
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