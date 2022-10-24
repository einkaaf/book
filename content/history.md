---
title: "تاریخچه"
type: chapter
weight: 3
---

زبان گو (Go) در سال ۲۰۰۷ (به شمسی: ۱۳۸۶) توسط «شرکت گوگل» با هدف افزایش بهره‌وری برنامه‌نویسی در محیط چندهسته‌ای، رایانه‌های شبکه‌ای و کدبیس‌های بزرگ طراحی شد [[به نقل از ویکی پدیا](https://fa.wikipedia.org/wiki/%DA%AF%D9%88_(%D8%B2%D8%A8%D8%A7%D9%86_%D8%A8%D8%B1%D9%86%D8%A7%D9%85%D9%87%E2%80%8C%D9%86%D9%88%DB%8C%D8%B3%DB%8C))] و سپس به عنوان یک زبان کامپایلری و تایپ استاتیک در نوامبر سال ۲۰۰۹ بصورت عمومی با هدف {{< tooltip text="کامپایل کارآمد" note="efficient compilation" >}}، {{< tooltip text="اجرای کارآمد" note="efficient execution" >}} و{{< tooltip text="سهولت برنامه نویسی" note="ease of programming" >}} معرفی شد که توسط شرکت گوگل توسعه داده شده است و بسیاری از اعضای تیم طراحی و توسعه زبان گو [[Ken Thompson](https://en.wikipedia.org/wiki/Ken_Thompson), [Rob Pike](https://en.wikipedia.org/wiki/Rob_Pike), [Robert Griesemer](https://en.wikipedia.org/wiki/Robert_Griesemer)] سال ها تجربه در زمینه تحقیق و توسعه زبان برنامه نویسی دارند.




زبان گو دارای یک سری ویژگی های منحصر به فرد می باشد و برخی از ویژگی هایش از سایر زبان ها الهام گرفته شده است :

-   پشتیبانی از برنامه نویسی  {{< tooltip text="همزمانی" note="Concurrency" >}} بصورت Built-in 
-    {{< tooltip text="گوروتین" note="Goroutine" >}} ها امکان اجرای همزمانی توابع را فراهم می کند و همچنین گوروتین ها واقعا خیلی سبک هستند به طوری که شما می توانید هزاران گوروتین را همزمان در سخت افزارهای مدرن بدون هیچ مشکل عملکردی اجرا کنید.
-   {{< tooltip text="کانال" note="Channel" >}} ها برپایه مدل CSP می باشد که امکان همگام سازی داده ها بین گوروتین ها را فراهم می کند.
-   پشتیبانی از تایپ های map و slice
-   امکان پیاده سازی {{< tooltip text="پلی مورفیسم" note="Polymorphism" >}} با استفاده از  {{< tooltip text="اینترفیس" note="Interface" >}} ها
-   پوینترها
-    {{< tooltip text="کلوژر" note="Closures" >}} توابع (یک تابع معمولی که داخل یک تابع دیگر به عنوان  {{< tooltip text="بازگشت" note="return" >}} تعریف می شود)
-   {{< tooltip text="متدها" note="Method" >}}
-   امکان defer برای تعویق فراخوانی یک تابع
-   قابلیت  {{< tooltip text="جاسازی" note="Embedding" >}} تایپ ها
-   ایمنی حافظه در زبان گو
-   قابلیت {{< tooltip text="زباله جمع کن" note="Garbage Collector" >}} خودکار
-   سازگاری کامل با انواع پلتفرم ها نظیر [linux, windows, mac, AIX, android, freeBSD] جهت توسعه و کامپایل
-   امکان Cross-compile با این امکان می توانید در هر پلتفرمی برای سایر پلتفرم ها کامپایل کنید
-   پشتیبانی از {{< tooltip text="جنریک" note="Generics" >}} یا تایپ پارامتر (از نسخه ۱.۱۸)
-   تست نویسی آسان
-    {{< tooltip text="اینترفیس" note="Interface" >}} و  {{< tooltip text="رفلکشن" note="Reflection" >}}
-   زبان گو مثل سایر زبان ها نظیر c, cpp یا java نیاز به نقطه ویرگول (Semicolons) ندارد و به نسبت زبان هایی که معرفی کردیم پرانتز کمتری استفاده می کند و همچنین ظاهر سینتکس گو خیلی خواناتر و راحتر می باشد.


علاوه بر ویژگی های که در بالا معرفی کردیم یک سری نکات برجسته در خصوص زبان گو وجود دارد که به شرح زیر می باشند:

-   سینتکس زبان گو به گونه ای طراحی شده که خیلی ساده و تمیز می باشد و این باعث می شود خیلی سریع زبان گو را یاد بگیرید و از همه مهم تر توسعه پروژه های مقیاس پذیر {{< tooltip text="مقیاس پذیر" note="Scale up" >}} با زبان گو به دلیل سادگی و آشکار بودن مفاهیم خیلی سریعتر صورت میگیرد.
    
-   زبان گو دارای کلی {{< tooltip text="پکیج های استاندارد" note="Standard packages" >}} و کاربردی جهت توسعه می باشد که همه این پکیج ها در انواع پلتفرم ها جهت توسعه قابل استفاده است.
    
-   زبان گو دارای یک جامعه بزرگ از توسعه دهندگان و انجمن های فعال می باشد که خیلی سریع می توانید به پاسخ سوالات خود برسید.


{{< hint=info >}}
برنامه نویس های زبان گو را {{< tooltip text="گوفر" note="Gopher" >}} صدا میزنند.
{{< /hint >}}