
---
############################# Static ############################
layout: "format"
date:  2024-11-21T08:27:19
draft: false
lang: th
format: Png
product: "Comparison"
product_tag: "comparison"
platform: "Python via .NET"
platform_tag: "python-net"

############################# Head ############################
head_title: "เปรียบเทียบรูปภาพ PNG โดยใช้ Python API"
head_description: "ไลบรารี GroupDocs.Comparison for Python via .NET สร้างรายงานโดยละเอียดที่แสดงความแตกต่างระหว่างไฟล์ภาพ PNG"

############################# Header ############################
title: "วิเคราะห์รูปภาพ PNG ใน Python" 
description: "ใช้ประโยชน์จาก Python API เพื่อค้นหาความคลาดเคลื่อนในไฟล์ PNG ได้อย่างราบรื่นภายในแอปพลิเคชัน Python ของคุณ รับรายงานที่ครอบคลุมได้อย่างง่ายดาย"
subtitle: "เครื่องมือเปรียบเทียบไฟล์ขั้นสูง" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "ดาวน์โหลดฟรีจาก PyPi"
      link: "https://releases.groupdocs.com/comparison/python-net/"
      
############################# About ############################
about:
    enable: true
    title: "สำรวจฟีเจอร์ของ GroupDocs.Comparison for Python via .NET API"
    link: "/comparison/python-net/"
    link_title: "เรียนรู้เพิ่มเติม"
    picture: "about_viewer.svg" # 480 X 400
    content: |
       สร้างรายงานอย่างละเอียดโดยให้รายละเอียดความคลาดเคลื่อนระหว่างเวอร์ชันของรูปภาพ PNG โดยตรงภายในแอปพลิเคชัน Python โดยไม่ต้องอาศัยซอฟต์แวร์เพิ่มเติม ติดตามการเปลี่ยนแปลงทั้งหมดที่เกี่ยวข้องกับภาพ PNG ของคุณ

############################# Steps ############################
steps:
    enable: true
    title: "สร้างรายงานการเปรียบเทียบสำหรับรูปภาพ PNG ด้วย Python"
    content: |
      ตรวจสอบการเปลี่ยนแปลงในไฟล์ PNG โดยใช้ [GroupDocs.Comparison](https://products.groupdocs.com/comparison/python-net/) และสร้างรายงานได้อย่างง่ายดาย
      
      1. รับแพ็คเกจ GroupDocs.Comparison ผ่านทาง [PyPi](https://pypi.org/project/groupdocs-comparison-net/)
      2. สร้างอินสแตนซ์ของเครื่องมือเปรียบเทียบและป้อนเส้นทางสำหรับรูปภาพ PNG ภาพแรก
      3. รวมไฟล์ PNG หนึ่งไฟล์ขึ้นไปสำหรับการศึกษาเปรียบเทียบ
      4. เข้าถึงรายงานที่ครอบคลุมซึ่งมีรายละเอียดความคลาดเคลื่อนทางภาพทั้งหมด
   
    code:
      platform: "python-net"
      copy_title: "คัดลอก"
      result_enable: true
      result_link: "/examples/comparison/comparison_result.pdf"
      result_title: "ตัวอย่างไฟล์ผลลัพธ์"
      install:
        command: "pip install groupdocs-comparison-net"
        copy_tip: "คลิกเพื่อคัดลอก"
        copy_done: "คัดลอก"
      links:
        #  loop
        - title: "ตัวอย่างเพิ่มเติม"
          link: "https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET/"
        #  loop
        - title: "เอกสาร"
          link: "https://docs.groupdocs.com/comparison/python-net/"
          
      content: |
        ```python {style=abap}
        def run():

            # เปรียบเทียบหลายไฟล์เพื่อดูความเหมือนและความแตกต่าง

            # เริ่มต้น Comparer และโหลดไฟล์แรก
            with groupdocs.comparison.Comparer("first.png") as comparer:

                # เพิ่มไฟล์เพิ่มเติมเพื่อการเปรียบเทียบ
                comparer.add('second.png')
                comparer.add('third.png')

                # รับรายงานการเปรียบเทียบขั้นสุดท้าย
                comparer.compare('report_full.png')

                print("\nDocuments compared successfully.\nCheck output.")
        ```            

############################# Actions ############################

actions:
  enable: true
  title: "พร้อมที่จะเริ่มแล้วหรือยัง?"
  description: "ลองใช้คุณสมบัติ GroupDocs.Comparison ฟรีหรือขอใบอนุญาต"
  items:
    #  loop
    - title: "PyPi ดาวน์โหลด"
      link: "https://releases.groupdocs.com/comparison/python-net/"
      color: "red"
        #  loop
    - title: "การออกใบอนุญาต"
      link: "https://purchase.groupdocs.com/pricing/comparison/python-net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "เปรียบเทียบรูปภาพในรูปแบบเช่น PNG"
    exclude: "PNG"
    description: "ใช้ GroupDocs.Comparison for Python via .NET เพื่อระบุความแตกต่างระหว่างรูปภาพ PNG สร้างรายงานโดยละเอียดเพื่อติดตามการเปลี่ยนแปลงที่สำคัญ"
    items: 
        # format loop 1
        - name: "เปรียบเทียบไฟล์ PDF"
          format: "PDF"
          link: "/comparison/python-net/pdf/"
          description: "รูปแบบเอกสาร Adobe Portable"

        # format loop 2
        - name: "เปรียบเทียบไฟล์ DOCX"
          format: "DOCX"
          link: "/comparison/python-net/docx/"
          description: "ไมโครซอฟท์ Word เปิดเอกสาร XML"

        # format loop 3
        - name: "เปรียบเทียบไฟล์ RTF"
          format: "RTF"
          link: "/comparison/python-net/rtf/"
          description: "รูปแบบไฟล์ข้อความที่หลากหลาย"

        # format loop 4
        - name: "เปรียบเทียบไฟล์ TXT"
          format: "TXT"
          link: "/comparison/python-net/txt/"
          description: "รูปแบบไฟล์ข้อความธรรมดา"

        # format loop 5
        - name: "เปรียบเทียบไฟล์ XLSX"
          format: "XLSX"
          link: "/comparison/python-net/xlsx/"
          description: "ไมโครซอฟท์ Excel เปิดสเปรดชีต XML"

        # format loop 6
        - name: "เปรียบเทียบไฟล์ CSV"
          format: "CSV"
          link: "/comparison/python-net/csv/"
          description: "ไฟล์ค่าคั่นเครื่องหมายจุลภาค"

        # format loop 7
        - name: "เปรียบเทียบไฟล์ PPTX"
          format: "PPTX"
          link: "/comparison/python-net/pptx/"
          description: "PowerPoint เปิดการนำเสนอ XML"

        # format loop 8
        - name: "เปรียบเทียบไฟล์ ODS"
          format: "ODS"
          link: "/comparison/python-net/ods/"
          description: "Open Document สเปรดชีต"

        # format loop 9
        - name: "เปรียบเทียบไฟล์ ODP"
          format: "ODP"
          link: "/comparison/python-net/odp/"
          description: "OpenDocument รูปแบบไฟล์นำเสนอ"

        # format loop 10
        - name: "เปรียบเทียบไฟล์ ODT"
          format: "ODT"
          link: "/comparison/python-net/odt/"
          description: "Open Document ข้อความ"

        # format loop 11
        - name: "เปรียบเทียบไฟล์ JPEG"
          format: "JPEG"
          link: "/comparison/python-net/jpeg/"
          description: "JPEG รูปภาพ"

        # format loop 12
        - name: "เปรียบเทียบไฟล์ PNG"
          format: "PNG"
          link: "/comparison/python-net/png/"
          description: "Portable กราฟิกเครือข่าย"

        # format loop 13
        - name: "เปรียบเทียบไฟล์ GIF"
          format: "GIF"
          link: "/comparison/python-net/gif/"
          description: "ไฟล์รูปแบบการแลกเปลี่ยนแบบกราฟิก"

        # format loop 14
        - name: "เปรียบเทียบไฟล์ BMP"
          format: "BMP"
          link: "/comparison/python-net/bmp/"
          description: "รูปแบบไฟล์บิตแมป"

        # format loop 15
        - name: "เปรียบเทียบไฟล์ HTML"
          format: "HTML"
          link: "/comparison/python-net/html/"
          description: "ภาษามาร์กอัปข้อความไฮเปอร์"

        # format loop 16
        - name: "เปรียบเทียบไฟล์ MSG"
          format: "MSG"
          link: "/comparison/python-net/msg/"
          description: "ไมโครซอฟท์ Outlook ข้อความอีเมล"

        # format loop 17
        - name: "เปรียบเทียบไฟล์ ONE"
          format: "ONE"
          link: "/comparison/python-net/one/"
          description: "ไมโครซอฟท์ OneNote"

        # format loop 18
        - name: "เปรียบเทียบไฟล์ VSDX"
          format: "VSDX"
          link: "/comparison/python-net/vsdx/"
          description: "ไมโครซอฟท์ Visio การวาดภาพ"

        # format loop 19
        - name: "เปรียบเทียบไฟล์ CS"
          format: "CS"
          link: "/comparison/python-net/cs/"
          description: "ภาษา CSharp"

        # format loop 20
        - name: "เปรียบเทียบไฟล์ Java"
          format: "Java"
          link: "/comparison/python-net/java/"
          description: "Java ภาษา"
          
        # format loop 21
        - name: "เปรียบเทียบไฟล์ CPP"
          format: "CPP"
          link: "/comparison/python-net/cpp/"
          description: "ภาษา C ++"
---