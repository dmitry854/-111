<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <link
      href="https://fonts.googleapis.com/css2?family=Marck+Script&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="stule.css" />
  </head>
  <body>
    <div class="header">
      <a href="#bottom"><h1 class="title">Попробуйте наше кофе</h1></a>
    </div>
    <a name="bottom"></a>
    <div class="menu">
      <div class="item">
        <div class="picture">
          <img
            src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/16/Classic_Cappuccino.jpg/411px-Classic_Cappuccino.jpg"
          />
        </div>
        <div class="info">
          <h3>Капучино</h3>
          Классический итальянский напиток готовится по следующему рецепту: в
          керамическую чашку из кофемашины наливается одна порция эспрессо,
          после чего в чашку вливается подогретое и вспененное паром молоко.
        </div>
      </div>
      <div class="item">
        <div class="picture">
          <img src="https://www.coffeeproject.ru/images/blog/124/4.jpg" />
        </div>
        <div class="info">
          <h3>Американо</h3>
          Американо готовится из одной или двух порций эспрессо, в который
          добавляется от 30 до 470 мл горячей воды. В процессе приготовления
          горячую воду можно брать как из эспрессо-машины, так и из отдельного
          чайника или подогревателя.
        </div>
      </div>
      <div class="item">
        <div class="picture">
          <img
            src="https://kofella.net/images/stories/vseokofe/frappuchino-1.jpg"
          />
          
        </div>
        <div class="info">
          <h3>Фраппучино</h3>
          Впервые напиток под таким названием начал продаваться в сети кофеен
          The Coffee Connection в штате Массачусетс.
        </div>
      </div>
    </div>
  </body>
</html>
.header {
  width: 100%;
  height: 100vh;
  background-size: cover;
  background-image: url(./img/фон.jpg);
}
h1 {
  text-align: center;
  padding-top: 200px;
  font-family: "Marck Script", cursive;
  color: rgb(255, 251, 0);
  margin: 0%;
}
body {
  margin: 0%;
}

.picture {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  overflow: hidden;
  margin: auto;
}
img {
  height: 100%;
}
.menu {
  background-color: rgb(201, 170, 84);
  width: 100%;
  margin: auto;
  padding-top: 10px;
  height: 100vh;
}
.item {
  width: 50%;
  margin: 10px auto;
  text-align: center;
  border-bottom: 2px rgb(150, 87, 45) solid;
  padding: 10px;
}
a {
  text-decoration: none;
}
