# Tillaboyev Xojiakbar — shaxsiy portfolio

GitHub Pages uchun tayyor statik sayt. Backend, npm yoki server kerak emas.

## Joylash

1. GitHub'da **public** repository yarating: `xojiakbar-portfolio`. README qo'shmang (agar ZIP fayllarni birinchi marta yuklayotgan bo'lsangiz).
2. Ushbu papkaning **ichidagi** `index.html`, `placeholder-avatar.svg`, `favicon.svg`, `.nojekyll`, `README.md` fayllarini repository ildiziga (`/`) yuklang. **ZIP faylning o'zini yuklamang:** `index.html` GitHub'da alohida ko'rinishi kerak. GitHub web orqali upload yashirin `.nojekyll` faylini qabul qilmasa, bu fayl shart emas.
3. GitHub repository ichida: **Settings → Pages → Build and deployment → Source: Deploy from a branch** ni tanlang. `main` va `/(root)` ni tanlab **Save** bosing.
4. Nashrdan so'ng manzil: `https://Xojiakbarr7.github.io/xojiakbar-portfolio/`.

## Suratni barcha foydalanuvchilar uchun qo'shish

Shaxsiy haqiqiy suratingizni `image_23b677.jpg` nomi bilan repo ildiziga yuklang. Saytdagi barcha tasvirlar avtomatik uni ko'rsatadi. Rasm yuklanmagunicha `TX` belgisi ko'rsatiladi.

Saytdagi **Rasmni yuklash** tugmasi orqali tanlangan surat brauzer xotirasiga yoziladi va **faqat shu qurilmada/brauzerda** saqlanadi. Hamma ko'rishi uchun rasmingizni albatta GitHub repositoryga yuklang.

## Tekshirish

`index.html` faylini brauzerda oching yoki lokal tekshirish uchun shu papkada `python -m http.server 8000` ishga tushirib `http://localhost:8000` ga kiring.

Tailwind CSS, Three.js, Font Awesome va Google Fonts CDN orqali yuklanadi. To'liq dizayn uchun internet kerak. Agar WebGL qo'llab-quvvatlanmasa, 3D fon ishlamasligi mumkin, lekin sahifa navigatsiyasi ishlashda davom etadi.

**Eslatma:** ROI kalkulyatordagi natijalar namuna hisoblash modeliga asoslanadi, kafolatlangan natija emas. Aloqa formasi Telegram'ni ochadi; saytda server yoki murojaatlarni saqlovchi ma'lumotlar bazasi mavjud emas.
