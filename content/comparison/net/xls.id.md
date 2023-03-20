
---
############################# Static ############################
layout: "auto-gen-comparison"
date: 2022-07-07T12:44:18+03:00
draft: false

############################# Head ############################
head_title: "Bandingkan dua file XLS di .NET | API Perbandingan Dokumen"
head_description: "Bandingkan dan gabungkan lebih dari dua (file XLS dalam aplikasi C# .NET. Dapatkan ringkasan perbedaan dalam konten, teks & gaya file XLS, gambar, dan format dokumen."

############################# Header ############################
title: "Bandingkan File XLS di C# .NET"
description: ".API perbandingan dokumen .NET untuk mendeteksi perubahan antara dua versi file XLS dan mengekspor ke dokumen akhir dengan ringkasan terperinci tentang perbedaan antara dokumen yang dibandingkan."
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
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
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-comparison-net.png"
        product: "GroupDocs.Comparison"
        platform: ".NET"

    middle:
        button: 
            # button loop
            - link: "https://apireference.groupdocs.com/comparison/net"
              text: "Referensi API"

            # button loop
            - link: "https://github.com/groupdocs-comparison"
              text: "Contoh Kode"

            # button loop
            - link: "https://products.groupdocs.app/comparison/family"
              text: "Demo Langsung"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/comparison/net"
              text: "Harga"

    right:
        link_download: "https://downloads.groupdocs.com/comparison"
        link_learn: "https://docs.groupdocs.com/comparison/net"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: "Tentang GroupDocs.Perbandingan untuk .NET API"
    content: |
        [GroupDocs.Comparison for .NET](/id/comparison/net/) adalah .NET API asli untuk membandingkan beberapa gambar dan dokumen dengan format yang sama. Ini membantu Anda mendeteksi perbedaan dalam paragraf, kata, karakter, bentuk, bahkan gaya teks dari dokumen yang dibandingkan, menggabungkan perubahan dan mengekspor ke dokumen akhir. Mendukung membandingkan dan menggabungkan PDF, dokumen Word, spreadsheet Excel, presentasi PowerPoint, diagram Visio, email Outlook, HTML, gambar dan format file gambar tanpa menggunakan perpustakaan eksternal.

############################# Steps ############################
steps:
    enable: true
    title_left: "Langkah-langkah untuk Membandingkan File XLS di C#"
    content_left: |
        [GroupDocs.Comparison](/id/comparison/net/) memudahkan pengembang .NET untuk membandingkan & menggabungkan beberapa file XLS dalam aplikasi mereka dengan menerapkan beberapa langkah mudah.
        
        * Buat instance objek **Comparer** dengan jalur atau aliran dokumen sumber.
        * Panggil metode Tambah dan tentukan jalur atau aliran dokumen target. Ulangi langkah ini untuk setiap dokumen target.
        * Metode Panggil Bandingkan.
    title_right: "Persyaratan sistem"
    content_right: |
        GroupDocs.Comparison untuk .NET API didukung di semua platform dan sistem operasi utama. Sebelum menjalankan kode di bawah ini, pastikan Anda telah menginstal prasyarat berikut di sistem Anda.
        
        * Sistem Operasi: Microsoft Windows, Linux, MacOS
        * Lingkungan Pengembangan: Microsoft Visual Studio, Xamarin, MonoDevelop
        * Kerangka: .NET Framework, .NET Standard, .NET Core, Mono
        * Dapatkan GroupDocs.Comparison versi terbaru untuk .NET yang diunduh dari [NuGet](https://www.nuget.org/packages/groupdocs.comparison)
    code: |
        ```cs
        // Bandingkan beberapa dokumen dari disk lokal
        
        using (Comparer comparer = new Comparer("source.xls")
        {
        	comparer.Add("target1.xls");
            comparer.Add("target2.xls");
            comparer.Add("target3.xls");
            comparer.Compare("result.xls");
        }
        
        // Bandingkan beberapa dokumen dari aliran
        
        using (Comparer comparer = new Comparer(File.OpenRead("source.xls"))
        {
        	comparer.Add(File.OpenRead("target1.xls"));
            comparer.Add(File.OpenRead("target2.xls"));
            comparer.Add(File.OpenRead("target3.xls"));
            comparer.Compare(File.Create("result.xls"));
        }
        ```

############################# Demos ############################
demos:
    enable: true
    title: "Demo Langsung Membandingkan File XLS"
    content: |
        Deteksi perbedaan antara file XLS sekarang juga dengan mengunjungi situs web [GroupDocs.Comparison](https://products.groupdocs.app/comparison/family). Demo langsung memiliki manfaat sebagai berikut.

############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-xls"
          title: "Tentang Format Berkas XLS"
          content: |
            File dengan ekstensi XLS mewakili Format File Biner Excel. File tersebut dapat dibuat oleh Microsoft Excel serta program spreadsheet serupa lainnya seperti OpenOffice Calc atau Apple Numbers. File yang disimpan oleh Excel dikenal sebagai Buku Kerja di mana setiap buku kerja dapat memiliki satu atau beberapa lembar kerja. Data disimpan dan ditampilkan kepada pengguna dalam format tabel di lembar kerja dan dapat mencakup nilai numerik, data teks, rumus, koneksi data eksternal, gambar, dan bagan. Aplikasi seperti Microsoft Excel memungkinkan Anda mengekspor data buku kerja ke beberapa format berbeda termasuk PDF, CSV, XLSX, TXT, HTML, XPS, dan beberapa lainnya. Format file XLS diganti dengan format yang lebih terbuka dan terstruktur, XLSX, dengan dirilisnya Microsoft Excel 2007. Versi terbaru masih memberikan dukungan untuk membuat dan membaca file XLS, meskipun XLSX adalah pilihan pertama yang digunakan sekarang.
          link: "https://docs.fileformat.com/image/xls/"

############################# More Formats ############################
more_formats:
    enable: true
    title: "Membandingkan Format File Lain"
    content: |
        Dokumen multi format dan API perbandingan gambar untuk .NET. Analisis perbedaan antara dokumen dengan format yang sama tanpa menggunakan alat eksternal apa pun.
    format: 
        - name: "Bandingkan File PDF"
          link: "/comparison/net/pdf/"
          description: "Format Dokumen Portabel Adobe"

        - name: "Bandingkan File DOC"
          link: "/comparison/net/doc/"
          description: "Dokumen Microsoft Word"

        - name: "Bandingkan File DOCM"
          link: "/comparison/net/docm/"
          description: "Dokumen Berkemampuan Makro Microsoft Word"

        - name: "Bandingkan File DOCX"
          link: "/comparison/net/docx/"
          description: "Microsoft Word Buka Dokumen XML"

        - name: "Bandingkan File DOT"
          link: "/comparison/net/dot/"
          description: "Templat Dokumen Microsoft Word"

        - name: "Bandingkan File DOTM"
          link: "/comparison/net/dotm/"
          description: "Templat Microsoft Word Macro-Enabled"

        - name: "Bandingkan File DOTX"
          link: "/comparison/net/dotx/"
          description: "Templat Dokumen XML Word Terbuka"

        - name: "Bandingkan File RTF"
          link: "/comparison/net/rtf/"
          description: "Format File Teks Kaya"

        - name: "Bandingkan File TXT"
          link: "/comparison/net/txt/"
          description: "Format File Teks Biasa"

        - name: "Bandingkan File XLS"
          link: "/comparison/net/xls/"
          description: "Format File Biner Microsoft Excel"

        - name: "Bandingkan File XLSX"
          link: "/comparison/net/xlsx/"
          description: "Microsoft Excel Buka XML Spreadsheet"

        - name: "Bandingkan File XLTM"
          link: "/comparison/net/xltm/"
          description: "Templat berkemampuan makro Microsoft Excel"

        - name: "Bandingkan File XLSM"
          link: "/comparison/net/xlsm/"
          description: "Spreadsheet Berkemampuan Makro Microsoft Excel"

        - name: "Bandingkan File XLSB"
          link: "/comparison/net/xlsb/"
          description: "File Spreadsheet Biner Microsoft Excel"

        - name: "Bandingkan File CSV"
          link: "/comparison/net/csv/"
          description: "File Nilai Dipisahkan Koma"

        - name: "Bandingkan File PPT"
          link: "/comparison/net/ppt/"
          description: "Presentasi powerpoint"

        - name: "Bandingkan File PPS"
          link: "/comparison/net/pps/"
          description: "Pertunjukan Slide Microsoft PowerPoint"

        - name: "Bandingkan File PPTX"
          link: "/comparison/net/pptx/"
          description: "Presentasi PowerPoint Terbuka XML"

        - name: "Bandingkan File PPSX"
          link: "/comparison/net/ppsx/"
          description: "PowerPoint Terbuka XML Slide Show"

        - name: "Bandingkan File POT"
          link: "/comparison/net/pot/"
          description: "Templat Microsoft PowerPoint"

        - name: "Bandingkan File POTX"
          link: "/comparison/net/potx/"
          description: "Templat XML Terbuka Microsoft PowerPoint"

        - name: "Bandingkan File ODS"
          link: "/comparison/net/ods/"
          description: "Buka Spreadsheet Dokumen"

        - name: "Bandingkan File ODP"
          link: "/comparison/net/odp/"
          description: "Format File Presentasi OpenDocument"

        - name: "Bandingkan File OTP"
          link: "/comparison/net/otp/"
          description: "Templat Grafik Asal"

        - name: "Bandingkan File ODT"
          link: "/comparison/net/odt/"
          description: "Buka Teks Dokumen"

        - name: "Bandingkan File OTT"
          link: "/comparison/net/ott/"
          description: "Buka Templat Dokumen"

        - name: "Bandingkan File VST"
          link: "/comparison/net/vst/"
          description: "Gambar XML Microsoft Visio 2003-2010"

        - name: "Bandingkan File TIFF"
          link: "/comparison/net/tiff/"
          description: "Format File Gambar yang Ditandai"

        - name: "Bandingkan File JPEG"
          link: "/comparison/net/jpeg/"
          description: "Gambar JPEG"

        - name: "Bandingkan File PNG"
          link: "/comparison/net/png/"
          description: "Grafik Jaringan Portabel"

        - name: "Bandingkan File GIF"
          link: "/comparison/net/gif/"
          description: "File Format Pertukaran Grafis"

        - name: "Bandingkan File BMP"
          link: "/comparison/net/bmp/"
          description: "Format File Bitmap"

        - name: "Bandingkan File HTML"
          link: "/comparison/net/html/"
          description: "Hyper Text Markup Language"

        - name: "Bandingkan File MHT"
          link: "/comparison/net/mht/"
          description: "Mime HTML"

        - name: "Bandingkan File MHTML"
          link: "/comparison/net/mhtml/"
          description: "Enkapsulasi MIME dari HTML Agregat"

        - name: "Bandingkan File MSG"
          link: "/comparison/net/msg/"
          description: "Pesan Email Microsoft Outlook"

        - name: "Bandingkan File EML"
          link: "/comparison/net/eml/"
          description: "Pesan email"

        - name: "Bandingkan File EMLX"
          link: "/comparison/net/emlx/"
          description: "File Email Apple Mail"

        - name: "Bandingkan SATU File"
          link: "/comparison/net/one/"
          description: "Microsoft OneNote"

        - name: "Bandingkan File VSD"
          link: "/comparison/net/vsd/"
          description: "Gambar Microsoft Visio 2003-2010"

        - name: "Bandingkan File VSDX"
          link: "/comparison/net/vsdx/"
          description: "Gambar Microsoft Visio"

        - name: "Bandingkan File VSS"
          link: "/comparison/net/vss/"
          description: "Microsoft Visio 2003-2010 Stensil"

        - name: "Bandingkan File VST"
          link: "/comparison/net/vst/"
          description: "Templat Microsoft Visio 2003-2010"

        - name: "Bandingkan File VDX"
          link: "/comparison/net/vdx/"
          description: "Gambar XML Microsoft Visio 2003-2010"

        - name: "Bandingkan File CS"
          link: "/comparison/net/cs/"
          description: "Bahasa CSharp"

        - name: "Bandingkan File Java"
          link: "/comparison/net/java/"
          description: "bahasa jawa"

        - name: "Bandingkan File CPP"
          link: "/comparison/net/cpp/"
          description: "Bahasa C++"

        - name: "Bandingkan File JS"
          link: "/comparison/net/js/"
          description: "Bahasa JavaScript"

        - name: "Bandingkan File PY"
          link: "/comparison/net/py/"
          description: "Bahasa Python"

        - name: "Bandingkan File RB"
          link: "/comparison/net/rb/"
          description: "Bahasa Ruby"

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Comparison offers document viewing APIs for other popular formats"

    solution:
        

############################# Back to top ###############################
back_to_top:
    enable: true
---
