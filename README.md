# Charla para el Flisol 2015 sobre Firefox
Este es el documento base para usar en la charla general sobre Firefox en el Flisol. También puede usarse para tener un conocimiento general básico sobre los temas a tratar si es que estamos en un stand con nuestra máquina.

La presentación usa el sistema [Revealjs](https://github.com/hakimel/reveal.js/). En el readme de este proyecto pueden ver la forma de controlarlo y modificarlo. El concepto más básico de Reveal es que cada slide/diapositiva está marcada en dentro del código con una etiqueta `<section>`.

#Modo de uso
Clonen el repositorio o descarguen el zip y descomprímanlo en una carpeta. Abran el archivo flisol2015.html en su editor de HTML favorito (si no tienen ninguno favorito, lo pueden abrir con el editor de texto más simple con el que cuenten) y editen la primera parte, donde encuentren este código:

```
<section>
    <h1>Firefox, presente y futuro</h1>
		<h3>Flisol</h3>
		<p>
		  <small>Tu nombre - link a redes sociales </small>
        </p>
</section>
```

Agreguen sus datos personales y si quieren pueden cambiarle el título. 

Cuando tengan que mostrar la presentación, abran el archivo flisol2015.html en Firefox (recomiendo usar la versión "estable", no Beta o Nightly) y podrán pasar de slide/diapositiva con las teclas del cursor.

#Detalles
Verán que además de cada slide/diapositva, la mayoría de las `<section>` contienen una etiqueta `<aside>` con una serie de items. Estos están puestos para que tengan una base sobre qué hablar en cada slide/diapositiva. Al mismo tiempo, el sistema revealjs permite que si mientras tienen abierta la presentación en el navegador presionan la tecla `s` y se abrirá una ventana que les permitirá tener un mejor control de la presentación y les mostrará estos ítems como notas.
