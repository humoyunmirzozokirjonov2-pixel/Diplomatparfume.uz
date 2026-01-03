from flask import Flask, render_template

app = Flask(__name__)

@app.route("/")
def home():
    return render_template("index.html")

if __name__ == "__main__":
    app.run()
flask
<!DOCTYPE html>
<html lang="uz">
<head>
  <meta charset="UTF-8">
  <title>Diplomat Parfume</title>

  <!-- Telegram Web App -->
  <script src="https://telegram.org/js/telegram-web-app.js"></script>
  <script>
    Telegram.WebApp.ready();
  </script>
</head>
<body>
  <h1>Diplomat Parfume</h1>
  <p>Premium original atirlar</p>

  <button onclick="alert('Keyingi bosqichda ishlaymiz')">
    Buyurtma berish
  </button>
</body>
</html>
git init
git add .
git commit -m "Initial MVP"
git branch -M main
git remote add origin https://github.com/USERNAME/diplomat-webapp.git
git push -u origin main
