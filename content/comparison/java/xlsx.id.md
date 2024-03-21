
---
############################# Static ############################
layout: "format"
date:  2024-03-21T15:26:18
draft: false
lang: id
format: Xlsx
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "GroupDocs.Comparison for Java untuk perbandingan XLSX."
head_description: "GroupDocs.Comparison API menawarkan pengambilan laporan yang merinci variasi dalam dokumen XLSX. Kompatibel dengan lingkungan Java, J2EE, dan J2SE."

############################# Header ############################
title: "Java aplikasi untuk mendeteksi perubahan di XLSX spreadsheet" 
description: "GroupDocs.Comparison Java API memungkinkan perbandingan XLSX spreadsheet dalam aplikasi Java, J2EE, atau J2SE."
subtitle: "Kerangka pemeriksaan perbedaan dokumen"  

header_actions:
  enable: true
  items:
    #  loop
    - title: "Unduhan gratis Maven"
      link: "https://releases.groupdocs.com/comparison/java/"
      
############################# About ############################
about:
    enable: true
    title: "Jelajahi keuntungan dari GroupDocs.Comparison for Java API"
    link: "/comparison/java/"
    link_title: "Pelajari selengkapnya"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       API GroupDocs.Comparison for Java memudahkan perbandingan spreadsheet XLSX, menghasilkan laporan tentang perbedaan yang ditemukan dalam teks, paragraf, bentuk, gaya, dan elemen lainnya. Selain itu, mendukung penggabungan perubahan dari beberapa file asli tanpa memerlukan pustaka eksternal. Tingkatkan Java proyek Anda dengan integrasi kode minimal.

############################# Steps ############################
steps:
    enable: true
    title: "Gunakan Java untuk membandingkan beberapa file XLSX"
    content: |
      Gunakan [GroupDocs.Comparison](https://products.groupdocs.com/comparison/java/) untuk menganalisis MS Excel spreadsheet
      
      1. Instal paket dari [Maven](https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/)
      2. Buat instance Comparer dengan spreadsheet XLSX pertama sebagai parameter
      3. Sertakan spreadsheet XLSX tambahan untuk perbandingan
      4. Nikmati laporan komprehensif
   
    code:
      platform: "net"
      copy_title: "Salin"
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
        copy_tip: "klik untuk menyalin"
        copy_done: "menyalin"
      links:
        #  loop
        - title: "Lebih banyak contoh"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
        #  loop
        - title: "Dokumentasi"
          link: "https://docs.groupdocs.com/comparison/java/"
          
      content: |
        ```java {style=abap}

        // Periksa file dari hard drive Anda untuk perbedaan atau persamaan

        // Buat objek Comparer dengan menentukan file awal
        try (Comparer comparer = new Comparer("main.xlsx") 
        {
            // Sertakan file tambahan untuk membandingkan
        	comparer.add("version1.xlsx");
            comparer.add("version2.xlsx");
            comparer.add("version3.xlsx");

            // Dapatkan laporan dengan nama yang ditentukan sebagai hasilnya
            final Path resultPath = comparer.compare("full_report.xlsx"); 

            System.out.println("\nDocuments compared successfully.");
        }
        
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "Siap untuk memulai?"
  description: "Coba fitur GroupDocs.Comparison secara gratis atau minta lisensi"
  items:
    #  loop
    - title: "Maven unduhan"
      link: "https://releases.groupdocs.com/comparison/java/"
      color: "red"
        #  loop
    - title: "Perizinan"
      link: "https://purchase.groupdocs.com/pricing/comparison/java/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Kelola perubahan di lembar bentang XLSX menggunakan Java"
    exclude: "XLSX"
    description: "Pustaka GroupDocs.Comparison Java memberdayakan pengguna untuk memantau berbagai versi spreadsheet XLSX melalui laporan terperinci dan tepat yang mudah disusun."
    items: 
        # format loop 1
        - name: "Bandingkan File PDF"
          format: "PDF"
          link: "/comparison/java/pdf/"
          description: "Adobe Portable Format Dokumen"

        # format loop 2
        - name: "Bandingkan File DOCX"
          format: "DOCX"
          link: "/comparison/java/docx/"
          description: "Microsoft Word Buka Dokumen XML"

        # format loop 3
        - name: "Bandingkan File RTF"
          format: "RTF"
          link: "/comparison/java/rtf/"
          description: "Format File Teks Kaya"

        # format loop 4
        - name: "Bandingkan File TXT"
          format: "TXT"
          link: "/comparison/java/txt/"
          description: "Format File Teks Biasa"

        # format loop 5
        - name: "Bandingkan File XLSX"
          format: "XLSX"
          link: "/comparison/java/xlsx/"
          description: "Microsoft Excel Buka Spreadsheet XML"

        # format loop 6
        - name: "Bandingkan File CSV"
          format: "CSV"
          link: "/comparison/java/csv/"
          description: "File Nilai yang Dipisahkan Koma"

        # format loop 7
        - name: "Bandingkan File PPTX"
          format: "PPTX"
          link: "/comparison/java/pptx/"
          description: "PowerPoint Presentasi XML Terbuka"

        # format loop 8
        - name: "Bandingkan File ODS"
          format: "ODS"
          link: "/comparison/java/ods/"
          description: "Open Document Spreadsheet"

        # format loop 9
        - name: "Bandingkan File ODP"
          format: "ODP"
          link: "/comparison/java/odp/"
          description: "OpenDocument Format Berkas Presentasi"

        # format loop 10
        - name: "Bandingkan File ODT"
          format: "ODT"
          link: "/comparison/java/odt/"
          description: "Open Document Teks"

        # format loop 11
        - name: "Bandingkan File JPEG"
          format: "JPEG"
          link: "/comparison/java/jpeg/"
          description: "JPEG Gambar"

        # format loop 12
        - name: "Bandingkan File PNG"
          format: "PNG"
          link: "/comparison/java/png/"
          description: "Portable Grafik Jaringan"

        # format loop 13
        - name: "Bandingkan File GIF"
          format: "GIF"
          link: "/comparison/java/gif/"
          description: "File Format Pertukaran Grafis"

        # format loop 14
        - name: "Bandingkan File BMP"
          format: "BMP"
          link: "/comparison/java/bmp/"
          description: "Format File Bitmap"

        # format loop 15
        - name: "Bandingkan File HTML"
          format: "HTML"
          link: "/comparison/java/html/"
          description: "Bahasa Markup Teks Hyper"

        # format loop 16
        - name: "Bandingkan File MSG"
          format: "MSG"
          link: "/comparison/java/msg/"
          description: "Pesan E-mail Microsoft Outlook"

        # format loop 17
        - name: "Bandingkan File ONE"
          format: "ONE"
          link: "/comparison/java/one/"
          description: "Microsoft OneNote"

        # format loop 18
        - name: "Bandingkan File VSDX"
          format: "VSDX"
          link: "/comparison/java/vsdx/"
          description: "Microsoft Visio Menggambar"

        # format loop 19
        - name: "Bandingkan File CS"
          format: "CS"
          link: "/comparison/java/cs/"
          description: "Bahasa CSharp"

        # format loop 20
        - name: "Bandingkan File Java"
          format: "Java"
          link: "/comparison/java/java/"
          description: "Java Bahasa"
          
        # format loop 21
        - name: "Bandingkan File CPP"
          format: "CPP"
          link: "/comparison/java/cpp/"
          description: "Bahasa C++"
---