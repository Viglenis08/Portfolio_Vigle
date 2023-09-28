<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Viglenis Brito</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Lato:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <nav class="nav-container">
            <img class="logo" src="img/logo.jpg"  alt ="Logo">
            <button class="open-menu">
                <img src="img/Hamburger_icon.svg_.png" alt="abrir menu">
            </button>
            <ul class="menu-container" >
                <button class="close-menu">
                    <img src="img/cerrar.png" alt="cerrar menu">
                </button>
                <li class="menu-item"><a href="#perfil" class="active">Perfil</a></li>
                <li class="menu-item"><a href="#habilidades">Habilidades</a></li>
                <li class="menu-item"><a href="#resumen">Experiencia</a></li>
                <li class="menu-item"><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="perfil" class="perfil-container">
            <img src="img/vigle.png" alt="img-perfil">
            <ul class="perfil-text">
                <li>
                    <h1>Hola! Soy Viglenis</h1>
                </li>
                <li>
                    <p>Graduada de una Tecnicatura en Informática, y actualmente estudiando 3er año de Análisis de Sistemas. <br/>
                        Con amplia experiencia en el área de administración tanto en Venezuela como en Argentina
                    </p>
                    <p>
                        Realizando actualmente un curso de Front-End del proyecto Código Latam y Eidos-Global"
                    </p>
                </li>
                <li>
                    <button>
                        <a class="project-details-button download-cv" href="CvInf Viglenis Brito.pdf"><b>Download CV</b></a>
                    </button>
                </li>
            </ul>  
        </section>

        <section class="habilidades" id="habilidades">
            <div class="contenido-seccion">
                <h2 class="titulo-seccion">Mis habilidades</h2>
                
                <div class="fila">
                    <div class="col">
                        <span><b>HTML/CSS</b></span>
                        <div class="cont-barra">
                            <div class="barra" id="html">
                                <!-- mediante javascript luego genereremos 17 barritas con clase e -->
                                
                            </div>
                            <span><b>80%</b></span>
                        </div>
                    </div>
                    <div class="col">
                        <span><b>JAVASCRIPT</b></span>
                        <div class="cont-barra">
                            <div class="barra" id="javascript">
                                <!-- mediante javascript luego genereremos 17 barritas con clase e -->
                               
                            </div>
                            <span><b>70%</b></span>
                        </div>
                    </div>
                </div>
                <div class="fila">
                    <div class="col">
                        <span><b>POWER BI</b></span>
                        <div class="cont-barra">
                            <div class="barra" id="power_bi">
                                <!-- mediante javascript luego genereremos 17 barritas con clase e -->
                               
                            </div>
                            <span><b>90%</b></span>
                        </div>
                    </div>
                    <div class="col">
                        <span><b>PYTHON</b></span>
                        <div class="cont-barra">
                            <div class="barra" id="leng_pyhton">
                                <!-- mediante javascript luego genereremos 17 barritas con clase e -->
                            </div>
                            <span><b>60%</b></span>
                        </div>
                    </div>
                </div>
                <div class="fila">
                    <div class="col">
                        <span><b>PHP</b></span>
                        <div class="cont-barra">
                            <div class="barra" id="php">
                                <!-- mediante javascript luego genereremos 17 barritas con clase e -->
                               
                            </div>
                            <span><b>70%</b></span>
                        </div>
                    </div>
                    <div class="col">
                        <span><b>BASE DE DATOS</b></span>
                        <div class="cont-barra">
                            <div class="barra" id="base_de_dato">
                                <!-- mediante javascript luego genereremos 17 barritas con clase e -->
                               
                            </div>
                            <span><b>80%</b></span>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    
    <!-- SECCION RESUMEN -->
    <section class="resumen" id="resumen">
        <div class="contenido-seccion">
            <h2 class="titulo-seccion">Resumen</h2>
            <h3>Mi preparación y experiencia</h3>
            <div class="info">
                <div class="col">
                    <span class="titulo">Educación</span>
                    <table>
                        <tr>
                            <td class="datos">
                                <h3>2021 - 2023</h3>
                            </td>
                            <td rowspan="2" class="descripcion">
                                Analizar e interpretar las necesidades operativas, de información o de servicios de las organizaciones en lo referente a sus requerimientos informático.
                                Asesorar en la elección y/o adquisición de software existente en el mercado, actuando bajo las normativas vigentes.
                                Diseñar y desarrollar sistemas informáticos.
                                Realizar procesos de implementación de sistemas informáticos y su consiguiente adaptación a los actuales procesos administrativos.
                            </td>
                        </tr>
                        <tr>
                            <td>
                                <h4>Técnico Superior en Análisis de Sistemas</h4>
                                <p>Instituto de Formación Técnica Nro. 19</p>
                                <span class="pais">Argentina</span>
                            </td>
                        </tr>
                    </table>
                    <table>
                        <tr>
                            <td class="datos">
                                <h3>2007 - 2011</h3>
                            </td>
                            <td rowspan="2" class="descripcion">
                                Programación, administración, sistemas, bases de datos, contabilidad y computación.
                                Software de uso más generalizado en las plataformas de mayor utilización.
                                Mantenimiento de Sistemas de Información en el ámbito técnico.
                            </td>
                        </tr>
                        <tr>
                            <td>
                                <h4>Técnico Superior Universitario en Informatica</h4>
                                <p>Universidad Politecnica Territorial Cecilio Acosta</p>
                                <span class="pais">Venezuela</span>
                            </td>
                        </tr>
                    </table>
                    <table>
                        <tr>
                            <td class="datos">
                                <h3>2002 - 2004</h3>
                            </td>
                            <td rowspan="2" class="descripcion">
                                Registro de las operaciones contables de la organización.
                                Calcular costos de producción e impuestos.
                                Controlar registros de operaciones de caja.
                                Analizar e interpretar la información financiera de la organización.
                            </td>
                        </tr>
                        <tr>
                            <td>
                                <h4>Técnico Medio Mercantil en Contabilidad</h4>
                                <p>Escuela Tecnica Don Bosco</p>
                                <span class="pais">Venezuela</span>
                            </td>
                        </tr>
                    </table>

                </div>
                <div class="col">
                    <span class="titulo">Experiencia Laboral</span>
                    <table>
                        <tr>
                            <td class="datos">
                                <h3>Actualmente</h3>
                            </td>
                            <td rowspan="2" class="descripcion">
                                Manejar los procesos de cotizaciones, negociaciones, acuerdos y gestión del rendimiento y 
                                las relaciones con proveedores aprobados o potenciales. 
                                Generar nuevas opciones de compra que cumplan con los requisitos de la organización y el 
                                manejo de proyectos de compras.Llevar los registros auxiliares de los gastos por cada cuenta de presupuesto.
                            </td>
                        </tr>
                        <tr>
                            <td>
                                <h4>Clinica Basilea</h4>
                                <p>Admiinistrativo de Compras</p>
                               
                            </td>
                        </tr>
                    </table>
                    <table>
                        <tr>
                            <td class="datos">
                                <h3>2022-2023</h3>
                            </td>
                            <td rowspan="2" class="descripcion">
                                Buscar y seleccionar los proveedores más eficientes, con los productos de mejor calidad a un precio competitivo.
                                Supervisar la calidad de los productos o artículos comprados
                                Gestionar los documentos relativos a la compra
                                Control de stock
                            </td>
                        </tr>
                        <tr>
                            <td>
                                <h4>Asesor de Compras</h4>
                                <p>Farmacia República de Barracas</p>
                            </td>
                        </tr>
                    </table>
                    <table>
                        <tr>
                            <td class="datos">
                                <h3>2021-2022</h3>
                            </td>
                            <td rowspan="2" class="descripcion">
                                Implementar y mejorar los procedimientos administrativos, garantizando una eficiente gestión de la documentación, registros y flujos de trabajo.
                                Colaborar en la selección y contratación de personal administrativo, realizar evaluaciones de desempeño, ofrecer capacitación y fomentar un ambiente de trabajo productivo y motivador.
                                
                            </td>
                        </tr>
                        <tr>
                            <td>
                                <h4>Responsable Administrativo</h4>
                                <p>Grupo G24</p>
                            </td>
                        </tr>
                    </table>
                    <table>
                        <tr>
                            <td class="datos">
                                <h3>2011-2018</h3>
                            </td>
                            <td rowspan="2" class="descripcion">
                                Supervisar y coordinar las operaciones diarias de la farmacia, incluyendo la atención al cliente, el inventario de productos, la gestión de personal y la administración de los recursos disponibles.
                                Capacidad para establecer metas claras y trabajar de manera proactiva para lograr resultados positivos y alcanzar los objetivos establecidos.
                                Capacidad para adaptarse rápidamente a los cambios y trabajar en un entorno dinámico y exigente.
                            </td>
                        </tr>
                        <tr>
                            <td>
                                <h4>Sub Gerente</h4>
                                <p>Farmatodo C.A</p>
                            </td>
                        </tr>
                    </table>
                </div>
            </div>
        </div>
    </section>


        <section id="contacto" class="contacto">
                <div class="logo-contacto"><a href="mailto:viglenisbrito@gmail.com" target="_blank"> <img src="img/mail.png" alt="Mail"></a></div>
                <div class="logo-contacto"><a href="https://github.com/Viglenis08" target="_blank"><img src="img/github.png" alt="Github"></a></div>
                <div class="logo-contacto"><a href="https://linkedin.com/in/viglenis-brito-malave" target="_blank"><img src="img/linkedin.png" alt="Linkdln"></a></div>
        </section>
    </main>

    <footer>
        Codigo Latam
    </footer>

<script src="js/main.js"></script>
</body>
</html>
