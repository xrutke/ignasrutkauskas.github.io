<!DOCTYPE html>
<html lang="lt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Ignas Rutkauskas – Asmeninis Profilis</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@picocss/pico@1/css/pico.min.css">
</head>
<body>

  <!-- Navigacija -->
  <nav class="container-fluid">
    <ul>
      <li><strong>Ignas Rutkauskas</strong></li>
    </ul>
    <ul>
      <li><a href="#apie">Apie</a></li>
      <li><a href="#projektai">Projektai</a></li>
      <li><a href="#kontaktai" role="button">Kontaktai</a></li>
    </ul>
  </nav>

  <!-- Pagrindinis turinys -->
  <main class="container">
    <div class="grid">
      <section id="apie">
        <hgroup>
          <h2>Apie mane</h2>
          <h3>Trumpas įvadas</h3>
        </hgroup>
        <p>Sveiki! Esu Ignas Rutkauskas – kūrybingas ir motyvuotas specialistas, besidomintis technologijomis, programavimu ir dizainu. Mano tikslas – kurti vertingus sprendimus, kurie džiugina vartotojus.</p>
        <figure>
          <img src="https://source.unsplash.com/800x400/?technology,profile" alt="Ignas Rutkauskas">
          <figcaption><a href="https://unsplash.com" target="_blank">Nuotrauka iš Unsplash</a></figcaption>
        </figure>
        <h3>Pagrindiniai įgūdžiai</h3>
        <p>Programavimas (HTML, CSS, JavaScript), web dizainas, projektų valdymas, kūrybinis rašymas.</p>

        <h3>Pomėgiai</h3>
        <p>Technologijos, sportas, kelionės, fotografija.</p>
      </section>

      <!-- Projektai -->
      <section id="projektai">
        <hgroup>
          <h2>Projektai</h2>
          <h3>Mano darbai</h3>
        </hgroup>
        <p>Čia pateikiami keli mano atlikti projektai. Daugiau netrukus!</p>
      </section>
    </div>
  </main>

  <!-- Prenumerata -->
  <section aria-label="Prenumerata">
    <div class="container">
      <article>
        <hgroup>
          <h2>Prenumeruokite</h2>
          <h3>Gaukite naujienas tiesiai į savo el. paštą</h3>
        </hgroup>
        <form class="grid">
          <input type="text" id="firstname" name="firstname" placeholder="Vardas" aria-label="Vardas" required>
          <input type="email" id="email" name="email" placeholder="El. paštas" aria-label="El. paštas" required>
          <button type="submit" onclick="event.preventDefault()">Prenumeruoti</button>
        </form>
      </article>
    </div>
  </section>

  <!-- Kontaktai -->
  <footer class="container" id="kontaktai">
    <small>
      <a href="#">El. paštas</a> • <a href="#">LinkedIn</a> • <a href="#">GitHub</a>
    </small>
  </footer>

</body>
</html>
