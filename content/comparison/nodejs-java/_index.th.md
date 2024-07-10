
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: th
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
head_title: "Node.js API เปรียบเทียบเอกสาร | ตัวตรวจสอบความแตกต่าง"
head_description: "API เปรียบเทียบเอกสาร Node.js นำเสนอเครื่องมือที่มีประสิทธิภาพสำหรับการเปรียบเทียบเอกสารผสานเข้ากับ Node.js ได้อย่างราบรื่นสำหรับการติดตามการเปลี่ยนแปลงแบบเรียลไทม์"

############################# Header ############################
title: "เปรียบเทียบเอกสารด้วย Node.js: เน้นความแตกต่างใด ๆ"
description: "ใช้ GroupDocs.Comparison API เพื่อพัฒนาแอปพลิเคชันสคริปต์ Java ดั้งเดิมที่มีคุณสมบัติการเปรียบเทียบที่กำหนดค่าได้สูงเปรียบเทียบไฟล์ เนื้อหา และรูปแบบข้อความระหว่างรูปแบบเอกสารที่คล้ายกัน"
words:
  for: "สำหรับ"

actions:
  main: "ดาวน์โหลด NPM ฟรี"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.comparison"
  alt: "การออกใบอนุญาต"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/nodejs-java/"
  title: "พร้อมที่จะเริ่มแล้วหรือยัง?"
  description: "ลองใช้คุณสมบัติ GroupDocs.Comparison ฟรีหรือขอใบอนุญาต"

release:
  title: "เวอร์ชัน {0} เผยแพร่"
  notes: "ดูว่ามีอะไรใหม่"
  downloads: "ดาวน์โหลด"

code:
  title: "เปรียบเทียบ BMP รูปภาพในสคริปต์ Java"
  more: "ตัวอย่างเพิ่มเติม"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.comparison"
  content: |
    ```javascript {style=abap}

    // ระบุเอกสารต้นทาง
    const comparer = new Comparer("source.bmp");

    // เพิ่มเอกสารเป้าหมายอย่างน้อยหนึ่งฉบับ
    comparer.add("target.bmp");

    // ระบุตัวเลือกการเปรียบเทียบ
    const options = new groupdocs.comparison.CompareOptions();
    options.setGenerateSummaryPage(false);

    // เปรียบเทียบและบันทึกผล
    await comparer.compare("result.bmp", options);
    ```

############################# Overview ############################
overview:
  enable: true
  title: "สรุปภาพ GroupDocs.Comparison"
  description: "API เพื่อเปรียบเทียบเอกสารประเภทต่างๆ เช่น PDF, Microsoft Office, HTML, อีเมล หรือรูปภาพภายในแอปพลิเคชัน Node.js"
  features:
    # feature loop
    - title: "รายงานผลผลิตโดยละเอียด"
      content: "GroupDocs.Comparison ระบุการเปลี่ยนแปลงในเนื้อหาเอกสาร (อักขระคำย่อหน้าตารางแผนภูมิ) รวมถึงการเปลี่ยนแปลงในรูปแบบเอกสารช่วยให้ลูกค้าได้รับรายงานผลลัพธ์ที่มีข้อมูลมากมายเกี่ยวกับความแตกต่าง จำนวน และประเภท"

    # feature loop
    - title: "รองรับรูปแบบไฟล์และเอกสารยอดนิยม"
      content: "ด้วย GroupDocs.Comparison API คุณสามารถเปรียบเทียบเอกสารในรูปแบบที่รองรับได้อย่างมีประสิทธิภาพ เช่น PDF, HTML, อีเมล, เอกสาร Microsoft Office Word, สเปรดชีต Excel, งานนำเสนอ PowerPoint, OneNote, Visio ไดอะแกรม, ข้อความ, JPEG, PNG, GIF และ BMP และรูปแบบอื่น ๆ อีกมากมาย"

    # feature loop
    - title: "เอกสารและตัวอย่าง"
      content: "มีเอกสารมากมายเกี่ยวกับการใช้ไลบรารีเปรียบเทียบบนแพลตฟอร์มต่างๆ พร้อมตัวอย่างโค้ดดังนั้นคุณจึงไม่ต้องคิดอย่างหนักเกี่ยวกับวิธีทำงานกับ GroupDocs.Comparison API ในแอปพลิเคชัน Node.js ของคุณ"

    # feature loop
    - title: "เลือกการเปลี่ยนแปลงและรวมเข้ากับไฟล์เดียว"
      content: "หากคุณมีเอกสารหนึ่งเวอร์ชันที่แตกต่างกัน คุณสามารถเลือกเฉพาะการเปลี่ยนแปลงที่ต้องการและรวบรวมเอกสารใหม่โดยใช้ไลบรารี GroupDocs.Comparison"

############################# Platforms ############################
platforms:
  enable: true
  title: "อิสระของแพลตฟอร์"
  description: "GroupDocs.Comparison for Node.js via Java รองรับระบบปฏิบัติการ เฟรมเวิร์กและผู้จัดการแพ็คเกจต่อไปนี้"
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
    GroupDocs.Comparison for Node.js via Java รองรับการดำเนินการด้วย [รูปแบบไฟล์ ต่อไปนี้](https://docs.groupdocs.com/comparison/nodejs-java/supported-document-formats/)
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
  title: "คุณสมบัติ GroupDocs.Comparison for Node.js via Java"
  description: "เปรียบเทียบ PDF และ เอกสาร รูปภาพ และรูปแบบอื่น ๆ ของ Office ได้อย่างง่ายดาย"

  items:
    # feature loop
    - icon: "compare"
      title: "ง่ายต่อการเปรียบเทียบเอกสาร"
      content: "วิเคราะห์และระบุความแตกต่างภายในสองเอกสาร"

    # feature loop
    - icon: "note-stack"
      title: "เปรียบเทียบเอกสารหลายฉบับ"
      content: "วิเคราะห์และระบุความแตกต่างภายในเอกสารหลายฉบับพร้อมกัน"

    # feature loop
    - icon: "stacks"
      title: "รูปแบบที่รองรับ"
      content: "รองรับรูปแบบเอกสารยอดนิยมมากกว่า 50 รูปแบบจากหมวดหมู่ต่างๆ"

    # feature loop
    - icon: "rule"
      title: "ยอมรับหรือปฏิเสธการเปลี่ยนแปลง"
      content: "การแสดงภาพที่ชัดเจนของการเปลี่ยนแปลงที่ระบุโดยให้ตัวเลือกในการยอมรับหรือปฏิเสธการแก้ไข"

    # feature loop
    - icon: "preview"
      title: "สร้างตัวอย่าง"
      content: "บันทึกผลการเปรียบเทียบเป็นภาพ"

    # feature loop
    - icon: "two-pager"
      title: "การเปรียบเทียบเนื้อหา"
      content: "เปรียบเทียบเนื้อหาข้อความทีละบรรทัดตามย่อหน้าตามคำตามตัวอักษรเน้นการเปลี่ยนแปลง"

    # feature loop
    - icon: "format_color_text"
      title: "การเปรียบเทียบสไตล์"
      content: "ตรวจจับการเปลี่ยนแปลงในการจัดรูปแบบและสไตล์"

    # feature loop
    - icon: "folder-managed"
      title: "ตั้งค่าข้อมูลเมตา"
      content: "เก็บข้อมูลเมตาจากไฟล์ต้นฉบับหรือเป้าหมายหรืออนุญาตให้ผู้ใช้ระบุไว้"

    # feature loop
    - icon: "lock"
      title: "การป้องกันรหัสผ่าน"
      content: "วิเคราะห์เอกสารที่เข้ารหัสหรือรักษาความปลอดภัยเอกสารผลลัพธ์ด้วยรหัสผ่าน"

    # feature loop
    - icon: "select"
      title: "เปรียบเทียบหน้าเฉพาะ"
      content: "โหลดเฉพาะส่วนหรือหน้าเฉพาะของเอกสาร"

    # feature loop
    - icon: "speaker-notes"
      title: "แสดงความคิดเห็น"
      content: "เมื่อโหลดเอกสารต้นฉบับคุณสามารถเลือกว่าจะซ่อนหรือแสดงความคิดเห็น"

############################# Code samples ############################
code_samples:
  enable: true
  title: "ตัวอย่างรหัส"
  description: "บางกรณีการใช้งานของการดำเนินการ GroupDocs.Comparison for Node.js via Java ทั่วไป"
  items:
    # code sample loop
    - title: "เปรียบเทียบเอกสารที่ป้องกันด้วยรหัสผ่าน"
      content: |
        ในการเปรียบเทียบเอกสารที่ [ป้องกันด้วยรหัสผ่าน](https://docs.groupdocs.com/comparison/nodejs-java/load-password-protected-documents/) คุณต้องระบุเอกสารแล้วโหลดเอกสาร:
        {{< landing/code title="วิธีเปรียบเทียบเอกสารที่ป้องกันด้วยรหัสผ่าน">}}
        ```javascript {style=abap}

        import { Comparer, LoadOptions } from '@groupdocs/groupdocs.comparison'

        // โหลดเอกสารต้นฉบับและระบุรหัสผ่าน
        const comparer = new Comparer("source.docx", new LoadOptions("1234"));

        // โหลดเอกสารเป้าหมายและระบุรหัสผ่าน
        comparer.add("target.docx", new LoadOptions("5678"));

        // บันทึกผลการเปรียบเทียบลงในไฟล์ที่ระบุ
        comparer.compare("result.docx");
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "เปรียบเทียบเอกสาร PDF หลายเอกสาร"
      content: |
        GroupDocs.Comparison ช่วยให้คุณสามารถ [เปรียบเทียบเอกสารมากกว่าสองเอกสาร](https://docs.groupdocs.com/comparison/nodejs-java/compare-multiple-documents/)การดำเนินการเกือบจะเหมือนกับเมื่อเปรียบเทียบสองไฟล์คุณเพียงแค่ต้องเพิ่มไฟล์เป้าหมายเพิ่มเติมลงในคลาส `comparer`
        {{< landing/code title="วิธีเปรียบเทียบเอกสารสามอย่างขึ้นไป">}}
        ```javascript {style=abap}
        import { Comparer } from '@groupdocs/groupdocs.comparison'

        // โหลดเอกสารต้นฉบับ
        const comparer = new Comparer(source.pdf");

        // ระบุไฟล์ที่สองสำหรับการเปรียบเทียบ
        comparer.add("target2.pdf");

        // ระบุไฟล์ที่สามสำหรับการเปรียบเทียบ
        comparer.add("target3.pdf");

        // บันทึกผลการเปรียบเทียบลงในไฟล์ที่ระบุ
        comparer.compare("result.pdf");
        ```

        {{< /landing/code >}}

---