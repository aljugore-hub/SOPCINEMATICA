<!DOCTYPE html>
<!--Created by Ardora - www.webardora.net-->
<!--ArdoraSopa-->
<!--bajo licencia Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)
para otros usos contacte con el autor-->
<html lang="es">
<head><meta charset="utf-8" /><title>SOPA DE LETRAS</title>
<link type="text/css" href="SOPA_resources/css/ardoraSopa.css" rel="stylesheet" />
<script language="javascript" type="text/javascript" src="SOPA_resources/js/jquery.js"></script>
<script language="javascript" type="text/javascript" src="SOPA_resources/js/jquery-ui.min.js"></script>
<script language="javascript" type="text/javascript" src="SOPA_resources/js/jquery.ui.touch-punch.min.js"></script>
<script language="javascript" type="text/javascript" src="SOPA_resources/js/ardoraSopaCFG.js"></script>
<script language="javascript" type="text/javascript" src="SOPA_resources/js/ardoraScorm.js"></script>
<script language="javascript" type="text/javascript" src="SOPA_resources/js/ardoraSopa.js"></script>
<script language="javascript" type="text/javascript" src="SOPA_resources/js/ardoraTab.js"></script>
</head>
<body onLoad="loadPage()" onbeforeunload="unloadPage()" onUnload="unloadPage()">
<div id="ardoraMain">
<div id="ardoraEnu"><SPAN style="font-size:12px;color:#000000">EN LA SIGUIENTE SOPA DE LETRAS, ENCUENTRA LAS PALABRAS RELACIONADAS CON EL TEMA DE CINEMATICA </SPAN></div>
  <div id="ardoraAct">
<canvas id="ardoraActBoard" width="990px" height="600px"></canvas>
<canvas id="ardoraActSel" width="990px" height="600px"></canvas>
<svg id="s_pointer" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="558px" height="350px">
<line id="vertical" x1="0" y1="0" x2="0" y2="350" style="stroke:rgb(255,0,0);stroke-width:1" />
<line id="horizontal" x1="0" y1="0" x2="558" y2="0" style="stroke:rgb(255,0,0);stroke-width:1" />
<circle id="c_point" cx="0" cy="0" r="5"style="opacity:0.1;stroke:rgb(255,0,0);stroke-width:2"/></svg>
<canvas id="ardoraActCanvas" width="2px" height="2px"></canvas>
  </div>
<div id="ardoraTab">
  <canvas id="ardoraTabCanvas" width="70" height="88"></canvas>
</div></div>
<div id="ardoraAlumSCORM"><p></p></div>
<div id="ardoraAutor"><p>ALVARO GONZALES</p></div>
</body></html>
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Proyecto SOPCINEMÁTICA</title>
  <link rel="stylesheet" href="estilos/estilo.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f8fc;
      color: #333;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #005baa;
      color: white;
      padding: 20px;
      text-align: center;
    }
    main {
      padding: 30px;
      max-width: 800px;
      margin: auto;
    }
    .boton {
      display: inline-block;
      padding: 12px 20px;
      margin-top: 20px;
      background-color: #007acc;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }
    .boton:hover {
      background-color: #005f99;
    }
  </style>
</head>
<body>
  <header>
    <h1>Proyecto SOPCINEMÁTICA</h1>
    <p>Actividad interactiva sobre conceptos de cinemática</p>
  </header>
  <main>
    <h2>Bienvenido/a</h2>
    <p>Este sitio presenta una actividad pedagógica diseñada para reforzar el aprendizaje de la cinemática, desarrollada por <strong>Álvaro Gonzales</strong> en el marco de la gestión educativa institucional.</p>
    <p>Haz clic en el siguiente botón para acceder a la sopa de letras interactiva:</p>
    <a class="boton" href="actividad.html">Ir a la actividad</a>
  </main>
</body>
</html>
