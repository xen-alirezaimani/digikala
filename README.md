# پروژه کلون بکند دیجیکالا

### نام و نام خانوادگی: علیرضا ایمانی
### استاد: علیرضا جمیری
### دانشگاه آزاد اسلامی واحد مرند
</br>

## توضیحات پروژه

این پروژه فقط شامل بکند است و بخش گرافیکی ندارد.</br>
بعد از راه نصب و راه اندازی، می توان logic و API endpoint ها را امتحان کرد.</br>
بخشی از پروژه در زمان قطعی اینترنت و با میرور های داخلی پکیج ها نصب شده و توسعه یافته پس احتمال تداخل در ورژن ها وجود دارد.</br>


## پیش نیاز ها
[Node.js, npm](https://nodejs.org/en/download) </br>
[mysql](https://dev.mysql.com/downloads/file/) </br>
[Postman](https://www.postman.com/downloads/?forceOS=windows) or [Insomnia](https://insomnia.rest/download) </br>

## راه اندازی و اجرا
بعد از دانلود یا کلون ریپوزیتوری، پروژه را با vsCode باز کنید و به روت پروژه که package.json در آن وجود دارد بروید و ترمینال را باز کنید.
با زدن دستور ``npm i`` پکیح ها و وابستگی ها را دانلود کنید.<br/>
ممکن است برخی پکیح ها مانند (dotenvx, nodemon) نصب نشوند، آنها را بصورت (dependency) نصب کنید. </br>
در روت پروژه یک فایل با نام (.env) ایجاد کنید و در داخل آن محتوای پایین را قرار بدهید (ممکن است متغیر های محیطی شما متفاوت باشد) </br>
``
DATABASE_HOST="localhost"
DATABASE_PORT=3306
DATABASE_NAME="digikala"
DATABASE_USER_NAME="Alireza"
DATABASE_PASSWORD="admin"
ACCESS_TOKEN_SECRET="fkedsjagkojsadkolgjklrwdajgiowerh3265236jksdfvgbg"
REFRESH_TOKEN_SECRET="kjldgajklgdsjklaghjdsioakhgruieod8903425"
ACCESS_TOKEN_SECRET="wrkldafhygjyioeprwujti9u4u358okyg3j4koj"
``
</br>
به (mysql workbrenck) را باز کنید و در آن یک دیتابیس با نام بالا ایجاد کنید.</br>
حالا با دستور (``npm run dev``) پروژه را اجرا کنید. </br>
یک نرم افزار تست (api) که در بالا لینک دانلود آنها وجود دارد به پروژه متصل شوید و api ها را بررسی کنید و با دیتابیس خود ارتباط برقرار کنید.
