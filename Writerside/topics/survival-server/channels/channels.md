<show-structure depth="0"/>

# Textkanäle

Auf dem Server kannst du eigene Textkanäle erstellen und beitreten, um mit Freunden oder anderen
Spielern zu kommunizieren. Dies erleichtert die Koordination in gemeinsamen Projekten oder bietet
einen privaten Raum für Gespräche neben dem öffentlichen Chat. Du kannst selbst entscheiden, wer
deinen Textkanal betreten darf.

## Befehle

<tabs>


<tab title="Erstellen und Benennen">

/channel create &lt;name> [passwort]
: [Erstelle deinen Textkanal](channels.md#channel-create "%click-more-info%")

/channel rename &lt;channel> &lt;name>
: [Benenne deinen Textkanal um](channels.md#channel-rename "%click-more-info%")

­

<deflist>
<def title="Textkanal erstellen" id="channel-create">

Um deinen eigenen Textkanal zu erstellen, benutze den Befehl `/channel create <name> [passwort]`.
Ein optionales Passwort kann hinzugefügt werden, um den Zugang zu beschränken.

- Beispiel: `/channel create Bauteam Passwort123`

</def>
<def title="Textkanal umbenennen" id="channel-rename">

Um deinen Textkanal umzubenennen, benutze den Befehl `/channel rename <channel> <name>`.

- Beispiel: `/channel rename Bauteam Affenbande`

> Hierzu musst du Inhaber des Textkanals sein.
>
>
</def>
</deflist>
</tab>

<tab title="Teilnahme und Auswahl">

/channel join &lt;channel>
: [Trete einem Textkanal bei](channels.md#channel-join "%click-more-info%")

/channel select &lt;channel>
: [Wähle einen Textkanal aus](channels.md#channel-select "%click-more-info%")

/channel leave &lt;channel>
: [Verlasse einen Textkanal](channels.md#channel-leave "%click-more-info%")

­

<deflist>
<def title="Textkanäle beitreten" id="channel-join">

Mit dem Befehl `/channel join <channel>` kannst du verschiedenen Textkanäle betreten.
Wenn ein Passwort für den Channel gesetzt ist, musst dieses auch angeben.
</def>
<def title="Textkanal auswählen" id="channel-select">

Um einen Textkanal auszuwählen, nutze `/channel select <channel>`.
</def>
<def title="Textkanal verlassen" id="channel-leave">

Um einen Textkanal zu verlassen, benutze den Befehl `/channel leave <channel>`.
</def>
</deflist>
</tab>


<tab title="Mitgliederverwaltung">

/channel invite &lt;channel> &lt;player>
: [Lade Spieler in deinen Textkanal ein](channels.md#channel-invite "%click-more-info%")

/channel kick &lt;player>
: [Entferne Spieler aus deinem Textkanal](channels.md#channel-kick "%click-more-info%")

­

<deflist>
<def title="Mitglieder hinzufügen" id="channel-invite">

Mit `/channel invite <channel> <player>` lädst du Spieler in deinen Kanal ein, ohne das Passwort
teilen zu müssen. Der jeweilige Spieler erhält nun eine Benachrichtigung und wird in den Kanal
hinzugefügt, sobald er sie annimmt.

- Beispiel: `/channel invite Bauteam Twisti_Twixi`

> Hierzu musst du Inhaber des Textkanals sein.
>
{style="note"}

![Channel Invite](channel-invite.png) {width="500" border-effect="rounded"}

</def>
<def title="Mitglieder entfernen" id="channel-kick">

Um Mitglieder aus deinem Textkanal zu entfernen, benutze den Befehl **/channel kick &lt;player>**.

- Beispiel: `/channel kick Twisti_Twixi`

> Hierzu musst du Inhaber des Textkanals sein.
>
{style="note"}

</def>
</deflist>
</tab>

<tab title="Information">

/channel list
: [Textkanäle im Überblick](channels.md#channel-list "%click-more-info%")

­

<deflist>
<def title="Textkanal anzeigen" id="channel-list">

Um dir alle Textkanäle anzuzeigen, in denen du Mitglied bist, benutze den Befehl `/channel list`.
</def>
</deflist>
</tab>
</tabs>