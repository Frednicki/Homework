# Homework

<!--
    This file wows factors of prime numbers.
    Author: Fredrick Karau
    File: prime_numbers.html
    Date:2/20/2021
-->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Calculating Primes</title>
    <link rel="stylesheet" href="styles/styles.css">
    <script src="scripts/primes_module.js"></script>
    <script src="scripts/informal_tests.js"></script>
    <script src="scripts/calculations.js"></script>



</head>
<body>
<section id="number-analysis">
    <h1>Enter a number to analyze!</h1>
    <form>
        <div class="form-group">
            <label>Number:</label>
            <input type="text" id="number">
            <button id="analyze">Analyze!</button>
        </div>
    </form>
    <p id="analyze-error"></p>

    <fieldset>
        <legend>Prime Status</legend>
        <p id="prime-status"></p>
    </fieldset>
    <fieldset>
        <legend>Factors</legend>
        <ul id="factors"></ul>
    </fieldset>
</section>

<section id="primes-generation">
    <h1>Generate primes!</h1>
    <form>
        <div class="form-group">
            <label>Low:</label>
            <input type="text" id="low">
            <button id="generate">Generate!</button>
        </div>
        <div class="form-group">
            <label>High:</label>
            <input type="text" id="high">
        </div>
    </form>
    <p id="generate-error"></p>

    <fieldset>
        <legend>Primes</legend>
        <ul id="primes-list"></ul>
    </fieldset>
</section>
</body>
</html>
