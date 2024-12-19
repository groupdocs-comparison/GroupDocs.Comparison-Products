
---
############################# Static ############################
layout: "format"
date:  2024-12-19T07:49:49
draft: false
lang: th
format: Htm
product: "Comparison"
product_tag: "comparison"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "เปรียบเทียบไฟล์ HTM กับ C# ซอฟต์แวร์เปรียบเทียบ"
head_description: "เปรียบเทียบและผสานไฟล์ HTM ในแอปพลิเคชัน C# .NETดึงข้อมูลสรุปความแตกต่างในเนื้อหาข้อความ และสไตล์"

############################# Header ############################
title: "เปรียบเทียบ HTM ใน C# .NET" 
description: ".NET API เปรียบเทียบเอกสาร เพื่อตรวจสอบความแตกต่างระหว่างไฟล์ HTM สองเวอร์ชัน และส่งออกไปยังเอกสารสุดท้ายพร้อมสรุปโดยละเอียดของความแตกต่างระหว่างเอกสารที่เปรียบเทียบ"
subtitle: "โซลูชันเปรียบเทียบเอกสาร" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "ดาวน์โหลดฟรี Nuget"
      link: "https://releases.groupdocs.com/comparison/net/"
      
############################# About ############################
about:
    enable: true
    title: "ค้นพบข้อดีของ API GroupDocs.Comparison for .NET"
    link: "/comparison/net/"
    link_title: "เรียนรู้เพิ่มเติม"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison for .NET เป็น .NET API ดั้งเดิมที่ออกแบบมาสำหรับการเปรียบเทียบภาพและเอกสารหลายรูปภาพในรูปแบบเดียวกันช่วยในการตรวจจับความแตกต่างภายในย่อหน้าคำตัวอักษรรูปร่างและแม้แต่รูปแบบข้อความของเอกสารที่เปรียบเทียบด้วยความสามารถในการรวมการเปลี่ยนแปลงเหล่านี้และส่งออกไปยังเอกสารสุดท้าย จึงรองรับการเปรียบเทียบและการรวมเอกสาร PDF Word สเปรดชีต Excel งานนำเสนอ PowerPoint ไดอะแกรม Visio อีเมล Outlook HTML ภาพวาด และรูปแบบไฟล์รูปภาพต่างๆ ทั้งหมดนี้โดยไม่จำเป็นต้องใช้ไลบรารีภายนอก

############################# Steps ############################
steps:
    enable: true
    title: "วิธีเปรียบเทียบไฟล์ HTM หลายไฟล์โดยใช้ C#"
    content: |
      เป็นไปได้ที่จะใช้ [GroupDocs.Comparison](https://products.groupdocs.com/comparison/net/) เพื่อรับรายงานเกี่ยวกับความแตกต่างในไฟล์ HTM จำนวนมาก
      
      1. ติดตั้ง GroupDocs.Comparison for .NET จาก [Nuget](https://www.nuget.org/packages/GroupDocs.Comparison) โดยใช้โปรแกรมจัดการแพ็คเกจที่คุณชื่นชอบ
      2. จัดเตรียมอินสแตนซ์ของคลาส Comparer ที่มีเส้นทางเต็มไปยังไฟล์ HTM เริ่มต้น
      3. ใส่ HTM อื่นอย่างน้อยหนึ่งตัวลงใน Comparer
      4. รับรายงานขั้นสุดท้ายพร้อมความแตกต่างที่อธิบายอย่างแม่นยำ
   
    code:
      platform: "net"
      copy_title: "คัดลอก"
      result_enable: true
      result_link: "/examples/comparison/comparison_result.pdf"
      result_title: "ตัวอย่างไฟล์ผลลัพธ์"
      install:
        command: "dotnet add package GroupDocs.Comparison"
        copy_tip: "คลิกเพื่อคัดลอก"
        copy_done: "คัดลอก"
      links:
        #  loop
        - title: "ตัวอย่างเพิ่มเติม"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET"
        #  loop
        - title: "เอกสาร"
          link: "https://docs.groupdocs.com/comparison/net/"
          
      content: |
        ```csharp {style=abap}

        // เปรียบเทียบเอกสารหลายเอกสารจากดิสก์ท้องถิ่น

        // Instantiate Comparer ให้ไฟล์แรก
        using (Comparer comparer = new Comparer("main_document.htm"))
        {
            // เพิ่มไฟล์อื่น ๆ
        	comparer.Add("modified_1.htm");
            comparer.Add("modified_2.htm");

            // รับไฟล์ผลลัพธ์ที่มีชื่อที่ระบุ
            comparer.Compare("report.htm"); 
        }
        
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "พร้อมที่จะเริ่มแล้วหรือยัง?"
  description: "ลองใช้คุณสมบัติ GroupDocs.Comparison ฟรีหรือขอใบอนุญาต"
  items:
    #  loop
    - title: "Nuget ดาวน์โหลด"
      link: "https://releases.groupdocs.com/comparison/net/"
      color: "red"
        #  loop
    - title: "การออกใบอนุญาต"
      link: "https://purchase.groupdocs.com/pricing/comparison/net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "เปรียบเทียบรูปแบบไฟล์ยอดนิยมโดยใช้ C#"
    exclude: "HTM"
    description: ".NET API สำหรับการเปรียบเทียบรูปแบบเอกสารรับทราบข้อมูลอย่างดีเกี่ยวกับการเปลี่ยนแปลงในการประมวลผลเอกสารของคุณโดยไม่ต้องใช้ความพยายามเป็นพิเศษ"
    items: 
        # format loop 1
        - name: "เปรียบเทียบไฟล์ PDF"
          format: "PDF"
          link: "/comparison/net/pdf/"
          description: "รูปแบบเอกสาร Adobe Portable"

        # format loop 2
        - name: "เปรียบเทียบไฟล์ DOCX"
          format: "DOCX"
          link: "/comparison/net/docx/"
          description: "ไมโครซอฟท์ Word เปิดเอกสาร XML"

        # format loop 3
        - name: "เปรียบเทียบไฟล์ RTF"
          format: "RTF"
          link: "/comparison/net/rtf/"
          description: "รูปแบบไฟล์ข้อความที่หลากหลาย"

        # format loop 4
        - name: "เปรียบเทียบไฟล์ TXT"
          format: "TXT"
          link: "/comparison/net/txt/"
          description: "รูปแบบไฟล์ข้อความธรรมดา"

        # format loop 5
        - name: "เปรียบเทียบไฟล์ XLSX"
          format: "XLSX"
          link: "/comparison/net/xlsx/"
          description: "ไมโครซอฟท์ Excel เปิดสเปรดชีต XML"

        # format loop 6
        - name: "เปรียบเทียบไฟล์ CSV"
          format: "CSV"
          link: "/comparison/net/csv/"
          description: "ไฟล์ค่าคั่นเครื่องหมายจุลภาค"

        # format loop 7
        - name: "เปรียบเทียบไฟล์ PPTX"
          format: "PPTX"
          link: "/comparison/net/pptx/"
          description: "PowerPoint เปิดการนำเสนอ XML"

        # format loop 8
        - name: "เปรียบเทียบไฟล์ ODS"
          format: "ODS"
          link: "/comparison/net/ods/"
          description: "Open Document สเปรดชีต"

        # format loop 9
        - name: "เปรียบเทียบไฟล์ ODP"
          format: "ODP"
          link: "/comparison/net/odp/"
          description: "OpenDocument รูปแบบไฟล์นำเสนอ"

        # format loop 10
        - name: "เปรียบเทียบไฟล์ ODT"
          format: "ODT"
          link: "/comparison/net/odt/"
          description: "Open Document ข้อความ"

        # format loop 11
        - name: "เปรียบเทียบไฟล์ JPEG"
          format: "JPEG"
          link: "/comparison/net/jpeg/"
          description: "JPEG รูปภาพ"

        # format loop 12
        - name: "เปรียบเทียบไฟล์ PNG"
          format: "PNG"
          link: "/comparison/net/png/"
          description: "Portable กราฟิกเครือข่าย"

        # format loop 13
        - name: "เปรียบเทียบไฟล์ GIF"
          format: "GIF"
          link: "/comparison/net/gif/"
          description: "ไฟล์รูปแบบการแลกเปลี่ยนแบบกราฟิก"

        # format loop 14
        - name: "เปรียบเทียบไฟล์ BMP"
          format: "BMP"
          link: "/comparison/net/bmp/"
          description: "รูปแบบไฟล์บิตแมป"

        # format loop 15
        - name: "เปรียบเทียบไฟล์ HTML"
          format: "HTML"
          link: "/comparison/net/html/"
          description: "ภาษามาร์กอัปข้อความไฮเปอร์"

        # format loop 16
        - name: "เปรียบเทียบไฟล์ MSG"
          format: "MSG"
          link: "/comparison/net/msg/"
          description: "ไมโครซอฟท์ Outlook ข้อความอีเมล"

        # format loop 17
        - name: "เปรียบเทียบไฟล์ ONE"
          format: "ONE"
          link: "/comparison/net/one/"
          description: "ไมโครซอฟท์ OneNote"

        # format loop 18
        - name: "เปรียบเทียบไฟล์ VSDX"
          format: "VSDX"
          link: "/comparison/net/vsdx/"
          description: "ไมโครซอฟท์ Visio การวาดภาพ"

        # format loop 19
        - name: "เปรียบเทียบไฟล์ CS"
          format: "CS"
          link: "/comparison/net/cs/"
          description: "ภาษา CSharp"

        # format loop 20
        - name: "เปรียบเทียบไฟล์ Java"
          format: "Java"
          link: "/comparison/net/java/"
          description: "Java ภาษา"
          
        # format loop 21
        - name: "เปรียบเทียบไฟล์ CPP"
          format: "CPP"
          link: "/comparison/net/cpp/"
          description: "ภาษา C ++"
---