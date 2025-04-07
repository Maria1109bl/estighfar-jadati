# estighfar-jadati
اللهم ارحمها و اغفر لجدتي
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <title>استغفار لجدتي رحمها الله</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background: linear-gradient(to bottom, #d7ccc8, #f4e1d2); /* لون بني هادئ */
      text-align: center;
      padding: 50px;
    }

    h1 {
      color: #3e2723; /* لون بني داكن */
      font-size: 34px;
    }

    p {
      font-size: 20px;
      color: #3e2723;
      margin-bottom: 40px;
    }

    button {
      font-size: 24px;
      padding: 15px 30px;
      margin-top: 20px;
      background-color: #6d4c41; /* بني متوسط */
      color: white;
      border: none;
      border-radius: 15px;
      cursor: pointer;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      transition: 0.3s;
    }

    button:hover {
      background-color: #3e2723;
    }

    #count {
      font-size: 48px;
      color: #6d4c41;
      margin-top: 30px;
    }

    footer {
      margin-top: 60px;
      font-size: 14px;
      color: #8d6e63; /* لون بني فاتح */
    }
  </style>
</head>
<body>

  <h1>استغفار لجدتي رحمها الله</h1>
  <p>اللهم اغفر لجدتي وارحمها، واجعل استغفاري هذا نوراً في قبرها، ووسّع مدخلها، واغسلها بالماء والثلج والبرد، آمين.</p>
  <p>نوي ريم</p>
  <button onclick="incrementCount()">استغفر الله</button>
  <div id="count">0</div>

  <footer>
    اللهم اجعل هذا العمل صدقة جارية في ميزان حسناتها
  </footer>

  <script>
    let count = 0;
    function incrementCount() {
      count++;
      document.getElementById('count').innerText = count;
    }
  </script>

</body>
</html>
