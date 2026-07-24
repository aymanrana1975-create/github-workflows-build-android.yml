# بوابة الأسئلة بلس — بناء AAB في السحابة

## ▶️ الاستخدام:

1. فك ضغط هذا الملف في جذر مستودع GitHub الخاص بك
   (سيُنشأ مجلد .github/workflows/ تلقائياً)

2. ارفع الكود:
   git add .
   git commit -m "add cloud build"
   git push

3. افتح GitHub → تبويب Actions → "Build Android AAB"

4. اضغط "Run workflow" وانتظر ~6 دقائق

5. نزّل الملف من قسم Artifacts:
   quizgate-plus-aab.zip
   (يحتوي على app-release.aab)

6. ارفع app-release.aab إلى Google Play Console ✅

## 📦 النتيجة:
- اسم الحزمة: sa.quizgate.questions
- الإصدار: 1.0.0
- نوع الملف: .aab (Android App Bundle)

## ⚠️ للنشر الرسمي:
استخدم keystore ثابت — راجع التعليقات في نهاية ملف
.github/workflows/build-android.yml
