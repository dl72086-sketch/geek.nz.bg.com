# geek.nz.bg.com
Lots of unblocked games
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Geek Games – Unblocked Fun</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    }

    body {
      background: #060818;
      color: #f5f5f5;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }

    header {
      background: #0b1120;
      border-bottom: 1px solid #1f2937;
      padding: 1rem 2rem;
      display: flex;
      align-items: center;
      justify-content: space-between;
      position: sticky;
      top: 0;
      z-index: 10;
    }

    .logo {
      font-weight: 800;
      font-size: 1.4rem;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      color: #38bdf8;
    }

    nav a {
      color: #e5e7eb;
      margin-left: 1.25rem;
      text-decoration: none;
      font-size: 0.95rem;
    }

    nav a:hover {
      color: #38bdf8;
    }

    .hero {
      padding: 3rem 2rem 2rem;
      text-align: center;
      background: radial-gradient(circle at top, #1d4ed8 0, transparent 55%),
                  radial-gradient(circle at bottom, #0ea5e9 0, transparent 60%);
    }

    .hero h1 {
      font-size: clamp(2.3rem, 4vw, 3rem);
      margin-bottom: 0.75rem;
    }

    .hero p {
      color: #e5e7eb;
      max-width: 600px;
      margin: 0 auto 1.5rem;
    }

    .hero button {
      background: #38bdf8;
      border: none;
      color: #020617;
      padding: 0.75rem 1.5rem;
      border-radius: 999px;
      font-weight: 600;
      cursor: pointer;
      transition: transform 0.1s ease, box-shadow 0.1s ease, background 0.15s;
    }

    .hero button:hover {
      background: #0ea5e9;
      transform: translateY(-1px);
      box-shadow: 0 10px 25px rgba(15, 23, 42, 0.6);
    }

    main {
      flex: 1;
      padding: 2rem;
      max-width: 1100px;
      width: 100%;
      margin: 0 auto 3rem;
    }

    .section-title {
      font-size: 1.4rem;
      margin-bottom: 1rem;
      border-left: 4px solid #38bdf8;
      padding-left: 0.5rem;
    }

    .games-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 1.5rem;
    }

    .game-card {
      background: #020617;
      border-radius: 0.75rem;
      border: 1px solid #1e293b;
      padding: 1rem;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      box-shadow: 0 12px 30px rgba(15, 23, 42, 0.8);
      transition: transform 0.12s ease, box-shadow 0.12s ease, border-color 0.12s;
    }

    .game-card:hover {
      transform: translateY(-4px);
      box-shadow: 0 20px 40px rgba(15, 23, 42, 0.95);
      border-color: #38bdf8;
    }

    .game-tag {
      display: inline-block;
      padding: 0.1rem 0.55rem;
      border-radius: 999px;
      background: rgba(56, 189, 248, 0.15);
      color: #7dd3fc;
      font-size: 0.7rem;
      text-transform: uppercase;
      letter-spacing: 0.08em;
      margin-bottom: 0.5rem;
    }

    .game-title {
      font-size: 1.1rem;
      font-weight: 600;
      margin-bottom: 0.35rem;
    }

    .game-desc {
      font-size: 0.9rem;
      color: #9ca3af;
      margin-bottom: 0.75rem;
    }

    .game-meta {
      display: flex;
      justify-content: space-between;
      align-items: center;
      font-size: 0.8rem;
      color: #6b7280;
      margin-bottom: 0.75rem;
    }

    .play-btn {
      align-self: flex-start;
      background: #22c55e;
      color: #022c22;
      border: none;
      padding: 0.45rem 0.9rem;
      border-radius: 999px;
      font-size: 0.85rem;
      font-weight: 600;
      cursor: pointer;
      text-decoration: none;
      display: inline-flex;
      align-items: center;
      gap: 0.25rem;
      transition: background 0.15s ease, transform 0.1s ease;
    }

    .play-btn:hover {
      background: #16a34a;
      transform: translateY(-1px);
    }

    footer {
      border-top: 1px solid #111827;
      padding: 1rem 2rem;
      text-align: center;
      font-size: 0.8rem;
      color: #6b7280;
      background: #020617;
    }

    @media (max-width: 640px) {
      header {
        flex-direction: column;
        align-items: flex-start;
        gap: 0.5rem;
      }

      .hero {
        padding: 2.25rem 1.25rem 1.75rem;
      }

      main {
        padding: 1.5rem 1.25rem 2.5rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">geek.nz.bg</div>
    <nav>
      <a href="#featured">Featured</a>
      <a href="#popular">Popular</a>
      <a href="#new">New</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Geek Games – Unblocked, Anytime.</h1>
    <p>
      Fast, clean, and simple access to your favorite unblocked games. No clutter,
      no fake links — just click and play.
    </p>
    <button onclick="document.getElementById('featured').scrollIntoView({ behavior: 'smooth' });">
      Start Playing
    </button>
  </section>

  <main>
    <!-- FEATURED GAMES -->
    <section id="featured" style="margin-bottom: 2.5rem;">
      <h2 class="section-title">Featured Games</h2>
      <div class="games-grid">
        <article class="game-card">
          <span class="game-tag">Action</span>
          <h3 class="game-title">Slope Unblocked</h3>
          <p class="game-desc">
            Roll down an endless neon slope, dodge obstacles, and try not to fall off.
            High speed, high risk.
          </p>
          <div class="game-meta">
            <span>Difficulty: ★★★★☆</span>
            <span>Plays: 12,430</span>
          </div>
          <!-- Replace # with the real game link -->
          <a class="play-btn" href="#" target="_blank" rel="noopener noreferrer">
            ▶ Play Now
          </a>
        </article>

        <article class="game-card">
          <span class="game-tag">Arcade</span>
          <h3 class="game-title">Retro Bowl</h3>
          <p class="game-desc">
            Build your dream football team and lead them to glory in this retro-style
            sports classic.
          </p>
          <div class="game-meta">
            <span>Difficulty: ★★☆☆☆</span>
            <span>Plays: 9,810</span>
          </div>
          <a class="play-btn" href="#" target="_blank" rel="noopener noreferrer">
            ▶ Play Now
          </a>
        </article>

        <article class="game-card">
          <span class="game-tag">Puzzle</span>
          <h3 class="game-title">2048 Classic</h3>
          <p class="game-desc">
            Slide tiles, merge numbers, and try to reach the 2048 tile. Easy to learn,
            hard to stop.
          </p>
          <div class="game-meta">
            <span>Difficulty: ★★★☆☆</span>
            <span>Plays: 7,560</span>
          </div>
          <a class="play-btn" href="#" target="_blank" rel="noopener noreferrer">
            ▶ Play Now
          </a>
        </article>
      </div>
    </section>

    <!-- POPULAR GAMES -->
    <section id="popular" style="margin-bottom: 2.5rem;">
      <h2 class="section-title">Popular Right Now</h2>
      <div class="games-grid">
        <article class="game-card">
          <span class="game-tag">Multiplayer</span>
          <h3 class="game-title">Krunker.io</h3>
          <p class="game-desc">
            Fast-paced online FPS. Jump into a lobby and test your aim against
            players around the world.
          </p>
          <div class="game-meta">
            <span>Difficulty: ★★★★☆</span>
            <span>Plays: 21,004</span>
          </div>
          <a class="play-btn" href="#" target="_blank" rel="noopener noreferrer">
            ▶ Play Now
          </a>
        </article>

        <article class="game-card">
          <span class="game-tag">Casual</span>
          <h3 class="game-title">Cookie Clicker</h3>
          <p class="game-desc">
            Click, upgrade, and watch the numbers explode in this oddly satisfying
            idle game.
          </p>
          <div class="game-meta">
            <span>Difficulty: ★☆☆☆☆</span>
            <span>Plays: 15,722</span>
          </div>
          <a class="play-btn" href="#" target="_blank" rel="noopener noreferrer">
            ▶ Play Now
          </a>
        </article>

        <article class="game-card">
          <span class="game-tag">Racing</span>
          <h3 class="game-title">Moto X3M</h3>
          <p class="game-desc">
            Race through crazy tracks, pull off stunts, and try to beat the clock
            without crashing.
          </p>
          <div class="game-meta">
            <span>Difficulty: ★★★★☆</span>
            <span>Plays: 13,998</span>
          </div>
          <a class="play-btn" href="#" target="_blank" rel="noopener noreferrer">
            ▶ Play Now
          </a>
        </article>
      </div>
    </section>

    <!-- NEW GAMES / PLACEHOLDERS -->
    <section id="new">
      <h2 class="section-title">New &amp; Just Added</h2>
      <div class="games-grid">
        <article class="game-card">
          <span class="game-tag">New</span>
          <h3 class="game-title">Add Your Game Here</h3>
          <p class="game-desc">
            Edit this card in the HTML and drop in a new unblocked game link.
            Change the title, description, and stats.
          </p>
          <div class="game-meta">
            <span>Difficulty: ★★☆☆☆</span>
            <span>Plays: 0</span>
          </div>
          <a class="play-btn" href="#" target="_blank" rel="noopener noreferrer">
            ▶ Play Now
          </a>
        </article>

        <article class="game-card">
          <span class="game-tag">New</span>
          <h3 class="game-title">Add Another Game</h3>
          <p class="game-desc">
            Duplicate this game card block to quickly grow your library.
          </p>
          <div class="game-meta">
            <span>Difficulty: ★★☆☆☆</span>
            <span>Plays: 0</span>
          </div>
          <a class="play-btn" href="#" target="_blank" rel="noopener noreferrer">
            ▶ Play Now
          </a>
        </article>

        <article class="game-card">
          <span class="game-tag">New</span>
          <h3 class="game-title">Your Secret Game</h3>
          <p class="game-desc">
            Keep a hidden gem here that only your friends know about.
          </p>
          <div class="game-meta">
            <span>Difficulty: ★★★☆☆</span>
            <span>Plays: 0</span>
          </div>
          <a class="play-btn" href="#" target="_blank" rel="noopener noreferrer">
            ▶ Play Now
          </a>
        </article>
      </div>
    </section>
  </main>

  <footer>
    geek.nz.bg.com · Built by Dillon · Unblocked games for everyone
  </footer>
</body>
</html>
