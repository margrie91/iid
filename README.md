# iid
interface and interaction design course

Open Issues:
* (Prio 0) Fehlende Masken
* (Prio 1) Zurück Button in save-find and save-loss
* (Prio 2) Home Link via logo
* (Prio 4) Datenübergabe zwischen den Masken:
  - list-view-find: Hab's       -> contact-find: Felder mit Daten des Eintrags
  - list-view-find:Nicht dabei  -> save-find: Textboxen mit Daten der Suche
  - analog list-view-search
* (Prio 5) Warnung beim Verlassen einer save oder contact seite via header link bevor die form übertragen wurde  
* (Prio 6) Datenbasis Liste / Combo inkonsistent -> erweitern

uses bootstrap v3.3.6

<pre>
|   contact-find.html
|   contact-loss.html
|   home.html
|   list-view-find.html
|   list-view-lost.html
|   pinegrow.json
|   README.md                                           this file
|   save-find.html
|   save-loss.html
|   template.html                                       template for your html files                                      
|
+---bootstrap                                           do not touch bootstrap files
|   +---css
|   |       bootstrap-theme.css
|   |       bootstrap-theme.css.map
|   |       bootstrap-theme.min.css
|   |       bootstrap-theme.min.css.map
|   |       bootstrap.css
|   |       bootstrap.css.map
|   |       bootstrap.min.css
|   |       bootstrap.min.css.map
|   |
|   +---fonts
|   |       glyphicons-halflings-regular.eot
|   |       glyphicons-halflings-regular.svg
|   |       glyphicons-halflings-regular.ttf
|   |       glyphicons-halflings-regular.woff
|   |       glyphicons-halflings-regular.woff2
|   |
|   \---js
|           bootstrap.js
|           bootstrap.min.js
|           npm.js
|
+---css                                               manipulate styles here (do not touch bootstrap styles)
|       blocks.css
|       custom.css
|       font-awesome.min.css
|       plugins.css
|       style-library-1.css
|
+---doc                                               documentation
|       storyboard_0.1.jpg                            as created on 09.12.2015
|
+---fonts
|       fontawesome-webfont.eot
|       fontawesome-webfont.svg
|       fontawesome-webfont.ttf
|       fontawesome-webfont.woff
|       fontawesome-webfont.woff2
|       FontAwesome.otf
|
+---images
|   |   new-messages-red.png
|   |
|   \---brand
|           fundbox-logo-nostrap.png
|           fundbox-logo.jpg
|
\---js
        bootstrap.js
        bootstrap.min.js
        bskit-scripts.js
        contact-form.php
        html5shiv.js
        jquery-1.11.1.min.js
        plugins.js
        respond.min.js