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
    height: 162px;
    border-width: 10px;
    border-color: Black;
    margin-right: 10px;
    margin-bottom: 10px;
   }
   .surds {
    display: inline-block;
   }
  .surdsimg {
    width: 225px;
    height: 162px;
    object-fit: cover;
    border-width: 10px;
    border-color: Black;
    margin-right: 10px;
    margin-bottom: 10px;
   }
   .quadratic {
    display: inline-block;
   }
  .quadraticimg {
    width: 225px;
    height: 162px;
    object-fit: cover;
    border-width: 10px;
    border-color: Black;
    margin-right: 10px;
    margin-bottom: 10px;
   }
   .polynomial {
    display: inline-block;
   }
  .polynomialimg {
    width: 225px;
    height: 162px;
    object-fit: cover;
    border-width: 10px;
    border-color: Black;
    margin-bottom: 10px;
   }
 </style>
</head>

<p class="intro">
 Below is a list of some topics for A Math.
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

<div class="quadratic">
 <img class="quadraticimg" src="images/quadratic.JPG">
 <br/>
 <button onclick="quadratic()"> Quadratic Functions </button>
</div>

<div class="polynomial">
 <img class="polynomialimg" src="images/maths-in7-00.png">
 <br/>
 <button onclick="polynomial()"> Polynomials and Partial Fractions </button>
</div>

<p id="notes"> <br> Click on the buttons of any of the following topics to see its notes! </p>

<script>
 function binomial(){
  document.getElementById("notes").innerHTML = "<br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br>  Binomial theorem is a topic about expanding the sum of two monomials raised to a certain power. For example, let us take a look at the sum of two real numbers a and b, raised to an increasingly higher exponent.<br><br>(a + b)⁰ = 1<br>(a + b)¹ = a + b<br>(a + b)² = a² + 2ab + b²<br>(a + b)³ = a³ + 3a²b + 3ab² + b³<br>(a + b)⁴ = a⁴ + 4a³b + 6a²b² + 4ab³ + b⁴<br>(a + b)⁵ = a⁵ + 5a⁴b + 10a³b² + 10a²b³ + 5ab⁴ + b⁵<br><br>As the exponent increases, the expanded polynomial becomes longer and longer. Binomial theorem can be used to quickly find the resulting expanded polynomial using a pattern within these expansions. So what is this pattern?<br><br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br>Taking a look at the coefficients of the resulting terms, we can see a pattern forming:<br><br>1<br>1 1<br>1 2 1<br>1 3 3 1<br>1 4 6 4 1<br> 1 5 10 10 5 1<br><br>When arranged in a pyramid, we can see that each number is equal to the sum of the two numbers above it. This is famously known as Pascal's triangle, and it appears within the coefficients of the terms in binomial expansions. Hence...<br><br>The coefficients of the terms in (x+y)ⁿ is equal to the numbers in the (n+1)th row of Pascal's triangle.<br><br>Additionally, the expanded result will be equal to the sum of (nCr)xⁿ⁻ʳyʳ for all values of r from 0 to n.<br><br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br>In the second equation, the operation 'nCr' refers to the operation of 'n choose r'. This operation identifies the number of unique sets of numbers that can be constructed if r numbers are picked from n numbers.<br><br> Hence, n choose 0 is 1, n choose 1 is n, and n choose n is 1.<br><br>Additionally, the operation n choose r can be expressed as a fraction of factorial products, equivalent to n!/r!(n-r)!, in which the exclamation mark represents the factorial operation, which calculates the product of a number as well as every integer smaller than it to one.<br><br>As an example, 3! is 3 x 2 x 1, which is 6. 4! is 4 x 3 x 2 x 1, which is 24. Surprisingly, 0! is equal to 1, because a factorial can also be rewritten as (n+1)!/(n+1), in which 0! is equal to 1!/1, which is 1. Additionally, factorials can also be rewritten as (n)(n-1)!, which can be used to simplify fractions with factorials."
 }
</script>

<script>
 function surds(){
  document.getElementById("notes").innerHTML = "<br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br>  Surds are irrational roots of integers. These numbers cannot be expressed as a fraction. They are decimals that trail infinitely long. Consider square roots such as √2.<br><br>√2 ≈ 1.4142135…<br><br>In this case, √2 is a surd as it is a root with an irrational value. These surds are often better left in this surd form as approximating their value is less accurate. Values such as √4, however, would likely not be considered a surd as it has a rational value of 2 and can be easily expressed precisely.<br><br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br>There are a few laws of surds that is true regardless of the surd involved. Here are some of the basic laws:<br><br>1. √a x √b = √ab<br>2. √a x √a = a<br>3. √a/√b = √(a/b)<br><br> Using these laws of surds can be used to simplify equations with surds.<br><br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br>When surds are present in the denominator of a fraction, there are several approaches to take.<br><br>One scenario would be when the denominator is a single surd. These fractions, such as 3/√2, can be multiplied on both sides by the same surd to simplify the fraction, which in this case will be 3√2.<br><br> Another scenario would be when the denominator is a surd plus or minus another value, for example the denominator is 3/√2+3.<br><br>This surd is known as a conjugate surd. To rationalize the denominator, we can use the algebraic identity of a² - b² = (a+b)(a-b) to help us. In the case of 3/√2+3, we can multiply both sides by √2-3. (√2+3)(√2-3) will be equivalent to (√2)² - 3², equal to -5. 3 can then be divided by -5 to give a simplified result."
 }
</script>

<script>
 function quadratic(){
  document.getElementById("notes").innerHTML = "<br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br>  Quadratic functions are polynomials in which its degree is 2, in the form of y = ax² + bx + c. These types of functions, when drawn on a graph, take the shape of a parabola, unlike linear graphs, that curves either upward or downward. Quadratic graphs can have varying numbers of x-intercepts, but always a single y-intercept.<br><br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br> There are many things which can be determined from a given quadratic equation. When its equation is in the form of y = ax² + bx + c, c is always the y-intercept.<br><br>The x-intercept, on the other hand, can vary in numbers. One quadratic graph can have either no, one, or two x-intercepts, which can be determined by its discriminant, expressed in the form b²-4ac.<br><br>If the resulting number is below 0, the quadratic curve has no x-intercepts. If the number is equal to 0, the quadratic curve has a single x-intercept. If the number is greater than 0, the quadratic curve has two x-intercepts.<br><br>To find these x-intercepts, y can be substituted as 0, and the equation can be factorised. However, if the equation cannot be factorised, the quadratic formula of ((-b)√b²-4ac)/2a can be used. The resulting number will thus be the value of x. This equation is performable on most calculators.<br><br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br>To determine the turning point of the graph, the quadratic equation of y = ax² + bx + c must be factorised in the completing the square form. To perform completing the square, if a is not 1, it must be taken out of the equation first as a(x²+(b/a)x)+c. Afterwards, a squared binomial must be formed in which the products give x² and either bx or (b/a)x, depending on if the coefficient of x was 1. In the squared binomial, the additional product, 2ab, must then be removed from c. Completing the square will give an equation of the formula a(x-h)2+k, in which (-h,k) is the turning point."
 }
</script>

<script>
 function quadratic(){
  document.getElementById("notes").innerHTML = "<br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br>  Quadratic functions are polynomials in which its degree is 2, in the form of y = ax² + bx + c. These types of functions, when drawn on a graph, take the shape of a parabola, unlike linear graphs, that curves either upward or downward. Quadratic graphs can have varying numbers of x-intercepts, but always a single y-intercept.<br><br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br> There are many things which can be determined from a given quadratic equation. When its equation is in the form of y = ax² + bx + c, c is always the y-intercept.<br><br>The x-intercept, on the other hand, can vary in numbers. One quadratic graph can have either no, one, or two x-intercepts, which can be determined by its discriminant, expressed in the form b²-4ac.<br><br>If the resulting number is below 0, the quadratic curve has no x-intercepts. If the number is equal to 0, the quadratic curve has a single x-intercept. If the number is greater than 0, the quadratic curve has two x-intercepts.<br><br>To find these x-intercepts, y can be substituted as 0, and the equation can be factorised. However, if the equation cannot be factorised, the quadratic formula of ((-b)√b²-4ac)/2a. The resulting number will thus be the value of x. This equation is performable on most calculators.<br><br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br>To determine the turning point of the graph, the quadratic equation of y = ax² + bx + c must be factorised in the completing the square form. To perform completing the square, if a is not 1, it must be taken out of the equation first as a(x²+(b/a)x)+c. Afterwards, a squared binomial must be formed in which the products give x² and either bx or (b/a)x, depending on if the coefficient of x was 1. In the squared binomial, the additional product, 2ab, must then be removed from c. Completing the square will give an equation of the formula a(x-h)2+k, in which (-h,k) is the turning point."
 }
</script>

<script>
 function polynomial(){
  document.getElementById("notes").innerHTML = "<br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br>  A polynomial is an expression of more than two algebraic terms, especially the sum of several terms that contain different powers of the same variable, commonly denoted as f(x), P(x), or Q(x). The degree of a polynomial in x is the highest power of x inside the polynomial. When it is stated that f(x) is equal to a polynomial, and f(x) = 4, it is implied that every x in the polynomial be replaced with 4. This substitution is usually used to get the value of x within polynomials given additional information. Products of two algebraic equations can also give polynomials. To identify coefficients of a certain algebraic variable in the final product, inspection can be done to only calculate the necessary products that form the coefficient.<br><br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br>Polynomials can be divided by other equations using long division. A dividend is defined as a number that is to be divided by another number. A divisor is the number the dividend is divided by. Meanwhile, a quotient is defined as an integer quantity produced by the division of two numbers. The remainder is what cannot be divided by the divisor without producing a non-integer. A polynomial can thus be expressed in terms of its divisor multipied by the quotient plus the remainder. When a polynomial divided by an algebraic equation produces no remainder, it is a factor of the polynomial.<br><br>According to the remainder theorem, if a polynomial P(x) is divided by a linear divisor of ax-b, the remainder will be P(b/a). Additionally, according to the factor theorem, if a polynomial is divided by (x-a) and f(a) = 0, then (x-a) is a factor of f(x). Conversely, if f(a) = 0, then (x-a) is a factor of f(x).<br><br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br>Cubic polynomials can be factorised, using either Euclidean division or long division. It usually involves guessing, however. Most calculators have the capability to get the roots of a cubic equation.<br><br>Additionally, for a cubic polynomial P(x), if the graph cuts the x-axis at x=a, (x-a) is a factor of P(x). The number of distinct real rools equals to the number of intersections of P(x) with the x-axis. It is also not necessarily that there are always 3 distinct real roots.<br><br>Also, the formula for a cubed number subtracted by a cubed number, represented by a and b, is shown below:<br>a³ - b³ = (a – b)(a² + ab + b²)<br><br>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br><br>Finally, a partial fraction is an algebraic fraction that forms part of a bigger algebraic fraction. Any algebraic fraction f(x)/g(x) may be expressed as a sum of simpler fractions with factors of g(x) as denominators.<br><br>To split a fraction with a denominator of a linear factor into partial fractions, the corresponding partial fractions are A/(ax+b) + B/(cx+d).<br><br>To split a fraction with a denominator that has a repeated linear factor, its corresponding partial fractions are A/(ax+b) + B/(cx+d) + C/(cx+d)².<br><br>Finally, to split a fraction with a denominator that has a quadratic factor that cannot be factorised, its corresponding partial fractions are A/(ax+b) + Bx+C/(x²+c²).<br><br>Splitting fractions into partial fractions require the resulting partial fractions to be combined into the form of the original. Then, apt substitution should be used to figure out the required values.<br><br>It is very important to note if your fraction is improper. If the degree of the numerator polynomial is higher than the degree of the denominator polynomial, long division should be done first. The quotient should be added at the back, and the remainder should be put into a fraction and subsequently split into its partial fractions."
 }
</script>




</body>
</html>
