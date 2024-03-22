
---
############################# Static ############################
layout: "format"
date:  2024-03-22T13:27:49
draft: false
lang: th
format: Docx
product: "Comparison"
product_tag: "comparison"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

############################# Head ############################
head_title: "Node.js API ช่วยให้สามารถเปรียบเทียบเอกสาร DOCX"
head_description: "MS Word DOCX ความแตกต่างของไฟล์ อาจถูกตรวจสอบโดย GroupDocs.Comparison Node.js API ที่สร้างรายงานที่มีประโยชน์ซึ่งอธิบายการเปลี่ยนแปลงเอกสาร"

############################# Header ############################
title: "DOCX เปรียบเทียบไฟล์ กับ Node.js via Java" 
description: "ใช้ API การประมวลผลเอกสารใน Node.js เพื่อตรวจจับและเปิดเผยการเปลี่ยนแปลงใด ๆ ในไฟล์ MS Word DOCX โดยแอปพลิเคชัน Node.js via Javaใช้ประโยชน์จากการสร้างรายงานที่รวดเร็วและง่ายดาย"
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
    title: "เปิดคุณสมบัติ API GroupDocs.Comparison for Node.js via Java"
    link: "/comparison/nodejs-java/"
    link_title: "เรียนรู้เพิ่มเติม"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       รายงานโดยละเอียดที่นำข้อมูลมากมายเกี่ยวกับการเปลี่ยนแปลงในเอกสาร DOCX เวอร์ชันต่างๆ จัดทำโดย GroupDocs.Comparisonใช้ Node.js via Java พร้อมกับ API ของเราโดยการเพิ่มโค้ดสองบรรทัดและไม่มีไลบรารีอื่นวิเคราะห์การเปลี่ยนแปลงในหน้า ข้อความ รูปแบบข้อความ หรือรูปร่างในเอกสาร MS Wordเลือกเฉพาะข้อมูลที่ถูกต้องและเขียนเอกสาร DOCX สุดท้ายโดยการผสานรวมก้าวหน้าในโซลูชันการประมวลผลเอกสารของคุณด้วยซอฟต์แวร์ของเรา

############################# Steps ############################
steps:
    enable: true
    title: "จัดทำรายงานด้วยความแตกต่างของเอกสาร DOCX ใน JavaScript"
    content: |
      [GroupDocs.Comparison](https://products.groupdocs.com/comparison/nodejs-java/) และ Node.js via Java ช่วยให้เราสามารถเปรียบเทียบเอกสาร DOCX
      
      1. ใช้ [NPM](https://www.npmjs.com/package/@groupdocs/groupdocs.comparison) เพื่อติดตั้ง GroupDocs.Comparison สำหรับ Node.js via Java
      2. การเรียกตัวสร้าง Comparer ต้องการเส้นทาง DOCX
      3. ต้องจัดเตรียมไฟล์ DOCX อื่น ๆ
      4. เพลิดเพลินกับผลลัพธ์
   
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
        const comparer = new groupdocs.comparison.Comparer('first.docx');

        // เพิ่มไฟล์เพิ่มเติม
        comparer.add('second.docx');
        comparer.add('third.docx');

        // ดึงรายงานขั้นสุดท้าย
        await comparer.compare('report_full.docx');

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
      link: "https://purchase.groupdocs.com/pricing/comparison/java/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "ใช้ JavaScript สำหรับการเปรียบเทียบเอกสาร DOCX"
    exclude: "DOCX"
    description: "ไฟล์ MS Word DOCX ใดก็ได้สามารถเปรียบเทียบกับ GroupDocs.Comparison for Node.js via Javaใช้ข้อมูลที่มีค่าเกี่ยวกับการเปลี่ยนแปลงในเอกสารของคุณ"
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