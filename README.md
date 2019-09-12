# HTML.index

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Catch'em all!</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <section>
            <img class="hover-effect" src="http://images.innoveduc.fr/integration_parcours/css/css_selectors_props/hobbit-house.jpg" alt="Hobbit house">
            <p>Photo by conner Bowe on Unsplash</p>
            <img src="http://images.innoveduc.fr/integration_parcours/css/css_selectors_props/hobbit-house-grass.jpg" alt="Hobbit house with grass">
            <p>Photo by Jeff Finley on Unsplash</p>
            <img class="hover-effect" src="http://images.innoveduc.fr/integration_parcours/css/css_selectors_props/hobbit-house-grey-grass.jpg" alt="Hobbit house with grey grass">
            <p>Photo by Tyler Lastovich on Unsplash</p>
        </section>
    </body>
</html>

CSS.index

body {
    font-family: 'Courier New', Courier, monospace;
}

/* English : Replace the dots below by a selector targeting all the images of the page. */
/* Français : Remplace les points ci-dessous par un sélecteur ciblant toutes les images de la page. */

img{
    width: 300px;
    height: 300px;
    border-radius: 30px;
}         /* English : Replace with a property that makes the image borders look rounded. */
                    /* Français : Remplace par une propriété arrondissant les angles de l'image. */



/* English : Replace the dots below by a class named "hover-effect" with a :hover pseudo-class. This class has to target the first image and the last image of the page. */
/* Français : Remplace les points ci-dessous par une classe "hover-effect" avec une pseudo-classe :hover. Cette classe doit cibler la première image et la troisième image de la page. */

.hover-effect:hover {
   opacity: 0.8;         /* English : Replace with a property responsible for opacity changes. */
                    /* Français : Remplace par une propriété modifiant l'opacité. */
    cursor: pointer;
  }

/* English : Replace the dots below by a selector targeting the second image of the page. Do not use a class or an id! */
/* Français : Remplace les points ci-dessous par un sélecteur ciblant la seconde image de la page. N'utilise pas de classe ou d'i*/

img:nth-of-type(2) {
   filter: grayscale(100%); 
        /* English : Replace with a property that makes the image look black & white. */
                /* Français : Remplace par une propriété faisant paraître l'image en noir et blanc. */
}
