## ✨ Project Overview | پروجیکٹ کا جائزہ ✨

The Hanafi Purity Tracker is a client-side web application designed to assist Muslim women following the Hanafi (Deoband) school of Fiqh in accurately tracking and calculating their periods of menstruation (Haidh), non-menstrual bleeding (Istihadah), and purity (Tuhr). This single-file application leverages IndexedDB for persistent local data storage, ensuring privacy and offline functionality. | حنفی طہارت ٹریکر ایک کلائنٹ سائیڈ ویب ایپلیکیشن ہے جسے حنفی (دیوبند) فقہ کی پیروی کرنے والی مسلم خواتین کی حیض، استحاضہ، اور طہارت کے دنوں کو درست طریقے سے ٹریک اور شمار کرنے میں مدد کرنے کے لیے ڈیزائن کیا گیا ہے۔ یہ سنگل فائل ایپلیکیشن مقامی ڈیٹا سٹوریج کے لیے IndexedDB کا استعمال کرتی ہے، جو رازداری اور آف لائن فعالیت کو یقینی بناتی ہے۔

---

## 🎯 Features | خصوصیات 🎯

*   **🌍 Bilingual Support (Urdu & English)** | **دو لسانی معاونت (اردو اور انگریزی)**
    *   Switch seamlessly between Urdu (default) and English for all UI text. | تمام UI ٹیکسٹ کے لیے اردو (پہلے سے طے شدہ) اور انگریزی کے درمیان آسانی سے سوئچ کریں۔
*   **🗓️ Comprehensive Fiqh Engine** | **جامع فقہ انجن**
    *   Strict adherence to Hanafi (Deoband) jurisprudence for Haidh, Istihadah, and Tuhr calculations. | حیض، استحاضہ اور طہارت کے حسابات کے لیے حنفی (دیوبند) فقہ کی سختی سے پابندی۔
*   **🔄 Habit ('Adah') Management** | **عادت (عادہ) کا انتظام**
    *   Automatically calculates, stores, and applies a user's Haidh and Tuhr habits based on valid cycles. | درست سائیکلوں کی بنیاد پر صارف کی حیض اور طہارت کی عادات کا خود بخود حساب، ذخیرہ اور اطلاق کرتا ہے۔
*   **📊 Intuitive Dashboard** | **بدیہی ڈیش بورڈ**
    *   Clearly displays current purity status, established habits, and context-aware action buttons. | موجودہ طہارت کی حیثیت، قائم شدہ عادات اور سیاق و سباق کے مطابق ایکشن بٹن واضح طور پر دکھاتا ہے۔
*   **✍️ Bleeding Event Logging** | **خون آنے کے واقعات کی لاگنگ**
    *   Easy logging of bleeding start and end times with date and time pickers. | تاریخ اور وقت کے انتخاب کاروں کے ساتھ خون آنے کے شروع اور اختتامی اوقات کی آسان لاگنگ۔
*   **📜 Cycle History View** | **سائیکل ہسٹری کا منظر**
    *   View a detailed, reverse-chronological list of all past cycles with their classification (Haidh/Istihadah). | تمام پچھلے سائیکلوں کی درجہ بندی (حیض/استحاضہ) کے ساتھ ایک تفصیلی، معکوس-تاریخی فہرست دیکھیں۔
*   **💾 Local Data Storage (IndexedDB)** | **مقامی ڈیٹا سٹوریج (IndexedDB)**
    *   All user data persists securely on the user's device, ensuring privacy and offline functionality. | تمام صارف کا ڈیٹا صارف کے آلے پر محفوظ طریقے سے برقرار رہتا ہے، جو رازداری اور آف لائن فعالیت کو یقینی بناتا ہے۔
*   **📦 Data Backup & Restore** | **ڈیٹا بیک اپ اور بحالی**
    *   Export and import application data (user profile and cycle history) for migration or backup purposes. | منتقلی یا بیک اپ کے مقاصد کے لیے ایپلیکیشن ڈیٹا (صارف کا پروفائل اور سائیکل ہسٹری) کو ایکسپورٹ اور امپورٹ کریں۔
*   **📱 Mobile-First & Responsive Design** | **موبائل-فرسٹ اور ریسپانسیو ڈیزائن**
    *   Built with Tailwind CSS for a clean, modern, and adaptive user interface across devices. | تمام آلات پر ایک صاف، جدید اور موافقت پذیر یوزر انٹرفیس کے لیے Tailwind CSS کے ساتھ بنایا گیا ہے۔
*   **💡 Informative Disclaimer** | **معلوماتی دستبرداری**
    *   A clear disclaimer emphasizing the app as a tool and not a substitute for scholarly or medical advice. | ایک واضح دستبرداری جو ایپ کو ایک ٹول کے طور پر زور دیتی ہے نہ کہ علمی یا طبی مشورے کا متبادل۔

---

## ⚙️ Core Logic & Jurisprudence (Hanafi School) | بنیادی منطق اور فقہ (حنفی مکتب) ⚙️

The application's calculations are meticulously implemented based on the following Hanafi Fiqh principles: | ایپلیکیشن کے حسابات درج ذیل حنفی فقہ کے اصولوں کی بنیاد پر احتیاط سے نافذ کیے گئے ہیں:

### Haidh (Menstruation) | حیض (ماہواری)
*   **Minimum Duration:** 3 complete days and nights (exactly 72 hours). | **کم از کم مدت:** 3 مکمل دن اور رات (بالکل 72 گھنٹے)۔
*   **Maximum Duration:** 10 complete days and nights (exactly 240 hours). | **زیادہ سے زیادہ مدت:** 10 مکمل دن اور رات (بالکل 240 گھنٹے)۔

### Tuhr (Purity) | طہارت (پاکیزگی)
*   **Minimum Duration:** 15 complete days (exactly 360 hours). | **کم از کم مدت:** 15 مکمل دن (بالکل 360 گھنٹے)۔
*   **Maximum Duration:** No maximum limit. | **زیادہ سے زیادہ مدت:** کوئی زیادہ سے زیادہ حد نہیں۔

### Istihadah (Non-menstrual/Irregular Bleeding) | استحاضہ (غیر ماہواری/بے قاعدہ خون)
*   Any bleeding that lasts for less than 72 hours. | کوئی بھی خون جو 72 گھنٹے سے کم رہے۔
*   Any bleeding that continues beyond 240 hours. | کوئی بھی خون جو 240 گھنٹے سے آگے جاری رہے۔
*   Any bleeding that starts before 360 hours of purity have passed since the end of the last Haidh. | کوئی بھی خون جو پچھلے حیض کے اختتام کے بعد 360 گھنٹے کی طہارت گزرنے سے پہلے شروع ہو۔

### 'Adah (Habit) | عادہ (عادت)
*   The habit is determined by the duration of the most recent valid Haidh and the subsequent valid Tuhr. This habit is used to calculate future cycles, especially when bleeding exceeds 10 days. | عادت کا تعین سب سے حالیہ درست حیض اور اس کے بعد کی درست طہارت کی مدت سے ہوتا ہے۔ یہ عادت مستقبل کے سائیکلوں کا حساب لگانے کے لیے استعمال ہوتی ہے، خاص طور پر جب خون 10 دن سے تجاوز کر جائے۔

---

## 🛠️ Technologies Used | استعمال شدہ ٹیکنالوجیز 🛠️

*   **HTML5** | **ایچ ٹی ایم ایل 5**
    *   For structuring the web application. | ویب ایپلیکیشن کو منظم کرنے کے لیے۔
*   **Tailwind CSS** | **ٹیل ونڈ سی ایس ایس**
    *   For a modern, utility-first, and responsive design. Loaded via CDN. | ایک جدید، افادیت-اول، اور ریسپانسیو ڈیزائن کے لیے۔ CDN کے ذریعے لوڈ کیا گیا ہے۔
*   **JavaScript (ES6+)** | **جاوا اسکرپٹ (ES6+)**
    *   For all application logic, calculations, and DOM manipulation. | تمام ایپلیکیشن لاجک، حسابات اور DOM ہیرا پھیری کے لیے۔
*   **IndexedDB API** | **انڈیکسڈ ڈی بی اے پی آئی**
    *   For robust, persistent client-side data storage. | مضبوط، مستقل کلائنٹ سائیڈ ڈیٹا سٹوریج کے لیے۔

---

## 🚀 How to Use | استعمال کا طریقہ 🚀

1.  **Clone the repository:** | **ریپوزٹری کلون کریں:**
    ```bash
    git clone it
    ```
2.  **Open `index.html`:** | **`index.html` کھولیں:**
    Simply open the `index.html` file in your web browser. No server setup is required! | اپنے ویب براؤزر میں صرف `index.html` فائل کھولیں۔ کسی سرور سیٹ اپ کی ضرورت نہیں!

---

## 👨‍💻 Contribution | شراکت 👨‍💻

Contributions are welcome! If you have suggestions for features, improvements, or bug fixes, please feel free to open an issue or submit a pull request. | شراکتیں خوش آئند ہیں! اگر آپ کے پاس خصوصیات، بہتری یا بگ فکسز کے لیے تجاویز ہیں، تو براہ کرم ایک ایشو کھولیں یا پل کی درخواست جمع کروائیں۔

---

## ⚖️ License | لائسنس ⚖️

This project is open-sourced under the MIT License. | یہ پروجیکٹ MIT لائسنس کے تحت اوپن سورس ہے۔