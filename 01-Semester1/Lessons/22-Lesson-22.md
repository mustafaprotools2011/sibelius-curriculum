# الدرس الثاني والعشرون: التدوين المتقدم بالقضبان وTuplets
## Lesson 22: Advanced Beaming & Tuplets

---

### 1. معلومات الدرس | Lesson Information

- **رقم الدرس:** 22
- **عنوان عربي:** التدوين المتقدم بالقضبان وTuplets
- **English Title:** Advanced Beaming & Tuplets
- **الوحدة:** 3 — الإيقاعات الخليجية | Gulf Rhythms
- **الأهداف | Objectives:**
  - فهم قواعد التجميع المتقدمة (Beaming) في الإيقاعات الخليجية
  - تعلم أنواع Tuplets المختلفة: Triplet, Quintuplet, Sextuplet
  - تطبيق Beaming يدوي وتلقائي في Sibelius
  - استخدام Tuplets مع الإيقاعات الخليجية
  - تحسين مظهر النوتة الموسيقية باستخدام Beaming الصحيح
- **المقام | Maqam:** عجم (Ajam / C Major)
- **الإيقاع | Rhythm:** تطبيقات Beaming و Tuplets على الإيقاعات الخليجية

---

### 2. النظري | Theory (10 دقائق)

#### الجزء 1: التدوين المتقدم بالقضبان | Advanced Beaming

**ما هو القضيب (Beam)؟**
القضيب هو الخط الذي يربط بين مجموعة من النوتات (Croches أو Double Croches أو أصغر) لتسهيل القراءة وتنظيم الإيقاع.

**قواعد Beaming الأساسية:**

| القاعدة | الشرح | مثال |
|---------|-------|------|
| 1. تجميع حسب الضربة | كل مجموعة تمثل ضربة واحدة | 2/4: تجميع Croches في زوج |
| 2. عدم تجميع عبر Barlines | لا يمر القضيب عبر خط المازورة | ممنوع |
| 3. تجميع متساوٍ | مجموعات متساوية العدد | 4/4: 4 مجموعات من 2 Croches |
| 4. تجميع Tuplets | Tuplets لها قضبان خاصة | 3:2 داخل القضيب |

**قواعد Beaming للإيقاعات الخليجية:**

**2/4 (الخبيتي، الهيوا، الليوا):**
```
صحيح:  | ♫  ♫  |  (2 مجموعتين من 2 Croches)
       | Dum Tak |
        
خطأ:   | ♪♪ ♪♪  |  (غير مجمعة)
```

**4/4 (البندري، الحربي، البستة):**
```
صحيح:  | ♫ ♫ ♫ ♫ |  (4 مجموعات من 2 Croches)
       | Dum Tak Dum Tak |

صحيح:  | ♬ ♬ |  (مجموعتين من 4 Double Croches)
```

**Beaming غير المتساوي (Cross-Bar Beaming):**
في بعض الإيقاعات الخليجية، قد نحتاج إلى تجميع غير متساوٍ:
```
| Dum . Tak Tak | Dum . .  |
| ♫  ♫  ♫♪ ♪♪  |  (2+2+2+2)
```

#### الجزء 2: Tuplets

**ما هو Tuplet؟**
Tuplet هو مجموعة من النوتات تُعزف ضمن مدة زمنية محددة، عادة ما تكون غير متساوية مع العدد الطبيعي للنوتات في تلك المدة.

**أنواع Tuplets الرئيسية:**

| النوع | العدد | الرمز | المدة | المثال |
|-------|-------|-------|-------|--------|
| Triplet | 3 | 3 | 3 نوتات في زمن 2 | 3 Croches في زمن 1 Noire |
| Quintuplet | 5 | 5 | 5 نوتات في زمن 4 | 5 Double Croches في زمن 1 Noire |
| Sextuplet | 6 | 6 | 6 نوتات في زمن 4 | 6 Double Croches في زمن 1 Noire |
| Septuplet | 7 | 7 | 7 نوتات في زمن 4 | 7 Double Croches في زمن 1 Noire |
| Duplet | 2 | 2 | 2 نوتات في زمن 3 | 2 Noires في زمن 3 Noires (6/8) |

**Tuplets في الإيقاعات الخليجية:**

**Triplet في الخبيتي:**
```
بدلاً من: | Dum Tak | (2 Croches)
يمكن:    | Dum 3♪♪♪ | (Triplet Croches — 3 نوتات في زمن 1 Noire)
```

**Triplet في البندري:**
```
| Dum 3♪♪♪ | Tak 3♪♪♪ | Dum 3♪♪♪ | Tak 3♪♪♪ |
(3 Croches لكل ضربة بدلاً من 2)
```

**Quintuplet في البستة:**
```
| Dum 5♪♪♪♪♪ | Dum . . . |
(5 Double Croches في زمن 1 Noire)
```

---

### 3. التطبيق العملي | Practice (30 دقيقة)

#### التمرين 1: Beaming اليدوي في Sibelius

1. افتح مشروع جديد (2/4, 8 مازورات):
2. اكتب نمط خبيتي بدون Beaming تلقائي:
   ```
   | C3.Croche C4.Croche | C3.Croche C4.Croche |
   ```
3. تطبيق Beaming يدوي:
   - حدد أول Croche
   - اضغط **Shift+B** → اختر **Beam Together**
   - أو استخدم **; (Semicolon)** لتبديل القضيب
4. كرر لكل مجموعة

5. جرب **Ctrl+Shift+B (Reset Beaming)** لرؤية الفرق

#### التمرين 2: Beaming في إيقاعات 4/4

1. افتح مشروع جديد (4/4, 8 مازورات)
2. اكتب نمط بندري:
   ```
   المازورة 1: | C3.Croche C3.Croche C4.Croche C4.Croche |
   ```
3. التجميع الصحيح: | ♫ ♫ | (مجموعتين من 2)

4. جرب التجميع الخاطئ ثم صححه:
   - اكتب 4 Croches متصلة
   - استخدم **; (Semicolon)** لفك التجميع عند منتصف المازورة

#### التمرين 3: Triplet في الإيقاعات الخليجية

**Triplet Croche في الخبيتي (2/4):**

1. في مازورة جديدة:
   - حدد قيمة **Noire** (5)
   - اضغط **Ctrl+3** لإنشاء Triplet
   - ثلاث Croches ستظهر في زمن Noire

2. كتابة Triplet يدوياً:
   ```
   الخطوة 1: اختر Noire (5)
   الخطوة 2: Ctrl+3
   الخطوة 3: اكتب C3, C4, C4 (Dum, Tak, Tak)
   
   النتيجة: | [3 C3 C4 C4] |
   ```

**Triplet في البندري (4/4):**
```
المازورة 1: | [3 C3 C3 C3] | C4.Croche C4.Croche |
معنى: 3 Dum في Triplet، ثم Tak-Tak
```

#### التمرين 4: Quintuplet و Sextuplet

**Quintuplet (5):**
1. اختر قيمة **Noire** (5)
2. اضغط **Ctrl+5** لإنشاء Quintuplet
3. اكتب 5 Double Croches:
   ```
   | [5 C3 C4 C3 C4 C4] |
   ```

**Sextuplet (6):**
1. اختر قيمة **Noire** (5)
2. اضغط **Ctrl+6** لإنشاء Sextuplet
3. اكتب 6 Double Croches:
   ```
   | [6 C3 C3 C4 C4 C4 C4] |
   ```

#### التمرين 5: Tuplets مع Beaming متقدم

اجمع بين Tuplets و Beaming في مقطوعة خليجية:

```
المازورة 1: | [3 C3 C4 C4] | [3 C3 C4 C4] |  (Triplets)
المازورة 2: | ♫ ♫ | (Croches عادية)
المازورة 3: | [5 C3 C4 C4 C3 C4] | (Quintuplet)
المازورة 4: | [6 C3 C3 C4 C4 C4 C4] | (Sextuplet)
```

**تعديل Beaming للTuplets:**
- حدد الTuplet → **Appearance → Reset Beaming**
- أو استخدم **Shift+B** لتعديل التجميع داخل الTuplet

---

### 4. اختصارات Sibelius (5 دقائق)

| الاختصار | الوظيفة | العربية |
|----------|---------|---------|
| **Ctrl+3** | Create Triplet / إنشاء Triplet | ثلاثي |
| **Ctrl+5** | Create Quintuplet / إنشاء Quintuplet | خماسي |
| **Ctrl+6** | Create Sextuplet / إنشاء Sextuplet | سداسي |
| **; (Semicolon)** | Toggle Beam / تبديل القضيب | تبديل قضيب |
| **Shift+B** | Beam Groups / مجموعات التجميع | تجميع |

---

### 5. مراجعة وواجب | Review & Homework (5 دقائق)

#### أسئلة المراجعة | Review Questions

1. **ما الاختصار لإنشاء Triplet في Sibelius؟**
   - *Ctrl+3*

2. **كم عدد النوتات في Quintuplet و Sextuplet على التوالي؟**
   - *5 نوتات (Quintuplet)، 6 نوتات (Sextuplet)*

3. **متى نستخدم القضيب (Beam) بين النوتات؟**
   - *لربط Croches أو Double Croches التي تنتمي لنفس الضربة*

#### واجب منزلي | Homework

**الواجب: مقطوعة Tuplets الخليجية**

أنشئ مقطوعة من 16 مازورة (4/4) تحتوي على:
- 4 مازورات بندري عادي (Croches)
- 4 مازورات بندري مع Triplets (Ctrl+3)
- 4 مازورات بندري مع Quintuplets (Ctrl+5)
- 4 مازورات بندري مع Sextuplets (Ctrl+6)
- Beaming صحيح في جميع المازورات
- صدر PDF باسم `Advanced_Beaming_Tuplets_HW`

---

### 6. تطبيق عملي | Practical Application

#### تمرين على آلتك الموسيقية

**Triplet على العود:**
```
رشة Dum + Tak-Tak (3 نوتات متساوية في زمن Noire)

| [3 Dum Tak Tak] | [3 Dum Tak Tak] |
| Dum Dum . .     | Tak Tak . .     |
```

**Sextuplet على الإيقاع (رق):**
```
6 نقرات سريعة في زمن Noire واحدة

| [6 Dum Dum Tak Tak Tak Tak] |
| (يمين-يمين-يسار-يسار-يسار-يسار) |
```

**تمارين إضافية:**
- جرب Quintuplet بسرعة ♩ = 100
- جرب Sextuplet بسرعة ♩ = 120
- أضف Tuplets إلى إيقاع الحربي

---

### 7. التقييم | Assessment

| المعيار | ممتاز (5) | جيد (4) | مقبول (3) | ضعيف (1-2) |
|---------|:---------:|:-------:|:---------:|:----------:|
| Beaming صحيح | يطبق جميع القواعد | معظمها صحيح | بعض الأخطاء | لا يطبق |
| Triplet | صحيح + متنوع | صحيح أساسي | أخطاء في الإنشاء | لم ينفذ |
| Quintuplet/Sextuplet | صحيح + تطبيق إيقاعي | صحيح أساسي | أخطاء | لم ينفذ |
| التطبيق العملي | يعزف Tuplets بثقة | يعزف Triplet فقط | صعوبة في العزف | لا يعزف |

---

### 8. مفردات الدرس | Vocabulary

| العربية | English | الشرح |
|---------|---------|-------|
| قضيب | Beam | خط يصل النوتات |
| تجميع | Beaming | عملية ربط النوتات بقضبان |
| ثلاثي | Triplet | 3 نوتات في زمن نوتتين |
| خماسي | Quintuplet | 5 نوتات في زمن 4 |
| سداسي | Sextuplet | 6 نوتات في زمن 4 |
| تحرير القضبان | Beam Editing | تعديل التجميع يدوياً |
| إعادة تعيين | Reset Beaming | إعادة التجميع التلقائي |

---

### 9. ملاحظات المدرس | Teacher Notes

- Beaming هو مفتاح القراءة الجيدة — لا تسمح للطلاب بتجاهل قواعد التجميع
- Tuplets تمثل تحدياً — ابدأ بـ Triplet (الأسهل) وانتقل تدريجياً
- Quintuplet و Sextuplet قد تكون صعبة على الطلاب في العزف — ركز على التدوين
- استخدم **Playback** في Sibelius لسماع الفرق بين Croches العادية و Tuplets
- تذكر أن Tuplets في السياق الخليجي ليس شائعاً جداً — هذه مهارة تدوينية متقدمة
- الدرس القادم: المزامنة والإيقاعات المتقاطعة
