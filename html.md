<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Code Club - HTML</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="style.css">
  <script src="script.js" defer></script>
</head>

<body>
  <header>
    <h1 class="logo">Code Club</h1>
    <button id="menuButton" class="menu-button" aria-label="Open menu" aria-expanded="false"></button>
    <nav id="navigation">
      <a href="index.html">Home</a>
      <a href="html.html">HTML</a>
      <a href="css.html">CSS</a>
      <a href="javascript.html">JavaScript</a>
    </nav>
  </header>

  <main class="max-w-5xl mx-auto px-4">
    <section class="welcome">
      <h2>What is HTML?</h2>
      <p>HTML stands for HyperText Markup Language. It is used to create the structure of a webpage.</p>
    </section>

    <section class="simple-content">
      <h2 class="heading">What can HTML do?</h2>
        <p>HTML can add headings, paragraphs, images, links and lists to a webpage.</p>
      <h2 class="heading">Example of HTML</h2>

      <pre>
        <code>&lt;h1&gt;Hello!&lt;/h1&gt;
        &lt;p&gt;This is my first webpage.&lt;/p&gt;</code>
      </pre>

      <p>The h1 tag creates a large heading. The p tag creates a paragraph.</p>
      <h2 class="heading">Try it yourself</h2>
      <p>Make a webpage about yourself. Add your name as a heading and write a short paragraph about your hobbies.</p>
      <a class="back-link" href="index.html">Back to Home</a>
    
    </section>
  </main>
  <footer><p>Code Club - Learn to code!</p></footer>
</body>
</html>
