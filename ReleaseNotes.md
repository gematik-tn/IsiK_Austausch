Im Rahmen der ISiK-Veröffentlichungen wird das [Semantic Versioning](https://semver.org/lang/de/) verwendet.

Die erste Ziffer X bezeichnet ein Major-Release und regelt die Gültigkeit von Releases. Die dritte Ziffer Y (Release x.0.y) bezeichnet eine technische Korrektur und versioniert kleinere Änderungen (Packages) während eines Jahres, z. B. 1.0.1.

----
Version: 1.0.0

Datum: 29.06.2021

Übergreifende Festlegungen
Korrektur von verpflichtenden Suchparametern im CapabilityStatement mit Hinblick auf Must-Support-Flags in den Datenobjekt-Profilen
Anpassung der ISiK-Profile an die Version v1.0.0-rc4 der Deutschen Basisprofile
Version: 1.0.0 CC1

----
Datum: 17.05.2021

##### Übergreifende Festlegungen
- HTTPS muss in Kombination mit TLS unterstützt werden
- Die eingesetzte Software eines Drittherstellers wird nur im Rahmen des Bestätigungsverfahrens zu einem Bestandteil des Primärsystems
- Der Suchparameter "encounter" MUSS unterstützt werden
- Fix vom CapabilityStatement
- Fix URL-Referenzen
- Textuelle Korrekturen

##### Diagnose
- Must Support für Procedure.encounter
- Kein Must Support mehr für Condition.onset

##### Kontakt
- Hinweise zu der begrifflichen Abgrenzung von Fall / Kontakt hinzugefügt
- Basis-Statuswerte "in-progress", "finished" und "cancelled" werden nun gefordert
- Der Suchparameter "encounter" MUSS unterstützt werden

##### Patient
- Kardinalität 0..* für Slices von Patient.address 
- Update der Beispieldaten

##### Procedure
- Must Support für Procedure.encounter
----
