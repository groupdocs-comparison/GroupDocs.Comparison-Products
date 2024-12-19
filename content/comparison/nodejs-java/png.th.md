
---
############################# Static ############################
layout: "format"
date:  2024-12-19T07:49:55
draft: false
lang: th
format: Png
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

############################# Head ############################
head_title: "JavaScript API สำหรับการเปรียบเทียบ PNG ภาพ"
head_description: "ไลบรารี GroupDocs.Comparison for Node.js via Java แสดงรายงานโดยละเอียดเกี่ยวกับความแตกต่างในรูปภาพในรูปแบบ PNG"

############################# Header ############################
title: "PNG เปรียบเทียบภาพ Node.js แอปพลิเคชันผ่าน Java" 
description: "ใช้ประโยชน์จากการใช้ Node.js API เพื่อติดตามการเปลี่ยนแปลงที่ไฟล์ PNG ที่แอปพลิเคชัน JavaScriptรับรายงานโดยละเอียดได้อย่างง่ายดายและรวดเร็ว"
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
    title: "เปิดความเป็นไปได้ API GroupDocs.Comparison for Node.js via Java"
    link: "/comparison/nodejs-java/"
    link_title: "เรียนรู้เพิ่มเติม"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       จัดทำรายงานฉบับเต็มเกี่ยวกับการเปลี่ยนแปลงใด ๆ ในเอกสาร PNG เวอร์ชันต่างๆ โดยแอปพลิเคชัน JavaScript ของคุณไม่จำเป็นต้องใช้ซอฟต์แวร์ของบุคคลที่สามรับทราบข้อมูลอย่างดีเกี่ยวกับการเปลี่ยนแปลงใด ๆ ในเวอร์ชันของภาพ PNG ของคุณ

############################# Steps ############################
steps:
    enable: true
    title: "เขียนรายงานความแตกต่างของรูปภาพ PNG ใน JavaScript"
    content: |
      ติดตามการเปลี่ยนแปลงเอกสาร PNG โดยใช้รายงานที่จัดทำโดย [GroupDocs.Comparison](https://products.groupdocs.com/comparison/nodejs-java/)
      
      1. ติดตั้งแพคเกจ GroupDocs.Comparison ผ่าน [NPM](https://www.npmjs.com/package/@groupdocs/groupdocs.comparison)
      2. ใช้ตัวสร้างคลาส Comparer ที่มีเส้นทางไปยัง PNG
      3. เพิ่ม PNG s เพื่อเปรียบเทียบ
      4. รับรายงานที่มีข้อมูลเกี่ยวกับความแตกต่าง
   
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
        const comparer = new groupdocs.comparison.Comparer('first.png');

        // เพิ่มไฟล์เพิ่มเติม
        comparer.add('second.png');
        comparer.add('third.png');

        // ดึงรายงานขั้นสุดท้าย
        await comparer.compare('report_full.png');

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
    title: "จับคู่รูปภาพในรูปแบบยอดนิยม เช่น PNG โดยใช้ JavaScript"
    exclude: "PNG"
    description: "ใช้ GroupDocs.Comparison for Node.js via Java เพื่อรับข้อมูลเกี่ยวกับความแตกต่างของรูปภาพ PNGรายงานโดยละเอียดช่วยให้คุณได้รับแจ้งเกี่ยวกับการเปลี่ยนแปลงใด ๆ ในข้อมูลสำคัญ"
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