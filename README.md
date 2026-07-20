[Uploading index (2).html…]()
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>START — заработок на привлечении курьеров</title>
<meta name="description" content="Приводите курьеров в доставку и получайте до 60 000 ₽ с одного человека. Бесплатное обучение, выплаты дважды в месяц, 20+ городов России.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Unbounded:wght@600;800&family=Inter:wght@400;500;600;700&family=IBM+Plex+Mono:wght@500;700&display=swap" rel="stylesheet">
<style>
:root{
  --night:#12131A;
  --slate:#1E2029;
  --fog:#F5F4F0;
  --paper:#FFFFFF;
  --line:#E4E2DC;
  --line-dark:#2C2E38;
  --muted:#6B6D77;
  --lime:#C8F04A;
  --lime-deep:#8FB010;
  --ink:#12131A;
  --r:16px;
  --max:1140px;
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth;-webkit-text-size-adjust:100%}
body{
  background:var(--fog);color:var(--ink);
  font:400 16px/1.65 'Inter',system-ui,-apple-system,sans-serif;
  -webkit-font-smoothing:antialiased;overflow-x:hidden;
}
.wrap{max-width:var(--max);margin:0 auto;padding:0 24px}
h1,h2,h3{font-family:'Unbounded',sans-serif;letter-spacing:-.03em;line-height:1.08}
a{color:inherit}
.mono{font-family:'IBM Plex Mono',monospace}

/* ============ NAV ============ */
nav{position:sticky;top:0;z-index:100;background:rgba(18,19,26,.94);backdrop-filter:blur(14px);border-bottom:1px solid var(--line-dark)}
.nav-in{display:flex;align-items:center;justify-content:space-between;gap:20px;padding:15px 0}
.logo{display:flex;align-items:center;gap:11px;color:#fff;font-family:'Unbounded';font-weight:800;font-size:16px;letter-spacing:-.02em;text-decoration:none}
.logo i{width:26px;height:26px;border-radius:8px;background:var(--lime);display:grid;place-items:center;font-style:normal;color:var(--night);font-size:14px;font-weight:800}
.nav-links{display:flex;gap:26px;font-size:14px;font-weight:500}
.nav-links a{color:#A7A9B4;text-decoration:none;transition:.15s}
.nav-links a:hover{color:#fff}
.nav-cta{background:var(--lime);color:var(--night);padding:10px 20px;border-radius:10px;font-weight:700;font-size:14px;text-decoration:none;white-space:nowrap;transition:.15s}
.nav-cta:hover{background:#d5fa62}
@media(max-width:900px){.nav-links{display:none}}

/* ============ HERO ============ */
.hero{background:var(--night);color:#fff;padding:80px 0 90px;position:relative;overflow:hidden}
.hero::after{
  content:"";position:absolute;right:-180px;top:-120px;width:620px;height:620px;
  background:radial-gradient(circle,rgba(200,240,74,.12),transparent 62%);pointer-events:none;
}
.hero-in{position:relative;z-index:2;display:grid;grid-template-columns:1.15fr .85fr;gap:60px;align-items:center}
@media(max-width:940px){.hero-in{grid-template-columns:1fr;gap:44px}}
.badge{
  display:inline-flex;align-items:center;gap:9px;padding:7px 14px;border-radius:99px;
  border:1px solid var(--line-dark);background:#191B24;font-size:13px;font-weight:600;color:#C9CBD4;margin-bottom:26px;
}
.badge .pulse{width:7px;height:7px;border-radius:50%;background:var(--lime);box-shadow:0 0 0 0 rgba(200,240,74,.6);animation:p 2.4s infinite}
@keyframes p{70%{box-shadow:0 0 0 9px rgba(200,240,74,0)}100%{box-shadow:0 0 0 0 rgba(200,240,74,0)}}
.hero h1{font-size:clamp(34px,5.4vw,60px);font-weight:800}
.hero h1 mark{background:none;color:var(--lime)}
.hero p.lede{margin-top:24px;font-size:18px;color:#B4B6C0;max-width:52ch}
.hero-btns{display:flex;gap:12px;flex-wrap:wrap;margin-top:34px}
.btn{display:inline-block;padding:15px 28px;border-radius:12px;font-weight:700;font-size:15px;text-decoration:none;border:1px solid transparent;cursor:pointer;transition:.16s;font-family:'Inter'}
.btn-lime{background:var(--lime);color:var(--night)}
.btn-lime:hover{background:#d5fa62;transform:translateY(-1px)}
.btn-ghost{border-color:#383A45;color:#fff;background:transparent}
.btn-ghost:hover{background:#1E2029}
.hero-stats{display:flex;gap:34px;margin-top:44px;flex-wrap:wrap}
.hero-stats div .n{font-family:'Unbounded';font-weight:800;font-size:26px;color:var(--lime);letter-spacing:-.03em}
.hero-stats div .l{font-size:13px;color:#8A8C97;margin-top:3px}

.hero-card{background:#191B24;border:1px solid var(--line-dark);border-radius:20px;padding:30px}
.hero-card .cap{font-family:'IBM Plex Mono';font-size:11px;letter-spacing:.16em;text-transform:uppercase;color:#7C7E8A;margin-bottom:18px}
.pay-row{display:flex;justify-content:space-between;align-items:center;padding:13px 0;border-bottom:1px solid var(--line-dark);font-size:14px;color:#C9CBD4}
.pay-row:last-of-type{border-bottom:0}
.pay-row b{font-family:'IBM Plex Mono';color:#fff;font-size:15px}
.hero-card .tot{margin-top:20px;padding-top:20px;border-top:2px solid var(--lime);display:flex;justify-content:space-between;align-items:baseline}
.hero-card .tot span{font-size:13px;color:#8A8C97}
.hero-card .tot b{font-family:'Unbounded';font-weight:800;font-size:30px;color:var(--lime);letter-spacing:-.03em}

/* ============ GENERIC SECTION ============ */
section{padding:86px 0}
.eyebrow{font-family:'IBM Plex Mono';font-size:11px;font-weight:700;letter-spacing:.18em;text-transform:uppercase;color:var(--lime-deep);margin-bottom:14px}
.sec-h{font-size:clamp(27px,4vw,42px);font-weight:800;max-width:20ch}
.sec-p{color:var(--muted);max-width:62ch;margin-top:16px;font-size:17px}


/* ============ INTRO ============ */
.intro{background:var(--paper);border-bottom:1px solid var(--line);padding:74px 0}
.intro-grid{display:grid;grid-template-columns:1fr 1fr;gap:64px;align-items:start}
@media(max-width:900px){.intro-grid{grid-template-columns:1fr;gap:36px}}
.intro h2{font-size:clamp(25px,3.6vw,36px);font-weight:800;max-width:18ch}
.intro .p{color:#3C3E46;font-size:17px;margin-top:20px;max-width:60ch}
.intro .p + .p{margin-top:15px}
.sign{display:flex;align-items:center;gap:15px;margin-top:30px;padding-top:24px;border-top:1px solid var(--line)}
.sign .av{width:52px;height:52px;border-radius:50%;background:var(--night);color:var(--lime);display:grid;place-items:center;font-family:'Unbounded';font-weight:800;font-size:19px;flex:none}
.sign .who b{display:block;font-size:15px;font-weight:600}
.sign .who span{font-size:13px;color:var(--muted)}
.facts{display:grid;gap:12px}
.fact{display:grid;grid-template-columns:38px 1fr;gap:16px;padding:19px 21px;border:1px solid var(--line);border-radius:13px;background:var(--fog);align-items:center}
.fact .fi{width:38px;height:38px;border-radius:10px;background:var(--paper);border:1px solid var(--line);display:grid;place-items:center;font-size:16px}
.fact b{display:block;font-size:15px;font-weight:600}
.fact span{margin-top:4px;display:block}
.fact span{font-size:14px;color:var(--muted);line-height:1.55}

/* ============ WHAT IS IT ============ */
.what{background:var(--paper);border-top:1px solid var(--line);border-bottom:1px solid var(--line)}
.what-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:44px}
@media(max-width:880px){.what-grid{grid-template-columns:1fr}}
.wcard{border:1px solid var(--line);border-radius:var(--r);padding:28px;background:var(--fog);transition:.18s}
.wcard:hover{border-color:var(--ink);transform:translateY(-2px)}
.wcard .ic{width:44px;height:44px;border-radius:12px;background:var(--night);color:var(--lime);display:grid;place-items:center;font-size:19px;margin-bottom:18px}
.wcard h3{font-size:17px;font-weight:600;margin-bottom:9px}
.wcard p{font-size:15px;color:var(--muted)}

/* ============ STEPS ============ */
.steps{counter-reset:s;display:grid;gap:0;margin-top:46px;border-top:1px solid var(--line)}
.step{
  counter-increment:s;display:grid;grid-template-columns:78px 1fr;gap:26px;
  padding:30px 0;border-bottom:1px solid var(--line);align-items:start;
}
.step::before{
  content:counter(s,decimal-leading-zero);font-family:'IBM Plex Mono';font-weight:700;
  font-size:26px;color:var(--line);letter-spacing:-.02em;
}
.step:hover::before{color:var(--lime-deep)}
.step h3{font-size:19px;font-weight:600;margin-bottom:8px}
.step p{color:var(--muted);font-size:15px;max-width:66ch}
@media(max-width:640px){.step{grid-template-columns:52px 1fr;gap:16px}.step::before{font-size:20px}}

/* ============ TRAINING (dark band) ============ */
.train{background:var(--night);color:#fff}
.train .sec-p{color:#A7A9B4}
.train-grid{display:grid;grid-template-columns:1fr 1fr;gap:60px;align-items:center}
@media(max-width:880px){.train-grid{grid-template-columns:1fr;gap:38px}}
.train-list{list-style:none;display:grid;gap:14px}
.train-list li{display:grid;grid-template-columns:26px 1fr;gap:14px;align-items:start;font-size:16px;color:#D2D4DC}
.train-list li i{width:24px;height:24px;border-radius:50%;background:rgba(200,240,74,.13);color:var(--lime);display:grid;place-items:center;font-style:normal;font-size:13px;font-weight:700}
.free-tag{display:inline-block;background:var(--lime);color:var(--night);font-family:'IBM Plex Mono';font-weight:700;font-size:12px;letter-spacing:.1em;text-transform:uppercase;padding:6px 13px;border-radius:7px;margin-bottom:20px}

/* ============ CALCULATOR ============ */
.calc-shell{background:var(--paper);border:1px solid var(--line);border-radius:22px;overflow:hidden;margin-top:44px;box-shadow:0 2px 0 var(--line)}
.calc-grid{display:grid;grid-template-columns:1fr 380px}
@media(max-width:900px){.calc-grid{grid-template-columns:1fr}}
.calc-ctrl{padding:34px}
.field{margin-bottom:30px}
.field:last-child{margin-bottom:0}
.field .lab{display:flex;justify-content:space-between;align-items:baseline;margin-bottom:13px;gap:12px}
.field .lab .t{font-weight:600;font-size:15px}
.field .lab .v{font-family:'IBM Plex Mono';font-weight:700;font-size:19px;color:var(--ink)}
select{
  width:100%;padding:14px 15px;border:1px solid var(--line);border-radius:12px;background:var(--fog);
  font:600 15px 'Inter',sans-serif;color:var(--ink);cursor:pointer;
  appearance:none;background-image:url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='12' height='8' viewBox='0 0 12 8'><path d='M1 1l5 5 5-5' stroke='%236B6D77' stroke-width='1.8' fill='none' stroke-linecap='round'/></svg>");
  background-repeat:no-repeat;background-position:right 16px center;
}
input[type=range]{
  -webkit-appearance:none;appearance:none;width:100%;height:6px;border-radius:99px;cursor:pointer;
  background:linear-gradient(var(--lime-deep),var(--lime-deep)) no-repeat,var(--line);
  background-size:var(--fill,50%) 100%;
}
input[type=range]::-webkit-slider-thumb{-webkit-appearance:none;width:24px;height:24px;border-radius:50%;background:#fff;border:4px solid var(--lime-deep);box-shadow:0 2px 7px rgba(0,0,0,.16);cursor:pointer}
input[type=range]::-moz-range-thumb{width:24px;height:24px;border-radius:50%;background:#fff;border:4px solid var(--lime-deep);box-shadow:0 2px 7px rgba(0,0,0,.16);cursor:pointer}
.scale{display:flex;justify-content:space-between;font-family:'IBM Plex Mono';font-size:11px;color:#9A9CA6;margin-top:8px}

.calc-out{background:var(--night);color:#fff;padding:36px 32px;display:flex;flex-direction:column;justify-content:center}
.calc-out .cap{font-family:'IBM Plex Mono';font-size:11px;letter-spacing:.16em;text-transform:uppercase;color:#7C7E8A;margin-bottom:10px}
.calc-out .big{font-family:'Unbounded';font-weight:800;font-size:clamp(34px,6vw,48px);color:var(--lime);letter-spacing:-.04em;line-height:1}
.calc-out .sub{font-size:13px;color:#8A8C97;margin-top:8px}
.calc-out .rows{margin-top:26px;border-top:1px solid var(--line-dark);padding-top:20px;display:grid;gap:11px}
.calc-out .rows div{display:flex;justify-content:space-between;font-size:14px;color:#B4B6C0}
.calc-out .rows b{font-family:'IBM Plex Mono';color:#fff}
.hintbox{margin-top:22px;padding:13px 15px;background:#191B24;border-left:2px solid var(--lime);border-radius:0 9px 9px 0;font-size:13px;color:#B4B6C0;line-height:1.55}
.calc-note{margin-top:20px;font-size:13px;color:var(--muted);max-width:70ch}

/* ============ FAQ ============ */
details{border:1px solid var(--line);background:var(--paper);border-radius:13px;margin-bottom:11px;overflow:hidden}
details[open]{border-color:var(--ink)}
summary{padding:20px 24px;font-weight:600;font-size:16px;cursor:pointer;list-style:none;display:flex;justify-content:space-between;gap:16px;align-items:center}
summary::-webkit-details-marker{display:none}
summary::after{content:"+";font-family:'IBM Plex Mono';font-size:22px;color:var(--muted);flex:none;line-height:1}
details[open] summary::after{content:"–"}
details p{padding:0 24px 22px;color:var(--muted);font-size:15px;max-width:74ch}

/* ============ FORM ============ */
.form-sec{background:var(--night);color:#fff}
.form-grid{display:grid;grid-template-columns:.9fr 1.1fr;gap:60px;align-items:start}
@media(max-width:900px){.form-grid{grid-template-columns:1fr;gap:38px}}
.form-sec .sec-p{color:#A7A9B4}
.trust{list-style:none;margin-top:30px;display:grid;gap:13px}
.trust li{display:grid;grid-template-columns:22px 1fr;gap:13px;font-size:15px;color:#C9CBD4;align-items:start}
.trust li i{color:var(--lime);font-style:normal;font-weight:700}
.form-card{background:var(--paper);border-radius:20px;padding:34px;color:var(--ink)}
.form-card h3{font-size:21px;font-weight:600;margin-bottom:6px}
.form-card .fp{font-size:14px;color:var(--muted);margin-bottom:26px}
.fg{margin-bottom:17px}
.fg label{display:block;font-size:13px;font-weight:600;margin-bottom:7px}
.fg input,.fg select,.fg textarea{
  width:100%;padding:13px 15px;border:1px solid var(--line);border-radius:11px;
  font:400 15px 'Inter',sans-serif;background:var(--fog);color:var(--ink);
}
.fg textarea{resize:vertical;min-height:82px}
.fg input:focus,.fg select:focus,.fg textarea:focus{outline:none;border-color:var(--ink);background:#fff}
.consent{display:grid;grid-template-columns:22px 1fr;gap:12px;align-items:start;margin:22px 0;font-size:13px;color:var(--muted);line-height:1.55}
.consent input{width:19px;height:19px;margin-top:2px;accent-color:var(--lime-deep);cursor:pointer}
.consent a{color:var(--ink);text-decoration:underline;text-underline-offset:2px}
.submit{width:100%;padding:16px;border:0;border-radius:12px;background:var(--night);color:#fff;font:700 16px 'Inter';cursor:pointer;transition:.16s}
.submit:hover:not(:disabled){background:#000}
.submit:disabled{opacity:.4;cursor:not-allowed}
.ok{display:none;padding:18px;border-radius:12px;background:#EDF7D4;border:1px solid var(--lime-deep);font-size:15px;font-weight:600;color:#4C5F08;margin-top:18px}
.err{color:#B5321B;font-size:13px;margin-top:6px;display:none}

:focus-visible{outline:2px solid var(--lime-deep);outline-offset:3px;border-radius:4px}

/* ============ FOOTER ============ */
footer{background:#0C0D12;color:#7C7E8A;padding:46px 0 56px;font-size:13px;line-height:1.75}
footer .flinks{display:flex;gap:20px;flex-wrap:wrap;margin-top:16px}
footer a{color:#A7A9B4;text-decoration:none}
footer a:hover{color:var(--lime)}
.disclaim{margin-top:22px;padding-top:20px;border-top:1px solid var(--line-dark);max-width:78ch;color:#5E606B}
@media(prefers-reduced-motion:reduce){*{transition:none!important;animation:none!important;scroll-behavior:auto}}
</style>
</head>
<body>

<nav>
  <div class="wrap nav-in">
    <a class="logo" href="#top"><i>S</i>START</a>
    <div class="nav-links">
      <a href="#about">О компании</a>
      <a href="#what">Что это за работа</a>
      <a href="#how">Как это работает</a>
      <a href="#train">Обучение</a>
      <a href="#calc">Калькулятор</a>
      <a href="#faq">Вопросы</a>
    </div>
    <a class="nav-cta" href="#form">Оставить заявку</a>
  </div>
</nav>

<!-- ============ HERO ============ -->
<header class="hero" id="top">
  <div class="wrap hero-in">
    <div>
      <div class="badge"><span class="pulse"></span>Набор партнёров открыт в 20+ городах России</div>
      <h1>Приводите курьеров в доставку и получайте до <mark>60 000 ₽</mark> с одного человека</h1>
      <p class="lede">Вы находите людей, которые хотят работать курьером, и помогаете им зарегистрироваться. Дальше сервис платит вам за каждого, кто вышел на заказы. Опыт не нужен — обучение бесплатное.</p>
      <div class="hero-btns">
        <a class="btn btn-lime" href="#form">Стать партнёром</a>
        <a class="btn btn-ghost" href="#calc">Посчитать доход</a>
      </div>
      <div class="hero-stats">
        <div><div class="n">до 60 000 ₽</div><div class="l">с одного курьера</div></div>
        <div><div class="n">20+</div><div class="l">городов России</div></div>
        <div><div class="n">2 раза</div><div class="l">выплаты в месяц</div></div>
        <div><div class="n">0 ₽</div><div class="l">вложений на старте</div></div>
      </div>
    </div>

    <aside class="hero-card">
      <div class="cap">Пример месяца партнёра</div>
      <div class="pay-row"><span>Привлечено курьеров</span><b>8</b></div>
      <div class="pay-row"><span>Вышли на заказы</span><b>6</b></div>
      <div class="pay-row"><span>Средняя выплата за курьера</span><b>28 500 ₽</b></div>
      <div class="pay-row"><span>Часов работы в неделю</span><b>~10</b></div>
      <div class="tot"><span>Доход за месяц</span><b>171 000 ₽</b></div>
    </aside>
  </div>
</header>


<!-- ============ INTRO ============ -->
<section class="intro" id="about">
  <div class="wrap intro-grid">
    <div>
      <div class="eyebrow">Кто мы</div>
      <h2>Мы рекрутинговая компания START</h2>
      <p class="p">Мы занимаемся подбором линейного персонала для сервисов доставки: находим людей, которые ищут работу курьером, и доводим их до первого рабочего дня. Это наша основная деятельность, а не разовая акция.</p>
      <p class="p">Спрос на курьеров стабильно превышает то, что мы закрываем своими силами. Поэтому мы открыли партнёрскую программу: вы приводите кандидатов, мы берём на себя оформление, документы и расчёты с сервисом, а вы получаете выплату за каждого, кто вышел на заказы.</p>
      <p class="p">Мы работаем официально как ИП, заключаем с партнёрами договор и не берём денег за вход, обучение или материалы. Наш доход — процент от сервиса, поэтому нам выгодно, чтобы вы зарабатывали как можно больше.</p>
      <div class="sign">
        <div class="av">СК</div>
        <div class="who">
          <b>Кирилл Стародубов</b>
          <span>Основатель рекрутинговой компании START</span>
        </div>
      </div>
    </div>

    <div class="facts">
      <div class="fact">
        <div class="fi">◈</div>
        <div><b>Официальное трудоустройство</b></div>
      </div>
      <div class="fact">
        <div class="fi">₽</div>
        <div><b>Мы не берём с вас денег</b><span>Ни за обучение, ни за доступ, ни за материалы. Если где-то просят предоплату за партнёрство — это не мы.</span></div>
      </div>
      <div class="fact">
        <div class="fi">▤</div>
        <div><b>Прозрачные начисления</b><span>В кабинете видно каждого приведённого курьера и его заказы. Сумма считается по ставке города, а не «на усмотрение».</span></div>
      </div>
      <div class="fact">
        <div class="fi">◷</div>
        <div><b>Официальные выплаты</b></div>
      </div>
      <div class="fact">
        <div class="fi">☎</div>
        <div><b>Живая поддержка</b><span>У каждого нового партнёра есть куратор на первый месяц и общий чат, где отвечают люди, а не бот.</span></div>
      </div>
    </div>
  </div>
</section>

<!-- ============ WHAT ============ -->
<section class="what" id="what">
  <div class="wrap">
    <div class="eyebrow">Что это за работа</div>
    <h2 class="sec-h">Вы — тот, кто соединяет людей и работу</h2>
    <p class="sec-p">Сервисам доставки постоянно нужны курьеры. Найти их самостоятельно сервис не успевает, поэтому платит партнёрам за каждого приведённого человека. Ваша задача — рассказать о вакансии и довести кандидата до первого заказа.</p>

    <div class="what-grid">
      <div class="wcard">
        <div class="ic">◎</div>
        <h3>Это не курьерская работа</h3>
        <p>Вам не нужно ничего развозить. Вы работаете с людьми: находите кандидатов, отвечаете на вопросы, помогаете с регистрацией.</p>
      </div>
      <div class="wcard">
        <div class="ic">▤</div>
        <h3>Полностью удалённо</h3>
        <p>Всё делается с телефона или компьютера. Объявления, переписка, отправка ссылки на регистрацию. Место жительства не имеет значения.</p>
      </div>
      <div class="wcard">
        <div class="ic">◷</div>
        <h3>Свободный график</h3>
        <p>Совмещается с основной работой или учёбой. Большинство партнёров тратят 1–2 часа в день на переписку с кандидатами.</p>
      </div>
      <div class="wcard">
        <div class="ic">₽</div>
        <h3>Оплата за результат</h3>
        <p>Деньги начисляются, когда курьер выполнил заказы. Чем больше он работает в первый месяц, тем выше ваша выплата — вплоть до 60 000 ₽.</p>
      </div>
      <div class="wcard">
        <div class="ic">△</div>
        <h3>Без вложений</h3>
        <p>Стартовать можно с бесплатных площадок объявлений и чатов. Мы даём готовые тексты, макеты и скрипты — платить за них не нужно.</p>
      </div>
      <div class="wcard">
        <div class="ic">◇</div>
        <h3>Прозрачная статистика</h3>
        <p>В личном кабинете видно каждого приведённого курьера: сколько заказов выполнил, сколько начислено и когда будет выплата.</p>
      </div>
    </div>
  </div>
</section>

<!-- ============ HOW ============ -->
<section id="how">
  <div class="wrap">
    <div class="eyebrow">Как это работает</div>
    <h2 class="sec-h">Пять шагов от заявки до первой выплаты</h2>
    <p class="sec-p">Схема одинаковая в любом городе. Первую выплату партнёры обычно получают на 3–4 неделе.</p>

    <div class="steps">
      <div class="step">
        <div>
          <h3>Оставляете заявку и проходите обучение</h3>
          <p>Мы связываемся с вами, открываем доступ в личный кабинет и в обучающий раздел. Обучение бесплатное и занимает пару вечеров.</p>
        </div>
      </div>
      <div class="step">
        <div>
          <h3>Размещаете вакансию</h3>
          <p>Берёте готовые тексты и картинки из базы материалов и публикуете их на площадках объявлений, в тематических чатах и соцсетях своего города.</p>
        </div>
      </div>
      <div class="step">
        <div>
          <h3>Общаетесь с кандидатом</h3>
          <p>Отвечаете на типовые вопросы: сколько платят, какой график, нужен ли транспорт. На частые возражения есть готовые ответы в обучении.</p>
        </div>
      </div>
      <div class="step">
        <div>
          <h3>Помогаете зарегистрироваться</h3>
          <p>Отправляете кандидату вашу персональную ссылку. Он загружает документы и проходит проверку. Курьер закрепляется за вами автоматически.</p>
        </div>
      </div>
      <div class="step">
        <div>
          <h3>Получаете выплату</h3>
          <p>Курьер выходит на заказы, вам начисляются деньги. Вывод на карту или счёт самозанятого — два раза в месяц по запросу из кабинета.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ============ TRAINING ============ -->
<section class="train" id="train">
  <div class="wrap train-grid">
    <div>
      <div class="free-tag">Бесплатно · без предоплат</div>
      <h2 class="sec-h" style="color:#fff">Обучение, после которого понятно, что делать завтра утром</h2>
      <p class="sec-p">Никакой теории про «мышление предпринимателя». Только практика: где искать людей, что им писать и как довести до регистрации. Доступ открывается сразу после заявки и остаётся навсегда.</p>
      <a class="btn btn-lime" href="#form" style="margin-top:30px">Получить доступ</a>
    </div>
    <ul class="train-list">
      <li><i>✓</i><span>Где искать кандидатов: площадки объявлений, чаты, соцсети, офлайн-точки</span></li>
      <li><i>✓</i><span>Готовые тексты вакансий и макеты для объявлений — просто копируете</span></li>
      <li><i>✓</i><span>Как настроить объявление, чтобы его видели именно ваши кандидаты</span></li>
      <li><i>✓</i><span>Скрипты переписки: первое сообщение, ответы на вопросы, работа с отказами</span></li>
      <li><i>✓</i><span>Разбор документов и типичных ошибок при регистрации курьера</span></li>
      <li><i>✓</i><span>Как мотивировать курьера выйти на заказы — от этого зависит ваша выплата</span></li>
      <li><i>✓</i><span>Личный куратор и чат поддержки на первый месяц</span></li>
    </ul>
  </div>
</section>

<!-- ============ CALCULATOR ============ -->
<section id="calc">
  <div class="wrap">
    <div class="eyebrow">Калькулятор</div>
    <h2 class="sec-h">Посчитайте, сколько вы будете получать</h2>
    <p class="sec-p">Выберите город и подвиньте ползунки. Выплата зависит от ставки города и от того, сколько заказов курьер успеет выполнить в первые 20 дней.</p>

    <div class="calc-shell">
      <div class="calc-grid">
        <div class="calc-ctrl">
          <div class="field">
            <div class="lab"><span class="t">Город</span></div>
            <select id="city" aria-label="Город"></select>
          </div>

          <div class="field">
            <div class="lab"><span class="t">Курьеров в месяц</span><span class="v" id="cv">6</span></div>
            <input type="range" id="couriers" min="1" max="30" value="6" aria-label="Курьеров в месяц">
            <div class="scale"><span>1</span><span>15</span><span>30</span></div>
          </div>

          <div class="field">
            <div class="lab"><span class="t">Заказов на курьера за 20 дней</span><span class="v" id="ov">60</span></div>
            <input type="range" id="orders" min="5" max="100" value="60" aria-label="Заказов на курьера">
            <div class="scale"><span>5</span><span>50</span><span>100</span></div>
          </div>
        </div>

        <div class="calc-out">
          <div class="cap">Ваш доход за месяц</div>
          <div class="big" id="total">—</div>
          <div class="sub" id="sub">—</div>
          <div class="rows">
            <div><span>Ставка за заказ</span><b id="rate">—</b></div>
            <div><span>Выплата за одного курьера</span><b id="per">—</b></div>
            <div><span>Максимум за курьера в городе</span><b id="cap">—</b></div>
            <div><span>Всего заказов</span><b id="ords">—</b></div>
          </div>
          <div class="hintbox" id="hint">—</div>
        </div>
      </div>
    </div>
    <p class="calc-note">Расчёт ориентировочный. Ставки по городам периодически пересматриваются — актуальные значения партнёр видит в личном кабинете. Доход не гарантирован и зависит от того, сколько курьеров вы привлечёте и как активно они будут работать.</p>
  </div>
</section>

<!-- ============ FAQ ============ -->
<section class="what" id="faq">
  <div class="wrap">
    <div class="eyebrow">Вопросы</div>
    <h2 class="sec-h">Что спрашивают чаще всего</h2>
    <div style="margin-top:38px">
      <details open><summary>Нужен ли опыт или образование?</summary><p>Нет. Требуется возраст от 18 лет, телефон с интернетом и готовность общаться с людьми в переписке. Всему остальному учим бесплатно.</p></details>
      <details><summary>Нужно ли вкладывать деньги на старте?</summary><p>Нет. Материалы, обучение и личный кабинет бесплатны. Начать можно с бесплатных площадок объявлений. Платная реклама — по желанию, когда вы уже понимаете, что окупается.</p></details>
      <details><summary>Когда придут первые деньги?</summary><p>Начисление происходит после того, как курьер выполнит заказы. Обычно первая выплата приходит на 3–4 неделе после старта. Вывод — дважды в месяц по запросу из кабинета.</p></details>
      <details><summary>Откуда берутся 60 000 ₽ с курьера?</summary><p>Это максимальная сумма в городах с самой высокой ставкой при условии, что курьер выполнит 100 заказов за первые 20 дней. В среднем выплата за активного курьера получается меньше — калькулятор выше показывает реалистичный диапазон.</p></details>
      <details><summary>Как оформляются выплаты?</summary><p>Работа ведётся по договору. Для получения выплат нужен статус самозанятого или ИП — помогаем оформить его на обучении, это бесплатно и занимает 15 минут в приложении банка.</p></details>
      <details><summary>А если курьер не выйдет на заказы?</summary><p>Тогда выплаты за него не будет — оплата идёт за результат. Поэтому в обучении отдельный блок о том, как поддерживать связь с курьером в первые дни: это напрямую влияет на ваш доход.</p></details>
      <details><summary>Можно ли работать не в своём городе?</summary><p>Да. Многие партнёры размещают объявления сразу по нескольким городам из списка. Ограничений по вашему месту жительства нет.</p></details>
      <details><summary>Сколько времени это занимает?</summary><p>Партнёры на старте тратят 1–2 часа в день: разместить объявления и ответить кандидатам. Дальше время сокращается, потому что часть вопросов закрывают готовые шаблоны.</p></details>
    </div>
  </div>
</section>

<!-- ============ FORM ============ -->
<section class="form-sec" id="form">
  <div class="wrap form-grid">
    <div>
      <div class="eyebrow" style="color:var(--lime)">Заявка</div>
      <h2 class="sec-h" style="color:#fff">Оставьте заявку — откроем доступ к обучению</h2>
      <p class="sec-p">Свяжемся в течение рабочего дня, ответим на вопросы и заведём личный кабинет. Заявка ни к чему не обязывает.</p>
      <ul class="trust">
        <li><i>✓</i><span>Обучение и материалы — бесплатно, без предоплат</span></li>
        <li><i>✓</i><span>Не звоним без предупреждения: сначала пишем в мессенджер</span></li>
        <li><i>✓</i><span>Данные используем только для связи по программе</span></li>
        <li><i>✓</i><span>Отписаться и удалить данные можно в любой момент</span></li>
      </ul>
    </div>

    <div class="form-card">
      <h3>Анкета партнёра</h3>
      <p class="fp">Все поля со звёздочкой обязательны.</p>
      <form id="lead" novalidate>
        <div class="fg">
          <label for="fname">Имя *</label>
          <input id="fname" name="name" type="text" placeholder="Как к вам обращаться" required>
        </div>
        <div class="fg">
          <label for="fphone">Телефон или мессенджер *</label>
          <input id="fphone" name="phone" type="tel" placeholder="+7 900 000-00-00" required>
        </div>
        <div class="fg">
          <label for="fcity">Город *</label>
          <select id="fcity" name="city" required></select>
        </div>
        <div class="fg">
          <label for="fexp">Есть ли опыт привлечения людей?</label>
          <select id="fexp" name="exp">
            <option>Опыта нет, хочу разобраться</option>
            <option>Есть опыт в HR или рекрутинге</option>
            <option>Работал с другой партнёрской программой</option>
            <option>Есть свои каналы и аудитория</option>
          </select>
        </div>
        <div class="fg">
          <label for="fcomm">Комментарий</label>
          <textarea id="fcomm" name="comment" placeholder="Сколько времени готовы уделять, что хотите уточнить"></textarea>
        </div>

        <label class="consent" for="fagree">
          <input id="fagree" type="checkbox" required>
          <span>Я даю <a href="#" target="_blank" rel="noopener">согласие на обработку персональных данных</a> и подтверждаю, что ознакомлен с <a href="#" target="_blank" rel="noopener">политикой конфиденциальности</a> и <a href="#" target="_blank" rel="noopener">публичной офертой</a>. Согласие можно отозвать в любой момент.</span>
        </label>

        <button class="submit" type="submit" id="btn" disabled>Отправить заявку</button>
        <div class="err" id="err">Заполните обязательные поля и отметьте согласие.</div>
        <div class="ok" id="ok">Заявка отправлена. Напишем вам в течение рабочего дня и откроем доступ к обучению.</div>
      </form>
    </div>
  </div>
</section>

<footer>
  <div class="wrap">
    <div class="logo" style="margin-bottom:14px"><i>S</i>START</div>
    Рекрутинговая компания START<br>
    ИП Стародубов Кирилл Вячеславович<br>
    Партнёрская программа по привлечению курьеров в сервисы доставки. Работает в 20+ городах России.
    <div class="flinks">
      <a href="#">Согласие на обработку персональных данных</a>
      <a href="#">Политика конфиденциальности</a>
      <a href="#">Публичная оферта</a>
      <a href="#">Правила для партнёров</a>
      <a href="#">Поддержка</a>
    </div>
    <p class="disclaim">Указанные суммы — максимально возможные выплаты при условии выполнения курьером 100 заказов в первые 20 дней после регистрации. Фактический доход зависит от города, количества привлечённых курьеров и их активности и не является гарантированным. Ставки по городам могут изменяться; актуальные значения публикуются в личном кабинете партнёра.</p>
  </div>
</footer>

<script>
/* ---------- Города и ставки: [ставка за заказ ₽, максимум за курьера ₽] ---------- */
const CITIES = [
  ["Москва",              600, 60000],
  ["Санкт-Петербург",     575, 57500],
  ["Балашиха",            560, 56000],
  ["Химки",               550, 55000],
  ["Подольск",            540, 54000],
  ["Екатеринбург",        505, 50500],
  ["Новосибирск",         500, 50000],
  ["Казань",              485, 48500],
  ["Нижний Новгород",     480, 48000],
  ["Краснодар",           470, 47000],
  ["Самара",              460, 46000],
  ["Ростов-на-Дону",      450, 45000],
  ["Челябинск",           445, 44500],
  ["Уфа",                 440, 44000],
  ["Пермь",               430, 43000],
  ["Воронеж",             425, 42500],
  ["Волгоград",           420, 42000],
  ["Тюмень",              420, 42000],
  ["Красноярск",          410, 41000],
  ["Саратов",             405, 40500],
  ["Омск",                400, 40000],
  ["Тольятти",            390, 39000],
  ["Ижевск",              385, 38500],
  ["Барнаул",             380, 38000]
];

const rub = n => n.toLocaleString('ru-RU') + ' ₽';
const plural = (n,a,b,c) => {const m=n%100,d=n%10; return m>=11&&m<=14?c:d===1?a:d>=2&&d<=4?b:c;};

/* заполняем оба списка городов */
const citySel = document.getElementById('city');
const formCity = document.getElementById('fcity');
CITIES.forEach((c,i)=>{
  const o=document.createElement('option');
  o.value=i; o.textContent=`${c[0]} — до ${c[2].toLocaleString('ru-RU')} ₽ за курьера`;
  citySel.appendChild(o);
  const o2=document.createElement('option');
  o2.value=c[0]; o2.textContent=c[0];
  formCity.appendChild(o2);
});
const other=document.createElement('option'); other.textContent='Другой город'; formCity.appendChild(other);

/* ---------- калькулятор ---------- */
const cs=document.getElementById('couriers'), os=document.getElementById('orders');
const cv=document.getElementById('cv'), ov=document.getElementById('ov');
const elTotal=document.getElementById('total'), elSub=document.getElementById('sub');
const elRate=document.getElementById('rate'), elPer=document.getElementById('per');
const elCap=document.getElementById('cap'), elOrds=document.getElementById('ords'), elHint=document.getElementById('hint');

function fill(el){el.style.setProperty('--fill',((el.value-el.min)/(el.max-el.min)*100)+'%');}

function calc(){
  const [name,rate,max] = CITIES[+citySel.value];
  const c=+cs.value, o=+os.value;
  const one = Math.min(Math.round(rate*o), max);
  const total = one*c;

  cv.textContent=c; ov.textContent=o;
  elRate.textContent=rub(rate);
  elPer.textContent=rub(one);
  elCap.textContent=rub(max);
  elOrds.textContent=(c*o).toLocaleString('ru-RU');
  elTotal.textContent=rub(total);
  elSub.textContent=`${name} · ${c} ${plural(c,'курьер','курьера','курьеров')} по ${o} ${plural(o,'заказу','заказа','заказов')}`;

  elHint.textContent = o>=100
    ? 'Курьер вышел на максимальную ставку — это потолок выплаты за одного человека в этом городе.'
    : `Если курьер доведёт число заказов до 100 за 20 дней, выплата за него вырастет до ${rub(max)}. Поэтому важно поддерживать связь в первые дни.`;

  fill(cs); fill(os);
}
[citySel,cs,os].forEach(el=>el.addEventListener('input',calc));
calc();

/* ---------- форма ---------- */
const form=document.getElementById('lead'), agree=document.getElementById('fagree'),
      btn=document.getElementById('btn'), err=document.getElementById('err'), ok=document.getElementById('ok');
const name=document.getElementById('fname'), phone=document.getElementById('fphone');

function validate(){
  btn.disabled = !(agree.checked && name.value.trim().length>1 && phone.value.trim().length>4);
}
[agree,name,phone].forEach(el=>el.addEventListener('input',validate));
agree.addEventListener('change',validate);

form.addEventListener('submit',e=>{
  e.preventDefault();
  if(btn.disabled){err.style.display='block';return;}
  err.style.display='none';
  form.querySelectorAll('input,select,textarea,button').forEach(el=>el.disabled=true);
  ok.style.display='block';
  ok.scrollIntoView({block:'center',behavior:'smooth'});
});
</script>
</body>
</html>
