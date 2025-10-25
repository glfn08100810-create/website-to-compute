<!DOCTYPE html>
<html>
  <head>
    <title>밸런스 게임</title>
    <style>
      body { font-family: Arial; text-align: center; margin-top: 100px; }
      .choice { padding: 20px; margin: 10px; border: 2px solid black; display: inline-block; cursor: pointer; }
    </style>
  </head>
  <body>
    <h1>밸런스 게임</h1>
    <div class="choice">🍎 사과</div>
    <div class="choice">🍌 바나나</div>

    <script>
      const choices = document.querySelectorAll('.choice');
      choices.forEach(c => {
        c.addEventListener('click', () => {
          alert(c.textContent + ' 선택!');
        });
      });
    </script>
  </body>
</html>
