در این داکیومنت درمورد آیپی وی 6 صحبت میکنیم و نحوه استفاده اش با تونل RTT لطفا اگه میخواید از این قابلیت استفاده کنید این مطلب را کامل بخونید چون به راحتی میتونید اشتباه اجرا کنید برنامه را.


# توضیحات اولیه

اولین نکته اینه که باید بدونین سرور ها میتونن ایپی وی ۴ داشته باشن  یا نداشته باشن ؛ ایپی وی 6 هم همینطور 
یعنی سرور ها میتونن یا فقط ایپی ورژن ۴ یا فقط ایپی ورژن ۶ یا هردو رو با هم داشته باشن

آیپی وی 6 تقریبا بی نهایت وجود داره مثل آیپی ورژن ۴ تعدادش کم نیست و به همین دلیل رایگان هست ؛ تقریبا همه دیتا سنتر های خارجی وقتی ازشون سرور میخرید میتونید انتخاب کنید که سرور تون آیپی وی ۶ داشته باشه یا نه
همچنین حتی میتونید سرور خارجی بگیرید که فقط ایپی وی ۶ داشته باشه و پول آیپی وی ۴ که نیم یورو هست در ماه حدودا رو ندین.

اما دیتا سنتر های ایرانی ؛ حدوا ۳۰ درصدشون به سرور شما ایپی وی ۶ میتونن بدن چون بغیشون شبکشون از ایپی وی ۶ پشتیبانی نمیکنه

شرکت آروان جدیدا ایپی وی ۶ را پشتیبانی میکند ؛ هنگام ساخت سرور جدید باید گزینشو انتخاب کنید و همچنین حتما وارد تنظیمات فایروال آروان شده و با توجه به گروه ابرک خود ؛ اجازه ورود ترافیک های ایپی وی ۶ (هم از نوع Tcp و هم Udp و هم icmp) رو بدین وگر نه تونل نمیتونه ارتباط بگیره!

شما میتوانید روی سرور های ایران هم که تنها ایپی وی ۴ ارایه میدهند؛ آیپی وی سیکس ایجاد کنید و استفاده کنید ؛ اموزش های زیادی در یویتوب هست و کار سختی نیست؛ پس نیاز نیست حتما دیتا سنتری پیدا کنید که خودش ایپی وی ۶ بده.

 برای اینکار این آموزش هارو ببینید:


[آموزش اول متنی(اگه با لینوکس آشنایی دارین)
](https://linux.die.net/HOWTO/Linux+IPv6-HOWTO/configuring-ipv6to4-tunnels.html)


[آموزش دوم متنی (اگه با لینوکس آشنایی دارین)
](https://ubuntuforums.org/showthread.php?t=1752125)

[آموزش سوم متنی (اگه با لینوکس آشنایی دارین)](https://tldp.org/HOWTO/Linux+IPv6-HOWTO/ch09s04.html)

لازم نیست هر ۳ تاشو انجام بدین ؛ همشون یه چیزو میگن ؛ یکیشو انجام بدین کافیه و کار تمومه
ولی اگه موفق نشدین باید ویدیو با جزییات رو ببینید.


با تشکر از opiranclub که تنها فیلم آموزش فارسی این روش بود ولی خوب خیلی با جزییات توضیح داد باید با حوصله ببینید.

[آموزش ویدیویی (جزیات کامل ولی طولانی و تخصصی تر)](https://www.youtube.com/watch?v=jD3nmHSOekI)

حتما ازشون با لایک و سابسکرایپ حمایت کنید ؛ خود من هم اولین بار از این ویدیو بود که فهمیدم میشه همچین کاری کرد.


این آموزش هم یه روش دیگه هست پیشناهاد میکنم با روش های بالا راه بندازید اگه نشد این رو ببینید
[آموزش ویدیویی (یه روش دیگه) ](https://www.youtube.com/watch?v=eIivVQ7-TDA&t=5s)


***

خوب نکته دوم که مهم هست اینه که:

اگه شما یه سرور بخرید که فقط ایپی وی 6 داشته باشه؛ فقط میتونید با مقصد هایی ارتباط بگیرید که اون ها  ایپی وی ۶ داشته باشن و نمیتونید به جا هایی که فقط ایپی وی 4 هستن وصل بشید
و همچنین ؛ اگه سرورتون فقط ایپی وی ۴ داشته باشه ؛ فقط با مقاصدی ارتباط میگیرید که ایپی وی ۴ داشته باشن و نمیتونید به جا هایی که فقط ایپی وی ۶ هستن وصل بشید

اما همونطور که بالا گفتم ؛ شما میتونید در سرورتون هم ایپی ۶ داشته باشین هم ایپی وی ۴  و برای ارتباط با مقاصدی که ایپی وی ۶ هستن از ایپی وی 6 سرورتون استفاده میشه و برای ارتباط با مقاصدی که روی ایپی وی ۴ هستن
از ایپی وی ۴ سرورتون استفاده خواهد شد

همچنین بدونین که همه وب سایت ها میشه گفت ایپی وی ۴ دارن و بدون مشکل باز میشن ولی هستن سایت هایی که ایپی وی ۴ دارن ولی ۶ ندارن! مثل گیت هاب ؛ پورن هاب و غیره

# مزایای استفاده از تونل ایپی وی۶ 

1- عدم فیلتر شدن ایپی
همونطور که بالا هم گفتم ایپی وی 6 تعدادش تقریبا بی نهایته پس در نتیجه فایروال بلاک نمیکنه چون اگه بخواد روی پکت های ایپی وی 6 وقت بزاره  و بعد از کلی برسی تازه یه ایپی بلاک کنه ؛ خودشو مسخره کرده چون ایپی رایگان هست و به راحتی یه جدید میندازن رو سرور ؛‌کما اینکه خیلی ها مثلا ۱۰ تا ایپی وی 6 مختلف میندازن رو سرور و با ایجاد لود بالانسر میوتنن تا زمانی که هر ۱۰ تاش فیلتر نشده اتصال برقراره

ولی خوب گفتم نیاز به این کارا نیست ایپی وی 6 فیلترینگش بی معنیه .

2- قیمت رایگان

3- پینگ بهتر

# معایب استفاده از تونل ایپی وی۶

1- همونطور که گفتم ایپی وی 6 فیلترینگ رو بی معنی میکنه ؛ پس اگه قرار باشه واقعا فیلترینگ رو شدید کنن و اثر گزار کنن چاره ای ندارن که شبکه ایپی وی 6 با خارج از کشور رو کلا قطع کنن ؛ کما اینکه مدت ها بود که قطع بود و ممکنه در آینده این اتفاق بفته

2- هم سرور ایران و هم سرور خارج برای ارتباط باید ایپی وی 6 داشته باشن ؛ که  پیدا کردن سرور ایران با ایپی وی 6 چالش شما هست ؛ هر دیتا سنتری نداره سرور با ایپی وی 6 ؛ اما اگرم نداشت مشکلی نیست شما میتونید خودتون ایپی وی سیکس گلوبال ایجاد کنید از طریق ایپی ۴ سرورتون؛ همون ۲ تا لینک فیلمی که بالا گزاشتم رو ببینید متوجه میشید

3- سرور ایران نمیتوانید فقط با ایپی وی 6 (بدون ایپی وی ۴) بخرید. چرا؟

 چون خیلی از کاربرای داخل ایران از نت های مختلف استفاده میکنن از فیبر بگیر تا adsl و موبایل و p2p و غیره ؛ به نظرتون همه این ها ایپی وی 6 در اختیار کاربر قرار میدن تا با همین ایپی وی 6 به سرور ایرانتون وصل بشه ؟

قطعا خیر ؛ پس نیاز دارید در سرور ایران ایپی وی ۴ رو در کنار ایپی وی 6 داشته باشید ؛ نمیتونید مثل سرور خارج فقط با ایپی وی ۶ باشه و ایپی وی ۴ براش نخریده باشید.

4- اگه سرور خارجتون فقط ایپی وی 6 داشته باشه و ایپی وی ۴ نباشه درسته نیم یورو در ماه ارزون تر درمیاد یکم ولی خیلی از سایت ها هستن که ایپی وی 6 ساپورت نمیکنن ! مثل گیت هاب و یا حتی پورن هاب و اگه برای سرور خارج ایپی وی ۴ تهیه نکنید ؛ کاربر نمی تونه با اون وی پی ان سایت های ایپی وی فور رو داشته باشه و محدود میشه پس پیشناهاد میکنم سرور خارج هم ایپی وی ۴ داشته باشه ولی از ایپی وی 6 برای تونل استفاده کنه تا این مشکلات پیش نیاد 

در کل من ۲ تا مثال میزنم تا متوجه داستان بشین و اینکه چه محدودیت هایی ممکنه ایجاد شه و چه راه حل هایی وجود داره

# شروع
بهترین روش برای نشون دادن تونل ایپی وی 6 مثاله پس شروع کنیم

دوستان دقت کنید ایپی وی ۶ رو من خیلی تست کردم ؛ درست مراحل رو انجام بدین به راحتی کار میکنه ؛ لطفا کامل برسی کنید بعد issue ثبت کنید

# پیدا کردن آیپی وی ۶ ایران

برای دیدن ایپی وی سیکس سرور ایران این دستورو اجرا کنید ؛ اگر نصب نبود با apt نصب کنید
> ifconfig


؛ این خط که توش global نوشته و توی عکس هم با رنگ زرد زیرش خط کشیدم میشه ایپی وی سیکس ایرانتون

اگه این خط رو ندارید که توش global نوشته باشه یعنی سروتون ایپی وی سیکس نداره
![image](https://github.com/radkesvat/ReverseTlsTunnel/assets/134321679/3de60e3c-1488-4efc-b5fa-f8b7cfe79168)





# مثال اول 
میخواهیم ارزون ترین سناریو ممکن رو بسازیم ؛ سرورخارج میگیریم از هتزنر بدون ایپی وی فور یعنی این :



![image](https://github.com/radkesvat/ReverseTlsTunnel/assets/134321679/1dd3080b-9f52-4b4e-8a67-b7b3d01e4766)






خوب سرور که ساخته بشه یه همچین چیزی میبنید 
![image](https://github.com/radkesvat/ReverseTlsTunnel/assets/134321679/b65ea31c-0701-44d9-a1f3-5a41ab87351b)





آیپی وی ۶ که هتزنر به ما نشون میده این هست :

> 2a01:4f9:c011:2013::/64

اما دقت کنید این آیپی وی 6 ما نیست دقیقا ؛‌ اینو باید تغییر بدیم آخرشو که میشه این آیپی 

> 2a01:4f9:c011:2013::1

خوب حالا ما میتونیم برای تست توی ویندوز که هستیم این آیپی رو پینگ کنیم
> ping -6 2a01:4f9:c011:2013::1

و باید بدون مشکل پینگ بده ؛ اگه رو ویندوز ایپی وی 6 غیر فعال کرده باشین یا شبکه ای که بهش متصل هستین آیپی وی 6 نداده باشه بهتون
ارور دریافت میکنید 


خوب الان باید به این ایپی وی 6 خارجمون ssh بزنیم تا تونل رو روش نصب کنیم ؛ اما یه نکته مهم هست! ؛ توی برنامه ssh مثل پاتی یا کلا هرچی ؛ وقتی میخواید آیپی وی 6 بزارید
باید داخل براکت قرار بدین یعنی این :

> [2a01:4f9:c011:2013::1]

خوب حالا میتونیم اینو داخل برنامه قرار بدیم و وصل شیم




![image](https://github.com/radkesvat/ReverseTlsTunnel/assets/134321679/44ac6d45-bd9b-4c7f-9ef8-0587a340049a)


جا داره یه بار دیگه تکرار کنم اگه لبتابی که روش هستین ایپی وی 6 نداشته باشه ssh هم نمیتونین بزنین به خارجتون اگه نتونستید شبکه با ایپی وی 6 گیر بیارید ؛ سرور هتزنرتونو با ایپی وی ۴ و وی ۶ با هم بسازید 



خوب حالا ما وارد سرور خارج شدیم و میخوایم تونل رو نصب کنیم 
دستور نصب تونل رو اجرا میکنیم ولی خطا میخوریم به این شکل:


![image](https://github.com/radkesvat/ReverseTlsTunnel/assets/134321679/4c87937c-afb1-434b-90f7-dd9403f584fb)



خلاصه بگم ؛ گیت هاب ایپی وی 6 ساپورت نکرده و 3 تا راه داریم
یا باید همون سرور هتزنرمونو با ایپی وی ۴ بخریم برنامه رو نصب کنیم.

یا باید خودتون فایل اخرین نسخه رو اپلود کنید روی یه فضای ابری که ایپی وی ۶ ساپورت کنه و از اونجا با wget دانلود کنید.

یا باید با ftp فایل زیپ برنامه رو دستی ببریم روی کلود ؛ مثلا توی moba xterm میشه درگ کرد فایلو داخل سرور.

پس من از این لینک https://github.com/radkesvat/ReverseTlsTunnel/releases اخرین نسخه فایل زیپ مد نظرم رو بر میدارم ؛ چون من cpu رو arm انتخاب کردم موقع ساخت سرور در هتزنر 
اینجا هم v5.1_linux_arm64.zip را دانلود میکنم و درگ میکنم توی سرور خارج ام


خوب پس فایل زیپ رو داخل سرور بردیم ؛ بعد آنزیپ میکنیم و تمام برنامه روی سرور خارج هست و میتونیم اجرا کنیم 


> unzip v5.....zip

> ./RTT --kharej --iran-ip:xxx:xxx:xxx:xxx::1 --iran-port:443 --toip:127.0.0.1 --toport:443 --password:123 --sni:myket.ir

دقت کنید که ایپی وی 6 سرور ایرانو باید بهش بدین

دقت کنید ایپی ورژن 6 قرارداده شده بدون براکت هست! 

حالا میایم روی سرور ایران ؛ در سرور ایران برنامه رو با دستور نصب خیلی ساده نصب میکنیم چون ایپی وی ۴ هم داریم روی سرور ایران؛ گیتهاب مشکل ساز نمیشه ؛ بعد اینطوری اجرا میکنیم


> ./RTT --iran  --lport:443 --password:123 --sni:myket.ir

بله ؛ هیچ چیز خاصی اضافه نشده کاملا عادی اجرا شده ؛ و اینطوری ما با ایپی وی 6 تونل کردیم ؛ اما کار بر هم میتونه به ایپی وی 6 ایران وصل شه برای استفاده و هم ایپی وی ۴ 
بسته به کانفیگی که بهش میدین و دامنه ای که دادین این خواهد بود ؛ دست خودتونه خلاصه

نکته مهم ارتباط بین سرور ایران و خارج هست که با ایپی وی 6 برقرار شده و فیلتریگ رو عملا بی معنی کرده.

دقت کنید تمام امکانات تونل از لود بالانس گرفته تا اپلود فیک رو میتونید با ایپی وی 6 به کار بگیرید مغایرتی وجود ندارد.

در این روش چون برای سرور خارج ایپی وی ۴ تهینه نکردیم  ؛ کاربری که از این وی پی ان استفاده کنه نمیتونه سایت هایی مثل گیت هاب رو باز کنه و یه عده سایت های دیگه که تعدادشون زیاد نیست.


# مثال دوم

معقول ترین راه استفاده از ایپی وی 6 این روشه ؛ که از ایپی وی 6 فقط برای تونل استفاده میکنه و هیچ محدودیتی هم برای کاربر یا شما ایجاد نمیکنه چون برای خارج هم قراره ایپی وی ۴ تهیه کنیم؛ شروع کنیم

برای سرور خارج هتزنر هم ایپی وی ۴ میگیرید هم وی 6
![image](https://github.com/radkesvat/ReverseTlsTunnel/assets/134321679/ee977da8-5934-4116-a912-439c3a88dbea)



خوب با استفاده از ایپی وی ۴ که گرفتیم کاملا عادی ssh میزنیم به سرور خارج و تونل رو نصب میکنیم و اینطوری اجرا میکنیم

> ./RTT --kharej --iran-ip:xxx:xxx:xxx:xxx::1 --iran-port:443 --toip:127.0.0.1 --toport:443 --password:123 --sni:myket.ir


 دقت کنید ایپی ورژن 6 قرارداده شده بدون براکت هست! 
 
خوب ما باید آیپی وی 6 ایران رو داخل iran-ip قرار بدیم ؛‌ وقتی اینکارو انجام بدین  برنام با استفاده از ایپی وی 6 خودش  و سرور ایران ارتباط میگیره و هیچ ipv4 ای استفاده نمیشه در نتیجه فیلترینگ دست و پاش بسته میشه و فقط
ایپی وی 6 میبینه از سرور خارج و ایران شما


در سرور ایران که هم ایپی وی 6 داریم هم وی ۴ ؛ تونل رو نصب و عادی اجرا میکنیم

./RTT --iran  --lport:443 --password:123 --sni:myket.ir


خوب تونل انجام شد و در این روش هم مثل روش اول ارتباط بین سرور ایران و خارج با ایپی وی 6 برقرار شده و فیلتریگ رو عملا بی معنی کرده.


در این روش کاربر اگه خواست با ایپی ۴ یا ۶ به سرور ایران وصل میشه ؛ از طریق ایپی وی ۶ تونل میشه به خارج که هیچ مشکلی نداره و محدودیتی هم ایجاد نمیشه ؛ بعد که به خارج رسید ؛ میتونه هم سایت های ایپی وی ۴ که همه سایت ها هستن
و هم سایت هایی که ایپی وی ۶ ساپورت میکنن هم باز کنه و استفاده کنه ؛ البته اگه خواستید از ایپی وی 6 برای بازدید از سایتی استفاده نکنه اینو توی پنل میتونین تنظیم کنین.






