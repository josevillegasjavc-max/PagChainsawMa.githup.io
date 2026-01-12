<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Chainsaw Man Fans</title>

         <style>
            :root {
                --naranja:    #ef4f2a;
                --verde-neon: #39FF14;
                --amarillo:   #efdb2a;
                --oscuro:     #1a1a1a;
                --gris-fondo: #2d2d2d;
            }

            body {
                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                background-color: var(--gris-fondo);
                color: aliceblue;
                margin: 0;
            }

            .Base {
                border-bottom: 5px double var(--naranja);
                background-color: var(--oscuro);
                text-align: center;
                padding: 20px;
            }

            h1 img {
                max-width: 100%;
                filter: drop-shadow(0 0 10px rgba(209, 47, 14, 0.833));
            }

            .Enlace ul {
                display: flex;
                list-style: none;
                gap: 22px;
                justify-content: center;
                margin-top: 15px;
            }

            .Enlace a {
                color: var(--amarillo);
                font-weight:bold;
                text-decoration:none;
                font-size: 16px;
                transition: 0.3s;
            }
            
            .Enlace a:hover{
                color: var(--verde-neon);
                text-shadow: 0 0 8px var(--amarillo);    
            }

            main {
                max-width: 1000px;
                margin: 50px auto;
            }

            section {
                background-color: var(--oscuro);
                border: 4px solid #444;
                border-radius: 12px;
                padding: 20px;
                margin-bottom: 40px;
                box-shadow: 10px 10px 0 rgba(0, 0, 0, 0.112);
            }

            section h2 {
                background-color: var(--verde-neon);
                border: 2px solid var(--gris-fondo);
                color: var(--oscuro);
                display: inline-block;
                padding: 5px 20px;
                transform: skewX(-10deg);
                margin-bottom: 16px;
                border-radius: 5px;
            }
            
            .imagen {
                display: flex;
                justify-content: center;
                gap: 45px;
                margin-top: 40px;
            }

            .imagen img {
                border: 4px solid var(--amarillo); 
                border-radius: 14px;
                padding: 0;
                box-shadow: 8px 8px 0 rgba(0,0,0,0.2);
                width: 200px;
                height: 300px;
                display: block;
            }
            
            article {
                border-left: 5px solid var(--verde-neon);
                background: linear-gradient(90deg, #2b2e2be2 0%, #1a1a1a 100%);
                margin: 15px auto;
                padding: 10px;
                border-radius: 5px 15px 15px 5px;
                transition: transform 0.3s;
            }

            article h3 {
                margin: 0;
                color: var(--verde-neon);
            }

            article:hover {
                border-left-color: var(--amarillo);
                transform: translate(10px);
                color: var(--amarillo);
            }

            article:hover h3{
                color: var(--amarillo);
            }

            .tables {
                border-radius: 10px; 
                border: 5px double var(--amarillo);
                overflow: auto;
                margin: 12px auto;
            }

            table {
                width: 100%;
                border-collapse: collapse;
                background-color: #222;
            }
            
            th {
                background-color: var(--amarillo);
                color: black;
                padding: 15px;
            }

            td {
                text-align: center;
                padding: 12px;
                border-bottom: 1px solid #333;
            }

            td img{
                width: 117px;
                height: 165px;
                border: 3px solid var(--amarillo);
                border-radius: 14px;
                box-shadow: 8px 8px 0 rgba(0,0,0,0.2);
                transition: 0.3s;
            }

            td img:hover{
                cursor: pointer;
                border-color: var(--verde-neon);
                transform: translate(4px);
            }
            
            .nick {
                color: var(--amarillo);
            }
            
            tr:hover {
                color: var(--verde-neon);
                transition: 0.5s;
                background-color: #333;
            }

            .boton  {
                font-weight: bold;
                display: flex;
                justify-content: center;
                gap: 100px;  
            }

            .boton a {
                background-color: var(--naranja);
                color: whitesmoke;
                text-decoration: none;
                padding: 10px 60px;
                margin-top: 20px;
                border: 4px solid var(--amarillo);
                border-radius: 10px;
                transition: 0.2s;
            }

            .boton a:hover {
                background-color: var(--verde-neon);
                color: black;
                border: 4px solid black;
                filter: drop-shadow(0 0 10px rgba(55, 226, 8, 0.833));
            }

            aside {
                background-color: #3d3d3d;
                border: 4px solid var(--oscuro);
                border-radius: 12px;
                padding: 10px;
                margin-bottom: 40px;
                box-shadow: 10px 10px 0 rgba(0,0,0,0.2);
            }

            aside h2 {
                background-color: var(--naranja);
                border: 2px solid var(--oscuro);
                color: var(--gris-fondo);
                display: inline-block;
                padding: 5px 20px;
                transform: skewX(-10deg);
                margin-bottom: 16px;
                border-radius: 5px;
            }

            aside b {
                margin: 0;
                font-size: 15px;
                color: var(--naranja);
            }

            .Curiosidades {
                border-left: 5px solid var(--naranja);
                background: linear-gradient(50deg, #1a1a1a 0%, #3d3d3d 100%);
                list-style: none;
                margin: 18px auto;
                padding: 18px 16px;
                border-radius: 5px 15px 15px 5px;
                transition: 0.3s;
            }

            .Curiosidades:hover {
                border-left: 5px solid var(--amarillo);
                color: var(--amarillo);
                transform: translate(5px);
                
            }

            .Curiosidades:hover b {
                color: var(--amarillo);
            }

            .CardContent {
                display: flex;
                gap: 30px;    
                padding: 5px 10px;
                justify-content: center;
            }

            .Card {
                border: 2px solid var(--gris-fondo);
                border-radius: 8px;
                width:  200px;
                height: 300px;
                margin: 10px 10px;
                padding: 10px 12px;
                box-shadow: 2px 8px 4px 0 var(--oscuro);
                transition: 250ms ease-in-out;
                color: transparent;
                background-size: cover;
                font-weight: bold;
            }

            .Card + .Card {
                margin-left: -9%;
            }

            .Card:hover {
                cursor: pointer;
                transform: rotate(-3deg) translateY(-25px);
                border: 2px solid var(--oscuro);
                filter: brightness(0.6);
            }

            .Card:hover .obras{
                transition: 0.4s 0.2s;
                padding: 2px 5px;
                color: var(--naranja);
                background-color: var(--gris-fondo);
                border: 2px solid var(--oscuro);
            }

            .Card:hover ~ .Card {
                z-index: 1;
                translate: 70px;
            }

            .CardContent:has(.Card:hover) .Card:not(:hover):not(.Card:hover ~ .Card) {
                z-index: 0;
                translate: -70px;
            }

            footer {
                margin-top: 50px;
                border-top:5px double var(--naranja) ;
            }
       
            /* --- AJUSTES PARA MÓVadasILES --- */
        @media (max-width: 768px) {
            /* 1. Reducimos el tamaño de la fuente global */
            body {
                font-size: 1rem;
            }

            /* 2. El menú se apila en vertical para que no se amontone */
            .Enlace ul {
                flex-direction: column;
                gap: 10px;
            }

            /* 3. Las imágenes de Pochita y Denji se ponen una debajo de otra */
            .imagen {
                flex-direction: column;
                align-items: center;
                gap: 20px;
            }

            /* 4. Los botones de abajo se ajustan para que no se salgan */
            .boton {
                flex-direction: column;
                gap: 15px;
                align-items: center;
            }

            .boton a {
                width: 80%; /* Botones más anchos para tocar con el dedo */
                padding: 12px 0;
                text-align: center;
            }

            /* 5. Ajuste de la tabla para que se pueda leer bien */
            td img {
                width: 60px; /* Portadas más pequeñas en móvil */
                height: auto;
            }

            section h2 {
                font-size: 1.2rem; /* Títulos un poco más pequeños */
            }
        }
        
         </style>
    </head>
    <body>
        <header class="Base">
            <h1 id="Inicio"><img src="https://upload.wikimedia.org/wikipedia/commons/archive/4/4b/20240312075921%21Chainsaw_Man_logo.png" alt="20240312075921%21Chainsaw Man logo"></h1>
                <nav class="Enlace">
                    <ul >
                        <li><a href="#Definicion">¿QUIEN ES?</a></li>
                        <li><a href="#Caracteristicas">CARACTERÍSTICAS</a></li>
                        <li><a href="#Personajes">PERSONAJES</a></li>
                        <li><a href="#Datos">DATOS CURIOSOS</a></li>
                        <li><a href="#Contacto">CONTACTANOS</a></li>
                    </ul>
                </nav>
        </header>
        <main>
            <section id="Definicion">
                <h2>¿QUIÉN ES EL CHAINSAW MAN?</h2>
                    <p>
                        Chainsaw Man tambien conocido como el pibe motosierra es el alias de Denji, un joven 
                        y pobre cazador de demonios que, tras fusionarse con su compañero demoníaco, Pochita 
                        (el Demonio Motosierra), obtiene la habilidad de transformar partes de su cuerpo en 
                        sierras mecánicas, convirtiéndose en un híbrido humano-demonio para luchar contra
                        otras criaturas demoníacas mientras busca una vida normal.
                    </p>
                    <figure class="imagen">
                        <img  src="https://upload.wikimedia.org/wikipedia/en/2/24/Chainsawman.jpg?20190915132521" alt="chainsawman">
                        <img  src="https://fbi.cults3d.com/uploaders/23833535/illustration-file/9812e779-d886-46ac-a0c8-365b88ebbce1/pochita.jpg" alt="pochita">
                    </figure>
            </section>
            <section id="Caracteristicas">
                <h2>CARACTERÍSTICAS DEL CHAINSAW MAN</h2>
                    <article>
                        <h3>Personalidad</h3>
                        <p>Simple, intrépido, leal a sus deseos, carente de sentido común, pero con gran empatía a pesar de su grosería.</p>
                    </article>
                    <article>
                        <h3>Habilidades de Combate</h3>
                        <p>Posee sierras en sus brazos y cabeza, regeneración casi instantánea y una velocidad considerable, lo que lo hace extremadamente peligroso.</p>
                    </article>
                    <article>
                        <h3>Motivación</h3>
                        <p>Anhela una vida normal (comida, un hogar, una novia) y lucha por mantenerla, no por ideales elevados.</p>
                    </article>
                    <article>
                        <h3>Apariencia</h3>
                        <p>En su forma híbrida, tiene sierras en brazos y cabeza, pelo rubio y aspecto demoníaco.</p>
                    </article>
            </section>
            <section id="Personajes">
                <h2>ENCICLOPEDIA DE PERSONAJES</h2>
                <div class="tables">
                <table>
                    <thead>
                        <tr>
                            <th>Nombre</th>
                            <th>Edad</th>
                            <th>Especie</th>
                            <th>Contrato/Nombre de Demonio</th>
                            <th>Apariencia</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td class="nick">Denji</td>
                            <td>17</td>
                            <td>Hibrido</td>
                            <td>Demonio Motosierra</td>
                            <td><img src="https://i.redd.it/zj32ygu1oij61.jpg"></td>
                        </tr>
                        <tr>
                            <td class="nick">Power</td>
                            <td>18</td>
                            <td>Humano Demonio</td>
                            <td>Demonio Sangre</td>
                            <td><img src="https://preview.redd.it/5gf9s3wy40u21.jpg?width=640&crop=smart&auto=webp&s=a3bac274c06aa2d926e5ede70f1367b874fa5a76"></td>
                        </tr>
                        <tr>
                            <td class="nick">Aki</td>
                            <td>19</td>
                            <td>Humano</td>
                            <td> Demonio Zorro / Futuro </td>
                            <td><img src="https://i.redd.it/yg0fzsqmv1p31.jpg"></td>
                        </tr>
                        <tr>
                            <td class="nick">Makima</td>
                            <td>25</td>
                            <td>Demonio</td>
                            <td>Demonio Control</td>
                            <td><img src="https://external-preview.redd.it/H8THyuV8QW0Syb0I6EYvY17VovSRgrxSyGd9kRRAMF4.jpg?width=640&crop=smart&auto=webp&s=b127813ad3c5d49b19d82da91da8007191ac85ad"></td>
                        </tr>
                    </tbody>
                </table>
                </div>
                <div class="boton">
                    <a target="_blank" href="https://es.wikipedia.org/wiki/Chainsaw_Man">LEER WIKI</a>
                    <a target="_blank" href="https://www.youtube.com/watch?v=tIGUiyxx384">VER VIDEO</a>
                </div>
            </section>
        <aside id="Datos">
            <h2 class="DatCur">Datos sobre el autor y la creación</h2>
                <ul>
                    <li class="Curiosidades"><b>Inspiraciones cinematográficas:</b> El autor, Tatsuki Fujimoto, se inspira mucho en el cine, incluyendo The Texas Chainsaw Massacre y películas de terror.</li> 
                    <li class="Curiosidades"><b>El autor es excéntrico:</b> Fujimoto es tan peculiar como sus personajes, y le encanta escribir a Power.</li> 
                    <li class="Curiosidades"><b>Fan de las motosierras: </b>Su fascinación por las motosierras va más allá de la serie.</li> 
                </ul>
        </aside>
        <aside>
            <h2>Otras obras de Tatsuki Fujimoto</h2>
            <ul class="CardContent">
               <li class="Card" style="background-image: url(https://images.cdn1.buscalibre.com/fit-in/360x360/75/6e/756ed64cb21d1fab98e311b987f2bd9f.jpg); z-index: 1;"><span class="obras">Look Back</span></li>
               <li class="Card" style="background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTEKgyi4gIs1-zzfRAHNi59vEVYnus2-O_DDg&s); z-index: 2"><span class="obras">Fire Punch</span></li>
               <li class="Card" style="background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQC1WEb5PXrQNEKVKCST0js2WwyalZFbPQ4Dw&s); z-index: 3"><span class="obras">Goodbye, Eri</span></li>
               <li class="Card" style="background-image: url(https://i0.wp.com/codigoespagueti.com/wp-content/uploads/2023/02/Chainsaw-Man-En-que-se-inspiro-Tatsuki-Fujimoto-para-crear-a-Makima-min-2.jpg?resize=892%2C1300&ssl=1); z-index: 4"><span class="obras">Yogen no Nayuta</span></li>
            </ul>
        </aside>
    </main>    
    <footer class="Base">
        <p>Copyright 2025</p>
        <p id="Contacto">Contactanos con:</p>
        <p><a style="color: var(--verde-neon);" href="mailto:ChainsawManFan@gmail.com">ChainsawManFan@gmail.com</a></p>
        <p class="Enlace"><a href="#Inicio">VOLVER AL INICIO</a></p>
    </footer>  
    </body>
</html>
