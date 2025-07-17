# mi-pagina
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Portafolio de Tareas</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Merriweather&display=swap" rel="stylesheet">
  <style>
   body {
  background-color: #fdfdfd;
  background-image: url('https://www.transparenttextures.com/patterns/paper-fibers.png');
  background-repeat: repeat;
  background-size: auto;
  color: #1e3a8a;
}

.boton-descarga {
  background-color: #1e3a8a;
  color: white;
  padding: 12px 24px;
  border-radius: 8px;
  text-decoration: none;
  font-weight: 600;
  font-size: 16px;
  transition: background-color 0.3s ease;
}

.boton-descarga:hover {
  background-color: #3b82f6;
}

    header {
      background: #1e3a8a;
      color: white;
      text-align: center;
      padding: 50px 20px 30px;
    }

    header h1 {
      font-family: 'Merriweather', serif;
    }

    nav {
      background: white;
      border-bottom: 1px solid #d1d5db;
      padding: 14px 0;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 999;
    }

    nav a {
      color: #1e3a8a;
      margin: 0 16px;
      text-decoration: none;
      font-weight: 600;
      font-size: 16px;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #3b82f6;
    }

    .intro {
      text-align: center;
      padding: 50px 20px 30px;
      max-width: 800px;
      margin: auto;
      animation: fadeIn 1.2s ease;
    }

    .intro img {
      width: 140px;
      height: 140px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #1e3a8a;
      margin-bottom: 20px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

.logo-utp {
  height: 60px;
  width: auto;
  background-color: white;
  padding: 4px;
  border-radius: 6px;
}

    hr.decorado {
      border: none;
      height: 2px;
      background-color: #e0e7ff;
      margin: 40px auto;
      width: 60%;
    }

    .contenedor {
      max-width: 1100px;
      margin: 40px auto;
      padding: 0 20px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 24px;
    }

    .semana {
      background: white;
      border: 1px solid #d1d5db;
      border-radius: 10px;
      padding: 20px;
      text-align: center;
      transition: transform 0.3s ease, box-shadow 0.3s ease, border-color 0.3s ease;
    }

    .semana:hover {
      transform: translateY(-8px);
      border-color: #1e3a8a;
      box-shadow: 0 12px 20px rgba(30, 58, 138, 0.15);
    }

    .semana h2 {
      font-family: 'Merriweather', serif;
    }

    .galeria img {
      width: 100%;
      border-radius: 6px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.05);
    }

    footer {
      background: #f1f5f9;
      color: #1e3a8a;
      text-align: center;
      padding: 20px;
      font-size: 14px;
      margin-top: 60px;
    }

    .subir {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #1e3a8a;
      color: white;
      padding: 12px;
      border-radius: 50%;
      text-decoration: none;
      font-size: 20px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .progreso {
      height: 4px;
      background: #3b82f6;
      position: fixed;
      top: 0;
      left: 0;
      z-index: 1000;
    }
  </style>
</head>
<body onscroll="actualizarBarra()">
  <div class="progreso" id="barra"></div>

  <header>
  <div style="display: flex; align-items: center; justify-content: center; flex-wrap: wrap; padding: 10px 20px; position: relative;">
    <!-- Logo alineado a la izquierda -->
    <img src="logo-utp.png" alt="Logo UTP" class="logo-utp" style="position: absolute; left: 20px; top: 20px; height: 60px;">

    <!-- Contenido centrado -->
    <div style="text-align: center; flex: 1;">
      <h1>Portafolio Final</h1>
      <p>Universidad Tecnológica del Perú - UTP</p>
      <p style="font-style: italic; opacity: 0.9;">“Del trazo a la precisión: cada línea dibujada es un paso hacia la ingeniería.”</p>
    </div>
  </div>
</header>

  <nav>
    <a href="#inicio"><i class="fa fa-home"></i> Inicio</a>
    <a href="#semanas"><i class="fa fa-calendar-week"></i> Semanas</a>
  </nav>

  <div class="intro" id="inicio">
    <h2>Owight Capa Villar</h2>
    <p>Curso: Dibujo para ingeniería<br>Docente: Sandro Rivera Valle<br>Sección: 22328</p>
  </div>

  <hr class="decorado">

  <section style="max-width:800px;margin:40px auto;padding:0 20px;">
    <h2 style="color:#1e3a8a;">Sobre mí</h2>
    <p>Soy estudiante de la Universidad Tecnológica del Perú, comprometido con mi formación profesional. Este portafolio recoge los trabajos realizados en el curso de Dibujo Técnico, desde escaneos hasta desarrollos en AutoCAD. Aquí podrás explorar cada semana con sus respectivas evidencias.</p>
  </section>

  <hr class="decorado">

  <div class="contenedor" id="semanas">
   <!-- Bloques de semana del 1 al 16 (excepto la 9) -->
<div class="semana">
  <a href="semana1.html" style="text-decoration: none; color: inherit;">
    <h2><i class="fa fa-calendar-alt"></i> Semana 1</h2>
    <div class="galeria">
    </div>
  </a>
</div>
<div class="semana">
  <a href="semana2.html" style="text-decoration: none; color: inherit;">
    <h2><i class="fa fa-calendar-alt"></i> Semana 2</h2>
    <div class="galeria">
    </div>
  </a>
</div>
<div class="semana">
  <a href="semana3.html" style="text-decoration: none; color: inherit;">
    <h2><i class="fa fa-calendar-alt"></i> Semana 3</h2>
    <div class="galeria">
    </div>
  </a>
</div>
<div class="semana">
  <a href="semana4.html" style="text-decoration: none; color: inherit;">
    <h2><i class="fa fa-calendar-alt"></i> Semana 4</h2>
    <div class="galeria">
    </div>
  </a>
</div>
<div class="semana">
  <a href="semana5.html" style="text-decoration: none; color: inherit;">
    <h2><i class="fa fa-calendar-alt"></i> Semana 5</h2>
    <div class="galeria">
    </div>
  </a>
</div>
<div class="semana">
  <a href="semana6.html" style="text-decoration: none; color: inherit;">
    <h2><i class="fa fa-calendar-alt"></i> Semana 6</h2>
    <div class="galeria">
    </div>
  </a>
</div>
<div class="semana">
  <a href="semana7.html" style="text-decoration: none; color: inherit;">
    <h2><i class="fa fa-calendar-alt"></i> Semana 7</h2>
    <div class="galeria">
    </div>
  </a>
</div>
<div class="semana">
  <a href="semana10.html" style="text-decoration: none; color: inherit;">
    <h2><i class="fa fa-calendar-alt"></i> Semana 10</h2>
    <div class="galeria">
    </div>
  </a>
</div>
<div class="semana">
  <a href="semana11.html" style="text-decoration: none; color: inherit;">
    <h2><i class="fa fa-calendar-alt"></i> Semana 11</h2>
    <div class="galeria">
    </div>
  </a>
</div>
<div class="semana">
  <a href="semana12.html" style="text-decoration: none; color: inherit;">
    <h2><i class="fa fa-calendar-alt"></i> Semana 12</h2>
    <div class="galeria">
    </div>
  </a>
</div>
<div class="semana">
  <a href="semana13.html" style="text-decoration: none; color: inherit;">
    <h2><i class="fa fa-calendar-alt"></i> Semana 13</h2>
    <div class="galeria">
    </div>
  </a>
</div>
<div class="semana">
  <a href="semana14.html" style="text-decoration: none; color: inherit;">
    <h2><i class="fa fa-calendar-alt"></i> Semana 14</h2>
    <div class="galeria">
    </div>
  </a>
</div>
<div class="semana">
  <a href="semana15.html" style="text-decoration: none; color: inherit;">
    <h2><i class="fa fa-calendar-alt"></i> Semana 15</h2>
    <div class="galeria">
    </div>
  </a>
</div>
<div class="semana">
  <a href="semana16.html" style="text-decoration: none; color: inherit;">
    <h2><i class="fa fa-calendar-alt"></i> Semana 16</h2>
    <div class="galeria">
    </div>
  </a>
</div>
<div class="semana">
  <a href="semana17.html" style="text-decoration: none; color: inherit;">
    <h2><i class="fa fa-calendar-alt"></i> Semana 17</h2>
    <div class="galeria">
    </div>
  </a>
</div>
  </div>

  <footer>© 2025 - Portafolio creado por Owight Capa Villar para la UTP</footer>
  <a href="#inicio" class="subir" title="Subir">↑</a>

<div style="text-align: center; margin: 40px 0;">
  <a href="portafolio.zip" download class="boton-descarga">
    <i class="fa fa-download"></i> Descargar Portafolio
  </a>
</div>

  <script>
    function actualizarBarra() {
      const barra = document.getElementById("barra");
      const scroll = document.documentElement.scrollTop;
      const altura = document.documentElement.scrollHeight - document.documentElement.clientHeight;
      const ancho = (scroll / altura) * 100;
      barra.style.width = ancho + "%";
    }
  </script>
</body>
</html>
