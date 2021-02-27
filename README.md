# 1.-taller-css
desarrollo web
----------------------------------
HOJA DE VIDA ARCHIVOS : 
----------------------------------

<!-- Nombres: Juan David Lopez Lombana - Juan Manuel Guerrero Arteaga -->


<!DOCTYPE html>
<html lang="es" dir="ltr">
  <head class="centrado">

    <meta charset="utf-8">
    <title>HOJA DE VIDA</title>
    <link rel="stylesheet" href="cvv.css">
  </head>
  <body>
    <div >
      <div class="centrado">
        <img class="centrado" src="C:\Users\JuanMa\Desktop\avatar.jpg" alt="logotipo">
      </div>


      <fieldset class="txt">
      <h1>Nombre:</h1>JuanMa
      <h1>Direccion:</h1>El poblado
      <h1>Cédula</h1>119222992
      <h1>Nacimiento</h1>01/02/2001
      </fieldset>

      <fieldset class="txt2">
        <h2>Mi Perfil</h2>
        <h2>Gracias a mi formación especializada, considero que puedo aportar valor y seguir desarrollándome profesionalmente en una compañía que coincida con mis valores y expectativas.</h2>
      </fieldset>

      <fieldset>
        <p class="txt3">Experiencia laboral</p>
        <table>
          <tr>
            <td>Fecha de Inicio</td><td> | 21/02/2021</td>
          </tr>

        </table>
        <table>
          <tr>
            <td>Fecha de Terminación</td><td> | 21/06/2023</td>
          </tr>
        </table>
        <table>
          <tr>
            <td>Nombre de la Empresa</td><td> | Google</td>
          </tr>
        </table>
        <table>
          <tr>
            <td>Cargo</td><td> | Ingeniero en Software</td>
          </tr>
        </table>
      </fieldset>


    </div>

  </body>
</html>

/*JUAN MANUEL GUERRERO ARTEAGA - JUAN DAVID LOPEZ LOMBANA */

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}


.centrado{

  text-align: center;
}

.txt{
  color: white;
  background-color: blue;
}

.txt2{
  color: white;
  background-color: blue;
}

.txt3{
  color: white;
  background-color: blue;

}

img.centrado{
  text-align: center;

  width: 60px;
  height: 60px;
}
----------------------------------------------------------
PUNTO DEL DIV MARGIN: 0 AUTO;
----------------------------------------------------------
/*Nombres: Juan David Lopez Lombana - Juan Manuel Guerrero Arteaga */

.div{
  margin: 0 auto;
  background: yellow;
}

<!-- Nombres: Juan David Lopez Lombana - Juan Manuel Guerrero Arteaga -->

<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="div.css">
    <title></title>
  </head>
  <body>
    <div >

      <p class="div">Como todos sabemos, el valor 0 automático significa que los márgenes
      superior e inferior son iguales a 0, y el margen lateral está configurado
      en automático. Después de asignar márgenes automáticos a un elemento,
      el navegador centrará el elemento en relación con su elemento principal.</p>



    </div>

  </body>
</html>

----------------------------------------------
PUNTO DE LOS COLORES
----------------------------------------------
/*Nombres: Juan David Lopez Lombana - Juan Manuel Guerrero Arteaga */
*{
  margin:0px;
  padding: 0px;
}

div#general{
  margin: auto;
  width: 500px;
  height: 500px;
  background-color:yellow;
}

div#ofertas{
  width: 60px;
  height:500px;
  background-color:blue;
}
 div#clase{
   width: 30px;
   height: 500px;
   background-color: red;
 }

 div#hola{
   margin: 60px;
   width: 15px;
   height: 500px;
   background-color: yellow;

 }

 div#jj{
   margin:50px;
   width:80px;
   height: 500px;
   background-color:red;
 }

 div#aa{
   margin:80px;
   width: 110px;
   height: 500px;
   background-color: blue;
 }

<!-- Nombres: Juan David Lopez Lombana - Juan Manuel Guerrero Arteaga -->

<!DOCTYPE html>

<html lang="es" >
  <head>
    <title></title>
    <meta http-equiv="content-type" content="text/html; charset=iso-8859">
    <link rel="stylesheet" type="text/css" href="colores.css"/>
  </head>
  <body>
    <div id="general">
        <div id="ofertas">
        <div id="clase">
        <div id="hola">
        <div id="jj">
        <div id="aa">


      </div>

  </body>
</html>

----------------------------------------------------
AUTOS
----------------------------------------------------
<!-- Nombres: Juan David Lopez Lombana - Juan Manuel Guerrero Arteaga -->

<!DOCTYPE html>
<html lang="es" dir="ltr">
  <head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="styleLY.css">
    <title>AUTOS </title>
  </head>
  <body>

    <header>
      <div class="logotipo">
        <img src="C:\Users\JuanMa\Desktop\shelby.jpg" width="300" alt="logo">
      </div>
      <nav>
        <ul>
          <li><a href="#"></li>
          <li><a href="C:\Users\JuanMa\Desktop\TALLER HTML2\4. layout\Renault.html">Renault</li>
          <li><a href="C:\Users\JuanMa\Desktop\TALLER HTML2\4. layout\Citroen.html">Citroen</li>
          <li><a href="C:\Users\JuanMa\Desktop\TALLER HTML2\4. layout\Peugeot.html">Peugeot</li>
          <li><a href="C:\Users\JuanMa\Desktop\TALLER HTML2\4. layout\Bugatti.html">Bugatti</li>
        </ul>

      </nav>
    </header>

    <section class="main">
      <section class="articles">
        <article>
          <h2>Pagina oficial de Carros</h2>
          <p>La historia del automóvil involucra la serie de eventos, innovaciones y conocimientos científico-tecnológicos que dieron nacimiento al automóvil. Son los eventos que le permitieron evolucionar y convertirse finalmente en lo que hoy forma parte de nuestra vida cotidiana.
             Llamados carros, autos o coches, los vehículos automotores terrestres son una de las más exitosas invenciones del ser humano en lo que a desplazamiento se refiere. Su popularidad durante sus más de dos siglos de historia ha sido tal, que se estima un número total de 1,2 billones de automóviles circulando en la actualidad.
             Etapa de la Invención: comprende desde 1768 hasta 1889 aproximadamente. El primer automóvil fue llamado Fardier, por su inventor Nicholas Joseph Cugnot (mecánico, escritor e inventor) y comenzó a verse en las avenidas de París en el año 1769. La función inicial de este vehículo a vapor era el transporte de piezas de artillería pesadas. Era una especie de triciclo con una caldera y cilindros, que luego Cugnot fue perfeccionando, creando dos versiones posteriores (una en 1770 y otra
             en 1771), siendo la última la que se encuentra actualmente en el Museo Nacional de la Técnica, ubicado en París, Francia.</p>
           <h2>Carro mecánico</h2>
          <p>Un carro mecánico sin tracción animal: ese era el sueño de muchos ingenieros que acabó haciéndose realidad, pero poco a poco. Desde las primeras máquinas automotrices, a vapor, a los motores de combustión, las ruedas con neumáticos, la suspensión... No resulta sencillo marcar un momento preciso en la historia para decidir desde qué momento existe lo que hoy entendemos por automóvil. De lo que no cabe ninguna duda es de que, en aquella conquista tecnológica, Benz y su proyecto de motorwagen tuvieron mucho que ver.</p>
        </article>
      </section>
      <aside >
        <h2>Siglo </h2>
        <p>www.autoscout24.es/tematicas/especial/
          productores-de-coche/automoviles-franceses/</p>

        <p>Fue en el siglo 18 cuando comenzaron a aparecer los primeros vehículos, que en ese entonces eran propulsados mediante el vapor. La historia del automóvil está clasificada en siete etapas: etapa de la invención, etapa veterana, etapa Eduardiana, etapa de época, etapa pre-guerra, etapa post-guerra y etapa moderna. </p>
      </aside>

    </section>

    <footer class="articles">
      <p>Juan David Lopez & Juan Manuel Guerrero
         juandaju@gmail.com
        +57 321 677 8920
        Medellín - Antioquia </p>

    </footer>

  </body>
</html>
<!-- Nombres: Juan David Lopez Lombana - Juan Manuel Guerrero Arteaga -->

<!DOCTYPE html>
<html lang="es" dir="ltr">
  <head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="styleLY.css">
    <title>Peugeot</title>
  </head>
  <body>

    <header>
      <div class="logotipo">
        <center>
        <img src="C:\Users\JuanMa\Desktop\peu.png" width="300" alt="logo"></center>
      </div>

    </header>

    <section class="main">
      <section class="articles">
        <article>
          <h2>Peugeot</h2>
          <p>La marca francesa de Peugeot ha destacado por ser una de las primeras pioneras, tanto en el final del siglo XX como en la actualidad. Es una marca que, a pesar de tener unos comienzos difíciles, se ha asentado en Francia, Europa y en el mundo.

Su conocida tendencia por nombrar a todas sus series con números, en los cuales un cero está entre las tres cifras, y el característico león de su frontal son su seña de identidad. </p>

        </article>
      </section>
      <aside >
        <h2>Comienzos difíciles</h2>

        <p>No era un gran negocio y el inicio fue bastante poco esperanzador. Tuvieron muchos problemas económicos, necesitaron ayuda de otros socios capitalistas y durante más de 60 años la empresa estuvo a la deriva con todo tipo de problemas. En 1890, el dueño de la compañía (Armand Peugeot) conoce a Gottlieb Daimler de Mercedes-Benz, el cual le ayuda a crear el Peugeot Type 3, primer coche de la marca.

 </p>
      </aside>

    </section>

    <footer class="articles">
      <p>Juan David Lopez & Juan Manuel Guerrero
         juandaju@gmail.com
        +57 321 677 8920
        Medellín - Antioquia </p>

    </footer>

  </body>
</html>

<!-- Nombres: Juan David Lopez Lombana - Juan Manuel Guerrero Arteaga -->

<!DOCTYPE html>
<html lang="es" dir="ltr">
  <head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="styleLY.css">
    <title>Renault</title>
  </head>
  <body>

    <header>
      <div class="logotipo">
        <center>
        <img src="C:\Users\JuanMa\Desktop\renault.png" width="300" alt="logo"></center>
      </div>

    </header>

    <section class="main">
      <section class="articles">
        <article>
          <h2>RENAULT</h2>
          <p>Renault es uno de los tres pilares fundamentales de la industria automovilística en Francia, junto a Citroën y Peugeot. Estos últimos años se ha hecho notar gracias a sus éxitos en la Fórmula 1, claro exponente de innovación tecnológica en el mundo del motor y de los coches. Los resultados se han hecho notorios en forma de mayores ventas. La repercusión mundial y la publicidad que aportan las victorias en dicha competición no tiene precio, y Renault ha sabido sacar partido de esta circunstancia. Esta es la historia de Renault.</p>

        </article>
      </section>
      <aside >
        <h2>HISTORIA LOGO </h2>

        <p>El emblema original de Renault data de 1900, y en él figuran las iniciales de los tres hermanos: Louis, Ferdinand y Marcel. En 1906 el logo cambia por el frontal de un coche encerrado en un engranaje. Durante la Primera Guerra Mundial, Renault produce un tanque para las tropas aliadas llamado FT17, que se hizo tan popular que finalizada la guerra cambiaron el logotipo por el de un tanque. La fa forma de diamante se introdujo en 1925 y ha perdurado hasta nuestros días. El diseñador del logo actual es obra de Victor Vesarely, en 1972, que, después de alguna que otra modificación, perdura hasta hoy.

 </p>
      </aside>

    </section>

    <footer class="articles">
      <p>Juan David Lopez & Juan Manuel Guerrero
         juandaju@gmail.com
        +57 321 677 8920
        Medellín - Antioquia </p>

    </footer>

  </body>
</html>

/* Nombres: Juan David Lopez Lombana - Juan Manuel Guerrero Arteaga*/

*{
  margin: 0;
  padding: 0;
}

body{
  background: #e6e6e6;
}

header, .main, footer{
  width: 90%;
  max-width: 1000px;
  margin:20px auto;
}

header nav{
  background: #528ED5;
  overflow: hidden;
}

header nav ul{
  list-style: none;
}

header nav ul li{
  float: left;
}

header nav ul li a{
  padding: 10px 20px;
  display: block;
  color: #fff;
  text-decoration:none;
}

header nav ul li a:hover{
  background: #75ACEC;
}

.main .articles{
  width: 68.5%;
  margin-right: 1.5%;
  float: left;
  background: #fff;
}
.main .articles article{
  padding: 20px;
  background: #fff;
  margin-bottom: 20px;
}

aside{
  width: 30%;
  background: #ff8000;
  float: left;
  padding: 20px;
  box-sizing: border-box;
}

footer{
  background: #000;
  color: #fff;
  clear: both;
  padding: 10px 0px;
  text-align: center;
}

<!-- Nombres: Juan David Lopez Lombana - Juan Manuel Guerrero Arteaga -->

<!DOCTYPE html>
<html lang="es" dir="ltr">
  <head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="styleLY.css">
    <title>Bugatti</title>
  </head>
  <body>

    <header>
      <div class="logotipo">
        <center>
        <img src="C:\Users\JuanMa\Desktop\bug.png" width="300" alt="logo"></center>
      </div>

    </header>

    <section class="main">
      <section class="articles">
        <article>
          <h2>Bugatti</h2>
          <p>Automóviles Ettore Bugatti fue un fabricante francés de automóviles de alto rendimiento, fundado en 1909 en la ciudad alemana de Molsheim, Alsacia, por el diseñador industrial de origen italiano Ettore Bugatti. Los autos fueron conocidos por su belleza de diseño y por sus numerosas victorias en la carrera.A finales de la Segunda Guerra Mundial la marca, como otras del sector, conoció dificultades económicas y no pudo recuperar el esplendor alcanzado en los años 1920 y 30 pero su prestigio mantuvo el interés por relanzarla como competidora de Maserati o Alfa Romeo durante los años 1950 y 1960.</p>

        </article>
      </section>
      <aside >
        <h2>Bugatti entre las dos guerras</h2>

        <p>La vocación deportiva de la empresa comenzó a hacerse patente muy pronto, y así, en 1912, el Bugatti Type 13 acaparó los cuatro primeros lugares en el Gran Premio de Brescia.7​ Entre 1927 y 1933, Bugatti fabricó seis unidades de su modelo Type 41 Royale, el automóvil más lujoso de aquella época, una colosal limusina de 6,4 metros de largo propulsada por un motor de 12,7 litros y 300 CV. En 1935, Jean Bugatti presentó el Type 57, considerado un hito en la historia automotriz.8​9​ Otros diseños notables incluyeron al Type 57 Atlantic Coupe10​ de 1936. En 1939 fallecería Jean Bugatti en un accidente mientras probaba un prototipo, despojando a la firma del heredero más cualificado para suceder a su padre al frente de la empresa. Ese mismo año, la Segunda Guerra Mundial provocó el cierre de la fábrica, pues los alemanes la confiscaron después de ocupar territorio francés, obligando a Ettore Bugatti a refugiarse en Italia.11​

 </p>
      </aside>

    </section>

    <footer class="articles">
      <p>Juan David Lopez & Juan Manuel Guerrero
         juandaju@gmail.com
        +57 321 677 8920
        Medellín - Antioquia </p>

    </footer>

  </body>
</html>

<!-- Nombres: Juan David Lopez Lombana - Juan Manuel Guerrero Arteaga -->

<!DOCTYPE html>
<html lang="es" dir="ltr">
  <head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="styleLY.css">
    <title>Citroen</title>
  </head>
  <body>

    <header>
      <div class="logotipo">
        <center>
        <img src="C:\Users\JuanMa\Desktop\citroen.png" width="300" alt="logo"></center>
      </div>

    </header>

    <section class="main">
      <section class="articles">
        <article>
          <h2>Citroen</h2>
          <p>Citroën es un constructor automovilístico de origen francés fundado en el año 1919 por André Citroën. Se trata de uno de los fabricantes históricos en Europa por tener en su trayectoria el desarrollo de modelos y tecnologías que en su momento supusieron un importante hito en la industria del automóvil. Tanto en el pasado como en su historia reciente, Citroën siempre se ha caracterizado por ser una firma de espíritu vanguardista que destaca entre el resto de fabricantes generalistas en la puesta por conceptos y diseños rompedores o cuanto menos adelantados a su tiempo. </p>

        </article>
      </section>
      <aside >
        <h2>¿A qué grupo pertenece Citroën?</h2>

        <p>El fabricante Citroën pertenece al grupo francés PSA desde el año 1976. Este grupo es en la actualidad el segundo más importante del sector automovilístico en Europa teniendo entre sus firmas más destacadas las ya citadas Peugeot y Citroën, además de DS y la recientemente adquirida Opel que hasta ahora formaba parte de General Motors. PSA cuenta con importantes colaboraciones en el uso compartido de plataformas y mecánicas con otros fabricantes, siendo recientes los acuerdos con Ford para el desarrollo de mecánicas diésel (ya cesado), con Mitsubishi para la fabricación de los primeros modelos eléctricos de Peugeot y Citroën y vehículos todocamino (todavía vigente) o con Opel para la fabricación de vehículos comerciales y SUV (el más reciente). La reciente adquisición de Opel por parte de PSA forma parte de una estrategia de crecimiento y mejora de la competitividad en mercados clave para el grupo como Europa y Asia, siendo además España uno de los motores del grupo en materia de fabricación de vehículos con 3 factorías asentadas en nuestro país: Vigo, Villaverde y Figueruelas.

 </p>
      </aside>

    </section>

    <footer class="articles">
      <p>Juan David Lopez & Juan Manuel Guerrero
         juandaju@gmail.com
        +57 321 677 8920
        Medellín - Antioquia </p>

    </footer>

  </body>
</html>



