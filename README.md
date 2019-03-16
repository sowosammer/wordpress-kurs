# wordpress-kurs
Notizen zum Wordpresskurs

https://derphilipp.github.io/schulung_git/#1
https://derphilipp.github.io/schulung_webseiten/#1

## Aufbau - Server 
Applicationserver: Lädt Programm führt 
Webserver: Schnittstelle nach außen, Sicherheitsrelevante komponente, Cached, .... z.B. Apache, nginx, lighthttp
Reverse-Proxy: z.B. nginx, 

## Statische Seiten - z.B. hugo

Seitengestaltung mit Hugo

Links
Themes:
https://themes.gohugo.io/

Ansonsten suche hugo theme

Es wird nicht immer vollständig 1:1 umgesetzt. Im Zweifelsfall muss man auf der Homepage nachlesen ob voraussetzungen bzw. bestimmte Dateien vorhanden sein müssen.
**Grundsätzlich** müssen der theme name in config.toml und im theme der Name in der theme.toml und das themeverzeichnis übereinstimmen.

Beispiel Ananke:
https://github.com/budparr/gohugo-theme-ananke/archive/2.40.zip

// wenn hugo nicht im programm suchpfad ist immer den Pfad zur hugo exe angeben

hugo new beispiel // legt beispielanwendung an
hugo new site xy // erstellt neue seite in ordner content
hugo new content zx 
hugo serve -d // startet server, baut die seite im draftmodus , -> Seite ist unter Localhost.. verfügbar 

VS Code extensions 
* Markdown all in one



## Wordpress

lokal unter Windows: Xampp 
evtl. besser Docker.

### Xampp

Installation von Xampp siehe 

**Themes** bringen layout Änderungen.
**Plugins** bringen Frontend oder auch Bearbeitungsmöglichkeiten/eigenschaften.



