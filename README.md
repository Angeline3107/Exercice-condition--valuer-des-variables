# Exercice-condition-evaluer-des-variables
Exercices odyssey

// Declare and define three variables using a numerical value
// * If the three variables are equal, display "The three variables are the same" in the console
// * If only two of the variables are equal, display "Two of the variables are the same" in the console
// * If the variables are all different display "all variables are different" in the console

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <script>
    const a = 1;
    const b = 2;
    const c = 3;
    if (a === b && b === c) {
      console.log("Les trois variables sont identiques");
      }
      else if (a === b || a===c || b===c) {
      console.log("Deux des variables sont identiques");
    }
    else {
      console.log("Toutes les variables sont différentes");
    }
  </script>
</body>
</html>
