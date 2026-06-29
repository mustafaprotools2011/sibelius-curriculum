# الدرس 58 | Lesson 58
## MusicXML والتصدير المتقدم
## MusicXML & Advanced Exporting

هذا درس تقني محض — لا مقام ولا إيقاع جديد. سنتعلم كيف نصدر نوتاتنا بصيغ متقدمة تتجاوز PDF و MIDI: MusicXML للتوافق مع برامج النوتة الأخرى (Finale, Dorico, MuseScore)، Audio Export (WAV/MP3) للصوت، Video Export للعرض على YouTube، والمشاركة المباشرة عبر الإنترنت.

---
### معلومات الدرس | Lesson Info

| AR | EN |
|----|----|
| **رقم الدرس** | 58 |
| **عنوان عربي** | MusicXML والتصدير المتقدم |
| **English Title** | MusicXML & Advanced Exporting |
| **المقام** | لا يوجد — درس تقني محض |
| **الإيقاع** | لا يوجد — درس تقني محض |
| **الموضوع** | MusicXML, Audio Export (WAV/MP3), Video Export, Online Sharing, Cross-Platform Compatibility |

### الأهداف | Objectives
1. تصدير النوتة بصيغة MusicXML للتوافق مع Finale و Dorico و MuseScore
2. تصدير الصوت بصيغ WAV و MP3 بجودة احترافية
3. تصدير فيديو متزامن مع الصوت للنشر على YouTube
4. المشاركة عبر الإنترنت — SoundCloud, YouTube, Notion
5. فهم سير العمل الكامل: Sibelius → MusicXML → برنامج آخر → Audio → Video

---
### 1. النظري | Theory (10 min)

**ما هو MusicXML؟**

MusicXML هو **معيار عالمي مفتوح** لتبادل النوتات الموسيقية بين البرامج المختلفة. فكر فيه كـ "PDF للنوتات القابلة للتعديل":

- **Sibelius** → MusicXML → **Finale**: افتح نوتة Sibelius في Finale بدون فقدان البيانات
- **Sibelius** → MusicXML → **Dorico**: انتقل إلى Dorico بسلاسة
- **Sibelius** → MusicXML → **MuseScore**: شارك مع مستخدمي البرامج المجانية
- **Sibelius** → MusicXML → **Notion**: استخدم على iPad

**ماذا يحفظ MusicXML؟**

| الخاصية | يُحفظ؟ | ملاحظة |
|---------|--------|--------|
| النوتات (Pitches, Rhythms) | ✅ نعم | بدقة كاملة |
| العلامات التعبيرية (Dynamics) | ✅ نعم | mf, p, f, cresc. |
| Articulations (Staccato, Legato) | ✅ نعم | معظمها |
| Slurs و Ties | ✅ نعم | بدقة |
| كلمات الأغاني (Lyrics) | ✅ نعم | مع الـ Syllables |
| علامات المقام | ✅ نعم | Key Signatures |
| الإيقاع | ✅ نعم | Time Signatures |
| أسماء الآلات | ✅ نعم | Instrument Names |
| Sound Set | ❌ لا | لأن البرنامج الوجهة ليس Sibelius |
| Mixer Settings | ❌ لا | كل برنامج له Mixer مختلف |
| Playback Effects | ❌ لا | MIDI Controller Data محدودة |

**لماذا لا نستخدم MIDI بدلاً من MusicXML؟**
MIDI يحفظ **النوتات فقط** — لا يحفظ المقامات، الإيقاعات، الـ Dynamics، الـ Slurs، الكلمات. MusicXML يحفظ كل هذه التفاصيل. MIDI هو تعليمات صوتية — MusicXML هو نوتة قابلة للتحرير.

**تصدير الصوت — Audio Export (WAV / MP3)**

Sibelius يمكنه تصدير الصوت باستخدام Sound Set الداخلي:

| الصيغة | الجودة | الاستخدام | حجم الملف |
|--------|--------|----------|-----------|
| **WAV** | 44.1kHz / 16-bit (CD Quality) | ماستر، تحرير في DAW، أرشفة | كبير (~10MB/دقيقة) |
| **MP3** | 128-320 kbps | مشاركة، رفع على الإنترنت | صغير (~1MB/دقيقة) |
| **AIFF** | 44.1kHz / 16-bit | مشابه لـ WAV لأجهزة Apple | كبير (~10MB/دقيقة) |
| **FLAC** | 44.1kHz / 24-bit | ضغط بدون فقدان جودة | متوسط (~5MB/دقيقة) |

**إعدادات الصوت المهمة:**
- **Sample Rate:** 44.1kHz (قياسي لـ CD)، 48kHz (للفيديو)
- **Bit Depth:** 16-bit (CD Quality)، 24-bit (Studio Quality)
- **Bit Rate (MP3):** 320 kbps (أفضل جودة)، 192 kbps (جيدة)، 128 kbps (مقبولة)
- **Export Range:** All (كل النوتة)، Selection (جزء محدد)، Pages (صفحات معينة)

**تصدير الفيديو — Video Export**

Sibelius 2023+ يتيح تصدير فيديو متزامن مع الصوت:

- **Video Resolution:** 720p (HD), 1080p (Full HD), 4K
- **Frame Rate:** 30fps
- **Video Codec:** H.264 (MP4)
- **Audio:** مشفر مع الفيديو
- **ما يظهر في الفيديو:** النوتة تتحرك مع الـ Playback Cursor

**استخدامات الفيديو:**
- رفع على **YouTube** كدرس أو عرض موسيقي
- استخدامه في **PowerPoint** أو **Keynote** للعروض التقديمية
- فيديو تدريبي للطلاب (يتحرك الـ Cursor مع الموسيقى)
- عرض الـ Portfolio الموسيقي

**المشاركة عبر الإنترنت — Online Sharing**

يمكنك مشاركة نتاجك عبر:
- **YouTube:** ارفع الفيديو أو الصوت مع صورة النوتة
- **SoundCloud:** ارفع MP3 مع صورة الغلاف
- **Notion:** أدرج ملف PDF أو فيديو مباشرة في صفحة
- **Google Drive / OneDrive:** شارك ملفات .sib و PDF و MIDI
- **Website شخصي:** أنشئ صفحة لكل مقطوعة مع خيارات التحميل

---
### 2. التطبيق العملي | Practice (30 min)

**تمرين 1: تصدير MusicXML للتوافق مع Finale و Dorico (8 دقائق)**

1. افتح ملفاً من الدروس السابقة — مثلاً Lesson56_Mixer_Sound.sib
   - أو أنشئ مقطوعة بسيطة: رباعي وتري (Violin I, Violin II, Viola, Cello) — 16 مازورة

2. **تصدير MusicXML:**
   - **File** → **Export** → **MusicXML** (أو **Ctrl+Shift+E** ثم اختر MusicXML)
   - ستظهر نافذة Export MusicXML

3. **إعدادات MusicXML الأساسية:**
   - **Export Type:** اختر **Uncompressed (.xml)**
     - **Uncompressed (.xml):** ملف XML عادي — متوافق مع كل البرامج
     - **Compressed (.mxl):** ملف مضغوط — أصغر حجماً، متوافق مع معظم البرامج الحديثة
   - **Layout:** اختر **Optimized for interchange** (الأفضل للتوافق العام)
   - **Export all staves:** ✅ نعم — كل الآلات

4. **إعدادات متقدمة (Advanced):**
   - **Export graphics (pictures):** ✅ نعم — إذا كان هناك صور في النوتة
   - **Export lyrics:** ✅ نعم — إذا كانت هناك كلمات أغاني
   - **Export chord symbols:** ✅ نعم — رموز الكوردات
   - **Export fingering:** ✅ نعم — أرقام الأصابع

5. اختر مجلد الحفظ واسم الملف: `Lesson58_MusicXML.xml`
6. اضغط **Export**

7. **التحقق في برنامج آخر:**
   - افتح **MuseScore** (أو أي برنامج نوتة آخر مثبت)
   - **File** → **Open** → اختر `Lesson58_MusicXML.xml`
   - تحقق من:
     - هل كل النوتات موجودة؟
     - هل المقامات والإيقاعات صحيحة؟
     - هل الـ Dynamics و Articulations محفوظة؟

8. احفظ ملف Sibelius باسم `Lesson58_MusicXML.sib`

**تمرين 2: تصدير الصوت — WAV / MP3 (8 دقائق)**

1. من نفس الملف، **File** → **Export** → **Audio** (أو **Ctrl+Shift+R**)

2. **تصدير WAV (CD Quality):**
   - **Format:** اختَر **WAV**
   - **Sample Rate:** **44100 Hz**
   - **Bit Depth:** **16-bit**
   - **Export Range:** **All pages**
   - **Audio Engine:** استخدم **Sibelius Default** أو **NotePerformer** إذا كان مثبتاً
   - اسم الملف: `Lesson58_Audio.wav`
   - اضغط **Export**
   - انتظر — التصدير قد يستغرق 30-60 ثانية لمقطوعة 3 دقائق

3. **تصدير MP3 للنشر:**
   - **File** → **Export** → **Audio**
   - **Format:** اختَر **MP3**
   - **Bit Rate:** **320 kbps** (أعلى جودة MP3)
   - **Export Range:** **All pages**
   - اسم الملف: `Lesson58_Audio.mp3`
   - اضغط **Export**

4. **التحقق من الصوت:**
   - افتح ملف WAV في أي مشغل (VLC، Windows Media Player)
   - استمع إلى الجودة — هل الصوت واضح؟ هل التوازن بين الآلات صحيح؟
   - قارن بين WAV و MP3 — الفرق في الجودة واضح عند سماعه بسماعات احترافية

5. **نصيحة احترافية:**
   - قبل تصدير الصوت، تأكد من **Mixer Settings** (Ctrl+Alt+M):
     - كل آلة في مستوى Volume مناسب
     - لا يوجد Clipping (مستوى الصوت لا يتجاوز 0 dB)
     - استخدم **Panning** لتوزيع الآلات يميناً وشمالاً

**تمرين 3: تصدير فيديو للنشر على YouTube (7 دقائق)**

1. **File** → **Export** → **Video** (أو **Ctrl+Shift+V**)

2. **إعدادات الفيديو الأساسية:**
   - **Resolution:** اختَر **1920×1080 (Full HD 1080p)**
   - **Frame Rate:** **30 fps**
   - **Video Codec:** **H.264** (MP4)
   - **Include audio from playback:** ✅ نعم

3. **إعدادات Audio ضمن الفيديو:**
   - **Sample Rate:** **48000 Hz** (قياسي للفيديو)
   - **Audio Format:** **AAC** (أفضل تنسيق للفيديو)

4. **مظهر الفيديو (Video Appearance):**
   - **Show playback cursor:** ✅ نعم — ليظهر المؤشر وهو يتحرك
   - **Cursor color:** اختَر لوناً بارزاً (مثلاً **Red** أو **Blue**)
   - **Follow playback:** ✅ نعم — لتتحرك الصفحات تلقائياً
   - **Show page turns:** ✅ نعم — ليظهر انتقال الصفحة

5. اسم الملف: `Lesson58_Video.mp4`
6. اضغط **Export** — هذه العملية قد تستغرق 2-5 دقائق حسب طول المقطوعة

7. **التحقق من الفيديو:**
   - افتح الفيديو في أي مشغل
   - تحقق من:
     - الصوت متزامن مع النوتة
     - الـ Cursor يتحرك مع الموسيقى
     - دقة الفيديو 1080p
     - لا يوجد تقطيع أو مشاكل في الصورة

**تمرين 4: رفع الفيديو على YouTube (4 دقائق)**

1. افتح متصفح الإنترنت واذهب إلى **YouTube Studio** (studio.youtube.com)

2. اضغط على **Upload Videos** → اختَر **Lesson58_Video.mp4**

3. **إعدادات الفيديو:**
   - **Title:** "مقطوعة في مقام كرد | String Quartet — Sibelius | Composition in Maqam Kurd"
   - **Description:**
     ```
     مقطوعة لرباعي وتري تم إنشاؤها في Avid Sibelius.
     A string quartet composition created in Avid Sibelius.
     
     البرامج المستخدمة | Software Used:
     - Sibelius (Composition & Notation)
     - NotePerformer (Audio Engine)
     
     #Sibelius #MusicNotation #StringQuartet #MaqamKurd
     ```
   - **Visibility:** اختَر **Public** أو **Unlisted** (للاختبار)

4. أضف صورة مصغرة (Thumbnail) جذابة:
   - استخدم لقطة شاشة للنوتة مع عنوان جميل
   - أو صمم صورة غلاف في Canva/Photoshop

**تمرين 5: المشاركة عبر SoundCloud و Notion (3 دقائق)**

1. **SoundCloud:**
   - افتح soundcloud.com → **Upload**
   - اختر ملف `Lesson58_Audio.mp3`
   - أضف:
     - **Title:** "Magnum Opus I — String Quartet in Maqam Kurd"
     - **Genre:** Classical / Contemporary
     - **Tags:** Sibelius, String Quartet, Maqam
   - اختر صورة غلاف للمقطوعة
   - اضغط **Save**

2. **Notion Portfolio:**
   - أنشئ صفحة جديدة في Notion
   - أضف:
     - عنوان المقطوعة
     - صورة الغلاف
     - ملف PDF للنوتة (مرفوع)
     - رابط YouTube للفيديو
     - رابط SoundCloud للصوت
     - ملاحظاتك على المقطوعة

---
### 3. اختصارات Sibelius (5 min)

| # | الاختصار | الوظيفة | Function |
|---|---------|---------|----------|
| 1 | **Ctrl+Shift+E** | فتح نافذة Export (اختيار الصيغة) | Opens Export window (format selection) |
| 2 | **Ctrl+Shift+R** | تصدير الصوت (Audio Export) | Audio Export |
| 3 | **Ctrl+Shift+V** | تصدير الفيديو (Video Export) | Video Export |
| 4 | **Ctrl+Shift+U** | مشاركة عبر الإنترنت (Upload) | Online Sharing / Upload |
| 5 | **Ctrl+Shift+S** | حفظ باسم (Save As) مع اختيار الصيغة | Save As with format selection |

---
### 4. مراجعة وواجب | Review & HW (5 min)

**أسئلة المراجعة:**
1. ما الفرق بين MusicXML و MIDI؟ لماذا نستخدم MusicXML للتبادل بين برامج النوتة المختلفة؟
2. ما الفرق بين WAV و MP3؟ أي صيغة تستخدم للأرشفة وأي صيغة تستخدم للنشر على الإنترنت؟
3. كيف تصدر فيديو متزامن مع الصوت من Sibelius؟ ما الإعدادات التي تتحكم في جودة الفيديو؟

**الواجب المنزلي**
1. اكتب تمرين رقم (———) في كتاب الصولفيج المقرر
**الواجب:**
1. افتح مقطوعة العود من الدرس 54 أو أي ملف سابق
2. صدر MusicXML باسم `Oud_Piece.mxl` — اختبر فتحه في متصفح MusicXML (musicxml-viewer.com) أو في MuseScore
3. صدر الصوت كـ **WAV 44.1kHz 16-bit** — اسم الملف: `Oud_Piece.wav`
4. صدر الصوت كـ **MP3 320kbps** — اسم الملف: `Oud_Piece.mp3`
5. صدر **فيديو 1080p** — اسم الملف: `Oud_Piece_Video.mp4`
6. ارفع الفيديو على YouTube (Unlisted) وشارك الرابط مع زملائك
7. احفظ ملف Sibelius باسم `Lesson58_Export_Advanced.sib`

---
### 5. تطبيق عملي | Practical Application

**تصدير موسيقى العود للعالم الرقمي:**

1. استخدم مقطوعة عود من درس سابق (مثلاً Lesson54_Shahnaz_Suznak.sib أو أي تقاسيم)

2. **MusicXML للعود:**
   - صدر MusicXML باسم `Oud_Taqasim.mxl`
   - افتحه في MuseScore أو أي برنامج نوتة آخر
   - العود يظهر كآلة منفردة (عادةً Track واحد مع خطوط الـ Tablature)
   - تحقق من أن الـ Ornaments (زخارف العود) محفوظة

3. **تصدير صوت العود:**
   - استخدم **Oud** Sound Set إذا كان متاحاً في Sibelius
   - أو استخدم **Nylon Guitar** كبديل قريب
   - صدر **WAV** للأرشفة
   - صدر **MP3 320kbps** للمشاركة

4. **فيديو تعليمي للعود:**
   - صدر فيديو 1080p لتقنيات العود
   - الفيديو يظهر النوتة والمؤشر يتحرك — مثالي لتعليم التقاسيم
   - ارفع الفيديو على YouTube كدرس تعليمي بعنوان: "كيفية عزف تقاسيم على آلتك الموسيقية | Oud Taqasim Tutorial"

5. **نشر العود على SoundCloud:**
   - ارفع MP3 مع صورة العود
   - أضف وصفاً يشرح المقامات المستخدمة
   - استخدم #Oud #Maqam #ArabicMusic

---
### 6. التقييم | Assessment /15

| المعيار | ممتاز (3-5) | جيد (2) | يحتاج تحسين (1-0) | الدرجة |
|---------|------------|---------|-------------------|--------|
| **MusicXML Export** (4) | MusicXML صحيح + متوافق مع برنامج آخر + كل التفاصيل محفوظة | MusicXML يفتح لكن فقدان بعض التفاصيل (Dynamics, Slurs) | MusicXML مع أخطاء أو لم يصدر | /4 |
| **Audio Export — WAV + MP3** (4) | كلا الصيغتين صادرتين + جودة صحيحة + فهم الفرق | صيغة واحدة فقط أو جودة غير مناسبة | لم يصدر أو أخطاء في التنسيق | /4 |
| **Video Export 1080p** (3) | فيديو 1080p + صوت متزامن + Cursor يتحرك | فيديو بدقة أقل أو مشاكل في التزامن | لم يصدر أو غير قابل للتشغيل | /3 |
| **Online Sharing** (4) | رفع على YouTube + SoundCloud + Notion + كل الوسوم | رفع على منصة واحدة فقط | لم يرفع أي شيء | /4 |
| **المجموع** | | | | **/15** |

---
### 7. مفردات الدرس | Vocabulary

| عربي | English | شرح |
|------|---------|------|
| MusicXML | MusicXML | معيار مفتوح لتبادل النوتات بين البرامج المختلفة |
| توافق بين البرامج | Cross-Platform Compatibility | قدرة النوتة على العمل في برامج مختلفة (Sibelius, Finale, Dorico, MuseScore) |
| تصدير الصوت | Audio Export | تحويل النوتة إلى ملف صوتي (WAV, MP3) |
| عينات الصوت | Sample Rate | عدد العينات في الثانية — 44100 Hz قياسي لـ CD |
| عمق البت | Bit Depth | دقة العينة — 16-bit للـ CD، 24-bit للاستوديو |
| معدل البت | Bit Rate (kbps) | كمية البيانات في الثانية — كلما زاد، زادت الجودة (320 kbps لـ MP3) |
| تصدير الفيديو | Video Export | تصدير النوتة كفيديو متزامن مع الصوت |
| قرار الفيديو | Video Resolution | دقة الفيديو — 1080p (Full HD)، 720p (HD) |
| ترميز الفيديو | Video Codec | طريقة ضغط الفيديو — H.264 الأكثر شيوعاً |
| المشاركة عبر الإنترنت | Online Sharing | رفع الملفات على YouTube, SoundCloud, Notion |
| صيغة مضغوطة | Compressed (.mxl) | MusicXML بحجم أصغر للتحميل السريع |
| صيغة غير مضغوطة | Uncompressed (.xml) | MusicXML بحجم أكبر لكن قابل للقراءة بأي محرر نصوص |

---
### 8. ملاحظات المدرس | Teacher Notes

- **MusicXML هو المهارة الأهم في هذا الدرس:** كثير من الموسيقيين لا يعرفون أن MusicXML موجود — اشرح أنه أنقذ حياة الكثيرين الذين احتاجوا تحويل نوتاتهم بين Sibelius و Finale.
- **اختبار التوافق:** إذا توفر MuseScore في المعمل، اطلب من الطلاب فتح MusicXML فيه مباشرة. الفرق بين Sibelius و MuseScore سيكون واضحاً لكن MusicXML يحافظ على البيانات الأساسية.
- **WAV vs MP3:** الفرق السمعي بين WAV و MP3 قد لا يكون واضحاً للطلاب على سماعات عادية. استخدم ملفاً صوتياً عالي الجودة في مكبرات جيدة للتوضيح.
- **مشكلة شائعة — Audio Export بطيء:** إذا كان التصدير الصوتي بطيئاً جداً، قلل من الـ Sample Rate إلى 22050 Hz للاختبار السريع، ثم استخدم 44100 Hz للتصدير النهائي.
- **مشكلة شائعة — Video Export يتوقف:** إذا توقف تصدير الفيديو، حاول إغلاق التطبيقات الأخرى لتوفير الذاكرة، أو قلل Resolution إلى 720p.
- **للطلاب المتقدمين:** اطلب منهم تصدير نفس المقطوعة إلى برنامجين مختلفين (Finale و MuseScore) ثم المقارنة — لاحظ الفروق في التنسيق.
- **للطلاب الأقل تقدماً:** ركز على التمارين 1 (MusicXML) و 2 (Audio) فقط. اترك Video و Online لجلسة لاحقة.
- **مشروع ختامي مقترح:** "أطلق مقطوعتك على الإنترنت" — اطلب من كل طالب:
  1. تصدير MusicXML
  2. تصدير WAV (أرشيف)
  3. تصدير MP3 (نشر)
  4. تصدير فيديو 1080p
  5. رفع الفيديو على YouTube
  6. رفع MP3 على SoundCloud
  7. إنشاء صفحة Notion للمشروع
  8. مشاركة الرابط مع الفصل
- **Sibelius و NotePerformer:** إذا كان NotePerformer مثبتاً، استخدمه لتصدير الصوت — جودته أعلى بكثير من Sibelius Default Sound Set.
