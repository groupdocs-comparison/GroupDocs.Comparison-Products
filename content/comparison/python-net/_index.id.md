
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: id
product: "Comparison"
product_tag: "comparison"
platform: "Python via .NET"
platform_tag: "python-net"

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
head_title: "Python API Perbandingan Dokumen | pemeriksa perbedaan"
head_description: "Python Document Comparison API menawarkan alat yang efisien untuk membandingkan dokumen. Terintegrasi secara mulus dengan Python untuk pelacakan perubahan instan"

############################# Header ############################
title: "Bandingkan Dokumen dengan Python: Sorot Setiap Perbedaan"
description: "Gunakan API GroupDocs.Comparison untuk mengembangkan aplikasi Python asli dengan fitur perbandingan yang sangat dapat dikonfigurasi. Bandingkan file, kontennya, dan gaya teks antara format dokumen serupa."
words:
  for: "untuk"

actions:
  main: "Unduhan PyPi Gratis"
  main_link: "https://pypi.org/project/groupdocs-comparison-net/"
  alt: "Perizinan"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/python-net/"
  title: "Siap untuk memulai?"
  description: "Coba fitur GroupDocs.Comparison secara gratis atau minta lisensi"

release:
  title: "Versi {0} dirilis"
  notes: "Lihat apa yang baru"
  downloads: "Unduhan"

code:
  title: "Bandingkan gambar BMP di Python"
  more: "Lebih banyak contoh"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET/"
  install: "pip install groupdocs-comparison-net"
  content: |
    ```python {style=abap}
    def run():

        # Tentukan dokumen sumber
        with groupdocs.comparison.Comparer("in.bmp") as comparer:

            # Menambahkan satu atau lebih dokumen target
            comparer.add("target.bmp")

            # Tentukan opsi perbandingan
            options = new groupdocs.comparison.CompareOptions()
            options.setGenerateSummaryPage(false)

            # Bandingkan dan simpan hasil
            comparer.compare("result.bmp", options)
    ```

############################# Overview ############################
overview:
  enable: true
  title: "Sekilas tentang GroupDocs.Comparison"
  description: "API untuk membandingkan jenis dokumen populer seperti PDF, Microsoft Office, HTML, email, atau gambar dalam aplikasi Python."
  features:
    # feature loop
    - title: "Laporan Keluaran Terperinci"
      content: "GroupDocs.Comparison mengidentifikasi perubahan konten dokumen (karakter, kata, paragraf, tabel, bagan) serta perubahan gaya dokumen. Ini memberi pengguna laporan yang berisi informasi rinci tentang perbedaan, termasuk jumlah dan jenisnya."

    # feature loop
    - title: "Mendukung Format File dan Dokumen Populer"
      content: "Dengan API GroupDocs.Comparison, Anda dapat membandingkan dokumen secara efisien dalam format seperti PDF, HTML, email, Microsoft Office Word, spreadsheet Excel, presentasi PowerPoint, OneNote, diagram Visio, file teks, JPEG, PNG, GIF, gambar BMP, dan banyak format lainnya."

    # feature loop
    - title: "Dokumentasi dan Contoh Komprehensif"
      content: "Tersedia dokumentasi ekstensif dan contoh kode untuk menggunakan pustaka Perbandingan pada berbagai platform, sehingga memudahkan integrasi GroupDocs.Comparison API ke dalam aplikasi Python Anda."

    # feature loop
    - title: "Pilih dan Gabungkan Perubahan menjadi Satu File"
      content: "Jika Anda memiliki versi dokumen yang berbeda, Anda dapat memilih perubahan tertentu dan mengompilasi dokumen baru menggunakan pustaka GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independensi platform"
  description: "GroupDocs.Comparison for Python via .NET mendukung sistem operasi, kerangka kerja, dan manajer paket berikut"
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
    GroupDocs.Comparison for Python via .NET mendukung operasi dengan [format file](https://docs.groupdocs.com/comparison/net/supported-document-formats/) berikut.
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
  title: "GroupDocs.Comparison for Python via .NET Fitur"
  description: "Bandingkan dokumen PDF dan Office, gambar, dan format lainnya dengan mudah."

  items:
    # feature loop
    - icon: "compare"
      title: "Perbandingan Dokumen yang Ramah Pengguna"
      content: "Menganalisis dan mengidentifikasi perbedaan antara dua dokumen."

    # feature loop
    - icon: "note-stack"
      title: "Bandingkan Beberapa Dokumen"
      content: "Analisis dan identifikasi perbedaan dalam beberapa dokumen secara bersamaan."

    # feature loop
    - icon: "stacks"
      title: "Format yang Didukung"
      content: "Mendukung lebih dari 50 format dokumen populer dari berbagai kategori."

    # feature loop
    - icon: "rule"
      title: "Terima atau Tolak Perubahan"
      content: "Representasi visual yang jelas tentang perubahan yang teridentifikasi, dengan opsi untuk menerima atau menolak modifikasi."

    # feature loop
    - icon: "preview"
      title: "Hasilkan Pratinjau"
      content: "Simpan hasil perbandingan sebagai gambar."

    # feature loop
    - icon: "two-pager"
      title: "Perbandingan Konten"
      content: "Bandingkan konten teks baris demi baris, paragraf, kata, atau karakter. Sorot perubahannya."

    # feature loop
    - icon: "format_color_text"
      title: "Perbandingan Gaya"
      content: "Mendeteksi perubahan dalam format dan gaya."

    # feature loop
    - icon: "folder-managed"
      title: "Tetapkan Metadata"
      content: "Pertahankan metadata dari file sumber atau target, atau izinkan untuk ditentukan oleh pengguna."

    # feature loop
    - icon: "lock"
      title: "Perlindungan Kata Sandi"
      content: "Analisis dokumen terenkripsi, atau amankan dokumen yang dihasilkan dengan kata sandi."

    # feature loop
    - icon: "select"
      title: "Bandingkan Halaman Tertentu"
      content: "Memuat dan membandingkan bagian atau halaman tertentu dari suatu dokumen."

    # feature loop
    - icon: "speaker-notes"
      title: "Tampilkan Komentar"
      content: "Pilih untuk menyembunyikan atau menampilkan komentar saat memuat dokumen sumber."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Contoh kode"
  description: "Jelajahi kasus penggunaan umum operasi GroupDocs.Comparison for Python via .NET"
  items:
    # code sample loop
    - title: "Membandingkan Dokumen yang Dilindungi Kata Sandi"
      content: |
        Untuk membandingkan dokumen yang [dilindungi dengan kata sandi](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/), Anda perlu menentukan kata sandi saat memuat dokumen:
        {{< landing/code title="Cara membandingkan dokumen yang dilindungi kata sandi.">}}
        ```python {style=abap}
        def run():

            # Muat dokumen sumber dan tentukan kata sandinya
            with groupdocs.comparison.Comparer("source.docx", new LoadOptions("1234")) as comparer:

                # Muat dokumen target dan tentukan kata sandinya
                comparer.add("target.docx", new LoadOptions("5678"));

                # Simpan hasil perbandingan ke file tertentu
                comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Membandingkan beberapa PDF dokumen."
      content: |
        GroupDocs.Comparison memungkinkan Anda untuk [membandingkan lebih dari dua dokumen](https://docs.groupdocs.com/comparison/python-net/compare-multiple-documents/). Operasi ini hampir sama dengan ketika membandingkan dua file. Anda hanya perlu menambahkan lebih banyak file target ke kelas `comparer`.
        {{< landing/code title="Bagaimana membandingkan tiga dokumen atau lebih.">}}
        ```python {style=abap}
        def run():

            # Muat dokumen sumber
            with groupdocs.comparison.Comparer(source.pdf") as comparer:

                # Tentukan file kedua untuk perbandingan
                comparer.add("target2.pdf");

                # Tentukan file ketiga untuk perbandingan
                comparer.add("target3.pdf");

                # Simpan hasil perbandingan ke file tertentu
                comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---