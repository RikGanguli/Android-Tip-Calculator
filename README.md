<h1>Tip Calculator App</h1>

<p>This Android app assists users in calculating the total dining cost including a selected tip, and allows for splitting the total evenly among multiple people. The app is developed using Java in Android Studio and supports both portrait and landscape orientations with consistent behavior.</p>

<h2>Features</h2>
<ul>
  <li>Calculates the total cost of a meal including the tip.</li>
  <li>Allows the user to select from four tip percentage options: 12%, 15%, 18%, and 20%.</li>
  <li>Splits the total cost (with tip) evenly among a specified number of people.</li>
  <li>Rounds the amount per person up to the nearest cent.</li>
  <li>Responsive UI in both portrait and landscape orientations using ConstraintLayout.</li>
  <li>Keeps calculated values intact when switching between portrait and landscape orientations.</li>
  <li>Clear button resets all input fields and calculations.</li>
</ul>

<h2>Inputs</h2>
<ul>
  <li><b>Bill Total:</b> Positive whole or decimal number.</li>
  <li><b>Tip Percentage:</b> Select from 12%, 15%, 18%, or 20% using radio buttons.</li>
  <li><b>Number of People:</b> Positive whole number (no zero or decimal values).</li>
</ul>

<h2>Output</h2>
<ul>
  <li><b>Tip Amount:</b> The tip calculated based on the selected percentage.</li>
  <li><b>Total with Tip:</b> The total bill including the tip.</li>
  <li><b>Amount per Person:</b> The total cost divided evenly, rounded up to the nearest cent.</li>
</ul>

<h2>Behavior</h2>
<ul>
  <li>If the <b>Bill Total</b> is empty, selecting a tip percentage will do nothing, and the selected tip percentage radio button will be automatically unselected.</li>
  <li>Pressing the "GO" button calculates the amount per person and displays the value in the designated field, rounding up to the nearest cent.</li>
  <li>Pressing the "Clear" button resets all input fields, unchecks the radio buttons, and clears all calculated fields.</li>
</ul>

<h2>Landscape Layout</h2>
<p>The app includes a separate landscape layout to ensure optimal user experience on devices in landscape mode. No data is lost when rotating between orientations, and the calculated values (Tip Amount, Total with Tip, and Amount per Person) remain intact.</p>

<h2>Installation</h2>
<ol>
  <li>Clone this repository:</li>
  <pre><code>git clone https://github.com/RikGanguli/Android-Tip-Calculator.git</code></pre>
  <li>Open the project in Android Studio.</li>
  <li>Build the project and run the app on an emulator or physical device.</li>
</ol>

<h2>Requirements</h2>
<ul>
  <li>Android Studio (4.x or higher)</li>
  <li>Java 8 or higher</li>
</ul>

<h2>Usage</h2>
<ol>
  <li>Enter the total bill amount.</li>
  <li>Select a tip percentage from the radio buttons.</li>
  <li>Enter the number of people to split the bill.</li>
  <li>Tap the "GO" button to calculate the total per person.</li>
  <li>Use the "Clear" button to reset all values.</li>
</ol>

<h2>Credits</h2>
<p>Developed by Rik Ganguli Biswas</p>
