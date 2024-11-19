
---
############################# Static ############################
layout: "landing"
date: 2024-11-19T07:50:40
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
head_title: "Python Alat Perbandingan Dokumen | Analisis Dokumen"
head_description: "Temukan kecanggihan Alat Perbandingan Dokumen Python untuk analisis dokumen menyeluruh. Terintegrasi dengan mudah dengan Python untuk pelacakan modifikasi yang komprehensif."

############################# Header ############################
title: "Bandingkan Dokumen dengan Python: Sorot Setiap Perbedaan"
description: "Manfaatkan API GroupDocs.Comparison untuk membuat aplikasi asli dengan Python dengan fungsi perbandingan yang dapat disesuaikan. Periksa file, kontennya, dan variasi gaya di seluruh format dokumen."
words:
  for: "untuk"

actions:
  main: "Dapatkan Unduhan Gratis PyPi Sekarang"
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
  title: "Bandingkan gambar BMP menggunakan Python"
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
  description: "API yang dirancang untuk membandingkan jenis dokumen yang banyak digunakan seperti PDF, file Microsoft Office, HTML, email, atau gambar dalam aplikasi Python."
  features:
    # feature loop
    - title: "Laporan Keluaran Komprehensif"
      content: "GroupDocs.Comparison mendeteksi perubahan konten dokumen (karakter, kata, paragraf, tabel, bagan) serta perubahan gaya dokumen. Pengguna menerima laporan terperinci yang menyoroti sifat dan jumlah perubahan."

    # feature loop
    - title: "Beragam Format File dan Dokumen"
      content: "API GroupDocs.Comparison memungkinkan Anda membandingkan dokumen dalam format seperti PDF, HTML, email, Microsoft Office Word, buku kerja Excel, file PowerPoint, catatan OneNote, diagram Visio, dokumen teks, gambar JPEG, PNG, GIF, BMP, di antara banyak lainnya."

    # feature loop
    - title: "Dokumentasi Menyeluruh dan Contoh Kode"
      content: "Dokumentasi mendalam dan kode contoh untuk pustaka Perbandingan di berbagai platform sudah tersedia, menyederhanakan integrasi API GroupDocs.Comparison ke dalam aplikasi Python Anda."

    # feature loop
    - title: "Pilih dan Gabungkan Perubahan menjadi Satu Dokumen"
      content: "Jika Anda memiliki berbagai versi dokumen, Anda dapat mengkompilasi perubahan secara selektif ke dalam satu file baru menggunakan pustaka GroupDocs.Comparison."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independensi platform"
  description: "GroupDocs.Comparison for Python via .NET kompatibel dengan sistem operasi, kerangka kerja, dan manajer paket berikut."
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
    GroupDocs.Comparison for Python via .NET dapat beroperasi dengan [format file](https://docs.groupdocs.com/comparison/net/supported-document-formats/) berikut.
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
  title: "Kemampuan GroupDocs.Comparison for Python via .NET"
  description: "Bandingkan PDF, dokumen Office, gambar, dan berbagai format lainnya dengan lancar."

  items:
    # feature loop
    - icon: "compare"
      title: "Perbandingan Dokumen Intuitif"
      content: "Periksa dan soroti perbedaan antara dua dokumen."

    # feature loop
    - icon: "note-stack"
      title: "Perbandingan Beberapa Dokumen"
      content: "Periksa beberapa dokumen untuk mengetahui perbedaannya secara bersamaan."

    # feature loop
    - icon: "stacks"
      title: "Dukungan Format yang Luas"
      content: "Kompatibel dengan lebih dari 50 format dokumen yang umum digunakan di berbagai kategori."

    # feature loop
    - icon: "rule"
      title: "Terima atau Tolak Perubahan"
      content: "Visualisasikan perubahan dengan jelas, tawarkan opsi untuk menerima atau menolak pengeditan."

    # feature loop
    - icon: "preview"
      title: "Hasilkan Pratinjau Visual"
      content: "Buat pratinjau hasil perbandingan dalam format gambar."

    # feature loop
    - icon: "two-pager"
      title: "Perbandingan Konten Berbasis Teks"
      content: "Lakukan perbandingan baris demi baris, paragraf, kata, atau karakter untuk menyorot perubahan."

    # feature loop
    - icon: "format_color_text"
      title: "Deteksi Perubahan Pemformatan"
      content: "Identifikasi perubahan dalam gaya dan pemformatan dokumen."

    # feature loop
    - icon: "folder-managed"
      title: "Penanganan Metadata yang Dapat Disesuaikan"
      content: "Pertahankan metadata dari file sumber atau target, atau izinkan pengguna menentukan metadata baru."

    # feature loop
    - icon: "lock"
      title: "Menangani File yang Dilindungi Kata Sandi"
      content: "Bekerja dengan dokumen terenkripsi, atau buat dokumen aman yang dilindungi kata sandi."

    # feature loop
    - icon: "select"
      title: "Perbandingan Halaman Terfokus"
      content: "Pilih dan bandingkan bagian tertentu atau halaman individual suatu dokumen."

    # feature loop
    - icon: "speaker-notes"
      title: "Kelola Visibilitas Komentar"
      content: "Putuskan untuk mengungkapkan atau menyembunyikan komentar saat memeriksa dokumen sumber."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Contoh kode"
  description: "Temukan skenario umum untuk memanfaatkan fungsi GroupDocs.Comparison for Python via .NET."
  items:
    # code sample loop
    - title: "Membandingkan Dokumen dengan Perlindungan Kata Sandi"
      content: |
        Untuk membandingkan dokumen yang [diamankan dengan kata sandi](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/), Anda perlu menentukan kata sandi saat memuat dokumen:
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