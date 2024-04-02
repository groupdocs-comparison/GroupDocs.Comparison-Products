
---
############################# Static ############################
layout: "landing"
date: 2024-04-02T14:08:51
draft: false

lang: vi
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

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
head_title: "Node.js API so sánh tài liệu | trình kiểm tra diff"
head_description: "API So sánh tài liệu Node.js cung cấp các công cụ hiệu quả để so sánh tài liệu. Tích hợp liền mạch với Node.js để theo dõi thay đổi theo thời gian thực"

############################# Header ############################
title: "So sánh tài liệu với Node.js: Đánh dấu bất kỳ sự khác biệt nào"
description: "Sử dụng GroupDocs.Comparison API để phát triển các ứng dụng Script Java gốc với các tính năng so sánh có thể cấu hình cao. So sánh các tệp, nội dung và kiểu văn bản giữa các định dạng tài liệu tương tự."
words:
  for: "cho"

actions:
  main: "Tải xuống NPM miễn phí"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.comparison"
  alt: "Cấp phép"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/nodejs-java/"
  title: "Sẵn sàng để bắt đầu?"
  description: "Dùng thử GroupDocs.Comparison tính năng miễn phí hoặc yêu cầu giấy phép"

release:
  title: "Phiên bản {0} đã phát hành"
  notes: "Xem những gì mới"
  downloads: "Tải xuống"

code:
  title: "So sánh BMP hình ảnh trong Java Script"
  more: "Thêm ví dụ"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.comparison"
  content: |
    ```javascript {style=abap}

    // Chỉ định tài liệu nguồn
    const comparer = new Comparer("source.bmp");

    // Thêm một hoặc nhiều tài liệu mục tiêu
    comparer.add("target.bmp");

    // Chỉ định các tùy chọn so sánh
    const options = new groupdocs.comparison.CompareOptions();
    options.setGenerateSummaryPage(false);

    // So sánh và lưu kết quả
    await comparer.compare(outputFileName, options);
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Comparison trong nháy mắt"
  description: "API để so sánh các loại tài liệu khác nhau như PDF, Microsoft Office, HTML, e-mail hoặc hình ảnh trong Node.js ứng dụng"
  features:
    # feature loop
    - title: "Báo cáo đầu ra chi tiết"
      content: "GroupDocs.Comparison xác định những thay đổi trong nội dung tài liệu (ký tự, từ, đoạn văn, bảng, biểu đồ), cũng như thay đổi trong kiểu tài liệu. Nó cung cấp cho khách hàng một báo cáo kết quả chứa thông tin phong phú về sự khác biệt, số lượng và loại của chúng."

    # feature loop
    - title: "Hầu hết các định dạng tệp và tài liệu phổ biến được hỗ trợ"
      content: "Với GroupDocs.Comparison API, bạn có thể so sánh hiệu quả các tài liệu của bất kỳ định dạng được hỗ trợ như PDF, HTML, e-mail, tài liệu Microsoft Office Word, Excel bảng tính, PowerPoint bản trình bày, OneNote, Visio sơ đồ, văn bản, JPEG, PNG, GIF, và BMP hình ảnh cũng như nhiều định dạng khác."

    # feature loop
    - title: "Tài liệu và ví dụ"
      content: "Đã có rất nhiều tài liệu về việc sử dụng thư viện So sánh trên các nền tảng khác nhau với các ví dụ mã, vì vậy bạn không phải suy nghĩ kỹ về cách làm việc với GroupDocs.Comparison API trong ứng dụng Node.js của bạn."

    # feature loop
    - title: "Chọn thay đổi và hợp nhất chúng vào một tệp"
      content: "Nếu bạn có các phiên bản khác nhau của một tài liệu, bạn chỉ có thể chọn các thay đổi mong muốn và biên dịch tài liệu mới bằng thư viện GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Độc lập nền tảng"
  description: "GroupDocs.Comparison for Node.js via Java hỗ trợ các hệ điều hành, framework và trình quản lý gói sau"
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
    GroupDocs.Comparison for Node.js via Java hỗ trợ các hoạt động với [định dạng tệp] sau đây (https://docs.groupdocs.com/comparison/nodejs-java/supported-document-formats/).
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
  title: "GroupDocs.Comparison for Node.js via Java tính năng"
  description: "Dễ dàng so sánh PDF và tài liệu Office, hình ảnh và các định dạng khác"

  items:
    # feature loop
    - icon: "compare"
      title: "So sánh tài liệu dễ sử dụng"
      content: "Phân tích và xác định sự khác biệt trong hai tài liệu."

    # feature loop
    - icon: "note-stack"
      title: "So sánh nhiều tài liệu"
      content: "Phân tích và xác định sự khác biệt trong nhiều tài liệu cùng một lúc."

    # feature loop
    - icon: "stacks"
      title: "Các định dạng được hỗ trợ"
      content: "Hỗ trợ hơn 50 định dạng tài liệu phổ biến từ các danh mục khác nhau."

    # feature loop
    - icon: "rule"
      title: "Chấp nhận hoặc từ chối thay đổi"
      content: "Biểu diễn trực quan rõ ràng về các thay đổi đã xác định, cung cấp tùy chọn chấp nhận hoặc từ chối sửa đổi."

    # feature loop
    - icon: "preview"
      title: "Tạo bản xem trước"
      content: "Lưu kết quả so sánh dưới dạng hình ảnh."

    # feature loop
    - icon: "two-pager"
      title: "So sánh nội dung"
      content: "So sánh nội dung văn bản từng dòng, theo đoạn văn, theo từ, theo ký tự. Làm nổi bật những thay đổi."

    # feature loop
    - icon: "format_color_text"
      title: "So sánh phong cách"
      content: "Phát hiện thay đổi về định dạng và kiểu dáng."

    # feature loop
    - icon: "folder-managed"
      title: "Đặt siêu dữ liệu"
      content: "Giữ siêu dữ liệu từ tệp nguồn hoặc tệp đích hoặc cho phép người dùng chỉ định nó."

    # feature loop
    - icon: "lock"
      title: "Bảo vệ mật khẩu"
      content: "Phân tích các tài liệu được mã hóa hoặc bảo mật tài liệu kết quả bằng mật khẩu."

    # feature loop
    - icon: "select"
      title: "So sánh các trang cụ thể"
      content: "Chỉ tải các phần hoặc trang cụ thể của tài liệu."

    # feature loop
    - icon: "speaker-notes"
      title: "Hiển thị nhận xét"
      content: "Khi tải tài liệu nguồn, bạn có thể chọn ẩn hoặc hiển thị nhận xét."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Mẫu mã"
  description: "Một số trường hợp sử dụng của hoạt động GroupDocs.Comparison for Node.js via Java điển hình"
  items:
    # code sample loop
    - title: "So sánh các tài liệu được bảo vệ bằng mật khẩu."
      content: |
        Để so sánh các tài liệu được [bảo vệ bằng mật khẩu](https://docs.groupdocs.com/comparison/nodejs-java/load-password-protected-documents/), bạn cần chỉ định tài liệu đó sau đó tải tài liệu:
        {{< landing/code title="Làm thế nào để so sánh các tài liệu được bảo vệ bằng mật khẩu.">}}
        ```javascript {style=abap}

        import { Comparer, LoadOptions } from '@groupdocs/groupdocs.comparison'

        // Tải tài liệu nguồn và chỉ định mật khẩu của nó
        const comparer = new Comparer("source.docx", new LoadOptions("1234"));

        // Tải tài liệu đích và chỉ định mật khẩu của nó
        comparer.add("target.docx", new LoadOptions("5678"));

        // Lưu kết quả so sánh vào một tệp được chỉ định
        comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "So sánh nhiều PDF tài liệu."
      content: |
        GroupDocs.Comparison cho phép bạn [so sánh nhiều hơn hai tài liệu](https://docs.groupdocs.com/comparison/nodejs-java/compare-multiple-documents/). Hoạt động gần giống như khi so sánh hai tệp. Bạn chỉ cần thêm nhiều tệp mục tiêu vào lớp `comparer`.
        {{< landing/code title="Làm thế nào để so sánh ba tài liệu trở lên.">}}
        ```javascript {style=abap}
        import { Comparer } from '@groupdocs/groupdocs.comparison'

        // Tải tài liệu nguồn
        const comparer = new Comparer(source.pdf");

        // Chỉ định tệp thứ hai để so sánh
        comparer.add("target2.pdf");

        // Chỉ định tệp thứ ba để so sánh
        comparer.add("target3.pdf");

        // Lưu kết quả so sánh vào một tệp được chỉ định
        comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---