<!DOCTYPE html>
<html lang="sv">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Spektors Group</title>
  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    /* Bakgrundsfärg och fontinställningar */
    body {
      background-color: #000;
      color: #fff;
      font-family: Arial, sans-serif;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }

    /* Centrering av innehållet */
    .content {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      flex: 1;
      padding: 20px;
    }

    h1 {
      font-size: 2em;
      margin-bottom: 1rem;
      font-weight: normal;
    }

    p {
      font-size: 1.2em;
      max-width: 700px;
      line-height: 1.5;
      margin: 0 auto 2rem auto;
    }

    .contact a {
      color: #fff;
      text-decoration: underline;
    }

    footer {
      text-align: center;
      padding: 0.5rem 0;
      font-size: 0.9em;
    }

    /* Responsiv anpassning för mindre skärmar */
    @media (max-width: 600px) {
      h1 {
        font-size: 1.5em;
      }
      p {
        font-size: 1em;
      }
    }
  </style>
</head>
<body>

  <div class="content">
    <h1>Spektors Group</h1>
    <p>
      Vi leder förändring i gränslandet mellan teknik och användare – med fokus på innovation, automation och AI som skapar värde.
    </p>
    <p class="contact">
      Kontakta oss på <a href="mailto:info@spektors.se">info@spektors.se</a>
    </p>
  </div>

  <footer>
    © 2025 Spektors Group
  </footer>

</body>
</html>
