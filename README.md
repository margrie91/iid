# iid W2015 #
interface and interaction design course 

### Important Information ###
This website is optimized and tested for Chrome Browser.
Known issues with Mozilla Firefox: DatePicker / Dateformat dd.mm.YYYY

### Repository link: ###
https://github.com/margrie91/iid.git

####Solved Issues: ####
* (Prio 0) Fehlende Seiten
* (Prio 1) Zurück Button in save-find and save-loss
* (Prio 2) Home Link via Logo
* (Prio 3) Konsistente Verwendung der Farben
* (Prio 4) Datenbasis inkonsistent -> erweitern
* (Prio 5) Datenübergabe zwischen den Masken:
  - list-view-find: Hab's       -> contact-find: Felder mit Daten des Eintrags
  - list-view-find: Nicht dabei -> save-find: Textboxen mit Daten der Suche
  - analog list-view-search	
  
#### Open Issues: ####
* (Prio 6) Warnung beim Verlassen einer save oder contact seite via header link bevor die form übertragen wurde  
* (Prio 7) Firefox: DatePicker / Dateformat dd.mm.YYYY

uses bootstrap v3.3.6

<pre>
|   contact-find.html
|   contact-loss.html
|   delete-find.html
|   delete-loss.html
|   dummy-find.html                               
|   dummy-loss.html
|   dummy-save-find.html
|   dummy-save-loss.html
|   email-find.html
|   email-loss.html
|   entry-saved-find.html
|   entry-saved-loss.html
|   home.html                                       Start here
|   list-view-find.html
|   list-view-lost.html
|   mail-client-dummy-find.html
|   mail-client-dummy-loss.html
|   mail-find-edit-delete.html
|   mail-loss-edit-delete.html
|   message-sent-find.html
|   message-sent-loss.html
|   rating-find.html
|   rating-loss.html
|   README.md                                       This file
|   save-find-edit.html
|   save-find.html
|   save-loss-edit.html
|   save-loss.html
|   template.html                                   Template for your html files
|
+---bootstrap                                       Bootstrap files, do not edit
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
+---css                                             Edit styles here
|       blocks.css
|       custom.css
|       font-awesome.min.css
|       plugins.css
|       style-library-1.css
|
+---doc                                                                
|       storyboard_0.1.jpg                          as created on 09.12.2015
|       Entwurf.jpg
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
|   |   new-filled-red.png
|   |   new-messages-red.png
|   |
|   \---brand
|           fundbox-logo-nostrap.png
|           fundbox-logo.jpg
|
+---js
|       bskit-scripts.js
|       contact-form.php
|       html5shiv.js
|       jquery-1.11.1.min.js
|       plugins.js
|       respond.min.js
