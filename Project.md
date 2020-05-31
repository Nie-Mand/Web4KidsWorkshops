# Project 

## Part 1
> fichier : index.html 
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Acceuil</title>
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Dosis" rel="stylesheet">
    <style>
      * {
        font-family: 'Dosis', sans-serif;
      }
    </style>
  </head>
  <body>
        <nav class="navbar navbar-expand-sm bg-dark navbar-dark">
          <div class="container" >
            <a class="navbar-brand" href="index.html">Logo</a>
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link" href="symptoms.html">Symptômes</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="proteger.html">Se protéger</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="email.html">Email-me</a>
              </li>
            </ul>
          </div>
        </nav>
          <div class="container" >
            <h1>Qu’est-ce que la COVID-19 ?</h1>
            La COVID-19 est la maladie infectieuse causée par le dernier coronavirus qui a été découvert. Ce nouveau virus et cette maladie
            étaient inconnus avant l’apparition de la flambée à Wuhan (Chine) en décembre 2019. La COVID-19 est maintenant pandémique et touche
            de nombreux pays dans le monde.
        </div>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js"></script>
  </body>
</html>

```

## Part 2
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Project</title>
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css">
  </head>
  <body>
    <div class="container" >
      <form>
        <h1>Test COVID-19</h1>
        Nom : <input type="text" name="nom" /><br>
        Prénom : <input type="text" name="prenom" /><br>

        <h3>Symptômes graves: </h3>
        difficultés à respirer ou essoufflement :
        Oui <input type="radio" name="grave1" value="1" /> 
        Non <input type="radio" name="grave1" value="0" /> 
        <br>
        sensation d’oppression ou douleur au niveau de la poitrine :
        Oui <input type="radio" name="grave2" value="1" /> 
        Non <input type="radio" name="grave2" value="0" /> 
        <br>
        perte d’élocution ou de motricité :
        Oui <input type="radio" name="grave3" value="1" /> 
        Non <input type="radio" name="grave3" value="0" /> 
        <br>

        <h3>Symptômes les plus fréquents: </h3>
        fièvre :
        Oui <input type="radio" name="plusfr1" value="1" /> 
        Non <input type="radio" name="plusfr1" value="0" /> 
        <br>
        toux sèche :
        Oui <input type="radio" name="plusfr2" value="1" /> 
        Non <input type="radio" name="plusfr2" value="0" /> 
        <br>
        fatigue :
        Oui <input type="radio" name="plusfr3" value="1" /> 
        Non <input type="radio" name="plusfr3" value="0" /> 
        <br>

        <h3>Symptômes moins fréquents: </h3>
        courbatures :
        Oui <input type="radio" name="moinfr1" value="1" /> 
        Non <input type="radio" name="moinfr1" value="0" /> 
        <br>
        maux de gorge :
        Oui <input type="radio" name="moinfr2" value="1" /> 
        Non <input type="radio" name="moinfr2" value="0" /> 
        <br>
        conjonctivite :
        Oui <input type="radio" name="moinfr3" value="1" /> 
        Non <input type="radio" name="moinfr3" value="0" /> 
        <br>
        perte de l’odorat ou du goût :
        Oui <input type="radio" name="moinfr4" value="1" /> 
        Non <input type="radio" name="moinfr4" value="0" /> 
        <br>

        <button class="btn btn-warning" >voir résultat</button>
      </form>
    </div>
  </body>
</html>
```

## Part 3
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Project</title>
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css">
  </head>
  <body>
    <div class="container" >
      <form>
        <h1>Test COVID-19</h1>
        Nom : <input type="text" name="nom" /><br>
        Prénom : <input type="text" name="prenom" /><br>

        <h3>Symptômes graves: </h3>
        difficultés à respirer ou essoufflement :
        Oui <input type="radio" name="grave1" value="1" /> 
        Non <input type="radio" name="grave1" value="0" /> 
        <br>
        sensation d’oppression ou douleur au niveau de la poitrine :
        Oui <input type="radio" name="grave2" value="1" /> 
        Non <input type="radio" name="grave2" value="0" /> 
        <br>
        perte d’élocution ou de motricité :
        Oui <input type="radio" name="grave3" value="1" /> 
        Non <input type="radio" name="grave3" value="0" /> 
        <br>

        <h3>Symptômes les plus fréquents: </h3>
        fièvre :
        Oui <input type="radio" name="plusfr1" value="1" /> 
        Non <input type="radio" name="plusfr1" value="0" /> 
        <br>
        toux sèche :
        Oui <input type="radio" name="plusfr2" value="1" /> 
        Non <input type="radio" name="plusfr2" value="0" /> 
        <br>
        fatigue :
        Oui <input type="radio" name="plusfr3" value="1" /> 
        Non <input type="radio" name="plusfr3" value="0" /> 
        <br>

        <h3>Symptômes moins fréquents: </h3>
        courbatures :
        Oui <input type="radio" name="moinfr1" value="1" /> 
        Non <input type="radio" name="moinfr1" value="0" /> 
        <br>
        maux de gorge :
        Oui <input type="radio" name="moinfr2" value="1" /> 
        Non <input type="radio" name="moinfr2" value="0" /> 
        <br>
        conjonctivite :
        Oui <input type="radio" name="moinfr3" value="1" /> 
        Non <input type="radio" name="moinfr3" value="0" /> 
        <br>
        perte de l’odorat ou du goût :
        Oui <input type="radio" name="moinfr4" value="1" /> 
        Non <input type="radio" name="moinfr4" value="0" /> 
        <br>

        <button class="btn btn-warning" onclick="test()" >voir résultat</button>
      </form>
    </div>
  </body>
</html>
```
