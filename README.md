# Clearvision Addons
<p>Addons created for Clearvision theme. Might not work properly with other themes</p>

<h2>Transparency</h2>
<p>Makes your Discord transparent. Maintained by Nyx.</p>

<h3>Usage</h3>
<ol>
  <li>Copy and paste <code>@import url(https://clearvision.github.io/Addons/transparency.css);</code> below the other imports</li>
  <li>Change your --background-image variable to <code>transparent</code>: 
    <pre><code>--background-image: transparent; /* app background image (link must be HTTPS) [default: url(https://clearvision.github.io/images/sapphire.jpg)]</code></pre></li>
  <li>Make sure to toggle the background transparency toggle in BetterDiscord settings if you are on that, or any other relevant toggle if you are on another injector that supports transparency.</li>
</ol>
<br>

<h2>Gradients</h2>
<p>Adds gradients to various parts of the theme to make it more colourful. Maintained by Nyx.</p>

<h3>Usage</h3>
<ol>
  <li>Copy and paste <code>@import url(https://clearvision.github.io/Addons/gradients.css);</code> below the other imports</li>
  <li>Add the following at the bottom inside of root: 
    <pre><code>/* Gradients */
    --gradient-color1: var(--main-color); /* primary color [default: var(--main-color) */
    --gradient-color2: var(--hover-color); /* secondary color [default: var(--hover-color) */
    --gradient-direction: 130deg; /* angle of gradient [default: 130deg] */</code></pre></li>
  <li>Change the values to customize it and you're done</li>
</ol>
<br>
<h2>Old Discord Font</h2>
<p>Use the old discord font, Whitney. Maintained by Nyx, credit to @Overimagine1 for providing the new version of files and script. The old clearvision whitney script is obsolete due to missing characters</p>
<h3>Usage</h3>
<ol>
  <li>Copy and paste <code>@import url(https://clearvision.github.io/Addons/whitney.css);</code> below the other imports</li>
  <li>Now, change your main-font back to Whitney (this looks like <code>--main-font: Whitney, Helvetica Neue, Helvetica, Arial, sans-serif;</code>)</li>
</ol>
<br>
<h2>Speech Bubbles - DEPRECATED</h2>
<p>Displays text in chat as speech bubbbles. <s>Maintained by Leo</s></p>
<h3>Usage</h3>
<ol>
  <li>Copy and paste <code>@import url(https://clearvision.github.io/Addons/speech-bubbles.css);</code> below the other imports</li>
  <li><b>Optional:</b> to change the colors add the following at the bottom inside of root: 
    <pre><code>/* Speech Bubbbles */
    --bubble-color: #fff;
    --bubble-hover-color: #fff:</code></pre></li>
</ol>

