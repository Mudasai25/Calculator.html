<!DOCTYPE html>
<html lang="en">
  <head>
    <link rel="stylesheet" href="style.css" />
    <title>Calculator</title>
  </head>
  <body>
    <div class="container">
      <div class="calculator">
        <h4 style="color: rgb(255,255,255);">CALCULATOR</h4>
        <input type="text" id="inputBox" placeholder="0" />
        <div>
          <button class="button operator">AC</button>
          <button class="button operator">DEL</button>
          <button class="button operator">%</button>                         
          <button class="button operator">/</button>
        </div>
        <div>
          <button class="button">7</button>
          <button class="button">8</button>
          <button class="button">9</button>
          <button class="button operator">*</button>
        </div>
        <div>
          <button class="button">4</button>
          <button class="button">5</button>
          <button class="button">6</button>
          <button class="button operator">-</button>
        </div>
        <div>
          <button class="button">1</button>
          <button class="button">2</button>
          <button class="button">3</button>
          <button class="button operator">+</button>
        </div>

        <div>
          <button class="button">00</button>
          <button class="button">0</button>
          <button class="button">.</button>
          <button class="button equalBtn">=</button>
        </div>
      </div>
    </div>
    <script src="script.js"></script>
  </body>
</html>
