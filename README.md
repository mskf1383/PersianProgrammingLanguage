<div dir="rtl">
  
# زبان برنامه نویسی فردوسی
یک زبان برنامه نویسی ساده؛ نوشته شده با پایتون


## روش استفاده
برای تفسیر دستور زیر را در خط فرمان وارد کنید:
</div>

```
python3 interpreter.py <آدرس فایل>
```

<div dir="rtl">
  
توجه: فایل باید دارای پسوند fd. باشد

برای مثال:
</div>

```
python3 interpreter.py examples/helloworld.fd
```
<div dir="rtl">

اگر در حال حاضر فایلی ندارید، می‌توانید به طور زنده در ترمینال برنامه نویسی کنید:
</div>
  
```
python3 interpreter.py
```
<div dir="rtl">


## مثال‌ها
### سلام دنیا


`
"سلام، دنیا!"
`
</div>
<div dir="rtl">
  
### چاپ
</div>

```plain
"چاپ کن "سلام دنیا
```
  <div dir="rtl">
  
### شرط‌ها
</div>

```plain
اگر 12 برابر 10 + 2 باشد آنگاه "ده با دو میشود دوازده" وگرنه "ده با دو نمیشود دوازده"
```
<div dir="rtl">
    
### ورودی
</div>

```plain
عدد = عددگیر
نام = ورودی
```
<div dir="rtl">

### کامنت‌ها
</div>

```plain
# این یک کامنت است
# کامنت ها برنامه را تغییر نمیدهند
```
<div dir="rtl">

### شمارنده
</div>

```plain
اگر 5 شمارنده 10 باشد آنگاه "درسته" وگرنه "غلطه"
```
<div dir="rtl">

### تابع‌ها
</div>

```plain
زوج_فرد یعنی اگر 2 شمارنده عدد باشد آنگاه "زوج" وگرنه "فرد"

عدد = 15
زوج_فرد را اجرا کن
```
<div dir="rtl">
  
### عملگرها
</div>

```plain
اول = 10
دوم = 2

جمع = اول + دوم
تفریق = اول - دوم
ضرب = اول * دوم
تقسیم = اول / دوم
```

* * *
<div dir="rtl">

**این مفسر به وسیله [SLY](https://sly.readthedocs.io/en/latest/sly.html) ساخته شده است**
</div>
