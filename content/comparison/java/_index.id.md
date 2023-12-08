---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "API Perbandingan Dokumen Java | Bandingkan Teks & Gaya PDF Word Excel HTML"
head_description: "API Perbandingan Dokumen Java untuk membandingkan & menggabungkan Word Excel PPTX OpenOffice, Web, PDF, AutoCAD & format file lainnya. Bandingkan dokumen dengan melacak perubahan."

############################# Header ############################
title: "Java API untuk Membandingkan File"
description: "Buat aplikasi Java untuk membandingkan konten file secara efektif untuk mengetahui perbedaan dalam semua format file dokumen dan gambar standar."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Unduh Uji Coba Gratis"
    link: "https://downloads.groupdocs.com/comparison/java"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Comparison for Java"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
        product: "GroupDocs.Comparison"
        platform: "Java"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "Ringkasan"

            # button loop
            - link: "#features"
              text: "Fitur"

            # button loop
            - link: "#support"
              text: "Mendukung"

            # button loop
            - link: "https://products.groupdocs.app/comparison"
              text: "Demo Langsung"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/java"
              text: "Harga"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    example_image: "/comparison/comparison-example.webp"
    content: |
      
    more_overview:
      # more_overview_loop
      - title: "Apa itu GroupDocs.Comparison for Java"
        content: "GroupDocs.Comparison for Java adalah API paling fleksibel dan mudah digunakan untuk membantu Anda mengembangkan aplikasi perbandingan dokumen di lingkungan Java. API pemeriksa perbedaan dan penggabungan dokumen memungkinkan Anda mendeteksi perubahan dan perbedaan konten serta gaya teks antara format dokumen serupa."

      # more_overview_loop
      - title: "Format yang Didukung"
        content: "Pustaka GroupDocs.Comparison mendukung pendeteksian perbedaan konten dan gaya teks antara format gambar dan dokumen populer seperti PDF, HTML, email Outlook, dokumen Microsoft Office Word, spreadsheet Excel, presentasi PowerPoint, OneNote, diagram Visio, teks, png , gambar gif dan bmp serta ratusan format lainnya."
        
      # more_overview_loop
      - title: "Kemampuan Perbandingan"
        content: "Perbandingan dapat dilakukan untuk mendeteksi perubahan dalam isi kata, paragraf, tabel atau bagan dan gayanya, dan akan memberi Anda dokumen perbandingan yang mencantumkan ringkasan perbedaan, jumlah dan jenisnya. GroupDocs.Comparison for Java dapat dengan mudah mengekstrak informasi dasar tentang dokumen sumber, membandingkan dan menyimpan dokumen sederhana, dilindungi kata sandi, dan terenkripsi dalam berbagai format melalui file atau aliran data."
        
      # more_overview_loop
      - title: "Dokumentasi dan Contoh"
        content: "Sudah ada banyak dokumentasi tentang penggunaan pustaka Perbandingan di berbagai platform dengan contoh kode, jadi Anda tidak perlu berpikir keras tentang cara bekerja dengan GroupDocs.Comparison untuk Java API di aplikasi Anda."
        
      # more_overview_loop
      - title: "Kesesuaian"
        content: "GroupDocs.Comparison for Java tidak memerlukan instalasi perangkat lunak eksternal apa pun di sistem. Ini kompatibel dengan semua versi Java dan mendukung sistem operasi populer (Windows, Linux, MacOS) yang mampu menjalankan lingkungan runtime Java."
    examples:
      enable: true
      
    more_feature:
      # more_feature_loop
      - title: "Bandingkan Dokumen dengan Mudah menggunakan Java API"
        content: |
          Melalui API GroupDocs.Comparison for Java Anda dapat dengan mudah membandingkan dokumen dengan format yang didukung untuk menemukan perbedaan di antara dokumen tersebut. Contoh berikut menunjukkan cara membandingkan dua dokumen Microsoft Word menggunakan Java:
          
          ```java
          try (Comparer comparer = new Comparer("D:\\source.pdf")) {
              comparer.add("D:\\target.pdf");
              comparer.compare("D:\\result.pdf");
          }
          ```
      # more_feature_loop
      - title: "Tentukan Tingkat Detail Perbandingan"
        content: "GroupDocs.Comparison for Java memungkinkan Anda membandingkan dokumen sedalam tiga tingkat. Anda dapat mengatur intensitas perbandingan menjadi rendah (membandingkan teks kata demi kata dengan akurasi untuk kisi pencitraan = 50), menengah (membandingkan teks karakter demi karakter dengan akurasi untuk kisi pencitraan = 100) atau tinggi (membandingkan teks karakter demi karakter dengan akurasi untuk pencitraan kisi = 150)."

      # more_feature_loop
      - title: "Bandingkan Gaya Teks"
        content: "Selain konten dokumen, API GroupDocs.Comparison for Java juga memungkinkan untuk membandingkan gaya teks.

        Nama font, ukuran, warna, gaya (tebal, miring, garis bawah, huruf kecil, dan hyperlink) dan jika berlaku, warna di bawah juga dapat dibandingkan untuk memeriksa perbedaan di antara dokumen yang dibandingkan, saat kata dan karakter dibandingkan.  

        Untuk perbandingan paragraf, perataan, indentasi (indentasi kiri, indentasi kanan), spasi (spasi setelah, spasi sebelumnya), indentasi baris pertama, dan spasi baris juga dapat dibandingkan.  

        Demikian pula, jika memungkinkan, bagian halaman lainnya juga dapat dibandingkan melalui API GroupDocs.Comparison for Java. Bagian tersebut meliputi, jarak footer, margin halaman (kiri, kanan, atas, dan bawah), tinggi halaman, orientasi halaman, warna batas, dan lebar garis."
      
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Berikut ini ikhtisar GroupDocs.Comparison for Java:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Ringkasan"
          content: |
            * Bandingkan Isi & Gaya
            * Dapatkan Ringkasan Perbandingan
            * Terima/Tolak Perubahan di Word
            * Gabungkan & Bandingkan 3 File Word
            * Dukungan untuk Streaming
            * Deteksi Jenis File melalui Stream
            * Bandingkan File yang Dilindungi
            * Bandingkan File Terenkripsi
            * Simpan Perbandingan sebagai Gambar
            * Bandingkan Halaman Tertentu di Word
            * Bandingkan Tanda Air dalam PDF
            * Terapkan/Buang Perubahan
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison for Java mendukung semua [format file dokumen](https://docs.groupdocs.com/comparison/java/supported-document-formats/) yang populer termasuk: Microsoft Office, gambar, diagram, dan banyak lainnya .
        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** [DOC](https://products.groupdocs.com/comparison/java/doc/), [DOCX](https://products.groupdocs.com/comparison/java/docx/), [DOCM](https://products.groupdocs.com/comparison/java/docm/), [DOT](https://products.groupdocs.com/comparison/java/dot/), [DOTX](https://products.groupdocs.com/comparison/java/dotx/), [DOTM](https://products.groupdocs.com/comparison/java/dotm/), [RTF](https://products.groupdocs.com/comparison/java/rtf/), [TXT](https://products.groupdocs.com/comparison/java/txt/)
                * **Excel:** [XLS](https://products.groupdocs.com/comparison/java/xls/), [XLSX](https://products.groupdocs.com/comparison/java/xlsx/), [XLSM](https://products.groupdocs.com/comparison/java/xlsm/), [XLSB](https://products.groupdocs.com/comparison/java/xlsb/), [XLTM](https://products.groupdocs.com/comparison/java/xltm/), [XLT](https://products.groupdocs.com/comparison/java/xlt/), [XLTM](https://products.groupdocs.com/comparison/java/xltm/), [XLTX](https://products.groupdocs.com/comparison/java/xltx/), [XLAM](https://products.groupdocs.com/comparison/java/xlam/), [SXC](https://products.groupdocs.com/comparison/java/sxc/), [SpreadsheetML](https://products.groupdocs.com/comparison/java/xml/)
                * **PowerPoint:** [PPT](https://products.groupdocs.com/comparison/java/ppt/), [PPTX](https://products.groupdocs.com/comparison/java/pptx/), [PPS](https://products.groupdocs.com/comparison/java/pps/), [PPSX](https://products.groupdocs.com/comparison/java/ppsx/), [PPSM](https://products.groupdocs.com/comparison/java/ppsm/), [POT](https://products.groupdocs.com/comparison/java/pot/), [POTM](https://products.groupdocs.com/comparison/java/potm/), [POTX](https://products.groupdocs.com/comparison/java/potx/), [PPTM](https://products.groupdocs.com/comparison/java/pptm/)
                * **Visio:** [VSD](https://products.groupdocs.com/comparison/java/vsd/), [VDX](https://products.groupdocs.com/comparison/java/vdx/), [VSS](https://products.groupdocs.com/comparison/java/vss/), [VSSX](https://products.groupdocs.com/comparison/java/vssx/), [VSX](https://products.groupdocs.com/comparison/java/vsx/), [VST](https://products.groupdocs.com/comparison/java/vst/), [VSTX](https://products.groupdocs.com/comparison/java/vstx/), [VTX](https://products.groupdocs.com/comparison/java/vtx/), [VSDX](https://products.groupdocs.com/comparison/java/vsdx/), [VDW](https://products.groupdocs.com/comparison/java/vdw/), [VSTM](https://products.groupdocs.com/comparison/java/vstm/), [VSSM](https://products.groupdocs.com/comparison/java/vssm/), [VSDM](https://products.groupdocs.com/comparison/java/vsdm/)
                * **Outlook:** [MSG](https://products.groupdocs.com/comparison/java/msg/), [EML](https://products.groupdocs.com/comparison/java/eml/), [EMLX](https://products.groupdocs.com/comparison/java/emlx/), [PST](https://products.groupdocs.com/comparison/java/pst/), [OST](https://products.groupdocs.com/comparison/java/ost/)
                * **OneNote:** [ONE](https://products.groupdocs.com/comparison/java/one/)

        right:
          enable: true
          table:
            # table loop
            - title: "Format Lainnya"
              content: |
                * **Bahasa pemrograman**: [CS](https://products.groupdocs.com/comparison/java/cs/), [Java](https://products.groupdocs.com/comparison/java/java/), [CPP](https://products.groupdocs.com/comparison/java/cpp/), [JS](https://products.groupdocs.com/comparison/java/js/), [PY](https://products.groupdocs.com/comparison/java/py/), [RB](https://products.groupdocs.com/comparison/java/rb/), [PL](https://products.groupdocs.com/comparison/java/pl/), [ASM](https://products.groupdocs.com/comparison/java/asm/), [GROOVY](https://products.groupdocs.com/comparison/java/groovy/), [JSON](https://products.groupdocs.com/comparison/java/json/), [PHP](https://products.groupdocs.com/comparison/java/php/), [SQL](https://products.groupdocs.com/comparison/java/sql/), [LOG](https://products.groupdocs.com/comparison/java/log/), [DIFF](https://products.groupdocs.com/comparison/java/diff/), [LESS](https://products.groupdocs.com/comparison/java/less/), [SCALA](https://products.groupdocs.com/comparison/java/scala/)
                * **OpenDocument**: [ODT](https://products.groupdocs.com/comparison/java/odt/), [OTT](https://products.groupdocs.com/comparison/java/ott/), [ODS](https://products.groupdocs.com/comparison/java/ods/), [ODP](https://products.groupdocs.com/comparison/java/odp/), [OTP](https://products.groupdocs.com/comparison/java/otp/)
                * **Portable**: [PDF](https://products.groupdocs.com/comparison/java/pdf/), [MOBI](https://products.groupdocs.com/comparison/java/mobi/)
                * **AutoCAD**: [DXF](https://products.groupdocs.com/comparison/java/dxf/), [DWG](https://products.groupdocs.com/comparison/java/dwg/)
                * **Email**: [EML](https://products.groupdocs.com/comparison/java/eml/), [EMLX](https://products.groupdocs.com/comparison/java/emlx/), [MSG](https://products.groupdocs.com/comparison/java/msg/)
                * **Images**: [JPEG](https://products.groupdocs.com/comparison/java/jpeg/), [BMP](https://products.groupdocs.com/comparison/java/bmp/), [PNG](https://products.groupdocs.com/comparison/java/png/), [GIF](https://products.groupdocs.com/comparison/java/gif/), [DCM](https://products.groupdocs.com/comparison/java/dcm/), [DICOM](https://products.groupdocs.com/comparison/java/dicom/), [DjVu](https://products.groupdocs.com/comparison/java/djvu/)
                * **Web**: [HTM](https://products.groupdocs.com/comparison/java/htm/), [HTML](https://products.groupdocs.com/comparison/java/html/), [MHTML](https://products.groupdocs.com/comparison/java/mhtml/)
                * **Text**: [TXT](https://products.groupdocs.com/comparison/java/txt/)

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Comparison for Java mendukung Sistem Operasi, Kerangka & Manajer Paket berikut:
      
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Sistem operasi"
              content: |
                * Microsoft Windows Desktop
                * Microsoft Windows Server
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "Kerangka Kerja yang Didukung"
              content: |
                * Java 7 (1.7) atau lebih tinggi

        right:
          enable: true
          table:
            
            # table loop
            - icon: "fas fa-cogs"
              title: "Lingkungan Pembangunan"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse
            # table loop
            - icon: "fas fa-tools"
              title: "Bangun Alat Otomatisasi"
              content: |
                * Maven

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Comparison for Java Fitur"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "[Bandingkan dan Identifikasi Perubahan Konten & Gaya Teks](https://docs.groupdocs.com/comparison/java/compare-documents/)"

      # feature loop
      - icon: "fas fa-eye"
        content: "[Simpan Daftar Perbandingan Ringkas tentang Dokumen yang Dibandingkan](https://docs.groupdocs.com/comparison/java/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-bolt"
        content: "[Bandingkan Halaman Tertentu dari Dokumen Word](https://docs.groupdocs.com/comparison/java/accept-or-reject-detected-changes/)"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "[Gabungkan hingga 3 File Microsoft Word untuk Dibandingkan dengan Dukungan untuk “Lacak Perubahan”](https://docs.groupdocs.com/comparison/java/compare-multiple-documents-with-specific-compare-settings/)"

      # feature loop
      - icon: "fas fa-code"
        content: "[Temukan dengan mudah Perubahan mana yang berasal dari Dokumen mana selama Perbandingan](https://docs.groupdocs.com/comparison/java/get-list-of-changes/)"

      # feature loop
      - icon: "fas fa-cloud"
        content: "[Dukungan untuk Membaca Dokumen Sumber dan Mengirim Dokumen yang Dihasilkan melalui Aliran](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "[Deteksi Jenis Format File saat Mengambil dari Aliran](https://docs.groupdocs.com/comparison/java/get-file-info/)"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "[Bandingkan Dokumen yang Dilindungi Kata Sandi](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/)"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "[Simpan Hasil Perbandingan sebagai Gambar](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-border-all"
        content: "[Bandingkan Format File Berbeda sebagai Gambar](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-wrench"
        content: "[Bandingkan Tanda Air dalam Dokumen PDF](https://docs.groupdocs.com/comparison/java/how-to-spot-photos-differences-in-java-or-kotlin/)"

      # feature loop
      - icon: "fas fa-columns"
        content: "[Bandingkan Dokumen dari File atau Aliran dan Kirim Dokumen Hasil melalui Aliran atau File](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-file-word"
        content: "[Terima atau Buang Perubahan setelah Perbandingan File Word, PDF atau Excel](https://docs.groupdocs.com/comparison/java/accept-or-reject-detected-changes/)"

      # feature loop
      - icon: "fas fa-envelope"
        content: "[Bandingkan Dokumen Terenkripsi melalui File atau Aliran](https://docs.groupdocs.com/comparison/java/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-print"
        content: "[Opsi Lisensi Terukur untuk Operasi Perbandingan](https://docs.groupdocs.com/comparison/java/evaluation-limitations-and-licensing-of-groupdocs-comparison/)"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "[Sorot Teks untuk Perubahan yang Ditandai saat Membandingkan Dokumen PDF, Word, Excel, PowerPoint & Catatan](https://docs.groupdocs.com/comparison/java/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-lock"
        content: "[Hitung Koordinat Perubahan yang Benar dalam PDF, Slide & Diagram PowerPoint](https://docs.groupdocs.com/comparison/java/get-changes-coordinates/)"

      # feature loop
      - icon: "fas fa-file-code"
        content: "[Bandingkan Beberapa (lebih dari dua) PDF, Excel, OneNote, Diagram, Email, & Dokumen Teks](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/)"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "[Bandingkan Header & Footer Format File yang Didukung](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "[Bandingkan Dokumen & Simpan Halaman Dokumen dengan Format Berbeda sebagai Gambar](https://docs.groupdocs.com/comparison/java/generate-document-pages-preview/)"


############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison menawarkan API tampilan dokumen untuk lingkungan pengembangan populer lainnya"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
          product: "GroupDocs.Comparison"
          platform: ".NET"
          link: "/comparison/net/"

############################# Back to top ###############################
back_to_top:
  enable: true
---