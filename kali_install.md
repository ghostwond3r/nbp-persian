# نحوه نصب VirtualBox و Kali Linux در ویندوز - گام به گام

## هشدار: لینک‌های زیر فایل‌ها را به‌طور خودکار دانلود می‌کنند، بنابراین فقط از جایی که می‌خواهید آن را نصب کنید، روی آن کلیک کنید!

1- دانلود:

    * For Windows: https://download.virtualbox.org/virtualbox/6.1.38/VirtualBox-6.1.38-153438-Win.exe
    * For Linux (Debian 11): https://download.virtualbox.org/virtualbox/6.1.38/virtualbox-6.1_6.1.38-153438~Debian~bullseye_amd64.deb

2- بسته افزونه را دانلود کنید:

    * https://download.virtualbox.org/virtualbox/6.1.38/Oracle_VM_VirtualBox_Extension_Pack-6.1.38.vbox-extpack

3- دانلود کالی لینوکس:

    * https://kali.download/virtual-images/kali-2022.3/kali-linux-2022.3-virtualbox-amd64.7z

4- باید زیر سیستم ویندوز را برای لینوکس فعال کنید. برای انجام این کار، "ویژگی های ویندوز" را در نوار جستجوی منوی ویندوز تایپ کنید، سپس باز کنید، به پایین بروید و کادر "Windows Subsystem for Linux" را علامت بزنید، سپس ذخیره کنید، خارج شوید و کامپیوتر خود را مجددا راه اندازی کنید.

![photo_2022-06-10_14-44-13](https://user-images.githubusercontent.com/64184513/175776446-b373d0e5-4672-471f-a78a-93e0f2891313.jpg)

5- جعبه مجازی را باز کنید و دستورالعمل نصب را دنبال کنید.

6- در منو روی file و سپس تنظیمات کلیک کنید و به پسوند بروید. سپس بسته الحاقی را که قبلا دانلود کرده اید اضافه می کنید.

![8](https://user-images.githubusercontent.com/64184513/175776890-4f44fdbd-97ec-4bf9-bcf1-8db3aafa4459.jpg)


7- مجددا در منو روی فایل کلیک کنید، سپس یک دستگاه را وارد کنید

![1](https://user-images.githubusercontent.com/64184513/175776398-7038d85a-a306-4c4c-ad89-325b5c938383.jpg)

8- کالی را که دانلود کردید (فایل ova) انتخاب کنید و روی ادامه کلیک کنید.

![2](https://user-images.githubusercontent.com/64184513/175776400-a41767db-3686-4a3b-b978-bf136286f9f0.jpg)

9- روی "وارد کردن" کلیک کنید

![3](https://user-images.githubusercontent.com/64184513/175776402-4eff95b8-9785-47e1-9877-67df34d808e2.jpg)

10- "پیکربندی" کالی جدید خود را باز کنید و در حالت ایده آل حداقل 2 سی پی یو برای کارایی + 4 گیگابایت رم قرار دهید. (از خط قرمز عبور نکنید)

![4](https://user-images.githubusercontent.com/64184513/175776404-1eb16270-54d3-4d42-9741-2d2bbb0ce29b.jpg)
![5](https://user-images.githubusercontent.com/64184513/175776405-1227974e-c82f-4272-9b58-8163c14687e0.jpg)

11- در قسمت شبکه، اتصال را روی آداپتور پل تنظیم کنید و آدرس مک را تصادفی کنید.

![7](https://user-images.githubusercontent.com/64184513/175776409-de0300c0-4908-4e94-ac28-6ac0e980f2b0.jpg)

12- از پنل تنظیمات خارج شوید.

13- را شروع کنید، به صفحه ورود خواهید رسید:
نام کاربری: kali
رمز عبور: kali

## شروع با Kali Linux - گام به گام

- اکنون که در دستگاه جدید خود هستید، روی منو کلیک کنید و یک ترمینال ریشه (قرمز) باز کنید.
رمز عبور: kali

این دستور را تایپ کنید؛
```
apt update && apt upgrade -y
```

- حالا ما در این صفحه ادامه می دهیم!

https://github.com/NeverWonderLand/no-more.git
