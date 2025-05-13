/* Folder Structure:
- index.html (Home)
- app.html (App)
- about.html (About)
- faq.html (FAQ)
- contact.html (Contact)
- /css/style.css
*/

<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SightWordsRed - Home</title>
  <link rel="stylesheet" href="css/style.css" />
</head>
<body>
  <header>
    <h1>SightWordsRed</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="app.html">App</a>
      <a href="about.html">About</a>
      <a href="faq.html">FAQ</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>
  <main>
    <h2>Welcome to SightWordsRed</h2>
    <p>Empowering learners through fun and interactive iOS apps.</p>
  </main>
</body>
</html>

<!-- app.html, about.html, faq.html, contact.html follow similar layout with different content -->
<!-- css/style.css -->
body {
  font-family: Arial, sans-serif;
  background: #f4f4f4;
  margin: 0;
  padding: 0;
}

header {
  background: #ff595e;
  padding: 1em;
  color: white;
  text-align: center;
}

nav a {
  margin: 0 10px;
  text-decoration: none;
  color: white;
  font-weight: bold;
}

main {
  padding: 2em;
  text-align: center;
}
