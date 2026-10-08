# Moliya Hisobchi — Telegram Mini App

Professional Telegram Mini App + bot backend.

## Asosiy imkoniyatlar
- Telegram Mini App
- Daromad/xarajat qo‘shish
- Balans va tarix
- Chatdan avtomatik yozuv: `5000 oldim` → daromad +5000
- Chatdan xarajat: `5000 sarfladim` / `5000 xarajat`
- SQLite baza
- Telegram foydalanuvchisi bo‘yicha alohida hisob
- Yashil premium responsive dizayn
- Bot komandalar: /start, /app, /balans, /hisobot
- Mini App Telegram WebApp SDK bilan ishlaydi

## O‘rnatish
1. Node.js 18+ o‘rnating.
2. `npm install`
3. `.env.example` ni `.env` qilib nusxalang.
4. BOT_TOKEN ga BotFather tokenini yozing.
5. `WEBAPP_URL` ga HTTPS Mini App manzilini yozing.
6. `npm start`

## Webhook
Server ishga tushgandan keyin:
`https://YOUR-DOMAIN.com/api/setup-webhook`

Yoki brauzerda shu URLni oching.

## Muhim
Bot tokenini ZIP ichiga kiritmang. `.env` serverda saqlanadi.
Mini App HTTPS manzilda ishlashi kerak.
