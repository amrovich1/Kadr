# Kadr
كاميرا بتوجّهك قبل ما تصوّر. Kotlin + Compose + CameraX + ML Kit.

التشغيل: افتح المجلد في Android Studio (Koala 2024.1.1 أو أحدث) → Sync → Run على جهاز حقيقي (الحساسات والكاميرا).
- minSdk 29، الاتجاه Portrait فقط حالياً.
- ضبط عتبات التوجيه: `guidance/GuidanceEngine.kt` (الثوابت أعلى الملف).
- ضبط توقيت الرسائل: `guidance/GuidanceThrottler.kt`.
- أيقونة المتجر: `icon/kadr_icon_512.png` (والمصدر SVG).

## البناء على GitHub
ارفع المشروع على فرع main ← تبويب Actions ← "Build APK" ← افتح آخر تشغيل ← نزّل `Kadr-debug-apk` من Artifacts (ملف zip جواه app-debug.apk).
الـ APK ده debug (موقّع بمفتاح debug تلقائي) ويتثبّت مباشرة على الموبايل بعد السماح بالتثبيت من مصدر غير معروف.
