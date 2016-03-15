CSS
===

**Elemente auswählen**  
- `<div class="content">` - Jedes Element, `div`, `h1`, `a`, `p`, usw. kann eine Klasse haben. Hier hat ein div Element eine Klasse "content". Elemente, die die selbe Klasse haben, nutzen den gleichen CSS-Style, der hinter der Klasse liegt.  
Schriftfarbe auf blau und Schriftgröße auf 20 Pixel für den Inhalt aller "content" setzen:

        .content {
          color: blue;
          font-size: 20px;
        }

- `<div id="einmal">` - "id" = "Identifier" = "Identifizierer" sind nur für ein Element da. CSS zum setzen des Hintergrundes: `#einmal { background: black; }`  
- `<h1>  </h1>` - Alle Elemente eines Types können einen eigenen Stil bekommen.  
Schriftart aller Hauptüberschriften auf "Roboto" setzen, wenn es "Roboto" nicht gibt, auf "Arial": `h1 { font-family: Roboto,Arial; }`
- Mouseover-effekte wie, wenn die Maus drüber ist die SFarbe ändern `a:hover { color: darkblue; }`  

**Eigenschaften**
`font-size: 15px;` - Schriftgröße auf 15 Pixel setzen  
`color: #666A73;` - Schriftfarbe auf `#666A73` setzen  
`letter-spacing: .5px;` - Abstand der Buchstaben auf 0,5 Pixel setzen  
`width: 66.66667%;` - Breite auf 2/3 setzen  
`height: 2em;` - Höhe doppelte Schriftgröße setzen  
`padding: 10px;` - Innen größer machen (mit Hintergrund) 
`margin: 10px;` - Abstand gräßer machen (ohne Hintergrund)  
`margin-right`, `margin-left`, `margin-top`, `margin-bottom` - spezielle Ränder, analog bei padding  
**Längenangaben**  
Es gibt z.B. `px`(Pixel), `%`(Anteil am Maximum), `em`(*Schriftgröße), [tinyurl.com/ctyzh9z](http://tinyurl.com/ctyzh9z)  
**Von anderen Webseiten abgucken**  
Rechtsklick auf ein Element → Inspect Element → Inspector → Rules