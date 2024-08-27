<h1>Drum Kit</h1>

<p>This is a simple web-based drum kit application that allows users to play different drum sounds by either clicking on drum buttons or pressing specific keys on their keyboard. The project is built using HTML, CSS, and JavaScript.</p>

<h2>Features</h2>
<ul>
    <li><strong>Interactive Drum Buttons:</strong> Users can click on drum buttons to play corresponding drum sounds.</li>
    <li><strong>Keyboard Support:</strong> Users can press specific keys (W, A, S, D, J, K, L) to play drum sounds.</li>
    <li><strong>Visual Feedback:</strong> When a drum button is pressed, it briefly animates to indicate activation.</li>
</ul>

<h2>How It Works</h2>
<ul>
    <li>Each drum button is associated with a specific sound file.</li>
    <li>When a user clicks a drum button or presses a corresponding key, a JavaScript function is triggered that plays the appropriate sound.</li>
    <li>The application also provides a brief animation to visually indicate the button press.</li>
</ul>

<h2>Getting Started</h2>

<h3>Prerequisites</h3>
<p>You only need a web browser to run this project.</p>

<h3>Installation</h3>

<p><strong>Clone the Repository:</strong></p>
<pre><code>git clone https://github.com/pranav7368/drum-kit.git</code></pre>

<p><strong>Navigate to the Project Directory:</strong></p>
<pre><code>cd drum-kit</code></pre>

<p><strong>Open <code>index.html</code> in your web browser.</strong></p>

<h2>Usage</h2>

<p><strong>Click on the drum buttons</strong> to play the drum sounds.</p>
<p><strong>Press the following keys</strong> on your keyboard to play the corresponding sounds:</p>
<ul>
    <li><strong>W:</strong> Tom 1</li>
    <li><strong>A:</strong> Tom 2</li>
    <li><strong>S:</strong> Tom 3</li>
    <li><strong>D:</strong> Tom 4</li>
    <li><strong>J:</strong> Crash</li>
    <li><strong>K:</strong> Snare</li>
    <li><strong>L:</strong> Kick Bass</li>
</ul>

<h2>Project Structure</h2>
<pre><code>drum-kit/
├── sounds/
│   ├── crash.mp3
│   ├── kick-bass.mp3
│   ├── snare.mp3
│   ├── tom-1.mp3
│   ├── tom-2.mp3
│   ├── tom-3.mp3
│   └── tom-4.mp3
├── index.html
├── styles.css
└── script.js
</code></pre>

<h2>JavaScript Functions</h2>
<ul>
    <li><code>makeSound(key)</code>: Plays the corresponding drum sound based on the key/button pressed.</li>
    <li><code>addAnimation(currentKey)</code>: Adds a brief animation to the button to indicate it has been pressed.</li>
</ul>

<h2>License</h2>
<p>This project is licensed under the MIT License. See the LICENSE file for more details.</p>

<h2>Acknowledgments</h2>
<p>This project was inspired by the need to practice JavaScript event handling and DOM manipulation.</p>

