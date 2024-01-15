<div dir=rtl>

<h1>PS5-Game-Info</h1>
<img src="images/Screenshot 2024-01-14 205102.png">

## این برنامه می تواند اطلاعات بازی دامپ گرفته شده PS5 را به شما نشان دهد

## امکانات

- خواندن فایل param.json و نشان دادن آن (شاید **نه همه** بازی ها, باید تست شود)
- Detect whether the eboot.bin is fake or not (It just check the eboot.bin file not others)
- Get the size of the game folder (Its HARD TO READ From Properties)

## نکته ۱: It can't show you the PKG files. Neither PS4/5 PKG, Only dump file of PS5 games (not ps4)
## نکته ۲: این برنامه در مرحله تست هستش پس اگه مشکلی پیدا کردین، به من در <a href="https://x.com/sinajet1">X (Twitter)</a> اطلاع بدین

# نحوه استفاده:
### شما باید مسیر پوشه بازیتون رو انتخاب کنین, مسیر پوشه بازیتون در واقع همون مسیری هست که فایل eboot.bin درونش قرار داره
### شما چهار راه برای انتخاب کردن پوشه بازیتون دارین:
۱- روی آیکون پوشه در برنامه بزنین و پوشه بازی رو انتخاب کنین.</br>
2- مسیر پوشه بازی رو در فضای خالی کپی کنین و ENTER بزنین</br>
3- منوی File رو در برنامه باز کنین، "Open Game Folder" رو انتخاب کنین و مسیر بازی رو مشخص کنین</br>
4- وارد پوشه بازی بشید (جایی که eboot.bin هستش), روی فایلی کلیک راست کنید (مثل eboot.bin یا eboot.bin.esbak یا contentids.json) "Open with" رو انتخاب کنید، و فایل را با PS5 Game Info باز کنید</br>
## نکته ۳: اگه از روش چهارم استفاده میکنین، فایل EXE رو حذف و یا منتقل نکنین
## فایل EXE رو از <a href="https://github.com/sinajet/PS5-Game-Info/releases/">اینجا</a> دانلود کنین
### شما میتونین که از کد من در هر جایی استفاده کنین اما یادتون نره که من رو منشن کنین ;)
### همچنین، اگه به این برنامه اطمینان ندارین میتونین با استفاده از این سورس خودتون خروجی بگیرین
### این برنامه با Qt Designer و PyQt6 ساخته شده

## منابع
<a href="https://www.psxhax.com/threads/ps4pkgviewer-a-ps4-pkg-viewer-by-lman-theleecherman.4784/">PS4 PKG Viewer By LMAN</a><br>
<a href="https://www.psdevwiki.com/ps5/Param.json">Param.json page on psdevwiki</a><br>
