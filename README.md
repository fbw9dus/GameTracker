# GameTracker
Application for hosting Pingpong Tournaments

## TODOs
### Benutzeroberfläche (HTML + CSS)
#### Elemente
- Spielerliste mit Punktzahl jedes Spielers
- Textfeld und Button um Spieler hinzuzufügen
- Button um Spiel zu starten
- Gegner-Namen
- Punkte-Anzeige für beide Gegner eines Spiels


### Logik (JavaScript)
#### Aufbau
- Meisterschaft
  - Liste der gespielten Spiele
  - Wieviele Spiele noch zu spielen
- Spiel
  - Gegner
  - Sieger
- Spieler
  - Punkte
  
- Objekt für Einstellungen
  - Anzahl der Sätze pro Spiel

## Hilfe
###### Text aus Textfeld
```html
<input type="text" id="myText">
```
```javascript
var userInput = document.getElementById("myText").value
```

###### Inhalt in HTML-Element einfügen
```html
<ul id="myList">

</ul>
```
```javascript
document.getElementById("myList").innerHTML = "<li>Bees</li><li>Hornets</li>"
```
###### Auf Klick reagieren
```html
<button>Klick mich!<button>
```
```javascript
var button = document.querySelector('button')

function tellClick(){
  alert("Ich wurde geklickt!")
}

button.addEventListener('click', tellClick)
```
