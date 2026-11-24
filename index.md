<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Code Club - Home</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="style.css">
  <script src="script.js" defer></script>
</head>

<body>
  <header>
    <h1 class="logo">Code Club</h1>
    <button id="menuButton" class="menu-button" aria-label="Open menu" aria-expanded="false">☰</button>
    <nav id="navigation">
      <a href="index.html">Home</a>
      <a href="html.html">HTML</a>
      <a href="css.html">CSS</a>
      <a href="javascript.html">JavaScript</a>
    </nav>
  </header>

  <main class="max-w-5xl mx-auto px-4">
    <section class="welcome">
      <h2>Welcome to Code Club!</h2>
      <p>Learn how to make your own websites. You do not need to know anything about coding to get started.</p>
    </section>

    <h2 class="heading">Learn about the three technologies</h2>
    <section class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
      <article class="card">
        <h3>HTML</h3>
        <p>HTML is used to add content to a webpage, such as headings, paragraphs, pictures and links.</p>
        <a href="html.html">Learn about HTML</a>
      </article>

      <article class="card">
        <h3>CSS</h3>
        <p>CSS is used to make a webpage look nice. It changes colours, fonts, sizes and page layouts.</p>
        <a href="css.html">Learn about CSS</a>
      </article>

      <article class="card">
        <h3>JavaScript</h3>
        <p>JavaScript makes a webpage interactive. It can make buttons work and show messages.</p>
        <a href="javascript.html">Learn about JavaScript</a>
      </article>
    </section>
  </main>

  <footer>
    <p>Code Club - Learn to code!</p>
  </footer>
</body>
</html>
