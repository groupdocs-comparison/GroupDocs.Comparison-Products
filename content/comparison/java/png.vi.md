
---
############################# Static ############################
layout: "format"
date:  2024-03-21T15:26:18
draft: false
lang: vi
format: Png
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "Nhận báo cáo khác biệt cho PNG hình ảnh bằng cách sử dụng Java."
head_description: "API GroupDocs.Comparison for Java tạo báo cáo so sánh hữu ích cho PNG tài liệu trong các ứng dụng hỗ trợ J2EE và J2SE."

############################# Header ############################
title: "So sánh PNG hình ảnh bằng Java" 
description: "Tăng cường các ứng dụng Java, J2EE hoặc J2SE của bạn với GroupDocs.Comparison API. Truy xuất thông tin chi tiết về bất kỳ thay đổi nào tại PNG ảnh của bạn."
subtitle: "Khung kiểm tra sự khác biệt tài liệu"  

header_actions:
  enable: true
  items:
    #  loop
    - title: "Tải xuống miễn phí Maven"
      link: "https://releases.groupdocs.com/comparison/java/"
      
############################# About ############################
about:
    enable: true
    title: "Được thông báo về các tính năng API GroupDocs.Comparison for Java"
    link: "/comparison/java/"
    link_title: "Tìm hiểu thêm"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison được phát triển như một API Java gốc phù hợp để soạn các báo cáo chi tiết dựa trên các biến thể giữa các phiên bản hình ảnh khác nhau được trình bày ở định dạng PNG. Không chỉ định dạng PNG được hỗ trợ. Rất nhiều tính năng hữu ích được cung cấp bởi API của chúng tôi.

############################# Steps ############################
steps:
    enable: true
    title: "Sử dụng Java để so sánh các tập tin PNG"
    content: |
      So sánh PNG tệp với [GroupDocs.Comparison](https://products.groupdocs.com/comparison/java/) và truy xuất báo cáo liên quan về các thay đổi của chúng
      
      1. Cài đặt gói GroupDocs.Comparison for Java tải xuống từ [Maven](https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/)
      2. Cung cấp phiên bản Comparer và chuyển đường dẫn đến PNG
      3. Thêm PNG tệp để so sánh thêm
      4. Lưu báo cáo vào đĩa cục bộ
   
    code:
      platform: "net"
      copy_title: "Sao chép"
      install:
        command: |
          <dependencies>
            <dependency>
              <groupId>com.groupdocs</groupId>
              <artifactId>groupdocs-comparison</artifactId>
              <version>{0}</version>
            </dependency>
          </dependencies>

          <repositories>
            <repository>
              <id>repository.groupdocs.com</id>
              <name>GroupDocs Repository</name>
              <url>https://repository.groupdocs.com/repo/</url>
            </repository>
          </repositories>
        copy_tip: "bấm để sao chép"
        copy_done: "sao chép"
      links:
        #  loop
        - title: "Thêm ví dụ"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
        #  loop
        - title: "Tài liệu"
          link: "https://docs.groupdocs.com/comparison/java/"
          
      content: |
        ```java {style=abap}

        // Kiểm tra các tệp từ ổ cứng của bạn để biết sự khác biệt hoặc tương đồng

        // Tạo một đối tượng Comparer bằng cách chỉ định tệp ban đầu
        try (Comparer comparer = new Comparer("main.png") 
        {
            // Bao gồm các tệp bổ sung để so sánh
        	comparer.add("version1.png");
            comparer.add("version2.png");
            comparer.add("version3.png");

            // Nhận báo cáo với tên được chỉ định làm kết quả
            final Path resultPath = comparer.compare("full_report.png"); 

            System.out.println("\nDocuments compared successfully.");
        }
        
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "Sẵn sàng để bắt đầu?"
  description: "Dùng thử GroupDocs.Comparison tính năng miễn phí hoặc yêu cầu giấy phép"
  items:
    #  loop
    - title: "Maven tải về"
      link: "https://releases.groupdocs.com/comparison/java/"
      color: "red"
        #  loop
    - title: "Cấp phép"
      link: "https://purchase.groupdocs.com/pricing/comparison/java/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Tìm sự khác biệt ở các phiên bản khác nhau của PNG hình ảnh qua Java"
    exclude: "PNG"
    description: "GroupDocs.Comparison for Java API theo dõi các thay đổi bên trong PNG hình ảnh và soạn các báo cáo minh họa để phân tích thêm."
    items: 
        # format loop 1
        - name: "So sánh tập tin PDF"
          format: "PDF"
          link: "/comparison/java/pdf/"
          description: "Định dạng tài liệu Adobe Portable"

        # format loop 2
        - name: "So sánh tập tin DOCX"
          format: "DOCX"
          link: "/comparison/java/docx/"
          description: "Microsoft Word Tài liệu XML mở"

        # format loop 3
        - name: "So sánh tập tin RTF"
          format: "RTF"
          link: "/comparison/java/rtf/"
          description: "Định dạng tệp văn bản phong phú"

        # format loop 4
        - name: "So sánh tập tin TXT"
          format: "TXT"
          link: "/comparison/java/txt/"
          description: "Định dạng tệp văn bản thuần túy"

        # format loop 5
        - name: "So sánh tập tin XLSX"
          format: "XLSX"
          link: "/comparison/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop 6
        - name: "So sánh các tập tin CSV"
          format: "CSV"
          link: "/comparison/java/csv/"
          description: "Tệp giá trị được phân tách bằng dấu phẩy"

        # format loop 7
        - name: "So sánh tập tin PPTX"
          format: "PPTX"
          link: "/comparison/java/pptx/"
          description: "PowerPoint Bản trình bày XML mở"

        # format loop 8
        - name: "So sánh tập tin ODS"
          format: "ODS"
          link: "/comparison/java/ods/"
          description: "Open Document Bảng tính"

        # format loop 9
        - name: "So sánh các tập tin ODP"
          format: "ODP"
          link: "/comparison/java/odp/"
          description: "OpenDocument Định dạng tập tin trình bày"

        # format loop 10
        - name: "So sánh tập tin ODT"
          format: "ODT"
          link: "/comparison/java/odt/"
          description: "Open Document Văn bản"

        # format loop 11
        - name: "So sánh tập tin JPEG"
          format: "JPEG"
          link: "/comparison/java/jpeg/"
          description: "JPEG Hình ảnh"

        # format loop 12
        - name: "So sánh tập tin PNG"
          format: "PNG"
          link: "/comparison/java/png/"
          description: "Portable Đồ họa mạng"

        # format loop 13
        - name: "So sánh tập tin GIF"
          format: "GIF"
          link: "/comparison/java/gif/"
          description: "Tệp định dạng trao đổi đồ họa"

        # format loop 14
        - name: "So sánh tập tin BMP"
          format: "BMP"
          link: "/comparison/java/bmp/"
          description: "Định dạng tệp bitmap"

        # format loop 15
        - name: "So sánh các tập tin HTML"
          format: "HTML"
          link: "/comparison/java/html/"
          description: "Ngôn ngữ đánh dấu siêu văn bản"

        # format loop 16
        - name: "So sánh tập tin MSG"
          format: "MSG"
          link: "/comparison/java/msg/"
          description: "Thư điện tử Microsoft Outlook"

        # format loop 17
        - name: "So sánh tập tin ONE"
          format: "ONE"
          link: "/comparison/java/one/"
          description: "Microsoft OneNote"

        # format loop 18
        - name: "So sánh tập tin VSDX"
          format: "VSDX"
          link: "/comparison/java/vsdx/"
          description: "Microsoft Visio Bản vẽ"

        # format loop 19
        - name: "So sánh các tập tin CS"
          format: "CS"
          link: "/comparison/java/cs/"
          description: "Ngôn ngữ CSharp"

        # format loop 20
        - name: "So sánh tập tin Java"
          format: "Java"
          link: "/comparison/java/java/"
          description: "Java Ngôn ngữ"
          
        # format loop 21
        - name: "So sánh các tập tin CPP"
          format: "CPP"
          link: "/comparison/java/cpp/"
          description: "Ngôn ngữ C++"
---