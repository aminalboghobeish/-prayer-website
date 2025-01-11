1. index.html:

<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>سایت دعا نویسی</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>سایت دعا نویسی</h1>
    <nav>
      <ul>
        <li><a href="#">خانه</a></li>
        <li><a href="#">دعاها</a></li>
        <li><a href="#">استخاره</a></li>
        <li><a href="#">پشتیبانی</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <section id="prayer-request">
      <h2>درخواست دعا</h2>
      <form action="#" method="post">
        <label for="name">نام:</label>
        <input type="text" id="name" name="name" required>
        <label for="request">درخواست دعا:</label>
        <textarea id="request" name="request" required></textarea>
        <button type="submit">ارسال</button>
      </form>
    </section>
  </main>
  <footer>
    <p>تمامی حقوق محفوظ است &copy; 2025</p>
  </footer>
</body>
</html>

2. styles.css:

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f4;
}

header {
  background-color: #333;
  color: white;
  padding: 20px 0;
  text-align: center;
}

header h1 {
  margin-bottom: 10px;
}

nav ul {
  list-style-type: none;
  padding: 0;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav ul li a {
  color: white;
  text-decoration: none;
}

main {
  padding: 30px;
  background-color: white;
  margin-top: 20px;
}

h2 {
  margin-bottom: 15px;
}

form label {
  display: block;
  margin-bottom: 8px;
}

input, textarea {
  width: 100%;
  padding: 10px;
  margin-bottom: 20px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

button {
  padding: 10px 20px;
  background-color: #333;
  color: white;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

button:hover {
  background-color: #555;
}

footer {
  text-align: center;
  background-color: #333;
  color: white;
  padding: 10px 0;
  margin-top: 20px;
}

3. script.js:

document.querySelector('form').addEventListener('submit', function(event) {
  event.preventDefault();
  alert('درخواست شما ارسال شد!');
});

# -prayer-website
A website for prayer requests and spiritual services.
