
---
############################# Static ############################
layout: "format"
date:  2024-12-19T07:49:45
draft: false
lang: th
format: Png
product: "Comparison"
product_tag: "comparison"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "รับรายงานความแตกต่างสำหรับรูปภาพ PNG โดยใช้ Java"
head_description: "API GroupDocs.Comparison for Java สร้างรายงานการเปรียบเทียบที่เป็นประโยชน์สำหรับเอกสาร PNG ในแอปพลิเคชันที่รองรับ J2EE และ J2SE"

############################# Header ############################
title: "เปรียบเทียบรูปภาพ PNG โดยใช้ Java" 
description: "เพิ่มพลังให้กับแอปพลิเคชัน Java, J2EE หรือ J2SE ของคุณด้วย API GroupDocs.Comparisonดึงข้อมูลรายละเอียดเกี่ยวกับการเปลี่ยนแปลงใด ๆ ที่รูปภาพ PNG ของคุณ"
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
    title: "รับทราบเกี่ยวกับคุณสมบัติ API GroupDocs.Comparison for Java"
    link: "/comparison/java/"
    link_title: "เรียนรู้เพิ่มเติม"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       GroupDocs.Comparison พัฒนาเป็น API Java ดั้งเดิมที่เหมาะสำหรับการจัดทำรายงานโดยละเอียดตามความแปรปรของภาพรุ่นต่าง ๆ ที่แสดงในรูปแบบ PNGไม่เพียงรองรับรูปแบบ PNG เท่านั้นคุณสมบัติที่มีประโยชน์มากมายที่จัดทำโดย API ของเรา

############################# Steps ############################
steps:
    enable: true
    title: "ใช้ Java เพื่อเปรียบเทียบไฟล์ PNG"
    content: |
      เปรียบเทียบไฟล์ PNG กับ [GroupDocs.Comparison](https://products.groupdocs.com/comparison/java/) และดึงรายงานที่เกี่ยวข้องเกี่ยวกับการเปลี่ยนแปลง
      
      1. ติดตั้งแพคเกจ GroupDocs.Comparison for Java ดาวน์โหลดจาก [Maven](https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-comparison/)
      2. ให้อินสแตนซ์ Comparer และส่งเส้นทางไปยัง PNG
      3. เพิ่มไฟล์ PNG เพื่อเปรียบเทียบเพิ่มเติม
      4. บันทึกรายงานไปยังดิสก์ท้องถิ่น
   
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
        try (Comparer comparer = new Comparer("main.png") 
        {
            // รวมไฟล์เพิ่มเติมในการเปรียบเทียบ
        	comparer.add("version1.png");
            comparer.add("version2.png");
            comparer.add("version3.png");

            // รับรายงานที่มีชื่อที่ระบุเป็นผลลัพธ์
            final Path resultPath = comparer.compare("full_report.png"); 

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
    title: "ค้นหาความแตกต่างในรูปภาพ PNG เวอร์ชันต่างๆผ่าน Java"
    exclude: "PNG"
    description: "GroupDocs.Comparison for Java API ติดตามการเปลี่ยนแปลงภายในรูปภาพ PNG และจัดทำรายงานสาธิตเพื่อวิเคราะห์เพิ่มเติม"
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