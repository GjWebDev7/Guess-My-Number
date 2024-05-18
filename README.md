# Guess-My-Number
<h1>Guess My Number Game</h1>
<p>Welcome to the "Guess My Number" game! This project is a simple number guessing game where the player tries to guess a randomly generated number between 1 and 20. The game provides feedback on whether the guess is too high or too low, and tracks the player's score and high score.</p>
<h2>Table of Contents</h2>
<ul>
  <li><a href="#introduction">Introduction</a></li>
  <li><a href="#features">Features</a></li>
  <li><a href="#technologies-used">Technologies Used</a></li>
  <li><a href="#setup">Setup</a></li>
  <li><a href="#how-to-play">How to Play</a></li>
  <li><a href="#project-structure">Project Structure</a></li>
  <li><a href="#contributing">Contributing</a></li>
  <li><a href="#license">License</a></li>
</ul>

<h2 id="introduction">Introduction</h2>
<p>This project is designed to demonstrate basic DOM manipulation and event handling in JavaScript, as well as responsive web design using HTML and CSS. It can be used as a fun game to play or as a learning tool for beginners in web development.</p>

<h2 id="features">Features</h2>
<ul>
  <li>Random number generation between 1 and 20.</li>
  <li>User input for guessing the number.</li>
  <li>Feedback messages for too high, too low, and correct guesses.</li>
  <li>Score tracking and high score storage.</li>
  <li>Responsive design for different screen sizes.</li>
</ul>

<h2 id="technologies-used">Technologies Used</h2>
<ul>
  <li>HTML5</li>
  <li>CSS3</li>
  <li>JavaScript (ES6)</li>
</ul>

<h2 id="setup">Setup</h2>
<p>To run this game locally, follow these steps:</p>
<ol>
  <li>Clone the repository:
    <pre><code>git clone https://github.com/yourusername/guess-my-number.git</code></pre>
  </li>
  <li>Navigate to the project directory:
    <pre><code>cd guess-my-number</code></pre>
  </li>
  <li>Open the <code>index.html</code> file in your preferred web browser:
    <pre><code>open index.html</code></pre>
  </li>
</ol>

<h2 id="how-to-play">How to Play</h2>
<ol>
  <li>The game generates a random secret number between 1 and 20.</li>
  <li>Enter your guess in the input field and click the "Check!" button.</li>
  <li>The game will provide feedback:
    <ul>
      <li>If the guess is too high, a "📈 Too High!" message appears.</li>
      <li>If the guess is too low, a "📉 Too Low!" message appears.</li>
      <li>If the guess is correct, a "🎉 Correct Number!" message appears, and the background color changes.</li>
    </ul>
  </li>
  <li>The score decreases with each incorrect guess.</li>
  <li>If the score reaches zero, a "💥 You lost the game" message appears, and the game ends.</li>
  <li>Click the "Again!" button to restart the game with a new secret number and reset the score.</li>
</ol>

<h2 id="project-structure">Project Structure</h2>
<pre><code>guess-my-number/
├── index.html
├── styles.css
└── script.js
</code></pre>

<ul>
  <li><code>index.html</code>: The main HTML file that contains the structure of the game.</li>
  <li><code>styles.css</code>: The CSS file that contains styles and responsive design rules.</li>
  <li><code>script.js</code>: The JavaScript file that contains the game logic and DOM manipulation.</li>
</ul>

<h2 id="contributing">Contributing</h2>
<p>Contributions are welcome! If you have any suggestions or improvements, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.</p>

<ol>
  <li>Fork the repository.</li>
  <li>Create a new branch (<code>git checkout -b feature-branch</code>).</li>
  <li>Commit your changes (<code>git commit -am 'Add new feature'</code>).</li>
  <li>Push to the branch (<code>git push origin feature-branch</code>).</li>
  <li>Open a pull request.</li>
</ol>

<h2 id="license">License</h2>
<p>This project is licensed under the MIT License. See the <code>LICENSE</code> file for more details.</p>
