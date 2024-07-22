# Sonstiges

<tabs>
<tab title="Befehle" id="plot-commands">

<deflist>
<def title="Besitzer herausfinden" id="plot-get-owner">
Um den Besitzer eines Grundstücks herauszufinden, nutze den Befehl `/pwho` während du auf einem Grundstück stehst.
</def>
</deflist>

<deflist>
<def title="Feststecken" id="plot-unstuck">

Solltest du auf einem fremden Grundstück feststecken, kannst du `/unstuck` verwenden, um wieder
zum Spawn zu gelangen.
> Der Missbrauch dieses Befehls wird als Exploiting gewertet und bestraft!
>
{style="warning"}
</def>
</deflist>
</tab>

<tab title="Weiteres" id="plot-other">
<deflist>
<def title="Grundstücksnachrichten" id="plot-messages">  

Beim Betreten oder Verlassen eines Grundstückes bekommst du im Chat eine Nachricht.
Diese Funktion lässt sich jedoch ein- oder ausschalten.
1. Führe hierzu den Befehl `/protect` im Chat aus.
2. Klicke anschließend auf die Lederschuhe. ![toggle plotmessage](plot-toggle-plotmessage.png)
</def>
</deflist>
</tab>

<tab title="Berechnung" id="plot-calculation">

<deflist>
<def title="Berechnung des Grundstückes" id="plot-price-calculation">

````tex
\begin{align*}
p(x) &= \max\left(4, \left\lfloor -0.0016666666667 \times x + 12.3333333333 \right\rceil \right) \\
x &= \text{Distanz zum Spawn in Blöcken}
\end{align*}
````
Hierbei gilt:
- `p(x)` ist der berechnete Preis pro Block.
- `x` ist die Distanz vom Grundstück zum Spawn, gemessen in Blöcken.
- `⌊...⌉` bedeutet runden.
</def>
</deflist>

</tab>
</tabs>