<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Структура сайту з навігацією</title>
  <style>
    body {
      display: grid;
      grid-template-areas: 
        "header header"
        "nav main"
        "aside main"
        "footer footer";
      grid-template-columns: 200px 1fr;
      grid-template-rows: auto;
      gap: 10px;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header { grid-area: header; background: #f0f0f0; padding: 20px; }
    nav { grid-area: nav; background: #d9edf7; padding: 20px; }
    aside { grid-area: aside; background: #fcf8e3; padding: 20px; }
    main { grid-area: main; padding: 20px; }
    footer { grid-area: footer; background: #f5f5f5; padding: 20px; text-align: center; }
    a { display: block; margin-bottom: 10px; }
  </style>
</head>
<body>
  <header>
    <h1>Приклад структури сайту</h1>
  </header>

  <nav>
    <h2>Навігація</h2>
    <a href="#h1">Вступ</a>
    <a href="#h2">Форматування</a>
    <a href="#h3">Заголовки</a>
    <a href="#h4">Структурування</a>
  </nav>

  <aside>
    <h3>Бічна панель</h3>
    <p>Тут можуть бути додаткові посилання або інформація.</p>
  </aside>

  <main>
    <section>
      <article>
        <h2 id="h1">Вступ</h2>
        <p>HTML дозволяє створювати структуровані документи, використовуючи теги заголовків, абзаців, списків та інше. Це дає змогу робити сторінки зручними для читача.</p>

        <h2 id="h2">Форматування</h2>
        <p>Можна використовувати теги <strong>&lt;strong&gt;</strong> для виділення важливого, <em>&lt;em&gt;</em> для акценту, та <code>&lt;code&gt;</code> для коду.</p>

        <h2 id="h3">Заголовки</h2>
        <p>Заголовки від <code>&lt;h1&gt;</code> до <code>&lt;h6&gt;</code> формують ієрархію змісту. Вони допомагають користувачу орієнтуватися на сторінці та покращують SEO.</p>

        <h2 id="h4">Структурування</h2>
        <p>Сучасний HTML5 вводить теги <code>&lt;header&gt;</code>, <code>&lt;nav&gt;</code>, <code>&lt;aside&gt;</code>, <code>&lt;main&gt;</code>, <code>&lt;section&gt;</code> та <code>&lt;article&gt;</code>, які роблять структуру сторінки логічнішою.</p>
      </article>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Приклад сайту</p>
  </footer>
</body>
</html>
