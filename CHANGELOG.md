Website Manager - Changelog
===========================

### Version 2.0.0 - 02. Februar 2014

* Mechanismus hinzugefügt um Custom Code vor und nach Website-Erstellung/Zerstörung einzuschleusen (siehe Custom-Ordner und Einstellungen-Seite). Nützlich wenn man zusätzliche VIEWS etc. für AddOns anlegen will.
* Bei eingeschaltetem One Page Mode von SEO42 wird nun der Anzeigen-Link korrekt gesetzt
* Plugin-Einbindung nicht mehr hartcodiert. Abschnitt "Entwicklung von Plugins für den Website Manager" zur Readme hinzugefügt.
* Uninstall wird nur noch erlaubt wenn zuvor von Hand alle angelegten Websites wieder gelöscht wurden
* Uninstall Messages verbessert
* Website Auswahl wird nun zurückgesetzt auf die Master Website wenn ausgeloggt
* Wenn der Benutzer keine Rechte hat für min. eine Website wird nun eine entsprechende Fehlermeldung angezeigt
* Hilfe verbessert, Debug und Log Sections hinzugefügt
* Readme erweitert um Abschnitte `AddOns mit gleichem Datenbestand` und `AddOns mit unterschiedlichem Datenbestand`
* Setup etwas verbessert
* Finetuning

### Version 1.3.0 - 24. Oktober 2013

* Hinweise in Readme.md aktualisiert
* Auf der REDAXO System-Seite werden die Felder deaktiviert die über den Website Manager befüllt werden müssen
* Automatische Breitenanpassung des Website Selectors
* Bei Deinstallation wird auf die Codezeile in der `master.inc.php` geprüft
* Bei Installation wird auf das Frontend Link Plugin geprüft
* Verbesserte Anleitung für Setup Schritt 2

### Version 1.2.2 - 01. August 2013

* Bei Installation wird auf das Colorizer/Customizer Plugin geprüft
* Fixed #33: Bug in der "Cache global löschen" Logik führte zu einem Durcheinander in den verschiedenen Generated-Ordnern
* Drag'n Drop Sortierung der Websites auch für Nicht-Admins aktiviert

### Version 1.2.1 - 21. Mai 2013

* Fixed: Generate All funktionierte nicht mehr sauber
* Neue Option: `ignore_permissions`. Siehe Hinweise in der README.md
* Fixed: Wenn Website Manager installiert und aktiviert gab es eine Endlosschleife wenn Setup erneut durchlaufen wurde
* Theme Plugin Update
* Wenn `identical_templates` auf `false` wird ein Textfeld bei Website anlegen/bearbeiten angezeigt, anstelle eines Select-Feldes
* Position des Init-Includes in der `master.inc.php` geändert. Siehe Setup im AddOn
* Wenn Domain nicht existiert wird jetzt eine 404 Page erzeugt
* Init-Methode wegen Image Manager gesäubert. Sattdessen darf man jetzt aktuell den Core patchen ;) siehe README.md
* Fixed #30: Website Select funktioniert jetzt auch wenn man sich in der Struktur und Content Ansicht befindet (thx@serbis)
* Fixed: REXSEO/SEO42 Pathlist war leer (404 Erros) wenn neue Website hinzugefügt wurde
* PHP-Methoden `websiteSwitch()` und `masterWebsiteSwitch()` zu Klasse `rex_website_manager` hinzugefügt um Websites on the fly zu switchen
* PHP-Methoden `getMasterWebsite()` und `getMasterWebsiteId()` zu Klasse `rex_website_manager` hinzugefügt

### Version 1.1.0

* Theme-Plugin erweitert: Dynamische CSS Generierung mittels PHP und SCSS
* Kleinere Cosmetics ud Fixes

### Version 1.0.0



