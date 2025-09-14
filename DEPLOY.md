# تعليمات سريعة للنشر (Vercel + إعدادات إضافية)

## نشر سريع على Vercel
1. ارفع المشروع إلى GitHub (أنشئ مستودع جديد وادفع الكود).
2. في Vercel: اضغط New Project > Import from Git > اختر المستودع > Deploy.
3. Vercel سيقوم بتشغيل `npm install` و `npm run build` تلقائيًا.

## إعداد متغيرات البيئة
- لإضافة Stripe أو مفاتيح سرية: في Vercel Dashboard > Settings > Environment Variables
- مثال: STRIPE_SECRET_KEY

## تشغيل الخادم محليًا
- npm install
- npm run dev
- افتح http://localhost:3000
