<style type="text/css">
kbd {
    background-color: white;
    border: 1px solid black;
    padding-left: 3px;
    padding-right: 3px;
    border-radius: 4px;
    font-family: Courier New, courier, monospace;
    box-shadow: 1px 1px;
}
</style>

## Bildschirmeinrichtung

Die zur Zeit beliebten Bildschirme im Format 16:9 eignen sich für
Textverarbeitungsanwendungen, in denen hauptsächlich mit Hochformat gearbeitet wird,
nur bedingt. Sie sind sehr breit, dafür fehlt es aber an Höhe.

Dadurch, dass im Normalfall auch die Fensterleiste entlang der unteren Bildschirmkante
angeordnet ist, bietet es sich an, die Fensterleiste an den rechten oder linken Rand
des Bildschirmes zu verschieben.

Ähnlich kann auch mit einigen der gestapelt vorhandenen Icon- und Menüeleisten in
LibreOffice verfahren werden. So ist es möglich, volle A4-Seiten zumindest quer zu
lesen, ohne Scrollen zu müssen.

## Betriebssystem

### Copy & Paste

Im EIP wird oft zwischen einzelnen Fenstern Text kopiert. Während das unter anderen Betriebsystemen besser gelöst ist, bietet Windows 10 zumindest eine durchaus sinnvolle Funktion an: Die Zwischenablage kann nun nicht nur eine sondern bis zu 25 Textschnippsel aufnehmen. Eingefügt wird in diesem Fall nicht mit <kbd>Strg + v</kbd> sondern <kbd>Windows + v</kbd>.

Diese Funktion muss aber erst aktiviert werden. Das macht man in den Systemeinstellungen unter "System" und dem Menüpunkt "Zwischenablage".

"Auf allen Geräten synchronisieren" würde ich aber nicht aktivieren.

### Maus finden

Auf zwei Bildschirmen verschwindet manchmal die Maus und man sucht hektisch herum fuchtelnd danach. Das geht auch eleganter: In der Systemsteuerung "Zeigerposition beim Drücken der STRG-Taste anzeigen" aktivieren. Danach wird bei Drücken von <kbd>Strg</kbd> und wieder Loslassen die Mausposition durch sich vergrößernde Ringe angezeigt.

[Microsoft Support-Seite](https://support.microsoft.com/de-de/windows/schnelles-wiederfinden-des-mauszeigers-dbc1d222-778c-da15-5218-cb8336074554#:~:text=Windows%2010%20erm%C3%B6glicht%20es%20Ihnen,sie%20aus%20der%20Liste%20aus.)

## Textverarbeitung & Co.

### Rechnen in LibreOfficeWriter

Man kann einfach innerhalb von LibreOfficeWriter Rechnungen ausführen, indem man
den zu berechnenden Ausdruck (etwa "1234 * 0,2") markiert und dann
<kbd>Strg + +</kbd> drückt. Das Ergebnis der Berechnung steht in
der Folge in der Zwischenablage zur Verfügung und kann mit <kbd>Strg + v</kbd> an beliebiger Stelle in den Text eingefügt werden.

*Achtung*: Damit die Berechnung funktioniert, dürfen die Zahlen seit LibreOffice
6.0 kein Tausender-Trennzeichen enthalten!

## Hardware

### Dragon Naturally Speaking ohne Headset

<img src="imgs/Philips Digital Pocket Memo.png" title="Philips Digital Pocket Memo" alt="Philips Digital Pocket Memo" style="float: right">
Wer mit Dragon Naturally Speaking arbeitet und sein Headset nicht zwischen
Arbeitsplatz und Homeoffice hin- und hertragen will, kann auch auf das
Diktiergerät zurückgreifen. Ich habe es nur mit der neuen Variante 4 (bunter
Bildschirm) getestet, was verhältnismäßig gut funktioniert.

- Diktiergerät mit einem ausreichend langem USB-Kabel mit dem Rechner verbinden
  und einschalten. Den SpeechExec-Dialog zum Überspielen schließen.
- Darauf achten, dass der Vor- und Rückspultaste in Neutral-Stellung ist.
- Dragon Naturally Speaking starten (idealerweise mit <kbd>&#8862; Win</kbd> - "Drag" -
  <kbd>Enter</kbd>).
- Der Dialog fragt nach dem zu verwendenden Mikrofon, hier das Philips Pocket
  Memo auswählen.
- Einrichtung abschließen.
- Nun kann wie üblich diktiert werden, wobei die Aufnahmetaste am Diktiergerät
  das Mikrofon ein- und ausschaltet.
- Den Schieber für Vor- und Zurückspulen *nicht* verwenden!
- Am besten funktioniert es, wenn man das Diktiergerät etwa 5 cm vom Mund
  entfernt hält und man in einer ruhigen Umgebung dikiert.

#### Bonus-Tipp

Es klappt zur Not auch nur mit dem Laptop, wenn er aufgeklappt ist und man
relativ nahe (50 bis 75 cm) davor sitzt. In diesem Fall die eingebauten
Mikrofone beim Öffnen des Dragon Naturally Speaking auswählen.

Das Diktiergerät verfügt auch über einen Modus, der automatisch aktiv wird, sobald es flach
am Tisch liegt. So nimmt es Stimmen aus dem ganzen Raum auf und kann als Mikrofon für
Zoom-Verhandlungen dienen.
