# Study Manager Cloud

## GitHub Pages
1. GitHub repository ichidagi eski `index.html` faylini shu yangi `index.html` bilan almashtiring.
2. Commit changes qiling.
3. Settings → Pages → Deploy from a branch → main → /(root) tanlangan bo‘lsin.
4. Saytni oching va Supabase'da oldindan yaratgan email/parol bilan kiring.

## Supabase
- Ushbu fayl Supabase JS v2 CDN orqali ulanadi.
- Project URL va Publishable key fayl ichiga kiritilgan.
- `Secret` yoki `service_role` kalit ishlatilmaydi.
- Ma'lumotlar RLS bilan himoyalangan. Har bir foydalanuvchi faqat o‘zining qatorlarini ko‘radi.
- SQL jadvallari `groups`, `students`, `orders`, `payments` nomlari va avval yaratilgan ustunlar bilan mos bo‘lishi kerak.

## Eslatma
Agar login xatosi chiqsa, Supabase Authentication → Users ichidagi foydalanuvchining emaili va parolini tekshiring. Bu versiyada foydalanuvchi ro‘yxatdan o‘tishi o‘chiq; admin yaratgan login ishlatiladi.
