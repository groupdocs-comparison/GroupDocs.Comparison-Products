
---
############################# Static ############################
layout: "landing"
date: 2024-11-19T07:50:40
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
head_title: "Python เครื่องมือเปรียบเทียบเอกสาร | การวิเคราะห์เอกสาร"
head_description: "ค้นพบประสิทธิภาพของเครื่องมือเปรียบเทียบเอกสาร Python เพื่อการวิเคราะห์เอกสารอย่างละเอียด ผสานรวมกับ Python ได้อย่างง่ายดายเพื่อการติดตามการแก้ไขที่ครอบคลุม"

############################# Header ############################
title: "เปรียบเทียบเอกสารกับ Python: เน้นความแตกต่างใดๆ"
description: "ใช้ API ของ GroupDocs.Comparison เพื่อสร้างแอปพลิเคชันเนทิฟใน Python พร้อมฟังก์ชันการเปรียบเทียบที่ปรับแต่งได้ ตรวจสอบไฟล์ เนื้อหา และรูปแบบการจัดรูปแบบต่างๆ ของรูปแบบเอกสาร"
words:
  for: "สำหรับ"

actions:
  main: "ดาวน์โหลด PyPi ฟรีตอนนี้"
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
  title: "เปรียบเทียบภาพ BMP โดยใช้ Python"
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
  description: "API ที่ออกแบบมาเพื่อการเปรียบเทียบประเภทเอกสารที่ใช้กันอย่างแพร่หลาย เช่น PDF, ไฟล์ Microsoft Office, HTML, อีเมล หรือรูปภาพภายในแอปพลิเคชัน Python"
  features:
    # feature loop
    - title: "รายงานผลลัพธ์ที่ครอบคลุม"
      content: "GroupDocs.Comparison ตรวจจับการเปลี่ยนแปลงในเนื้อหาเอกสาร (อักขระ คำ ย่อหน้า ตาราง แผนภูมิ) รวมถึงการเปลี่ยนแปลงรูปแบบของเอกสาร ผู้ใช้จะได้รับรายงานโดยละเอียดที่เน้นลักษณะและจำนวนการเปลี่ยนแปลง"

    # feature loop
    - title: "รูปแบบไฟล์และเอกสารที่หลากหลาย"
      content: "GroupDocs.Comparison API ช่วยให้คุณสามารถเปรียบเทียบเอกสารในรูปแบบต่างๆ เช่น PDF, HTML, อีเมล, Microsoft Office Word, สมุดงาน Excel, ไฟล์ PowerPoint, บันทึกย่อ OneNote, ไดอะแกรม Visio, เอกสารข้อความ, JPEG, PNG, GIF, รูปภาพ BMP, ท่ามกลางคนอื่น ๆ อีกมากมาย"

    # feature loop
    - title: "เอกสารประกอบและตัวอย่างโค้ดอย่างละเอียด"
      content: "เอกสารเชิงลึกและโค้ดตัวอย่างสำหรับไลบรารีการเปรียบเทียบบนแพลตฟอร์มต่างๆ พร้อมใช้งานแล้ว ซึ่งทำให้การรวม GroupDocs.Comparison API เข้ากับแอปพลิเคชัน Python ของคุณง่ายขึ้น"

    # feature loop
    - title: "เลือกและรวมการเปลี่ยนแปลงเป็นเอกสารเดียว"
      content: "หากคุณมีเอกสารหลายเวอร์ชัน คุณสามารถเลือกรวบรวมการเปลี่ยนแปลงเป็นไฟล์ใหม่ไฟล์เดียวได้โดยใช้ไลบรารี GroupDocs.Comparison"

############################# Platforms ############################
platforms:
  enable: true
  title: "อิสระของแพลตฟอร์"
  description: "GroupDocs.Comparison for Python via .NET เข้ากันได้กับระบบปฏิบัติการ เฟรมเวิร์ก และตัวจัดการแพ็คเกจต่อไปนี้"
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
    GroupDocs.Comparison for Python via .NET สามารถดำเนินการกับ [รูปแบบไฟล์](https://docs.groupdocs.com/comparison/net/supported-document-formats/ ต่อไปนี้)
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
  title: "ความสามารถของ GroupDocs.Comparison for Python via .NET"
  description: "เปรียบเทียบ PDF, เอกสาร Office, รูปภาพ และรูปแบบอื่นๆ ที่หลากหลายได้อย่างราบรื่น"

  items:
    # feature loop
    - icon: "compare"
      title: "การเปรียบเทียบเอกสารที่ใช้งานง่าย"
      content: "ตรวจสอบและเน้นความแตกต่างระหว่างเอกสารสองฉบับ"

    # feature loop
    - icon: "note-stack"
      title: "การเปรียบเทียบเอกสารหลายชุด"
      content: "ตรวจสอบเอกสารหลายฉบับเพื่อดูความแตกต่างในเวลาเดียวกัน"

    # feature loop
    - icon: "stacks"
      title: "การสนับสนุนรูปแบบที่กว้างขวาง"
      content: "เข้ากันได้กับรูปแบบเอกสารที่ใช้กันทั่วไปมากกว่า 50 รูปแบบในหมวดหมู่ต่างๆ"

    # feature loop
    - icon: "rule"
      title: "ยอมรับหรือปฏิเสธการเปลี่ยนแปลง"
      content: "แสดงภาพการเปลี่ยนแปลงอย่างชัดเจน เสนอตัวเลือกสำหรับการยอมรับหรือปฏิเสธการแก้ไข"

    # feature loop
    - icon: "preview"
      title: "สร้างการแสดงตัวอย่างภาพ"
      content: "สร้างการแสดงตัวอย่างผลลัพธ์การเปรียบเทียบในรูปแบบภาพ"

    # feature loop
    - icon: "two-pager"
      title: "การเปรียบเทียบเนื้อหาแบบข้อความ"
      content: "เปรียบเทียบทีละบรรทัด ย่อหน้า คำ หรืออักขระเพื่อเน้นการเปลี่ยนแปลง"

    # feature loop
    - icon: "format_color_text"
      title: "การตรวจจับการเปลี่ยนแปลงการจัดรูปแบบ"
      content: "ระบุการเปลี่ยนแปลงในลักษณะและการจัดรูปแบบของเอกสาร"

    # feature loop
    - icon: "folder-managed"
      title: "การจัดการข้อมูลเมตาที่ปรับแต่งได้"
      content: "เก็บข้อมูลเมตาจากไฟล์ต้นฉบับหรือเป้าหมาย หรืออนุญาตให้ผู้ใช้กำหนดข้อมูลเมตาใหม่"

    # feature loop
    - icon: "lock"
      title: "จัดการไฟล์ที่ป้องกันด้วยรหัสผ่าน"
      content: "ทำงานกับเอกสารที่เข้ารหัสหรือสร้างเอกสารที่ปลอดภัยที่ป้องกันด้วยรหัสผ่าน"

    # feature loop
    - icon: "select"
      title: "การเปรียบเทียบหน้าที่เน้น"
      content: "เลือกและเปรียบเทียบส่วนใดส่วนหนึ่งหรือแต่ละหน้าของเอกสาร"

    # feature loop
    - icon: "speaker-notes"
      title: "จัดการการมองเห็นความคิดเห็น"
      content: "ตัดสินใจเปิดเผยหรือปกปิดความคิดเห็นเมื่อตรวจสอบเอกสารต้นฉบับ"

############################# Code samples ############################
code_samples:
  enable: true
  title: "ตัวอย่างรหัส"
  description: "ค้นพบสถานการณ์ทั่วไปในการใช้ฟังก์ชัน GroupDocs.Comparison for Python via .NET"
  items:
    # code sample loop
    - title: "การเปรียบเทียบเอกสารกับการป้องกันด้วยรหัสผ่าน"
      content: |
        หากต้องการเปรียบเทียบเอกสารที่ [ปลอดภัยด้วยรหัสผ่าน](https://docs.groupdocs.com/comparison/python-net/load-password-protected-documents/) คุณต้องระบุรหัสผ่านเมื่อโหลดเอกสาร:
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