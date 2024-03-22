
---
############################# Static ############################
layout: "landing"
date: 2024-03-22T13:27:50
draft: false

lang: id
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

############################# Head ############################
head_title: "Java Perpustakaan Perbandingan Dokumen | diff checker"
head_description: "Perangkat lunak asli Java untuk membandingkan gaya dokumen & konten. Bandingkan dokumen dari berbagai format untuk mengidentifikasi perbedaan."

############################# Header ############################
title: "Bandingkan dan periksa perbedaan file menggunakan Java API"
description: "Kembangkan Java aplikasi dengan pustaka perbandingan dokumen yang sangat dapat dikonfigurasi untuk membandingkan format dokumen serupa, termasuk file, konten, dan gaya teks."
words:
  for: "untuk"

actions:
  main: "Unduhan Maven Gratis"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/"
  alt: "Perizinan"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/java/"
  title: "Siap untuk memulai?"
  description: "Coba fitur GroupDocs.Comparison secara gratis atau minta lisensi"

release:
  title: "Versi {0} dirilis"
  notes: "Lihat apa yang baru"
  downloads: "Unduhan"

code:
  title: "Bandingkan file DOCX dalam Java"
  more: "Lebih banyak contoh"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
  install: |
    <dependency>
      <groupId>com.groupdocs</groupId>
      <artifactId>groupdocs-comparison</artifactId>
      <version>{0}</version>
    </dependency>
  content: |
    ```java {style=abap}  
    // Tentukan dokumen sumber
    try (Comparer comparer = new Comparer("source.docx"))
    {    
      // Menambahkan satu atau lebih dokumen target
      comparer.add("target.docx");

      // Tentukan opsi perbandingan
      CompareOptions options = new CompareOptions();
      options.setShowRevisions(false);

      // Bandingkan dan simpan hasil
      final comparer.compare("result.docx", options);
    }    
    ```

############################# Overview ############################
overview:
  enable: true
  title: "Sekilas tentang GroupDocs.Comparison"
  description: "API untuk membandingkan perbedaan antara dokumen dalam Java aplikasi"
  features:
    # feature loop
    - title: "Perbandingan file di Java"
      content: "Mendeteksi perubahan antara file sumber dan target pada tingkat paragraf, kata, dan karakter. Identifikasi perubahan gaya dan pemformatan seperti huruf tebal, miring, garis bawah, garis-garis, jenis font, dan lainnya."

    # feature loop
    - title: "Sejumlah besar format yang didukung"
      content: "Dengan GroupDocs.Comparison API, Anda dapat dengan mudah membandingkan dokumen dari berbagai format yang didukung. Ini termasuk PDF, HTML, email, Microsoft Office Word dokumen, Excel spreadsheet, PowerPoint presentasi, OneNote, Visio diagram, teks, JPEG, PNG, GIF, dan BMP gambar, serta banyak format lainnya."

    # feature loop
    - title: "Menerapkan atau tolak perubahan dengan mudah"
      content: "Setiap perbedaan antara dokumen yang dibandingkan dapat diterapkan atau ditolak dan kemudian diekspor ke dokumen keluaran."

    # feature loop
    - title: "Laporan ringkasan perbandingan"
      content: "Buat laporan ringkasan yang mencantumkan semua perubahan dalam dokumen yang dibandingkan."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independensi platform"
  description: "GroupDocs.Comparison for Java mendukung sistem operasi, kerangka kerja dan manajer paket berikut"
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
  title: "Format file yang didukung"
  description: |
    GroupDocs.Comparison for Java mendukung operasi dengan [format file] berikut (https://docs.groupdocs.com/comparison/java/supported-document-formats/).
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
  title: "GroupDocs.Comparison fitur"
  description: "Bandingkan dokumen PDF dan Office, gambar, dan format lainnya dengan mudah"

  items:
    # feature loop
    - icon: "compare"
      title: "Perbandingan dokumen yang mudah digunakan"
      content: "Mudah menganalisis dan menentukan perbedaan antara dua dokumen."

    # feature loop
    - icon: "note-stack"
      title: "Bandingkan beberapa dokumen"
      content: "Secara bersamaan memeriksa dan menyorot variasi di beberapa dokumen."

    # feature loop
    - icon: "stacks"
      title: "Format yang didukung"
      content: "Kompatibilitas dengan lebih dari 50 format dokumen yang banyak digunakan dari berbagai kategori."

    # feature loop
    - icon: "rule"
      title: "Menerima atau tolak perubahan"
      content: "Visualisasi yang jelas dari perubahan yang diidentifikasi, dengan opsi untuk menerima atau menolak modifikasi."

    # feature loop
    - icon: "preview"
      title: "Hasilkan pratinjau"
      content: "Kemampuan untuk menyimpan hasil perbandingan sebagai pratinjau gambar."

    # feature loop
    - icon: "two-pager"
      title: "Perbandingan konten"
      content: "Perbandingan menyeluruh konten teks pada berbagai tingkatan - termasuk baris demi baris, paragraf, kata, dan analisis karakter, dengan penekanan pada perubahan."

    # feature loop
    - icon: "format_color_text"
      title: "Perbandingan gaya"
      content: "Kemampuan untuk mendeteksi dan menyorot perubahan dalam elemen pemformatan dan gaya."

    # feature loop
    - icon: "folder-managed"
      title: "Tetapkan metadata"
      content: "Opsi untuk menyimpan metadata dari file sumber atau target, atau mengizinkan pengaturan metadata yang ditentukan pengguna."

    # feature loop
    - icon: "lock"
      title: "Perlindungan kata sandi"
      content: "Memfasilitasi analisis dokumen yang dilindungi kata sandi dan memungkinkan perlindungan kata sandi untuk dokumen yang dihasilkan."

    # feature loop
    - icon: "select"
      title: "Bandingkan halaman tertentu"
      content: "Muat dan bandingkan bagian atau halaman tertentu dari dokumen sesuai kebutuhan."

    # feature loop
    - icon: "speaker-notes"
      title: "Tampilkan komentar"
      content: "Fleksibilitas untuk menampilkan atau menyembunyikan komentar saat memuat dokumen sumber."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Contoh kode"
  description: "Beberapa kasus penggunaan operasi GroupDocs.Comparison for Java tipikal"
  items:
    # code sample loop
    - title: "Membandingkan dokumen yang dilindungi kata sandi."
      content: |
        Untuk membandingkan dokumen yang [dilindungi dengan kata sandi](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/), Anda perlu menentukannya lalu memuat dokumen:
        {{< landing/code title="Cara membandingkan dokumen yang dilindungi kata sandi.">}}
        ```java {style=abap}
        // Muat dokumen sumber dan tentukan kata sandinya
        try (Comparer comparer = new Comparer("source.docx", new LoadOptions("1234")))
        {
            // Muat dokumen target dan tentukan kata sandinya
            comparer.add("target.docx", new LoadOptions("5678"));
        
            // Simpan hasil perbandingan ke file tertentu
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Membandingkan beberapa PDF dokumen."
      content: |
        GroupDocs.Comparison memungkinkan Anda untuk [membandingkan lebih dari dua dokumen](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/). Operasi ini hampir sama dengan ketika membandingkan dua file. Anda hanya perlu menambahkan lebih banyak file target ke kelas `comparer`.
        {{< landing/code title="Bagaimana membandingkan tiga dokumen atau lebih.">}}
        ```java {style=abap}   
        // Muat dokumen sumber
        try (Comparer comparer = new Comparer("source.docx") 
        {
            // Tentukan file kedua untuk perbandingan
            comparer.add("target2.docx");

            // Tentukan file ketiga untuk perbandingan
            comparer.add("target3.docx");

            // Simpan hasil perbandingan ke file tertentu
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---

