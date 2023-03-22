# ProyectosVS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css" integrity="sha512-SzlrxWUlpfuzQ+pcUCosxcglQRNAq/DZjVsC0lE40xsADsfeQoEypE+enwcOiGjk/bSuGGKHEyjSoQ1zVisanQ==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>PORTAFOLIO</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="contenedor-header">
        <header>
            <div class="logo">
                <a href="#">LINA</a>
            </div>
            <nav id="nav">
                <ul>
                    <li><a href="#inicio" onclick="seleccionar()">INICIO</a></li>
                    <li><a href="#sobremi" onclick="seleccionar()">SOBRE MI</a></li>
                    <li><a href="#skills" onclick="seleccionar()">SKILLS</a></li>
                    <li><a href="#curriculum" onclick="seleccionar()">CURRICULUM</a></li>
                    <li><a href="#portafolio" onclick="seleccionar()">PORTAFOLIO</a></li>
                    <li><a href="#contacto" onclick="seleccionar()">CONTACTO</a></li>
                </ul>
            </nav>

            <div class="nav-responsive" onclick="MostrarOcultarMenu()">
                <i class="fa-solid fa-bars-staggered"></i>
            </div>
        </header>
    </div>

    <!--  S E C C I ON     I N I C I O  -->

    <section id="inicio" class="inicio">
        <div class="contenido-banner">
                <div class="contenedor-img">
                    <img src="images/hero.jpg">
                </div>
                <h1>LINA BEDOYA</h1>
                <h2>Ingeniera de Software - Experta en Diseño Web</h2>
                <div class="redes">
                    <a href="#"><i class="fa-brands fa-facebook"></i></a>
                    <a href="#"><i class="fa-brands fa-linkedin"></i></a>
                    <a href="#"><i class="fa-brands fa-twitter"></i></a>
                    <a href="#"><i class="fa-brands fa-skype"></i></a>
                    <a href="#"><i class="fa-solid fa-rss"></i></a> 
                </div>
        </div>
    </section>
     <!--    S E C C I O N   S O B R E M I  -->

    <section id="sobremi" class="sobremi">
        <div class="contenido-seccion">
            <h2>SOBRE MÍ</h2>
            <p><span>Hola, soy Lina Bedoya</span>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Numquam animi rem eius vero temporibus facere sequi amet nostrum aliquid ratione hic corrupti aut,
            obcaecati, distinctio sed eaque voluptatum magnam delectus.</p>

            <div class="fila">
                <div class="col">
                    <h3>Datos Personales</h3>
                    <ul>
                        <li>
                            <strong>Cumpleaños</strong>
                            07-05-2002
                        </li>
                        <li>
                            <strong>Telefono</strong>
                            3132874902
                        </li>
                        <li>
                            <strong>E-mail</strong>
                            cw@example.com
                        </li>
                        <li>
                            <strong>Website</strong>
                            www.example.com
                        </li>
                        <li>
                            <strong>Dirección</strong>
                            123 Cali, Colombia
                        </li>
                        <li>
                            <strong>Cargo</strong>
                            <span>FREELANCE</span>
                        </li>
                    </ul>
                </div>

                <div class="col">
                    <h3>Intereses</h3>
                    <div class="contenedor-intereses">
                        <div class="interes">
                            <i class="fa-solid fa-computer"></i>
                            <span>PROGRAMAR</span>
                        </div>
                        <div class="interes">
                            <i class="fa-brands fa-youtube"></i>
                            <span>VIDEOS</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-headphones-simple"></i>
                            <span>MUSICA</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-ticket"></i>
                            <span>PELICULAS</span>
                        </div>
                    </div>
                </div>
            </div>
            <button>
                Descargar CV <i class="fa-solid fa-cloud-arrow-down"></i>
                <span class="overlay"></span>
            </button>
        </div>
    </section>

 <!--    S E C C I O N     S K I L L S  -->

    <section id="skills" class="skills">
        <div class="contenido-seccion">
            <h2>SKILLS</h2>
            <div class="fila">
                <div class="col">
                    <h3>Technical Skills</h3>
                    <div class="skill">
                        <span>javascript</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>75%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>HTML & CSS</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>80%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Photoshop</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>95%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Wordpress</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>81%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Drupal</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>55%</span>
                            </div>
                        </div>
                    </div>
                </div>
                <!--PROFESSIONAL SKILLS-->
                <div class="col">
                    <h3>Professional Skills</h3>
                    <div class="skill">
                        <span>Comunicación</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>80%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Trabajo en Equipo</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>70%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Creatividad</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>50%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Dedicación</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>65%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Proyect Management</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>90%</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

<!--    S E C C I O N    C U R R I C U L U M  -->

    <section id="curriculum" class="curriculum">
       <div class="contenido-seccion">
        <h2>CURRICULUM</h2>
        <div class="fila">
            <div class="col izquierda">
                <h3>Educacion</h3>
                <div class="item izq">
                    <h4>Arte y Multimedia</h4>
                    <span class="casa">Universidad del Valle</span>
                    <span class="fecha">2019 - 2022</span>
                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dolores maxime itaque assumenda expedita voluptas 
                       provident reiciendis excepturi consectetur earum eos nam porro, veniam tenetur reprehenderit accusantium quod 
                       illum? Itaque, fugiat!</p>
                    <div class="conectori">
                        <div class="circuloi"></div>
                    </div>
                </div>
            </div>

            <div class="col derecha">
                <h3>Experiencia de Trabajo</h3>
                <div class="item der">
                    <h4>Front Developer</h4>
                    <span class="casa">Nombre de la Compañía</span>
                    <span class="fecha">2019 - 2022</span>
                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dolores maxime itaque assumenda expedita voluptas 
                       provident reiciendis excepturi consectetur earum eos nam porro, veniam tenetur reprehenderit accusantium quod 
                       illum? Itaque, fugiat!</p>
                    <div class="conectord">
                        <div class="circulod"></div>
                    </div>
                </div>
            </div>
            <div class="col derecha">
                <h3>Educación</h3>
                <div class="item der">
                    <h4>Arte y Multimedia</h4>
                    <span class="casa">Universidad del Valle</span>
                    <span class="fecha">2019 - 2022</span>
                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dolores maxime itaque assumenda expedita voluptas 
                       provident reiciendis excepturi consectetur earum eos nam porro, veniam tenetur reprehenderit accusantium quod 
                       illum? Itaque, fugiat!</p>
                    <div class="conectord">
                        <div class="circulod"></div>
                    </div>
                </div>
            </div>
            <div class="col derecha">
                <h3>Experiencia de Trabajo</h3>
                <div class="item der">
                    <h4>Front Developer</h4>
                    <span class="casa">Nombre de la Compañía</span>
                    <span class="fecha">2019 - 2022</span>
                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dolores maxime itaque assumenda expedita voluptas 
                       provident reiciendis excepturi consectetur earum eos nam porro, veniam tenetur reprehenderit accusantium quod 
                       illum? Itaque, fugiat!</p>
                    <div class="conectord">
                        <div class="circulod"></div>
                    </div>
                </div>
            </div>
        </div>
       </div> 
    </section>

<!--    S E C C I O N     P O R T A F O L I O   -->

    <section id="portafolio" class="portafolio">
        <div class="contenido-seccion">
            <h2>PORTAFOLIO</h2>
            <div class="galeria">
                <div class="proyecto">
                    <img src="images/p1.jpg">
                    <div class="overlay">
                        <h3>Diseño Creativo</h3>
                        <p>Fotografía</p>
                    </div>
                </div>
                <div class="proyecto">
                    <img src="images/p2.jpg">
                    <div class="overlay">
                        <h3>Diseño Creativo</h3>
                        <p>Fotografía</p>
                    </div>
                </div>
                <div class="proyecto">
                    <img src="images/p3.jpg">
                    <div class="overlay">
                        <h3>Diseño Creativo</h3>
                        <p>Fotografía</p>
                    </div>
                </div>
                <div class="proyecto">
                    <img src="images/p4.jpg">
                    <div class="overlay">
                        <h3>Diseño Creativo</h3>
                        <p>Fotografía</p>
                    </div>
                </div>
                <div class="proyecto">
                    <img src="images/p5.jpg">
                    <div class="overlay">
                        <h3>Diseño Creativo</h3>
                        <p>Fotografía</p>
                    </div>
                </div>
                <div class="proyecto">
                    <img src="images/p6.jpg">
                    <div class="overlay">
                        <h3>Diseño Creativo</h3>
                        <p>Fotografía</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

<!--     S E C C I O N     C O N T A C T O        -->

    <section id="contacto" class="contacto">
        <div class="contenido-seccion">
            <h2>CONTACTO</h2>
            <div class="fila">
                <!--formulario-->
                <div class="col">
                    <input type="text" placeholder="Tu Nombre">
                    <input type="text" placeholder="Número Telefónico">
                    <input type="text" placeholder="Correo Electrónico">
                    <input type="text" placeholder="Tema">
                    <textarea name="" id="" cols="30" rows="10" placeholder="Mensaje"></textarea>
                    <button>
                        Enviar Mensaje <i class="fa-sharp fa-solid fa-paper-plane"></i>
                        <span class="overlay"></span>
                    </button>
                </div>
                <!--MAPA-->
                <div class="col">
                    <img src="images/ubicacion.png">
                    <div class="info">
                        <ul>
                            <li>
                                <i class="fa-sharp fa-solid fa-location-dot"></i>
                                Colombia 123 Puertas del Sol
                            </li>
                            <li>
                                <i class="fa-solid fa-mobile"></i>
                                Llamanos al: 3207653891
                            </li>
                            <li>
                                <i class="fa-solid fa-envelope-circle-check"></i>
                                Email: Lb@example.com
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!--   S E C C I O N     F O O T E R    -->

    <footer>
        <a href="#inicio" class="arriba">
            <i class="fa-solid fa-angles-up"></i>
        </a>
        <div class="redes">
            <a href="#"><i class="fa-brands fa-facebook"></i></a>
            <a href="#"><i class="fa-brands fa-linkedin"></i></a>
            <a href="#"><i class="fa-brands fa-twitter"></i></a>
            <a href="#"><i class="fa-brands fa-skype"></i></a>
            <a href="#"><i class="fa-solid fa-rss"></i></a> 
        </div>

    </footer>

    <script src="script.js"></script>
</body>
</html>
