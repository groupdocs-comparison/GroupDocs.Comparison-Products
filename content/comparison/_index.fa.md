
---
############################# Static ############################
layout: "family"
date:  2024-07-10T18:47:13
draft: false

product: "Comparison"
product_tag: "comparison"

lang: fa

############################# Head ############################
head_title: "کتابخانه مقایسه اسناد پایتون C# Java Node.js | بررسی کننده تفاوت"
head_description: "GroupDocs کتابخانه مقایسه اسناد بومی C# .NET Java و Node.js. تفاوت بین فایل های فرمت های پشتیبانی شده را بررسی کنید."

############################# Header ############################
title: "مقایسه تفاوت های بین انواع فایل های محبوب"
description: |
  API قوی برای مقایسه اسناد در فرمت های مختلف فایل.

  تفاوت های محتوا را با حداقل تلاش برای کدگذاری شناسایی و برجسته کنید.

  تفاوت های قابل مشاهده را برجسته کنید و تغییرات در خواص پنهان را کشف کنید.

############################# Supported Platforms ###############################
supported_platforms:
  enable: true
  head_title: "پلت فرم خود را انتخاب کنید"
  title: "استقلال پلت فرم"
  description: "کتابخانه GroupDocs.Comparison از سیستم عامل ها و چارچوبهای زیر پشتیبانی می کند:"
  details_link_title: "بیشتر بدانید"

  items:
    # items loop
    - title: ".NET"
      description: GroupDocs.Comparison برای .NET 
      color: "blue"
      tag: "net"
      link: "/comparison/net/"
      features_link: "https://docs.groupdocs.com/comparison/net/system-requirements/"
      features:
          # features loop
          - rows: "4"
            content: |
                    .NET Framework 4.6.2 or higher <br> .NET Core 2.0 or higher <br> .NET 6.0 or higher
      
          # features loop
          - rows: "1"
            content: |
                    Windows <br> Linux <br> Mac OS
      
          # features loop
          - rows: "3"
            content: |
                    Microsoft Visual Studio <br> JetBrains Rider
      
          # features loop
          - rows: "1"
            content: |
                    50+ file formats
      

    # items loop
    - title: "Java"
      description: GroupDocs.Comparison برای Java
      color: "red"
      tag: "java"
      link: "/comparison/java/"
      features_link: "https://docs.groupdocs.com/comparison/java/system-requirements/"
      features:
          # features loop
          - rows: "4"
            content: |
                    Java 8 or higher <br> Kotlin
      
          # features loop
          - rows: "1"
            content: |
                    Windows <br> Linux <br> Mac OS
      
          # features loop
          - rows: "3"
            content: |
                    IntelliJ IDEA <br> Eclipse <br> NetBeans
      
          # features loop
          - rows: "1"
            content: |
                    50+ file formats

    # items loop
    - title: "Node.js"
      description: GroupDocs.Comparison برای Node.js
      color: "green"
      tag: "nodejs-java"
      link: "/comparison/nodejs-java/"
      features_link: "https://docs.groupdocs.com/comparison/nodejs-java/system-requirements/"
      features:
          # features loop
          - rows: "4"
            content: |
                    Node.js 16+ and J2SE 8.0 (1.8)+
      
          # features loop
          - rows: "1"
            content: |
                    Windows <br> Linux <br> Mac OS
      
          # features loop
          - rows: "3"
            content: |
                    Atom <br> Visual Studio Code <br> هر ویرایشگر متن دیگر
      
          # features loop
          - rows: "1"
            content: |
                    50+ file formats

    # items loop
    - title: "Python"
      description: GroupDocs.Comparison Python
      color: "yellow"
      tag: "python-net"
      link: "/comparison/python-net/"
      features_link: "https://docs.groupdocs.com/comparison/net/system-requirements/"
      features:
          # features loop
          - rows: "4"
            content: |
                    Python 3.9+ and .Net 6+
      
          # features loop
          - rows: "1"
            content: |
                    Windows <br> Linux <br> Mac OS
      
          # features loop
          - rows: "3"
            content: |
                    IDLE <br> PyCharm <br> Visual Studio Code
      
          # features loop
          - rows: "1"
            content: |
                    50+ file formats

############################# Features ###############################
features:
  enable: true
  title: "ویژگی های کلیدی GroupDocs.Comparison"
  description: "API برای مقایسه و مشاهده تفاوت در PDF، Word، Excel، فایل های کد منبع و موارد دیگر."

  items:
    # items loop
    - icon: "analize"
      title: "نتیجه نمایش دیف بصری"
      content: "تغییرات را به راحتی با تفاوت های برجسته در یک گزارش تک سند تجزیه و تحلیل کنید."

    # items loop
    - icon: "merge"
      title: "فرآیند بررسی تغییرات کارآمد"
      content: "برای تصمیم گیری آسان، تغییرات را با تغییرات متمایز از نظر بصری قبول یا رد کنید."

    # items loop
    - icon: "styles"
      title: "مقایسه محتوا و سبک"
      content: "محتویات متن و همچنین تغییرات در قالب بندی و سبک را مقایسه کنید."

    # items loop
    - icon: "pages"
      title: "مقایسه صفحات خاص"
      content: "فقط بخش ها یا صفحات خاص سند را برای مقایسه بارگذاری کنید."

############################# Code samples ############################
code_samples:
  enable: true
  title: "نمایشگاه کد عملی"
  description: "برخی از موارد استفاده از عملیات معمولی GroupDocs.Comparison."
  items:
    # code sample loop
    - title: "مقایسه دو فایل"
      content: |
       برای مقایسه دو سند، با بارگذاری هر دو فایل منبع و هدف شروع کنید و سپس روش `compare` را اعمال کنید. شما انعطاف پذیری را دارید که تنظیمات مقایسه خاص را برای تجزیه و تحلیل متناسب تر انتخاب کنید.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // سند منبع را مشخص کنید
            using (Comparer comparer = new Comparer("source.docx"))
            {
                // اضافه کردن یک یا چند سند هدف
                comparer.Add(target.docx");

                // گزینه های مقایسه را مشخص کنید
                CompareOptions options = new CompareOptions() {ShowRevisions = false};
                // مقایسه و ذخیره نتیجه
                comparer.Compare("result.docx", options);
            }
            ```
        - language: "Java"
          color: "red"
          content: |
            ```java {style=abap}   
            // سند منبع را مشخص کنید
            try (Comparer comparer = new Comparer("source.docx"))
            {
                // اضافه کردن یک یا چند سند هدف
                comparer.add("target.docx");

                // گزینه های مقایسه را مشخص کنید
                CompareOptions options = new CompareOptions();
                options.setShowRevisions(false);

                // مقایسه و ذخیره نتیجه
                final comparer.compare("result.docx", options);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // سند منبع را مشخص کنید
            const comparer = new groupdocs.comparison.Comparer("source.docx");

            // اضافه کردن یک یا چند سند هدف
            comparer.add("target.docx");

            // گزینه های مقایسه را مشخص کنید
            const options = new groupdocs.comparison.CompareOptions();
            options.setShowRevisions(false);

            // مقایسه و ذخیره نتیجه
            comparer.compare("result.docx", options);
            ```
        - language: "Python"
          color: "yellow"
          content: |
            ```python {style=abap}  
            def run():

                # سند منبع را مشخص کنید
                with groupdocs.comparison.Comparer("source.docx") as comparer:

                    # اضافه کردن یک یا چند سند هدف
                    comparer.add("target.docx")

                    # گزینه های مقایسه را مشخص کنید
                    options = new groupdocs.comparison.CompareOptions()
                    options.setShowRevisions(false)

                    # مقایسه و ذخیره نتیجه
                    comparer.compare("result.docx", options)
            ```


############################# Supported Formats ###############################
formats:
  enable: true
  title: "50+ فرمت فایل پشتیبانی می شود"
  description: "GroupDocs.Comparison عملیات مقایسه را در خانواده های فرمت مختلف فعال می کند."

############################# Metrics ###############################
metrics:
  enable: true
  title: "معیارهای دقیق و بینش آماری"
  description: "تجزیه و تحلیل کاملی از ارقام کلیدی ما را بررسی کنید و معیارهای جامع و بینش آماری را در مورد دستاوردها، نفوذ و گسترش ما ارائه دهید."

  items:
    # items loop
    - number: "50+"
      title: "فرمت های پشتیبانی شده"
      content: "API بیش از 50 فرمت فایل و سند پرکاربرد را در خود جای می دهد."

    # items loop
    - number: "800k"
      title: "NuGet دانلود"
      content: "GroupDocs.Comparison برای .NET بیش از 800K دانلود از طریق مدیر بسته NuGet دریافت کرده است."

    # items loop
    - number: "15k"
      title: "دانلود های Maven"
      content: "GroupDocs.Comparison برای Java بیش از 15K دانلود از مخزن Maven ما جمع آوری کرده است."

    # items loop
    - number: "140+"
      title: "مشتریان خوشحال"
      content: "کتابخانه های ما توسط توسعه دهندگان فردی و شرکت های برتر در سراسر جهان پذیرفته می شوند"


############################# Customers ###############################
customers:
  enable: true
  title: "مشتریان خوشحال ما"
  description: "GroupDocs کتابخانه توسط مارک های مشهور و برجسته جهانی در سراسر جهان استخدام می شوند."

  items:
    # items loop
    - title: "BenQ Corporation"
      logo: "benq"
      
    # items loop
    - title: "Nasdaq Stock Market"
      logo: "nasdaq"
      
    # items loop
    - title: "AT&T Inc."
      logo: "att"
      
    # items loop
    - title: "Customer logo AstraZeneca"
      logo: "astrazeneca"
      
    # items loop
    - title: "Central Bank of Argentina"
      logo: "argentinacentralbank"
      
    # items loop
    - title: "Roche Holding AG"
      logo: "roche"
      
    # items loop
    - title: "Capita"
      logo: "capita"
      
    # items loop
    - title: "Axa S.A."
      logo: "axa"
      
    # items loop
    - title: "Instructure Inc."
      logo: "instructure"
      
    # items loop
    - title: "Wipro"
      logo: "wipro"


############################# Actions ###############################
actions:
  enable: true
  title: "آماده شروع هستید؟"
  description: "GroupDocs.Comparison ویژگی را به صورت رایگان در پلتفرم خود امتحان کنید"

  items:
    # items loop
    - title: ".NET"
      color: "blue"
      link: "/comparison/net/"

    # items loop
    - title: "Java"
      color: "red"
      link: "/comparison/java/"

    # items loop
    - title: "Node.js"
      color: "green"
      link: "/comparison/nodejs-java/"      

############################# FAQ ###############################
faq:
  enable: true
  title: "سوالات متداول"
  description: "پاسخ به سوالات متداول"

  items:
    # items loop
    - question: "آیا کتابخانه GroupDocs.Comparison به نرم افزار شخص ثالث دیگری برای دستکاری اسناد نیاز دارد؟"
      answer: "GroupDocs.Comparison نیازی به نصب هیچ نرم افزار خارجی مانند Adobe Acrobat، Microsoft Office یا هر نرم افزار دیگری ندارد."

    # items loop
    - question: "آیا می توانم کتابخانه GroupDocs.Comparison را قبل از خرید آن امتحان کنم؟"
      answer: "بله، شما می توانید GroupDocs.Comparison را بدون خرید مجوز امتحان کنید. پس از نصب بدون مجوز، کتابخانه در حالت آزمایشی کار می کند. در این حالت، نشان های آزمایشی به سند حاصل اضافه می شوند و به 3 صفحه اول برش داده می شوند. اگر می خواهید GroupDocs.Comparison را بدون محدودیت نسخه آزمایشی آزمایش کنید، می توانید مجوز موقت 30 روزه را نیز درخواست کنید. برای جزئیات بیشتر، [مجوز موقت](https://purchase.groupdocs.com/temporary-license/) را ببینید."

    # items loop
    - question: "چه مجوزهایی دارید؟"
      answer: "ما چندین نوع مجوز را برای متناسب با نیازهای توسعه دهندگان یا شرکت های خاص ارائه می دهیم. انواع مجوز به تعداد توسعه دهندگان، تعداد مکان های سایت توسعه دهنده و اینکه آیا نیاز دارید SDK/API ما را به مشتریان نهایی خود ارائه دهید بستگی دارد. متناوباً، می توانید مجوزهای Metered را بر اساس استفاده ماهانه از محصول انتخاب کنید. در [قیمت گذاری](https://purchase.groupdocs.com/pricing/comparison/net/) بیشتر بدانید."

############################# Cloud Links ###############################
cloud_links:
  enable: true
  title: "GroupDocs.Comparison API های کد پایین"
  description: "قابلیت های مقایسه اسناد را با استفاده از API REST مبتنی بر ابر ما در هر برنامه ای بگنجانید."
  
  items:
    # items loop
    - title: "GroupDocs.Comparison Cloud for cURL"
      content: "با API مقایسه سند cURL REST full برای مقایسه Word، Excel، PowerPoint و سایر فرمت های فایل محبوب کار کنید."
      icon: "groupdocs_comparison-for-curl"
      link: "https://products.groupdocs.cloud/comparison/curl"

    # items loop
    - title: "GroupDocs.Comparison Cloud for .NET"
      content: "قابلیت های قدرتمند مقایسه اسناد را در .NET برنامه با استفاده از Cloud SDK برای .NET اضافه کنید. DOCX، XLSX، PPTX و موارد دیگر را مقایسه کنید."
      icon: "groupdocs_comparison-for-net"
      link: "https://products.groupdocs.cloud/comparison/net"

    # items loop
    - title: "GroupDocs.Comparison Cloud for Java"
      content: "ویژگی های مقایسه اسناد با وفاداری بالا را به برنامه های جاوا خود با SDK مقایسه اسناد مخصوص طراحی شده برای Java اضافه کنید."
      icon: "groupdocs_comparison-for-java"
      link: "https://products.groupdocs.cloud/comparison/java"

############################# App links ###############################
app_links:
  enable: true
  title: "GroupDocs.Comparison برنامه های نوکد"
  description: "برنامه مبتنی بر وب که به شما امکان می دهد مقایسه ها را در بیش از 50 فرمت فایل محبوب مستقیماً در مرورگر خود انجام دهید."

  items:
    # items loop
    - title: "GroupDocs.Comparison Total"
      content: "ابزار آنلاین diff برای مقایسه دو سند از هر دستگاه."
      icon: "groupdocs_comparison-app"
      link: "https://products.groupdocs.app/comparison/total"

    # items loop
    - title: "GroupDocs.Comparison DOCX"
      content: "DOCX فایل را به صورت آنلاین مقایسه کنید."
      icon: "groupdocs_words-app"
      link: "https://products.groupdocs.app/comparison/docx"

    # items loop
    - title: "GroupDocs.Comparison PDF"
      content: "Diff PDF اسناد آنلاین با استفاده از برنامه مقایسه PDF."
      icon: "groupdocs_pdf-app"
      link: "https://products.groupdocs.app/comparison/pdf"


      


---