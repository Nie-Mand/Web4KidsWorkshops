# Project 

## Part 1
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Project</title>
    <script>
      function test() {
        
      }
    </script>
  </head>
  <body>
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

      <button>voir résultat</button>
    </form>
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
