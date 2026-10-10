# apk-factory
<div dir="rtl">

# apk-factory

مستودع البناء الذي يستخدمه تطبيق «مصنع التطبيقات». لا تعدّل فيه شيئاً يدوياً.

عند ضغط **ابنِ APK** في التطبيق، يحدّث الملفين `www/index.html` و`capacitor.config.json`، ثم يشغّل `build-apk.yml`. بعد انتهاء البناء يظهر ملف APK في قسم **Releases** بوسم باسم `run-` متبوعاً برقم التشغيل.

## المطلوب

- أن تكون **Actions** مفعّلة على المستودع.
- رمز GitHub بصلاحيتي Contents وActions بمستوى Read and write على هذا المستودع.
- أن يُرفع مجلد `.github` مع باقي الملفات.

</div>
