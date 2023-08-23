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

<div class="surds">
 <img class="surdsimg" src="images/surds.JPG">
 <br/>
 <button onclick="surds()"> Surds </button>
</div>

<p id="notes"> <br> Click on any topic to get notes! </p>

<script>
 function binomial(){
  document.getElementById("notes").innerHTML = "<br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br>  Binomial theorem is a topic about expanding the sum of two monomials raised to a certain power. For example, let us take a look at the sum of two real numbers a and b, raised to an increasingly higher exponent.<br><br>(a + b)⁰ = 1<br>(a + b)¹ = a + b<br>(a + b)² = a² + 2ab + b²<br>(a + b)³ = a³ + 3a²b + 3ab² + b³<br>(a + b)⁴ = a⁴ + 4a³b + 6a²b² + 4ab³ + b⁴<br>(a + b)⁵ = a⁵ + 5a⁴b + 10a³b² + 10a²b³ + 5ab⁴ + b⁵<br><br>As the exponent increases, the expanded polynomial becomes longer and longer. Binomial theorem can be used to quickly find the resulting expanded polynomial using a pattern within these expansions. So what is this pattern?<br><br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br>Taking a look at the coefficients of the resulting terms, we can see a pattern forming:<br><br>1<br>1 1<br>1 2 1<br>1 3 3 1<br>1 4 6 4 1<br> 1 5 10 10 5 1<br><br>When arranged in a pyramid, we can see that each number is equal to the sum of the two numbers above it. This is famously known as Pascal's triangle, and it appears within the coefficients of the terms in binomial expansions. Hence...<br><br>The coefficients of the terms in (x+y)ⁿ is equal to the numbers in the (n+1)th row of Pascal's triangle.<br><br>Additionally, the expanded result will be equal to the sum of (nCr)xⁿ⁻ʳyʳ for all values of r from 0 to n.<br><br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br>In the second equation, the operation 'nCr' refers to the operation of 'n choose r'. This operation identifies the number of unique sets of numbers that can be constructed if r numbers are picked from n numbers.<br><br> Hence, n choose 0 is 1, n choose 1 is n, and n choose n is 1.<br><br>Additionally, the operation n choose r can be expressed as a fraction of factorial products, equivalent to n!/r!(n-r)!, in which the exclamation mark represents the factorial operation, which calculates the product of a number as well as every integer smaller than it to one.<br><br>As an example, 3! is 3 x 2 x 1, which is 6. 4! is 4 x 3 x 2 x 1, which is 24. Surprisingly, 0! is equal to 1, because a factorial can also be rewritten as (n+1)!/(n+1), in which 0! is equal to 1!/1, which is 1. Additionally, factorials can also be rewritten as (n)(n-1)!, which can be used to simplify fractions with factorials."
 }
</script>

<script>
 function surds(){
  document.getElementById("notes").innerHTML = "<br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br>  "
 }
</script>



</body>
</html>
