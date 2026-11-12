# ميزان التقصير - مشروع أندرويد

## البناء على GitHub (دون تثبيت شيء)
1. أنشئ مستودعاً جديداً على github.com (خاص أو عام) وارفع محتويات هذا المجلد إليه.
2. افتح تبويب Actions ثم "Build APK" ثم Run workflow.
3. بعد دقائق نزّل الملف mizan-altaqseer-apk من قسم Artifacts، وفيه app-debug.apk.
4. انقل الملف إلى الهاتف وثبّته (يلزم السماح بالتثبيت من مصدر غير معروف).

## البناء بـ Android Studio
افتح المجلد android ثم Build > Build APK(s).

## تعديل التطبيق
عدّل www/index.html ثم نفّذ: npm ci && npx cap sync android
