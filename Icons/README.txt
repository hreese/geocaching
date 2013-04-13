= Intuitivere Icons für Garmin-Geräte mittels GSAK =

Updates gibt's im grünen Forum in diesem Thread: http://www.geoclub.de/ftopic13617.html

== Installation ==

1. Zipdatei irgendwo auspacken

  Zum Beispiel nach c:\tmp.

2. Die Icons in Mapsource integrieren

  Kopiere alle Dateien aus dem Verzeichnis c:\tmp\Mapsource nach My Documents\My Garmin\Custom Waypoint Symbols.
  Bei deutschem Windows heißt das anders, sollte aber intuitiv zu finden sein...

3. Die Icons auf das Gerät bringen

  Besorge dir von Garmin die Software xImage. Liegt irgendwo bei garmin.com im Support/Download-Bereich rum.
  Damit kann man die Icons aus dem Verzeichnis c:\tmp\Gerät auf dein Garmin laden. Mache vorher eine Sicherungskopie
  der jetzigen Icons (ebenfalls mit xImage).

4. GSAK anpassen

  Das Macro c:\tmp\GSAK\GarminIcons.txt irgendwohin kompieren, wo man es später in GSAK einbinden kann. Meins liegt
  beispielsweise unter c:\Program Files\GSAK\Macros\GarminIcons.txt. In GSAK setzt du jetzt im Dialog GPS/Send Waypoints
  einen Haken bei "Use macro for symbol generation" und gibst darunter den Ort an, wo das Macro liegt.

  Die Datei c:\tmp\GarminOther.txt kommt in das Verzeichnis, in dem du GSAK installiert hast. Sichere vorher eine
  evtl. vorhandene Version.

5. optional: POI-Icons
  
  Im Verzeichnis c:\tmp\POIs liegen ein paar Icons, die ich für bestimmte POI-Datenbanken nutze. Zum Kopieren mit
  POILoader muss das Icon genauso heissen wie die entsprechende POI-Datei.

Bei Fragen/Anregungen/Ideen einfach eine PM an sprawl im grünen Forum schicken.