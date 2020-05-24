# Web4Kids Checkpoints

## Checkpoint 1
**Sujet :**<br>
dans ce Checkpoint, vous créerez un compte sur GitHub, puis vous téléchargerez les outils dont vous avez besoin, suivez les instructions de l'atelier pour vous aider, vous devez partager le lien vers votre profil GitHub afin que nous puissions noter vos exercices
<br>
**Solution :**
- téléchargez et installez git et un éditeur de texte de votre choix (Atom, VSC, Sublime Text ..)
- créer un compte sur GitHub et envoyez-nous le lien du compte
<br>

## Checkpoint 2
**Sujet :**<br>
Dans ce checkpoint, vous allez créer une page Web contenant un article, n'hésitez pas à écrire quoi que ce soit, vous pouvez utiliser Internet pour en obtenir. l'article a un titre, un auteur, une catégorie et un contenu, le contenu doit comprendre au moins 3 mots avec un format spécial (souligné, gras ...)
<br>
**Solution :**
> fichier : index.html
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Checkpoint 2</title>
  </head>
  <body>
      <article>
        <h3>Article : Les Langages de développement web, <i>Catégorie : Web</i></h3>
        <b>Auteur : John Doe</b>
        <hr>
        <p>
          Utilisé aujourd’hui dans sa version 5, le <u>HTML</u> est le langage servant à la création de pages pour le web. Il s’agit donc d’un langage web. En réalité, le <u>HTML5</u> n’est pas à proprement parlé un langage de programmation. Il s’agit plutôt d’un langage de balisage. Cela veut simplement dire que votre code contiendra des balises qui elles-mêmes contiendront les informations que vous souhaitez afficher sur votre page web.
Le binôme du <u>HTML5</u> est le <u>CSS3</u>. Là où le <u>HTML</u> mettra les contenus sur notre page web, le <u>CSS</u> sera utilisé pour mettre en forme ces contenus. Vous allez ainsi pouvoir, grâce au <u>CSS</u>, choisir la police que vous souhaitez utiliser, sa taille ou encore la couleur du fond de votre page web. Chaque instruction en <u>CSS</u> que vous écrirez va ainsi pointer l’élément HTML que vous souhaiterez customiser. Le <u>HTML5</u> et le <u>CSS3</u> sont à la base de tous les sites web.
        </p>
      </article>
  </body>
</html>
```
<br>

## Checkpoint 3
**Sujet :**<br>
Dans ce checkpoint, vous utiliserez votre travail précédent pour ajouter un menu et un pied de page, le menu contient une page "à propos" et une page "contactez-nous", la page à propos contiendra des informations vous concernant, et la page "contactez-nous" contiendra un lien vers votre compte github. le pied de page contient votre nom. le code doit contenir au moins un bloc "div"
<br>
**Solution :**
> fichier : index.html
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Checkpoint 2</title>
  </head>
  <body>
    <menu>
      <ul>
          <li><a href="apropos.html">à propos</a></li>
          <li><a href="https://www.github.io/TON_COMPTE">contactez-nous</a></li>
      </ul>
    </menu>
      <div>
        <h3>Article : Les Langages de développement web, <i>Catégorie : Web</i></h3>
        <b>Auteur : John Doe</b>
        <hr>
        <p>
          Utilisé aujourd’hui dans sa version 5, le <u>HTML</u> est le langage servant à la création de pages pour le web. Il s’agit donc d’un langage web. En réalité, le <u>HTML5</u> n’est pas à proprement parlé un langage de programmation. Il s’agit plutôt d’un langage de balisage. Cela veut simplement dire que votre code contiendra des balises qui elles-mêmes contiendront les informations que vous souhaitez afficher sur votre page web.
Le binôme du <u>HTML5</u> est le <u>CSS3</u>. Là où le <u>HTML</u> mettra les contenus sur notre page web, le <u>CSS</u> sera utilisé pour mettre en forme ces contenus. Vous allez ainsi pouvoir, grâce au <u>CSS</u>, choisir la police que vous souhaitez utiliser, sa taille ou encore la couleur du fond de votre page web. Chaque instruction en <u>CSS</u> que vous écrirez va ainsi pointer l’élément HTML que vous souhaiterez customiser. Le <u>HTML5</u> et le <u>CSS3</u> sont à la base de tous les sites web.
        </p>
      </div>
      <footer>
        Powered by : TON NOM
      </footer>
  </body>
</html>
```
> fichier : apropos.html
```html
<!DOCTYPE html>
<html>
  <head>
    <title>à propos</title>
  </head>
  <body>
    <h1>à propos : TON NOM</h1>
    parler de soi..
  </body>
</html>
```
<br>

## Checkpoint 4
**Sujet :**<br>
tu te souviens de ton dernier checkpoint? vous voudrez peut-être commencer à y ajouter votre premier code CSS, dans ce point de contrôle, vous travaillerez avec CSS, vous devez l'ajouter via un fichier externe ou une balise de style, vous devez ajouter au moins une propriété du modèle de boîte.
<br>
**Solution :**
> fichier : index.html
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Checkpoint 4</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
      <article>
        <h3>Article : Les Langages de développement web</h3>
        <hr>
        <p>
          Utilisé aujourd’hui dans sa version 5, le HTML est le langage servant à la création de pages pour le web. Il s’agit donc d’un langage web. En réalité, le HTML5 n’est pas à proprement parlé un langage de programmation. Il s’agit plutôt d’un langage de balisage. Cela veut simplement dire que votre code contiendra des balises qui elles-mêmes contiendront les informations que vous souhaitez afficher sur votre page web.
Le binôme du HTML5 est le CSS3. Là où le HTML mettra les contenus sur notre page web, le CSS sera utilisé pour mettre en forme ces contenus. Vous allez ainsi pouvoir, grâce au CSS, choisir la police que vous souhaitez utiliser, sa taille ou encore la couleur du fond de votre page web. Chaque instruction en CSS que vous écrirez va ainsi pointer l’élément HTML que vous souhaiterez customiser. Le HTML5 et le CSS3 sont à la base de tous les sites web.
        </p>
        <img src="web.png" alt="Web" width="900" height="250" >
      </article>
  </body>
</html>
```
> fichier : styles.css
```css
article {
  border: 2px solid black;
}
h3 {
  padding: 10px;
  color: red;
  font-size: 20px;
}
p {
  padding: 10px;
  font-family: arial;
}
img {
  padding: 20px;
}
```
<br>

## Checkpoint 5
**Sujet :**<br>
vous souhaiterez peut-être commencer à utiliser Bootstrap dans vos sites Web. dans ce checkpoint, vous ferez une page Web simple qui contient une barre de navigation avec un menu déroulant, n'hésitez pas à choisir les liens que vous ajouterez et ajouter un article avec une image après la barre de navigation.
<br>
**Solution :**
> fichier : index.html
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Checkpoint 5</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" >
  </head>
  <body>
    <div class="container">
      <nav class="navbar navbar-expand-sm bg-dark navbar-dark">
        <a class="navbar-brand" href="#">Mon Site Web</a>
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" href="#">acceuil</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">à propos</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbardrop" data-toggle="dropdown">
              nos services
            </a>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="#">creation des sites Web</a>
              <a class="dropdown-item" href="#">creation des application Android</a>
              <a class="dropdown-item" href="#">creation des jeux vidéos</a>
            </div>
          </li>
        </ul>
      </nav>
      <article>
        <h3>Article : Les Langages de développement web</h3>
        <p>
          Utilisé aujourd’hui dans sa version 5, le HTML est le langage servant à la création de pages pour le web. Il s’agit donc d’un
       langage web. En réalité, le HTML5 n’est pas à proprement parlé un langage de programmation. Il s’agit plutôt d’un langage de
          balisage. Cela veut simplement dire que votre code contiendra des balises qui elles-mêmes contiendront les informations que vous souhaitez afficher sur votre page web.
Le binôme du HTML5 est le CSS3. Là où le HTML mettra les contenus sur notre page web, le CSS sera utilisé pour mettre en forme ces
          contenus. Vous allez ainsi pouvoir, grâce au CSS, choisir la police que vous souhaitez utiliser, sa taille ou encore la
          couleur du fond de votre page web. Chaque instruction en CSS que vous écrirez va ainsi pointer l’élément HTML que vous 
          souhaiterez customiser. Le HTML5 et le CSS3 sont à la base de tous les sites web.
        </p>
        <img src="web.png" alt="Web" width="900" height="250" >
      </article>
    </div>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js"></script>
  </body>
</html>

```
<br>

## Checkpoint 6
**Sujet :**<br>
dans ce checkpoint, vous allez faire un tableau à 2 colonnes, ‘s'inscrire’ et ‘se connecter’. le formulaire ‘s'inscrire’ contient le nom, l'adresse e-mail, le mot de passe (et le bouton Envoyer). le formulaire ‘se connecter’ ne contient que l'e-mail et le mot de passe (et le bouton Envoyer). il est préférable d'utiliser Bootstrap pour le rendre agréable.
<br>
**Solution :**
> fichier : index.html
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Checkpoint 6</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" >
  </head>
  <body>
    <div class="container" >
      <table class="table table-bordered table-hover table-dark" >
        <tr>
          <th>s'inscrire</th>
          <th>se connecter</th>
        </tr>
        <tr>
          <td>
            <form>
              Nom : <input type="text" name="nom" > <br>
              Email : <input type="text" name="email" > <br>
              Mot de passe : <input type="password" name="mdp" > <br>
              <input type="submit" value="s'inscrire" class="btn btn-warning" > <br>
            </form>
          </td>
          <td>
            <form>
              Email : <input type="text" name="email" > <br>
              Mot de passe : <input type="password" name="mdp" > <br>
              <input type="submit" value="se connecter" class="btn btn-warning" > <br>
            </form>
          </td>
        </tr>
      </table>
    <div>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js"></script>
  </body>
</html>
```
<br>

## Checkpoint 7
**Sujet :**<br>
vous allez créer une page Web qui contient un bouton et un paragraphe qui contient le texte "résultat" et une fois que vous cliquez sur un bouton vous entrez deux nombres dans une fenêtre contextuelle (x, y) puis le contenu du paragraphe sera changé en le produit de x et y, et la couleur du texte sera rouge.
<br>
**Solution :**
> fichier : index.html
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Checkpoint 7</title>
    <script>
      function checkpoint() {
        var x = prompt("Saisissez x : ")
        var y = prompt("Saisissez y : ")
        var resultat = document.getElementById("resultat")
        resultat.innerHTML = x * y
        resultat.style.color = "red"
      }
    </script>
  </head>
  <body>
    <p id="resultat" >résultat</p>
    <button onclick="checkpoint()" >Clicker</button>
  </body>
</html>
```
<br>

## Checkpoint 8
**Sujet :**<br>
dans ce checkpoint, vous ajouterez une partie de ce que nous avons discuté dans ce chapitre, vous devez ajouter une nouvelle police, de préférence à partir des polices Google, et vous ajouterez une transformation avec une transition (délai). vous pouvez utiliser l'un des codes précédents que nous avons fait
<br>
**Solution :**
> fichier : index.html
```html
<html><head>
    <title>Checkpoint 8</title>
    <link href="https://fonts.googleapis.com/css2?family=Chelsea+Market&amp;display=swap" rel="stylesheet">
      <style>
    article {
  border: 2px solid black;
  width: 700px;
  font-family: 'Chelsea Market', cursive;
  transform: translate(100px, 50px);
  transition: transform 1.5s;
}
h3 {
  padding: 10px;
  color: red;
  font-size: 20px;
}
p {
  padding: 10px;
}
      </style>
  </head>
  <body>
      <article class="article">
        <h3>Article : Les Langages de développement web</h3>
        <hr>
        <p>
          Utilisé aujourd’hui dans sa version 5, le HTML est le langage servant à la création de pages pour le web. Il s’agit donc d’un langage web. En réalité, le HTML5 n’est pas à proprement parlé un langage de programmation. Il s’agit plutôt d’un langage de balisage. Cela veut simplement dire que votre code contiendra des balises qui elles-mêmes contiendront les informations que vous souhaitez afficher sur votre page web.
Le binôme du HTML5 est le CSS3. Là où le HTML mettra les contenus sur notre page web, le CSS sera utilisé pour mettre en forme ces contenus. Vous allez ainsi pouvoir, grâce au CSS, choisir la police que vous souhaitez utiliser, sa taille ou encore la couleur du fond de votre page web. Chaque instruction en CSS que vous écrirez va ainsi pointer l’élément HTML que vous souhaiterez customiser. Le HTML5 et le CSS3 sont à la base de tous les sites web.
        </p>
        <img src="web.png" alt="Web" width="900" height="250">
      </article>
  
</body></html>
```
<br>

