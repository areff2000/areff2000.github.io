---
published: true
title: Valuing FTTN FTTP - Aster plot - multidimensional and weighted
layout: post
---
Creating a visualisation of FTTN vs FTTP, using an Aster Plot.<br>
<b>Strengths</b>: An Aster plot is multi-dimensional like a radar plot, but can assign a weighting to dimensions.<br>
<b>Weakness</b>: An Aster plot can only show one Value target at a time. Perhaps I can overlay with photoshop...<br>
<b>Update</b>: below I placed two Aster plots side by side, using iframes inside an html table...<br>

Data:  (Author's rating of FTTN FTTP value dimensions)<br><a href="http://areff2000.github.io/d3-bubble-plot/valueFlower/aster_dataFTTN.csv">http://areff2000.github.io/d3-bubble-plot/valueFlower/aster_dataFTTN.csv</a><br>
<a href="http://areff2000.github.io/d3-bubble-plot/valueFlower/aster_dataFTTN.csv">http://areff2000.github.io/d3-bubble-plot/valueFlower/aster_dataFTTP.csv</a>

Content at: 
<ul>
<li>
<a href="http://areff2000.github.io/d3-bubble-plot/valueFlower/indexFTTP.html">http://areff2000.github.io/d3-bubble-plot/valueFlower/indexFTTP.html</a> 
</li><li>
<a href="http://areff2000.github.io/d3-bubble-plot/valueFlower/indexFTTN.html">http://areff2000.github.io/d3-bubble-plot/valueFlower/indexFTTN.html</a>
</li></ul>

<p>To amend the data, and play with the Aster Chart, you need the following files:<br>
Download the files at: <a href="https://github.com/areff2000/d3-bubble-plot/tree/gh-pages/valueFlower">https://github.com/areff2000/d3-bubble-plot/tree/gh-pages/valueFlower</a><br>
style.css | <br>
Data: aster_dataFTTN.csv | aster_dataFTTP.csv<br>
Javascript: drawFTTN.js | drawFTTP.js<br>
Html: indexFTTN.html | indexFTTP.html<br>
Table to draw together two html files into a table with iframe: <a href="http://areff2000.github.io/d3-bubble-plot/valueFlower/valueFlower.html">valueFlower.html</a> (html in this page; View Source)</p>

Discussed at: <a href="http://bit.ly/1RiaCpo">http://bit.ly/1RiaCpo</a>; Rating of value dimensions in Table 1.<br>
Aster diagram; multidimensional, dimensions vary in weight; scores 0 (Max.) - 100 (Min.)
<ul>
<li>Closer to centre indicates more value.</li>
<li>Lower score (in bullseye) indicates more value.</li>
<ul>

<table>
<th>FTTP</th><th>FTTN</th>
<tr><td>
<iframe width="600" height="600" frameborder="0" scrolling="no" src="http://areff2000.github.io/d3-bubble-plot/valueFlower/indexFTTP.html"></iframe>
</td>
<td>
<iframe width="600" height="600" frameborder="0" scrolling="no" src="http://areff2000.github.io/d3-bubble-plot/valueFlower/indexFTTN.html"></iframe>
</td>
</tr>
<tr><td>
Key: Dimensions (weight):<br><br>
CAPEX 			(25)[Red]<br>
Future CAPEX 	(10)<br>
Time to rollout (25)<br>
Life of Asset 	(25)<br>
OPEX / Revenue 	(20) <br>
Current need 	(10)<br>
Future need 	(25)<br>
Reliability 	(30)<br>
Equity 			(10)<br>
Simplicity 		(5)<br>
Beauty 			(5)<br>
Unknown Unknowns(25)[Blue]<br>
</td><td>NB: closer to the bullseye is higher value<br>Data: weightings and ratings are author's assessment.<br> Bullseye rating is summary overall; the lower the better.</td></tr>
</table>

