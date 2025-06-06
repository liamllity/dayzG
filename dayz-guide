<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>DayZ Guide</title>
  <style>
    :root {
      --bg-color: #111;
      --text-color: #f0f0f0;
      --header-color: #ff5555;
    }

    body.light-mode {
      --bg-color: #f4f4f4;
      --text-color: #111;
      --header-color: #c0392b;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: var(--bg-color);
      color: var(--text-color);
      margin: 0;
      padding: 0;
      transition: background-color 0.3s, color 0.3s;
    }
    header {
      position: relative;
      background: #000;
      padding: 0;
      text-align: center;
    }
    header img {
      width: 100%;
      height: auto;
      opacity: 0.5;
    }
    header h1 {
      position: absolute;
      top: 35%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-size: 2.5em;
      color: #fff;
      margin: 0;
      text-shadow: 2px 2px 4px #000;
    }
    nav {
      background-color: #222;
      padding: 10px;
      text-align: center;
      flex-wrap: wrap;
    }
    .nav-button {
      background-color: #333;
      border: none;
      color: #ddd;
      padding: 10px 15px;
      margin: 5px;
      font-size: 1em;
      cursor: pointer;
      border-radius: 5px;
      transition: background-color 0.3s, color 0.3s;
    }
    .nav-button:hover {
      background-color: #555;
      color: #fff;
    }
    section {
      display: none;
      padding: 20px;
      max-width: 900px;
      margin: auto;
    }
    section.active {
      display: block;
    }
    h2 {
      color: var(--header-color);
      border-bottom: 1px solid #444;
      padding-bottom: 5px;
      transition: transform 0.3s;
    }
    h2:hover {
      transform: scale(1.05);
    }
    h3 {
      color: #f08888;
    }
    .subsection {
      margin-top: 20px;
      padding-left: 20px;
    }
    footer {
      background-color: #222;
      color: #aaa;
      text-align: center;
      padding: 20px;
    }
    a {
      color: #66ccff;
    }
    a:hover {
      color: #99ddff;
    }
    .toggle-mode {
      background: none;
      color: #66ccff;
      border: 1px solid #66ccff;
      padding: 6px 12px;
      border-radius: 5px;
      cursor: pointer;
      margin: 10px;
    }
    @media (max-width: 600px) {
      header h1 {
        font-size: 2em;
        top: 25%;
      }
      .nav-button {
        width: 90%;
        margin: 5px auto;
        display: block;
      }
    }
  </style>
  <script>
    function showSection(id) {
      const sections = document.querySelectorAll('section');
      sections.forEach(section => section.classList.remove('active'));
      const selected = document.getElementById(id);
      if (selected) {
        selected.classList.add('active');
      }
    }
    function toggleMode() {
      document.body.classList.toggle('light-mode');
    }
    window.onload = () => {
      showSection('history');
    };
  </script>
</head>
<body>
  <header>
    <img src="https://cdn.cloudflare.steamstatic.com/steam/apps/221100/header.jpg" alt="DayZ Cover" />
    <h1>DayZ Guide</h1>
  </header>

  <nav>
    <button class="toggle-mode" onclick="toggleMode()">ðŸŒ™/â˜€ï¸ Mode</button>
    <button class="nav-button" onclick="showSection('history')">History</button>
    <button class="nav-button" onclick="showSection('gameplay')">Gameplay</button>
    <button class="nav-button" onclick="showSection('crafting')">Crafting</button>
    <button class="nav-button" onclick="showSection('gear')">Gear</button>
    <button class="nav-button" onclick="showSection('survival')">Survival</button>
    <button class="nav-button" onclick="showSection('tips')">Tips</button>
    <button class="nav-button" onclick="showSection('maps')">Maps</button>
  </nav>

  <section id="history" class="active">
    <h2>Game History</h2>
    <div class="subsection">
      <p>DayZ is an open-world multiplayer survival game developed by Bohemia Interactive. It began as a mod for ARMA 2 before becoming a standalone game in 2013. It features realistic survival mechanics, including hunger, thirst, health, and player interaction in a post-apocalyptic world filled with zombies and other survivors.</p>
      <p>The game emphasizes realism, including permadeath, dynamic weather, diseases, and injury mechanics. Over the years, DayZ has expanded its map, added new weapons, items, base-building systems, and more.</p>
    </div>
  </section>

  <section id="gameplay">
    <h2>Gameplay Overview</h2>
    <div class="subsection">
      <p>You begin with minimal gear and must scavenge the environment for food, water, weapons, and medical supplies. Interaction with other players can be friendly or hostile. Every choice matters for your survival.</p>
      <ul>
        <li>Hunger and thirst management</li>
        <li>Combat with firearms and melee weapons</li>
        <li>Infection and injury treatment</li>
        <li>Crafting and base building</li>
        <li>Stealth and strategy</li>
      </ul>
    </div>
  </section>

  <section id="crafting">
    <h2>Crafting & Recipes</h2>
    <div class="subsection">
      <p>Crafting allows players to create useful items such as bandages, splints, improvised backpacks, and more. Here are some examples:</p>
      <ul>
        <li><strong>Bandages:</strong> Combine rags from clothes</li>
        <li><strong>Splint:</strong> Stick + Rags</li>
        <li><strong>Improvised Backpack:</strong> Burlap sack + Rope + Sticks</li>
        <li><a href="https://dayz.fandom.com/wiki/Crafting" target="_blank">Full Crafting List</a></li>
      </ul>
    </div>
  </section>

  <section id="gear">
    <h2>Gear & Loot</h2>
    <div class="subsection">
      <p>Gear is essential for survival and comes in different tiers:</p>
      <ul>
        <li><strong>Tier 1:</strong> Civilian gear (basic clothing, melee weapons)</li>
        <li><strong>Tier 2:</strong> Military outpost gear (helmets, rifles)</li>
        <li><strong>Tier 3:</strong> High-tier bases and helicopter crashes (advanced gear)</li>
        <li><a href="https://dayz.fandom.com/wiki/Loot" target="_blank">Loot Guide</a></li>
        <li><a href="https://www.youtube.com/watch?v=Z9xyhFj_owc" target="_blank">Tier List Video</a></li>
      </ul>
    </div>
  </section>

  <section id="survival">
    <h2>Survival Mechanics</h2>
    <div class="subsection">
      <p>Understanding how to manage health, temperature, and disease is key. Tips:</p>
      <ul>
        <li>Cook meat to avoid food poisoning</li>
        <li>Use water purification tablets</li>
        <li>Take vitamins to resist infection</li>
        <li>Build a fire to stay warm and dry</li>
      </ul>
    </div>
  </section>

  <section id="tips">
    <h2>Tips for Beginners</h2>
    <div class="subsection">
      <ul>
        <li>Always carry food, water, and medical supplies</li>
        <li>Stay quietâ€”zombies react to sound</li>
        <li>Don't trust everyoneâ€”players may kill on sight</li>
        <li>Find a map app or memorize landmarks</li>
        <li>Wear warm clothes in the north</li>
      </ul>
    </div>
  </section>

  <section id="maps">
    <h2>Map Resources</h2>
    <div class="subsection">
      <p>Explore the world of Chernarus and Livonia with these resources:</p>
      <ul>
        <li><a href="https://dayz.ginfo.gg/" target="_blank">Interactive DayZ Map (Chernarus)</a></li>
        <li><a href="https://www.izurvive.com/" target="_blank">iZurvive Map (Mobile Friendly)</a></li>
        <li><a href="https://dayz.fandom.com/wiki/Maps" target="_blank">Official Map Wiki</a></li>
      </ul>
    </div>
  </section>

  <footer>
    &copy; 2025 DayZ Fan Guide. All rights reserved.
  </footer>
</body>
</html>
