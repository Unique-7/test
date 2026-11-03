# TestHub — O'quvchilar Test Platformasi

## Ishlash tartibi

### 1. Demo rejim (hoziroq ishlatish)
`index.html` faylini brauzerda oching. Ma'lumotlar faqat shu qurilmada saqlanadi.

### 2. Online rejim (telefon + noutbuk birgalikda)

**Firebase ulash (bepul):**
1. https://console.firebase.google.com/ → Yangi loyiha yarating
2. Realtime Database → "Test rejimida boshlash"
3. Loyiha sozlamalari (⚙️) → "Your apps" → Web (`</>`) → Ilovani ro'yxatdan o'tkazing
4. Config kodni nusxalang
5. Platformada **🔧 Sozlama** → Firebase ma'lumotlarini kiriting → Saqlash

### 3. GitHub Pages (istalgan joydan kirish)

```bash
git init
git add .
git commit -m "TestHub"
# GitHub'da repo oching, keyin:
git remote add origin https://github.com/SIZNING/REPO.git
git push -u origin main
```

Repo Settings → Pages → Branch: main → Save

URL: `https://SIZNING.github.io/REPO`

---

## Titul varoq haqida

- A4 qog'ozda **2 ta** titul varoq chiqadi (qirqib olinadi)
- Har bir varoqda **4 ta burchak markeri** bor (skaner uchun)
- OMR uslubdagi **belgilash doiralari**: A, B, C, D
- O'quvchining **ID si** va ismi yozilgan

## Skaner

- Kamerani yoqing → Titul varoqni ramkaga to'g'rilang
- Yoki rasmni yuklang
- Javoblarni qo'lda ham kiritish mumkin

## Natijalar

- Real vaqtda Firebase'da saqlanadi
- Telefon + noutbuk birgalikda ko'radi
- Excel va PDF yuklab olish
