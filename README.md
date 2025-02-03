<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Guia Comercial - Seu Portal de Negócios</title>
  <link rel="stylesheet" href="styles.css">
  <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
</head>
<body>
  <header>
    <nav class="navbar">
      <div class="logo">
        <h1>Guia Comercial</h1>
      </div>
      <ul class="nav-links">
        <li><a href="#home">Início</a></li>
        <li><a href="#categories">Categorias</a></li>
        <li><a href="#businesses">Empresas</a></li>
        <li><a href="#contact">Contato</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="banner" class="advertise-banner">
      <div class="banner-content">
        <h2>Anuncie Aqui</h2>
        <p>Destaque sua empresa e alcance mais clientes!</p>
        <a href="#contact" class="cta-button">Faça Seu Anúncio</a>
      </div>
    </section>

    <section id="categories" class="categories">
      <h2>Categorias</h2>
      <div class="category-grid">
        <div class="category-card" data-category="servicos">
          <i data-feather="briefcase"></i>
          <h3>Serviços</h3>
        </div>
        <div class="category-card" data-category="comercio">
          <i data-feather="shopping-bag"></i>
          <h3>Comércio</h3>
        </div>
        <div class="category-card" data-category="industria">
          <i data-feather="tool"></i>
          <h3>Indústria</h3>
        </div>
        <div class="category-card" data-category="construcao">
          <i data-feather="home"></i>
          <h3>Construção</h3>
        </div>
      </div>
    </section>

    <section id="businesses" class="businesses">
      <h2>Empresas em Destaque</h2>
      <div class="business-grid">
        <!-- Business cards will be dynamically populated -->
      </div>
    </section>

    <section id="contact" class="contact">
      <h2>Faça Seu Anúncio</h2>
      <form id="advertise-form" class="contact-form">
        <input type="text" name="businessName" placeholder="Nome da Empresa" required>
        <select name="category" required>
          <option value="">Selecione uma Categoria</option>
          <option value="servicos">Serviços</option>
          <option value="comercio">Comércio</option>
          <option value="industria">Indústria</option>
          <option value="construcao">Construção</option>
        </select>
        <input type="text" name="description" placeholder="Breve descrição dos serviços" required>
        <input type="file" name="businessImage" accept="image/*" required>
        <input type="email" name="email" placeholder="Seu E-mail" required>
        <input type="tel" name="phone" placeholder="Seu Telefone">
        <button type="submit" class="submit-button">Enviar Anúncio</button>
      </form>
    </section>
  </main>

  <footer>
    <div class="footer-content">
      <p>&copy; 2023 Guia Comercial. Todos os direitos reservados.</p>
      <div class="social-links">
        <a href="#"><i data-feather="facebook"></i></a>
        <a href="#"><i data-feather="instagram"></i></a>
        <a href="#"><i data-feather="linkedin"></i></a>
      </div>
    </div>
  </footer>

  <script src="script.js" type="module"></script>
  <script>
    feather.replace();
  </script>
</body>
</html>
