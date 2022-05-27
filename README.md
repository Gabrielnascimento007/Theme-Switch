# Theme-Switch
Rocketseat
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>Theme Switcher</title>
  </head>
  <body>
    <header>
      <div id="button">
        <img class="moon" src="assets/Vector (1).svg" alt="moon" />
        <img class="sun" src="assets/sun.svg" alt="sun" />
        <div class="ball"></div>
      </div>
    </header>

    <script>
      document.querySelector('.ball').addEventListener('click', e => {
        e.target.classList.toggle('ball-move')
        document.body.classList.toggle('light')
      })
    </script>
  </body>
</html>
