
---
############################# Static ############################
layout: "landing"
date: 2024-07-10T18:47:13
draft: false

lang: th
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
head_title: "C# .NET ซอฟต์แวร์เปรียบเทียบเอกสาร | ตัวตรวจสอบความแตกต่าง"
head_description: "C# .NET ซอฟต์แวร์สำหรับเปรียบเทียบรูปแบบและเนื้อหาเอกสารเปรียบเทียบเอกสารในรูปแบบที่รองรับหลายรูปแบบเพื่อระบุการเปลี่ยนแปลงระหว่างไฟล์"

############################# Header ############################
title: "เปรียบเทียบเอกสารได้อย่างง่ายดายในโซลูชัน C# .NET ของคุณ"
description: "สร้างแอปพลิเคชัน C# ด้วย API เปรียบเทียบเอกสารที่ยืดหยุ่นซึ่งช่วยให้สามารถเปรียบเทียบไฟล์ตามเนื้อหาและสไตล์ในรูปแบบเอกสารต่างๆ"
words:
  for: "สำหรับ"

actions:
  main: "ดาวน์โหลดฟรี NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Comparison"
  alt: "การออกใบอนุญาต"
  alt_link: "https://purchase.groupdocs.com/pricing/comparison/net/"
  title: "พร้อมที่จะเริ่มแล้วหรือยัง?"
  description: "ลองใช้คุณสมบัติ GroupDocs.Comparison ฟรีหรือขอใบอนุญาต"

release:
  title: "เวอร์ชัน {0} เผยแพร่"
  notes: "ดูว่ามีอะไรใหม่"
  downloads: "ดาวน์โหลด"

code:
  title: "เปรียบเทียบไฟล์ DOCX ใน C#"
  more: "ตัวอย่างเพิ่มเติม"
  more_link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET"
  install: "dotnet add package GroupDocs.Comparison"
  content: |
    ```csharp {style=abap}   
    // ระบุเอกสารต้นทาง
    using (Comparer comparer = new Comparer("source.docx"))
    {
        // เพิ่มเอกสารเป้าหมายอย่างน้อยหนึ่งฉบับ
        comparer.Add("target.docx");

        // ระบุตัวเลือกการเปรียบเทียบ
        CompareOptions options = new CompareOptions() 
        {ShowRevisions = false};

        // เปรียบเทียบและบันทึกผล
        comparer.Compare("result.docx", options);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "สรุปภาพ GroupDocs.Comparison"
  description: "API เพื่อเปรียบเทียบความแตกต่างระหว่างเอกสารในแอปพลิเคชัน .NET"
  features:
    # feature loop
    - title: "การเปรียบเทียบไฟล์ใน C#"
      content: "ตรวจจับความแตกต่างระหว่างไฟล์ต้นฉบับและไฟล์เป้าหมายสำหรับการเปลี่ยนแปลงในย่อหน้า คำ และระดับอักขระระบุการเปลี่ยนแปลงสไตล์และการจัดรูปแบบ เช่น ตัวหนา เอียง ขีดเส้นใต้ แบบตัวอักษร ฯลฯ"

    # feature loop
    - title: "รองรับรูปแบบไฟล์และเอกสารยอดนิยม"
      content: "GroupDocs.Comparison API ช่วยให้สามารถเปรียบเทียบเอกสารได้อย่างมีประสิทธิภาพในรูปแบบที่หลากหลาย รวมถึง PDF, HTML, อีเมล, เอกสาร Microsoft Office (Word, Excel, PowerPoint, OneNote, Visio) ประเภทภาพต่างๆ (JPEG, PNG, GIF, BMP) ไฟล์ข้อความ และอื่นๆ"

    # feature loop
    - title: "ใช้หรือปฏิเสธการเปลี่ยนแปลงได้อย่างง่ายดาย"
      content: "แต่ละความแตกต่างที่ระบุในเอกสารเปรียบเทียบโดยใช้ API GroupDocs.Comparison สามารถเลือกหรือปฏิเสธได้ ทำให้สามารถปรับแต่งก่อนส่งออกไปยังเอกสารเอาต์พุตสุดท้าย"

    # feature loop
    - title: "รายงานสรุปเปรียบเทียบ"
      content: "สร้างรายงานสรุปของความแตกต่าง โดยระบุรายละเอียดการเปลี่ยนแปลงทั้งหมดที่พบในเอกสารเปรียบเทียบและบันทึกไว้เพื่ออ้างอิง"

############################# Platforms ############################
platforms:
  enable: true
  title: "อิสระของแพลตฟอร์"
  description: "GroupDocs.Comparison for .NET รองรับระบบปฏิบัติการ เฟรมเวิร์กและผู้จัดการแพ็คเกจต่อไปนี้"
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
  title: "รูปแบบไฟล์ที่รองรับ"
  description: |
    GroupDocs.Comparison for .NET รองรับการดำเนินการด้วย [รูปแบบไฟล์ ต่อไปนี้](https://docs.groupdocs.com/comparison/net/supported-document-formats/)
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
      content: "วิเคราะห์และระบุความแตกต่างระหว่างสองเอกสาร"

    # feature loop
    - icon: "note-stack"
      title: "เปรียบเทียบเอกสารหลายฉบับ"
      content: "วิเคราะห์และระบุความแตกต่างในเอกสารหลายฉบับพร้อมกัน"

    # feature loop
    - icon: "stacks"
      title: "รูปแบบที่รองรับ"
      content: "เข้ากันได้กับรูปแบบเอกสารที่ใช้กันอย่างแพร่หลายกว่า 50 รูปแบบจากหมวดหมู่ต่างๆ ทำให้มั่นใจได้ถึงการใช้งานที่กว้างขวาง"

    # feature loop
    - icon: "rule"
      title: "ยอมรับหรือปฏิเสธการเปลี่ยนแปลง"
      content: "แสดงผลภาพของการเปลี่ยนแปลงที่ตรวจพบพร้อมตัวเลือกที่จะยอมรับหรือปฏิเสธการแก้ไขเหล่านี้"

    # feature loop
    - icon: "preview"
      title: "สร้างตัวอย่าง"
      content: "ความสามารถในการบันทึกผลการเปรียบเทียบเป็นตัวอย่างภาพเพื่อการอ้างอิงและการแบ่งปันได้ง่าย"

    # feature loop
    - icon: "two-pager"
      title: "การเปรียบเทียบเนื้อหา"
      content: "ทำการเปรียบเทียบข้อความอย่างละเอียดในระดับต่างๆ รวมถึงบรรทัดต่อบรรทัดย่อหน้าคำและตัวอักษร โดยมีการเน้นความแตกต่างเพื่อความชัดเจนที่ดีขึ้น"

    # feature loop
    - icon: "format_color_text"
      title: "การเปรียบเทียบสไตล์และการจัดรูปแบบ"
      content: "ตรวจจับและเน้นการเปลี่ยนแปลงในการจัดรูปแบบเอกสารและรูปแบบเพื่อให้มั่นใจได้ว่ามีการตรวจสอบอย่างครอบคลุม"

    # feature loop
    - icon: "folder-managed"
      title: "การตั้งค่าเมตาที่ยืดหยุ่น"
      content: "เก็บข้อมูลเมตาจากไฟล์ต้นฉบับหรือเป้าหมายหรือปรับแต่งตามความต้องการของผู้ใช้"

    # feature loop
    - icon: "lock"
      title: "การป้องกันรหัสผ่าน"
      content: "วิเคราะห์เอกสารที่ป้องกันด้วยรหัสผ่านและรักษาความปลอดภัยเอกสารเอาต์พุตด้วยการเข้ารหัสรหัสผ่านเพื่อเพิ่มความปลอดภัย"

    # feature loop
    - icon: "select"
      title: "การเปรียบเทียบหน้าที่เลือก"
      content: "โหลดและเปรียบเทียบส่วนหรือหน้าเฉพาะของเอกสารเพื่อการวิเคราะห์เป้าหมาย"

    # feature loop
    - icon: "speaker-notes"
      title: "แสดงความคิดเห็น"
      content: "เลือกที่จะแสดงหรือซ่อนความคิดเห็นเมื่อโหลดเอกสารต้นฉบับ ซึ่งให้การควบคุมกระบวนการเปรียบเทียบได้มากขึ้น"

############################# Code samples ############################
code_samples:
  enable: true
  title: "ตัวอย่างรหัส"
  description: "บางกรณีการใช้งานของการดำเนินการ GroupDocs.Comparison for .NET ทั่วไป"
  items:
    # code sample loop
    - title: "เปรียบเทียบเอกสารที่ป้องกันด้วยรหัสผ่าน"
      content: |
        ในการเปรียบเทียบเอกสารที่ [ป้องกันด้วยรหัสผ่าน](https://docs.groupdocs.com/comparison/net/load-password-protected-documents/) คุณต้องระบุเอกสารแล้วโหลดเอกสาร:
        {{< landing/code title="วิธีเปรียบเทียบเอกสารที่ป้องกันด้วยรหัสผ่าน">}}
        ```csharp {style=abap}
        // โหลดเอกสารต้นฉบับและระบุรหัสผ่าน
        using(Comparer comparer = new Comparer("source.docx", new LoadOptions() {Password = "1234"}))  
        {
            // โหลดเอกสารเป้าหมายและระบุรหัสผ่าน
            comparer.Add("target.docx", new LoadOptions() {Password = "5678"});

            // บันทึกผลการเปรียบเทียบลงในไฟล์ที่ระบุ
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "เปรียบเทียบเอกสาร PDF หลายเอกสาร"
      content: |
        GroupDocs.Comparison ช่วยให้คุณสามารถ [เปรียบเทียบเอกสารมากกว่าสองเอกสาร](https://docs.groupdocs.com/comparison/net/compare-multiple-documents/)การดำเนินการเกือบจะเหมือนกับเมื่อเปรียบเทียบสองไฟล์คุณเพียงแค่ต้องเพิ่มไฟล์เป้าหมายเพิ่มเติมลงในคลาส `comparer`
        {{< landing/code title="วิธีเปรียบเทียบเอกสารสามอย่างขึ้นไป">}}
        ```csharp {style=abap}   
        // โหลดเอกสารต้นฉบับ
        using(Comparer comparer = new Comparer("source.docx") 
        {
            // ระบุไฟล์ที่สองสำหรับการเปรียบเทียบ
            comparer.Add("target2.docx");
            
            // ระบุไฟล์ที่สามสำหรับการเปรียบเทียบ
            comparer.Add("target3.docx");
            
            // บันทึกผลการเปรียบเทียบลงในไฟล์ที่ระบุ
            comparer.Compare("result.docx");
        }
        ```
        {{< /landing/code >}}

---
