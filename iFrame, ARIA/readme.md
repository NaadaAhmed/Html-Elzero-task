
# 💻  iFrame, ARIA

## 📝 وصف التاسك
في هذا التكليف تم التعرف على العناصر المناسبة لكل نوع من المحتوى داخل الصفحة مثل العناوين، الأقسام، الفقرات،  
وكيفية استخدام السمات الخاصة بإتاحة الوصول **(Accessibility)** عن طريق خصائص **ARIA** لتحسين تجربة المستخدمين،  
وكمان تم التعرف على أفضل الممارسات في كتابة الأرقام والنصوص بشكل مفهوم للجميع.

---

## 💡 أهم النقاط في التاسك

- استخدام العناصر الصحيحة في مكانها المناسب مثل:
  - `<h1>` ليكون عنوان الصفحة.
  - `<h2>` للعناوين الفرعية داخل الأقسام.
  - `<p>` للفقرات النصية.
  - `<input type="submit">` أو `<button type="submit">` لإرسال البيانات في النماذج.
- تحديد لغة الصفحة باستخدام الخاصية `lang` داخل وسم `<html>`.
- تطبيق خصائص **ARIA** مثل:
  - `role="group"` لتجميع عناصر مرتبطة.
  - `aria-labelledby="skills-label"` لربط المجموعة بعنوانها.

---

## 💬 مثال عملي

```html
<div class="choose-skill" role="group" aria-labelledby="skills-label">
  <h2 id="skills-label">Choose Your Skills</h2>

  <div class="skill">
    <input type="checkbox" id="python" name="skills" value="Python" />
    <label for="python">Python</label>
  </div>

  <div class="skill">
    <input type="checkbox" id="php" name="skills" value="PHP" />
    <label for="php">PHP</label>
  </div>

  <div class="skill">
    <input type="checkbox" id="javascript" name="skills" value="JavaScript" />
    <label for="javascript">JavaScript</label>
  </div>
</div>
````

---

## 👩‍💻 نبذة عني

أنا **ندى أحمد حسن**، خريجة كلية الآداب قسم **نظم المعلومات الجغرافية (GIS)**.
بحب مجال **Front-End Development** ولسه في بداية طريقي فيه.
اتعلمت من كورس **أسامة الزيرو** وبتدرّب حاليًا على **HTML وCSS وJavaScript**
علشان أطور نفسي وأبني مشاريع احترافية في المستقبل ❤️


