
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Lioden CSS Preview</title>

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Georgia, serif;
  color: #B8C9A5;
  background-color: #273126;
  background-image:
    linear-gradient(
      rgba(76, 82, 72, 0.25),
      rgba(76, 82, 72, 0.25)
    ),
    url("1https://i.ibb.co/gLVVBLCJ/IMG-20261028-WA0000.jpg");
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
}

header {
  padding: 25px;
  text-align: center;
  background: rgba(25, 34, 25, 0.85);
  border-bottom: 2px solid #697B60;
}

header h1 {
  margin: 0;
  font-size: 36px;
  letter-spacing: 5px;
}

nav {
  padding: 12px;
  text-align: center;
  background: rgba(20, 28, 20, 0.9);
}

nav span {
  display: inline-block;
  margin: 5px 12px;
}

.container {
  display: grid;
  grid-template-columns: 240px 1fr;
  gap: 15px;
  max-width: 1100px;
  margin: 20px auto;
  padding: 0 12px;
}

.panel {
  margin-bottom: 15px;
  background: rgba(76, 82, 72, 0.88);
  border: 1px solid #697B60;
}

.panel h2 {
  margin: 0;
  padding: 12px;
  font-size: 17px;
  font-weight: normal;
  background: rgba(25, 34, 25, 0.55);
  border-bottom: 1px solid #697B60;
}

.content {
  padding: 15px;
}

.king {
  min-height: 180px;
  display: grid;
  place-items: center;
  text-align: center;
  background: rgba(25, 34, 25, 0.35);
  border: 1px dashed #B8C9A5;
}

.columns {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 15px;
}

.caves {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
}

.cave {
  min-height: 100px;
  display: flex;
  align-items: end;
  padding: 10px;
  background: rgba(25, 34, 25, 0.5);
  border: 1px solid #697B60;
}

footer {
  padding: 20px;
  text-align: center;
}

@media (max-width: 650px) {
  .container {
    grid-template-columns: 1fr;
  }

  .columns {
    grid-template-columns: 1fr;
  }

  .caves {
    grid-template-columns: 1fr 1fr;
  }
}
</style>
</head>

<body>

<header>
  <h1>LIODEN</h1>
  <p>THE LION SIMULATOR</p>
</header>

<nav>
  <span>Den</span>
  <span>Pride</span>
  <span>Breeding</span>
  <span>Explore</span>
  <span>Crossroads</span>
</nav>

<div class="container">

  <aside>
    <section class="panel">
      <h2>King of the Pride</h2>
      <div class="content">
        <div class="king">
          Imagem do rei
        </div>
        <h3>Borus II</h3>
        <p>Mngwa · G3 · Golden</p>
      </div>
    </section>

    <section class="panel">
      <h2>Territory</h2>
      <div class="content">
        Overview<br><br>
        Pride<br><br>
        Wishlist<br><br>
        Sales<br><br>
        Decorations
      </div>
    </section>
  </aside>

  <main>
    <section class="panel">
      <h2>Welcome to My Den</h2>
      <div class="content">
        Bem-vindo ao meu território!
      </div>
    </section>

    <div class="columns">
      <section class="panel">
        <h2>About Me</h2>
        <div class="content">
          Espaço para sua descrição.
        </div>
      </section>

      <section class="panel">
        <h2>Wishlist</h2>
        <div class="content">
          Espaço para seus itens desejados.
        </div>
      </section>
    </div>

    <section class="panel">
      <h2>Caves</h2>
      <div class="content caves">
        <div class="cave">Breeding</div>
        <div class="cave">Mutations</div>
        <div class="cave">For Sale</div>
        <div class="cave">Pregnant</div>
        <div class="cave">Unsorted</div>
        <div class="cave">Other Lions</div>
      </div>
    </section>

    <section class="panel">
      <h2>Art & Extras</h2>
      <div class="content">
        Espaço para arte e decorações.
      </div>
    </section>
  </main>

</div>

<footer>
  Lioden CSS Preview
</footer>

</body>
</html>
