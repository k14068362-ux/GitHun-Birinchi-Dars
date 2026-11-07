<!DOCTYPE html>
<html lang="uz"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta name="color-scheme" content="dark">
<title>Junior — Telegram bot dasturchi</title>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@500;700;800&family=Manrope:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{--bg:#101017;--card:#17171f;--ink:#f4f4f7;--mute:#9d9db2;--line:#272733;--red:#ff3b1f;color-scheme:dark;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
*{box-sizing:border-box}html{scroll-padding-top:env(safe-area-inset-top,0px);scroll-behavior:smooth}
body{margin:0;background:var(--bg);color:var(--ink);font:400 17px/1.65 Manrope,system-ui,sans-serif}
.wrap{max-width:960px;margin:0 auto;padding:0 24px}
nav{display:flex;justify-content:space-between;align-items:center;padding:22px 0}
nav b{font:800 20px 'Bricolage Grotesque',sans-serif}
nav a{color:var(--mute);text-decoration:none;margin-left:22px;font-weight:600}
nav a:hover,nav a:focus-visible{color:var(--red)}
.hero{position:relative;padding:48px 0 96px}
.hero::before{content:"";position:absolute;left:50%;top:-40px;width:900px;max-width:140%;height:520px;transform:translateX(-50%);background:radial-gradient(closest-side,rgba(255,59,31,.30),rgba(255,59,31,0));pointer-events:none}
.logo{position:relative;display:block;width:min(100%,640px);height:auto;margin:0 0 44px}
h1{position:relative;font:800 clamp(36px,6.4vw,68px)/1.04 'Bricolage Grotesque',sans-serif;letter-spacing:-.025em;margin:0 0 20px;max-width:15ch}
.hero p{position:relative;color:var(--mute);max-width:48ch;margin:0 0 32px}
.cta{position:relative;display:flex;align-items:center;gap:22px;flex-wrap:wrap}
.btn{background:var(--red);color:#fff;padding:15px 28px;border-radius:999px;text-decoration:none;font-weight:700;box-shadow:0 10px 30px -8px rgba(255,59,31,.7)}
.btn:hover{filter:brightness(1.1)}.btn:focus-visible{outline:3px solid #fff;outline-offset:3px}
.typing{display:flex;align-items:center;gap:6px;color:var(--mute);font-size:15px}
.typing i{width:9px;height:9px;border-radius:50%;background:var(--red);animation:b 1.2s infinite}
.typing i:nth-child(2){animation-delay:.18s}.typing i:nth-child(3){animation-delay:.36s}
@keyframes b{0%,60%,100%{transform:translateY(0);opacity:.45}30%{transform:translateY(-6px);opacity:1}}
@media(prefers-reduced-motion:reduce){.typing i{animation:none}}
section{padding:60px 0;border-top:1px solid var(--line)}
h2{font:700 32px 'Bricolage Grotesque',sans-serif;margin:0 0 28px;letter-spacing:-.01em}
.row{display:grid;grid-template-columns:210px 1fr;gap:24px;padding:20px 0;border-bottom:1px solid var(--line)}
.row:last-child{border:0}.row h3{margin:0;font:700 19px 'Bricolage Grotesque',sans-serif}.row p{margin:0;color:var(--mute)}
.proj{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:20px}
.p{background:var(--card);border:1px solid var(--line);border-top:3px solid var(--red);border-radius:12px;padding:24px}
.p h3{margin:0 0 8px;font:700 20px 'Bricolage Grotesque',sans-serif}.p p{margin:0 0 14px;color:var(--mute);font-size:16px}
.tags{display:flex;flex-wrap:wrap;gap:8px}.tags span,.skills span{font-size:14px;padding:3px 12px;border-radius:999px;border:1px solid var(--line);color:var(--mute)}
.skills{display:flex;flex-wrap:wrap;gap:10px}.skills span{font-size:16px;padding:8px 18px;color:var(--ink);font-weight:600;background:var(--card)}
.contact a{display:block;color:var(--red);font-weight:700;font-size:22px;margin:6px 0;text-decoration:none}
footer{padding:36px 0;color:var(--mute);font-size:15px;border-top:1px solid var(--line)}
@media(max-width:720px){.row{grid-template-columns:1fr;gap:6px}.hero{padding-bottom:64px}}
</style></head><body><div class="wrap">

<nav><b>Junior</b><div><a href="#loyihalar">Loyihalar</a><a href="#aloqa">Aloqa</a></div></nav>

<header class="hero">
<img class="logo" src="logo.png" alt="Junior logotipi">
<h1>Biznesingiz uchun Telegram botlar yasayman</h1>
<p>Buyurtma qabul qiladigan, mijozlarga javob beradigan va vaqtingizni tejaydigan botlar. Do'kon, salon va kafelar uchun.</p>
<div class="cta"><a class="btn" href="#aloqa">Bot buyurtma qilish</a><span class="typing" aria-hidden="true"><i></i><i></i><i></i>&nbsp;javob beraman</span></div>
</header>

<section><h2>Nima qila olaman</h2>
<div class="row"><h3>Buyurtma botlari</h3><p>Menyu, savat va buyurtmani egasiga yuboradigan bot. Lavash, kafe va do'konlar uchun.</p></div>
<div class="row"><h3>Navbat va yozilish</h3><p>Salon va xizmat ko'rsatuvchilar uchun: mijoz vaqt tanlaydi, siz ro'yxatni ko'rasiz.</p></div>
<div class="row"><h3>O'yin botlari</h3><p>Shashka va futbol kabi oddiy o'yinlar, do'stlar bilan Telegram ichida o'ynash uchun.</p></div></section>

<section id="loyihalar"><h2>Loyihalar</h2><div class="proj">
<div class="p"><h3>Shashka o'yini</h3><p>Ikki kishilik shashka. Yurishlar tekshiriladi, g'olib avtomatik aniqlanadi.</p><div class="tags"><span>Python</span><span>Telegram</span></div></div>
<div class="p"><h3>Futbol o'yini</h3><p>Telegramda o'ynaladigan yengil futbol o'yini.</p><div class="tags"><span>Python</span><span>Telegram</span></div></div>
<div class="p"><h3>Do'kon boti</h3><p>Mahalliy do'kon uchun katalog va buyurtma boti (namuna).</p><div class="tags"><span>Python</span><span>Buyurtma</span></div></div></div></section>

<section><h2>Texnologiyalar</h2><div class="skills"><span>Python</span><span>Telegram Bot API</span><span>aiogram</span><span>SQLite</span><span>Git</span></div></section>

<section id="aloqa" class="contact"><h2>Bog'laning</h2><p style="color:var(--mute);margin-top:0">Qanday bot kerakligini yozing.</p>
<a href="https://t.me/username">Telegram: @username</a><a href="mailto:ism@example.com">ism@example.com</a></section>

<footer>© 2026 Junior</footer></div></body></html>
