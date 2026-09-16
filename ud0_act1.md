Lenguaje de marcas y sistemas de gestión de la información

1. Crea un archivo de texto llamado textos.txt:
<h1>Texto grande</h1>
<h3>Texto pequeño</h3>
Ábrelo con un navegador. Cámbialo de nombre por textos.html. Vuélvelo a abrir con el navegador.
Lo que ocurre es que el navegador interpreta la extensión .txt como texto plano (muestra literalmente las etiquetas), mientras que en .html el navegador interpreta las etiquetas y mostrara el texto h1 mas y h3 lo contrario.

2. Observa el siguiente fragmento de un texto:
<dam>
  <modulo><titulo>Lenguaje de Marcas</titulo>
    <contenido>
      <unidad>Introducción</unidad>
      <unidad>HTML</unidad>
      <unidad>CSS</unidad>
    </contenido>
  </modulo>

  <modulo>
    <titulo>Sistemas informáticos</titulo>
      <contenido>
        <unidad>Evolución histórica</unidad>
        <unidad>Arquitecturas informáticos</unidad>
        <unidad>Diseño de la CPU</unidad>
      </contenido>
  </modulo>

  <modulo>
    <titulo>Bases de Datos</titulo>
      <contenido>
        <unidad>Sistemas de Almacenamiento de la Información</unidad>
        <unidad>Modelo E-R</unidad>
        <unidad>Dominios</unidad>
      </contenido>
  </modulo>

  <modulo>
    <titulo>Programación</titulo>
      <contenido>
        <unidad>Introducción a la Programación</unidad>
        <unidad>Problemas, algoritmos y programas</unidad>
        <unidad>Conceptos en programación</unidad>
      </contenido>
  </modulo>

  <modulo>
    <titulo>Entornos de Desarrollo</titulo>
      <contenido>
        <unidad>Reconocimiento del Desarrollo de Elementos de Software</unidad>
        <unidad>Lenguajes de Programación</unidad>
        <unidad>Tipos de Lenguajes de Programación</unidad>
      </contenido>
  </modulo>

</dam>

3. Crea tu propio documento SGML indicando vocabulario y reglas. Implementa los
datos para PAISES DEL MUNDO.

<mundo>
  <region occidental>
    <país>
      <nombre>Estados Unidos</nombre>
      <capital>Washington D. C.</capital>
      <sistema>Capitalista</sistema>
    </país>
    <país>
      <nombre>Alemania</nombre>
      <capital>Berlín</capital>
      <sistema>Capitalista</sistema>
    </país>
  </region occidental>
  <region oriental>
    <país>
      <nombre>China</nombre>
      <capital>Pekín</capital>
      <sistema>Socialista</sistema>
    </país>
    <país>
      <nombre>Corea del Norte</nombre>
      <capital>Pionyang</capital>
      <sistema>Comunista</sistema>
    </país>
  </region oriental>
</mundo>

Vocabulario: mundo, región (occidental u oriental), país, nombre, capital, sistema.
Reglas: mundo tiene varias regiones, cada región contiene varios países, cada país tiene un nombre, capital y sistema.

4. Modifica con un lenguaje de marcas la siguiente información para darle estructura
y significado semántico al documento. Indica vocabulario y reglas.

<inventario>
  <libro>
    <titulo>FALCO</titulo>
    <autor>ARTURO PEREZ REVERTE</autor>
    <isbn>9788420419688</isbn>
    <páginas>296 págs</páginas>
    <editor>ALFAGUARA</editor>
    <idioma>CASTELLÀ</idioma>
  </libro>
  <libro>
    <titulo>TODO ALATRISTE</titulo>
    <isbn>9788420425528</isbn>
    <autor>ARTURO PEREZ REVERTE</autor>
    <editor>ALFAGUARA</editor>
    <idioma>CASTELLÀ</idioma>
  </libro>
  <libro>
    <titulo>HOMBRES BUENOS<titulo>
    <isbn>9788466329804</isbn>
    <autor>ARTURO PEREZ REVERTE</autor>
    <editor>PUNTO DE LECTURA</editor>
    <año>2024</año>
    <descripción>La heróica aventura de quienes se atrevieron a cambiar el mundo con libros. En tiempos de oscuridad siempre hubo hombres buenos que lucharon para llevar las luces y el progreso. Y otros que procuraron impedirlo.</descripción>
  </libro>
</inventario>

Vocabulario: inventario, libro, título, autor, isbn, páginas, editor, idioma, año, descripción.
Reglas: Inventario tiene libros, cada libro tiene su titulo, autor, isbn, editor, y pueden tener, idioma correspondiente, cantidad de páginas, año o descripción.
