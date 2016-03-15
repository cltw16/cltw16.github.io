HTML
====

Einrückungen sind wichtig für Menschen! Beispielwebseite:

    <html>
      <head>
        <meta charset="UTF-8" />
        <title>Chemnizter Linuxtage 2016</title>
        <link href="index.css" rel="stylesheet" />
      </head>
      <body>
        <h1>Chemnitzer Linuxtage 2016</h1>
      </body>
    </html>

`<html>  </html>` - darin steht alles zur Webseite  
`<head>  </head>` - darin stehen Infomrationen über die Webseite  
`<body>  </body>` - darin stehen Infomrationen auf der Webseite  
**In head:**  
`<meta charset="utf-8" />` - UTF-8 als Kodierung der Datei verwenden (alle Unicode Zeichen, beste Wahl)  
`<link href="style.css" rel="stylesheet" type="text/css" />` - Cascading Style Sheet in der Datei `style.css` einbinden  
`<link rel="icon" type="image/png" href="favicon.png">` - Webseitenlogo  
`<script type="text/javascript" src="trallala.js" crossorigin="anonymous"></script>` - die Datei `trallala.js` als JavaScript einbinden  
`<title>  </title>` - darin steht der Titel der Webseite  
**In body:**  
`<h1>  </h1>` - darin stehen Überschriften (`h1`, `h2`, `h3`, `h4`)
`<!--  -->` - darin stehen Kommentare für Programmierer, die nicht angezeigt werden  
`<div>  </div>` - darin steht ein Abschnitt. Divs eignen sich gut zum Stylen, siehe [CSS](css.md).  
`<p>  </p>` - darin steht ein Absatz  
`<br />` - ein Zeilenumbruch  
`Bin<wbr />de<wbr />strich` - Bindestriche, wenn das Wort "Bindestrich" umgebrochen werden muss wegen Platz  
`<a href="https://github.com/cltw16/cltw16.github.io">Github Repository</a>` - ein Link auf eine entfernte Webseite  
`<a href="/index.html">Home</a>` - ein Link auf die unterste `index.html`-Datei (man beachte den `/` am Anfang)  
`<a href="test.html">Test</a>` - ein Link auf eine `test.html`-Datei im selben Ordner (kein `/`).  
`<img src="test.png" />` - das Bild `test.png`, hier auch im selben Ordner  

Es gibt viele Unicodezeichen: [tinyurl.com/cyztmr](http://tinyurl.com/cyztmr)
