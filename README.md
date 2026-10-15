# RashSpeak Studio 2.6.1 — تحديث الأداة وإعداد المفاتيح

**[تنزيل RashSpeak Studio 2.6.1](https://raw.githubusercontent.com/ClearDataIQ/Rashspeak/main/RashSpeak_Studio_2.6.1.zip)** · [إضافة مفاتيح الخدمات](API_KEYS_2.6.1_AR.md) · [التغييرات](CHANGELOG_2.6.1_AR.md) · [نتائج الاختبارات](TEST_RESULTS_2.6.1.txt)

1. فك ZIP المصدر في مجلد جديد وشغّل `START_WINDOWS.bat`؛ يحتاج Python 3.11+ مع Tk. جهّز FFmpeg وffprobe كما في README_AR.md داخل الحزمة. هذه حزمة مصدر وليست مثبت EXE.
2. اضغط **مفاتيح YouTube وGemini** أعلى الشاشة. في المحرر يوجد زر **مفاتيح API**.
3. أدخل مفتاح كل خدمة في تبويبها، واختبر الاتصال ثم احفظ. يمكنك اختيار الحفظ في خزنة النظام للاستخدام بعد إعادة فتح البرنامج؛ الافتراضي للجلسة.

لكل خدمة حقل مخفي وفحص مستقل يعمل في الخلفية. اختبار المفتاح المكتوب لا يستبدله بمفتاح قديم ولا يحفظه تلقائيًا. الحقول الفارغة تحافظ على الإعداد السابق. المفاتيح غير مرفقة ولا تدخل المشروع أو أرشيف الوسائط. لتنزيل المقتطفات المسموحة ثبّت `INSTALL_MEDIA_SOURCES.bat`؛ YouTube Data API نفسه للبحث والبيانات، وليس تنزيل الفيديو.

نجح **216 اختبارًا شاملًا**، ثم **16 اختبار واجهة واتصال** بعد التنسيق النهائي. فُتحت الحزمة المستقلة في Auto Studio وPro Editor. جُربت أزرار الاتصال فعليًا: نجح Gemini، وأظهر YouTube رفض وكيل السحابة قبل المصادقة. لذلك صلاحية مفتاح YouTube وتنزيله الحي غير مثبتين هنا. Windows وخزنة Windows لم يُختبرا حيًا في بيئة Linux.

تشمل الحزمة إصلاح معاينة الإطار وحالة نقص الوسائط وتصحيح فحص تكرار أسماء الألعاب. اكتمل تحليل 160 جملة من تسجيل المالك الحقيقي؛ **لم ينتج فيديو نهائي مصحح** لأن الوسائط غير متاحة في هذه السحابة. الفيديوهات القديمة أدناه مرفوضة ولا تمثّل مونتاجًا مقبولًا. لا توليد صور أو فيديو بالذكاء الاصطناعي داخل الأداة.

حزمة المصدر لا تتضمن مفاتيح أو تسجيلات أو نماذج. بصمة الحزمة في RashSpeak_Studio_2.6.1_SHA256.txt، وتفاصيلها في RashSpeak_Studio_2.6.1_MANIFEST.json.

---

# أرشيف تسليم 2.5 السابق

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

لتشغيل الإصدار الحالي استخدم رابط 2.6.1 أعلى الصفحة. تبقى حزمة 2.5 هنا للأرشفة فقط.
