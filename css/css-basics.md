<h1>CSS-Basics</h1>

<p>CSS ist eine deklarative Sprache und steuert, wie Websiten im Browser aussehen</p>
<br>
<p>Der Begriff Kaskadierung beschreibt, wie CSS entscheidet, welcher Style am Ende für ein Element gilt, wenn mehrere Styles gleichzeitig zutreffen.
CSS „kaskadiert“ also die Regeln — ähnlich wie Wasser, das über mehrere Ebenen fließt, bis es unten ankommt.
</p>
<br>
<p class="highlight"><strong>Warum also Kaskadierung</strong>
Weil CSS alle Regeln wie eine Kaskade von oben nach unten auswertet und am Ende entscheidet:<br>
Welche Regel ist am spezifischsten, steht zuletzt und passt am besten?<br>

So kann man viele Styles definieren, ohne dass sie sich gegenseitig vollständig überschreiben — die Kaskade sorgt für Ordnung.

</p>
<br>
<ol>
    <li>Spezifität</li>
    <li>Reihenfolge im stylesheet</li>
    <li>Vererbung</li>
</ol>
<br>
<h4>Spezifität</h4>
<p>Je genauer der Selektor ist, desto wichtiger ist seine Regel.<br>
Entscheidet darüber, welche CSS Regel am Ende gewinnt,  <br>
wenn Regeln auf das gleiche Element zutreffen. <br>
Beispiel (von schwach -> stark):<br>
<ul>
    <li>p (Typselektor)</li>
    <li>.info (Klassenselektro)</li>
    <li>#header (ID Selektor)</li>
    <li>style="..." (inline Styles)</li>
</ul>
<br>
<h4>Reihenfolge im Stylesheet<h4>
<p>Wenn zwei Regeln gleich spezifisch sind, gewinnt die zuletzt geschriebene.</p>
<br>
<h4>Vererbung<h4>
<p>Einige CSS-Eigenschaften werden automatisch vom Eltern-Element an Kinder weitergegeben, z. B.: <br>
<ul>
    <li>color</li>
    <li>font-size</li>
    <li>font-family</li>
</ul>
<br>
<p>Wenn ein Kindelement keinen eigenen Wert hat, übernimmt es den Wert des Elternteils.</p>
<br>
<h2>Was macht CSS</h2>
<p>CSS-Regeln werden auf ein HTML-Element angewendet und legen fest, <br>
wie der Inhalt angezeigt werden soll.<br>
Dabei besteht eine CSS Regel aus zwei Teilen:
<br>
einem <em>Selektor</em> und einer <em>Deklaration</em>.
</p>

<p>
<strong>Selektor = p</strong> Deklaration = {font-family: Arial;}
<br>
p { <br>
    font-family: Arial; <br>
}
<br>
</p>
<p> Diese Regel besagt, dass alle <p> Elemente in der Schriftart Arial angezeigt werden soll!</p>
<br>
<strong>Selektoren</strong> geben an, auf welches Element die Regel angewandt werden soll. <br>
Eine Regel kann auch auf mehrere Elemente gelten, wenn die einzelnen Elementnamen durch Kommata getrennt angegeben werden</p>
