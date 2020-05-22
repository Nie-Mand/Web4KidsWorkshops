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
dans ce Checkpoint, vous créerez un compte sur GitHub, puis vous téléchargerez les outils dont vous avez besoin, suivez les instructions de l'atelier pour vous aider, vous devez partager le lien vers votre profil GitHub afin que nous puissions noter vos exercices
<br>
**Solution :**
- téléchargez et installez git et un éditeur de texte de votre choix (Atom, VSC, Sublime Text ..)
- créer un compte sur GitHub et envoyez-nous le lien du compte
<br>

## Checkpoint 3
**Sujet :**<br>
dans ce Checkpoint, vous créerez un compte sur GitHub, puis vous téléchargerez les outils dont vous avez besoin, suivez les instructions de l'atelier pour vous aider, vous devez partager le lien vers votre profil GitHub afin que nous puissions noter vos exercices
<br>
**Solution :**
- téléchargez et installez git et un éditeur de texte de votre choix (Atom, VSC, Sublime Text ..)
- créer un compte sur GitHub et envoyez-nous le lien du compte
<br>

## Checkpoint 4
**Sujet :**<br>
dans ce Checkpoint, vous créerez un compte sur GitHub, puis vous téléchargerez les outils dont vous avez besoin, suivez les instructions de l'atelier pour vous aider, vous devez partager le lien vers votre profil GitHub afin que nous puissions noter vos exercices
<br>
**Solution :**
- téléchargez et installez git et un éditeur de texte de votre choix (Atom, VSC, Sublime Text ..)
- créer un compte sur GitHub et envoyez-nous le lien du compte
<br>

## Checkpoint 5
**Sujet :**<br>
vous souhaiterez peut-être commencer à utiliser Bootstrap dans vos sites Web. dans ce checkpoint, vous ferez une page Web simple qui contient une barre de navigation avec un menu déroulant, n'hésitez pas à choisir les liens que vous ajouterez et ajouter un article avec une image après la barre de navigation.
<br>
**Solution :**
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
dans ce Checkpoint, vous créerez un compte sur GitHub, puis vous téléchargerez les outils dont vous avez besoin, suivez les instructions de l'atelier pour vous aider, vous devez partager le lien vers votre profil GitHub afin que nous puissions noter vos exercices
<br>
**Solution :**
- téléchargez et installez git et un éditeur de texte de votre choix (Atom, VSC, Sublime Text ..)
- créer un compte sur GitHub et envoyez-nous le lien du compte
<br>

