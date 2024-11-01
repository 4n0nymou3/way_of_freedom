# خانگی

راه اندازی سرور خانگی مخصوص استفاده گروهی در یک مکان 

## آموزش راه‌اندازی Home Server با VPN مرکزی
شما در پایان این آموزش توانایی راه‌اندازی یک Home Server با امکانات زیر را خواهید داشت:
-VPN Server (Xray, Sing-Box, OpenVPN, WireGuard)
-Media Center (DLNA/Plex/Emby)
-Home Cloud/NAS
-MultiWAN
-Ad Blocker
-Docker

[Home Server](https://threadreaderapp.com/thread/1757862582717759721.html)

[آموزش راه‌اندازی Home Server با VPN مرکزی(قسمت دوم)](https://threadreaderapp.com/thread/1758165072625451522.html)

[راه‌اندازی Home Server با VPN مرکزی – قسمت ۳](https://ivpn.pro/openwrt/how-to-deploy-home-server-with-built-in-vpn/)

[نصب و راه‌اندازی OpenWrt روی کامپیوتر و رزبری با یک کارت شبکه](https://ivpn.pro/openwrt/how-to-install-openwrt-on-a-pc-or-raspberry-with-one-ethernet-port/)

[وبلاگ کوین](https://ivpn.pro/)


[راه‌اندازی Home Server با VPN مرکزی – قسمت ۶ – راه‌اندازی DLNA Server و Share Drive](https://ivpn.pro/openwrt/how-to-install-dlna-server-on-openwrt/)


تو این ویدیو نصب وطریقه راه اندازی سرور vpn خونگی روی دار هست رو توضیح دادم اسم این برنامه v2raya هست که میتونید کانفیگ های v2ray های خودتون رو بهش اضافه کنید تا اعضای خانواده بهش متصل بشن

[ سرور vpn خونگی خودتو روی داکر نصب کن با پنل v2raya راحت فیلترینگ رو دور بزن ](https://www.youtube.com/watch?v=qNLS590GrBg)



قسمت ۸ از سری آموزش‌های
"راه‌اندازی Home Server با VPN مرکزی"
منتشر شد:

نصب و راه‌اندازی Plex روی OpenWrt


[راه‌اندازی Home Server با VPN مرکزی – قسمت ۸ – نصب و راه‌اندازی Plex روی سرور خانگی OpenWrt](https://ivpn.pro/openwrt/how-to-install-plex-on-openwrt/)


 "راه‌اندازی WARP روی OpenWrt"

کردیت این آموزش تقدیم به مارک پشم‌فروش
@markpash


لینک آموزش:
https://ivpn.pro/openwrt/cloudflare-warp-on-openwrt/

در ساخت این آموزش از Warp Plus که مارک،  یوسف_قبادی و همکاران‌شان ساخته‌اند؛ استفاده شده است.


["راه‌اندازی WARP روی OpenWrt"](https://x.com/kevinzakarian/status/1795868295767138396)


[این OpenWrt چیه و به چه درد می‌خوره؟](https://threadreaderapp.com/thread/1796471460887965714.html)

## کنسول بازی

[ اشترک گذاری فیلترشکن رو کنسول با کمک برنامه Hiddify با استتفاده از warp بصورت رایگان ](https://www.youtube.com/watch?v=ZIOuMJGXr-Q)

## OpenWrt

عزیزانی که OpenWrt و PassWall 2 دارند، از طریق SSH با ۳ خط دستور زیر PassWall 2 را آپدیت کنید.
از پنل Luci و منوی System\Software امکان آپدیت نیست!

```
wget https://github.com/xiaorouji/openwrt-passwall2/releases/download/1.28-1/luci-23.05_luci-app-passwall2_1.28-1_all.ipk
opkg install luci-23.05_luci-app-passwall2_1.28-1_all.ipk
opkg update
```

رای سرور خانگی ما از سیستم‌عامل OpenWrt استفاده می‌کنیم و برای عبور از فیلترینگ اپ PassWall 2 رو روی OpenWrt نصب می‌کنیم. آپدیت‌ها از درون خود پنل OpenWrt انجام میشه ولی در مورد این آپدیت باید به سرور خونگی (همون OpenWrt) ارتباط SSH بزنیم و آپدیت رو انجام بدیم.

## Mikro tik

[اتصال با روش میکروتیک](https://www.youtube.com/watch?v=d2ou-XCLr4g)

[ آموزش نصب و راه اندازی پنل سنایی در میکروتیک | نصب Pihole در میکروتیک ](https://www.youtube.com/watch?v=zSCbAHpSXa0)


آموزش راه اندازی IPv6 در میکروتیک
در این ویدیو نحوه راه اندازی و اتصال به اینترنت از طریق IPv6 را به طور کامل آموزش داده ام
آدرس IP ورژن 6 دریافت شده به صورت Public می باشد که می توان با استفاده از آن سرویس هایی مبتنی بر IPv6 را راه اندازی و استفاده نمود.
لین

[ راه اندازی IPv6 در میکروتیک ](https://www.youtube.com/watch?v=1HYwi3eYRJ0)



[نصب میکروتیک در سرور مجازی aeza](https://telegra.ph/%D9%86%D8%B5%D8%A8-%D9%85%DB%8C%DA%A9%D8%B1%D9%88%D8%AA%DB%8C%DA%A9-%D8%AF%D8%B1-%D8%B3%D8%B1%D9%88%D8%B1-%D9%85%D8%AC%D8%A7%D8%B2%DB%8C-aeza-10-28)


## تبدیل سرور اوبونتو به میکروتیک -SIXTININELEARN 

سلام رفقا توی این ویدیو قراره بهتون یاد بدم چجوری خیلی راحت سرور ابونتوی خودتون رو به میکروتیک تبدیل کنین.

[youtube](https://www.youtube.com/watch?v=pz81NiG2STE)



## sing-box-plus

داداش اگه بدونی چه‌ها کردی با میکروتیک 🤩✌️

اجرای سینگ‌باکس پلاس با کانتاینر میکروتیک 🫶

اگه توی لاگها دقت کنی می‌بینی که اسکن کرده و ip تمیز پیدا کرده، دمت گرم 🙏

Cloudflare IP Scanner
TLS Fragmentation


https://github.com/kyochikuto/sing-box-plus

یک ریپوزیتوری جدید دارم در مورد سینگ باکس

https://github.com/kyochikuto/sing-box-plus

  @0xKyochikuto
  ,  @Eagle_1157
 
دارند بر همین اساس توسعه می دهند.

Cloudflare IP Scanner
Cloudflare WARP blocking bypass
TLS Fragmentation

به سینگ باکس این موارد رو اضافه کردند که حالا از همین روش میشه توی میکروتک هم استفاده کرد.


## ✅ نصب Emby روی OpenWrt

- مشابه Plex، مدیا سروری برای OpenWrt
- بدون حساسیت به IP ایران
- نصب سریع و آسان
- بدون محدودیت پخش در کلاینت
- برای انواع دیوایس‌ها از آیفون تا XBox.

لینک آموزش:
https://ivpn.pro/openwrt/how-to-install-emby-on-openwrt/


https://x.com/kevinzakarian/status/1839695617913765960


## نحوه تبدیل سرور اوبونتو به میکروتیک و نصب پنل X-UI

 یه آموزش رکورد کردم امیدوارم خوشتون بیاد - تبدیل سرور اوبونتو به میکروتیک و نصب پنل ثنایی بدون نشت dns
صفر تا صد


فقط من یادم رفت داخل ویدئو اشاره کنم که کانتینر فقط روی روتر های دارای سی پی یو ARM -ARM64 -X86-64  نصب میشه و از روتر او اس ورژن ۷.۷ به بالا اضافه شده .
امکانات خوبی رو میتونید از داکر ریجستری داخلش داشته باشید .
 برای منزل خودتون هم حتما باید آی پی پابلیک داشته باشید تا بتونید از بیرون به روتر خودتون وصل بشید  این پشنهاد منه که میتونید با خرید یک روتر HAP AX 3 میکروتیک که یک گیگ رم داره دقیقا مشابه همین سرور کارتون رو راه میندازه. 
در آینده ویدئو های جالب تری رو سعی میکنم آماده کنم در همین خصوص که کمکی به مردم خودم کرده باشم . کانتینر های جالبی هست که به کارتون میاد .
 ضمن اینکه تو این سروری که تست کردیم حدودا 3 یا 4 تا کانتینر میتونید داشته باشید .


https://www.youtube.com/watch?v=ZwA4ve8q-wI


##  نصب میکروتیک روی سرور مجازی Aeza - Mikrotik Chr Aeza vps 

در تکمیل ویدیوهای  آموزشی مربوط به میکرویتک با تبدیل سرور centos 7  از سایت Aeza در خدمتتون هستم

https://www.youtube.com/watch?v=JySeoXiCt60


##  نصب Pihole در میکروتیک -استفاده ازلینک اصلی سنایی - ثنایی ورژن جدید نصب کامل -Mikrotik Chr 

این سری سنایی رو از لینک اصلی نصب مردم و سرتیفیکیت هم از داخل پنل گرفتم که امکانات خوبی رو جدیدا اضافه کردن

https://www.youtube.com/watch?v=xtm6FwYChV0