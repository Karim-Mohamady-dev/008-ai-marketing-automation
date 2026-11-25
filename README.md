# Campaignly — 008-ai-marketing-automation

تخطط Campaignly الحملات، وتقسم جمهورك، وتكتب رسائل البريد والمنشورات التي تُرسل في موعدها.

## ما هذا المشروع؟

صفحة هبوط ثنائية اللغة (العربية RTL والإنجليزية LTR) لـ Campaignly. Campaignly plans campaigns, segments your audience, and drafts the emails and posts that go out on schedule.

## التشغيل محليا

```bash
npm install
npm run dev
npm run build
```

## المزايا

- مبدل لغة ظاهر، والتفضيل محفوظ في localStorage
- الترجمات في `locales/en/common.json` و `locales/ar/common.json`
- نموذج تجربة مجانية مع تحقق من البريد
- أقسام: البطل، المزايا، كيف يعمل، آراء نموذجية، الأسعار، الأسئلة الشائعة، الدعوة الأخيرة
- قسم كشف الشعار (tagline reveal) مع تحريك كلمة بكلمة
- الأسعار غير المؤكدة تظهر كعناصر نائبة `{{price}}`

## ملاحظات

- البيانات المعروضة تجريبية وموسومة كعينات.
- لا توجد أرقام أو شهادات مخترعة.
