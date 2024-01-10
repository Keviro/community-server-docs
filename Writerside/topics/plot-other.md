# Sonstiges

## Sonstige Befehle

<deflist>
<def title="Besitzer herausfinden">
Um den Besitzer eines Grundstücks herauszufinden, nutze <code>/pwho</code> während du auf einem Grundstück stehst.
</def>
<def title="Feststecken">
Solltest du auf einem fremden Grundstück feststecken, kannst du <code>/unstuck</code> verwenden, um wieder zum Spawn zu gelangen.
<warning>Der Missbrauch dieses Befehls um zum Spawn zu gelangen wird als Exploiting gewertet und bestraft!</warning>
</def>
</deflist>

## Berechnungen

### Grundstückspreis:

````tex
\begin{align*}
x &= \text{Distanz zum Spawn in Blöcken} \\
p(x) &= \max\left(4, \left\lfloor -0.0016666666667 \times x + 12.3333333333 \right\rceil \right)
\end{align*}
````
Hierbei:
- `x` ist die Distanz vom Grundstück zum Spawn, gemessen in Blöcken.
- `p(x)` ist der berechnete Preis pro Block.
- `⌊...⌉` bedeutet runden