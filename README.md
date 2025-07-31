<h1 align="center">💱 Currency Converter - Python (CLI)</h1>

<p align="center">
  A lightweight Python script that converts one currency to another using real-time exchange rates via the <a href="https://apilayer.com/marketplace/fixer-api" target="_blank">Fixer API</a>.  
  Great for beginners practicing APIs and input validation.
</p>

<p align="center">
  <img src="https://media.giphy.com/media/26FPnsRww3oQWmvHG/giphy.gif" width="300" alt="Money gif" />
</p>

---

<h2> How It Works</h2>
<ol>
  <li>The user is prompted to enter:</li>
  <ul>
    <li>Initial currency code (e.g., USD)</li>
    <li>Target currency code (e.g., EUR)</li>
    <li>Amount to convert</li>
  </ul>
  <li>The script sends a GET request to the Fixer API</li>
  <li>If successful, the result is shown like: <code>100 USD = 91.28 EUR</code></li>
  <li>If the API fails or invalid input is given, proper error messages are displayed</li>
</ol>

---

<h2> How to Run</h2>

<p><strong> Requirements:</strong></p>
<ul>
  <li>Python 3</li>
  <li><code>requests</code> module (comes pre-installed with most Python setups)</li>
  <li>A free API key from <a href="https://apilayer.com/marketplace/fixer-api">Fixer.io</a></li>
</ul>

<p><strong>Run the Script</strong></p>

python currency_converter.py
<h2>Example Output</h2>

Enter an initial currency: USD
Enter a target currency: EGP
Enter the amount: 50

50.0 USD = 2410.15 EGP
<h2> Technologies Used</h2> 
<ul> 
  <li> Python 3</li>
  <li> requests — for API requests</li> 
  <li> Fixer API — for real-time currency conversion</li>
</ul>
<h2>👨‍💻 Author</h2> <p>Made  by Youssef Talaat</p> 
