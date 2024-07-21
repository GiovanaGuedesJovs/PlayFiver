<template>
<head>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
  <div class="header">
    <nav class="navbar navbar-expand-lg bg-light navTop fixed-top">
      <a class="navbar-brand d-flex align-items-center" href="#">
        <img alt="Vue logo" class="logo" src="./assets/images/logo.jpg" width="40" height="40" />
        <span class="ms-2" style=font-weight:600>PLAY FIVER</span>
      </a>
      <div class="collapse navbar-collapse justify-content-end">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link itemMenu" href="#">Início</a>
          </li>
          <li class="nav-item">
            <a class="nav-link itemMenu" href="#">Suporte</a>
          </li>
          <li class="nav-item">
            <a class="nav-link itemMenu" href="#">Sobre nós</a>
          </li>
          <li class="nav-item ml-5">
            <a class="nav-link btn btnMain" href="#" style="margin-left: 30px !important;">
              Entrar <ArrowRightIcon class="icon"/>
            </a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
  <div class="bodyWelcome">
    <div class="row">
      <div class="col colunaTexto">
        <div class="content h-100">
          <h1 class="title1">Venha descobrir a</h1>
          <h1 class="title2">Play Fiver</h1>
          <p>Nossa API fornece diversos jogos de slots e ao vivo, com um GRR muito baixo.</p>
          <button class="btn btnMain">Cadastrar</button>
        </div>
      </div>
      <div class="col-4 colunaImagem" >
        <img src="./assets/images/imageWelcome.JPG" alt="">
      </div>
    </div>
  </div>
  <div class="bodyApresentacao">
    <h2 class="title text-center">Descubra nossa vasta rede com</h2>
    <h2 class="title text-center">um suporte eficiente</h2>
    <p class="text-center p-2">Rapidez e confiança em uma só solução</p>
    <div class="row text-center rowCards">
      <div class="col">
        <div class="cardCol col1">
          <img src="./assets/images/imageApresentacaoCol1.JPG" width="50" height="45" alt="">
          <h5 class="subtitle">GRR muito baixo</h5>
          <p>Oferecemos jogos de slots e ao vivo com um GRR extremamente baixo, aumentando seus lucros.</p>
        </div>
      </div>
      <div class="col">
        <div class="cardCol col2">
          <img src="./assets/images/imageApresentacaoCol2.JPG" width="50" height="45" alt="">
          <h5 class="subtitle">Servidores no Brasil</h5>
          <p>Nossa API utiliza servidores no Brasil, garantindo alta performance e disponibilidade.</p>
        </div>
      </div>
      <div class="col">
        <div class="cardCol col3">
          <img src="./assets/images/imageApresentacaoCol3.JPG" width="50" height="45" alt="">
          <h5 class="subtitle">Recarga com o PIX</h5>
          <p>Facilitamos recargas com Pix, tornando a operação do seu cassino mais ágil e segura.</p>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-5 colunaImagem2">
          <img src="./assets/images/imageApresentacao.JPG" alt="" class="imageApresentacao">
      </div>
      <div class="col">
          <h2 class="title" style="margin: 0">Uma das APIs mais confiáveis para cassinos</h2>
          <p style="margin: 20px 0 40px 0">A Play Fiver oferece uma API repleta de jogos variados, perfeita para suas necessidades. Contamos com um suporte técnico sempre à disposição para resolver qualquer problema rapidamente. Nossos servidores estão localizados no Brasil, garantindo alta performance, estabilidade e velocidade. Além disso, você pode recarregar sua API de maneira prática e ágil utilizando Pix, proporcionando mais conveniência para você. Nosso objetivo é oferecer uma integração perfeita, com jogos de alta qualidade, suporte dedicado e uma experiência ágil. Junte-se a nós e aproveite tudo o que a Play Fiver tem a oferecer!</p>
           <button class="btn btnMain">Descobrir</button>
      </div>
    </div>
  </div>
  <div class="bodyClientes">
    <div class="row">
      <div class="col colTexto">
        <h2 class="title" style="margin: 0">Avançando em</h2>
        <h2 class="title" style="margin: 0; color: #2593B4">diversas frentes</h2>
        <p style="margin-top:10px"> Progredindo para conquistar o mercado</p>
      </div>
      <div class="col colItems">
        <div class="row">
          <div class="col" style="margin-bottom: 30px">
            <div class="colIcon">
              <i class="fa-solid fa-users"></i>
            </div>
            <div class="colContent">
              <h3 class="m-0">1.673</h3>
              <p>Clientes </p>
            </div>
          </div>
         <div class="col" style="margin-bottom: 30px">
            <div class="colIcon">
              <i class="fa-solid fa-chart-line"></i>
            </div>
            <div class="colContent">
              <h3 class="m-0">1.673</h3>
              <p>Cassinos </p>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col" style="margin-bottom: 30px">
            <div class="colIcon">
              <i class="fa-solid fa-gamepad"></i>
            </div>
            <div class="colContent">
              <h3 class="m-0">1.673</h3>
              <p>Jogos </p>
            </div>
          </div>
         <div class="col" style="margin-bottom: 30px">
            <div class="colIcon">
              <i class="fa-solid fa-chart-bar"></i>
            </div>
            <div class="colContent">
              <h3 class="m-0">15 %</h3>
              <p>GRR</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="bodyApresentacao">
      <div class="row d-flex align-items-stretch" style="margin-bottom: 20px">
          <div class="col-4 colunaImagem2 h-100" style="text-align: center !important">
              <img src="./assets/images/imageApresentacao2.JPG" alt="" class="imageApresentacao2">
          </div>
          <div class="col h-100">
              <h2 class="title" style="margin: 0">Por que escolher a Play Fiver com tantas opções no mercado?</h2>
              <p style="margin: 20px 0 40px 0">A Play Fiver oferece jogos de fornecedores líderes, suporte técnico ágil e servidores rápidos no Brasil, garantindo uma experiência de alta qualidade. As recargas são simples e seguras via Pix, e nossa API conta com uma ampla variedade de jogos. Com uma taxa de retorno ao jogador (GRR) entre 2% e 10%, maximizamos sua rentabilidade. Escolha a Play Fiver e aproveite todos esses benefícios!</p>
          </div>
      </div>
      <div class="row text-center d-flex align-items-stretch rowCards2">
          <div class="col h-100">
              <div class="cardCol col1">
                  <h5 class="subtitle">Provedores de renome</h5>
                  <p>Oferecemos jogos de fornecedores líderes do setor, garantindo uma experiência premium para seus jogadores.</p>
              </div>
          </div>
          <div class="col h-100">
              <div class="cardCol col2">
                  <h5 class="subtitle">Suporte técnico dedicado</h5>
                  <p>Nossa equipe de suporte está sempre disponível para ajudar a resolver qualquer problema rapidamente e garantir uma operação tranquila.</p>
              </div>
          </div>
          <div class="col h-100">
              <div class="cardCol col3">
                  <h5 class="subtitle">Servidores de alta performance</h5>
                  <p>Utilizamos servidores localizados no Brasil, proporcionando alta velocidade e estabilidade para seus jogos.</p>
              </div>
          </div>
      </div>
      <div class="row text-center rowCards d-flex align-items-stretch">
          <div class="col h-100">
              <div class="cardCol col1">
                  <h5 class="subtitle">Fácil recarga PIX</h5>
                  <p>Oferecemos a conveniência de recargas rápidas e seguras através do Pix, simplificando a gestão financeira.</p>
              </div>
          </div>
          <div class="col h-100">
              <div class="cardCol col2">
                  <h5 class="subtitle">Variedade de jogos</h5>
                  <p>Nossa API inclui uma ampla gama de jogos, incluindo slots e jogos ao vivo, para atender a todos os gostos dos jogadores.</p>
              </div>
          </div>
          <div class="col h-100">
              <div class="cardCol col3">
                  <h5 class="subtitle">GRR competitivo</h5>
                  <p>Nossa taxa de retorno ao jogador (GRR) é muito baixa, variando de 2% a 10%, maximizando a rentabilidade do seu cassino.</p>
              </div>
          </div>
      </div>
  </div>
  <div class="bodyClientes">
    <div class="row">
      <div class="col colLogo" style="padding:0; max-width: 300px;">
        <img alt="Vue logo" class="logo2" src="./assets/images/logo.png" width="400" height="400" />
      </div>
      <div class="col colItems">
        <p>Play Fiver: a sua escolha inteligente para uma experiência de jogos premium, com suporte técnico dedicado e soluções de recarga ágeis, tudo para maximizar a rentabilidade do seu negócio.</p>
        <p style="color:#2593B4; font-weight: bold">Contato e Suporte</p>
        <p>Participe do nosso grupo no Telegram para receber suporte dedicado, documentação de integração da API e as últimas notícias sobre nossa API de jogos..</p>
        <div>
          <a href="#" class="social-icon2"><i class="fab fa-instagram"></i></a>
           <a href="#" class="social-icon2"><i class="fab fa-twitter"></i></a>
           <a href="https://t.me/playfiver" class="social-icon2"><i class="fab fa-telegram"></i></a>
           <a href="#" class="social-icon2"><i class="fab fa-youtube"></i></a>
        </div>
      </div>
    </div>
  </div>
  <footer class="footer">
    <div class="content">
      <div class="row">
        <div class="col">
          <p>Copyright © 2024 PlayFiver.</p>
          <p>Todos direitos reservados</p>
           <a href="#" class="social-icon"><i class="fab fa-instagram"></i></a>
           <a href="#" class="social-icon"><i class="fab fa-twitter"></i></a>
           <a href="https://t.me/playfiver" class="social-icon"><i class="fab fa-telegram"></i></a>
           <a href="#" class="social-icon"><i class="fab fa-youtube"></i></a>
        </div>
        <div class="col">
          <h5>Compania</h5>
          <ul>
            <li><a href="#">Sobre nós</a></li>
            <li><a href="#">Entre em contato</a></li>
            <li><a href="#">Descubra</a></li>
          </ul>
        </div>
        <div class="col">
          <h5>Suporte</h5>
          <ul>
            <li><a href="https://t.me/playfiver">Telegram</a></li>
            <li><a href="#">WhatsApp</a></li>
            <li><a href="#">Termos de Serviço</a></li>
          </ul>
        </div>
        <div class="col">
          <h5>Mantenha-se atualizado</h5>
          <input type="text" placeholder="Insira o seu e-mail">
        </div>
      </div>
    </div>
  </footer>
 
</template>

<style scoped>

.colContent {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.colContent p{
  margin: 0;
}

.colIcon {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
  padding-right: 20px;
}

.bodyClientes .colItems .col {
  display: flex;

}

.bodyClientes .colItems .row {
  display: flex;
  flex-wrap: wrap;
}

.colIcon i{
  font-size: 30px;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
  height: 50px;
  width: 50px;
}

.logo2 {
  display: block;
  margin: 0 auto 2rem;
  height:250px;
  width: 250px;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}

.navTop {
  padding: 15px 250px;
  background-color: white !important;
  position: fixed;
  width: 100%;
  z-index: 1030; 
  -webkit-box-shadow: 0px 10px 5px -10px rgba(211, 211, 211, 0.75);
  -moz-box-shadow: 0px 10px 5px -10px rgba(211, 211, 211, 0.75);
  box-shadow: 0px 10px 5px -10px rgba(211, 211, 211, 0.75);
}

.bodyWelcome {
  background-color: #F2F5F6;
  padding: 100px 250px;
  margin-top: 80px;
}

.bodyWelcome p{
  margin: 25px 0 35px 0;
}

.bodyWelcome img{
  width: 80%;
}

.btnMain {
  background-color: #2593B4;
  display: block;
  max-width: 140px;
  align-items: center;
  color: white;
  padding: 10px 25px !important;
}

.icon {
  width: 20px;
  height: 20px;
  margin-left: 5px;
}

.navbar-nav .itemMenu {
    margin: 5px 10px !important;
    font-weight: 600;
}

.icon[data-v-7a7a37b1] {
  width: 15px;
  height: 20px;
  margin-left: 10px;
}

body {
  font-family: 'Inter', sans-serif;
  font-size: 20px;
}

p{
    font-size: 20px !important;
}

div.bodyWelcome h1.title1, h1.title2{
  font-size: 60px;
  font-weight: 500;
}

div.bodyWelcome h1.title1{
  color: dimgrey;
}

div.bodyWelcome h1.title2{
  color: #2593B4;
}

.bodyApresentacao{
  padding: 50px 250px;
}

.title{
  font-size:38px;
  font-weight: 600;
}

.subtitle{
  font-size:25px;
  font-weight: bold;
  margin: 14px 0;
}

.rowCards{
  margin: 60px 0;
}

.rowCards .col, .rowCards2 .col{
  min-width: 260px;
}

.cardCol{
  -webkit-box-shadow: 0px 10px 5px -10px rgba(211, 211, 211, 0.75);
  -moz-box-shadow: 0px 10px 5px -10px rgba(211, 211, 211, 0.75);
  box-shadow: 0px 10px 5px -10px rgba(211, 211, 211, 0.75);
  padding-bottom: 20px;
}

.col1{
  margin-right: 70px !important;
}

.col2{
  margin: 0 35px !important;
}

.col3{
  margin-left: 70px !important;
}

.footer {
  background-color: #217189;
  color: white;
  padding: 60px 250px;
  min-height: 300px;
}

.footer .container {
  margin: 0;
  padding: 0;
}

.footer .row {
  display: flex;
  justify-content: space-between;
}

.footer .col {
  flex: 1;
  padding: 0;
  margin-right: 20px;
}

.footer input{
  padding: 10px 14px;
  color: white;
  background-color: #4f899b;
  box-shadow: none !important;
  border: none !important;
  border-radius: 10px
}

.footer input::placeholder {
  color: white !important;
}

.footer h5 {
  font-size: 18px;
  margin-bottom: 15px;
  font-weight: bold;
}

.footer ul {
  list-style: none;
  padding: 0;
}

.footer ul li {
  margin-bottom: 10px;
}

.footer ul li a {
  color: white;
  text-decoration: none;
}

.footer ul li a:hover {
  text-decoration: underline;
}

.footer p, .footer a{
  font-size: 16px !important;
}

.social-icon{
  color: white;
  font-size: 20px !important;
  padding: 6px 10px;
  background-color: #4f899b;
  border-radius: 50%;
  margin-right: 10px;
  margin-bottom: 10px;
  width: 35px;
  display: inline-block;
}

.social-icon2{
  color: rgb(0, 0, 0);
  font-size: 30px !important;
  border-radius: 50%;
  margin-right: 10px;
  margin-bottom: 10px;
  width: 35px;
  display: inline-block;
}

.footer .container .col{
      height: 100% !important;
}

.colunaImagem, .colunaImagem2{
  display: flex;
  flex-direction: column; 
  justify-content: center;
}

.colunaImagem{
  text-align: right;
}

.colunaImagem2{
  text-align: left;
  display: block;
}

.colunaTexto{
  display: flex;
  flex-direction: column; 
  justify-content: center;
  padding-right:40px;
}

@media(max-width: 1900px){
  .bodyWelcome{
    padding: 85px 200px !important;
  }
  .bodyClientes{
    padding: 85px 200px !important;
  }
  .navTop{
    padding: 15px 200px; 
  }
  .bodyApresentacao{
    padding: 50px 200px !important;
  }
  .title1, .title2{
    font-size: 50px !important;
  }
  .title{
    font-size: 30px;
  }
  .subtitle{
    font-size: 25px;
  }
}

@media(max-width: 1500px){
  .bodyWelcome{
    padding: 85px 130px !important;
  }
  .bodyClientes{
    padding: 85px 130px !important;
  }
  .navTop{
    padding: 15px 130px; 
  }
  .footer{
    padding: 60px 130px !important;
  }
  .bodyApresentacao{
    padding: 50px 130px !important;
  }
  .bodyWelcome img{
    width: 100%;
  }
  .col1{
    margin-right: 50px !important;
  }

  .col2{
    margin: 0 25px !important;
  }

  .col3{
    margin-left: 50px !important;
  }

  .title1, .title2{
    font-size: 45px !important;
  }
}

@media(max-width: 1000px){
  .colunaImagem {
    width: 400px;
    text-align: center;
    margin: auto;
    display: block;
    margin-top: 20px;
  }

  .footer{
    padding: 60px 70px !important;
  }

  .colunaTexto{
    padding-right: 0 !important;
    min-width: 100% !important;
  }

  .cardCol {
    min-width: 350px !important;
    margin-bottom: 40px !important;
  }
  .bodyWelcome{
    padding: 85px 110px !important;
  }
  .bodyClientes{
    padding: 85px 60px !important;
  }
  .navTop{
    padding: 15px 110px; 
  }
  .bodyApresentacao{
    padding: 50px 60px !important;
  }
  .col1{
    margin-right: 0 !important;
  }
  .col2{
    margin: 0 0 40px 0 !important;
  }
  .col3{
    margin-left: 0 !important;
    margin-bottom: 0 !important;
  }
  .colunaImagem2{
    min-width: 100% !important;
    text-align: center !important;
    margin-bottom: 50px;

  }
  .imageApresentacao{
    width: 60%;
  }
  .imageApresentacao2{
    width: 60%;
  }
  .cardCol{
    min-width: 100% !important;
  }
}

@media(max-width: 500px){
   .bodyWelcome{
    padding: 60px !important;
  }

  .bodyClientes{
    padding: 60px !important;
  }
  .navTop{
    padding: 15px 60px; 
  }
}

@media(max-width: 800px){
  .colLogo{
    display: none
  }
  .colItems{
    min-width: 300px;
    margin-top: 40px;
  }
  .colTexto{
    min-width: 200px;
  }

  .colItems .col{
    min-width: 100px;
  }

}

.container {  
    display: grid;  
    grid-template-columns: 1fr 1fr 1fr;  
    grid-template-rows: 50px 50px;  
}

.imageApresentacao{
  width: 80%;
}

.imageApresentacao2{
  width: 50%;
}

.logo{
  margin: 0 !important;
}

.bodyClientes{
  background-color: #F2F5F6;
  padding: 85px 250px;
}

</style>