# DNS Basics

## DNS چیست؟

DNS کمک می‌کند وقتی یک دامنه مثل `google.com` را وارد می‌کنیم، آدرس سروری که باید به آن وصل شویم پیدا شود.

## A Record

A Record دامنه را به یک آدرس IPv4 وصل می‌کند.

مثلاً:

`example.com → 192.0.2.10`

## AAAA Record

AAAA Record برای IPv6 استفاده می‌شود.

## CNAME

CNAME یک نام دامنه را به یک نام دامنه دیگر ارجاع می‌دهد.

مثلاً:

`www.example.com → example.com`

## MX Record

MX مربوط به ایمیل دامنه است و مشخص می‌کند ایمیل‌های یک دامنه باید به کدام Mail Server ارسال شوند.

## تست با nslookup

برای بررسی DNS از دستور `nslookup` استفاده کردم.

مثلاً:

```cmd
nslookup google.com
