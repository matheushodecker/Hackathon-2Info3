<template>
  <main>
    <section class="paes-em-destaque">
      <div class="container">
        <div class="grid">
          <div class="item">
            <img alt="Pão em destaque 1" src="/src/imagens/caneta.jpeg" />
            <h3>Pão em destaque 1</h3>
            <p>R$10,00</p>
          </div>
          <div class="item">
            <img alt="Pão em destaque 2" src="/src/imagens/feb76bc5-6389-47f5-b9f1-4612fb44b1a1.jpeg"/>
            <h3>Pão em destaque 2</h3>
            <p>R$12,00</p>
          </div>
          <div class="item">
            <img alt="Pão em destaque 3" src="/src/imagens/ee0b56d0-48fb-49e9-abdb-d7bdfab1abf7.jpeg"/>
            <h3>Pão em destaque 3</h3>
            <p>R$15,00</p>
          </div>
          <div class="item">
            <img alt="Pão em destaque 4" src="/src/imagens/0bc39858-cec0-471c-a29b-460ec69d6099.jpeg"/>
            <h3>Pão em destaque 4</h3>
            <p>R$8,00</p>
          </div>
          <div class="item">
            <img alt="Pão em destaque 5" src="/src/imagens/fdc79e9c-c0c3-43d9-b64a-fd0e209aa959.jpeg"/>
            <h3>Pão em destaque 5</h3>
            <p>R$12,00</p>
          </div>
          <div class="item">
            <img alt="Pão em destaque 6" src="/src/imagens/06033385-aea0-42de-8d58-431b460cff17.jpeg"/>
            <h3>Pão em destaque 6</h3>
            <p>R$8,00</p>
          </div>
        </div>
      </div>
    </section>
    <section class="sobre">
      <div class="container">
        <div class="grid">
          <div class="item2">
            <h2 style="font-size: 40px; margin-top: 50px;">Padaria Grão de Ouro</h2>
            <p style="margin: 100px;">
              Conhecemos as necessidades especiais do pão e da farinha. Com mais de 10 anos de
              experiência, garantimos qualidade em cada pedaço.
            </p>
            <ul style="font-size: 20px;margin-left: 30px;">
              <li><strong style="color: maroon;">150+</strong> Sabores diversos</li>
              <li><strong style="color: maroon;">15</strong> Tipos de qualidade</li>
            </ul>
          </div>
          <div class="item">
            <img alt="Mão segurando pão" src="/src/imagens/eeede4bf-1154-410e-b481-8f2a3c94ca28.jpeg" />
          </div>
        </div>
      </div>
    </section>
    <section class="avaliacoes">
      <div class="container">
        <div class="estrelas">
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
        </div>
        <p>
          Os pães fresquinhos do Grão de Ouro são simplesmente deliciosos! Sempre impecáveis, aqui
          você pode encontrar qualidade e sabor para merenda, lanches, café da manhã e qualquer
          ocasião!
        </p>
        <img alt="Chef de cozinha" />
        <p>Grão de Ouro</p>
      </div>
    </section>
  </main>
  <footer>
    <div class="container">
      <div class="grid">
        <div class="item">
          <h3>Clientes</h3>
          <p>
            Registre-se e receba todas as novidades, promoções e informações sobre os nossos
            serviços.
          </p>
          <ul class="social-media">
            <li>
              <a href="#"><i class="fab fa-facebook-f"></i></a>
            </li>
            <li>
              <a href="#"><i class="fab fa-instagram"></i></a>
            </li>
            <li>
              <a href="#"><i class="fab fa-twitter"></i></a>
            </li>
            <li>
              <a href="#"><i class="fab fa-youtube"></i></a>
            </li>
          </ul>
          <p>Copyright © 2023 Padaria Grão de Ouro. Todos os direitos reservados.</p>
        </div>
        <div class="item">
          <h3>Recursos</h3>
          <ul>
            <li><a href="#">Novidades</a></li>
            <li><a href="#">Promoções</a></li>
            <li><a href="#">Serviços</a></li>
            <li><a href="#">Contato</a></li>
          </ul>
        </div>
        <div class="item">
          <h3>Fale conosco</h3>
          <p>Digite o seu endereço de email</p>
          <input type="email" placeholder="exemplo@email.com" />
          <button class="btn">Enviar</button>
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped>
body {
  font-family: sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

h1,
h2,
h3 {
  text-align: center;
  margin-top: 0;
  margin-bottom: 20px;
}

p {
  text-align: center;
  margin-bottom: 20px;
  line-height: 1.6;
}

.btn {
  display: inline-block;
  background-color: #007bff;
  color: #fff;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  text-decoration: none;
  transition: background-color 0.3s;
}

.btn:hover {
  background-color: #0056b3;
}

/* Header styles */
header {
  background-color: #fff;
  padding: 20px;
  border-bottom: 1px solid #ddd;
}

.logo img {
  max-width: 200px;
}

nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
  text-align: right;
}

nav li {
  display: inline-block;
  margin-left: 20px;
}

nav a {
  text-decoration: none;
  color: #333;
}

/* Hero section styles */
.hero {
  background-image: url('hero.jpg');
  background-size: cover;
  background-position: center;
  padding: 100px 0;
  text-align: center;
  color: #fff;
}

.hero h1 {
  font-size: 3em;
  margin-bottom: 20px;
}

.hero p {
  font-size: 1.2em;
  margin-bottom: 40px;
}

/* Pães frescos section styles */
.paes-frescos {
  padding: 40px 0;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
}
.item2{
  text-align: left;
  border: 1px solid #ddd;
  padding: 20px;
  margin-top: 20px;
  margin-right: 20px;
  border-radius: 25px ;
}
.item {
  text-align: left;
  padding: 20px;
}

.item img {
  max-width: 100%;
  height: auto;
  margin-bottom: 20px;
  border-radius: 15px;
  transition: transform 0.5s;
}
.item img:hover{
 animation-duration: 1s;
 transform: scale(1.12);
}

/* Pães em destaque section styles */
.paes-em-destaque {
  padding: 40px 0;
}

.paes-em-destaque .item {
  text-align: center;
}

/* Sobre section styles */
.sobre {
  padding: 40px 0;
}

.sobre .item {
  text-align: left;
}

.sobre ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

.sobre li {
  margin-bottom: 10px;
}

/* Avaliações section styles */
.avaliacoes {
  background-color: #A57C5B;
  padding: 40px 0;
  text-align: center;
}

.estrelas {
  font-size: 2em;
  margin-bottom: 20px;
  color: #ffc107;
}

/* Footer styles */
footer {
  background-color: #4D4036;
  color: #fff;
  padding: 40px 0;
}

footer .grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

footer h3 {
  margin-top: 0;
  margin-bottom: 20px;
}

footer ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

footer li {
  margin-bottom: 10px;
}

footer a {
  text-decoration: none;
  color: #fff;
}

.social-media li {
  display: inline-block;
  margin-right: 10px;
}

.social-media a {
  font-size: 1.5em;
  color: #fff;
}

.social-media a:hover {
  color: #ffc107;
}

input[type='email'] {
  width: 100%;
  padding: 10px;
  border: 1px solid #ddd;
  border-radius: 5px;
  margin-bottom: 10px;
}

/* Responsive styles */
@media (max-width: 768px) {
  .grid {
    grid-template-columns: 1fr;
  }
}
</style>
