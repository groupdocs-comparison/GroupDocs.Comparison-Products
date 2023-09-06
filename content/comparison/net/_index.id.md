---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "API Perbandingan Dokumen C# .NET | Bandingkan & Gabungkan PDF Word Excel Web & Teks"
head_description: "API Perbandingan Dokumen C# .NET. Bandingkan & gabungkan PDF Word DOC DOCX, Excel Spreadsheet, PPT, PPTX, HTML, EMLX MSG, VSDX, DXF DWG & format file gambar."

############################# Header ############################
title: ".NET API untuk Membandingkan File"
description: "Kembangkan Aplikasi menggunakan API Perbandingan Dokumen .NET untuk Memeriksa & Membandingkan file untuk Perbedaan Konten & Gaya."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Unduh Uji Coba Gratis"
    link: "https://downloads.groupdocs.com/comparison/net"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Comparison for .NET"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
        product: "GroupDocs.Comparison"
        platform: ".NET"

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
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "Harga"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    example_image: "/comparison/comparison-example.png"
    content: |
      
    more_overview:
      # more_overview_loop
      - title: "Apa itu GroupDocs.Comparison for .NET"
        content: "GroupDocs.Comparison for .NET API adalah solusi cepat dan andal yang siap digunakan saat membuat aplikasi untuk mencari dan menyorot perbedaan antara dokumen dengan format yang sama atau berbeda dalam C#, ASP.NET, atau teknologi lain yang terkait dengan platform perangkat lunak .NET."

      # more_overview_loop
      - title: "Format yang Didukung"
        content: "Pustaka GroupDocs.Comparison mendukung pendeteksian perbedaan konten dan gaya teks antara format gambar dan dokumen populer seperti PDF, HTML, email Outlook, dokumen Microsoft Office Word, spreadsheet Excel, presentasi PowerPoint, OneNote, diagram Visio, teks, png , gambar gif dan bmp serta ratusan format lainnya."
        
      # more_overview_loop
      - title: "Kemampuan Perbandingan"
        content: "Perbandingan dapat dilakukan untuk mendeteksi perubahan dalam isi kata, paragraf, tabel atau bagan dan gayanya, dan akan memberi Anda dokumen perbandingan yang mencantumkan ringkasan perbedaan, jumlah dan jenisnya. GroupDocs.Comparison for .NET dapat dengan mudah mengekstrak informasi dasar tentang dokumen sumber, membandingkan dan menyimpan dokumen sederhana, dilindungi kata sandi, dan terenkripsi dalam berbagai format melalui file atau aliran data."
        
      # more_overview_loop
      - title: "Dokumentasi dan Contoh"
        content: "Sudah ada banyak dokumentasi tentang penggunaan pustaka Perbandingan di berbagai platform dengan contoh kode, jadi Anda tidak perlu berpikir keras tentang cara bekerja dengan GroupDocs.Comparison untuk .NET API di aplikasi Anda."
        
      # more_overview_loop
      - title: "Kesesuaian"
        content: "Anda dapat menggunakan GroupDocs.Comparison for .NET untuk membuat aplikasi di lingkungan pengembangan apa pun yang berorientasi pada platform .NET. Ini kompatibel dengan semua bahasa berbasis .NET dan mendukung sistem operasi populer (Windows, Linux, MacOS) di mana Anda dapat menginstal kerangka kerja Mono atau .NET (termasuk .NET Core)."
    examples:
      enable: true
      
    more_feature:
      # more_feature_loop
      - title: "Bandingkan Dokumen dengan Mudah menggunakan .NET API"
        content: |
          GroupDocs.Comparison for .NET API memberi Anda cara yang mudah dan efisien untuk membandingkan file Anda. Berikut adalah contoh yang menunjukkan bagaimana membandingkan dua dokumen DOCX menggunakan C#:  

          ```cs
          // File sumber dan target yang akan dibandingkan
          string source = @"source.docx";
          string target = @"target.docx";
          Comparer comparer = new Comparer();
          // Bandingkan dua dokumen
          ICompareResult result = comparer.Compare(source, target, new ComparisonSettings());
          ```
      # more_feature_loop
      - title: "Pilih Tingkat Detail untuk Perbandingan"
        content: "Dengan GroupDocs.Comparison for .NET Anda dapat menentukan sejauh mana Anda ingin dokumen tersebut dibandingkan. Anda dapat memilih di antara, rendah (membandingkan teks kata demi kata dengan akurasi untuk grid pencitraan = 50), menengah (membandingkan teks karakter demi karakter dengan akurasi untuk grid pencitraan = 100) atau tinggi (membandingkan teks karakter demi karakter dengan akurasi untuk grid pencitraan = 150)."

      # more_feature_loop
      - title: "Dukungan untuk Perbandingan Gaya Teks"
        content: |
          GroupDocs.Comparison for .NET menawarkan fitur untuk membandingkan gaya teks.  

          Saat kata dan karakter dokumen dibandingkan, nama font, ukuran font, warna font, gaya font (Tebal, Miring, Garis Bawah, Huruf Kecil, Hyperlink) dan warna garis bawah (jika ada) dapat dibandingkan untuk menemukan perbedaan.  

          Saat membandingkan paragraf, Anda dapat membandingkan gaya seperti, perataan paragraf, indentasi (indentasi kiri, indentasi kanan), spasi paragraf (spasi setelah, spasi sebelumnya), indentasi baris pertama, dan spasi baris.  

          GroupDocs.Comparison for .NET juga mendukung perbandingan bagian halaman lainnya, jika memungkinkan, seperti jarak footer, tinggi & orientasi halaman, margin (kiri, kanan, atas, dan bawah), lebar garis batas, dan warna batas.  
      
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Berikut ini ikhtisar GroupDocs.Comparison for .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Ringkasan"
          content: |
            * Perbandingan Dokumen
            * Perbandingan File HTML
            * Perbandingan PDF
            * Diagram Perbandingan
            * Bandingkan Konten File
            * Bandingkan Gaya Teks
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Comparison for .NET mendukung semua [format file dokumen](https://docs.groupdocs.com/comparison/net/supported-document-formats/) yang populer termasuk: Microsoft Office, PDF, gambar, dan banyak lainnya .
        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** [DOC](https://products.groupdocs.com/comparison/net/doc/), [DOCX](https://products.groupdocs.com/comparison/net/docx/), [DOCM](https://products.groupdocs.com/comparison/net/docm/), [DOT](https://products.groupdocs.com/comparison/net/dot/), [DOTX](https://products.groupdocs.com/comparison/net/dotx/), [DOTM](https://products.groupdocs.com/comparison/net/dotm/), [RTF](https://products.groupdocs.com/comparison/net/rtf/), [TXT](https://products.groupdocs.com/comparison/net/txt/)
                * **Excel:** [XLS](https://products.groupdocs.com/comparison/net/xls/), [XLSX](https://products.groupdocs.com/comparison/net/xlsx/), [XLSM](https://products.groupdocs.com/comparison/net/xlsm/), [XLSB](https://products.groupdocs.com/comparison/net/xlsb/), [XLTM](https://products.groupdocs.com/comparison/net/xltm/), [XLT](https://products.groupdocs.com/comparison/net/xlt/), [XLTM](https://products.groupdocs.com/comparison/net/xltm/), [XLTX](https://products.groupdocs.com/comparison/net/xltx/), [XLAM](https://products.groupdocs.com/comparison/net/xlam/), [SXC](https://products.groupdocs.com/comparison/net/sxc/), [SpreadsheetML](https://products.groupdocs.com/comparison/net/xml/)
                * **PowerPoint:** [PPT](https://products.groupdocs.com/comparison/net/ppt/), [PPTX](https://products.groupdocs.com/comparison/net/pptx/), [PPS](https://products.groupdocs.com/comparison/net/pps/), [PPSX](https://products.groupdocs.com/comparison/net/ppsx/), [PPSM](https://products.groupdocs.com/comparison/net/ppsm/), [POT](https://products.groupdocs.com/comparison/net/pot/), [POTM](https://products.groupdocs.com/comparison/net/potm/), [POTX](https://products.groupdocs.com/comparison/net/potx/), [PPTM](https://products.groupdocs.com/comparison/net/pptm/)
                * **Visio:** [VSD](https://products.groupdocs.com/comparison/net/vsd/), [VDX](https://products.groupdocs.com/comparison/net/vdx/), [VSS](https://products.groupdocs.com/comparison/net/vss/), [VSSX](https://products.groupdocs.com/comparison/net/vssx/), [VSX](https://products.groupdocs.com/comparison/net/vsx/), [VST](https://products.groupdocs.com/comparison/net/vst/), [VSTX](https://products.groupdocs.com/comparison/net/vstx/), [VTX](https://products.groupdocs.com/comparison/net/vtx/), [VSDX](https://products.groupdocs.com/comparison/net/vsdx/), [VDW](https://products.groupdocs.com/comparison/net/vdw/), [VSTM](https://products.groupdocs.com/comparison/net/vstm/), [VSSM](https://products.groupdocs.com/comparison/net/vssm/), [VSDM](https://products.groupdocs.com/comparison/net/vsdm/)
                * **Outlook:** [MSG](https://products.groupdocs.com/comparison/net/msg/), [EML](https://products.groupdocs.com/comparison/net/eml/), [EMLX](https://products.groupdocs.com/comparison/net/emlx/), [PST](https://products.groupdocs.com/comparison/net/pst/), [OST](https://products.groupdocs.com/comparison/net/ost/)
                * **OneNote:** [ONE](https://products.groupdocs.com/comparison/net/one/)

        right:
          enable: true
          table:
            # table loop
            - title: "Format Lainnya"
              content: |
                * **Bahasa pemrograman**: [CS](https://products.groupdocs.com/comparison/net/cs/), [Java](https://products.groupdocs.com/comparison/net/java/), [CPP](https://products.groupdocs.com/comparison/net/cpp/), [JS](https://products.groupdocs.com/comparison/net/js/), [PY](https://products.groupdocs.com/comparison/net/py/), [RB](https://products.groupdocs.com/comparison/net/rb/), [PL](https://products.groupdocs.com/comparison/net/pl/), [ASM](https://products.groupdocs.com/comparison/net/asm/), [GROOVY](https://products.groupdocs.com/comparison/net/groovy/), [JSON](https://products.groupdocs.com/comparison/net/json/), [PHP](https://products.groupdocs.com/comparison/net/php/), [SQL](https://products.groupdocs.com/comparison/net/sql/), [LOG](https://products.groupdocs.com/comparison/net/log/), [DIFF](https://products.groupdocs.com/comparison/net/diff/), [LESS](https://products.groupdocs.com/comparison/net/less/), [SCALA](https://products.groupdocs.com/comparison/net/scala/)
                * **OpenDocument**: [ODT](https://products.groupdocs.com/comparison/net/odt/), [OTT](https://products.groupdocs.com/comparison/net/ott/), [ODS](https://products.groupdocs.com/comparison/net/ods/), [ODP](https://products.groupdocs.com/comparison/net/odp/), [OTP](https://products.groupdocs.com/comparison/net/otp/)
                * **Portable**: [PDF](https://products.groupdocs.com/comparison/net/pdf/), [MOBI](https://products.groupdocs.com/comparison/net/mobi/)
                * **AutoCAD**: [DXF](https://products.groupdocs.com/comparison/net/dxf/), [DWG](https://products.groupdocs.com/comparison/net/dwg/)
                * **Email**: [EML](https://products.groupdocs.com/comparison/net/eml/), [EMLX](https://products.groupdocs.com/comparison/net/emlx/), [MSG](https://products.groupdocs.com/comparison/net/msg/)
                * **Images**: [JPEG](https://products.groupdocs.com/comparison/net/jpeg/), [BMP](https://products.groupdocs.com/comparison/net/bmp/), [PNG](https://products.groupdocs.com/comparison/net/png/), [GIF](https://products.groupdocs.com/comparison/net/gif/), [DCM](https://products.groupdocs.com/comparison/net/dcm/), [DICOM](https://products.groupdocs.com/comparison/net/dicom/), [DjVu](https://products.groupdocs.com/comparison/net/djvu/)
                * **Web**: [HTM](https://products.groupdocs.com/comparison/net/htm/), [HTML](https://products.groupdocs.com/comparison/net/html/), [MHTML](https://products.groupdocs.com/comparison/net/mhtml/)
                * **Text**: [TXT](https://products.groupdocs.com/comparison/net/txt/)

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Comparison for .NET mendukung Sistem Operasi, Kerangka & Manajer Paket berikut:
      
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Sistem operasi"
              content: |
                * Windows Desktop
                * Windows Server
                * Windows Azure
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "Kerangka Kerja yang Didukung"
              content: |
                * .NET Framework 2.0 atau lebih tinggi
                * Mono Framework 1.2 atau lebih tinggi
                * .NET Standard 2.0
                * .NET Core 2.0

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Manajer Paket"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Lingkungan Pembangunan"
              content: |
                * Microsoft Visual Studio
                * Xamarin.Android
                * Xamarin.IOS
                * Xamarin.Mac
                * MonoDevelop

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Comparison for .NET Fitur"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "[Identifikasi Perbedaan Konten dan Gaya Font](https://docs.groupdocs.com/comparison/net/compare-documents/)"

      # feature loop
      - icon: "fas fa-eye"
        content: "[Simpan Laporan Ringkas Semua Perbedaan yang Ditemukan setelah Perbandingan File](https://docs.groupdocs.com/comparison/net/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-bolt"
        content: "[Terapkan atau Tolak Perubahan setelah Menganalisis Perbedaan dan Mengekspor File yang Dihasilkan](https://docs.groupdocs.com/comparison/net/accept-or-reject-detected-changes/)"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "[Dukungan untuk Fungsi “Lacak Perubahan” Microsoft Word saat Membandingkan File Word](https://docs.groupdocs.com/comparison/net/show-revisions/)"

      # feature loop
      - icon: "fas fa-code"
        content: "[Uniknya Temukan Perubahan yang Berasal dari Setiap Dokumen yang Dibandingkan](https://docs.groupdocs.com/comparison/net/get-list-of-changes/)"

      # feature loop
      - icon: "fas fa-cloud"
        content: "[Baca dan Kirim Dokumen melalui Streams](https://docs.groupdocs.com/comparison/net/load-file-from-stream/)"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "[Lisensi Terukur – Penagihan Sesuai Penggunaan API](https://docs.groupdocs.com/comparison/net/licensing-and-evaluation-limitations/)"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "[Bandingkan Beberapa Dokumen Sumber dengan Satu Dokumen Target](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/)"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "[Bandingkan Halaman Tertentu File Word satu sama lain – Menerima atau menolak semua perubahan dalam satu Dokumen Word](https://docs.groupdocs.com/comparison/net/accept-or-reject-detected-changes/)"

      # feature loop
      - icon: "fas fa-border-all"
        content: "[Gabungkan hingga 3 Dokumen Word dan Bandingkan Rumus yang digunakan dalam File Word](https://docs.groupdocs.com/comparison/net/how-to-merge-source-code-files/)"

      # feature loop
      - icon: "fas fa-wrench"
        content: "[Dapatkan Informasi tentang Dokumen dari filePath](https://docs.groupdocs.com/comparison/net/get-file-info/)"

      # feature loop
      - icon: "fas fa-columns"
        content: "[Simpan Hasil Perbandingan HTML sebagai Gambar](https://docs.groupdocs.com/comparison/net/generate-document-pages-preview/)"

      # feature loop
      - icon: "fas fa-file-word"
        content: "[Pilihan untuk Menampilkan atau Menyembunyikan Konten yang Dihapus](https://docs.groupdocs.com/comparison/net/show-gap-lines/)"

      # feature loop
      - icon: "fas fa-envelope"
        content: "[Pilihan untuk MENGAKTIFKAN atau MENONAKTIFKAN Perbandingan Gaya Dokumen](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fas fa-print"
        content: "[Tentukan String untuk Menandai Item yang Disisipkan, Dihapus & Perubahan Gaya dalam Dokumen Perbandingan](https://docs.groupdocs.com/comparison/net/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "[Tentukan Pemisah Kata & Warna Font untuk Menata Teks yang Dibandingkan](https://docs.groupdocs.com/comparison/net/customize-changes-styles/)"

      # feature loop
      - icon: "fas fa-lock"
        content: "[Hitung Koordinat Perubahan yang Benar dalam PDF, Word, Slide & Diagram PowerPoint](https://docs.groupdocs.com/comparison/net/get-changes-coordinates/)"

      # feature loop
      - icon: "fas fa-file-code"
        content: "[Bandingkan File yang Dilindungi Kata Sandi](https://docs.groupdocs.com/comparison/net/how-to-compare-password-protected-files/)"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "[Bandingkan Judul Bagan di Spreadsheet – Hasilkan Bagan di File Sel yang dihasilkan](https://docs.groupdocs.com/comparison/net/how-to-compare-spreadsheet-or-tables/)"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "[Mengotomatiskan ukuran bentuk otomatis dalam file dokumen Sel yang dihasilkan](https://docs.groupdocs.com/comparison/net/how-to-compare-spreadsheet-or-tables/)"

      # feature loop
      - icon: "fas fa-heading"
        content: "[Akses Halaman Ringkasan Terperinci untuk Mendeteksi Perubahan Antara File Dokumen Sumber & Target](https://docs.groupdocs.com/comparison/net/get-extended-information-on-the-summary-page/)"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "[Bandingkan File Bahasa Pemrograman & Skrip Paling Populer](https://docs.groupdocs.com/comparison/net/get-supported-document-formats/)"

      # feature loop
      - icon: "fas fa-cube"
        content: "[Bandingkan Beberapa (lebih dari dua) Dokumen PDF, Word, Excel, Diagram, Email, Teks & OneNote](https://docs.groupdocs.com/comparison/net/compare-multiple-documents-with-specific-compare-settings/)"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "[Bandingkan Header & Footer Format File yang Didukung](https://docs.groupdocs.com/comparison/net/how-to-select-options-for-flexible-comparing/)"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "[Bandingkan Bookmark, Variabel & Properti Kustom Format Dokumen Word](https://docs.groupdocs.com/comparison/net/compare-bookmarks-in-word/)"

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison menawarkan API tampilan dokumen untuk lingkungan pengembangan populer lainnya"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Comparison for Java"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-java.png"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---