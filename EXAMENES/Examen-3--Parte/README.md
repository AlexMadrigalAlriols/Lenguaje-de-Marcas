# Examen 3ª Parte
En este ejercicio hemos utilizado una Responsive Web y hemos practicado Css y Html.
---
Lo primero de todo es poner el style.css con un <link>

`  <link href="style.css" rel="stylesheet"> `

Luego con la etiqueta de <meta> ajustamos el viewport para que se transforme en una Responsive Web, es decir que se ajuste a las pantallas.

`<meta name="viewport" content="width=device-width, initial-scale=1.0">`

Y ahora con estas etiquetas ya escribimos el codigo html normal:


<body>
 <main>
    <article>

      <iframe width="560" height="315" src="https://www.youtube.com/embed/p85rO57cWKM" frameborder="0"
        allowfullscreen></iframe>
      <h2>Rocking the free web</h2>

      <p>Mozilla are a global community of technologists, thinkers, and builders, working together to keep the Internet
        alive and accessible, so people worldwide can be informed contributors and creators of the Web. We believe this
        act of human collaboration across an open platform is essential to individual growth and our collective future.
      </p>

      <p>Click on the images below to find more information about the cool stuff Mozilla does. <a
          href="https://www.flickr.com/photos/mathiasappel/21675551065/">Red panda picture</a> by Mathias Appel.</p>
    </article>
    


    <div class="infodelpanda">
      <!-- insert images with srcsets and sizes -->
      <a href="https://www.mozilla.org/en-US/firefox/new/">
        <img src="firefox_logo-only_RGB.png" sizes="(max-width: 480px) 120px,
            400px" src="firefox_logo-only_RGB.png" alt="Firefox Logo">
      </a>
      <a href="https://www.mozilla.org/">
        <img src="mozilla-dinosaur-head.png" sizes="(max-width: 480px) 120px,
             400px" src="mozilla-dinosaur-head_Original.png" alt="Mozilla Logo">
      </a>
      <a href="https://addons.mozilla.org/">
        <img src="firefox-addons.jpg" sizes="(max-width: 480px) 120px,
             400px" src="firefox-addons.png" alt="Mozilla Add-Ons">
      </a>
      <a href="https://developer.mozilla.org/en-US/">
        <img src="mdn.svg" alt="Mozilla Developer Network Logo">
      </a>
      <div class="clearfix"></div>
    </div>


    <div class="pandahacker">
      <!-- insert picture element -->
      <picture>
        <source media="(max-width: 600px)" src="red-panda-closeup.png">
        <source media="(min-width: 601px)" src="red-panda-1200.jpeg">
        <img src="red-panda.jpg" alt="The beautiful red panda">
      </picture>
    </div>

  </main>
</body>

