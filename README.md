<h1>Bootstrap 5 Components Code Snippet</h1>

<h2>
  <a href="https://maxisandoval37.github.io/Bootstrap-Components-Code-Snippet/Index.html">Live demo</a>
</h2>

<h1 align="center">Notas</h1>

<h3>
  <a href="https://getbootstrap.com/docs/5.0/layout/containers/">Contenedores:</a>
</h3>
<ul>
 <li>container: predeterminado</li>
 <li>container-fluid: menos márgenes</li>
 <li>container-{breakpoint}: ancho 100% hasta llegar al breakpoint</li>
</ul>

<h3>Grid:</h3>
<ul>
 <li>El máximo de columnas que tenemos disponibles son 12.</li>
 <li>Podemos distribuir este espacio en los tamaños de las columnas. Ej: col-6 | col-6 (ocuparían la mitad de la pantalla).</li>
</ul>
<img src="https://user-images.githubusercontent.com/68869989/216829993-6c501054-90d2-4e0b-bca0-09a91a6a1ac1.png" alt="grid-1">

<h3>Columnas:</h3>
• Alineación:
<ul>
 <li>col align-self-start</li>
 <li>col align-self-center</li>
 <li>col align-self-end</li>
</ul>
• Espacios (offset): Permite saltear espacio de columnas. Ej: si quiero saltear una columna:
<ul>
 <li>col-4 offset-1</li>
</ul>
<img src="https://user-images.githubusercontent.com/68869989/216830193-c22a6060-4065-410d-b126-e0a5911a2e9c.png" alt="columns-1">
<ul>
 <li>col-4 <b>ms-auto</b> //coloca automáticamente las columnas hacia los extremos, sin dejar espacios.</li>
</ul>

<h3>Gutters:</h3>
Permite insertar <b>espacios</b> más específicos (de forma vertical u horizontal). Permite valores desde el 0 (sin espacio) hasta el 5 (máx.).
<ul>
 <li>gx-1 //horizontal</li>
 <li>gx-1 //vertical</li>
 <li>g-1 //ambos</li>
</ul>
Podemos especificar según el tipo de pantalla:
<ul>
 <li>gx-sm-0 gx-md-3 gx-lg-5</li>
</ul>

<h3>Espacios / Tamaños:</h3>
•	p-3 //padding de 3, en todas las direcciones (max. 5)
<br>
•	m-3 //margin de 3, en todas las direcciones (max. 5)
<ul>
 <li>mt-3 //margin top</li>
 <li>mb-3 //margin bottom</li>
 <li>my-3 //margen hacia arriba y hacia abajo</li>
 <li>ms-3 //margin start (left)</li>
 <li>me-3 //margin end (right)</li>
 <li>mx-3 //margen hacia los laterales</li>
</ul>
• Ancho:
<ul>
 <li>w-25 //El elemento se ajusta al 25% de ancho del contenedor</li>
 <li>w-auto //Se ajusta al tamaño del elemento actual</li>
</ul>
• Alto:
<ul>
 <li>h-25 //El elemento se ajusta al 25% de alto del contenedor</li>
 <li>h-auto //Se ajusta al tamaño del elemento actual</li>
</ul>

<h3>
  <a href="https://getbootstrap.com/docs/5.0/utilities/flex/">Alineación:</a>
</h3>
<ul>
 <li>justify-content-center</li>
 <li>justify-content-start</li>
 <li>justify-content-end</li>
 <li>...</li>
</ul>

<h3>
  <a href="https://getbootstrap.com/docs/5.0/components/badge/">Badge:</a>
</h3>
Útiles para contener elementos aplicando estilos.
<img src="https://user-images.githubusercontent.com/68869989/216830958-f3971a94-d46a-4dd5-8b80-9ff6302a537a.png" alt="badge-1">

<h3>Textos:</h3>
• Tamaños:
<ul>
 <li>.fs-1</li>
 <li>...</li>
 <li>.fs-6</li>
</ul>
• Quitar estilos (útil por ejemplo para los enlaces):
<ul>
 <li>text-decoration-none</li>
</ul>
