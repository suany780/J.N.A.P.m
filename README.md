<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UR-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>J.N.A.P.</title>
    <link rel="stylesheet" href="estilos.css">
</head>
<body>
    <h1>
        ♥FELIZ <span>CUMPLEAÑOS</span>♥
             T.Q.M
        
    </h1>
    <div class="cards-grid">
        <div class="flip-card">
            <div class="flip-card-inner">
                <div class="flip-card-front" style="background-image: url('blanco.jpg');">

                </div>
                <div class="flip-card-back">
                    Hola ♥
            Feliz Cumpleaños, Jongel.♥
        Dime, cómo te explico que yo estoy más feliz que tú hoy? que en verdadd estoy agradecida,
        no importa el que viniste hacer a mi vida si sea malo o bueno solo se que te quiero en ella, 
        me importas y lo sabes, pero jamás tendras idea de cuanto me importas.
                </div>
            </div>
        </div>

        <div class="flip-card">
            <div class="flip-card-inner">
                <div class="flip-card-front" style="background-image: url('jn.jpg');">

                </div>
                <div class="flip-card-back">
            Aun recuerdo la primera vez que te llene la cara de besos y  también recuerdo como me mirabas en 4to y como yo el último dia me digne a querer saber tu
            nombre y lo supe 5to grado "Jongel" que curiodo ese dia me lo repeti varias veces para que no se me olvidará
            porque la curiosidad de la primera vez que te vi ya la queria pasar al otro nivel, pero entonces me sonreiste 
            de la manera más linda y mi sentimiento se despertaron y no los pude controlar.♥
                </div>
            </div>
        </div>

        <div class="flip-card">
            <div class="flip-card-inner">
                <div class="flip-card-front" style="background-image: url('corazon.jpg');">

                </div>
                <div class="flip-card-back">
                Si te digo que TE QUIERO eso esta demás porque sabes todo lo que siento por ti, pero si te digo enserio
                que me gustaria verte triunfar, verte logras tu metas, estar ahí cuando estes mal y quedarme viendo como 
                te vuelves un HOMBRE que se vale por sí mismo y no por mi sino por ti porque decidiste mejorar y
                ver la vida de otra manera, así que, Espero y disfrutes tú dia.♥
                </div>
            </div>
        </div>
    </div>
</body>
</html>


/*
    ** All elements border-box
*/
*,
*:before,
*::after {
  box-sizing: border-box;
}

/*
    ** Root element font size
    ** No default margins and paddings
*/
html,
body {
  font-size: 16px;
  margin: 0;
  padding: 0;
}

/*
    **root elements display block
*/
html,
body {
  display: block;
}

/*
    ** Body main style
*/
body {
  line-height: 1.317101995;
  scroll-behavior: smooth;
  font-family: sans-serif;
  background-color: #ffffff;
}

button:focus {
  outline: 0;
}

img,
embed,
svg,
audio,
canvas,
iframe,
video {
  max-width: 100%;
  height: auto;
  vertical-align: middle;
}

hr {
  height: 0;
  border: 0;
  border-bottom: 1px solid #dfdfdf;
  margin: 0;
}

body {
  color: #5c7470;
  width: 100%;
  height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 32px 0;
}

h1 {
  font-size: 4rem;
  margin-top: 0;
  margin-bottom: 80px;
}

h1 span {
  color: #17B6D2;
}

p {
  margin: 0;
}

.cards-grid {
  display: flex;
  grid-gap: 80px;
  padding-bottom: 60px;
}

/* FLIP CARD */
.flip-card {
  width: 320px;
  height: 504px;
  perspective: 2000px;
}
.flip-card-inner {
  position: relative;
  width: 100%;
  height: 100%;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
  border-radius: 28px;
  transition: all 550ms cubic-bezier(0.1, 0.22, 0.8, 1.13);
  transform-style: preserve-3d;
}
.flip-card-front, .flip-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  border-radius: 28px;
  backface-visibility: hidden;
}
.flip-card-front {
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
.flip-card-back {
  font-size: 1.25rem;
  text-align: center;
  display: grid;
  place-items: center;
  padding: 32px;
  background-color: #B1CFC8;
  transform: rotateY(180deg);
}
.flip-card:hover .flip-card-inner {
  transform: rotateY(-180deg);
}

