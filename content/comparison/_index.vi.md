
---
############################# Static ############################
layout: "family"
date:  2024-07-08T16:30:19
draft: false

product: "Comparison"
product_tag: "comparison"

lang: vi

############################# Head ############################
head_title: "Thư viện so sánh tài liệu C# Java & Node.js | diff checker"
head_description: "GroupDocs Thư viện so sánh tài liệu có nguồn gốc từ C # .NET Java & Node.js. Kiểm tra sự khác biệt giữa các tệp có định dạng được hỗ trợ."

############################# Header ############################
title: "So sánh sự khác biệt giữa các loại tệp phổ biến"
description: |
  API mạnh mẽ để so sánh tài liệu trên các định dạng tệp khác nhau.

  Xác định và làm nổi bật sự khác biệt về nội dung với nỗ lực mã hóa tối thiểu.

  Làm nổi bật sự khác biệt có thể nhìn thấy và khám phá những thay đổi trong các thuộc tính ẩn.

############################# Supported Platforms ###############################
supported_platforms:
  enable: true
  head_title: "Chọn nền tảng của bạn"
  title: "Độc lập nền tảng"
  description: "Thư viện GroupDocs.Comparison hỗ trợ các hệ điều hành và framework sau:"
  details_link_title: "Tìm hiểu thêm"

  items:
    # items loop
    - title: ".NET"
      description: GroupDocs.Comparison cho .NET 
      color: "blue"
      tag: "net"
      link: "/comparison/net/"
      features_link: "https://docs.groupdocs.com/comparison/net/system-requirements/"
      features:
          # features loop
          - rows: "4"
            content: |
                    .NET Framework 4.6.2 or higher <br> .NET Core 2.0 or higher <br> .NET 6.0 or higher
      
          # features loop
          - rows: "1"
            content: |
                    Windows <br> Linux <br> Mac OS
      
          # features loop
          - rows: "3"
            content: |
                    Microsoft Visual Studio <br> JetBrains Rider
      
          # features loop
          - rows: "1"
            content: |
                    50+ file formats
      

    # items loop
    - title: "Java"
      description: GroupDocs.Comparison cho Java
      color: "red"
      tag: "java"
      link: "/comparison/java/"
      features_link: "https://docs.groupdocs.com/comparison/java/system-requirements/"
      features:
          # features loop
          - rows: "4"
            content: |
                    Java 8 or higher <br> Kotlin
      
          # features loop
          - rows: "1"
            content: |
                    Windows <br> Linux <br> Mac OS
      
          # features loop
          - rows: "3"
            content: |
                    IntelliJ IDEA <br> Eclipse <br> NetBeans
      
          # features loop
          - rows: "1"
            content: |
                    50+ file formats

    # items loop
    - title: "Node.js"
      description: GroupDocs.Comparison cho Node.js
      color: "green"
      tag: "nodejs-java"
      link: "/comparison/nodejs-java/"
      features_link: "https://docs.groupdocs.com/comparison/nodejs-java/system-requirements/"
      features:
          # features loop
          - rows: "4"
            content: |
                    Node.js 16+ and J2SE 8.0 (1.8)+
      
          # features loop
          - rows: "1"
            content: |
                    Windows <br> Linux <br> Mac OS
      
          # features loop
          - rows: "3"
            content: |
                    Atom <br> Visual Studio Code <br> Bất kỳ trình soạn thảo văn bản nào khác
      
          # features loop
          - rows: "1"
            content: |
                    50+ file formats

############################# Features ###############################
features:
  enable: true
  title: "Các tính năng chính của GroupDocs.Comparison"
  description: "API để so sánh và xem khác biệt trên PDF, Word, Excel, các tệp mã nguồn và hơn thế nữa."

  items:
    # items loop
    - icon: "analize"
      title: "Kết quả xem khác biệt trực quan"
      content: "Phân tích các thay đổi dễ dàng với sự khác biệt được đánh dấu trong một báo cáo tài liệu duy nhất."

    # items loop
    - icon: "merge"
      title: "Quy trình xem xét thay đổi hiệu quả"
      content: "Chấp nhận hoặc từ chối các thay đổi với các sửa đổi trực quan khác biệt để dễ dàng ra quyết định."

    # items loop
    - icon: "styles"
      title: "So sánh nội dung và kiểu dáng"
      content: "So sánh nội dung văn bản, cũng như thay đổi định dạng và kiểu dáng."

    # items loop
    - icon: "pages"
      title: "So sánh các trang cụ thể"
      content: "Chỉ tải các phần hoặc trang cụ thể của tài liệu để so sánh."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Giới thiệu mã thực tế"
  description: "Một số trường hợp sử dụng của hoạt động GroupDocs.Comparison điển hình."
  items:
    # code sample loop
    - title: "So sánh hai tập tin"
      content: |
       Để so sánh hai tài liệu, bắt đầu bằng cách tải cả tệp nguồn và tệp đích, sau đó áp dụng phương thức `compare`. Bạn có thể linh hoạt để chọn cài đặt so sánh cụ thể để phân tích phù hợp hơn.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Chỉ định tài liệu nguồn
            using (Comparer comparer = new Comparer("source.docx"))
            {
                // Thêm một hoặc nhiều tài liệu mục tiêu
                comparer.Add(target.docx");

                // Chỉ định các tùy chọn so sánh
                CompareOptions options = new CompareOptions() {ShowRevisions = false};
                // So sánh và lưu kết quả
                comparer.Compare("result.docx", options);
            }
            ```
        - language: "Java"
          color: "red"
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
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Chỉ định tài liệu nguồn
            const comparer = new groupdocs.comparison.Comparer("source.docx");

            // Thêm một hoặc nhiều tài liệu mục tiêu
            comparer.add("target.docx");

            // Chỉ định các tùy chọn so sánh
            const options = new groupdocs.comparison.CompareOptions();
            options.setShowRevisions(false);

            // So sánh và lưu kết quả
            comparer.compare("result.docx", options);
            ```


############################# Supported Formats ###############################
formats:
  enable: true
  title: "50+ định dạng tệp được hỗ trợ"
  description: "GroupDocs.Comparison cho phép các thao tác so sánh trong các họ định dạng khác nhau."

############################# Metrics ###############################
metrics:
  enable: true
  title: "Số liệu chi tiết và thông tin thống kê"
  description: "Khám phá phân tích kỹ lưỡng về các số liệu chính của chúng tôi, cung cấp các số liệu toàn diện và thông tin chi tiết thống kê về thành tích, ảnh hưởng và sự mở rộng của chúng tôi."

  items:
    # items loop
    - number: "50+"
      title: "Các định dạng được hỗ trợ"
      content: "API chứa hơn 50 định dạng tệp và tài liệu được sử dụng rộng rãi nhất."

    # items loop
    - number: "800k"
      title: "NuGet lượt tải"
      content: "GroupDocs.Comparison cho .NET đã nhận được hơn 800K lượt tải xuống thông qua trình quản lý gói NuGet."

    # items loop
    - number: "15k"
      title: "Tải xuống Maven"
      content: "GroupDocs.Comparison cho Java đã tích lũy được hơn 15K lượt tải xuống từ kho lưu trữ Maven của chúng tôi."

    # items loop
    - number: "140+"
      title: "Khách hàng hài lòng"
      content: "Thư viện của chúng tôi được áp dụng bởi cả các nhà phát triển cá nhân và các công ty hàng đầu trên toàn thế giới"


############################# Customers ###############################
customers:
  enable: true
  title: "Khách hàng hài lòng của chúng tôi"
  description: "GroupDocs thư viện được sử dụng bởi các thương hiệu nổi tiếng và nổi tiếng trên toàn thế giới."

  items:
    # items loop
    - title: "BenQ Corporation"
      logo: "benq"
      
    # items loop
    - title: "Nasdaq Stock Market"
      logo: "nasdaq"
      
    # items loop
    - title: "AT&T Inc."
      logo: "att"
      
    # items loop
    - title: "Customer logo AstraZeneca"
      logo: "astrazeneca"
      
    # items loop
    - title: "Central Bank of Argentina"
      logo: "argentinacentralbank"
      
    # items loop
    - title: "Roche Holding AG"
      logo: "roche"
      
    # items loop
    - title: "Capita"
      logo: "capita"
      
    # items loop
    - title: "Axa S.A."
      logo: "axa"
      
    # items loop
    - title: "Instructure Inc."
      logo: "instructure"
      
    # items loop
    - title: "Wipro"
      logo: "wipro"


############################# Actions ###############################
actions:
  enable: true
  title: "Sẵn sàng để bắt đầu?"
  description: "Dùng thử GroupDocs.Comparison tính năng miễn phí trên nền tảng của bạn"

  items:
    # items loop
    - title: ".NET"
      color: "blue"
      link: "/comparison/net/"

    # items loop
    - title: "Java"
      color: "red"
      link: "/comparison/java/"

    # items loop
    - title: "Node.js"
      color: "green"
      link: "/comparison/nodejs-java/"      

############################# FAQ ###############################
faq:
  enable: true
  title: "Câu hỏi thường gặp"
  description: "Câu trả lời cho các câu hỏi thường gặp nhất."

  items:
    # items loop
    - question: "Thư viện GroupDocs.Comparison có cần bất kỳ phần mềm bên thứ ba nào khác để thao tác tài liệu không?"
      answer: "GroupDocs.Comparison không yêu cầu cài đặt bất kỳ phần mềm bên ngoài nào như Adobe Acrobat, Microsoft Office hoặc bất kỳ phần mềm nào khác."

    # items loop
    - question: "Tôi có thể dùng thử thư viện GroupDocs.Comparison trước khi mua nó không?"
      answer: "Có, bạn có thể thử GroupDocs.Comparison mà không cần mua giấy phép. Sau khi cài đặt mà không có giấy phép, thư viện hoạt động ở chế độ dùng thử. Trong chế độ này, huy hiệu dùng thử được thêm vào tài liệu kết quả và nó được cắt thành 3 trang đầu tiên. Nếu bạn muốn thử nghiệm GroupDocs.Comparison mà không có giới hạn của phiên bản dùng thử, bạn cũng có thể yêu cầu giấy phép tạm thời 30 ngày. Để biết thêm chi tiết, hãy xem [giấy phép tạm thời](https://purchase.groupdocs.com/temporary-license/)."

    # items loop
    - question: "Bạn có giấy phép nào?"
      answer: "Chúng tôi cung cấp một số loại giấy phép để phù hợp với nhu cầu của các nhà phát triển hoặc công ty cụ thể. Các loại giấy phép phụ thuộc vào số lượng nhà phát triển, số lượng vị trí trang web của nhà phát triển và liệu bạn có cần cung cấp SDK/API của chúng tôi cho khách hàng cuối của mình hay không. Ngoài ra, bạn có thể chọn giấy phép đo đếm dựa trên mức sử dụng hàng tháng của sản phẩm. Tìm hiểu thêm tại [Pricing](https://purchase.groupdocs.com/pricing/comparison/net/)."

############################# Cloud Links ###############################
cloud_links:
  enable: true
  title: "GroupDocs.Comparison API mã thấp"
  description: "Kết hợp khả năng so sánh tài liệu vào bất kỳ ứng dụng nào bằng cách sử dụng API REST dựa trên đám mây của chúng tôi."
  
  items:
    # items loop
    - title: "GroupDocs.Comparison Cloud for cURL"
      content: "Làm việc với API so sánh tài liệu cURL REST full để so sánh Word, Excel, PowerPoint và các định dạng tệp phổ biến khác."
      icon: "groupdocs_comparison-for-curl"
      link: "https://products.groupdocs.cloud/comparison/curl"

    # items loop
    - title: "GroupDocs.Comparison Cloud for .NET"
      content: "Thêm khả năng so sánh tài liệu mạnh mẽ trong .NET ứng dụng sử dụng Cloud SDK cho .NET. So sánh DOCX, XLSX, PPTX và hơn thế nữa."
      icon: "groupdocs_comparison-for-net"
      link: "https://products.groupdocs.cloud/comparison/net"

    # items loop
    - title: "GroupDocs.Comparison Cloud for Java"
      content: "Thêm tính năng so sánh tài liệu có độ trung thực cao vào các ứng dụng java của bạn với SDK so sánh tài liệu được thiết kế đặc biệt cho Java."
      icon: "groupdocs_comparison-for-java"
      link: "https://products.groupdocs.cloud/comparison/java"

############################# App links ###############################
app_links:
  enable: true
  title: "GroupDocs.Comparison Ứng dụng NoCode"
  description: "Ứng dụng dựa trên web cho phép bạn thực hiện so sánh trên hơn 50 định dạng tệp phổ biến trực tiếp trong trình duyệt của bạn."

  items:
    # items loop
    - title: "GroupDocs.Comparison Total"
      content: "Công cụ khác biệt trực tuyến để so sánh hai tài liệu từ bất kỳ thiết bị nào."
      icon: "groupdocs_comparison-app"
      link: "https://products.groupdocs.app/comparison/total"

    # items loop
    - title: "GroupDocs.Comparison DOCX"
      content: "So sánh DOCX tập tin trực tuyến."
      icon: "groupdocs_words-app"
      link: "https://products.groupdocs.app/comparison/docx"

    # items loop
    - title: "GroupDocs.Comparison PDF"
      content: "Diff PDF tài liệu trực tuyến bằng ứng dụng so sánh PDF."
      icon: "groupdocs_pdf-app"
      link: "https://products.groupdocs.app/comparison/pdf"


      


---