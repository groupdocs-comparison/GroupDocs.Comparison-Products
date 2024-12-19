
---
############################# Static ############################
layout: "landing"
date: 2024-12-19T07:50:01
draft: false

lang: id
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
    # supported_platforms loop
    - title: "Python"
      tag: "python-net"

############################# Head ############################
head_title: "Node.js API Perbandingan Dokumen | pemeriksa perbedaan"
head_description: "API Perbandingan Dokumen Node.js menawarkan alat yang efisien untuk perbandingan dokumen. Terintegrasi dengan mulus dengan Node.js untuk pelacakan perubahan real-time"

############################# Header ############################
title: "Bandingkan Dokumen dengan Node.js: Sorot Perbedaan"
description: "Gunakan GroupDocs.Comparison API untuk mengembangkan aplikasi Script Java asli dengan fitur perbandingan yang sangat dapat dikonfigurasi. Bandingkan file, konten & gaya teksnya antara format dokumen serupa."
words:
  for: "untuk"

actions:
  main: "Unduhan NPM Gratis"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.comparison"
  alt: "Perizinan"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/nodejs-java/"
  title: "Siap untuk memulai?"
  description: "Coba fitur GroupDocs.Comparison secara gratis atau minta lisensi"

release:
  title: "Versi {0} dirilis"
  notes: "Lihat apa yang baru"
  downloads: "Unduhan"

code:
  title: "Bandingkan BMP gambar dalam Java Script"
  more: "Lebih banyak contoh"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.comparison"
  content: |
    ```javascript {style=abap}

    // Tentukan dokumen sumber
    const comparer = new Comparer("source.bmp");

    // Menambahkan satu atau lebih dokumen target
    comparer.add("target.bmp");

    // Tentukan opsi perbandingan
    const options = new groupdocs.comparison.CompareOptions();
    options.setGenerateSummaryPage(false);

    // Bandingkan dan simpan hasil
    await comparer.compare("result.bmp", options);
    ```

############################# Overview ############################
overview:
  enable: true
  title: "Sekilas tentang GroupDocs.Comparison"
  description: "API untuk membandingkan berbagai jenis dokumen seperti PDF, Microsoft Office, HTML, email, atau gambar dalam Node.js aplikasi"
  features:
    # feature loop
    - title: "Laporan keluaran terperinci"
      content: "GroupDocs.Comparison mengidentifikasi perubahan dalam konten dokumen (karakter, kata, paragraf, tabel, bagan), serta, perubahan gaya dokumen. Ini memberi pelanggan laporan hasil yang berisi informasi kaya tentang perbedaan, jumlah, dan jenisnya."

    # feature loop
    - title: "Format file dan dokumen paling populer didukung"
      content: "Dengan GroupDocs.Comparison API Anda dapat secara efisien membandingkan dokumen dari format yang didukung seperti PDF, HTML, e-mail, Microsoft Office Word dokumen, Excel spreadsheet, PowerPoint presentasi, OneNote, Visio diagram, teks, JPEG, PNG, GIF, dan BMP gambar serta banyak format lainnya."

    # feature loop
    - title: "Dokumentasi dan contoh"
      content: "Sudah ada banyak dokumentasi tentang penggunaan perpustakaan Perbandingan pada platform yang berbeda dengan contoh kode, jadi Anda tidak perlu berpikir keras tentang cara bekerja dengan GroupDocs.Comparison API di aplikasi Node.js Anda."

    # feature loop
    - title: "Pilih perubahan dan gabungkan ke satu file"
      content: "Jika Anda memiliki versi yang berbeda dari satu dokumen, Anda hanya dapat memilih perubahan yang diinginkan dan mengkompilasi dokumen baru menggunakan perpustakaan GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independensi platform"
  description: "GroupDocs.Comparison for Node.js via Java mendukung sistem operasi, kerangka kerja dan manajer paket berikut"
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
  title: "Format file yang didukung"
  description: |
    GroupDocs.Comparison for Node.js via Java mendukung operasi dengan [format file berikut](https://docs.groupdocs.com/comparison/nodejs-java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office & OpenDocument format
        * **Word:** DOCX, DOC, DOCM,DOT, DOTM, DOTX, RTX, RTF, TXT
        * **Excel:** XLSX, XLS, XLT, XLTM, XLSB, XLSM
        * **PowerPoint:** PPTX, PPT, POT, POTX, PPS, PPSX
        * **Outlook:** EML, EMLX, MSG
        * **OneNote:** ONE
        * **OpenDocument:** ODT, ODP, OTP, ODS, OTT
        * **Tata Letak Halaman Tetap:** PDF        
    # group loop
    - color: "blue"
      content: |
        ### Gambar, Grafik & Diagram
        * **Gambar raster:** BMP, GIF, JPG, JPEG, PNG
        * **Pencitraan Medis:** DICOM
        * **Microsoft Visio:** VSDX, VSD, VSS, VST, VDX
        * **AutoCAD Drawing:** DWG, DXF
      # group loop
    - color: "red"
      content: |
        ### Lainnya
        * **Teks:** TXT
        * **Bahasa Pemrograman:** CS, Java, CPP, JS, PY, RB, PL, ASM, GROOVY, JSON, PHP, SQL, LOG, DIFF, LESS, SCALA
        * **Web:** HTM, HTML, MHT, MHTML
        * **E-buku:** MOBI, DjVu
        * **Nilai yang dipisahkan pembatas:** CSV

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Comparison for Node.js via Java fitur"
  description: "Bandingkan dokumen PDF dan Office, gambar, dan format lainnya dengan mudah"

  items:
    # feature loop
    - icon: "compare"
      title: "Perbandingan dokumen yang mudah digunakan"
      content: "Menganalisis dan mengidentifikasi perbedaan dalam dua dokumen."

    # feature loop
    - icon: "note-stack"
      title: "Bandingkan beberapa dokumen"
      content: "Menganalisis dan mengidentifikasi perbedaan dalam beberapa dokumen secara bersamaan."

    # feature loop
    - icon: "stacks"
      title: "Format yang didukung"
      content: "Mendukung lebih dari 50 format dokumen populer dari berbagai kategori."

    # feature loop
    - icon: "rule"
      title: "Menerima atau tolak perubahan"
      content: "Representasi visual yang jelas dari perubahan yang diidentifikasi, memberikan opsi untuk menerima atau menolak modifikasi."

    # feature loop
    - icon: "preview"
      title: "Hasilkan pratinjau"
      content: "Simpan hasil perbandingan sebagai gambar."

    # feature loop
    - icon: "two-pager"
      title: "Perbandingan konten"
      content: "Bandingkan konten teks baris demi baris, dengan paragraf, dengan kata, dengan karakter. Sorot perubahannya."

    # feature loop
    - icon: "format_color_text"
      title: "Perbandingan gaya"
      content: "Mendeteksi perubahan dalam pemformatan dan gaya."

    # feature loop
    - icon: "folder-managed"
      title: "Tetapkan metadata"
      content: "Simpan metadata dari file sumber atau target atau izinkan untuk ditentukan oleh pengguna."

    # feature loop
    - icon: "lock"
      title: "Perlindungan kata sandi"
      content: "Analisis dokumen terenkripsi, atau amankan dokumen yang dihasilkan dengan kata sandi."

    # feature loop
    - icon: "select"
      title: "Bandingkan halaman tertentu"
      content: "Muat hanya bagian atau halaman tertentu dari dokumen."

    # feature loop
    - icon: "speaker-notes"
      title: "Tampilkan komentar"
      content: "Saat memuat dokumen sumber Anda dapat memilih apakah akan menyembunyikan atau menampilkan komentar."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Contoh kode"
  description: "Beberapa kasus penggunaan operasi GroupDocs.Comparison for Node.js via Java tipikal"
  items:
    # code sample loop
    - title: "Membandingkan dokumen yang dilindungi kata sandi."
      content: |
        Untuk membandingkan dokumen yang [dilindungi dengan kata sandi](https://docs.groupdocs.com/comparison/nodejs-java/load-password-protected-documents/), Anda perlu menentukannya lalu memuat dokumen:
        {{< landing/code title="Cara membandingkan dokumen yang dilindungi kata sandi.">}}
        ```javascript {style=abap}

        import { Comparer, LoadOptions } from '@groupdocs/groupdocs.comparison'

        // Muat dokumen sumber dan tentukan kata sandinya
        const comparer = new Comparer("source.docx", new LoadOptions("1234"));

        // Muat dokumen target dan tentukan kata sandinya
        comparer.add("target.docx", new LoadOptions("5678"));

        // Simpan hasil perbandingan ke file tertentu
        comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Membandingkan beberapa PDF dokumen."
      content: |
        GroupDocs.Comparison memungkinkan Anda untuk [membandingkan lebih dari dua dokumen](https://docs.groupdocs.com/comparison/nodejs-java/compare-multiple-documents/). Operasi ini hampir sama dengan ketika membandingkan dua file. Anda hanya perlu menambahkan lebih banyak file target ke kelas `comparer`.
        {{< landing/code title="Bagaimana membandingkan tiga dokumen atau lebih.">}}
        ```javascript {style=abap}
        import { Comparer } from '@groupdocs/groupdocs.comparison'

        // Muat dokumen sumber
        const comparer = new Comparer(source.pdf");

        // Tentukan file kedua untuk perbandingan
        comparer.add("target2.pdf");

        // Tentukan file ketiga untuk perbandingan
        comparer.add("target3.pdf");

        // Simpan hasil perbandingan ke file tertentu
        comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---