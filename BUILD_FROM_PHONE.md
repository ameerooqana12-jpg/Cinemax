# CineMax من الجوال فقط — الخطوات

## 1) فك الضغط
نزّل `CineMax_ready_for_phone_build.zip` وفك الضغط على هاتفك.

## 2) GitHub
أنشئ Repository جديدًا باسم `cinemax` ثم ارفع محتويات المجلد، وليس ملف ZIP نفسه.

## 3) Codemagic
سجّل الدخول إلى Codemagic واربط GitHub، ثم اختر Repository الخاص بـ CineMax.

## 4) Workflow
اختر Workflow الموجود في `codemagic.yaml` واسمه:
`CineMax Android`

الـ workflow ينفذ تلقائيًا:
- إنشاء ملفات Android
- تنزيل حزم Flutter
- بناء APK
- بناء AAB

## 5) التجربة
بعد نجاح Build، افتح Artifacts ونزّل ملف APK وثبّته على هاتفك.

## 6) Google Play لاحقًا
للنشر النهائي ستحتاج AAB وتوقيع Android. لا تشارك ملفات/كلمات مرور التوقيع مع أي شخص.

### ملاحظة
إذا كان رفع مجلد كامل إلى GitHub من المتصفح على الهاتف مزعجًا، أخبرني وسأعطيك طريقة بديلة تعتمد على رفع الملفات من الهاتف خطوة خطوة.
