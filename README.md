<h1>JS find a pair game for web</h1>

![image](https://user-images.githubusercontent.com/63814143/219867063-e7417144-b592-453f-8e77-4ff0e330efd4.png)

<h2>Installing</h2>
<ol>
<li>Add css file "findpgame.css" and js file "findpgame.js" to your page</li>
<li>Add "div" block with class "find-p-game" to your page, in place where you need this game</li>
<li>To "div" with class "find-p-game" add tags "img" with images, that you need for game (it will be cards in game)</li>
</ol>

<div>It will be somethihg like:</div>
<code>
    &lt;div class="find-p-game" data-findpgame-col="4" data-win-text="You win!" data-restart-btn="Restart"
        data-findpgame-cover="img/cover.svg"&gt;<br>
        &lt;img src="img/1.svg"&gt;<br>
        &lt;img src="img/2.svg"&gt;<br>
        &lt;img src="img/3.svg"&gt;<br>
        &lt;img src="img/4.svg"&gt;<br>
        &lt;img src="img/5.svg"&gt;<br>
        &lt;img src="img/6.svg"&gt;<br>
        &lt;img src="img/7.svg"&gt;<br><br>
        &lt;img src="img/8.svg"&gt;<br>
    &lt;/div&gt;<br>
</code>

<h2>Options</h2>
There are four parameters for setting your game. They all are attributes for "div" block with class "find-p-game".
<ol>
<li><b>data-findpgame-col</b> &mdash; set number of square columns. Default value "4".<br>
<b>Important!</b> If number of your images is less than number of cell in the square, the game add cells with random color to square.<br>
<b>Important!(2)</b>I didn't still add a lot of colors in array with random colors, so feature upper is corectly work for squares with number of columns five maximum :).
</li>
<li><b>data-win-text</b> &mdash; text for win screen. Default value "You win!"</li>
<li><b>data-restart-btn</b> &mdash; text for restart button on win screen. Default value "Restart"</li>
<li><b>data-findpgame-cover</b> &mdash; path for custom card cover. If it's empty, card cover will have background with #FFC061 color</li>
</ol>

<h2>Try it!</h2>
<a href="https://okeok.github.io/projects/find-a-pair-game/"></a>
