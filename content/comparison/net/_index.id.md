
---
############################# Static ############################
layout: "landing"
date: 2024-12-19T07:50:01
draft: false

lang: id
product: "Comparison"
product_tag: "comparison"
platform: "Net"
platform_tag: "net"

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
head_title: "C# .NET Perangkat Lunak Perbandingan Dokumen | diff checker"
head_description: "C# .NET Perangkat lunak untuk membandingkan gaya dokumen & konten. Bandingkan dokumen dari beberapa format yang didukung untuk mengidentifikasi perubahan antar file."

############################# Header ############################
title: "Bandingkan dokumen dengan mudah dalam solusi C# .NET"
description: "Buat C# aplikasi dengan API perbandingan dokumen fleksibel yang memungkinkan perbandingan file berdasarkan konten dan gaya di berbagai format dokumen."
words:
  for: "untuk"

actions:
  main: "Gratis NuGet Unduh"
  main_link: "https://www.nuget.org/packages/GroupDocs.Comparison"
  alt: "Perizinan"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/net/"
  title: "Siap untuk memulai?"
  description: "Coba fitur GroupDocs.Comparison secara gratis atau minta lisensi"

release:
  title: "Versi {0} dirilis"
  notes: "Lihat apa yang baru"
  downloads: "Unduhan"

code:
  title: "Bandingkan file DOCX dalam C#"
  more: "Lebih banyak contoh"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET"
  install: "dotnet add package GroupDocs.Comparison"
  content: |
    ```csharp {style=abap}   
    // Tentukan dokumen sumber
    using (Comparer comparer = new Comparer("source.docx"))
    {
        // Menambahkan satu atau lebih dokumen target
        comparer.Add("target.docx");

        // Tentukan opsi perbandingan
        CompareOptions options = new CompareOptions() 
        {ShowRevisions = false};

        // Bandingkan dan simpan hasil
        comparer.Compare("result.docx", options);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "Sekilas tentang GroupDocs.Comparison"
  description: "API untuk membandingkan perbedaan antara dokumen dalam .NET aplikasi"
  features:
    # feature loop
    - title: "Perbandingan file di C#"
      content: "Mendeteksi perbedaan antara file sumber dan target untuk perubahan pada tingkat paragraf, kata, dan karakter. Identifikasi perubahan gaya dan pemformatan seperti huruf tebal, miring, garis bawah, garis-garis, jenis font, dll."

    # feature loop
    - title: "Format file dan dokumen paling populer didukung"
      content: "GroupDocs.Comparison API memungkinkan perbandingan dokumen yang efisien di berbagai format, termasuk PDF, HTML, email, Microsoft Office dokumen (Word, Excel, PowerPoint, OneNote, Visio), berbagai jenis gambar (JPEG, PNG, GIF, BMP), file teks, dan banyak lagi."

    # feature loop
    - title: "Menerapkan atau tolak perubahan dengan mudah"
      content: "Setiap perbedaan yang diidentifikasi dalam dokumen yang dibandingkan menggunakan GroupDocs.Comparison API dapat diterapkan atau ditolak secara selektif, memungkinkan penyesuaian sebelum mengekspor ke dokumen keluaran akhir."

    # feature loop
    - title: "Laporan ringkasan perbandingan"
      content: "Buat laporan ringkasan perbedaan, merinci semua perubahan yang ditemukan dalam dokumen yang dibandingkan, dan simpan untuk referensi."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independensi platform"
  description: "GroupDocs.Comparison for .NET mendukung sistem operasi, kerangka kerja dan manajer paket berikut"
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
    - title: "VS Code"
      image: "vs_code"
    # platform loop
    - title: "ReSharper"
      image: "resharper"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NuGet"
      image: "nuget"

############################# File formats ############################
formats:
  enable: true
  title: "Format file yang didukung"
  description: |
    GroupDocs.Comparison for .NET mendukung operasi dengan [format file berikut](https://docs.groupdocs.com/comparison/net/supported-document-formats/).
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
      content: "Amenganalisis dan mengidentifikasi perbedaan antara dua dokumen."

    # feature loop
    - icon: "note-stack"
      title: "Bandingkan beberapa dokumen"
      content: "Secara bersamaan menganalisis dan mengidentifikasi perbedaan di beberapa dokumen."

    # feature loop
    - icon: "stacks"
      title: "Format yang didukung"
      content: "Kompatibel dengan lebih dari 50 format dokumen yang banyak digunakan dari berbagai kategori, memastikan penerapan yang luas."

    # feature loop
    - icon: "rule"
      title: "Menerima atau tolak perubahan"
      content: "Tampilan visual yang jelas dari perubahan yang terdeteksi, lengkap dengan opsi untuk menerima atau menolak modifikasi ini."

    # feature loop
    - icon: "preview"
      title: "Hasilkan pratinjau"
      content: "Kemampuan untuk menyimpan hasil perbandingan sebagai pratinjau gambar untuk referensi dan berbagi yang mudah."

    # feature loop
    - icon: "two-pager"
      title: "Perbandingan konten"
      content: "Lakukan perbandingan teks menyeluruh di berbagai tingkatan - termasuk baris demi baris, paragraf, kata, dan karakter - dengan perbedaan yang disorot untuk kejelasan yang lebih baik."

    # feature loop
    - icon: "format_color_text"
      title: "Perbandingan gaya dan pemformatan"
      content: "Mendeteksi dan menyoroti perubahan dalam format dan gaya dokumen, memastikan tinjauan komprehensif."

    # feature loop
    - icon: "folder-managed"
      title: "Pengaturan metadata yang fleksibel"
      content: "Pertahankan metadata dari file sumber atau target, atau sesuaikan sesuai dengan preferensi pengguna."

    # feature loop
    - icon: "lock"
      title: "Perlindungan kata sandi"
      content: "Analisis dokumen yang dilindungi kata sandi dan amankan dokumen keluaran dengan enkripsi kata sandi untuk keamanan tambahan."

    # feature loop
    - icon: "select"
      title: "Perbandingan halaman selektif"
      content: "Muat dan bandingkan bagian atau halaman tertentu dari dokumen untuk analisis yang ditargetkan."

    # feature loop
    - icon: "speaker-notes"
      title: "Tampilkan komentar"
      content: "Pilih untuk menampilkan atau menyembunyikan komentar saat memuat dokumen sumber, menawarkan kontrol yang lebih besar atas proses perbandingan."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Contoh kode"
  description: "Beberapa kasus penggunaan operasi GroupDocs.Comparison for .NET tipikal"
  items:
    # code sample loop
    - title: "Membandingkan dokumen yang dilindungi kata sandi."
      content: |
        Untuk membandingkan dokumen yang [dilindungi dengan kata sandi](https://docs.groupdocs.com/comparison/net/load-password-protected-documents/), Anda perlu menentukannya lalu memuat dokumen:
        {{< landing/code title="Cara membandingkan dokumen yang dilindungi kata sandi.">}}
        ```csharp {style=abap}
        // Muat dokumen sumber dan tentukan kata sandinya
        using(Comparer comparer = new Comparer("source.docx", new LoadOptions() {Password = "1234"}))  
        {
            // Muat dokumen target dan tentukan kata sandinya
            comparer.Add("target.docx", new LoadOptions() {Password = "5678"});

            // Simpan hasil perbandingan ke file tertentu
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Membandingkan beberapa PDF dokumen."
      content: |
        GroupDocs.Comparison memungkinkan Anda untuk [membandingkan lebih dari dua dokumen](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/). Operasi ini hampir sama dengan ketika membandingkan dua file. Anda hanya perlu menambahkan lebih banyak file target ke kelas `comparer`.
        {{< landing/code title="Bagaimana membandingkan tiga dokumen atau lebih.">}}
        ```csharp {style=abap}   
        // Muat dokumen sumber
        using(Comparer comparer = new Comparer("source.docx") 
        {
            // Tentukan file kedua untuk perbandingan
            comparer.Add("target2.docx");
            
            // Tentukan file ketiga untuk perbandingan
            comparer.Add("target3.docx");
            
            // Simpan hasil perbandingan ke file tertentu
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---
