<html>
<body>

<head>
 <style>
   .intro {
    font-size: 20px;
   }
   .binomial {
    display: inline-block;
   }
  .binomialimg {
    width: 225px;
    border-width: 10px;
    border-color: Black;
    margin-bottom: 10px;
   }
 </style>
</head>

<p class="intro">
 Below is a list of all the topics for A Math.
</p>

<div class="binomial">
 <img class="binomialimg" src="images/iqfyvgbq.png">
 <br/>
 <button onclick="binomial()"> Binomial Theorem </button>
</div>


<p id="notes"> <br> Click on any topic to get notes! </p>

<script>
 function binomial(){
  document.getElementById("notes").innerHTML = "<br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br>  Binomial theorem is a topic about expanding the sum of two monomials raised to a certain power. For example, let us take a look at the sum of two real numbers a and b, raised to an increasingly higher exponent.<br><br>Exponent of 0: (a + b)⁰ = 1<br>Exponent of 1: (a + b)¹ = a + b<br>Exponent of 2: (a + b)² = a² + 2ab + b²<br>Exponent of 3: (a + b)³ = a³ + 3a²b + 3ab² + b³<br>Exponent of 4: (a + b)⁴ = a⁴ + 4a³b + 6a²b² + 4ab³ + b⁴<br>Exponent of 5: (a + b)⁵ = a⁵ + 5a⁴b + 10a³b² + 10a²b³ + 5ab⁴ + b⁵"
 }
</script>



</body>
</html>
