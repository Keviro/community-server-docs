# Sonstiges


<tabs>
<tab title="Befehle">
<deflist>
<def title="Besitzer herausfinden">
Um den Besitzer eines Grundstücks herauszufinden, nutze <code>/pwho</code> während du auf einem Grundstück stehst.
</def>
<def title="Feststecken">
Solltest du auf einem fremden Grundstück feststecken, kannst du <code>/unstuck</code> verwenden, um wieder zum Spawn zu gelangen.
<warning>Der Missbrauch dieses Befehls um zum Spawn zu gelangen wird als Exploiting gewertet und bestraft!</warning>
</def>
</deflist>
</tab>

<tab title="Weiteres">
<procedure title="Grundstücknachrichten">
<p>
Beim Betreten oder Verlassen eines Grundstückes bekommst du im Chat eine Nachricht.
Diese Funktion lässt sich jedoch ein- oder ausschalten.
</p>
<step>
<p>
Führe hierzu den Befehl <code>/protect </code> im Chat aus.
</p>
</step>
<step>
Klicke anschließend auf die Lederschuhe.
<img src="plot-toggle-plotmessage.png" alt="toggle plotmessage"/>
</step>
</procedure>
</tab>

<tab title="Berechnung">
<deflist>
<def title="Berechnung des Grundstückes">
<code-block lang ="tex">
\begin{align*}
p(x) &= \max\left(4, \left\lfloor -0.0016666666667 \times x + 12.3333333333 \right\rceil \right) \\
x &= \text{Distanz zum Spawn in Blöcken}
\end{align*}
</code-block>
Hierbei gilt:
<ul>
    <li> <code>p(x)</code> ist der berechnete Preis pro Block. </li>
    <li> <code>x</code> ist die Distanz vom Grundstück zum Spawn, gemessen in Blöcken. </li>
    <li> <code>⌊...⌉</code> bedeutet runden. </li>
</ul>
</def>
</deflist>
</tab>
</tabs>