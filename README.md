<!doctype html>
<html>
  <head>
      <title>Форма</title>
      <meta charset="utf-8">
	  <link rel="stylesheet" href="App1.css">
  </head>
  <body>
      <div class="forma">
          <h3 class="font">me contacter</h3>
          <form  id="data" action="Personal data" method="post">
              <div form="data">
                  <label class="formcoloricon" for="fname"><img src="images/iconuser.png" alt=""></label>
                  <input class="forminput" id="fname" type="text" name="Имя" placeholder="Votre nom">
                  <label class="formcoloricon" for="femail"><img src="images/iconemail.png" alt=""></label>
                  <input class="forminput" id="femail" type="email" name="Електронный ящик" placeholder="Votre email">
              </div><br>
              <div form="data">
                  <label class="massageicon" for="femail"><img class="forimage" src="images/icontextarea.png" alt=""></label>
                  <textarea class="txtarea" name="Сообщение" placeholder="Votre message"></textarea>
              </div>
          </form><br>
          <div>
              <input class="button" type="submit" form="data" name="Отправить" value="envoyer">
          </div>
      </div><br><br>
          <div class="link">
              <a class="a" href="Table.html">Таблица</a>
          </div>
  </body>
</html>
