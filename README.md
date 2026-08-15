# Hosting Support Lab

## معرفی پروژه

این پروژه یک محیط یادگیری و مستندسازی عملی برای آشنایی با مفاهیم پشتیبانی هاستینگ، دامنه، DNS، وب‌سرور و عیب‌یابی مشکلات رایج وب‌سایت است.

هدف از این پروژه بررسی فرآیندهایی است که در پشتیبانی فنی هاستینگ برای تشخیص و رفع مشکلات کاربران استفاده می‌شود.

---

## موارد بررسی شده

### DNS

- بررسی تبدیل Domain به IP
- آشنایی با رکوردهای DNS
- بررسی رکورد MX برای سرویس ایمیل
- تست DNS Resolverهای مختلف

ابزارهای استفاده شده:

- nslookup

---

### Network Troubleshooting

بررسی ارتباط اولیه با سرور:

- بررسی دسترسی شبکه
- بررسی Packet Loss
- مشاهده زمان پاسخ

ابزار:

- ping

---

### HTTP / Web Server Troubleshooting

بررسی پاسخ وب‌سرور و Status Codeها:

- HTTP 200
- HTTP 301 Redirect
- بررسی Header پاسخ

ابزار:

- curl

---

### HTTPS / SSL

بررسی:

- اتصال HTTPS
- پورت 443
- TLS Handshake
- مفاهیم اولیه SSL Certificate

ابزار:

- curl

---

## رویکرد عیب‌یابی

در بررسی مشکلات وب‌سایت، ابتدا لایه‌های مختلف بررسی می‌شوند:

Domain
↓
DNS
↓
Network
↓
Web Server
↓
Application
↓
Database
↓
SSL

---

## هدف توسعه پروژه

در مراحل بعدی موارد زیر اضافه خواهند شد:

- کار با کنترل پنل‌های هاستینگ مانند cPanel و DirectAdmin
- مدیریت فایل و دیتابیس
- WordPress Troubleshooting
- آشنایی با Linux Server
- Deployment و Docker# hosting_support_lab
