به نام خداوند جان و خرد

نام و نام خانوادگی	تاریخ آزمایش	شماره آزمایش
مینا زواری	چهارشنبه 15 اسفند	آزمایش شماره 3


عنوان: 
راه اندازی کلید به صورت پایین کش و روشن کردن لامپ با آردوینو

هدف آزمایش:
هدف از این آزمایش، طراحی و پیاده‌سازی مداری است که با استفاده از یک کلید فشاری و برد آردوینو، یک لامپ LED را روشن یا خاموش کند. در این آزمایش، کلید به صورت پایین کش (Pull-down) پیکربندی شده است.
تئوری آزمایش:
•	کلید پایین کش (Pull-down): در این پیکربندی، یک مقاومت بین پایه کلید و زمین (GND) قرار می‌گیرد. هنگامی که کلید فشرده نمی‌شود، پایه کلید به زمین متصل است و ولتاژ آن صفر ولت (LOW) است. هنگامی که کلید فشرده می‌شود، پایه کلید به ولتاژ منبع (VCC) متصل می‌شود و ولتاژ آن 5 ولت (HIGH) می‌شود.
•	برد آردوینو UNO: این برد یک میکروکنترلر است که می‌تواند ورودی‌ها را از طریق پین‌های خود دریافت کرده و خروجی‌ها را کنترل کند. در این آزمایش، پین 8 به عنوان ورودی برای کلید و پین 2 به عنوان خروجی برای لامپ LED استفاده می‌شود.
•	لامپ LED: این قطعه یک دیود نورگسیل است که با عبور جریان الکتریکی از آن، نور تولید می‌کند.
•	مقاومت: برای محدود کردن جریان عبوری از LED و جلوگیری از سوختن آن، از یک مقاومت استفاده می‌شود.

شرح مدار و قطعات مورد استفاده:
•	برد آردوینو UNO
•	یک عدد کلید فشاری
•	یک عدد لامپ LED 
•	دو عدد مقاومت (یکی برای LED و دیگری برای Pull Down) 220Ω20kΩ , 
•	سیم‌های مخابراتی
•	برد بورد

روش انجام آزمایش:
1.	اتصالات سخت افزاری: 
o	کلید فشاری را روی برد بورد قرار می دهیم.
o	پایه  (AC)کلید را به  5V برد آردوینو متصل می کنیم.
o	پایه دیگر کلید  (AD)را به پین 8 برد آردوینو متصل می کنیم.
o	یک سر مقاومت 20kΩ  را به پایه  (AD)کلید و سر دیگر آن را به زمین متصل می کنیم.
o	یک سر مقاومت   220Ωرا به زمین (GND) برد آردوینو و سر دیگر آن را به آند LED متصل می کنیم.
o	کاتد  LEDرا به پین 2 برد آردوینو متصل می کنیم.










2.	برنامه نویسی آردوینو: 
o	برنامه آردوینو IDE را باز کنید.
o	کدهای زیر را در آن وارد کنید:





نتیجه گیری:
در این آزمایش، هدف، طراحی و پیاده‌سازی مداری بود که با استفاده از یک کلید فشاری و برد آردوینو، یک لامپ LED را کنترل کند. با توجه به نتایج به دست آمده، می‌توان نتیجه گرفت که:
•	مدار طراحی شده به درستی عمل می‌کند و با فشردن کلید، لامپ LED روشن و با رها کردن آن، خاموش می‌شود.
•	پیکربندی کلید به صورت پایین کش (Pull-down) به درستی انجام شده و سیگنال ورودی به آردوینو به درستی تشخیص داده می‌شود.
•	کدهای نوشته شده برای آردوینو به درستی عمل کرده و خروجی مورد نظر را تولید می‌کنند.
•	این آزمایش نشان می‌دهد که می‌توان با استفاده از برد آردوینو و قطعات الکترونیکی ساده، مدارهای کاربردی و مفیدی را طراحی و پیاده‌سازی کرد.







[pull down.pdf](https://github.com/user-attachments/files/19659005/pull.down.pdf)
![pull down](https://github.com/user-attachments/assets/706ab1df-e04f-400f-9b77-99916d26fe37)


https://github.com/user-attachments/assets/085ce067-dbc3-4e3e-9e38-30614cb4c8c7


