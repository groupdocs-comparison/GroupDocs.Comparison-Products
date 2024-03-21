
---
############################# Static ############################
layout: "format"
date:  2024-03-21T15:26:27
draft: false
lang: th
format: Py
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

############################# Head ############################
head_title: "เปรียบเทียบ PY โดยใช้ไลบรารี JavaScript"
head_description: "GroupDocs.Comparison for Node.js via Java นำเสนอซอฟต์แวร์เพื่อสร้างรายงานการตรวจสอบความแตกต่างโดยละเอียดสำหรับแอปพลิเคชัน Node.js"

############################# Header ############################
title: "เปรียบเทียบไฟล์ PY ของคุณใน Node.js" 
description: "ไลบรารีการเปรียบเทียบเอกสารที่อิงจาก Node.js ให้โอกาสในการรวบรวมและแสดงข้อมูลเกี่ยวกับความแตกต่างใด ๆ ในไฟล์ PYเพิ่มประสิทธิภาพการทำงานของโซลูชันของคุณในงานเปรียบเทียบไฟล์ด้วย GroupDocs.Comparison"
subtitle: "โซลูชันสำหรับการเปรียบเทียบไฟล์" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "ดาวน์โหลดฟรี NPM"
      link: "https://releases.groupdocs.com/comparison/nodejs-java/"
      
############################# About ############################
about:
    enable: true
    title: "สำรวจคุณสมบัติของ GroupDocs.Comparison for Node.js via Java"
    link: "/comparison/nodejs-java/"
    link_title: "เรียนรู้เพิ่มเติม"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison for Node.js via Java เป็น API ที่ช่วยในการเปรียบเทียบรูปภาพและเอกสารในรูปแบบเดียวกันสามารถค้นหาความแตกต่างในย่อหน้าคำตัวอักษรรูปร่างและรูปแบบข้อความระหว่างเอกสารที่เปรียบเทียบคุณสามารถรวมการเปลี่ยนแปลงเหล่านี้และบันทึกเป็นเอกสารสุดท้ายใช้งานได้ดีกับ PDF เอกสาร Word แผ่นงาน Excel สไลด์ PowerPoint ไดอะแกรม Visio อีเมล Outlook HTML ภาพวาด และประเภทภาพต่างๆ ทั้งหมดนี้โดยไม่ต้องใช้เครื่องมือเพิ่มเติม

############################# Steps ############################
steps:
    enable: true
    title: "วิธีการเปรียบเทียบไฟล์ PY โดยใช้ Node.js"
    content: |
      เป็นไปได้ที่จะใช้ไฟล์ PY โดยใช้ [GroupDocs.Comparison](https://products.groupdocs.com/comparison/nodejs-java/) เพื่อรับรายงานเกี่ยวกับความแตกต่างในไฟล์ PY จำนวนมาก
      
      1. ติดตั้ง GroupDocs.Comparison for Node.js via Java โดยใช้ [NPM](https://www.npmjs.com/package/@groupdocs/groupdocs.comparison)
      2. สร้างอินสแตนซ์ตัวเปรียบเทียบและให้เส้นทางไปยังไฟล์แรกในรูปแบบ PY
      3. เพิ่มไฟล์ PY อีกไฟล์หนึ่งไปยังตัวเปรียบเทียบ
      4. รับรายงานที่ชัดเจนซึ่งอธิบายความแตกต่างอย่างแม่นยำ
   
    code:
      platform: "net"
      copy_title: "คัดลอก"
      install:
        command: "npm i @groupdocs/groupdocs.comparison"
        copy_tip: "คลิกเพื่อคัดลอก"
        copy_done: "คัดลอก"
      links:
        #  loop
        - title: "ตัวอย่างเพิ่มเติม"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java"
        #  loop
        - title: "เอกสาร"
          link: "https://docs.groupdocs.com/comparison/nodejs-java/"
          
      content: |
        ```javascript {style=abap}

        // ตรวจสอบไฟล์หลายไฟล์เพื่อดูว่าไฟล์มีความคล้ายคลึงกันหรือแตกต่างกันอย่างไร

        // สร้างวัตถุ Comparer และให้ไฟล์แรกเป็นอินพุต
        const comparer = new groupdocs.comparison.Comparer('source.py');

        // เพิ่มไฟล์เพิ่มเติม
        comparer.add('file_v1.py');
        comparer.add('file_2023.py');

        // ดึงรายงานขั้นสุดท้าย
        await comparer.compare('report_new.py');

        console.log('\nFiles are compared.\nCheck result.');

        ```            

############################# Actions ############################

actions:
  enable: true
  title: "พร้อมที่จะเริ่มแล้วหรือยัง?"
  description: "ลองใช้คุณสมบัติ GroupDocs.Comparison ฟรีหรือขอใบอนุญาต"
  items:
    #  loop
    - title: "NPM ดาวน์โหลด"
      link: "https://releases.groupdocs.com/comparison/nodejs-java/"
      color: "red"
        #  loop
    - title: "การออกใบอนุญาต"
      link: "https://purchase.groupdocs.com/pricing/comparison/java/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "เปรียบเทียบประเภทเอกสารยอดนิยมผ่าน JavaScript"
    exclude: "PY"
    description: "API Node.js ของเราช่วยให้คุณสามารถเปรียบเทียบเอกสารในรูปแบบต่างๆติดตามการเปลี่ยนแปลงเอกสารได้อย่างง่ายดายโดยการประมวลผลโดยใช้เครื่องมือของเรา"
    items: 
        # format loop 1
        - name: "เปรียบเทียบไฟล์ PDF"
          format: "PDF"
          link: "/comparison/nodejs-java/pdf/"
          description: "รูปแบบเอกสาร Adobe Portable"

        # format loop 2
        - name: "เปรียบเทียบไฟล์ DOCX"
          format: "DOCX"
          link: "/comparison/nodejs-java/docx/"
          description: "ไมโครซอฟท์ Word เปิดเอกสาร XML"

        # format loop 3
        - name: "เปรียบเทียบไฟล์ RTF"
          format: "RTF"
          link: "/comparison/nodejs-java/rtf/"
          description: "รูปแบบไฟล์ข้อความที่หลากหลาย"

        # format loop 4
        - name: "เปรียบเทียบไฟล์ TXT"
          format: "TXT"
          link: "/comparison/nodejs-java/txt/"
          description: "รูปแบบไฟล์ข้อความธรรมดา"

        # format loop 5
        - name: "เปรียบเทียบไฟล์ XLSX"
          format: "XLSX"
          link: "/comparison/nodejs-java/xlsx/"
          description: "ไมโครซอฟท์ Excel เปิดสเปรดชีต XML"

        # format loop 6
        - name: "เปรียบเทียบไฟล์ CSV"
          format: "CSV"
          link: "/comparison/nodejs-java/csv/"
          description: "ไฟล์ค่าคั่นเครื่องหมายจุลภาค"

        # format loop 7
        - name: "เปรียบเทียบไฟล์ PPTX"
          format: "PPTX"
          link: "/comparison/nodejs-java/pptx/"
          description: "PowerPoint เปิดการนำเสนอ XML"

        # format loop 8
        - name: "เปรียบเทียบไฟล์ ODS"
          format: "ODS"
          link: "/comparison/nodejs-java/ods/"
          description: "Open Document สเปรดชีต"

        # format loop 9
        - name: "เปรียบเทียบไฟล์ ODP"
          format: "ODP"
          link: "/comparison/nodejs-java/odp/"
          description: "OpenDocument รูปแบบไฟล์นำเสนอ"

        # format loop 10
        - name: "เปรียบเทียบไฟล์ ODT"
          format: "ODT"
          link: "/comparison/nodejs-java/odt/"
          description: "Open Document ข้อความ"

        # format loop 11
        - name: "เปรียบเทียบไฟล์ JPEG"
          format: "JPEG"
          link: "/comparison/nodejs-java/jpeg/"
          description: "JPEG รูปภาพ"

        # format loop 12
        - name: "เปรียบเทียบไฟล์ PNG"
          format: "PNG"
          link: "/comparison/nodejs-java/png/"
          description: "Portable กราฟิกเครือข่าย"

        # format loop 13
        - name: "เปรียบเทียบไฟล์ GIF"
          format: "GIF"
          link: "/comparison/nodejs-java/gif/"
          description: "ไฟล์รูปแบบการแลกเปลี่ยนแบบกราฟิก"

        # format loop 14
        - name: "เปรียบเทียบไฟล์ BMP"
          format: "BMP"
          link: "/comparison/nodejs-java/bmp/"
          description: "รูปแบบไฟล์บิตแมป"

        # format loop 15
        - name: "เปรียบเทียบไฟล์ HTML"
          format: "HTML"
          link: "/comparison/nodejs-java/html/"
          description: "ภาษามาร์กอัปข้อความไฮเปอร์"

        # format loop 16
        - name: "เปรียบเทียบไฟล์ MSG"
          format: "MSG"
          link: "/comparison/nodejs-java/msg/"
          description: "ไมโครซอฟท์ Outlook ข้อความอีเมล"

        # format loop 17
        - name: "เปรียบเทียบไฟล์ ONE"
          format: "ONE"
          link: "/comparison/nodejs-java/one/"
          description: "ไมโครซอฟท์ OneNote"

        # format loop 18
        - name: "เปรียบเทียบไฟล์ VSDX"
          format: "VSDX"
          link: "/comparison/nodejs-java/vsdx/"
          description: "ไมโครซอฟท์ Visio การวาดภาพ"

        # format loop 19
        - name: "เปรียบเทียบไฟล์ CS"
          format: "CS"
          link: "/comparison/nodejs-java/cs/"
          description: "ภาษา CSharp"

        # format loop 20
        - name: "เปรียบเทียบไฟล์ Java"
          format: "Java"
          link: "/comparison/nodejs-java/java/"
          description: "Java ภาษา"
          
        # format loop 21
        - name: "เปรียบเทียบไฟล์ CPP"
          format: "CPP"
          link: "/comparison/nodejs-java/cpp/"
          description: "ภาษา C ++"
---