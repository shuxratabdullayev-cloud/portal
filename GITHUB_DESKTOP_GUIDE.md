# 🖥️ GitHub Desktop Orqali Deploy Qilish

## 1️⃣ GitHub Desktop O'rnatish

1. Quyidagi havoladan yuklab oling:
   **https://desktop.github.com/**

2. O'rnatib, GitHub akkauntingiz bilan kiring

## 2️⃣ Yangi Repozitoriya Yaratish

1. GitHub Desktop'ni oching
2. **File** → **New Repository** ni tanlang
3. Quyidagi ma'lumotlarni kiriting:
   - **Name:** `shuxratabdullayev-cloud.github.io`
   - **Local Path:** `C:\Users\Admin\.gemini\antigravity\scratch`
   - **Initialize with README:** ❌ (belgilamang)
4. **Create Repository** tugmasini bosing

## 3️⃣ Fayllarni Tashkil Qilish

### MUHIM: Fayllarni to'g'ri joylashtirish

Hozir sizda fayllar quyidagicha:
```
scratch/
├── bosh_sahifa/
│   └── index.html
├── buxgalteriya_trenajyor/
├── kassa_tizimi/
└── ...
```

**Kerak bo'lgan struktura:**
```
scratch/
├── index.html          (bosh_sahifa/index.html dan ko'chirish)
├── manifest.json       (bosh_sahifa/manifest.json dan)
├── sw.js              (bosh_sahifa/sw.js dan)
├── AMALIY_VAZIFALAR.html (bosh_sahifa/AMALIY_VAZIFALAR.html dan)
├── buxgalteriya_trenajyor/
├── kassa_tizimi/
└── ...
```

### Qanday qilish kerak:

1. `bosh_sahifa/index.html` faylini **ko'chiring** (copy)
2. `scratch` papkasiga **joylashtiring** (paste)
3. `bosh_sahifa/manifest.json` va `bosh_sahifa/sw.js` ni ham xuddi shunday qiling
4. `bosh_sahifa/AMALIY_VAZIFALAR.html` ni ham ko'chiring

## 4️⃣ index.html Faylini Tuzatish

Ko'chirilgan `index.html` faylidagi havolalarni tuzatish kerak:

**Eski (bosh_sahifa ichida):**
```html
<a href="../buxgalteriya_trenajyor/index.html">
```

**Yangi (scratch asosida):**
```html
<a href="./buxgalteriya_trenajyor/index.html">
```

Barcha `../` ni `./` ga o'zgartiring!

## 5️⃣ Commit va Push

1. GitHub Desktop'da o'zgarishlar ko'rinadi
2. Pastda **Summary** ga yozing: `Initial commit: Portal`
3. **Commit to main** tugmasini bosing
4. Yuqorida **Publish repository** tugmasini bosing
5. ✅ **Keep this code private** ni **OCHING** (public bo'lishi kerak)
6. **Publish Repository** ni bosing

## 6️⃣ GitHub Pages Yoqish

1. Brauzerda GitHub'ga kiring: https://github.com
2. `shuxratabdullayev-cloud.github.io` repozitoriyasini oching
3. **Settings** → **Pages** ga o'ting
4. **Branch:** `main` ni tanlang
5. **Folder:** `/ (root)` ni tanlang
6. **Save** tugmasini bosing

## 7️⃣ Kutish va Tekshirish

- 2-3 daqiqa kuting
- Keyin ochib ko'ring: **https://shuxratabdullayev-cloud.github.io**

---

## ✅ Muvaffaqiyat Belgisi

Agar sahifa ochilsa - BARAKALLA! 🎉
Agar 404 chiqsa - havolalarni tekshiring (../ → ./)
