# RashSpeak Studio 2.6 — المصدر المحدث

[تنزيل مصدر الأداة 2.6 وتعليمات تشغيلها](https://raw.githubusercontent.com/ClearDataIQ/Rashspeak/main/RashSpeak_Studio_2.6.zip) · [الوظائف المنجزة والقيود والإعداد](SOURCE_DIRECTOR_2.6_AR.md) · [نتائج الاختبارات](TEST_RESULTS_2.6.txt)

**الفيديوهات السابقة أدناه مرفوضة من المالك ولا تمثّل مونتاجًا مقبولًا. لم ينتج فيديو نهائي مصحح بعد: اتصال YouTube API في بيئة الاختبار محجوب قبل المصادقة.**

2.6 يضيف خطة مصادر لكل جملة، بحث القنوات المعتمدة، تحليل الفيديو/الصورة الأصلية عبر Gemini، صورًا من API مجاني دون cx، أرشيف تحميلات يعاد استخدامه، ومنع التصدير النهائي الناقص مع حفظ مسودة قابلة للتحرير. **لا توليد صور أو فيديو بالذكاء الاصطناعي داخل الأداة.**

نجح 196 اختبارًا شاملًا محليًا، ثم مجموعة 29 اختبار مصادر/مقتطفات تشمل اختبارًا إضافيًا. هذه اختبارات HTTP محاكاة ورندر FFmpeg فعلي لملفات اختبار معلنة؛ ليست إثباتًا لتنزيل YouTube حي أو قبول جودة مونتاج القناة. أعيد فتح ZIP المصدر والواجهة والأرشيف من مجلد مستقل بنجاح.

المفاتيح غير مرفقة. اضبطها من إعداد الأداة أو الحقول الآمنة للبيئة؛ لا تضعها في المشروع أو المستودع.

---

# RashSpeak Studio — ملفات التسليم الفعلية

الملفات الموجودة هنا هي نتيجة الإنتاج الفعلي من التسجيل المرفوع، دون إعادة الرندر.

| الملف | رابط التنزيل |
| --- | --- |
| الأداة 2.5 ومصدرها وتعليماتها | [RashSpeak_Studio_2.5.zip](https://raw.githubusercontent.com/ClearDataIQ/Rashspeak/main/RashSpeak_Studio_2.5.zip) |
| المقطع الطويل | [RashSpeak_Real_Long.mp4](https://raw.githubusercontent.com/ClearDataIQ/Rashspeak/main/RashSpeak_Real_Long.mp4) |
| الشورت الأول | [RashSpeak_Real_Short_01.mp4](https://raw.githubusercontent.com/ClearDataIQ/Rashspeak/main/RashSpeak_Real_Short_01.mp4) |
| الشورت الثاني | [RashSpeak_Real_Short_02.mp4](https://raw.githubusercontent.com/ClearDataIQ/Rashspeak/main/RashSpeak_Real_Short_02.mp4) |
| الشورت الثالث | [RashSpeak_Real_Short_03.mp4](https://raw.githubusercontent.com/ClearDataIQ/Rashspeak/main/RashSpeak_Real_Short_03.mp4) |
| المشروع الكامل مع التسجيل الأصلي | [RashSpeak_Real_Full_Project.zip](https://github.com/ClearDataIQ/Rashspeak/raw/refs/heads/main/RashSpeak_Real_Full_Project.zip) |

حزمة المشروع الكامل أكبر من 100 MB، وتُحفظ باستخدام Git LFS. حمّلها من الرابط المباشر بدل افتراض أن أرشيف Code → Download ZIP يحتوي تلقائيًا على ملف LFS الحقيقي.

المستودع عام بموافقة المالك. لا تتضمن الحزم مفاتيح APIs. تتوفر أحجام الملفات وبصمات SHA256 في delivery_manifest.json وSHA256SUMS.txt.

لتشغيل الأداة: فك RashSpeak_Studio_2.5.zip ثم اتبع README_AR.md داخل الحزمة. هذه حزمة مصدر Python وليست مثبت EXE.
