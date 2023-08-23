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
  document.getElementById("notes").innerHTML = "<br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br>  Binomial theorem is a topic about expanding the sum of two monomials raised to a certain power. For example, let us take a look at the sum of two real numbers a and b, raised to an increasingly higher exponent.<br><br>(a + b)⁰ = 1<br>(a + b)¹ = a + b<br>(a + b)² = a² + 2ab + b²<br>(a + b)³ = a³ + 3a²b + 3ab² + b³<br>(a + b)⁴ = a⁴ + 4a³b + 6a²b² + 4ab³ + b⁴<br>(a + b)⁵ = a⁵ + 5a⁴b + 10a³b² + 10a²b³ + 5ab⁴ + b⁵<br><br>As the exponent increases, the expanded polynomial becomes longer and longer. Binomial theorem can be used to quickly find the resulting expanded polynomial using a pattern within these expansions. So what is this pattern?<br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br>Taking a look at the coefficients of the resulting terms, we can see a pattern forming:<br><br>1<br>1 1<br>1 2 1<br>1 3 3 1<br>1 4 6 4 1<br> 1 5 10 10 5 1"
 }
</script>



</body>
</html>
