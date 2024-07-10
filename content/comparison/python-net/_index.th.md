
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: th
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
head_title: "Python API การเปรียบเทียบเอกสาร | ตัวตรวจสอบความแตกต่าง"
head_description: "API การเปรียบเทียบเอกสาร Python นำเสนอเครื่องมือที่มีประสิทธิภาพสำหรับการเปรียบเทียบเอกสาร ผสานรวมกับ Python ได้อย่างราบรื่นเพื่อการติดตามการเปลี่ยนแปลงทันที"

############################# Header ############################
title: "เปรียบเทียบเอกสารกับ Python: เน้นความแตกต่างใดๆ"
description: "ใช้ GroupDocs.Comparison API เพื่อพัฒนาแอปพลิเคชัน Python ดั้งเดิมพร้อมฟีเจอร์การเปรียบเทียบที่กำหนดค่าได้สูง เปรียบเทียบไฟล์ เนื้อหา และรูปแบบข้อความระหว่างรูปแบบเอกสารที่คล้ายคลึงกัน"
words:
  for: "สำหรับ"

actions:
  main: "ดาวน์โหลด PyPi ฟรี"
  main_link: "https://pypi.org/project/groupdocs-comparison-net/"
  alt: "การออกใบอนุญาต"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/python-net/"
  title: "พร้อมที่จะเริ่มแล้วหรือยัง?"
  description: "ลองใช้คุณสมบัติ GroupDocs.Comparison ฟรีหรือขอใบอนุญาต"

release:
  title: "เวอร์ชัน {0} เผยแพร่"
  notes: "ดูว่ามีอะไรใหม่"
  downloads: "ดาวน์โหลด"

code:
  title: "เปรียบเทียบภาพ BMP ใน Python"
  more: "ตัวอย่างเพิ่มเติม"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET/"
  install: "pip install groupdocs-comparison-net"
  content: |
    ```python {style=abap}
    def run():

        # ระบุเอกสารต้นทาง
        with groupdocs.comparison.Comparer("in.bmp") as comparer:

            # เพิ่มเอกสารเป้าหมายอย่างน้อยหนึ่งฉบับ
            comparer.add("target.bmp")

            # ระบุตัวเลือกการเปรียบเทียบ
            options = new groupdocs.comparison.CompareOptions()
            options.setGenerateSummaryPage(false)

            # เปรียบเทียบและบันทึกผล
            comparer.compare("result.bmp", options)
    ```

############################# Overview ############################
overview:
  enable: true
  title: "สรุปภาพ GroupDocs.Comparison"
  description: "API เพื่อเปรียบเทียบประเภทเอกสารยอดนิยม เช่น PDF, Microsoft Office, HTML, อีเมล หรือรูปภาพภายในแอปพลิเคชัน Python"
  features:
    # feature loop
    - title: "รายงานผลลัพธ์โดยละเอียด"
      content: "GroupDocs.Comparison ระบุการเปลี่ยนแปลงในเนื้อหาเอกสาร (อักขระ คำ ย่อหน้า ตาราง แผนภูมิ) รวมถึงการเปลี่ยนแปลงในรูปแบบเอกสาร โดยจะให้รายงานแก่ผู้ใช้ที่มีข้อมูลโดยละเอียดเกี่ยวกับความแตกต่าง รวมถึงจำนวนและประเภท"

    # feature loop
    - title: "รองรับรูปแบบไฟล์และเอกสารยอดนิยม"
      content: "ด้วย GroupDocs.Comparison API คุณสามารถเปรียบเทียบเอกสารในรูปแบบต่างๆ เช่น PDF, HTML, อีเมล, Microsoft Office Word, สเปรดชีต Excel, งานนำเสนอ PowerPoint, OneNote, ไดอะแกรม Visio, ไฟล์ข้อความ, JPEG, PNG, GIF, รูปภาพ BMP, และรูปแบบอื่น ๆ อีกมากมาย"

    # feature loop
    - title: "เอกสารและตัวอย่างที่ครอบคลุม"
      content: "มีเอกสารประกอบและตัวอย่างโค้ดที่ครอบคลุมสำหรับการใช้ไลบรารีการเปรียบเทียบบนแพลตฟอร์มต่างๆ ทำให้ง่ายต่อการรวม API GroupDocs.Comparison เข้ากับแอปพลิเคชัน Python ของคุณ"

    # feature loop
    - title: "เลือกและรวมการเปลี่ยนแปลงเป็นไฟล์เดียว"
      content: "หากคุณมีเอกสารเวอร์ชันที่แตกต่างกัน คุณสามารถเลือกการเปลี่ยนแปลงเฉพาะและคอมไพล์เอกสารใหม่ได้โดยใช้ไลบรารี GroupDocs.Comparison"

############################# Platforms ############################
platforms:
  enable: true
  title: "อิสระของแพลตฟอร์"
  description: "GroupDocs.Comparison for Python via .NET รองรับระบบปฏิบัติการ เฟรมเวิร์ก และตัวจัดการแพ็คเกจต่อไปนี้"
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
  title: "รูปแบบไฟล์ที่รองรับ"
  description: |
    GroupDocs.Comparison for Python via .NET รองรับการดำเนินการกับ [รูปแบบไฟล์ ต่อไปนี้](https://docs.groupdocs.com/comparison/net/supported-document-formats/)
  groups:
    # group loop
    - color: "green"
      content: |
        ### รูปแบบ Microsoft Office และ OpenDocument
        * **Word:** DOCX, DOC, DOCM,DOT, DOTM, DOTX, RTX, RTF, TXT
        * **Excel:** XLSX, XLS, XLT, XLTM, XLSB, XLSM
        * **PowerPoint:** PPTX, PPT, POT, POTX, PPS, PPSX
        * **Outlook:** EML, EMLX, MSG
        * **OneNote:** ONE
        * **OpenDocument:** ODT, ODP, OTP, ODS, OTT
        * **เค้าโครงหน้าคงที่:** PDF        
    # group loop
    - color: "blue"
      content: |
        ### รูปภาพ กราฟิก และไดอะแกรม
        * **ภาพแรสเตอร์:** BMP, GIF, JPG, JPEG, PNG
        * **การถ่ายภาพทางการแพทย์:** DICOM
        * **Microsoft Visio:** VSDX, VSD, VSS, VST, VDX
        * **AutoCAD Drawing:** DWG, DXF
      # group loop
    - color: "red"
      content: |
        ### อื่น ๆ
        * **ข้อความ:** TXT
        * **ภาษาการเขียนโปรแกรม:** CS, Java, CPP, JS, PY, RB, PL, ASM, GROOVY, JSON, PHP, SQL, LOG, DIFF, LESS, SCALA
        * **เว็บ:** HTM, HTML, MHT, MHTML
        * **หนังสืออิเล็กทรอนิกส์:** MOBI, DjVu
        * **ค่าที่คั่นด้วยตัวแยก:** CSV

############################# Features ############################
features:
  enable: true
  title: "คุณลักษณะของ GroupDocs.Comparison for Python via .NET"
  description: "เปรียบเทียบเอกสาร PDF และ Office รูปภาพ และรูปแบบอื่นๆ ได้อย่างง่ายดาย"

  items:
    # feature loop
    - icon: "compare"
      title: "การเปรียบเทียบเอกสารที่ใช้งานง่าย"
      content: "วิเคราะห์และระบุความแตกต่างระหว่างเอกสารสองฉบับ"

    # feature loop
    - icon: "note-stack"
      title: "เปรียบเทียบเอกสารหลายชุด"
      content: "วิเคราะห์และระบุความแตกต่างภายในเอกสารหลายฉบับพร้อมกัน"

    # feature loop
    - icon: "stacks"
      title: "รูปแบบที่รองรับ"
      content: "รองรับรูปแบบเอกสารยอดนิยมมากกว่า 50 รูปแบบจากหมวดหมู่ต่างๆ"

    # feature loop
    - icon: "rule"
      title: "ยอมรับหรือปฏิเสธการเปลี่ยนแปลง"
      content: "การแสดงการเปลี่ยนแปลงที่ระบุด้วยภาพที่ชัดเจน พร้อมตัวเลือกในการยอมรับหรือปฏิเสธการแก้ไข"

    # feature loop
    - icon: "preview"
      title: "สร้างการแสดงตัวอย่าง"
      content: "บันทึกผลการเปรียบเทียบเป็นรูปภาพ"

    # feature loop
    - icon: "two-pager"
      title: "การเปรียบเทียบเนื้อหา"
      content: "เปรียบเทียบเนื้อหาข้อความทีละบรรทัด ตามย่อหน้า ตามคำ หรือตามอักขระ เน้นการเปลี่ยนแปลง"

    # feature loop
    - icon: "format_color_text"
      title: "การเปรียบเทียบสไตล์"
      content: "ตรวจจับการเปลี่ยนแปลงการจัดรูปแบบและสไตล์"

    # feature loop
    - icon: "folder-managed"
      title: "ตั้งค่าข้อมูลเมตา"
      content: "เก็บข้อมูลเมตาจากไฟล์ต้นฉบับหรือไฟล์เป้าหมาย หรืออนุญาตให้ผู้ใช้ระบุได้"

    # feature loop
    - icon: "lock"
      title: "การป้องกันด้วยรหัสผ่าน"
      content: "วิเคราะห์เอกสารที่เข้ารหัสหรือรักษาความปลอดภัยเอกสารผลลัพธ์ด้วยรหัสผ่าน"

    # feature loop
    - icon: "select"
      title: "เปรียบเทียบหน้าเว็บเฉพาะ"
      content: "โหลดและเปรียบเทียบส่วนหรือหน้าเฉพาะของเอกสาร"

    # feature loop
    - icon: "speaker-notes"
      title: "แสดงความคิดเห็น"
      content: "เลือกที่จะซ่อนหรือแสดงความคิดเห็นเมื่อโหลดเอกสารต้นฉบับ"

############################# Code samples ############################
code_samples:
  enable: true
  title: "ตัวอย่างรหัส"
  description: "สำรวจกรณีการใช้งานทั่วไปของการดำเนินการ GroupDocs.Comparison for Python via .NET"
  items:
    # code sample loop
    - title: "การเปรียบเทียบเอกสารที่ป้องกันด้วยรหัสผ่าน"
      content: |
        หากต้องการเปรียบเทียบเอกสารที่ [ป้องกันด้วยรหัสผ่าน](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/) คุณต้องระบุรหัสผ่านเมื่อโหลดเอกสาร:
        {{< landing/code title="วิธีเปรียบเทียบเอกสารที่ป้องกันด้วยรหัสผ่าน">}}
        ```python {style=abap}
        def run():

            # โหลดเอกสารต้นฉบับและระบุรหัสผ่าน
            with groupdocs.comparison.Comparer("source.docx", new LoadOptions("1234")) as comparer:

                # โหลดเอกสารเป้าหมายและระบุรหัสผ่าน
                comparer.add("target.docx", new LoadOptions("5678"));

                # บันทึกผลการเปรียบเทียบลงในไฟล์ที่ระบุ
                comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "เปรียบเทียบเอกสาร PDF หลายเอกสาร"
      content: |
        GroupDocs.Comparison ช่วยให้คุณสามารถ [เปรียบเทียบเอกสารมากกว่าสองเอกสาร](https://docs.groupdocs.com/comparison/python-net/compare-multiple-documents/)การดำเนินการเกือบจะเหมือนกับเมื่อเปรียบเทียบสองไฟล์คุณเพียงแค่ต้องเพิ่มไฟล์เป้าหมายเพิ่มเติมลงในคลาส `comparer`
        {{< landing/code title="วิธีเปรียบเทียบเอกสารสามอย่างขึ้นไป">}}
        ```python {style=abap}
        def run():

            # โหลดเอกสารต้นฉบับ
            with groupdocs.comparison.Comparer(source.pdf") as comparer:

                # ระบุไฟล์ที่สองสำหรับการเปรียบเทียบ
                comparer.add("target2.pdf");

                # ระบุไฟล์ที่สามสำหรับการเปรียบเทียบ
                comparer.add("target3.pdf");

                # บันทึกผลการเปรียบเทียบลงในไฟล์ที่ระบุ
                comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---