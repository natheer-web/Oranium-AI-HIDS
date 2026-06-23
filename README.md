# Oranium-AI-HIDS
# ORANIUM AI-Powered HIDS 🛡️
# نظام أورانيوم الذكي لكشف التسلل 🛡️

A lightweight, automated Host-based Intrusion Detection System (HIDS) for Linux environments.
نظام خفيف ومؤتمت لكشف التسلل (HIDS) مخصص لبيئات أنظمة لينكس.

This tool is designed to monitor Linux authentication logs (`auth.log`) in real-time.
تم تصميم هذه الأداة لمراقبة سجلات المصادقة في لينكس (`auth.log`) بالوقت الفعلي.

It instantly detects unauthorized access attempts, such as SSH brute-force attacks.
تقوم باكتشاف محاولات الوصول غير المصرح بها فوراً، مثل هجمات التخمين على منفذ SSH.

The system uses Google's Gemini AI to analyze the threat and sends an immediate incident report via Telegram.
يستخدم النظام ذكاء جوجل (Gemini) لتحليل التهديد ويرسل تقرير فوري بالحادثة عبر تيليجرام.

## Features
## المميزات

* **Real-time Log Monitoring:** Continuous background scanning of system logs.
* **مراقبة السجلات بالوقت الفعلي:** فحص مستمر لسجلات النظام في الخلفية.

* **AI Threat Analysis:** Integrates with Generative AI (Gemini) to provide intelligent summaries of security events.
* **تحليل التهديدات بالذكاء الاصطناعي:** يدمج الذكاء الاصطناعي التوليدي لتقديم ملخصات ذكية للأحداث الأمنية.

* **Instant SOC Alerts:** Delivers automated alerts directly to a Telegram bot for rapid response.
* **تنبيهات فورية لمركز العمليات الأمنية:** يرسل تنبيهات مؤتمتة مباشرة إلى بوت تيليجرام لضمان الاستجابة السريعة.

* **Fault-Tolerant Architecture:** Built-in error handling ensures the script survives network drops.
* **بنية مقاومة للأخطاء:** برمجة تتضمن معالجة الأخطاء لضمان استمرار السكربت حتى عند انقطاع الشبكة.

## Prerequisites
## المتطلبات الأساسية

* A Linux-based OS (e.g., Ubuntu/Debian).
* نظام تشغيل مبني على لينكس (مثل أوبونتو/ديبيان).

* Python 3 installed on the server.
* تثبيت بايثون 3 على السيرفر.

* The `requests` library.
* مكتبة `requests`.

```bash
pip install requests
