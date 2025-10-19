# Doctorado en Ciencias e Investigación Estadística  

[Doctorado en Ciencias e Ingeniería Estadística – 2do. Ciclo](https://alamg-phd.github.io/AcademicTools/PHD%20-%20Antonio%20Lam%20-%202do%20Ciclo.html)

***

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Abrir Link en Nueva Pestaña</title>
</head>
<body>

    <h1>Ejemplo de Apertura de Enlace</h1>

    <button id="abrir-link-btn">Abrir PDF Antonio Lam</button>

    <script>
        // La URL que quieres abrir
        const url_destino = "https://alamg-phd.github.io/AcademicTools/PHD%20-%20Antonio%20Lam%20-%202do%20Ciclo.html";

        /**
         * Función para abrir la URL en una nueva pestaña/ventana.
         * window.open(url) abrirá la URL.
         * Si se llama desde un evento de clic (iniciada por el usuario), 
         * los navegadores modernos lo suelen abrir en una nueva pestaña.
         */
        function abrirLinkEnNuevaPestana(url) {
            // El primer parámetro es la URL. El segundo (opcional) es el nombre de la ventana.
            // Al omitir el segundo parámetro, o no usar '_blank', el navegador decide, 
            // pero si es iniciado por el usuario, casi siempre será una nueva pestaña.
            window.open(url); 
            
            // Opcional: El navegador podría interpretar una cadena vacía ""
            // o un nombre de ventana único como una solicitud para una nueva pestaña.
            // window.open(url, "nuevaVentanaUnica");
        }

        // Obtener el elemento botón
        const boton = document.getElementById('abrir-link-btn');

        // Asignar el evento 'click' al botón
        boton.addEventListener('click', () => {
            abrirLinkEnNuevaPestana(url_destino);
        });
    </script>

</body>
</html>

***


<a href="https://alamg-phd.github.io/AcademicTools/PHD%20-%20Antonio%20Lam%20-%202do%20Ciclo.html" target="_blank">
Doctorado en Ciencias e Ingeniería Estadística – 2do. Ciclo
</a>


<br>

<div style="
  border: 3px solid #007ACC;
  border-radius: 20px;
  background-color: #E6F0FF;
  padding: 20px;
  margin: 20px auto;
  max-width: 90%;
  box-sizing: border-box;
  display: block;
  word-wrap: break-word;
  overflow-wrap: break-word;
  overflow: hidden; /* Oculta cualquier contenido que desborde */
">

<b style="color:#004080;">

### Programa de Doctorado en Ciencias e Investigación Estadística  

El DCIES está diseñado para docentes universitarios y científicos o profesionales investigadores en ciencia y tecnología. El estudiante de este programa doctoral profundizará su estudio en fundamentos de la teoría estadística, probabilidad o aprendizaje de máquina mediante el desarrollo de investigaciones científicas en diversas áreas del conocimiento de la ingeniería y tecnología.  

### LÍNEAS DE INVESTIGACIÓN  

- Metodología estadística
- Modelos estadísticos espacio temporal
- Modelos geoespaciales
- Series de tiempo
- Análisis latente
- Aprendizaje de máquina
- Diseño experimental y muestreo
- Otras propuestas por el doctorado y su asesor.

### Referencias  

Durrett, R. (2019). Probability: Theory and Examples Cambridge University Press.   
Resnick, S. I. (2013). A Probability Path. Birkhäuser.   
Kallenberg, O. (2021). Springer.    
Shiryaev, A. N. (2016).Probability-1 (3.ª ed.).  

### Afiche DCIES - 2025-I  

</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/alamg-phd/AcademicTools/main/afiche_doctorado_20205.jpg" 
       alt="Afiche Doctorado 2025" 
       width="500" />
</div>

<br> 
<br>
<b>Antonio Lam</b></p>
