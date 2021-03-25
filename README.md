# quem---esse--pokemon
Quem é esse pokemon projeto da imersão alura dia 2 
https://codepen.io/chritianegozza/pen/YzNXpaq?editors=1100

<html>

<head>
  <title>
    Imersão Dev - Aula 02
  </title>
</head>

<body>
  <div class="container">
    <h1 class="page-title">
      Quem é esse Pokemmon ?
    </h1>
    <img src="https://www.alura.com.br/assets/img/imersoes/dev-2021/logo-imersao-calculadora.svg" class="page-logo" alt="">
    <div class="calculadora">
    </div>
  </div>
  <a href="https://alura.com.br/" target="_blank">
    <img src="https://www.alura.com.br/assets/img/home/alura-logo.svg" alt="" class="alura-logo">
  </a>
  <h2></h2>
</body>

</html>


css

body {
  font-family: "Roboto Mono", monospace;
  min-height: 500px;
  background-image: url("https://staticr1.blastingcdn.com/media/photogallery/2017/8/30/660x290/b_502x220/o-anime-pokemon-seria-coisa-do-demonio_1539703.jpg");
  background-color: #0288d1;
  background-size: 150vh;
  background-position: center bottom;
  background-repeat: no-repeat;
}

.container {
  text-align: center;
  padding: 20px;
  height: 100vh;
}

.page-title {
  color: rgb(255, 212, 22);
  margin: 0 0 5px;
}

.page-subtitle {
  color: rgb(255, 212, 22);
  margin-top: 10px;
}

.page.logo {
  width: 200px;
}

.Pokebola {
  width: 100px;
  height: 100px;

  background-image: url("https://pbs.twimg.com/profile_images/1155697286078296069/muxy-u6y.jpg");
  background-size: 100% 100%;
  background-repeat: no-repeat;
  border: solid 1px;
  box-shadow: 10px 10px 10px 2px white;
}

h2 {
  position: absolute;
  font-size: 16px;
  font-weight: bold;
  top: 142px;
  left: calc(50% - 72.5px);
  width: 145px;
  text-align: center;
}

.alura-logo {
  width: 40px;
  position: absolute;
  top: 10px;
  right: 10px;
}


js

/window.alert("Diga quem é esse Pokemon? ")/ /
  window.confirm("Digite o nome do Pokemon"); //janela com botão ok e cancela
var nome = window.prompt("Digite o nome do Pokemon amigo do Ash"); //vai perguntar o nome...
window.alert("Isso mesmo você acertou, " + nome);

//var nome = window.alert("Isso mesmo você acertou" + "Squirtle"); //
//var nome = window.alert("Isso mesmo você acertou" + "Pikacu");
//var nome = window.alert("Isso mesmo você acertou" + "bubasauro");
