# Flask DevOps Example

این پروژه نمونه‌ای ساده از یک اپلیکیشن Flask است که برای تمرین DevOps با Git، CI/CD و Docker ساخته شده.

## اجرا روی سیستم محلی

```bash
docker build -t flask-devops .
docker run -p 5000:5000 flask-devops
