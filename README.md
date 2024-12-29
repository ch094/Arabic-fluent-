# Arabic-fluent-
 Arabic fluent course 
<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>دورة تعلم اللغة العربية بطلاقة</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>تحدث العربية مثل العرب تماما!</h1>
    <p>البساطة .. المرح ..التعلم باللعب.</p>
    <button>اشترك الآن</button>
  </header>
  <section>
    <h2>المزايا</h2>
    <ul>
      <li>ميزة 1</li>
      <li>ميزة 2</li>
      <li>ميزة 3</li>
    </ul>
  </section>
  <footer>
    <p>© 2024 جميع الحقوق محفوظة.</p>
  </footer>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  text-align: center;
}

header {
  background: #007bff;
  color: white;
  padding: 50px 20px;
}

header h1 {
  font-size: 2.5em;
}

header p {
  font-size: 1.2em;
}

header button {
  padding: 10px 20px;
  font-size: 1em;
  background: #ffc107;
  border: none;
  cursor: pointer;
}

section {
  padding: 20px;
}

footer {
  background: #f1f1f1;
  padding: 10px 0;
}
<form id="subscribe-form">
  <input type="email" placeholder="أدخل بريدك الإلكتروني" required>
  <button type="submit">اشترك</button>
</form>

<script>
  document.getElementById('subscribe-form').addEventListener('submit', function(event) {
    event.preventDefault();
    alert('شكراً لتسجيلك!');
  });
</script>
