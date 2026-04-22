# AI Code Playground

موقع ذكاء اصطناعي لكتابة وتشغيل الكود مباشرة.

## طريقة الرفع على Vercel (5 دقائق)

### الخطوة 1 — حمّل المشروع على GitHub
1. روح على https://github.com/new
2. سمّي الـ repo مثلاً: `ai-code-playground`
3. ارفع ملفات المشروع (api/chat.js, public/index.html, vercel.json, package.json)

### الخطوة 2 — ارفع على Vercel
1. روح على https://vercel.com وسجل دخول بحساب GitHub
2. اضغط "Add New Project"
3. اختر الـ repo اللي رفعته
4. اضغط Deploy

### الخطوة 3 — أضف الـ API Key
1. في Vercel، روح على Settings → Environment Variables
2. أضف متغير جديد:
   - Name: `ANTHROPIC_API_KEY`
   - Value: مفتاحك من https://console.anthropic.com
3. اضغط Save ثم أعد النشر (Redeploy)

### الخطوة 4 — شوف موقعك!
Vercel بعطيك رابط مثل: `https://ai-code-playground.vercel.app`

---

## هيكل المشروع

```
ai-playground/
├── api/
│   └── chat.js          ← الـ backend (يخبي الـ API key)
├── public/
│   └── index.html       ← الواجهة الأمامية
├── vercel.json          ← إعدادات Vercel
└── package.json
```
