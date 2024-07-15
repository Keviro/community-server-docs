# Sonstiges

<tabs>
<tab title="Befehle">

Besitzer herausfinden
: Um den Besitzer eines Grundstücks herauszufinden, nutze `/pwho` während du auf einem Grundstück
stehst.

<deflist>
<def title="Feststecken">

Solltest du auf einem fremden Grundstück feststecken, kannst du **/unstuck** verwenden, um wieder
zum Spawn zu gelangen.
> Der Missbrauch dieses Befehls, um zum Spawn zu gelangen, wird als Exploiting gewertet und bestraft!
>
{style="warning"}
</def>
</deflist>
</tab>

<tab title="Weiteres">

Grundstücknachrichten
: Beim Betreten oder Verlassen eines Grundstückes bekommst du im Chat eine Nachricht.
Diese Funktion lässt sich jedoch ein- oder ausschalten.
1. Führe hierzu den Befehl `/protect` im Chat aus.
2. Klicke anschließend auf die Lederschuhe. ![toggle plotmessage](plot-toggle-plotmessage.png)

</tab>

<tab title="Berechnung">

Berechnung des Grundstückes
: 
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

</tab>
</tabs>