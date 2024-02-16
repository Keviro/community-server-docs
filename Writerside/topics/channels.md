# Textkanäle

Auf dem Server kannst du eigene Textkanäle erstellen oder beitreten.
In diesen kannst du zum Beispiel mit mehreren Freunden oder Spielern auf dem Server schreiben.
Dies ist sehr nützlich, wenn du mit mehreren Spielern gleichzeitig schreiben willst.
Somit erleichtert dieses Feature zum Beispiel die Kommunikation in gemeinsamen Bauprojekten mit
vielen Spielern aus der Community oder bietet einen einfachen Chatraum, welcher neben dem
öffentlichen Chat existiert.
Du kannst hierbei selbst entscheiden, wer deinen Textkanal betreten kann, und wer nicht.

## Befehle

<tabs>


<tab title="Erstellen und Benennen">
<deflist style="wide">
<def title="/channel create <name> [passwort]">
<a href="channels.md#channel-create" summary="%click-more-info%">Erstelle deinen Textkanal</a>
</def>
<def title="/channel rename <channel> <name>">
<a href="#channel-rename" summary="%click-more-info%">Benenne deinen Textkanal um</a>
</def>
</deflist>

<p>­</p>

<deflist>
<def title="Textkanal erstellen" id="channel-create">
Um deinen eigenen Textkanal zu erstellen,
benutze den Befehl <code>/channel create &lt;name&gt; [passwort] </code>.
Alternativ kannst du auch noch ein Passwort anfügen, damit nicht jeder Spieler bem Kanal beitreten kann.
Dieses ist jedoch optional und nicht zwingend notwendig.
<tip>
Zum Beispiel: <code>/channel create Bauteam Passwort123</code>
</tip>
</def>
<def title="Textkanal umbenennen" id="channel-rename">
Um deinen Textkanal umzubenennen, benutze den Befehl <code>/channel rename &lt;channel&gt; &lt;name&gt;</code>.
<note>
Hierzu musst du Inhaber des Textkanals sein.
</note>
<tip>
Zum Beispiel: <code>/channel rename Bauteam Affenbande</code>
</tip>
</def>
</deflist>
</tab>



<tab title="Teilnahme und Auswahl">
<deflist style="wide">
<def title="/channel join <channel>">
<a href="#channel-join" summary="%click-more-info%">Trete einem Textkanal bei</a>
</def>
<def title="/channel select <channel>">
<a href="#channel-select" summary="%click-more-info%">Wähle einen Textkanal aus</a>
</def>
<def title="/channel leave <channel>">
<a href="#channel-leave" summary="%click-more-info%">Verlasse einen Textkanal</a>
</def>
</deflist>

<p>­</p>

<deflist>
<def title="Textkanäle beitreten" id="channel-join">
Mit dem Befehl <code>/channel join &lt;channel&gt;</code> kannst du verschiedenen Textkanäle betreten. Wenn ein Passwort für den Channel gesetzt ist, musst dieses auch angeben. 
</def>
<def title="Textkanal auswählen" id="channel-select">
Um einen Textkanal auszuwählen, nutze <code>/channel select &lt;channel&gt;</code>.
</def>
<def title="Textkanal verlassen" id="channel-leave">
Um einen Textkanal zu verlassen, benutze den Befehl <code>/channel leave &lt;channel&gt;</code>.
</def>
</deflist>
</tab>



<tab title="Mitgliederverwaltung">
<deflist style="wide">
<def title="/channel invite <channel> <player>">
<a href="#channel-invite" summary="%click-more-info%">Lade Spieler in deinen Textkanal ein</a>
</def>
<def title="/channel kick <player>">
<a href="#channel-kick" summary="%click-more-info%">Entferne Spieler aus deinem Textkanal</a>
</def>
</deflist>

<p>­</p>

<deflist>
<def title="Mitglieder hinzufügen" id="channel-invite">
Um deinem Textkanal Mitglieder hinzuzufügen, ohne ihnen das Passwort zu verraten, kannst du sie einladen.
Hierzu erstellst du eine Einladung mit dem Befehl <code>/channel invite &lt;channel&gt; &lt;player&gt;</code>.
<note>
Hierzu musst du Inhaber des Textkanals sein.
</note>
<tip>
Zum Beispiel: <code>/channel invite Testkanal Twisti_Twixi</code>
</tip>
Der jeweilige Spieler erhält nun eine Benachrichtigung und wird in den Kanal hinzugefügt, sobald er sie annimmt.
<img src="channel-invite.png" alt="Alt text" width="500" border-effect="rounded"/>
</def>
<def title="Mitglieder entfernen" id="channel-kick">
Um Mitglieder aus deinem Textkanal zu entfernen, benutze den Befehl <code>/channel kick &lt;player&gt;</code>.
<note>
Hierzu musst du Inhaber des Textkanals sein.
</note>
<tip>
Zum Beispiel: <code>/channel kick Twisti_Twixi</code>
</tip>
</def>
</deflist>
</tab>



<tab title="Information">
<deflist style="wide">
<def title="/channel list">
<a href="#channel-list" summary="%click-more-info%">Textkanäle im Überblick</a>
</def>
</deflist>

<p>­</p>

<deflist>
<def title="Textkanal anzeigen" id="channel-list">
Um dir alle Textkanäle anzuzeigen, in denen du Mitglied bist, benutze den Befehl <code>/channel list</code>.
</def>
</deflist>
</tab>
</tabs>