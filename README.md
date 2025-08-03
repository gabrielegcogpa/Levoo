# Levoo
git init
git add .
git commit -m "Primeiro upload do site Levoo"
git branch -M main
git remote add origin https://github.com/seu-usuario/levoo.git
git push -u origin main
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Levoo - Delivery Inteligente</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>🍔 Levoo</h1>
    <nav>
      <a href="#">Início</a>
      <a href="#">Restaurantes</a>
      <a href="#">Entrar</a>
    </nav>
  </header>

  <main>
    <section class="hero">
      <h2>Quer delivery? É com a Levoo! 🚀</h2>
      <p>Peça comida dos seus restaurantes favoritos com poucos cliques.</p>
      <a href="#" class="btn">Fazer pedido agora</a>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Levoo. Todos os direitos reservados.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background-color: #fafafa;
  color: #333;
}

header {
  background-color: #ff3d00;
  color: white;
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav a {
  color: white;
  margin-left: 1rem;
  text-decoration: none;
  font-weight: bold;
}

.hero {
  text-align: center;
  padding: 4rem 2rem;
  background-color: #fff;
}

.hero h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 2rem;
}

.btn {
  background-color: #ff3d00;
  color: white;
  padding: 0.75rem 1.5rem;
  border-radius: 30px;
  text-decoration: none;
  font-size: 1rem;
  transition: background-color 0.3s;
}

.btn:hover {
  background-color: #e63300;
}

footer {
  background-color: #eee;
  text-align: center;
  padding: 1rem;
  margin-top: 2rem;
  font-size: 0.9rem;
}
document.querySelector('.btn').addEventListener('click', () => {
  alert('Em breve você poderá fazer pedidos pelo sistema da Levoo!');
});
levoo/
├── index.html
├── style.css
└📄 index.html  
📄 style.css  
📄 script.js── script.js
