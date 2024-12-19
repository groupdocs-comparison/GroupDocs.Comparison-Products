
---
############################# Static ############################
layout: "format"
date:  2024-12-19T07:49:55
draft: false
lang: th
format: Pdf
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

############################# Head ############################
head_title: "ไลบรารี JavaScript เพื่อตรวจสอบความแตกต่างใน PDF s"
head_description: "ซอฟต์แวร์ GroupDocs.Comparison Node.js สร้างรายงานที่ครอบคลุมโดยรายละเอียดความแตกต่างในเอกสาร PDF"

############################# Header ############################
title: "PDF เปรียบเทียบเอกสาร สำหรับ Node.js via Java" 
description: "ใช้ API เปรียบเทียบเอกสารของเราใน Node.js เพื่อตรวจจับและแสดงความแตกต่างใน PDF s ภายในแอปพลิเคชันที่ขับเคลื่อนด้วย JavaScriptรับประโยชน์จากการรับรายงานโดยละเอียดอย่างรวดเร็วและง่ายดาย"
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
    title: "สำรวจฟีเจอร์ไลบรารี GroupDocs.Comparison for Node.js via Java"
    link: "/comparison/nodejs-java/"
    link_title: "เรียนรู้เพิ่มเติม"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       รับรายงานโดยละเอียดเกี่ยวกับความแตกต่างภายในเอกสาร PDF ที่แอปพลิเคชัน .NET ของคุณใช้ GroupDocs.Comparison for Node.js via Java โดยการเพิ่มโค้ดสองบรรทัดโดยไม่ต้องใช้ซอฟต์แวร์เพิ่มเติมหรือไลบรารีภายนอกอื่น ๆควบคุมการเปลี่ยนแปลงใด ๆ ในย่อหน้า คำ อักขระ รูปร่าง และรูปแบบข้อความภายในไฟล์ PDF ของคุณการผสานการเปลี่ยนแปลงจากเอกสารหลายเวอร์ชันเป็นผลลัพธ์ PDF ก็พร้อมใช้งานเช่นกันประมวลผลเอกสารอย่างรวดเร็วและไม่ต้องใช้ความพยายามพิเศษ

############################# Steps ############################
steps:
    enable: true
    title: "รับรายงานความแตกต่างของ PDF ใน JavaScript"
    content: |
      ติดตามการเปลี่ยนแปลงของเอกสาร PDF ตามรายงานที่ประกอบด้วย [GroupDocs.Comparison](https://products.groupdocs.com/comparison/nodejs-java/)
      
      1. ใช้ [NPM](https://www.npmjs.com/package/@groupdocs/groupdocs.comparison) เพื่อติดตั้ง GroupDocs.Comparison สำหรับ Node.js via Java
      2. โทรหาคอนสตรัคเตอร์ Comparer ด้วยเส้นทางไฟล์ PDF
      3. ให้อีก PDF เพื่อเปรียบเทียบกับอันแรก
      4. ดึงรายงานสุดท้ายเกี่ยวกับความแตกต่างของไฟล์
   
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
        const comparer = new groupdocs.comparison.Comparer('first.pdf');

        // เพิ่มไฟล์เพิ่มเติม
        comparer.add('second.pdf');
        comparer.add('third.pdf');

        // ดึงรายงานขั้นสุดท้าย
        await comparer.compare('report_full.pdf');

        console.log('\nDocuments compared successfully.\nCheck output.');
        
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
      link: "https://purchase.groupdocs.com/pricing/comparison/nodejs-java/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "เปรียบเทียบรูปแบบไฟล์ยอดนิยม เช่น PDF โดยใช้ JavaScript"
    exclude: "PDF"
    description: "ไฟล์ PDF ของคุณสามารถเปรียบเทียบโดย API Node.js ของเราได้อย่างรวดเร็วควบคุมการเปลี่ยนแปลงเอกสารได้อย่างง่ายดายด้วยรายงานโดยละเอียด"
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