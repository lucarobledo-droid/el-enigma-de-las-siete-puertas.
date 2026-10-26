
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>El enigma de las siete puertas</title>
<style>
:root {
  --fondo: #100e12;
  --panel: #1b171b;
  --oro: #d8b46a;
  --texto: #eee7da;
  --suave: #b7a995;
}
* { box-sizing: border-box; }
html { scroll-behavior: smooth; }
body {
  margin: 0;
  background: var(--fondo);
  color: var(--texto);
  font-family: Georgia, "Times New Roman", serif;
  line-height: 1.85;
}
.portada {
  min-height: 78vh;
  padding: 70px 22px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  background:
    radial-gradient(ellipse at center, #49321e 0%, #211711 36%, #100e12 75%);
  border-bottom: 1px solid #66502c;
}
.simbolo {
  font-size: 58px;
  color: var(--oro);
  margin-bottom: 10px;
}
.etiqueta {
  color: var(--oro);
  letter-spacing: 5px;
  font: 12px Arial, sans-serif;
  text-transform: uppercase;
}
h1 {
  color: var(--oro);
  font-size: clamp(36px, 8vw, 66px);
  line-height: 1.15;
  max-width: 850px;
  margin: 22px auto;
  text-shadow: 0 3px 25px #000;
}
.subtitulo {
  color: var(--suave);
  font-style: italic;
  font-size: 19px;
}
button, .boton {
  background: var(--oro);
  color: #17120b;
  border: none;
  padding: 13px 20px;
  border-radius: 4px;
  font-weight: bold;
  cursor: pointer;
  text-decoration: none;
  font-family: Arial, sans-serif;
}
.portada button { margin-top: 30px; }
.contenedor {
  max-width: 850px;
  padding: 35px 23px 90px;
  margin: auto;
}
.aviso {
  border-left: 3px solid var(--oro);
  padding: 12px 18px;
  background: var(--panel);
  color: var(--suave);
  font-style: italic;
}
h2 {
  color: var(--oro);
  font-size: 29px;
  line-height: 1.35;
  margin-top: 55px;
}
h3 {
  color: var(--oro);
  font-size: 21px;
}
p { margin: 20px 0; }
.indice {
  background: var(--panel);
  padding: 23px;
  border: 1px solid #423629;
  border-radius: 6px;
}
.indice a {
  display: block;
  color: var(--texto);
  text-decoration: none;
  padding: 8px 0;
  border-bottom: 1px solid #342c28;
}
.indice a:hover { color: var(--oro); }
.capitulo {
  padding-top: 12px;
  border-top: 1px solid #463826;
}
.inicio {
  display: block;
  margin-top: 24px;
  color: var(--oro);
  font: 12px Arial, sans-serif;
  text-decoration: none;
}
.final {
  text-align: center;
  color: var(--oro);
  padding: 35px 0;
  font-style: italic;
}
footer {
  text-align: center;
  color: #8f8271;
  padding: 30px 15px;
  border-top: 1px solid #342b22;
  font-size: 13px;
}
@media (max-width: 500px) {
  .contenedor { padding: 25px 19px 60px; }
  h2 { font-size: 25px; }
}
</style>
</head>
<body>

<header class="portada" id="inicio">
  <div class="simbolo">✦</div>
  <div class="etiqueta">Una novela de misterio</div>
  <h1>EL ENIGMA DE<br>LAS SIETE PUERTAS</h1>
  <p class="subtitulo">Siete puertas. Siete secretos. Una verdad imposible.</p>
  <p>Algunas puertas están cerradas para protegerte.<br>Otras, para impedir que algo escape.</p>
  <button onclick="document.getElementById('libro').scrollIntoView({behavior:'smooth'})">
    ABRIR EL LIBRO
  </button>
</header>

<main class="contenedor" id="libro">

<section class="indice">
<h2 style="margin-top:0">Índice</h2>
<a href="#cap1">Capítulo I — La carta sin remitente</a>
<a href="#cap2">Capítulo II — La casa que no aparecía en los mapas</a>
<a href="#cap3">Capítulo III — La primera puerta</a>
<a href="#cap4">Capítulo IV — El pueblo de los desaparecidos</a>
<a href="#cap5">Capítulo V — La habitación de los relojes</a>
<a href="#cap6">Capítulo VI — El precio de recordar</a>
<a href="#cap7">Capítulo VII — La puerta de las sombras</a>
<a href="#cap8">Capítulo VIII — El guardián</a>
<a href="#cap9">Capítulo IX — La verdad bajo el castillo</a>
<a href="#cap10">Capítulo X — La séptima puerta</a>
<a href="#cap11">Capítulo XI — Lo que regresó</a>
<a href="#cap12">Capítulo XII — El último secreto</a>
</section>

<p class="aviso">Prólogo. Hay lugares que no figuran en ningún mapa. No porque estén escondidos, sino porque el mundo ha aprendido a olvidar que existen.</p>

<section class="capitulo" id="cap1">
<h2>CAPÍTULO I<br>La carta sin remitente</h2>

<p>La noche en que Daniel recibió la carta, todos los relojes de su casa se detuvieron a las 23:17.</p>

<p>No ocurrió de golpe. Primero se paró el reloj de la cocina. Después, el de la entrada. Finalmente, el pequeño reloj que su abuelo le había regalado cuando cumplió diez años dejó de hacer tic-tac. Daniel levantó la vista de su libro y escuchó un silencio tan profundo que incluso la lluvia pareció desaparecer.</p>

<p>Entonces llamaron a la puerta.</p>

<p>Tres golpes. Lentos. Espaciados.</p>

<p>Daniel vivía con su madre en una casa antigua, a las afueras de un pueblo del norte. Su madre trabajaba de noche en el hospital y aquella tarde le había pedido que no abriera a nadie. Aun así, se acercó al recibidor.</p>

<p>—¿Quién es?</p>

<p>Nadie contestó.</p>

<p>Abrió solo unos centímetros. En el suelo había un sobre negro. No había nadie en el porche ni en el camino. La lluvia caía sobre la grava sin dejar huellas, como si quien hubiera entregado la carta hubiese llegado volando.</p>

<p>En el sobre aparecía su nombre escrito con una caligrafía antigua: <em>Daniel Valera</em>.</p>

<p>Dentro encontró una llave negra, fría como el hielo, y una hoja doblada en cuatro.</p>

<p>«Daniel:</p>

<p>Si esta carta ha llegado hasta ti, significa que el sello se ha roto. No confíes en los relojes. No sigas las voces que conozcas. Y, sobre todo, no abras la séptima puerta hasta saber quién eres realmente.</p>

<p>Tu abuelo no murió como te contaron.</p>

<p>Ve al lugar donde termina el camino del bosque. Lleva la llave. Ve antes de la medianoche del viernes.</p>

<p>Si no lo haces, ellos vendrán a buscarte.</p>

<p>Perdóname por haberte dejado esta carga.</p>

<p>—A.»</p>

<p>Daniel leyó la carta cuatro veces. Su abuelo había muerto cuando él tenía seis años. Apenas conservaba recuerdos de él: unas manos enormes, olor a madera y una voz grave que le contaba historias sobre un castillo con siete puertas.</p>

<p>Su madre siempre había dicho que aquellas historias eran inventadas.</p>

<p>Al girar la hoja descubrió una frase escrita con tinta roja: «La primera puerta ya sabe tu nombre».</p>

<p>En ese instante, desde el piso de arriba, alguien susurró:</p>

<p>—Daniel...</p>

<p>Era la voz de su abuelo.</p>

<p>Daniel retrocedió. La casa estaba vacía. Su madre no regresaría hasta la mañana y él no había oído abrirse ninguna puerta.</p>

<p>—¿Abuelo?</p>

<p>Un golpe retumbó en el techo.</p>

<p>Después otro.</p>

<p>Y otro.</p>

<p>Como pasos que avanzaban lentamente hacia la escalera.</p>

<p>Daniel guardó la llave en el bolsillo y salió a la lluvia sin coger el abrigo. Mientras corría hacia el pueblo, miró el reloj de la plaza. Marcaba las 23:17.</p>

<p>Todos los relojes seguían detenidos.</p>

<p>Y, al otro lado del bosque, una luz acababa de encenderse en una ventana que llevaba cien años tapiada.</p>
<a class="inicio" href="#inicio">↑ Volver a la portada</a>
</section>

<section class="capitulo" id="cap2">
<h2>CAPÍTULO II<br>La casa que no aparecía en los mapas</h2>

<p>Daniel esperó hasta la tarde siguiente para contarle lo ocurrido a su mejor amiga, Clara. No se lo dijo por teléfono. Había algo en la carta que le hacía desconfiar de cualquier aparato electrónico.</p>

<p>Quedaron junto al puente viejo, donde el río se estrechaba entre dos paredes de piedra.</p>

<p>Clara escuchó la historia sin interrumpirlo. Cuando Daniel terminó, ella no se rio ni le dijo que estaba imaginando cosas. Eso fue lo que más le preocupó.</p>

<p>—Mi padre tiene una fotografía —dijo ella—. De tu abuelo. La encontró entre las cosas de mi bisabuela.</p>

<p>Sacó el móvil y le enseñó una imagen escaneada. En ella aparecían siete personas frente a una construcción de piedra. Seis miraban a la cámara. La séptima estaba de espaldas, con una mano apoyada sobre una puerta enorme.</p>

<p>Daniel reconoció a su abuelo inmediatamente. Era joven, quizá de veinte años. Pero había algo imposible: la fotografía tenía una fecha impresa en una esquina. 1891.</p>

<p>Su abuelo había nacido casi un siglo después.</p>

<p>—¿Quién te ha dado esto? —preguntó Daniel.</p>

<p>—Mi padre. Y me hizo prometer que nunca iría al bosque después de anochecer.</p>

<p>—¿Por qué?</p>

<p>Clara guardó el móvil.</p>

<p>—Porque mi bisabuela desapareció allí. Y porque, antes de desaparecer, dejó escrito que había siete puertas y que una de ellas podía devolver a los muertos.</p>

<p>Aquella noche buscaron mapas antiguos en la biblioteca municipal. Revisaron atlas, archivos y periódicos amarillentos. No encontraron ningún castillo, pero sí una noticia de 1924 sobre la desaparición de nueve habitantes de la comarca. El artículo terminaba con una frase extraña: «La policía descarta cualquier relación entre los hechos y la finca de Valdemora, cuya existencia no ha podido confirmar».</p>

<p>Debajo de la noticia había una fotografía borrosa de un camino que terminaba ante un muro.</p>

<p>Daniel reconoció la curva del río, los árboles torcidos y una piedra partida en dos. Era el camino que conducía al bosque detrás de su casa.</p>

<p>El viernes llegó con un cielo sin estrellas. A las once, Daniel y Clara cruzaron la verja oxidada que nadie recordaba haber visto abierta.</p>

<p>Caminaron durante cuarenta minutos. El sendero descendió entre árboles cada vez más altos hasta que el bosque terminó de repente.</p>

<p>Frente a ellos se alzaba un castillo negro, enorme, con siete puertas alineadas en su fachada. No tenía ventanas iluminadas ni humo en las chimeneas. Parecía llevar siglos abandonado.</p>

<p>Clara levantó una linterna.</p>

<p>—Daniel... mira el suelo.</p>

<p>En el barro había dos filas de huellas. Unas iban hacia el castillo. Las otras regresaban hacia el bosque.</p>

<p>Las de regreso eran de Daniel y Clara.</p>

<p>Las de ida eran de ellos también.</p>

<p>Pero las huellas de ida eran mucho más pequeñas, como si hubieran sido hechas por dos niños.</p>

<p>Y al final del camino, junto a la entrada, alguien había escrito con piedras: «Llegáis cien años tarde».</p>
<a class="inicio" href="#inicio">↑ Volver a la portada</a>
</section>

<section class="capitulo" id="cap3">
<h2>CAPÍTULO III<br>La primera puerta</h2>

<p>Las siete puertas eran distintas. La primera estaba hecha de madera oscura y tenía un ojo tallado en el centro. La segunda parecía de hierro. La tercera estaba cubierta de espejos. La cuarta era blanca, sin cerradura. La quinta tenía cientos de nombres grabados. La sexta estaba hecha de piedra.</p>

<p>La séptima no parecía una puerta. Era una superficie negra, lisa, sin bisagras ni marco, como un agujero recortado en la realidad.</p>

<p>La llave de Daniel empezó a calentarse al acercarse a la primera.</p>

<p>—Quizá deberíamos volver —dijo Clara.</p>

<p>—Podemos hacerlo. Pero la carta dice que mi abuelo no murió como me contaron.</p>

<p>Introdujo la llave en una cerradura que un segundo antes no estaba allí.</p>

<p>La puerta se abrió hacia dentro.</p>

<p>Al otro lado no había una habitación, sino la cocina de la casa de Daniel. Su madre estaba sentada a la mesa, mucho más joven de lo que él la recordaba. Frente a ella había un niño de seis años.</p>

<p>El niño era Daniel.</p>

<p>—No puede ser —susurró Clara.</p>

<p>El pequeño Daniel lloraba. Su madre le acariciaba el pelo mientras un anciano de ojos grises colocaba una llave sobre la mesa.</p>

<p>—Cuando crezca, vendrá a buscarme —dijo el anciano.</p>

<p>—No puedes pedirle eso —respondió la madre—. Es solo un niño.</p>

<p>—No se lo pediré. Él elegirá.</p>

<p>Daniel reconoció la voz de su abuelo. Pero había algo más: el anciano llevaba en la muñeca una pulsera de hilo rojo, idéntica a la que Daniel tenía desde pequeño.</p>

<p>La escena cambió. Su madre empezó a llorar. El anciano se inclinó hacia el niño y le susurró algo que Daniel no logró escuchar.</p>

<p>Entonces el pequeño levantó la cabeza y miró directamente hacia la puerta, hacia Daniel.</p>

<p>—Ya has tardado bastante —dijo el niño.</p>

<p>La visión se rompió como un cristal. La cocina desapareció y la habitación quedó a oscuras.</p>

<p>Clara agarró a Daniel del brazo.</p>

<p>—¿Lo has visto? ¡Ese eras tú!</p>

<p>Daniel no respondió. Había algo escrito en la pared de la habitación, letras que brillaban tenuemente.</p>

<p>«LA MEMORIA ES UNA PUERTA. CADA VEZ QUE LA ABRES, ALGO TE RECUERDA A TI».</p>

<p>En el suelo había una pequeña caja. Dentro encontraron una fotografía de la misma cocina, pero tomada muchos años antes. En la parte trasera alguien había escrito siete iniciales.</p>

<p>A. V. — E. M. — R. S. — C. D. — J. P. — M. L. — D. V.</p>

<p>La última correspondía a Daniel Valera.</p>

<p>Debajo, una frase: «Uno de ellos nunca nació».</p>

<p>Cuando salieron de la habitación, la primera puerta se cerró a sus espaldas.</p>

<p>Y desde el otro lado, una voz infantil empezó a contar hacia atrás.</p>

<p>—Siete... seis... cinco...</p>

<p>Daniel y Clara echaron a correr por el pasillo.</p>
<a class="inicio" href="#inicio">↑ Volver a la portada</a>
</section>

<section class="capitulo" id="cap4">
<h2>CAPÍTULO IV<br>El pueblo de los desaparecidos</h2>

<p>La segunda puerta se abrió sin necesidad de llave. Tras ella se extendía una calle empedrada bajo una niebla espesa. Había casas, una iglesia y una plaza con una fuente seca. Todo parecía un pueblo real, pero las ventanas estaban oscuras y ninguna chimenea expulsaba humo.</p>

<p>Un cartel oxidado anunciaba el nombre del lugar: San Telmo.</p>

<p>—Ese pueblo no existe —dijo Clara—. Mi padre estudió todos los municipios de la provincia.</p>

<p>En la plaza había un periódico abandonado. La fecha era la del día siguiente. El titular decía: «Dos jóvenes desaparecen en el bosque de Valdemora».</p>

<p>Debajo aparecían sus fotografías.</p>

<p>Daniel sintió un escalofrío. Antes de que pudiera leer más, una campana sonó en la iglesia. Todas las puertas de las casas se abrieron al mismo tiempo.</p>

<p>Salieron personas de todas las edades. Un anciano con uniforme militar, una mujer con un vestido antiguo, un niño descalzo. Todos tenían la misma expresión vacía.</p>

<p>Y todos miraban a Daniel.</p>

<p>Una mujer se acercó. Tenía los ojos enrojecidos y un anillo con una piedra azul.</p>

<p>—¿Eres el nieto de Arturo?</p>

<p>Daniel asintió.</p>

<p>La mujer cerró los ojos, como si llevara años esperando aquella respuesta.</p>

<p>—Entonces todavía podemos arreglarlo.</p>

<p>Se presentó como Elena. Dijo que había vivido allí en 1924 y que el pueblo había quedado atrapado entre dos momentos del tiempo. Nadie podía marcharse porque todos habían entregado algo al castillo: un recuerdo, un nombre o una persona querida.</p>

<p>—¿Qué entregaste tú? —preguntó Clara.</p>

<p>Elena miró sus manos.</p>

<p>—A mi hijo.</p>

<p>La campana volvió a sonar. Los habitantes comenzaron a retirarse a sus casas.</p>

<p>—Escuchadme —dijo Elena con urgencia—. No confiéis en el guardián. Él os mostrará lo que queréis ver. Os dirá que puede devolveros a los muertos. Pero nadie regresa de verdad.</p>

<p>—¿Quién es el guardián? —preguntó Daniel.</p>

<p>Elena señaló la iglesia.</p>

<p>En lo alto de la torre había una figura inmóvil. Llevaba un abrigo negro y sostenía un reloj de bolsillo.</p>

<p>Cuando Daniel parpadeó, la figura había desaparecido.</p>

<p>Elena les entregó una moneda partida por la mitad.</p>

<p>—Cuando encontréis la habitación de los relojes, no dejéis que el vuestro marque las doce.</p>

<p>—¿Y si las marca?</p>

<p>La mujer comenzó a llorar.</p>

<p>—Entonces el castillo recordará que existís.</p>

<p>Las calles se deshicieron en niebla. La plaza desapareció y los dos jóvenes se encontraron otra vez ante las siete puertas.</p>

<p>La tercera puerta, cubierta de espejos, reflejaba a Daniel y Clara.</p>

<p>Pero en el reflejo había una tercera persona detrás de ellos.</p>

<p>Un hombre con el rostro de Daniel, envejecido, que levantó un dedo hasta sus labios para pedirles silencio.</p>
<a class="inicio" href="#inicio">↑ Volver a la portada</a>
</section>

<section class="capitulo" id="cap5">
<h2>CAPÍTULO V<br>La habitación de los relojes</h2>

<p>La tercera puerta no se abrió hacia una habitación, sino hacia un corredor infinito de espejos. Cada espejo mostraba una versión distinta de los dos jóvenes: Daniel con uniforme militar, Clara con el pelo completamente blanco, ambos convertidos en ancianos. En uno, Daniel aparecía solo, llorando ante una tumba sin nombre.</p>

<p>—No mires demasiado tiempo —advirtió Clara.</p>

<p>Al final del corredor encontraron una puerta estrecha. Tras ella había una habitación circular llena de relojes. Grandes, pequeños, de pared, de bolsillo. Algunos colgaban del techo; otros estaban enterrados en el suelo hasta la mitad.</p>

<p>Todos marcaban las 23:17.</p>

<p>En el centro, sentado ante una mesa, estaba el hombre del abrigo negro.</p>

<p>—Os esperaba —dijo.</p>

<p>Tenía una voz tranquila, casi amable. Su rostro parecía cambiar ligeramente cada vez que Daniel intentaba fijarse en él.</p>

<p>—¿Eres el guardián? —preguntó Clara.</p>

<p>—Soy quien mantiene las puertas cerradas.</p>

<p>—¿Por qué?</p>

<p>El guardián sonrió sin alegría.</p>

<p>—Porque al otro lado hay cosas que aprendieron a imitar a los seres humanos.</p>

<p>Daniel sacó la carta.</p>

<p>—¿Conocías a mi abuelo?</p>

<p>Por primera vez, el guardián dejó de sonreír.</p>

<p>—Arturo fue el último que intentó cerrar la séptima puerta.</p>

<p>—¿Está vivo?</p>

<p>—Esa pregunta tiene un precio.</p>

<p>El guardián puso sobre la mesa un reloj de bolsillo y una pequeña fotografía. En ella aparecía Daniel de niño, sentado junto a un hombre al que no reconocía.</p>

<p>—Puedes hacer una pregunta —dijo el guardián—. Pero, a cambio, perderás uno de tus recuerdos.</p>

<p>Clara agarró la muñeca de Daniel.</p>

<p>—No lo hagas.</p>

<p>Daniel pensó en su abuelo, en la voz de la carta y en la escena que había visto detrás de la primera puerta.</p>

<p>—¿Qué le ocurrió a Arturo?</p>

<p>El reloj del guardián dio una vuelta completa. Daniel sintió un tirón dentro de la cabeza, como si alguien hubiera abierto un cajón de su memoria y se llevara algo sin pedir permiso.</p>

<p>De pronto, no pudo recordar la cara de su primer profesor. Sabía que había ido al colegio, pero aquel rostro había desaparecido para siempre.</p>

<p>El guardián contestó:</p>

<p>—Tu abuelo se quedó dentro para impedir que algo saliera. Pero el sello se está debilitando. Y tú llevas su sangre.</p>

<p>—¿Qué hay detrás de la séptima puerta?</p>

<p>—Eso ya es otra pregunta.</p>

<p>El guardián cerró el reloj.</p>

<p>Las agujas de todos los relojes avanzaron un segundo.</p>

<p>23:18.</p>

<p>La habitación entera tembló. Detrás de las paredes se escucharon golpes, muchos golpes, como si cientos de manos estuvieran llamando desde el otro lado.</p>

<p>El guardián se puso en pie.</p>

<p>—Ya os ha encontrado.</p>

<p>Y por primera vez, pareció tener miedo.</p>
<a class="inicio" href="#inicio">↑ Volver a la portada</a>
</section>

<section class="capitulo" id="cap6">
<h2>CAPÍTULO VI<br>El precio de recordar</h2>

<p>El guardián les abrió una puerta lateral y los empujó a un pasillo estrecho. Antes de cerrar, entregó a Daniel un pequeño cuaderno encuadernado en cuero.</p>

<p>—No lo leas hasta que escuches tres golpes —le advirtió—. Y si alguien que amas te pide que abras la puerta, asegúrate de que tenga sombra.</p>

<p>La puerta se cerró con un estruendo.</p>

<p>El pasillo terminaba en una escalera que descendía bajo el castillo. Las paredes estaban cubiertas de nombres, miles de ellos, grabados unos encima de otros. Clara iluminó uno con la linterna.</p>

<p>Era el nombre de su bisabuela.</p>

<p>Más abajo aparecía el de su padre. Después, el de su madre.</p>

<p>—Esto no tiene sentido —dijo Clara, temblando—. Mi familia no ha desaparecido.</p>

<p>Daniel encontró su propio nombre, escrito en una letra distinta. Debajo había una fecha: el día siguiente.</p>

<p>—Tenemos que salir de aquí.</p>

<p>Pero al llegar al final de la escalera encontraron una habitación llena de objetos: zapatos infantiles, fotografías, juguetes, cartas, alianzas de boda. Cosas que pertenecían a personas que habían entrado en el castillo y nunca habían regresado.</p>

<p>En una mesa había un retrato de Arturo Valera. No parecía mayor de cuarenta años. Detrás de él se veía la séptima puerta.</p>

<p>Daniel abrió el cuaderno. La primera página contenía una lista de reglas:</p>

<p>«Primera: el castillo no puede crear vida, solo imitarla.</p>
<p>Segunda: una memoria entregada al castillo no desaparece; queda almacenada.</p>
<p>Tercera: quien recupere un recuerdo deberá entregar otro.</p>
<p>Cuarta: la séptima puerta no debe abrirse desde este lado».</p>

<p>Entonces sonaron tres golpes.</p>

<p>Daniel levantó la cabeza.</p>

<p>Al otro lado de una puerta blanca estaba su madre.</p>

<p>—Daniel, cariño —dijo ella—. Abre, por favor. Tengo mucho frío.</p>

<p>Clara se quedó inmóvil.</p>

<p>Daniel se acercó, desesperado por escuchar una voz familiar. Puso la mano sobre el pomo.</p>

<p>Recordó la advertencia del guardián.</p>

<p>—Mamá, ¿qué hiciste el día que cumplí diez años?</p>

<p>La mujer guardó silencio.</p>

<p>—Te preparé una tarta —respondió finalmente.</p>

<p>Era cierto. Pero no era suficiente.</p>

<p>—¿Qué escribiste en la tarjeta?</p>

<p>Al otro lado, la voz empezó a llorar.</p>

<p>—Abre la puerta, Daniel.</p>

<p>Él miró al suelo.</p>

<p>La mujer no proyectaba ninguna sombra bajo la rendija.</p>

<p>Retrocedió.</p>

<p>El llanto se convirtió en una risa profunda y desconocida. Algo arañó la madera desde el otro lado.</p>

<p>—Entonces tendremos que entrar nosotros —susurró la voz.</p>

<p>La puerta empezó a hincharse hacia dentro.</p>

<p>Daniel y Clara echaron a correr mientras el primer tablón se partía.</p>
<a class="inicio" href="#inicio">↑ Volver a la portada</a>
</section>

<section class="capitulo" id="cap7">
<h2>CAPÍTULO VII<br>La puerta de las sombras</h2>

<p>La cuarta puerta era blanca y no tenía cerradura. Cuando Daniel apoyó la palma sobre ella, la superficie se volvió tan fría que tuvo que apartarse.</p>

<p>—Quizá necesita algo de nosotros —dijo Clara.</p>

<p>Daniel sacó la moneda partida que Elena les había entregado. La colocó en el centro de la puerta. Las dos mitades encajaron y formaron un símbolo parecido a un ojo cerrado.</p>

<p>La puerta se abrió.</p>

<p>Al otro lado se extendía un bosque idéntico al que habían atravesado para llegar al castillo. Sin embargo, los árboles estaban secos y el cielo tenía el color de una herida antigua.</p>

<p>En medio del camino había un niño con una chaqueta roja.</p>

<p>—Daniel —dijo Clara—. Ese niño...</p>

<p>Daniel lo reconoció. Era él mismo a los seis años, el niño de la escena que había visto tras la primera puerta.</p>

<p>El pequeño se volvió y echó a andar entre los árboles.</p>

<p>Daniel lo siguió.</p>

<p>—¡Espera! —gritó Clara.</p>

<p>Pero ella ya no estaba a su lado.</p>

<p>El bosque quedó en silencio. Daniel avanzó hasta encontrar una casa pequeña. En su interior había una mesa, una lámpara y un dibujo infantil: siete puertas, una figura negra y dos personas tomadas de la mano.</p>

<p>En la parte inferior, con letras torcidas, se leía: «Si olvido quién soy, que alguien me lo recuerde».</p>

<p>La puerta de la casa se cerró a sus espaldas.</p>

<p>El niño apareció sentado en la mesa.</p>

<p>—¿Por qué volviste? —preguntó.</p>

<p>—Busco a mi abuelo.</p>

<p>—No. Buscas saber por qué te dejó.</p>

<p>Daniel quiso responder, pero no encontró palabras.</p>

<p>El niño señaló una pared. Allí había siete sombras, cada una con una forma distinta. La última no tenía contorno fijo; se retorcía como humo bajo el agua.</p>

<p>—Ellos no pueden cruzar mientras las puertas sigan cerradas —dijo el niño—. Pero alguien les enseñó tu nombre.</p>

<p>—¿Quién?</p>

<p>El niño se levantó. Sus ojos eran exactamente iguales a los de Daniel.</p>

<p>—Tú.</p>

<p>Una grieta apareció en el suelo. Por ella surgió una mano negra, larga y delgada, que agarró al niño por el tobillo.</p>

<p>Daniel se lanzó a ayudarlo. En cuanto tocó la mano, sintió un frío insoportable y vio imágenes que no le pertenecían: una ciudad en llamas, siete personas arrodilladas, un hombre cerrando una puerta con sangre en las manos.</p>

<p>El niño se desvaneció.</p>

<p>La casa se convirtió en polvo y Daniel volvió al pasillo del castillo, tendido junto a Clara.</p>

<p>Ella lo sacudía por los hombros.</p>

<p>—¡Despierta! ¡Llevas minutos sin respirar!</p>

<p>Daniel se incorporó, jadeando.</p>

<p>En la palma de su mano había aparecido una marca negra: el mismo símbolo que llevaba la llave.</p>

<p>Y desde las profundidades del castillo llegó una voz que no necesitaba gritar para hacerse oír.</p>

<p>—Ya solo quedan tres.</p>
<a class="inicio" href="#inicio">↑ Volver a la portada</a>
</section>

<section class="capitulo" id="cap8">
<h2>CAPÍTULO VIII<br>El guardián</h2>

<p>Encontraron al guardián en una biblioteca subterránea. Las estanterías se perdían en la oscuridad y los libros estaban encadenados con eslabones de hierro.</p>

<p>—Habéis abierto la cuarta puerta —dijo él—. Eso significa que el castillo ha empezado a reconoceros.</p>

<p>—¿Qué quiere de nosotros? —preguntó Clara.</p>

<p>—No quiere. Recuerda. Es peor.</p>

<p>El guardián se quitó los guantes. Sus manos estaban cubiertas de pequeñas cicatrices y, en la palma izquierda, tenía la misma marca negra que Daniel.</p>

<p>—Yo también fui elegido —dijo—. Hace mucho tiempo.</p>

<p>Se llamaba Samuel. Había entrado en el castillo para buscar a su hermana, desaparecida durante una tormenta. Llegó hasta la séptima puerta y cometió el error de escuchar lo que había detrás.</p>

<p>—Oí su voz. Me dijo que estaba viva, que solo necesitaba que la dejara salir. Abrí la puerta unos centímetros.</p>

<p>—¿Y qué salió? —preguntó Daniel.</p>

<p>Samuel miró hacia el techo.</p>

<p>—Algo que sabía hablar como ella. Algo que sabía todas las cosas que yo recordaba de ella.</p>

<p>El guardián les mostró un libro abierto. Sus páginas estaban llenas de dibujos de personas, cada una con una sombra distinta. Algunas sombras tenían demasiados brazos; otras miraban en una dirección diferente a la de sus dueños.</p>

<p>—El castillo fue construido para contenerlas. Las siete puertas son siete sellos. Cada vez que alguien abre una, el sello se debilita.</p>

<p>—Entonces, ¿por qué nos ha dejado entrar? —preguntó Clara.</p>

<p>Samuel no respondió enseguida.</p>

<p>—Porque alguien ha cambiado las reglas.</p>

<p>Señaló un retrato al fondo de la biblioteca. Mostraba a siete guardianes frente al castillo. Daniel reconoció a Arturo, a Elena y a Samuel. El último rostro había sido raspado con tanta fuerza que el lienzo estaba agujereado.</p>

<p>Debajo aparecía una inscripción: «El séptimo guardián no puede morir. Solo puede olvidar».</p>

<p>Daniel sintió que la marca de su mano se calentaba.</p>

<p>—¿Quién es el séptimo guardián?</p>

<p>Samuel se acercó al retrato.</p>

<p>—Tu abuelo creía que eras tú.</p>

<p>Antes de que Daniel pudiera preguntar nada más, todas las cadenas de la biblioteca se tensaron a la vez.</p>

<p>Los libros comenzaron a abrirse solos.</p>

<p>De cada página surgió un susurro, miles de voces recitando el mismo nombre.</p>

<p>Daniel Valera.</p>

<p>Samuel cerró el libro de golpe.</p>

<p>—Ya sabe dónde estáis. Tenemos que llegar a la sexta puerta antes de que el reloj marque las doce.</p>

<p>—¿Y si no llegamos?</p>

<p>El guardián apagó la lámpara.</p>

<p>—Entonces la séptima puerta dejará de esperar.</p>
<a class="inicio" href="#inicio">↑ Volver a la portada</a>
</section>

<section class="capitulo" id="cap9">
<h2>CAPÍTULO IX<br>La verdad bajo el castillo</h2>

<p>La quinta puerta estaba cubierta de nombres. Miles de nombres grabados sobre la madera, algunos antiguos, otros tan recientes que la savia todavía brotaba de las letras.</p>

<p>Daniel encontró el de su madre. Después, el de Clara. Y, finalmente, el suyo, repetido siete veces.</p>

<p>Samuel les explicó que cada nombre pertenecía a alguien que había hecho un trato con el castillo. Algunos habían entregado un recuerdo para salvar a un ser querido. Otros habían pedido volver a ver a un muerto. Ninguno había comprendido el precio completo.</p>

<p>La llave abrió la puerta.</p>

<p>Al otro lado había un túnel de piedra que descendía bajo los cimientos. Las paredes vibraban con un pulso lento, como el corazón de una criatura gigantesca. A cada paso, Daniel escuchaba voces que le contaban recuerdos de su propia infancia.</p>

<p>Su primer día de colegio. El olor de la cocina de su madre. Una tarde jugando con su abuelo en el jardín.</p>

<p>Pero había algo extraño: los recuerdos no coincidían con lo que él recordaba. En todos aparecía una puerta negra al fondo, abierta unos centímetros.</p>

<p>Al final del túnel encontraron una cámara circular. En el centro había una máquina de hierro, formada por engranajes y péndulos, conectada a siete cadenas que desaparecían en la roca.</p>

<p>Junto a ella estaba Arturo Valera.</p>

<p>Daniel dejó de respirar.</p>

<p>Su abuelo tenía el mismo rostro que en las fotografías. Ni una arruga más. Ni una cana distinta.</p>

<p>—Has crecido —dijo Arturo.</p>

<p>Daniel quiso abrazarlo, pero Samuel lo detuvo.</p>

<p>—Espera. Comprueba su sombra.</p>

<p>Arturo estaba de pie bajo una lámpara. Su sombra se proyectaba en la pared, pero no copiaba sus movimientos. Mientras él levantaba una mano, la sombra permanecía inmóvil.</p>

<p>—No soy una de esas cosas —dijo Arturo—. Pero ya no soy del todo lo que recuerdas.</p>

<p>Les contó la verdad. Cien años atrás, siete guardianes habían descubierto una grieta entre el mundo de los vivos y otro lugar. Las criaturas que habitaban allí no tenían cuerpo propio. Para cruzar, necesitaban que alguien las recordara, que les diera un nombre y una forma.</p>

<p>La máquina mantenía cerrada la grieta, pero cada generación exigía un nuevo guardián.</p>

<p>Arturo había intentado destruirla. Fracasó y quedó atrapado en el castillo.</p>

<p>—La séptima puerta solo se abre cuando el guardián recuerda quién es —dijo.</p>

<p>Daniel miró su mano marcada.</p>

<p>—¿Y por qué yo?</p>

<p>Arturo bajó la cabeza.</p>

<p>—Porque cuando eras pequeño, te salvé la vida haciendo un trato. Te entregué parte de mi tiempo para que pudieras vivir. Desde entonces, el castillo te considera suyo.</p>

<p>—¿Qué tengo que hacer?</p>

<p>Su abuelo miró la máquina.</p>

<p>—Elegir qué recuerdo estás dispuesto a perder para cerrar la grieta.</p>

<p>En ese momento, una de las siete cadenas se rompió.</p>

<p>Desde detrás de la sexta puerta llegó un golpe tan fuerte que el polvo cayó del techo.</p>

<p>Arturo tomó la llave de Daniel y la sostuvo entre ambas manos.</p>

<p>—Ya no tenemos tiempo para elegir despacio.</p>
<a class="inicio" href="#inicio">↑ Volver a la portada</a>
</section>

<section class="capitulo" id="cap10">
<h2>CAPÍTULO X<br>La séptima puerta</h2>

<p>La sexta puerta era de piedra y no tenía pomo. Samuel les pidió que se apartaran mientras colocaba las manos sobre la superficie. Las cicatrices de sus dedos comenzaron a brillar.</p>

<p>—Cuando se abra, no escuchéis ninguna voz —advirtió—. Ni siquiera la mía.</p>

<p>La piedra se separó con un ruido profundo. Al otro lado no había una habitación, sino una oscuridad tan completa que la luz de la linterna parecía desaparecer antes de alcanzarla.</p>

<p>Daniel avanzó el primero.</p>

<p>En el centro de aquel vacío había una silla. Sobre ella descansaba un reloj de bolsillo idéntico al que había visto en la habitación de los relojes. La tapa estaba abierta y las agujas giraban hacia atrás.</p>

<p>Una voz habló desde la oscuridad.</p>

<p>—Daniel, soy tu abuelo. Ven conmigo.</p>

<p>Arturo estaba detrás de él. La voz, sin embargo, procedía de la silla.</p>

<p>—No la escuches —dijo el verdadero Arturo.</p>

<p>La voz cambió. Ahora era la de la madre de Daniel.</p>

<p>—Cariño, estoy aquí. Te he estado esperando.</p>

<p>Daniel cerró los ojos.</p>

<p>La oscuridad empezó a mostrar imágenes: su casa, su habitación, su madre sonriendo en la cocina. Después vio a su abuelo paseando con él por el jardín, contándole historias bajo el sol.</p>

<p>Todo parecía real. Demasiado real.</p>

<p>Clara le agarró la mano.</p>

<p>—Recuerda lo que dijo Samuel. No pueden crear vida. Solo imitarla.</p>

<p>La imagen de su madre se acercó.</p>

<p>—¿No quieres volver a casa?</p>

<p>Daniel apretó los dientes.</p>

<p>—Sí. Pero tú no eres ella.</p>

<p>Las imágenes se deformaron. La sonrisa de su madre se abrió demasiado, y detrás de sus ojos apareció un espacio negro, inmenso, lleno de figuras que se movían sin tocarse.</p>

<p>La criatura gritó. El sonido hizo temblar el castillo.</p>

<p>Daniel abrió los ojos. Frente a él estaba la séptima puerta, que había aparecido al fondo de la oscuridad. Su superficie era negra y lisa, sin cerradura ni bisagras.</p>

<p>La marca de su mano comenzó a arder.</p>

<p>Arturo se arrodilló a su lado.</p>

<p>—Ahora lo entiendes. No necesitas una llave para abrirla. Necesitas recordar por qué la cerraste.</p>

<p>Daniel miró a su abuelo, confundido.</p>

<p>Y entonces un recuerdo enterrado durante años regresó a su mente: él, con seis años, de pie ante aquella misma puerta. Su abuelo lloraba mientras le pedía que olvidara lo que había visto.</p>

<p>Daniel había estado allí antes.</p>

<p>Y había sido él quien había abierto la puerta la primera vez.</p>

<p>Detrás de ella, algo empezó a pronunciar su nombre con cientos de voces.</p>
<a class="inicio" href="#inicio">↑ Volver a la portada</a>
</section>

<section class="capitulo" id="cap11">
<h2>CAPÍTULO XI<br>Lo que regresó</h2>

<p>La séptima puerta no se abrió. Se volvió transparente.</p>

<p>Daniel vio un lugar sin cielo ni suelo, una extensión infinita donde flotaban recuerdos ajenos: cumpleaños, despedidas, promesas, últimos abrazos. Cada recuerdo tenía una luz distinta. En el centro se retorcía una sombra gigantesca, construida con miles de rostros.</p>

<p>La criatura habló con la voz de Arturo.</p>

<p>—Yo te salvé.</p>

<p>Después habló con la voz de Clara.</p>

<p>—Yo confié en ti.</p>

<p>Y, finalmente, con la voz del propio Daniel.</p>

<p>—Tú me dejaste aquí.</p>

<p>La verdad regresó por completo. De niño, Daniel había encontrado el castillo durante una excursión con su abuelo. Había visto la puerta abierta y, llevado por la curiosidad, había pronunciado su propio nombre ante la oscuridad. La criatura lo había elegido como entrada al mundo de los vivos.</p>

<p>Arturo lo había salvado entregando parte de su vida y cerrando la puerta desde dentro.</p>

<p>Pero la criatura nunca había dejado de recordar a Daniel.</p>

<p>—No quiero hacerte daño —dijo la sombra—. Solo quiero salir. Puedo devolverte todo lo que has perdido.</p>

<p>En la oscuridad apareció una imagen de su abuelo, libre y sonriente, caminando bajo el sol. Después apareció su madre, esperándolo en casa. Daniel sintió el deseo de atravesar la puerta y abrazarlos.</p>

<p>Entonces recordó algo que su abuelo le decía cuando era pequeño: «No todo lo que te llama por tu nombre te conoce».</p>

<p>Daniel se volvió hacia Clara.</p>

<p>—Necesito que me recuerdes quién soy.</p>

<p>Clara lo miró con lágrimas en los ojos.</p>

<p>—Eres Daniel Valera. Eres el chico que me ayudó cuando nadie más lo hizo. Eres terco, curioso y te metes en problemas porque no sabes dejar una pregunta sin respuesta.</p>

<p>La marca de la mano de Daniel empezó a apagarse.</p>

<p>—Sigue —dijo él.</p>

<p>Clara le habló de sus recuerdos compartidos, de sus conversaciones, de sus bromas y de todas las veces que habían estado a punto de rendirse y no lo habían hecho.</p>

<p>La sombra retrocedió.</p>

<p>Arturo comprendió lo que estaba pasando.</p>

<p>—¡Los recuerdos que compartimos no le pertenecen al castillo! —gritó—. ¡No puede arrebatarnos lo que seguimos eligiendo recordar!</p>

<p>Daniel extendió la mano hacia su abuelo. Arturo la tomó.</p>

<p>Por primera vez en cien años, la sombra de Arturo se movió exactamente al mismo tiempo que él.</p>

<p>La séptima puerta empezó a cerrarse.</p>

<p>Pero la criatura lanzó un último golpe contra la máquina. Las siete cadenas se rompieron a la vez.</p>

<p>El castillo comenzó a derrumbarse.</p>

<p>Y una mano negra cruzó el umbral antes de que la puerta se cerrara por completo.</p>
<a class="inicio" href="#inicio">↑ Volver a la portada</a>
</section>

<section class="capitulo" id="cap12">
<h2>CAPÍTULO XII<br>El último secreto</h2>

<p>El suelo se abrió bajo sus pies. Clara cayó de rodillas y Daniel la sujetó por la cintura. Arturo empujó a ambos hacia el túnel, mientras Samuel intentaba mantener cerrada la séptima puerta con las manos ensangrentadas.</p>

<p>—¡Marchaos! —gritó el guardián.</p>

<p>—¡No vamos a dejarte aquí! —respondió Daniel.</p>

<p>Samuel sonrió por primera vez.</p>

<p>—Llevo demasiado tiempo aquí. Ya es hora de que alguien recuerde mi nombre.</p>

<p>Se volvió hacia la oscuridad y pronunció su nombre completo: Samuel Echevarría. Las cadenas que quedaban se iluminaron y el guardián desapareció en una explosión de luz blanca.</p>

<p>La puerta se cerró.</p>

<p>Daniel, Clara y Arturo corrieron por el túnel mientras el castillo se deshacía a su alrededor. Las paredes se convertían en polvo y los nombres grabados desaparecían uno tras otro.</p>

<p>Cuando llegaron al exterior, el amanecer comenzaba a iluminar los árboles.</p>

<p>El castillo ya no estaba.</p>

<p>En su lugar había una colina cubierta de hierba, piedras antiguas y una pequeña placa de metal. Daniel se arrodilló ante ella y limpió la tierra con la manga.</p>

<p>La placa tenía grabados siete nombres. Entre ellos estaban los de Samuel y Arturo.</p>

<p>Pero el último nombre estaba vacío.</p>

<p>Arturo parecía mucho más viejo. Sus manos temblaban y su cabello se había vuelto completamente blanco.</p>

<p>—¿Qué te pasa? —preguntó Daniel.</p>

<p>—El tiempo que entregué al castillo está regresando de golpe. No me queda mucho.</p>

<p>Daniel sintió un nudo en la garganta.</p>

<p>—No puedes irte ahora. Acabo de encontrarte.</p>

<p>Arturo le acarició el pelo, igual que en los recuerdos de su infancia.</p>

<p>—Nunca me fui del todo, muchacho. Estuve en cada historia que te conté, en cada pregunta que hiciste y en cada vez que decidiste ser valiente aunque tuvieras miedo.</p>

<p>Se sentaron juntos en la hierba hasta que el sol apareció sobre los árboles.</p>

<p>Arturo cerró los ojos.</p>

<p>Cuando Daniel volvió a abrir los suyos, su abuelo había desaparecido. Solo quedaba la llave negra, convertida en una pequeña pieza de metal dorado.</p>

<p>Clara apoyó la cabeza en su hombro. Ninguno de los dos habló durante un largo rato.</p>

<p>Después regresaron al pueblo. Su madre abrazó a Daniel con tanta fuerza que apenas pudo respirar. No le preguntó dónde había estado. Solo lloró y le pidió que nunca volviera a desaparecer de aquella manera.</p>

<p>Durante semanas, Daniel intentó convencerse de que todo había terminado. Los relojes volvieron a funcionar. Las luces dejaron de parpadear. El bosque recuperó sus sonidos y el camino del castillo desapareció entre la maleza.</p>

<p>Sin embargo, había cosas que no encajaban.</p>

<p>En la fotografía de 1891, los rostros de los seis guardianes habían cambiado. Ya no estaban borrosos. Ahora Daniel podía distinguirlos perfectamente.</p>

<p>Y en la esquina, donde antes solo había una figura de espaldas, aparecía un niño con una chaqueta roja.</p>

<p>Era él.</p>

<p>Una noche, varios meses después, Daniel se despertó a las 23:17. Sobre su escritorio había un sobre negro que no estaba allí cuando se acostó.</p>

<p>Dentro encontró una hoja y una llave de plata.</p>

<p>La carta decía:</p>

<p>«Daniel:</p>

<p>Las siete puertas están cerradas. Pero una puerta cerrada no significa que no haya alguien al otro lado.</p>

<p>Has salvado el mundo que conoces. Ahora debes descubrir quién construyó el castillo y por qué existía una octava llave.</p>

<p>No confíes en el hombre que lleva tu rostro.</p>

<p>Nos veremos cuando los relojes vuelvan a detenerse.</p>

<p>—A.»</p>

<p>Daniel dejó caer la carta.</p>

<p>En el espejo de su habitación, su reflejo seguía sentado en la cama.</p>

<p>Él, en cambio, ya estaba de pie.</p>

<p>El reflejo sonrió.</p>

<p>Y detrás de él apareció una puerta que Daniel nunca había visto.</p>

<div class="final">
FIN DE LA PRIMERA PARTE<br><br>
El enigma continúa...
</div>
<a class="inicio" href="#inicio">↑ Volver a la portada</a>
</section>

</main>

<footer>
EL ENIGMA DE LAS SIETE PUERTAS<br>
Una historia de secretos, memoria y oscuridad.
</footer>

</body>
</html>
