<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="shortcut icon" href="IMAGEN.jpg">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KK94CHFLLe+nY2dmCWGMq91rCGa5gtU4mk92HdvYe+M/SXH301p5ILy+dN9+nJOZ" crossorigin="anonymous">
    <link rel="stylesheet" href="formulario.css">
    <title>Iconic Attire</title>
  </head>
  <body>
    <center>
      <form action="Gracias.html">
<br>
<style>
  /* Añadir estilo al cuerpo del formulario */
body {
  font-family: Optima;
  background: linear-gradient(to bottom right, #e15f6a, #cca4f9, #77c5d5);
  font-size: 27px;
  color: #444444;
  height: -500px;
  margin: 0;

}

/* Estilo para el título del formulario */
h1 {
  font-size: 36px;
  color: #000000;
}

/* Añadir estilo a las preguntas del formulario */
.check {
  border: 1px solid #1E90FF;
  padding: 20px;
  margin-bottom: 20px;
  border-radius: 15px;
}

/* Estilo para las etiquetas de radio */
.check-label {
  font-size: 29px;
  color: #1E90FF;
  font-family: sans-serif;
}

/* Estilo para los botones de radio */
.check-input {
  margin-right: 10px;
}

  /* Estilos para el botón "Enviar" */
  input[type="submit"] {
    display: inline-block;
    background-color: #ec6ec9;
    color: white;
    padding: 20px 30px;
    margin: 20px 0;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 16px;
    transition: background-color 0.3s ease;
  }

    /* Animaciones para el botón "Enviar" */
    input[type="submit"] {
      animation-name: pulse;
      animation-duration: 1s;
      animation-iteration-count: infinite;
    }
    
    @keyframes pulse {
      0% {
        transform: scale(1);
      }
       50% {
        transform: scale(1.2);
      }
      100% {
        transform: scale(1);
      }
    }

/* Estilo para la imagen */
img {
  border: 5px solid #30b9e6;
  border-radius: 15px;
} 

/* Añadir estilo al formulario */
form {
  max-width: 700px;
  margin: auto;
  background-color: #ffffff;
  padding: 20px;
  border-radius: 15px;
  box-shadow: 0px 0px 15px #1E90FF;
}
</style>
<h1>FORMULARIO</h1>
        <img img src="IMAGEN.jpg" height="200px" width="500px"><br><br>

       <div class="check">
         <label class="check-label" for="flexRadioDefault1" name="pregunta1" value="50">1. ¿Prefieres ropa cómoda o elegante?</label>
         <div> <input  class="check-input" type="radio" name="pregunta1" id="lexRadioDefault1" value="1"/>Comodidad</div>
         <div> <input class="check-input" type="radio" name="pregunta1" id="flexRadioDefault1" value="2"/>Elegancia</div>
         <div> <input class="check-input" type="radio" name="pregunta1" id="flexRadioDefault1" value="3"/>Depende de la ocasión</div>
         <div> <input class="check-input" type="radio" name="pregunta1" id="flexRadioDefault1" value="4"/>Me gusta combinar ambos estilos</div>
       </div><br>

       <div class="check">
         <label class="check-label" for="flexRadioDefault1" name="pregunta2" value="50">2. ¿Te gusta la ropa con estampados o preferirías prendas de un solo color?</label>
         <div> <input  class="check-input" type="radio" name="pregunta2" id="lexRadioDefault1" value="5"/>Estampados</div>
         <div> <input class="check-input" type="radio" name="pregunta2" id="flexRadioDefault1" value="6"/>Un solo color</div>
         <div> <input class="check-input" type="radio" name="pregunta2" id="flexRadioDefault1" value="7"/>Me gustan ambas opciones</div>
         <div> <input class="check-input" type="radio" name="pregunta2" id="flexRadioDefault1" value="8"/>Depende del tipo de prenda</div>
       </div><br>
       <div class="check">
         <label class="check-label" for="flexRadioDefault1" name="pregunta3" value="50">3. ¿Sueles comprar ropa de temporada o prendas que puedas usar en cualquier época del año?</label>
         <div> <input  class="check-input" type="radio" name="pregunta3" id="lexRadioDefault1" value="9"/>De temporada</div>
         <div> <input class="check-input" type="radio" name="pregunta3" id="flexRadioDefault1" value="10"/>Todo el año</div>
         <div> <input class="check-input" type="radio" name="pregunta3" id="flexRadioDefault1" value="11"/>Depende de mi presupuesto</div>
         <div> <input class="check-input" type="radio" name="pregunta3" id="flexRadioDefault1" value="12"/>Me gusta comprar prendas que puedan ser usadas en cualquier época del año</div>
       </div><br>
       <div class="check">
         <label class="check-label" for="flexRadioDefault1" name="pregunta4" value="50">4. ¿Te gusta la ropa holgada o ajustada al cuerpo?</label>
         <div> <input  class="check-input" type="radio" name="pregunta4" id="lexRadioDefault1" value="13"/>Holgada</div>
         <div> <input class="check-input" type="radio" name="pregunta4" id="flexRadioDefault1" value="14"/>Ajustada</div>
         <div> <input class="check-input" type="radio" name="pregunta4" id="flexRadioDefault1" value="15"/>Depende del tipo de prenda</div>
       </div><br>
       <div class="check">
         <label class="check-label" for="flexRadioDefault1" name="pregunta5" value="50">5. ¿Prefieres telas suaves o texturas más gruesas y rígidas?</label>
         <div> <input  class="check-input" type="radio" name="pregunta5" id="lexRadioDefault1" value="16"/>Suaves</div>
         <div> <input class="check-input" type="radio" name="pregunta5" id="flexRadioDefault1" value="18"/>Gruesas y rígidas</div>
         <div> <input class="check-input" type="radio" name="pregunta5" id="flexRadioDefault1" value="18"/>Depende del tipo de prenda</div>
       </div><br>
       <div class="check">
         <label class="check-label" for="flexRadioDefault1" name="pregunta6" value="50">6. ¿Te gusta la ropa clásica o prefieres seguir las últimas tendencias?</label>
         <div> <input  class="check-input" type="radio" name="pregunta6" id="lexRadioDefault1" value="19"/>Clásica</div>
         <div> <input class="check-input" type="radio" name="pregunta6" id="flexRadioDefault1" value="20"/>Últimas tendencias</div>
         <div> <input class="check-input" type="radio" name="pregunta6" id="flexRadioDefault1" value="21"/>Me gusta ambas opciones</div>
       </div><br>
       <div class="check">
         <label class="check-label" for="flexRadioDefault1" name="pregunta7" value="50">7. ¿Te interesa la ropa con diseños divertidos y creativos o prefieres un estilo más sobrio?</label>
         <div> <input  class="check-input" type="radio" name="pregunta7" id="lexRadioDefault1" value="22"/>Divertidos y creativos</div>
         <div> <input class="check-input" type="radio" name="pregunta7" id="flexRadioDefault1" value="23"/>Sobrio</div>
         <div> <input class="check-input" type="radio" name="pregunta7" id="flexRadioDefault1" value="24"/>Me gusta ambas opciones</div>
       </div><br>
       <div class="check">
         <label class="check-label" for="flexRadioDefault1" name="pregunta8" value="50">8. ¿Prefieres comprar ropa en línea o en tiendas físicas?</label>
         <div> <input  class="check-input" type="radio" name="pregunta8" id="lexRadioDefault1" value="25"/>En línea</div>
         <div> <input class="check-input" type="radio" name="pregunta8" id="flexRadioDefault1" value="26"/>En tiendas físicas</div>
         <div> <input class="check-input" type="radio" name="pregunta8" id="flexRadioDefault1" value="27"/>En ambas</div>
       </div><br>
       <div class="check">
         <label class="check-label" for="flexRadioDefault1" name="pregunta9" value="50">9. ¿Te gustaría personalizar tus prendas con detalles especiales?</label>
         <div> <input  class="check-input" type="radio" name="pregunta9" id="lexRadioDefault1" value="28"/>Sí</div>
         <div> <input class="check-input" type="radio" name="pregunta9" id="flexRadioDefault1" value="29"/>No</div>
         <div> <input class="check-input" type="radio" name="pregunta9" id="flexRadioDefault1" value="30"/>Tal vez</div>
       </div><br>
       <div class="check">
         <label class="check-label" for="flexRadioDefault1" name="pregunta10" value="50">10. ¿Prefieres marcas reconocidas o estás dispuesto/a a probar nuevas marcas?</label>
         <div> <input  class="check-input" type="radio" name="pregunta10" id="lexRadioDefault1" value="31"/>Marcas reconocidas</div>
         <div> <input class="check-input" type="radio" name="pregunta10" id="flexRadioDefault1" value="32"/>Nuevas marcas</div>
         <div> <input class="check-input" type="radio" name="pregunta10" id="flexRadioDefault1" value="33"/>No hay preferencia alguna</div>
       </div><br>

        <input type="submit" value="Enviar"><br>
      </form>
     </center>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ENjdO4Dr2bkBIFxQpeoTz1HIcje39Wm4jDKdf19U8gI4ddQ3GYNS7NTKfAdVQSZe" crossorigin="anonymous"></script>
  </body>
</html>
