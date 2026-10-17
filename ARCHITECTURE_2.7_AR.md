# بنية 2.7 وحدود الاختبار

يظل gui.py نقطة تشغيل Tk؛ production_ui.py يستدعي production.produce،
ثم reviewed_production.py ينسق المراحل المحفوظة. المحرر pro_editor_ui.py
يستخدم pro_project.py وpro_render.py؛ الرندر والمعاينة يأخذان نموذج
التعديلات نفسه، والبوابة project_bridge.py تحفظ current.rash.json.

captions.py يشغل faster-whisper بكلمات وتوقيت، وaudio_edit.py يحفظ
قرارات القص، وvoice_processing.py ينفذ المعالجة. audio_checkpoint.py
يمنع تكرار DSP عندما تتطابق بصمة الأصل والقص والإعدادات وبصمة الناتج.
resource_policy.py يسجل DLL داخل العملية، ويحد خيوط CPU، ويحجز البطاقة
للعمليات المتسلسلة داخل العملية وعبر ملفات القفل بين العمليات.

gemini_client.py واجهة توافق للمستدعين الحاليين؛ provider صريح يختار
Google أو openrouter_client.py. ai_runtime.py يثبت endpoint ومجال
المفتاح وتوقف الحصة. api_connections.py وai_capabilities.py ينفذان
اختبارات منفصلة حقيقية للمحتوى؛ api_settings_ui.py لا يملأ المفتاح
المحفوظ في الحقل ولا ينسخه للمشروع. الحفظ keyring اختياري.

gemini_context.py يحفظ دفعات فهم مرتبطة بالأصل/النموذج/المزوّد/البرومبت.
media_director.py وvisual_choices.py يربطان المشاهد بالأدلة وفحص الصور؛
media_archive.py يحفظ البصمات والحقوق. لا تمنح نتائج البحث تصريحًا.
production_quality.py يبقي مسودة نقص التغطية دون تصدير نهائي مضلل.

short_policy.py يطلب فكرة مكتملة ومقطع صوت متتابع25–60ثانية. المحرك
موجود من التطوير السابق؛ لم يجتز شورت حقيقي جديد في2.7 بسبب نقص
المصادر. لا تعتبر اختبارات التركيب الاصطناعي إثباتًا لملاءمة المشاهد.

الحفظ atomic_io.py يكتب staging فريدًا ويغلقه قبل الاستبدال ويحتفظ
بمسودة استعادة عند استمرار قفل Windows. صيغة المشاريع القديمة باقية؛
لا يوجد ترحيل إتلافي أو إعادة كتابة للمشروع. التوافق يُختبر في الوحدات.

الاختبارات المعلنة: tests/test_provider_runtime.py للمزوّد/الحصة،
test_checkpoints_bridge.py لاستئناف DSP وحفظ تحرير Pro،
test_windows_locale_cache.py لقراءة العربية مع تعطيل UTF8 الافتراضي،
test_production_ui.py للتحكم ووضوح الأزرار عند الحد الأدنى لحجم النافذة.
اختبار أصل التسجيل والمعاينات الاصطناعية والربط الحي موثقة منفصلة
في RELEASE_STATUS_2.7_WIP.json ودليل التشغيل، بلا ادعاء قبول نهائي.
