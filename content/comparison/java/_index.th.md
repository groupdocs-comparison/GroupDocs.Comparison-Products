
---
############################# Static ############################
layout: "landing"
date: 2024-03-21T15:26:29
draft: false

lang: th
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
head_title: "Java ห้องสมุดเปรียบเทียบเอกสาร| ตัวตรวจสอบความแตกต่าง"
head_description: "ซอฟต์แวร์เนทีฟ Java เพื่อเปรียบเทียบรูปแบบเอกสารและเนื้อหาเปรียบเทียบเอกสารหลายรูปแบบเพื่อระบุความแตกต่าง"

############################# Header ############################
title: "เปรียบเทียบและตรวจสอบความแตกต่างของไฟล์โดยใช้ Java API"
description: "พัฒนาแอปพลิเคชัน Java ด้วยไลบรารีการเปรียบเทียบเอกสารที่กำหนดค่าได้สูงเพื่อเปรียบเทียบรูปแบบเอกสารที่คล้ายคลึงกัน รวมถึงไฟล์ เนื้อหา และรูปแบบข้อความ"
words:
  for: "สำหรับ"

actions:
  main: "ดาวน์โหลด Maven ฟรี"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/"
  alt: "การออกใบอนุญาต"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/java/"
  title: "พร้อมที่จะเริ่มแล้วหรือยัง?"
  description: "ลองใช้คุณสมบัติ GroupDocs.Comparison ฟรีหรือขอใบอนุญาต"

release:
  title: "เวอร์ชัน {0} เผยแพร่"
  notes: "ดูว่ามีอะไรใหม่"
  downloads: "ดาวน์โหลด"

code:
  title: "เปรียบเทียบไฟล์ DOCX ใน Java"
  more: "ตัวอย่างเพิ่มเติม"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
  install: |
    <dependency>
      <groupId>com.groupdocs</groupId>
      <artifactId>groupdocs-comparison</artifactId>
      <version>{0}</version>
    </dependency>
  content: |
    ```java {style=abap}  
    // ระบุเอกสารต้นทาง
    try (Comparer comparer = new Comparer("source.docx"))
    {    
      // เพิ่มเอกสารเป้าหมายอย่างน้อยหนึ่งฉบับ
      comparer.add("target.docx");

      // ระบุตัวเลือกการเปรียบเทียบ
      CompareOptions options = new CompareOptions();
      options.setShowRevisions(false);

      // ทำการเปรียบเทียบและบันทึกเอกสารผลลัพธ์
      final comparer.compare("result.docx", options);
    }    
    ```

############################# Overview ############################
overview:
  enable: true
  title: "สรุปภาพ GroupDocs.Comparison"
  description: "API เพื่อเปรียบเทียบความแตกต่างระหว่างเอกสารในแอปพลิเคชัน Java"
  features:
    # feature loop
    - title: "การเปรียบเทียบไฟล์ใน Java"
      content: "ตรวจจับการเปลี่ยนแปลงระหว่างไฟล์ต้นฉบับและไฟล์เป้าหมายที่ระดับย่อหน้า คำ และอักขระระบุการเปลี่ยนแปลงสไตล์และการจัดรูปแบบ เช่น ตัวหนา ตัวเอียง ขีดเส้นขีดขวาง ประเภทตัวอักษร และอื่นๆ"

    # feature loop
    - title: "รูปแบบที่รองรับจำนวนมาก"
      content: "ด้วย GroupDocs.Comparison API คุณสามารถเปรียบเทียบเอกสารในรูปแบบที่รองรับหลายรูปแบบได้อย่างง่ายดายซึ่งรวมถึง PDF, HTML, อีเมล, เอกสาร Microsoft Office Word, สเปรดชีต, Excel, งานนำเสนอ PowerPoint, OneNote, Visio ไดอะแกรม, ข้อความ, JPEG, PNG, GIF และ BMP รูปภาพ รวมถึงรูปแบบอื่น ๆ อีกมากมาย"

    # feature loop
    - title: "ใช้หรือปฏิเสธการเปลี่ยนแปลงได้อย่างง่ายดาย"
      content: "ทุกความแตกต่างระหว่างเอกสารที่เปรียบเทียบสามารถนำไปใช้หรือปฏิเสธแล้วส่งออกไปยังเอกสารเอาต์พุต"

    # feature loop
    - title: "รายงานสรุปเปรียบเทียบ"
      content: "สร้างรายงานสรุปที่แสดงรายการการเปลี่ยนแปลงทั้งหมดในเอกสารที่เปรียบเทียบ"

############################# Platforms ############################
platforms:
  enable: true
  title: "อิสระของแพลตฟอร์"
  description: "GroupDocs.Comparison for Java รองรับระบบปฏิบัติการ เฟรมเวิร์กและผู้จัดการแพ็คเกจต่อไปนี้"
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
  title: "รูปแบบไฟล์ที่รองรับ"
  description: |
    GroupDocs.Comparison for Java รองรับการดำเนินการด้วย [รูปแบบไฟล์] ต่อไปนี้ (https://docs.groupdocs.com/comparison/java/supported-document-formats/)
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
  title: "คุณสมบัติ GroupDocs.Comparison"
  description: "เปรียบเทียบ PDF และ เอกสาร รูปภาพ และรูปแบบอื่น ๆ ของ Office ได้อย่างง่ายดาย"

  items:
    # feature loop
    - icon: "compare"
      title: "ง่ายต่อการเปรียบเทียบเอกสาร"
      content: "วิเคราะห์และระบุความแตกต่างระหว่างเอกสารสองฉบับได้อย่างง่ายดาย"

    # feature loop
    - icon: "note-stack"
      title: "เปรียบเทียบเอกสารหลายฉบับ"
      content: "ตรวจสอบและเน้นความแตกต่างในเอกสารหลายฉบับพร้อมกัน"

    # feature loop
    - icon: "stacks"
      title: "รูปแบบที่รองรับ"
      content: "เข้ากันได้กับรูปแบบเอกสารที่ใช้กันอย่างแพร่หลายกว่า 50 รูปแบบจากหมวดหมู่ที่หลากหลาย"

    # feature loop
    - icon: "rule"
      title: "ยอมรับหรือปฏิเสธการเปลี่ยนแปลง"
      content: "การแสดงภาพการเปลี่ยนแปลงที่ระบุไว้อย่างชัดเจนพร้อมตัวเลือกในการยอมรับหรือปฏิเสธการแก้ไข"

    # feature loop
    - icon: "preview"
      title: "สร้างตัวอย่าง"
      content: "ความสามารถในการบันทึกผลการเปรียบเทียบเป็นตัวอย่างภาพ"

    # feature loop
    - icon: "two-pager"
      title: "การเปรียบเทียบเนื้อหา"
      content: "การเปรียบเทียบเนื้อหาข้อความอย่างละเอียดในระดับต่างๆ รวมถึงการวิเคราะห์บรรทัดต่อบรรทัดย่อหน้าคำและอักขระโดยเน้นการเปลี่ยนแปลง"

    # feature loop
    - icon: "format_color_text"
      title: "การเปรียบเทียบสไตล์"
      content: "ความสามารถในการตรวจจับและเน้นการเปลี่ยนแปลงในองค์ประกอบการจัดรูปแบบและสไตล์"

    # feature loop
    - icon: "folder-managed"
      title: "ตั้งค่าข้อมูลเมตา"
      content: "ตัวเลือกในการเก็บข้อมูลเมตาจากไฟล์ต้นฉบับหรือไฟล์เป้าหมาย หรืออนุญาตการตั้งค่าข้อมูลเมตาที่ผู้ใช้กำหนด"

    # feature loop
    - icon: "lock"
      title: "การป้องกันรหัสผ่าน"
      content: "อำนวยความสะดวกในการวิเคราะห์เอกสารที่ป้องกันด้วยรหัสผ่านและเปิดใช้งานการป้องกันด้วยรหัสผ่านสำหรับเอกสารที่ได้รับ"

    # feature loop
    - icon: "select"
      title: "เปรียบเทียบหน้าเฉพาะ"
      content: "โหลดและเปรียบเทียบส่วนหรือหน้าเฉพาะของเอกสารตามความจำเป็น"

    # feature loop
    - icon: "speaker-notes"
      title: "แสดงความคิดเห็น"
      content: "ความยืดหยุ่นในการแสดงหรือซ่อนความคิดเห็นเมื่อโหลดเอกสารต้นทาง"

############################# Code samples ############################
code_samples:
  enable: true
  title: "ตัวอย่างรหัส"
  description: "บางกรณีการใช้งานของการดำเนินการ GroupDocs.Comparison for Java ทั่วไป"
  items:
    # code sample loop
    - title: "เปรียบเทียบเอกสารที่ป้องกันด้วยรหัสผ่าน"
      content: |
        ในการเปรียบเทียบเอกสารที่ [ป้องกันด้วยรหัสผ่าน](https://docs.groupdocs.com/comparison/java/load-password-protected-documents/) คุณต้องระบุเอกสารแล้วโหลดเอกสาร:
        {{< landing/code title="วิธีเปรียบเทียบเอกสารที่ป้องกันด้วยรหัสผ่าน">}}
        ```java {style=abap}
        // โหลดเอกสารต้นฉบับและระบุรหัสผ่าน
        try (Comparer comparer = new Comparer("source.docx", new LoadOptions("1234")))
        {
            // โหลดเอกสารเป้าหมายและระบุรหัสผ่าน
            comparer.add("target.docx", new LoadOptions("5678"));
        
            // บันทึกผลการเปรียบเทียบลงในไฟล์ที่ระบุ
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "เปรียบเทียบเอกสาร PDF หลายเอกสาร"
      content: |
        GroupDocs.Comparison ช่วยให้คุณสามารถ [เปรียบเทียบเอกสารมากกว่าสองเอกสาร](https://docs.groupdocs.com/comparison/java/compare-multiple-documents/)การดำเนินการเกือบจะเหมือนกับเมื่อเปรียบเทียบสองไฟล์คุณเพียงแค่ต้องเพิ่มไฟล์เป้าหมายเพิ่มเติมลงในคลาส `comparer`
        {{< landing/code title="วิธีเปรียบเทียบเอกสารสามอย่างขึ้นไป">}}
        ```java {style=abap}   
        // โหลดเอกสารต้นฉบับ
        try (Comparer comparer = new Comparer("source.docx") 
        {
            // ระบุไฟล์ที่สองสำหรับการเปรียบเทียบ
            comparer.add("target2.docx");

            // ระบุไฟล์ที่สามสำหรับการเปรียบเทียบ
            comparer.add("target3.docx");

            // บันทึกผลการเปรียบเทียบลงในไฟล์ที่ระบุ
            comparer.compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---

