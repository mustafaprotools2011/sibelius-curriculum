# الدرس 55 | Lesson 55
## تقنيات Sibelius متقدمة — Engraving, Layout, Parts, Percussion, Shortcuts
## Advanced Sibelius Techniques — Engraving, Layout, Parts, Percussion, Shortcuts

هذا درس تقني بحت — لا مقام ولا إيقاع جديد اليوم. سنتعلم أدوات Sibelius المخفية التي تجعل نوتتك تبدو احترافية: قواعد النقش (Engraving Rules)، تحسين تخطيط الصفحات (Layout Optimization)، استخراج الأجزاء المنفردة (Parts)، كتابة الإيقاع (Percussion Notation)، وإنشاء اختصاراتك الخاصة (Custom Shortcuts).

---
### معلومات الدرس | Lesson Info

| AR | EN |
|----|----|
| **رقم الدرس** | 55 |
| **عنوان عربي** | تقنيات Sibelius متقدمة — Engraving, Layout, Parts, Percussion, Shortcuts |
| **English Title** | Advanced Sibelius Techniques — Engraving, Layout, Parts, Percussion, Shortcuts |
| **المقام** | لا يوجد — درس تقني محض |
| **الإيقاع** | لا يوجد — درس تقني محض |
| **الموضوع** | Engraving Rules, Layout Optimization, Part Extraction, Percussion Notation, Custom Shortcuts |

### الأهداف | Objectives
1. ضبط قواعد النقش (Engraving Rules) لجعل النوتة تبدو احترافية
2. تحسين تخطيط الصفحات (Layout) وتوزيع المازورات
3. استخراج الأجزاء المنفردة (Parts) من النوتة الكاملة (Full Score)
4. كتابة الإيقاع (Percussion Notation) باستخدام Drum Map
5. إنشاء اختصارات لوحة مفاتيح مخصصة (Custom Shortcuts)

---
### 1. النظري | Theory (10 min)

**لماذا Engraving مهم؟**

النوتة الموسيقية ليست مجرد نوتات — هي وثيقة بصرية. **Engraving** هو فن ترتيب النوتات والرموز على الصفحة بحيث تكون سهلة القراءة وجميلة المظهر. Sibelius يحتوي على محرك نقش (Engraving Engine) قوي جداً، لكن النتائج الافتراضية ليست دائماً مثالية.

**مبادئ النقش الأساسية (Engraving Principles):**

1. **المسافات المتساوية (Spacing):** النوتات يجب أن تتباعد بطريقة تعكس الزمن الموسيقي — النوتات الأطول تأخذ مساحة أقل، والنوتات الأقصر (Croche, Double Croche) تأخذ مساحة أكبر نسبياً.
2. **تجنب التصادمات (Collisions):** العلامات (Accidentals) والنقاط (Dots) والتعبيرات (Articulations) يجب ألا تتزاحم مع بعضها أو مع النوتات.
3. **اتجاه الأعواد (Stem Direction):** فوق الخط الأوسط للStaff → العود للأسفل. تحت الخط الأوسط → العود للأعلى. القاعدة بسيطة لكن Sibelius أحياناً يحتاج تعديلاً يدوياً.
4. **المازورات (Bars):** يجب توزيع المازورات بالتساوي عبر الصفحة — لا مازورات قصيرة جداً أو طويلة جداً في سطر واحد.

**ما هو Layout Optimization؟**

**Layout** يتحكم في كيفية ترتيب الصفحات: كم عدد المازورات في كل سطر (System)، كم عدد الأسطر في كل صفحة، حجم الهوامش (Margins)، وغيرها.

Sibelius لديه ثلاثة مفاهيم رئيسية:
- **Score:** المستند الكامل بكل آلاته
- **Part:** جزء منفرد لآلة واحدة — يُستخرج من الـ Score
- **System:** سطر واحد من الموسيقى في الـ Score أو الـ Part

**ما هي Percussion Notation؟**

كتابة الإيقاع (Percussion) في Sibelius تختلف عن كتابة النوتات اللحنية:
- كل آلة إيقاعية (Drum, Snare, Hi-Hat, Bass Drum) لها **صوت (Sound)** و**خط (Staff position)** خاص بها
- تستخدم **Drum Map** — خريطة تربط كل آلة بموضع معين على الـ Staff (بين الخطوط أو على الخطوط)
- رأس النوتة (Notehead) يختلف: Bass Drum له رأس دائري (Normal)، Snare له رأس بيضوي، Cymbal له رأس X

**الآلات الشائعة في Drum Map:**
| الآلة | الاختصار | موضع Staff | رأس النوتة |
|-------|---------|-----------|-----------|
| Bass Drum | BD | أول خط | Normal |
| Snare Drum | SD | ثالث مسافة | Normal |
| Hi-Hat (Closed) | HH | أول مسافة | X |
| Hi-Hat (Open) | HHO | أول مسافة | Circle X |
| Crash Cymbal | CC | أول خط إضافي (Leager line) | X |
| Ride Cymbal | RC | آخر خط | X |

**ما هي Custom Shortcuts؟**

Sibelius يسمح لك بإنشاء اختصارات لوحة مفاتيح (Keyboard Shortcuts) مخصصة لأي أمر أو أداة. هذا مفيد جداً للمهام المتكررة. يمكنك أيضاً حفظ ملف الـ Shortcuts لاستخدامه على أجهزة أخرى.

---
### 2. التطبيق العملي | Practice (30 min)

**تمرين 1: ضبط Engraving Rules (7 دقائق)**

1. افتح Sibelius → **Blank Score** → Treble Clef → 4/4 → اختر أي Key Signature
2. اكتب 4 مازورات عشوائية — مثلاً سلم Do-Re-Mi-Fa-Sol-La-Si-Do مع بعض Noires و Croches و Doubles Croches
3. الآن اذهب إلى:
   - **Appearance** tab → **Engraving Rules** (أو Ctrl+Shift+E على macOS، لكن على Windows هو في Appearance)
4. نافذة Engraving Rules ستظهر — فيها عدة صفحات:
   - **Notes and Tremolos:** هنا تتحكم في تباعد النوتات (Note Spacing). جرب تغيير **Fixed** و **Proportional** — أي واحد يعطيك مسافات أفضل؟
   - **Stems:** هنا تتحكم في طول الأعواد وزواياها. جرب تغيير **Minimum Stem Length** من 2.5 إلى 3.5 spaces — ماذا تتغير؟
   - **Ties:** تحكم في شكل ربطات التمديد (Ties)
   - **Beams:** تحكم في تجميع Croches و Doubles Croches

**خطوات محددة:**
5. في صفحة **Notes**:
   - قم بتغيير **Note Spacing** إلى Proportional (إذا لم يكن كذلك)
   - غير **Fixed Note Spacing** من 0.8 إلى 1.0 — لاحظ كيف تتباعد النوتات أكثر
6. في صفحة **Beams**:
   - غير **Beam Angle** إلى 2 (لإمالة طفيفة)
   - غير **Secondary Beam Break** إلى ON
7. اضغط **OK** لتطبيق التغييرات
8. الآن قارن بين شكل النوتة قبل وبعد — الفرق واضح في احترافية المظهر

**تمرين 2: تحسين Layout (7 دقائق)**

1. استمر في نفس الملف، أو افتح ملفاً جديداً بـ 16 مازورة
2. اذهب إلى:
   - **Layout** tab → **Page Setup** (أو Ctrl+Shift+R)
3. في نافذة Page Setup:
   - غير **Staff Size** من 7mm إلى 8mm — النوتات تصبح أكبر
   - غير **Margin Top** من 15mm إلى 20mm
4. عد إلى الـ Score الرئيسي:
   - استخدم **Layout** tab → **Auto Layout** — ثم جرب خيارات:
     - **Reset Space Between Staves:** يرجع المسافات بين الـ Staves للوضع الطبيعي
     - **Reset Space Between Systems:** يرجع المسافات بين الأسطر
     - **Reset Note Spacing:** يرجع تباعد النوتات
5. الآن جرب **Lock Format**:
   - **Layout** tab → **Format** → **Lock Format**
   - هذا يمنع Sibelius من تغيير التنسيق تلقائياً بعد التعديلات اليدوية

**توزيع المازورات يدوياً:**
6. اذهب إلى **Layout** tab → **Breaks** (مجموعة الأيقونات):
   - **System Break:** اضغط عليه لإنهاء السطر (System) عند مازورة معينة
   - **Page Break:** اضغط عليه لبدء صفحة جديدة
7. جرب هذا: ضع System Break كل 4 مازورات — سترى كل 4 مازورات في سطر واحد
8. ضع Page Break عند المازورة 13 — سترى بداية صفحة جديدة من المازورة 13

**تمرين 3: استخراج Parts (6 دقائق)**

1. أنشئ ملفاً بأكثر من آلة — مثلاً اختر **Wind Quintet** أو **String Quartet** من القوالب (Templates):
   - **File** → **New** → **Ensemble** → اختر **String Quartet**
2. اكتب 8 مازورات لكل آلة
3. الآن لاستخراج جزء منفرد:
   - اذهب إلى **Parts** tab → **New Part**
   - ستظهر نافذة **New Part**: اختر آلة واحدة — مثلاً **Violin I**
   - اضغط **OK**
4. ستظهر علامة تبويب جديدة (Tab) في أعلى Sibelius:
   - **Score:** النوتة الكاملة
   - **Violin I:** الجزء المنفرد للكمان الأول
5. لاحظ الفرق: الـ Part يحتوي فقط على آلة Violin I مع عنوان (Title) خاص
6. جرب ضبط Layout في الـ Part:
   - اذهب إلى **Layout** tab → **Page Setup** → غير الـ Margins لتكون أضيق (10mm لكل الجهات)
   - لماذا؟ لأن الـ Part يحتاج مساحة أكبر للنوتات من الـ Score
7. لاستخراج كل الـ Parts دفعة واحدة:
   - **Parts** tab → **Parts Gallery** → **Generate All Parts**
   - هذا ينشئ Part لكل آلة تلقائياً

**نصائح للـ Parts:**
- دائماً اضبط Layout الـ Parts بعد الاستخراج — الـ Parts تحتاج تنسيقاً مختلفاً عن الـ Score
- استخدم **Edit Part Appearance** (Parts tab → Edit Part Appearance) لتغيير شكل كل Part على حدة

**تمرين 4: كتابة الإيقاع (Percussion Notation) (5 دقائق)**

1. **File** → **New** → **Blank Score**
2. في نافذة New Score:
   - اختر **Drum Set** من قائمة الآلات (Percussion and Drums → Drum Set)
   - 4/4، أي Key Signature
3. ستظهر Staff واحدة عليها علامة **Drum Set** (مع رسم مجموعة طبول صغيرة)
4. ابدأ بكتابة النوتات:
   - اضغط **N** (Note Input mode)
   - الآن اكتب باستخدام الحروف:
     - **C** أو **D** → Bass Drum (أسفل الـ Staff)
     - **E** أو **F** → Snare (وسط الـ Staff)
     - **G** أو **A** → Hi-Hat (أعلى الـ Staff)
     - **B** → Crash Cymbal (أعلى بكثير)
5. لتغيير رأس النوتة (Notehead):
   - اختر النوتة → **Notation** tab → **Notehead** → اختر **Normal** أو **Cross** أو **Circle Cross**
   - مثلاً: Hi-Hat له Notehead Cross (X)، Bass Drum له Notehead Normal (دائرة)

**نمط إيقاعي تجريبي (4 مازورات):**

| مازورة 1 | Bass Drum (Noire) | Snare (Noire) | Hi-Hat (Noire) | Snare (Noire) |
| مازورة 2 | BD (Noire) | HH (Croche) | SD (Croche) | BD (Noire) | HH (Noire) |
| مازورة 3 | BD SD HH (Triolet, Ctrl+3) | BD SD HH (Triolet) | BD SD HH (Triolet) | BD SD HH (Triolet) |

6. جرب تغيير **Drum Map**:
   - اذهب إلى **Home** tab → **Instruments** (أو اضغط **I**)
   - اختر الـ Drum Set → **Edit Instrument**
   - في **Drum Map**، يمكنك تغيير Pitch لكل آلة
   - جرب تغيير Bass Drum من C2 إلى D2

7. أضف **Drum Fill** قصير:
   - استخدم **Triolet (Ctrl+3)** مع Bass Drum و Snare — هذا يعطي "دربكة" أو Fill جميل
   - اكتب BD-SD-BD-SD في Triolet على آخر مازورة

**تمرين 5: إنشاء Custom Shortcuts (5 دقائق)**

1. **File** → **Preferences** → **Keyboard Shortcuts** (أو اضغط على أيقونة الترس في Sibelius)
2. في نافذة Keyboard Shortcuts:
   - اكتب في حقل **Search** كلمة "Note Input" أو "Tuplet"
   - ابحث عن أمر **Note Input: Flip (X)** — هذا يقلب اتجاه العود (Stem Direction)
   - إذا لم يكن له اختصار، خصص واحداً: اضغط على **Next Key** ثم **Ctrl+Shift+X**
   - اضغط **Assign**

3. جرب تخصيص اختصار لـ **Engraving Rules**:
   - ابحث عن **Engraving Rules** في القائمة
   - اضغط على **Next Key** ثم **Ctrl+Shift+I**
   - اضغط **Assign**

4. أضف ثلاث اختصارات أخرى:
   - **Reset Position (Default Positions):** ابحث عن **Reset Position** → خصص **Ctrl+Alt+D**
   - **Optimize:** ابحث عن **Optimize** → خصص **Ctrl+Shift+O**
   - **Parts Gallery:** ابحث عن **Parts Gallery** → خصص **Ctrl+Shift+P**

5. احفظ إعدادات الـ Shortcuts:
   - اضغط على **Export** في أسفل نافذة Keyboard Shortcuts
   - احفظ الملف باسم `MySibeliusShortcuts.kys`
   - هذا الملف يمكنك استيراده (Import) على أي جهاز Sibelius آخر!

6. جرب الاختصار الجديد **Ctrl+Shift+X** على نوتة: اختر نوتة ثم اضغط Ctrl+Shift+X — سيتغير اتجاه العود

---
### 3. اختصارات Sibelius (5 min)

| # | الاختصار | الوظيفة | Function |
|---|---------|---------|----------|
| 1 | **Ctrl+Shift+I** | فتح نافذة Engraving Rules | Opens Engraving Rules window |
| 2 | **Ctrl+Alt+D** | إعادة تعيين وضع العناصر للوضع الافتراضي | Reset Position / Default Positions |
| 3 | **Ctrl+Shift+P** | فتح Parts Gallery | Opens Parts Gallery |
| 4 | **Ctrl+Shift+X** | قلب اتجاه العود (Stem Direction) | Flip Stem Direction |
| 5 | **Ctrl+Shift+O** | تحسين توزيع المازورات | Optimize Layout |

---
### 4. مراجعة وواجب | Review & HW (5 min)

**أسئلة المراجعة:**
1. ما الفرق بين الـ Score والـ Part في Sibelius؟ وكيف تستخرج Part من Score؟
2. ما هي أهم إعدادات Engraving Rules التي تؤثر على مظهر النوتة؟ اذكر اثنين.
3. كيف نكتب آلة إيقاعية مثل Snare Drum في Sibelius؟ بماذا تختلف عن كتابة نوتة لحنية؟

**الواجب المنزلي**
1. اكتب تمرين رقم (———) في كتاب الصولفيج المقرر
**الواجب:**
1. أنشئ مقطوعة لـ String Quartet (Violin I/II, Viola, Cello) — 16 مازورة
2. استخرج Part منفرد لكل آلة
3. طبق Engraving Rules: غير Note Spacing إلى Proportional وضبط Beam Angle
4. أضف 4 مازورات إيقاعية (Drum Set) في نهاية المقطوعة
5. أنشئ 3 اختصارات مخصصة من اختيارك واحفظها في ملف `MyShortcuts.kys`
6. احفظ باسم `Lesson55_AdvancedTechniques.sib`

---
### 5. تطبيق عملي | Practical Application

هذا درس تقني محض — لا يوجد تطبيق عود جديد. لكن يمكنك تطبيق أدوات Engraving على نوتة العود:
- اكتب تقسيماً لـ Maqam Rast على آلتك الموسيقية (8 مازورات)
- طبق **Engraving Rules** على نوتة العود
- استخرج **Part** منفرد للعود
- اضبط **Layout** بحيث تكون النوتة مقروءة

كتمرين إضافي للعود: أنشئ مقطوعة من 16 مازورة للعود فقط، وطبق كل تقنيات الدرس عليها.

---
### 6. التقييم | Assessment /15

| المعيار | ممتاز (3-5) | جيد (2) | يحتاج تحسين (1-0) | الدرجة |
|---------|------------|---------|-------------------|--------|
| **Engraving Rules** (3) | ضبط 3+ إعدادات بشكل صحيح مع شرح التغيير | ضبط إعدادين | لم يضبط أي إعداد | /3 |
| **Layout Optimization** (4) | استخدام System Break و Page Break + Staff Size صحيح | استخدم System Break فقط | لم يستخدم Breaks أو Staff Size غير مناسب | /4 |
| **Parts Extraction** (4) | استخراج 4 Parts + ضبط Layout لكل Part | استخراج 2-3 Parts | لم يستخرج Parts أو أخطاء في الاستخراج | /4 |
| **Percussion + Shortcuts** (4) | كتابة 3+ آلات إيقاعية + 3 اختصارات مخصصة | كتابة آلتين + اختصارين | كتابة آلة واحدة فقط أو أخطاء | /4 |
| **المجموع** | | | | **/15** |

---
### 7. مفردات الدرس | Vocabulary

| عربي | English | شرح |
|------|---------|------|
| نقش | Engraving | فن ترتيب النوتات والرموز على الصفحة |
| قواعد النقش | Engraving Rules | إعدادات Sibelius للتحكم في مظهر النوتة |
| تخطيط | Layout | ترتيب الصفحات والمازورات والأسطر |
| جزء منفرد | Part | نسخة من النوتة لآلة واحدة فقط |
| النوتة الكاملة | Score | المستند الكامل بكل الآلات |
| مسافة الـ Staff | Staff Size | حجم الـ Staff (المسافة بين خطين متجاورين) |
| كسر السطر | System Break | إنهاء سطر (System) عند مازورة معينة |
| كسر الصفحة | Page Break | بدء صفحة جديدة |
| خريطة الطبول | Drum Map | خريطة تربط كل آلة إيقاعية بموضع على الـ Staff |
| رأس النوتة | Notehead | شكل رأس النوتة (دائري، X، معين...) |
| اختصارات مخصصة | Custom Shortcuts | اختصارات لوحة مفاتيح من إنشاء المستخدم |
| تحسين توزيع | Optimize Layout | وظيفة توزع المازورات بشكل متساوٍ |

---
### 8. ملاحظات المدرس | Teacher Notes

- **هذا درس تقني بحت:** ذكر الطلاب أن اليوم لا يوجد مقام ولا إيقاع — سنتعلم كيف نجعل النوتة جميلة واحترافية.
- **التركيز على "أين تجد" كل أداة:** اشرح المسار بدقة (مثلاً: Appearance tab → Engraving Rules).
- **التبديل بين الـ Score والـ Parts:** أسهل طريقة لرؤية الفرق هي النقر على التبويبات أعلى الشاشة مباشرة.
- **Drum Map مربك للمبتدئين:** ابدأ بمثال بسيط — Bass Drum فقط + Snare فقط + Hi-Hat فقط. لا تدخل في تفاصيل كثيرة.
- **التفريق للطلاب المتقدمين:** اطلب منهم إنشاء Custom Shortcut لـ Staff Spacing أو System Object Positions.
- **للطلاب الأقل تقدماً:** ركز على تمرين Engraving Rules و Layout فقط، واترك الـ Parts و Percussion لجلسة لاحقة.
- **اقتراح استماع:** اجعل الطلاب يستمعون لمقطوعة كلاسيكية (مثل String Quartet لـ Mozart) وينظروا إلى Score و Parts منفصلة — لتوضيح لماذا الـ Parts مهمة.
- **ملف الـ Shortcuts (.kys):** شجع الطلاب على حفظ اختصاراتهم في ملف ومشاركته مع زملائهم — هذا مفيد جداً في مختبر Sibelius الجماعي.
- **المشكلة الشائعة:** بعد تغيير Engraving Rules، قد لا يظهر التغيير فوراً. اضغط **Ctrl+Z** ثم **Ctrl+Y** لتحديث الشاشة، أو اغلق الملف وافتحه مجدداً.
