
---
############################# Static ############################
layout: "landing"
date: 2024-12-19T07:50:01
draft: false

lang: vi
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

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
head_title: "Java Thư viện so sánh tài liệu| diff checker"
head_description: "Phần mềm gốc Java để so sánh phong cách và nội dung tài liệu. So sánh các tài liệu có nhiều định dạng để xác định sự khác biệt."

############################# Header ############################
title: "So sánh và kiểm tra sự khác biệt của tệp bằng Java API"
description: "Phát triển Java ứng dụng với thư viện so sánh tài liệu có thể cấu hình cao để so sánh các định dạng tài liệu tương tự, bao gồm các tệp, nội dung của chúng và kiểu văn bản."
words:
  for: "cho"

actions:
  main: "Tải xuống miễn phí Maven"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/"
  alt: "Cấp phép"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/java/"
  title: "Sẵn sàng để bắt đầu?"
  description: "Dùng thử GroupDocs.Comparison tính năng miễn phí hoặc yêu cầu giấy phép"

release:
  title: "Phiên bản {0} đã phát hành"
  notes: "Xem những gì mới"
  downloads: "Tải xuống"

code:
  title: "So sánh DOCX tập tin trong Java"
  more: "Thêm ví dụ"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
  install: |
    <dependency>
      <groupId>com.groupdocs</groupId>
      <artifactId>groupdocs-comparison</artifactId>
      <version>{0}</version>
    </dependency>
  content: |
    ```java {style=abap}  
    // Chỉ định tài liệu nguồn
    try (Comparer comparer = new Comparer("source.docx"))
    {    
      // Thêm một hoặc nhiều tài liệu mục tiêu
      comparer.add("target.docx");

      // Chỉ định các tùy chọn so sánh
      CompareOptions options = new CompareOptions();
      options.setShowRevisions(false);

      // So sánh và lưu kết quả
      final comparer.compare("result.docx", options);
    }    
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison trong nháy mắt"
  description: "API để so sánh sự khác biệt giữa các tài liệu trong Java ứng dụng"
  features:
    # feature loop
    - title: "So sánh tập tin trong Java"
      content: "Phát hiện các thay đổi giữa tệp nguồn và tệp mục tiêu ở cấp đoạn văn, từ và ký tự. Xác định các thay đổi về kiểu dáng và định dạng như in đậm, in nghiêng, gạch chân, gạch ngang, kiểu phông chữ, v.v."

    # feature loop
    - title: "Số lượng lớn các định dạng được hỗ trợ"
      content: "Với GroupDocs.Comparison API, bạn có thể dễ dàng so sánh các tài liệu của nhiều định dạng được hỗ trợ. Điều này bao gồm PDF, HTML, email, Microsoft Office Word tài liệu, Excel bảng tính, PowerPoint bản trình bày, OneNote, Visio sơ đồ, văn bản, JPEG, PNG, GIF, và BMP hình ảnh, cũng như nhiều định dạng khác."

    # feature loop
    - title: "Áp dụng hoặc từ chối thay đổi một cách dễ dàng"
      content: "Mọi sự khác biệt giữa các tài liệu được so sánh có thể được áp dụng hoặc từ chối và sau đó xuất sang tài liệu đầu ra."

    # feature loop
    - title: "Báo cáo tóm tắt so sánh"
      content: "Tạo một báo cáo tóm tắt liệt kê tất cả các thay đổi trong các tài liệu được so sánh."

############################# Platforms ############################
platforms:
  enable: true
  title: "Độc lập nền tảng"
  description: "GroupDocs.Comparison for Java hỗ trợ các hệ điều hành, framework và trình quản lý gói sau"
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
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "Maven"
      image: "maven"

############################# File formats ############################
formats:
  enable: true
  title: "Định dạng tập tin được hỗ trợ"
  description: |
    GroupDocs.Comparison for Java hỗ trợ các hoạt động với [định dạng tệp sau đây](https://docs.groupdocs.com/comparison/java/supported-document-formats/).
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
      content: "Dễ dàng phân tích và xác định chính xác sự khác biệt giữa hai tài liệu."

    # feature loop
    - icon: "note-stack"
      title: "So sánh nhiều tài liệu"
      content: "Đồng thời kiểm tra và làm nổi bật các phương sai trên nhiều tài liệu."

    # feature loop
    - icon: "stacks"
      title: "Các định dạng được hỗ trợ"
      content: "Khả năng tương thích với hơn 50 định dạng tài liệu được sử dụng rộng rãi từ các danh mục khác nhau."

    # feature loop
    - icon: "rule"
      title: "Chấp nhận hoặc từ chối thay đổi"
      content: "Hình dung rõ ràng về các thay đổi đã xác định, với các tùy chọn để chấp nhận hoặc từ chối sửa đổi."

    # feature loop
    - icon: "preview"
      title: "Tạo bản xem trước"
      content: "Khả năng lưu kết quả so sánh dưới dạng xem trước hình ảnh."

    # feature loop
    - icon: "two-pager"
      title: "So sánh nội dung"
      content: "So sánh kỹ lưỡng nội dung văn bản ở các cấp độ khác nhau - bao gồm phân tích từng dòng, đoạn văn, từ và ký tự, nhấn mạnh vào các thay đổi."

    # feature loop
    - icon: "format_color_text"
      title: "So sánh phong cách"
      content: "Khả năng phát hiện và làm nổi bật những thay đổi trong các yếu tố định dạng và kiểu dáng."

    # feature loop
    - icon: "folder-managed"
      title: "Đặt siêu dữ liệu"
      content: "Tùy chọn để giữ lại siêu dữ liệu từ các tệp nguồn hoặc mục tiêu hoặc cho phép cài đặt siêu dữ liệu do người dùng xác định."

    # feature loop
    - icon: "lock"
      title: "Bảo vệ mật khẩu"
      content: "Tạo điều kiện phân tích các tài liệu được bảo vệ bằng mật khẩu và cho phép bảo vệ mật khẩu cho các tài liệu kết quả."

    # feature loop
    - icon: "select"
      title: "So sánh các trang cụ thể"
      content: "Tải và so sánh các phần hoặc trang cụ thể của tài liệu theo yêu cầu."

    # feature loop
    - icon: "speaker-notes"
      title: "Hiển thị nhận xét"
      content: "Tính linh hoạt để hiển thị hoặc che giấu nhận xét khi tải tài liệu nguồn."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Mẫu mã"
  description: "Một số trường hợp sử dụng của hoạt động GroupDocs.Comparison for Java điển hình"
  items:
    # code sample loop
    - title: "So sánh các tài liệu được bảo vệ bằng mật khẩu."
      content: |
        Để so sánh các tài liệu được [bảo vệ bằng mật khẩu](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/), bạn cần chỉ định tài liệu đó sau đó tải tài liệu:
        {{< landing/code title="Làm thế nào để so sánh các tài liệu được bảo vệ bằng mật khẩu.">}}
        ```java {style=abap}
        // Tải tài liệu nguồn và chỉ định mật khẩu của nó
        try (Comparer comparer = new Comparer("source.docx", new LoadOptions("1234")))
        {
            // Tải tài liệu đích và chỉ định mật khẩu của nó
            comparer.add("target.docx", new LoadOptions("5678"));
        
            // Lưu kết quả so sánh vào một tệp được chỉ định
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "So sánh nhiều PDF tài liệu."
      content: |
        GroupDocs.Comparison cho phép bạn [so sánh nhiều hơn hai tài liệu](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/). Hoạt động gần giống như khi so sánh hai tệp. Bạn chỉ cần thêm nhiều tệp mục tiêu vào lớp `comparer`.
        {{< landing/code title="Làm thế nào để so sánh ba tài liệu trở lên.">}}
        ```java {style=abap}   
        // Tải tài liệu nguồn
        try (Comparer comparer = new Comparer("source.docx") 
        {
            // Chỉ định tệp thứ hai để so sánh
            comparer.add("target2.docx");

            // Chỉ định tệp thứ ba để so sánh
            comparer.add("target3.docx");

            // Lưu kết quả so sánh vào một tệp được chỉ định
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---

