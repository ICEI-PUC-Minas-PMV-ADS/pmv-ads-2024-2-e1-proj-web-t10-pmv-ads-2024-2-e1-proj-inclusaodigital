# Template padrão da Aplicação

Layout padrão do site (HTML e CSS) que será utilizado em todas as páginas com a definição de identidade visual, aspectos de responsividade e iconografia.

Layout Padrão HTML
<!doctype html>
<html>

<head>
  <link rel="stylesheet" href="style.css">
  </head>
<body>
  
  <div class="header">
    <h1>CIDADANIA DIGITAL</h1>
    <p>Ativos em Maturidade e Saúde.</p>
  </div>

  <form>
    <input type="search" name="q" placeholder="Pesquisar" />
    <input type="submit" value="Buscar" />
  </form>

  <div class="topnav">
    <a href="#">QUEM SOMOS</a>
    <a href="#">TUTORIAIS</a>
    <a href="#">AGENDAMENTOS</a>
    <a href="#">APOSENTADORIA</a>
    <a href="#">DEFICIENTES(PCD)</a>
    <a href="#">ENTERTENIMENTO</a>
    <a href="#" style="float:right">FALE CONOSCO</a>
  </div>
<main>
  <div class="row">
    <div class="leftcolumn">
      <div class="card">        
        <h2>CONECTE-SE</h2> 
        <img src="idosos1.jpg.jpg"
        <div class="fakeimg" style="height: 350px"; style="width: 150px";"</div>    
        <p>Cidadania Digital é essencial em especial os idosos, enfrentam dificuldades com tecnologias.
          O projeto "Cidadania Digital" visa simplificar o acesso a serviços essenciais,
          como sites governamentais e ferramentas essenciais, por meio de uma plataforma inclusiva
          que oferece guias e tutoriais.</p>
        <p>O objetivo é promover a autonomia e facilidade ao acesso a informações importantes de maneira rápida e
          dinâmica.</p>
      </div>
      <div class="card">
        <h2>USUÁRIOS</h2>
        <img src="idosos2.jpg.jpg"
        <div class="fakeimg" style="height:450px;" </div>
        <p>Os efeitos da exclusão digital podem atingir pessoas de diferentes idades e locais,
          mas o foco deste projeto está principalmente na acessibilidade para usuários idosos com mais de 60 anos.
          Esse grupo enfrenta dificuldades para acessar serviços digitais devido à pouca familiaridade com tecnologia
          e limitações físicas. Além dos idosos, adultos entre 45 e 59 anos também são considerados, pois, apesar de
          possuírem conhecimentos básicos de tecnologia, necessitam de uma ferramenta confiável para gerenciar serviços
          relacionados ao trabalho, saúde e finanças. Ambos os grupos demandam interfaces simples e tutoriais
          detalhados para facilitar a navegação em plataformas governamentais e bancárias, que muitas vezes são
          complexas demais
          para seus níveis de experiência.</p>
        <p>Outro grupo relevante são os cuidadores e familiares que assistem idosos no dia a dia e
          frequentemente auxiliam com questões tecnológicas. Esses usuários geralmente possuem um conhecimento
          intermediário de tecnologia e se beneficiariam de uma plataforma fácil de entender, que lhes permita orientar
          e apoiar os
          idosos de forma eficaz.</p>
      </div>
    </div>
    <div class="rightcolumn">
      <div class="card">
        <h2>Cadastre-se</h2>
        <div <form action="/signup" method="post">
          <p>
            <label>Gênero</label><br>
            <label>
              <input type="radio" name="title" value="masculino">
              Masculino
            </label>
            <label>
              <input type="radio" name="title" value="feminino">
              Feminino
            </label>
          </p>
          <p>
            <label>Nome Completo</label><br>
            <input type="text" name="nome completo">
          </p>
          <p>
            <label>Email</label><br>
            <input type="email" name="email" required>
          </p>
          <p>
            <label>Número de Celular</label><br>
            <input type="telefone" name="celular">
          </p>
          <p>
            <label>Senha</label><br>
            <input type="senha" name="senha">
          </p>
          <p>
            <label>Estado</label><br>
            <select>
              <option>Belo Horizonte</option>
              <option>São Paulo</option>
              <option>Rio de Janeiro</option>
              <option>Espírito Santo</option>
              <option>Santa Catarina</option>
            </select>
          </p>
          <p>
            <label>
              <input type="checkbox" value="termos">
              Eu concordo com os <a href="/termos">termos e condições</a>
            </label>
          </p>
          <p>
            <button>Cadastrar</button>
            <button type="resetar">Entrar</button>
          </p>
          </form>
          <p>Tenha uma experiência dinâmica e prática conosco.</p>
        </div>
        <div>
          <form action="/subscribe" method="post">
            <fieldset>
              <legend>SUGESTÕES</legend>
              <div class="form-group">
                <label for="usr">Nome:</label>
                <input type="text" class="form-control" id="usr">
              </div>
              <div class="form-group">
                <label for="celular">Celular</celular>:</label>
                <input type="celular" class="form-control" id="celular">
                <div class="form-group">
                  <label for="comment">Esvreva aqui:</label>
                  <textarea class="form-control" rows="5" id="comment"></textarea>
                </div>
              </div>
              <button>Enviar Sugestão</button>
            </fieldset>
        </div>
        </form>
      </div>
    </div>
  </div>
  <aside>
    <h2>DÚVIDAS</h2>
    <ul>
      <li><a href="#">NÃO CONSIGO FAZER O LOGIN</a></li>
      <li><a href="#">ESQUECI MINHA SENHA</a></li>
      <li><a href="#">DÚVIDAS SOBRE OS TUTORIAIS</a></li>
      <li><a href="#">DÚVIDAS SOBRE APOSENTADORIA</a></li>
      <li><a href="#">DÚVIDAS SOBRE APLICATIVOS DE BANCO</a></li>
      <li><a href="#">TUDO SOBRE FGTS</a></li>
    </ul>
  </aside>
</main>
<footer class="footer">
  <div class="container">
  <p>&copy; 2024 Cidadania Digital, PUC Virtual</p>
  </div>
</footer>
</body>
</html>

Padrão Css:
< !DOCTYPE html><html><head><style>* {
  box-sizing: border-box;
}

body {
  font-family: Arial;
  padding: 10px;
  background: #ccffca;
}

/* Header/Blog Title */
.header {
  padding: 30px;
  text-align: center;
  background: white;
}

.header h1 {
  font-size: 50px;
}

/* Style the top navigation bar */
.topnav {
  overflow: hidden;
  background-color: #097722;
}

/* Style the topnav links */
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 16px 20px;
  text-decoration: none;
}

/* Change color on hover */
.topnav a:hover {
  background-color: #ddd;
  color: black;
}

/* Create two unequal columns that floats next to each other */
/* Left column */
.leftcolumn {
  float: left;
  width: 100%;
  ;
}

/* Right column */
.rightcolumn {
  float: left;
  width: 30%;
  background-color: #ccffca;
  padding-left: 40px;
}

/* Fake image */
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 10px;
}

/* Add a card effect for articles */
.card {
  background-color: white;
  padding: 30px;
  margin-top: 20px;
}

/* Clear floats after the columns */
.row::after {
   display: flex;
  clear: both;
  padding: 10px;
  margin-top: 20px;
}

/* DÚVIDAS */
.DÚVIDAS {
  padding: 20px;
  text-align: left;
  background: #0b0b0b;
   margin-top: 20px;
}

.footer {
  background-color: #097722;
  padding: 10px;
  text-align: center;
  clear: both;
  position: relative;
  width: 100%;
  bottom: 0;
  }
  
  .footer .container {
  max-width: 800px;
  margin: 0 auto;
  }
  
  .footer p {
  margin-bottom: 10px;
  font-size: 20px;
  color: #ffffff;
  }
  
</style></head><body>

> **Links Úteis**:
>
> - [CSS Website Layout (W3Schools)](https://www.w3schools.com/css/css_website_layout.asp)
> - [Website Page Layouts](http://www.cellbiol.com/bioinformatics_web_development/chapter-3-your-first-web-page-learning-html-and-css/website-page-layouts/)
> - [Perfect Liquid Layout](https://matthewjamestaylor.com/perfect-liquid-layouts)
> - [How and Why Icons Improve Your Web Design](https://usabilla.com/blog/how-and-why-icons-improve-you-web-design/)
