
---
############################# Static ############################
layout: "landing"
date: 2024-03-22T13:27:50
draft: false

lang: vi
product: "Comparison"
product_tag: "comparison"
platform: "Net"
platform_tag: "net"

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

############################# Head ############################
head_title: "C# .NET Phần mềm so sánh tài liệu | diff checker"
head_description: "C# .NET Phần mềm để so sánh phong cách và nội dung tài liệu. So sánh các tài liệu của nhiều định dạng được hỗ trợ để xác định các thay đổi giữa các tệp."

############################# Header ############################
title: "So sánh tài liệu một cách dễ dàng trong các giải pháp C# .NET của bạn"
description: "Xây dựng C# ứng dụng với API so sánh tài liệu linh hoạt cho phép so sánh tệp theo nội dung và kiểu trên các định dạng tài liệu khác nhau."
words:
  for: "cho"

actions:
  main: "Tải xuống miễn phí NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Comparison"
  alt: "Cấp phép"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/net/"
  title: "Sẵn sàng để bắt đầu?"
  description: "Dùng thử GroupDocs.Comparison tính năng miễn phí hoặc yêu cầu giấy phép"

release:
  title: "Phiên bản {0} đã phát hành"
  notes: "Xem những gì mới"
  downloads: "Tải xuống"

code:
  title: "So sánh DOCX tập tin trong C#"
  more: "Thêm ví dụ"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET"
  install: "dotnet add package GroupDocs.Comparison"
  content: |
    ```csharp {style=abap}   
    // Chỉ định tài liệu nguồn
    using (Comparer comparer = new Comparer("source.docx"))
    {
        // Thêm một hoặc nhiều tài liệu mục tiêu
        comparer.Add("target.docx");

        // Chỉ định các tùy chọn so sánh
        CompareOptions options = new CompareOptions() 
        {ShowRevisions = false};

        // So sánh và lưu kết quả
        comparer.Compare("result.docx", options);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison trong nháy mắt"
  description: "API để so sánh sự khác biệt giữa các tài liệu trong .NET ứng dụng"
  features:
    # feature loop
    - title: "So sánh tập tin trong C#"
      content: "Phát hiện sự khác biệt giữa tệp nguồn và tệp mục tiêu cho các thay đổi ở cấp đoạn văn, từ và ký tự. Xác định các thay đổi về kiểu dáng và định dạng như in đậm, in nghiêng, gạch chân, gạch ngang, kiểu phông chữ, v.v."

    # feature loop
    - title: "Hầu hết các định dạng tệp và tài liệu phổ biến được hỗ trợ"
      content: "GroupDocs.Comparison API cho phép so sánh tài liệu hiệu quả trên nhiều định dạng, bao gồm PDF, HTML, email, Microsoft Office tài liệu (Word, Excel, PowerPoint, OneNote, Visio), các loại hình ảnh khác nhau (JPEG, PNG, GIF, BMP), tệp văn bản và hơn thế nữa."

    # feature loop
    - title: "Áp dụng hoặc từ chối thay đổi một cách dễ dàng"
      content: "Mỗi sự khác biệt được xác định trong các tài liệu so sánh bằng GroupDocs.Comparison API có thể được áp dụng chọn lọc hoặc từ chối, cho phép tùy chỉnh trước khi xuất sang tài liệu đầu ra cuối cùng."

    # feature loop
    - title: "Báo cáo tóm tắt so sánh"
      content: "Tạo báo cáo tóm tắt về sự khác biệt, trình bày chi tiết tất cả các thay đổi được tìm thấy trong các tài liệu được so sánh và lưu nó để tham khảo."

############################# Platforms ############################
platforms:
  enable: true
  title: "Độc lập nền tảng"
  description: "GroupDocs.Comparison for .NET hỗ trợ các hệ điều hành, framework và trình quản lý gói sau"
  items:
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
    - title: "ReSharper"
      image: "resharper"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NuGet"
      image: "nuget"

############################# File formats ############################
formats:
  enable: true
  title: "Định dạng tập tin được hỗ trợ"
  description: |
    GroupDocs.Comparison for .NET hỗ trợ các hoạt động với [định dạng tệp] sau đây (https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
  title: "GroupDocs.Comparison tính năng"
  description: "Dễ dàng so sánh PDF và tài liệu Office, hình ảnh và các định dạng khác"

  items:
    # feature loop
    - icon: "compare"
      title: "So sánh tài liệu dễ sử dụng"
      content: "Phân tích và xác định sự khác biệt giữa hai tài liệu."

    # feature loop
    - icon: "note-stack"
      title: "So sánh nhiều tài liệu"
      content: "Đồng thời phân tích và xác định sự khác biệt giữa nhiều tài liệu."

    # feature loop
    - icon: "stacks"
      title: "Các định dạng được hỗ trợ"
      content: "Tương thích với hơn 50 định dạng tài liệu được sử dụng rộng rãi từ nhiều danh mục khác nhau, đảm bảo khả năng ứng dụng rộng rãi."

    # feature loop
    - icon: "rule"
      title: "Chấp nhận hoặc từ chối thay đổi"
      content: "Hiển thị trực quan rõ ràng các thay đổi được phát hiện, hoàn chỉnh với các tùy chọn để chấp nhận hoặc từ chối các sửa đổi này."

    # feature loop
    - icon: "preview"
      title: "Tạo bản xem trước"
      content: "Khả năng lưu kết quả so sánh dưới dạng xem trước hình ảnh để dễ dàng tham khảo và chia sẻ."

    # feature loop
    - icon: "two-pager"
      title: "So sánh nội dung"
      content: "Tiến hành so sánh văn bản kỹ lưỡng ở các cấp độ khác nhau - bao gồm từng dòng, đoạn văn, từ và ký tự - với sự khác biệt được đánh dấu để rõ ràng hơn."

    # feature loop
    - icon: "format_color_text"
      title: "So sánh kiểu dáng và định dạng"
      content: "Phát hiện và làm nổi bật những thay đổi trong định dạng và kiểu tài liệu, đảm bảo xem xét toàn diện."

    # feature loop
    - icon: "folder-managed"
      title: "Cài đặt siêu dữ liệu linh hoạt"
      content: "Bảo tồn siêu dữ liệu từ các tệp nguồn hoặc mục tiêu hoặc tùy chỉnh nó theo sở thích của người dùng."

    # feature loop
    - icon: "lock"
      title: "Bảo vệ mật khẩu"
      content: "Phân tích tài liệu được bảo vệ bằng mật khẩu và bảo mật tài liệu đầu ra bằng mã hóa mật khẩu để tăng cường bảo mật."

    # feature loop
    - icon: "select"
      title: "So sánh trang có chọn lọc"
      content: "Tải và so sánh các phần hoặc trang cụ thể của tài liệu để phân tích mục tiêu."

    # feature loop
    - icon: "speaker-notes"
      title: "Hiển thị nhận xét"
      content: "Chọn hiển thị hoặc ẩn nhận xét khi tải tài liệu nguồn, cung cấp quyền kiểm soát tốt hơn đối với quá trình so sánh."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Mẫu mã"
  description: "Một số trường hợp sử dụng của hoạt động GroupDocs.Comparison for .NET điển hình"
  items:
    # code sample loop
    - title: "So sánh các tài liệu được bảo vệ bằng mật khẩu."
      content: |
        Để so sánh các tài liệu được [bảo vệ bằng mật khẩu](https://docs.groupdocs.com/comparison/net/load-password-protected-documents/), bạn cần chỉ định tài liệu đó sau đó tải tài liệu:
        {{< landing/code title="Làm thế nào để so sánh các tài liệu được bảo vệ bằng mật khẩu.">}}
        ```csharp {style=abap}
        // Tải tài liệu nguồn và chỉ định mật khẩu của nó
        using(Comparer comparer = new Comparer("source.docx", new LoadOptions() {Password = "1234"}))  
        {
            // Tải tài liệu đích và chỉ định mật khẩu của nó
            comparer.Add("target.docx", new LoadOptions() {Password = "5678"});

            // Lưu kết quả so sánh vào một tệp được chỉ định
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "So sánh nhiều PDF tài liệu."
      content: |
        GroupDocs.Comparison cho phép bạn [so sánh nhiều hơn hai tài liệu](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/). Hoạt động gần giống như khi so sánh hai tệp. Bạn chỉ cần thêm nhiều tệp mục tiêu vào lớp `comparer`.
        {{< landing/code title="Làm thế nào để so sánh ba tài liệu trở lên.">}}
        ```csharp {style=abap}   
        // Tải tài liệu nguồn
        using(Comparer comparer = new Comparer("source.docx") 
        {
            // Chỉ định tệp thứ hai để so sánh
            comparer.Add("target2.docx");
            
            // Chỉ định tệp thứ ba để so sánh
            comparer.Add("target3.docx");
            
            // Lưu kết quả so sánh vào một tệp được chỉ định
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---
