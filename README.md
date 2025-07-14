<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="shortcut icon" type="image/png" href="./images/favicon.png" />

  <!-- Put your site title here -->
  <title>
    Breno | Um desenvolverdor web iniciante
  </title>

  <meta name="description" content="Add small description of yourslef.">
  <!-- Add some coding keywords below, Ex: (React, CSS etc) -->
  <meta name="keywords" content="Put your name, skills and some coding keywords" />
  <link rel="stylesheet" href="index.css" />
</head>

<body>

  <!-- ***** Header ***** -->

  <header class="header" role="banner" id="top">
    <div class="row">
      <nav class="nav" role="navigation">
        <ul class="nav__items">
          <li class="nav__item"><a href="#work" class="nav__link">Meus Trabalhos</a></li>
          <li class="nav__item">
            <a href="#about" class="nav__link">Sobre</a>
          </li>
          <li class="nav__item">
            <a href="#contact" class="nav__link">Contato</a>
          </li>
        </ul>
      </nav>
    </div>
    <div class="header__text-box row">
      <div class="header__text">
        <h1 class="heading-primary">
          <!-- Replace the following name with your name -->
          <span>Breno Gualberto do Nascimento</span>
        </h1>
        <!-- Put a small paragraph about yourself -->
        <p>Um desenvolverdor web iniciante</p>
        <a href="#contact" class="btn btn--pink">Veja Mais</a>
      </div>
    </div>
  </header>

  <main role="main">

    <!-- ***** Work ***** -->

    <section class="work" id="work">
      <div class="row">
        <h2>Meus trabalhos</h2>
        <div class="work__boxes">

          <!-- Each div with the work__box class is a project. -->

          <div class="work__box">
            <div class="work__text">
              <h3>Hubble</h3>
              <p>
                Um projeto feito para um TCC do SENAI.
              </p>
              <ul class="work__list">
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>PHP e SQL</li>
              </ul>
            </div>

            <div class="work__image-box">
              <img src="./images/project-1.png" class="work__image" alt="Project 1" />
            </div>
          </div>

          <div class="work__box">
            <div class="work__text">
              <h3>Site de Cadastro</h3>
              <p>
                Um teste de conexão com PHP e Banco de Dados
              </p>
              <ul class="work__list">
                <li>HTML</li>
                <li>CSS</li>
                <li>PHP e SQL</li>
              </ul>

            </div>
            <div class="work__image-box">
              <img src="./images/project-2.png" class="work__image" alt="Project 1" />
            </div>
          </div>

          <div class="work__box">
            <div class="work__text">
              <h3>Sistema de Cadastro (JS)</h3>
              <p>
                Uma página que realiza cadastros, usando como base o JavaScript.
              </p>
              <ul class="work__list">
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
              </ul>
            </div>
            <div class="work__image-box">
              <img src="./images/project-3.png" class="work__image" alt="Project 3" />
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ***** About ***** -->

    <section class="about" id="about">
      <div class="row">
        <h2>Sobre Mim</h2>
        <div class="about__content">
          <div class="about__text">
            <p>
                Sou um desenvolverdor web iniciante, fazendo o curso Técnico de Informática para Internet, no SENAI.</p>
          </div>
          <div class="about__photo-container">
            <img class="about__photo" src="./images/imagem.jpeg" alt="" />
          </div>
        </div>
      </div>
    </section>
  </main>

  <!-- ***** Contact ***** -->

  <section class="contact" id="contact">
    <div class="row">
      <h2>Contato</h2>
      <div class="contact__info">
        <p>
          <b>Email:</b> 0001066177@senaimgaluno.com.br
        </p>
        <p>
          <b>Telefone:</b> (37) 99801-2865
        </p>
        <!-- Replace the email with yours -->
      </div>
    </div>
  </section>

  <!-- ***** Footer ***** -->

  <footer role="contentinfo" class="footer">
    <div class="row">
      <!-- Update the links to point to your accounts -->
      <ul class="footer__social-links">
        <li class="footer__social-link-item">
            <img src="./images/twitter.svg" class="footer__social-image" alt="Twitter">
        </li>
        <li class="footer__social-link-item">
            <img src="./images/github.svg" class="footer__social-image" alt="Github">
        </li>
        <li class="footer__social-link-item">
            <img src="./images/codepen.svg" class="footer__social-image" alt="Codepen">
        </li>
        <li class="footer__social-link-item">
            <img src="./images/linkedin.svg" title="Link to Linkedin Profile" class="footer__social-image" alt="Linkedin">
        </li>
      </ul>
    </div>
  </footer>
</html>
