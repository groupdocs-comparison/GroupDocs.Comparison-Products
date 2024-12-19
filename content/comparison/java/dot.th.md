
---
############################# Static ############################
layout: "format"
date:  2024-12-19T07:49:43
draft: false
lang: th
format: Dot
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "Java DOT API เปรียบเทียบ - ตรวจสอบไฟล์ DOT เพื่อหาความแตกต่าง"
head_description: "เปรียบเทียบและรวมไฟล์ DOT ในแอปพลิเคชัน Java, J2EE, J2SEวิเคราะห์สรุปความแตกต่างในเนื้อหาข้อความ และสไตล์"

############################# Header ############################
title: "เปรียบเทียบไฟล์ DOT ใน Java" 
description: "ทำการเปรียบเทียบเนื้อหาระหว่างไฟล์ DOT มากกว่าสองไฟล์ใน Javaดึงรายการความแตกต่างและบันทึกไฟล์ที่เปรียบเทียบลงในเอกสารเดียว"
subtitle: "กรอบการตรวจสอบความแตกต่างของเอกสาร" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "ดาวน์โหลดฟรี Maven"
      link: "https://releases.groupdocs.com/comparison/java/"
      
############################# About ############################
about:
    enable: true
    title: "สำรวจความสามารถของไลบรารี GroupDocs.Comparison for Java"
    link: "/comparison/java/"
    link_title: "เรียนรู้เพิ่มเติม"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison for Java เป็นซอฟต์แวร์ Java ที่สร้างขึ้นเพื่อเปรียบเทียบภาพและเอกสารหลายรูปภาพที่ใช้รูปแบบเดียวกันช่วยในการระบุรูปแบบภายในย่อหน้าคำตัวอักษรรูปร่างและแม้แต่รูปแบบข้อความในเอกสารที่เปรียบเทียบด้วยความสามารถในการรวมการเปลี่ยนแปลงเหล่านี้และส่งออกไปยังเอกสารสุดท้าย ช่วยให้สามารถเปรียบเทียบและรวมเอกสาร PDF, Word, สเปรดชีต Excel, งานนำเสนอ PowerPoint, ไดอะแกรม Visio, อีเมล Outlook, HTML, ภาพวาด และรูปแบบไฟล์รูปภาพต่างๆ ซึ่งช่วยลดความจำเป็นสำหรับไลบรารีภายนอกใด ๆ

############################# Steps ############################
steps:
    enable: true
    title: "วิธีเปรียบเทียบเอกสาร DOT หลายฉบับโดยใช้ Java"
    content: |
      ใช้ [GroupDocs.Comparison](https://products.groupdocs.com/comparison/java/) เพื่อเปรียบเทียบไฟล์ DOT หลายไฟล์ และสร้างรายงานโดยรายละเอียดความแตกต่าง
      
      1. ใช้ตัวจัดการแพ็คเกจที่คุณต้องการเพื่อติดตั้ง GroupDocs.Comparison for Java จาก [Maven](https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/)
      2. สร้างอินสแตนซ์ของเส้นทางการตั้งค่าคลาส Comparer ไปยังไฟล์ใดไฟล์หนึ่งใน DOT
      3. เพิ่ม DOT เพิ่มเติมอย่างน้อยหนึ่งรายการลงในอินสแตนซ์ Comparer
      4. รับรายงานขั้นสุดท้ายโดยละเอียดโดยสรุปความแตกต่างที่แน่นอน
   
    code:
      platform: "net"
      copy_title: "คัดลอก"
      install:
        command: |
          <dependencies>
            <dependency>
              <groupId>com.groupdocs</groupId>
              <artifactId>groupdocs-comparison</artifactId>
              <version>{0}</version>
            </dependency>
          </dependencies>

          <repositories>
            <repository>
              <id>repository.groupdocs.com</id>
              <name>GroupDocs Repository</name>
              <url>https://repository.groupdocs.com/repo/</url>
            </repository>
          </repositories>
        copy_tip: "คลิกเพื่อคัดลอก"
        copy_done: "คัดลอก"
      links:
        #  loop
        - title: "ตัวอย่างเพิ่มเติม"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java"
        #  loop
        - title: "เอกสาร"
          link: "https://docs.groupdocs.com/comparison/java/"
          
      content: |
        ```java {style=abap}

        // ตรวจสอบไฟล์จากฮาร์ดไดรฟ์ของคุณเพื่อหาความแตกต่างหรือความคล้ายคลึงกัน

        // สร้างวัตถุ Comparer โดยระบุไฟล์เริ่มต้น
        try (Comparer comparer = new Comparer("source.dot") 
        {
            // รวมไฟล์เพิ่มเติมในการเปรียบเทียบ
        	comparer.add("target1.dot");
            comparer.add("target2.dot");

            // รับรายงานที่มีชื่อที่ระบุเป็นผลลัพธ์
            final Path resultPath = comparer.compare("result.dot"); 

            System.out.println("\nDocuments compared successfully.");
        }
        
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "พร้อมที่จะเริ่มแล้วหรือยัง?"
  description: "ลองใช้คุณสมบัติ GroupDocs.Comparison ฟรีหรือขอใบอนุญาต"
  items:
    #  loop
    - title: "Maven ดาวน์โหลด"
      link: "https://releases.groupdocs.com/comparison/java/"
      color: "red"
        #  loop
    - title: "การออกใบอนุญาต"
      link: "https://purchase.groupdocs.com/pricing/comparison/java/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "เปรียบเทียบเอกสารต่างๆโดยใช้ Java"
    exclude: "DOT"
    description: "โซลูชัน Java ของเราช่วยให้คุณสามารถเปรียบเทียบเอกสารในรูปแบบต่างๆอัปเดตเกี่ยวกับการเปลี่ยนแปลงเอกสารโดยประมวลผลได้อย่างง่ายดาย"
    items: 
        # format loop 1
        - name: "เปรียบเทียบไฟล์ PDF"
          format: "PDF"
          link: "/comparison/java/pdf/"
          description: "รูปแบบเอกสาร Adobe Portable"

        # format loop 2
        - name: "เปรียบเทียบไฟล์ DOCX"
          format: "DOCX"
          link: "/comparison/java/docx/"
          description: "ไมโครซอฟท์ Word เปิดเอกสาร XML"

        # format loop 3
        - name: "เปรียบเทียบไฟล์ RTF"
          format: "RTF"
          link: "/comparison/java/rtf/"
          description: "รูปแบบไฟล์ข้อความที่หลากหลาย"

        # format loop 4
        - name: "เปรียบเทียบไฟล์ TXT"
          format: "TXT"
          link: "/comparison/java/txt/"
          description: "รูปแบบไฟล์ข้อความธรรมดา"

        # format loop 5
        - name: "เปรียบเทียบไฟล์ XLSX"
          format: "XLSX"
          link: "/comparison/java/xlsx/"
          description: "ไมโครซอฟท์ Excel เปิดสเปรดชีต XML"

        # format loop 6
        - name: "เปรียบเทียบไฟล์ CSV"
          format: "CSV"
          link: "/comparison/java/csv/"
          description: "ไฟล์ค่าคั่นเครื่องหมายจุลภาค"

        # format loop 7
        - name: "เปรียบเทียบไฟล์ PPTX"
          format: "PPTX"
          link: "/comparison/java/pptx/"
          description: "PowerPoint เปิดการนำเสนอ XML"

        # format loop 8
        - name: "เปรียบเทียบไฟล์ ODS"
          format: "ODS"
          link: "/comparison/java/ods/"
          description: "Open Document สเปรดชีต"

        # format loop 9
        - name: "เปรียบเทียบไฟล์ ODP"
          format: "ODP"
          link: "/comparison/java/odp/"
          description: "OpenDocument รูปแบบไฟล์นำเสนอ"

        # format loop 10
        - name: "เปรียบเทียบไฟล์ ODT"
          format: "ODT"
          link: "/comparison/java/odt/"
          description: "Open Document ข้อความ"

        # format loop 11
        - name: "เปรียบเทียบไฟล์ JPEG"
          format: "JPEG"
          link: "/comparison/java/jpeg/"
          description: "JPEG รูปภาพ"

        # format loop 12
        - name: "เปรียบเทียบไฟล์ PNG"
          format: "PNG"
          link: "/comparison/java/png/"
          description: "Portable กราฟิกเครือข่าย"

        # format loop 13
        - name: "เปรียบเทียบไฟล์ GIF"
          format: "GIF"
          link: "/comparison/java/gif/"
          description: "ไฟล์รูปแบบการแลกเปลี่ยนแบบกราฟิก"

        # format loop 14
        - name: "เปรียบเทียบไฟล์ BMP"
          format: "BMP"
          link: "/comparison/java/bmp/"
          description: "รูปแบบไฟล์บิตแมป"

        # format loop 15
        - name: "เปรียบเทียบไฟล์ HTML"
          format: "HTML"
          link: "/comparison/java/html/"
          description: "ภาษามาร์กอัปข้อความไฮเปอร์"

        # format loop 16
        - name: "เปรียบเทียบไฟล์ MSG"
          format: "MSG"
          link: "/comparison/java/msg/"
          description: "ไมโครซอฟท์ Outlook ข้อความอีเมล"

        # format loop 17
        - name: "เปรียบเทียบไฟล์ ONE"
          format: "ONE"
          link: "/comparison/java/one/"
          description: "ไมโครซอฟท์ OneNote"

        # format loop 18
        - name: "เปรียบเทียบไฟล์ VSDX"
          format: "VSDX"
          link: "/comparison/java/vsdx/"
          description: "ไมโครซอฟท์ Visio การวาดภาพ"

        # format loop 19
        - name: "เปรียบเทียบไฟล์ CS"
          format: "CS"
          link: "/comparison/java/cs/"
          description: "ภาษา CSharp"

        # format loop 20
        - name: "เปรียบเทียบไฟล์ Java"
          format: "Java"
          link: "/comparison/java/java/"
          description: "Java ภาษา"
          
        # format loop 21
        - name: "เปรียบเทียบไฟล์ CPP"
          format: "CPP"
          link: "/comparison/java/cpp/"
          description: "ภาษา C ++"
---