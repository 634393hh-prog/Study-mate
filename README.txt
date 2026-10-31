StudyMate Offline PWA

الملفات:
- index.html: التطبيق
- sw.js: التخزين للعمل دون إنترنت
- manifest.webmanifest: تعريف التطبيق
- icon-192.png و icon-512.png: الأيقونات

مهم: لا يمكن تفعيل Service Worker من ملف HTML محلي مباشرة. يجب رفع هذه الملفات إلى استضافة HTTPS مجانية (مثل GitHub Pages). افتح الرابط مرة واحدة بالإنترنت في Safari، انتظر اكتمال التحميل، ثم Share > Add to Home Screen. بعد ذلك افتح التطبيق مرة أخرى وهو متصل بالإنترنت حتى يكتمل التخزين المؤقت، ثم اختبره بوضع الطيران.
