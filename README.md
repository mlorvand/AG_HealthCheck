# 🧩 SQL Server Always On Availability Group Monitor

![SQL Server](https://img.shields.io/badge/SQL%20Server-Always%20On-blue?logo=microsoftsqlserver)
![Language](https://img.shields.io/badge/Language-TSQL-purple)
![Monitoring](https://img.shields.io/badge/Category-Monitoring-yellow)
![License](https://img.shields.io/badge/License-MIT-green)
![Author](https://img.shields.io/badge/Author-Mahdi%20Lorvand-orange)

A professional T-SQL script to monitor the health, synchronization state, and performance of your **SQL Server Always On Availability Groups** in real time.

---

## 🌐 Languages
- 🇮🇷 [فارسی](#-نسخه-فارسی)
- 🇬🇧 [English](#-english-version)
- 🇸🇦 [العربية](#-الإصدار-العربي)

---

## 🇮🇷 نسخه فارسی

### 🧠 معرفی  
این اسکریپت یک کوئری پیشرفته SQL برای مانیتورینگ وضعیت **Availability Groups** در SQL Server است.  
با اجرای آن می‌توانید اطلاعات دقیقی از وضعیت Replicaها، همگام‌سازی، سلامت ارتباط و نرخ انتقال لاگ‌ها مشاهده کنید.

---

### 🚀 ویژگی‌ها  
✅ نمایش نام گروه (AG Name) و Replica  
✅ بررسی وضعیت همگام‌سازی و سلامت (Health & Sync State)  
✅ مشاهده نرخ ارسال و بازپخش لاگ‌ها (Log Send / Redo Rate)  
✅ نمایش LSNها و زمان آخرین Commit  
✅ سازگار با تمامی نسخه‌های SQL Server دارای Always On

---

### 🧾 نحوه استفاده  
1. وارد SQL Server Management Studio شوید.  
2. کوئری را در سطح Instance اجرا کنید.  
3. نتیجه در لحظه وضعیت Replicaها و Databaseها را نمایش می‌دهد.  

> 🔒 نیاز به دسترسی `VIEW SERVER STATE` دارد.

---

### 🧑‍💻 نویسنده  
**مهدی لوروند (Mahdi Lorvand)**  
💼 Helpdesk & VoIP Expert | SQL Learner | IT Enthusiast  
📧 [mehdilorvand92@gmail.com](mailto:mehdilorvand92@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/mehdi-lorvand-08aa151a4/)

---

## 🇬🇧 English Version

### 🧠 Overview  
This T-SQL script provides detailed monitoring for **SQL Server Always On Availability Groups**, helping DBAs and engineers track synchronization, health, and performance metrics in real time.

---

### 🚀 Features  
✅ Display Availability Group and Replica names  
✅ Check synchronization & health status  
✅ Monitor log send/redo rates and queue sizes  
✅ View important LSNs (commit, hardened, redo)  
✅ Fully compatible with all SQL Server editions supporting Always On

---

### 🧾 How to Use  
1. Open **SQL Server Management Studio (SSMS)**.  
2. Run the script at the **instance level** (not per database).  
3. Review the live results to identify any lag or sync issues.

> ⚙️ Requires `VIEW SERVER STATE` permission.

---

### 🧑‍💻 Author  
**Mahdi Lorvand**  
💼 Helpdesk & VoIP Expert | SQL Learner | IT Enthusiast  
📧 [mehdilorvand92@gmail.com](mailto:mehdilorvand92@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/mehdi-lorvand-08aa151a4/)

---

## 🇸🇦 الإصدار العربي

### 🧠 المقدّمة  
هذا السكربت بلغة SQL يساعدك على مراقبة **مجموعات التوافر (Availability Groups)** في SQL Server.  
يوفّر تفاصيل دقيقة حول النسخ (Replicas) وحالة المزامنة والصحة وسرعة إرسال السجلات.

---

### 🚀 المميزات  
✅ عرض أسماء مجموعات التوافر والنسخ  
✅ التحقق من حالة المزامنة والصحة  
✅ عرض معدلات الإرسال وإعادة التشغيل (Redo)  
✅ عرض قيم الـ LSN المهمة وزمن آخر عملية Commit  
✅ متوافق مع جميع إصدارات SQL Server التي تدعم Always On  

---

### 🧾 طريقة الاستخدام  
1. افتح **SQL Server Management Studio**.  
2. شغّل الاستعلام على مستوى الخادم (Instance).  
3. شاهد النتائج لمراقبة حالة المزامنة والأداء مباشرةً.  

> 🔐 يتطلب صلاحية `VIEW SERVER STATE`.

---

### 🧑‍💻 المؤلف  
**مهدي لورفند (Mahdi Lorvand)**  
💼 خبير دعم فني وVoIP | متعلّم SQL | مهتم بتقنية المعلومات  
📧 [mehdilorvand92@gmail.com](mailto:mehdilorvand92@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/mehdi-lorvand-08aa151a4/)

---

## 🪪 License
MIT License — Free to use, modify, and share with attribution.

---

## ⭐️ Support
If this script helped you, please give it a ⭐️ on GitHub or share it with your DBA friends!
