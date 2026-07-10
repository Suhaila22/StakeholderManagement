# StakeSphere — حزمة النشر الكاملة | Full Deployment Package

هذه الحزمة تحتوي على صفحة الهبوط والتطبيق معاً، جاهزة للنشر دفعة واحدة.
This package contains the landing page and the app together, ready to publish as one.

## الملفات | Files
- `index.html` — صفحة الهبوط (الصفحة الرئيسية) | the landing page (home)
- `app.html`   — التطبيق الكامل، ملف مستقل يعمل بلا خادم | the full app, self-contained, no server needed

أزرار "ابدأ مجاناً" و"شاهد عرضاً" في صفحة الهبوط تفتح التطبيق تلقائياً.
The "Start free" / "See demo" buttons on the landing page open the app automatically.

## كيف تنشرينها | How to publish

### الخيار الأسهل — Netlify Drop (بدون حساب، دقيقة واحدة)
1. اذهبي إلى https://app.netlify.com/drop
2. اسحبي هذا المجلد كاملاً إلى الصفحة
3. ستحصلين على رابط مباشر فوراً — انتهى ✅

### الخيار الثاني — GitHub Pages (مجاني ودائم)
1. أنشئي مستودعاً جديداً على GitHub
2. ارفعي `index.html` و `app.html`
3. Settings → Pages → Source: main branch → Save
4. الرابط: `https://<username>.github.io/<repo>/`

### الخيار الثالث — Vercel / Cloudflare Pages
اسحبي المجلد أو اربطيه بمستودع GitHub — يكتشف الملفات تلقائياً.

## ملاحظات | Notes
- كلا الملفين يعملان بفتحهما مباشرة في المتصفح (لا يحتاجان بناءً أو تثبيتاً).
- الخطوط تُحمّل من Google Fonts (يلزم اتصال إنترنت لأول تحميل).
- لتغيير رابط شعار أو زر، حرّري `index.html` بأي محرر نصوص.

Powered by Boost Consulting & Training
