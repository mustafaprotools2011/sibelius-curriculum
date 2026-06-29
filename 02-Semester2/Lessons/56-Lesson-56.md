# الدرس 56 | Lesson 56
## تقنيات Sibelius — الـ Mixer والصوت
## Sibelius Techniques — Mixer & Sound

هذا درس تقني محض — لا مقام ولا إيقاع جديد. سنتعلم كل شيء عن الصوت في Sibelius: الـ Mixer، Sound Sets، VST Instruments، Playback Configuration، وكيفية جعل النوتة تصدر صوتاً احترافياً.

---
### معلومات الدرس | Lesson Info

| AR | EN |
|----|----|
| **رقم الدرس** | 56 |
| **عنوان عربي** | تقنيات Sibelius — الـ Mixer والصوت |
| **English Title** | Sibelius Techniques — Mixer & Sound |
| **المقام** | لا يوجد — درس تقني محض |
| **الإيقاع** | لا يوجد — درس تقني محض |
| **الموضوع** | Mixer, Sound Sets, VST Instruments, Playback Configuration |

### الأهداف | Objectives
1. فهم واجهة الـ Mixer في Sibelius والتحكم في مستويات الصوت (Volume) والتوزيع المجازي (Pan)
2. تعلم Sound Sets — كيف يربط Sibelius النوتات بأصوات عالية الجودة
3. إضافة وتشغيل VST Instruments (آلات افتراضية خارجية)
4. ضبط إعدادات Playback — جودة الصوت، التأخير (Latency)، واختيار واجهة الصوت (Audio Interface)
5. تعلم استخدام ReWire لتوصيل Sibelius ببرامج صوتية أخرى

---
### 1. النظري | Theory (10 min)

**كيف يعمل الصوت في Sibelius؟**

عندما تكتب نوتة في Sibelius وتضغط Play، يقوم Sibelius بالآتي:
1. **يقرأ النوتات** من الـ Score (كل نوتة لها Pitch + Duration + Velocity)
2. **يُرسل النوتات** إلى Sound Engine (محرك الصوت)
3. **Sound Engine** يطابق كل نوتة مع **Sound Set** المناسب (مثلاً Violin له Sound Set خاص)
4. **Sound Set** يختار **Sample** (تسجيل حقيقي) أو **Synthesizer** المناسب
5. **الصوت يخرج** عبر Mixer إلى مكبرات الصوت

**مكونات الصوت الرئيسية:**
- **Playback Device:** ما الذي ينتج الصوت — Sibelius Sounds (المدمج)، أو VST (جهة خارجية)
- **Sound Set:** ملف يربط كل آلة في Sibelius بعينة صوتية (Sample) محددة
- **Mixer:** لوحة التحكم في مستويات الصوت، Pan، Reverb، وغيرها

**ما هو الـ Mixer؟**

الـ Mixer في Sibelius يشبه خلاط الصوت الحقيقي. يمكنك رؤيته بالضغط على **F10** (أو **Window** → **Mixer**).

**عناصر الـ Mixer (من اليسار لليمين):**
1. **Master Channel:** التحكم الرئيسي في الصوت الكلي — Volume Master و Pan Master
2. **قنوات الآلات (Instrument Channels):** كل آلة في الـ Score لها قناة خاصة — Violin I لها قناة، Piano لها قناة، إلخ
3. **Mute / Solo:** زر كتم (M) أو عزف منفرد (S) لكل آلة
4. **Volume Slider:** شريط التحكم في مستوى الصوت (من -∞ إلى +6 dB)
5. **Pan Knob:** مقبض التحكم في التوزيع المجازي — يسار/يمين (L/R)
6. **Reverb / Effects:** إضافة صدى (Reverb) أو مؤثرات أخرى
7. **VST / Sound Set:** اختيار Sound Set لكل آلة

**ما هي Sound Sets؟**

**Sound Set** هو ملف تكوين (Configuration File) يخبر Sibelius:
- أي **Sample Library** سيستخدم لكل آلة
- أي **Articulation** (مثلاً Pizzicato vs Arco للكمان) سيتم تشغيله
- أي **Dynamics** (p, mf, f) تؤثر على الصوت

مثال: عندما تكتب **Violin** في Sibelius، Sound Set يختار:
- إذا كان فيه Pizzicato → عينة صوت Pizzicato
- إذا كان فيه Arco → عينة صوت Arco
- إذا كان فيه **f** (Forte) → عينة بصوت عالٍ

**ما هي VST Instruments؟**

VST (Virtual Studio Technology) هو معيار يسمح بتشغيل آلات افتراضية داخل Sibelius — مثل Kontakt (أشهر مكتبة عينات)، أو Vienna Symphonic Library، أو EastWest.

**لماذا نستخدم VST بدلاً من Sibelius Sounds المدمج؟**
- **جودة أعلى:** VST عادة يحتوي على آلاف العينات المسجلة بأوركسترا حقيقية
- **تحكم أكثر:** يمكنك ضبط كل تفصيلة في الصوت
- **مؤثرات إضافية:** Reverb، EQ، Compressor، وغيرها

**ما هو ReWire؟**

**ReWire** هو بروتوكول يسمح بتوصيل Sibelius مع برنامج DAW (مثل Cubase, Logic, Pro Tools, Ableton Live). هذا يسمح لك:
- بتشغيل صوت Sibelius مباشرة في الـ DAW
- بمزامنة سرعة Sibelius مع سرعة الـ DAW (Tempo Sync)
- بتسجيل MIDI مباشرة من Sibelius إلى الـ DAW

---
### 2. التطبيق العملي | Practice (30 min)

**تمرين 1: فتح واستكشاف الـ Mixer (5 دقائق)**

1. افتح Sibelius → **File** → **New** → اختر **Piano** (آلة واحدة فقط — أبسط)
2. اكتب 4 مازورات: سلم Do (C Major) صعوداً ونزولاً، كل نوتة Noire
3. افتح الـ Mixer:
   - اضغط **F10** — ستظهر نافذة Mixer في أسفل الشاشة
   - أو: **Window** → **Mixer**
4. استكشف الـ Mixer:
   - **Master Channel** (أقصى اليسار): شريط **Volume Master** — ارفعه إلى 0 dB (الافتراضي)
   - **Piano Channel** (القناة الوحيدة): ستجد:
     - **Mute (M):** اضغط عليها → سيصمت البيانو. اضغط مجدداً ليعود الصوت
     - **Solo (S):** اضغط عليها → فقط البيانو سيصدر صوتاً (مفيد حين يوجد 10 آلات)
     - **Volume Slider:** اسحبه لأسفل (لـ 70% أو -6 dB) — سيخفض الصوت
     - **Pan Knob:** أدره لليمين (R) — سيصدر الصوت من السماعة اليمنى فقط
5. جرب التالي:
   - غير Pan إلى 0 (مركز) — الصوت في المنتصف
   - غير Volume إلى 100% (0 dB) — أعلى صوت
   - اضغط **Play** (Spacebar) — استمع للفرق
6. أضف **Reverb:**
   - في الـ Mixer، ابحث عن قائمة **Effects** أو **Reverb**
   - اختر **Hall** (إعداد مسبق — Preset)
   - ارفع Reverb Amount إلى 30% — ستسمع الصدى
   - جرب **Room** (غرفة صغيرة) و **Cathedral** (كاتدرائية كبيرة) — ما الفرق؟

**تمرين 2: Sound Sets — تبديل وتخصيص (6 دقائق)**

1. افتح ملفاً جديداً أو استخدم ملف Piano السابق
2. في الـ Mixer (F10)، ابحث عن اسم الآلة — Piano
3. فوق اسم الآلة، ستجد قائمة منسدلة (Dropdown) لاختيار **Sound Set**:
   - اضغط على السهم المجاور لاسم Piano
   - ستظهر قائمة بأصوات مختلفة — اختر **Grand Piano v2** أو **Bright Piano** إذا كان متاحاً
4. جرب تغيير **Articulation** (تقنية العزف):
   - في الـ Mixer، ابحث عن قائمة **Articulation** أو **Technique**
   - جرب **Pizzicato** (إذا متاح للآلة الوترية) — ستسمع صوت نقر بدلاً من قوس
   - ارجع إلى **Arco** (القوس العادي)
5. أضف آلة جديدة بأصوات مختلفة:
   - **Home** tab → **Instruments** (أو I)
   - أضف **Violin** — اختر **Solo Violin** أو **Violin Section**
   - اكتب 4 مازورات للكمان — أي لحن بسيط
6. الآن في الـ Mixer، لاحظ أن هناك قناتين: **Piano** و **Violin**
   - لكل قناة Volume و Pan و Mute/Solo خاص بها
   - جرب Solo على Violin — Piano سيُكتم تلقائياً
7. **تغيير Sound Set لآلة:**
   - في قناة Violin، اضغط على قائمة **Sound Set** (اسم الآلة)
   - اختر **Changing Sound Set** أو اختر مكتبة صوتية أخرى
   - إذا كان VST مثبتاً (مثل NotePerformer)، اختره — الفرق في الجودة كبير جداً

**تمرين 3: إضافة VST Instrument (7 دقائق)**

هذا التمرين يتطلب وجود VST مثبت على جهاز الكمبيوتر. إذا لم يتوفر VST، تابع قراءة الخطوات وافهم كيف تعمل.

1. **تثبيت VST (نظرياً):**
   - قم بتثبيت أي VST (مثل Kontakt Player — مجاني، أو NotePerformer — تجريبي)
   - تأكد من معرفة مسار التثبيت (عادة C:\Program Files\VSTPlugins أو C:\Program Files\Common Files\VST3)

2. **إضافة VST إلى Sibelius:**
   - **File** → **Preferences** → **Playback**
   - في قسم **VST and Audio Units**:
     - اضغط **Add** → اختر مسار مجلد VST
     - Sibelius سيفحص المجلد ويضيف كل VST الموجود
   - اضغط **OK** واعد تشغيل Sibelius

3. **استخدام VST مع آلة:**
   - في الـ Mixer (F10):
     - اختر آلة (مثلاً Piano)
     - في قائمة **Sound Set** أو **Device**، اختر الـ VST الذي أضفته
     - مثلاً: اختر **Kontakt** → ستظهر نافذة Kontakt لتحميل آلة
   - اكتب نوتات — الآن الصوت يأتي من VST بدلاً من Sibelius Sounds

4. **إضافة VST Effect:**
   - في الـ Mixer، ابحث عن **Slot FX** أو **Inserts**
   - اضغط على **Add** → اختر **Reverb** (من VST Effects)
   - الآن الصوت يمر عبر Reverb قبل الخروج

5. **تجربة عملية بدون VST:**
   - في الـ Mixer، جرب **Sibelius Player** (المدمج)
   - هذه الآلات تأتي مع Sibelius — جودة جيدة جداً للمبتدئين
   - جرب أصوات مختلفة من Sibelius Sounds عبر قائمة Sound Set

**تمرين 4: ضبط Playback Configuration (6 دقائق)**

1. **Play** tab → **Playback Setup** (أو **Ctrl+Shift+Y** على Windows)
2. نافذة Playback Setup تحتوي على عدة أقسام:

**قسم Device Configuration:**
- **Audio Engine** أو **Playback Device:**
  - اختر **Sibelius Sounds** (أو **ASIO** إذا كان لديك واجهة صوت خارجية)
  - إذا كان لديك واجهة صوت (Audio Interface مثل Focusrite Scarlett)، اختر **ASIO** + اسم الواجهة

**قسم Audio Settings:**
- **Sample Rate:** اختر 44100 Hz (جودة CD) — الأفضل للتوافق العام
- **Buffer Size (Latency):**
  - **256 samples:** تأخير منخفض (جيد للعزف المباشر)
  - **512 samples:** تأخير متوسط (جيد للتشغيل العادي)
  - **1024 samples:** تأخير عالي (جيد للـ Mixing النهائي)
  - جرب 512 — توازن جيد بين الجودة والسرعة
- **Bit Depth:** اختر **16-bit** (للتصدير العادي) أو **24-bit** (لجودة أعلى)

**قسم MIDI Input:**
- إذا كان لديك **MIDI Keyboard** متصل:
  - اختر اسم الـ MIDI Device من القائمة
  - الآن يمكنك العزف على الكيبورد وتسجيل النوتات مباشرة في Sibelius

3. جرب التالي:
   - غير **Buffer Size** من 512 إلى 256 — لاحظ أن التأخير (Latency) يصبح أقل
   - لو سمعت صوت **Click** أو **Pop** (تشويش)، ارجع إلى 512
   - غير **Sample Rate** من 44100 إلى 48000 — اختبر الفرق (قليل جداً في الأذن البشرية)

**تمرين 5: ReWire (أو Export Audio بديل) (6 دقائق)**

**الجزء A — ReWire (إذا كان متاحاً):**
1. افتح Sibelius + برنامج DAW على جهازك (مثل Cubase أو Ableton أو Logic)
2. في الـ DAW:
   - إنشاء مشروع جديد
   - أضف **ReWire Channel** → اختر **Sibelius**
3. في Sibelius:
   - سيظهر Sibelius تلقائياً كـ ReWire Device في الـ DAW
   - الآن صوت Sibelius يذهب مباشرة إلى الـ DAW
4. اضغط **Play** في الـ DAW — Sibelius سيتزامن تلقائياً

**الجزء B — Export Audio (بديل ReWire للمبتدئين):**
إذا لم يتوفر ReWire، يمكنك تصدير الصوت مباشرة:

1. **File** → **Export** → **Audio**
2. نافذة Export Audio:
   - **Format:** اختر **WAV** (جودة عالية، غير مضغوط)
   - **Sample Rate:** 44100 Hz
   - **Bit Depth:** 16-bit
   - **File Name:** اختر اسماً مثل `MyComposition`
   - **Save Location:** اختر مجلد
3. اضغط **Export**
4. سيقوم Sibelius بتصدير الصوت كملف WAV — يمكنك فتحه في أي مشغل وسائط أو DAW

**الجزء C — Export MIDI (مهم للدرس القادم):**
1. **File** → **Export** → **MIDI**
2. اختر **MIDI Type 1** (كل آلة في Track منفصل)
3. اضغط **Export**
4. هذا الملف MIDI يمكن فتحه في أي DAW أو برنامج نوتة آخر

---
### 3. اختصارات Sibelius (5 min)

| # | الاختصار | الوظيفة | Function |
|---|---------|---------|----------|
| 1 | **F10** | فتح نافذة Mixer | Opens Mixer window |
| 2 | **Ctrl+Shift+Y** | فتح Playback Setup | Opens Playback Setup |
| 3 | **Ctrl+Shift+E** | تصدير الصوت (Export Audio) | Export Audio |
| 4 | **M** | كتم القناة المحددة (Mute) | Mute selected channel |
| 5 | **S** | عزف منفرد للقناة (Solo) | Solo selected channel |

---
### 4. مراجعة وواجب | Review & HW (5 min)

**أسئلة المراجعة:**
1. ما هو الفرق بين Sound Set و VST Instrument؟ كيف يختار Sibelius الصوت المناسب لكل آلة؟
2. ماذا يفعل ضبط Buffer Size في Playback Setup؟ لماذا يؤثر على التأخير (Latency)؟
3. كيف يمكنك جعل البيانو يصدر صوتاً من السماعة اليمنى فقط في الـ Mixer؟

**الواجب المنزلي**
1. اكتب تمرين رقم (———) في كتاب الصولفيج المقرر
**الواجب:**
1. أنشئ مقطوعة لـ **Trio** (Violin, Viola, Cello) — 12 مازورة
2. استخدم الـ Mixer لضبط:
   - Volume مختلف لكل آلة (Violin أعلى، Cello أخفض)
   - Pan مختلف (Violin يسار 30%، Viola وسط 0%، Cello يمين 30%)
3. أضف Reverb (Hall أو Room) على كل الآلات
4. صدر المقطوعة كـ **WAV Audio File**
5. صدر المقطوعة كـ **MIDI File (Type 1)**
6. احفظ باسم `Lesson56_Mixer_Sound.sib`

---
### 5. تطبيق عملي | Practical Application

**تطبيق Mixer على آلتك الموسيقية:**
1. اكتب تقسيماً لـ Maqam Rast على آلتك الموسيقية في Sibelius (8 مازورات)
2. اختر آلة **Oud** من Sibelius Sounds (أو Ayoute إذا متاح — آلة شرقية شبيهة)
3. في الـ Mixer:
   - اجعل Pan متمركزاً (0%)
   - أضف Reverb بنسبة 20-30% (لطابع شرقي)
   - جرب Sound Set مختلف — **Nylon Guitar** (جيتار نايلون) يعطي صوتاً قريباً من العود إذا لم يتوفر Oud مباشر
4. صدر الـ Audio كـ WAV واستمع إلى النتيجة

**نصيحة:**
إذا لم تجد آلة Oud في Sound Set، جرب:
- **Nylon Guitar** (قريب جداً من صوت العود)
- **Santoor** (صوت مختلف لكنه شرقي)
- **Kemenche** (صوت عود تقليدي)

---
### 6. التقييم | Assessment /15

| المعيار | ممتاز (3-5) | جيد (2) | يحتاج تحسين (1-0) | الدرجة |
|---------|------------|---------|-------------------|--------|
| **Mixer — Volume & Pan** (4) | ضبط Volume و Pan لكل آلة مع توزيع متوازن | ضبط Volume فقط أو Pan فقط | لم يضبط أو إعدادات غير مناسبة | /4 |
| **Sound Set** (3) | اختيار Sound Set المناسب لكل آلة + تغيير Articulation | اختيار Sound Set صحيح لكن بدون Articulation | نفس Sound Set الافتراضي للكل | /3 |
| **Reverb & Effects** (4) | إضافة Reverb بكمية مناسبة لكل آلة + فهم الفرق بين Room/Hall | إضافة Reverb لكن بنسبة غير مناسبة | لم يضف أي Effect | /4 |
| **Export Audio + MIDI** (4) | تصدير WAV صحيح + MIDI Type 1 صحيح + فهم الفرق بينهما | تصدير صحيح لكن Format خاطئ | لم يصدر أو أخطاء في التصدير | /4 |
| **المجموع** | | | | **/15** |

---
### 7. مفردات الدرس | Vocabulary

| عربي | English | شرح |
|------|---------|------|
| خلاط الصوت | Mixer | لوحة التحكم في مستويات الصوت والتوزيع المجازي والمؤثرات |
| مجموعة الصوت | Sound Set | ملف يربط كل آلة بعينة صوتية معينة |
| آلة افتراضية | VST (Virtual Studio Technology) | برنامج آلة موسيقية يعمل داخل Sibelius |
| إعادة التشغيل | Playback | تشغيل النوتة كصوت عبر Sibelius |
| مستوى الصوت | Volume | شدة الصوت — يتحكم فيه شريط (Slider) في الـ Mixer |
| توزيع مجازي | Pan | توزيع الصوت بين السماعة اليسرى واليمنى |
| صدى | Reverb | مؤثر صوتي يحاكي الغرفة أو القاعة |
| كتم | Mute | كتم صوت آلة معينة |
| عزف منفرد | Solo | تشغيل آلة واحدة فقط وكتم البقية |
| تأخير الصوت | Latency | الفارق الزمني بين العزف وسماع الصوت |
| حجم العازل | Buffer Size | عدد العينات الصوتية في المخزن المؤقت — يتحكم في Latency |
| إعادة التوصيل | ReWire | بروتوكول لتوصيل Sibelius مع برامج DAW |
| التصدير الصوتي | Export Audio | تحويل النوتة إلى ملف صوتي (WAV/MP3) |

---
### 8. ملاحظات المدرس | Teacher Notes

- **هذا درس تقني بحت مع تركيز على الصوت:** ابدأ بتشغيل مقطوعة قصيرة في Sibelius واسأل الطلاب: "كيف تعتقدون أن Sibelius ينتج الصوت؟"
- **الـ Mixer هو أهم أداة:** اشرح أن Mixer Sibelius يشبه خلاط الصوت الحقيقي (Audio Mixer) — تعلمه الآن يساعدك في أي DAW مستقبلاً.
- **Sound Set مفهوم مجرد:** استخدم تشبيهاً: Sound Set مثل قاموس يترجم "Piano" إلى صوت بيانو حقيقي مسجل. كل آلة لها ترجمتها في القاموس.
- **Latency مفهوم صعب للمبتدئين:** قارنه بـ "التأخير بين ضرب الكرة الأرضية ووصول الصوت إلى أذنك" — Buffer Size الصغير = تأخير أقل. Buffer الكبير = تأخير أكبر لكن تشغيل أكثر استقراراً.
- **VST قد لا يكون متاحاً للجميع:** إذا لم يكن VST مثبتاً على أجهزة المختبر، ركز على Sibelius Sounds (المدمج) — جودته كافية جداً لتعلم الأساسيات.
- **التفريق للطلاب المتقدمين:** اطلب منهم إضافة VST Effect خارجي (مثل Compressor) على آلة معينة وضبط إعداداته.
- **للطلاب الأقل تقدماً:** ركز على التمارين 1 (Mixer) و 4 (Playback Setup) فقط — هذه هي الأساسيات التي يحتاجونها.
- **اقتراح استماع:** استمع إلى مقطوعة أوركسترالية (مثل Beethoven Symphony No. 5) — استخدم الـ Mixer لعزل كل آلة (Solo) لسماع دورها.
- **مشكلة شائعة:** إذا لم يخرج صوت عند Play، تحقق من:
  1. هل الـ Mute غير مفعل؟ (أيقونة M يجب ألا تكون زرقاء)
  2. هل Playback Device صحيح؟ (File → Preferences → Playback → Audio Device)
  3. هل الـ Volume في الـ Mixer غير صفر؟
  4. هل Sound Set موجود لكل آلة؟
- **تذكير للدرس القادم:** الدرس 57 سيكون عن تصدير PDF و MIDI — تأكد من أن الطلاب يعرفون الآن كيف يصدرون Audio و MIDI من هذا الدرس.
