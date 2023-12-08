# INTRODUCTION <a name="introduction"></a>

Bonjour à toi, jeune développeur ! Aujourd'hui, tu vas découvrir comment faire un petit site Internet en manipulant les langages HTML, CSS et JavaScript !

# TABLE DES MATIÈRES <a name="table-des-matières"></a>

- [INTRODUCTION](#introduction)
- [TABLE DES MATIÈRES](#table-des-matières)
- [PRÉ-REQUIS](#pré-requis)
- [FONCTIONNEMENT D'UN SITE WEB](#fonctionnement-dun-site-web)
- [CRÉER UN SITE WEB](#créer-un-site-web)
- [POUR LES PLUS COURAGEUX](#pour-les-plus-courageux)

# PRÉ-REQUIS <a name="pré-requis"></a>

- Un navigateur web ouvert sur [CodePen](https://codepen.io/pen/).
- Et c'est tout ! (pour une fois !)

## CodePen.io ?

CodePen.io est un site qui permet de développer un micro site web sans avoir à configurer quoi que ce soit. Pendant que tu écris ton code, ton site se mettra à jour en temps réel !

# FONCTIONNEMENT D'UN SITE WEB <a name="fonctionnement-dun-site-web"></a>

Un site web est composé de 3 parties :
- Le HTML
- Le CSS
- Le JavaScript

## HTML

Le HTML est le langage qui permet de créer la structure de votre site. C'est grâce à lui que vous pouvez créer des paragraphes, des titres, des images, etc. Pour imager, le HTML est le squelette de votre site.
Si vous voulez en savoir plus sur le HTML, je vous conseille de lire [ce tutoriel](https://www.w3schools.com/html/).

Ou alors voici quelques exemples de balises HTML :

### Titre basique avec un paragraphe
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Mon premier site</title>
    </head>
    <body>
        <h1>Bonjour à tous !</h1>
        <p>Je suis un paragraphe</p>
    </body>
</html>
```

### Mettre un lien
```html
<a href="https://www.google.com">Cliquez ici pour aller sur google</a>
```

### Mettre une image
```html
<img src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png" alt="Logo de google">
```

### Mettre une liste
```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

Il y a beaucoup d'autres balises HTML, mais je vous laisse découvrir par vous-même.

## CSS

Le CSS est le langage qui permet de mettre du style à votre site. C'est grâce à lui que vous pouvez changer la couleur de votre texte, la taille de votre texte, etc. Pour imager, le CSS est la peau, le "makeup" de votre site.
Les fichiers css sont généralement nommés "style.css" et sont stockés dans un dossier nommé "css" -- dans notre cas, CodePen.io nous fait grâce d'intégrer automatiquement tout ça, donc rien à faire de ce côté là !

Si vous voulez en savoir plus sur le CSS, je vous conseille de lire [ce tutoriel](https://www.w3schools.com/css/).
Ou alors voici quelques jeu online pour apprendre le CSS :

- [Flexbox Froggy](https://flexboxfroggy.com/)
- [Grid Garden](https://cssgridgarden.com/)
- [CSS Diner](https://flukeout.github.io/)
- [CSS Battle](https://cssbattle.dev/)

C'est pas vraiment ce qu'il manque comme jeu pour apprendre le CSS.
Voici quelques exemples de code CSS :

### Changer la couleur du texte
```css
h1 {
    color: red;
}
```

### Changer la taille du texte
```css
h1 {
    font-size: 50px;
}
```

### Changer la couleur de fond
```css
body {
    background-color: black;
}
```

### Changer la taille d'une image
```css
img {
    width: 100px;
}
```

Et plein d'autres choses encore.

## JavaScript

Le JavaScript est le langage qui permet de rendre votre site dynamique. C'est grâce à lui que vous pouvez faire des animations, des formulaires, etc. Pour imager, le JavaScript est le cerveau de votre site.
Les fichiers JavaScript sont généralement nommés "script.js" et sont stockés dans un dossier nommé "js".
Le javascript est un langage très puissant, il vas vous permettre de faire intéragir votre site avec l'utilisateur, de faire des formulaires, de faire des animations, etc.

Si vous voulez en savoir plus sur le JavaScript, je vous conseille de lire [ce tutoriel](https://www.w3schools.com/js/).

# CRÉER UN SITE WEB <a name="créer-un-site-web"></a>

Maintenant que vous savez comment fonctionne un site web, vous pouvez commencer à créer le vôtre. Trouvez un thème ou un sujet qui vous plait, une idée de site, etc. et lancez-vous !

Si vous voulez trouvez des idées de site, vous pouvez aller sur [Dribbble](https://dribbble.com/).

Si vous voulez trouver des thèmes pour votre site, vous pouvez aller sur [ThemeForest](https://themeforest.net/).

Et voici une pelleté de site pour vous aider à créer votre site ou bien pour avoir des idées / code :
- [W3Schools](https://www.w3schools.com/)
- [MDN Web Docs](https://developer.mozilla.org/fr/)
- [StackOverflow](https://stackoverflow.com/)
- [CSS Tricks](https://css-tricks.com/)

# POUR LES PLUS COURAGEUX <a name="pour-les-plus-courageux"></a>

Pour les plus courageux vous pouvez faire ce qu'on appelle des call API. C'est à dire que vous pouvez faire des requêtes à des API pour récupérer des données et les afficher sur votre site. Vous pouvez donc intégrez des données de météo, images, gifs, etc. sur votre site.

Une API est une interface de programmation qui permet de récupérer des données. Elle est généralement gratuite et vous pouvez l'utiliser pour faire des requêtes à partir de votre site. Une API marche grâce à des URL et à des paramètres. Il existe plusieurs types de requètes (GET, POST, PUT, DELETE, etc.)
vous pouvez voir dans le dossier `code/` des exemples de requêtes à des API.

Voici quelques api pour vous aider :
- [OpenWeatherMap](https://openweathermap.org/api)
- [Giphy](https://developers.giphy.com/docs/api#quick-start-guide)
- [Picsum](https://picsum.photos/)
- [The Movie Database](https://developers.themoviedb.org/3/getting-started/introduction)
- [The Cat API](https://thecatapi.com/)
- [The Dog API](https://thedogapi.com/)
- [The Chuck Norris Database](https://api.chucknorris.io/)
- [The Rick and Morty API](https://rickandmortyapi.com/)
- [The Star Wars API](https://swapi.dev/)
- [The Breaking Bad API](https://breakingbadapi.com/)
- [The Breaking Bad API](https://breakingbadapi.com/)
et plein d'autres encore...
