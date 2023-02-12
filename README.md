<!DOCTYPE html>
<html>
  <head>
    <style>
      #love-button {
        padding: 10px 20px;
        font-size: 20px;
        background-color: pink;
        color: white;
        border-radius: 5px;
        cursor: pointer;
      }

      #love-message {
        font-size: 20px;
        display: none;
      }
    </style>
  </head>
  <body>
    <button id="love-button">Confess Love</button>
    <div id="love-message">I love you.</div>

    <script>
const loveButton = document.getElementById("love-button");
      const loveMessage = document.getElementById("love-message");

      loveButton.addEventListener("click", () => {
        loveMessage.style.display = "block";
      });
    </script>
  </body>
</html>
