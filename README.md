# Bachelor-Arbeit
Diese Order besteht aus zwei Dateien:
- region_geojson.ipynb
- graphen.ipynb

Um diese Dateien auszuführen, sollten die in 'requirements.txt' aufgelisteten Bibliotheken benutzt werden (Alternativ: mit 'environment.yml' -> https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/ ).


## region_geojson
Diese File macht neue Reporting Units für Regionen, Kantone sowie weitere funktionalen Einheiten. Es besteht aus vier verschiedenen Funktionen:
- new_region_geojson: Reporting Unit der Regionen
- new_kanton_geojson: Reporting Unit der Kantone
- new_rep_units: weitere Reporting Units für funktionalen Einheiten nach Variante 1
- test_rep_unit_2: weitere Reporting Units für funktionalen Einheiten nach Variante 2


## graphen
Diese Datei erstellt Graphen über die zeitliche Entwicklung der Zersiedelung und seiner Indikatoren aus den erzeugten Daten von QGIS mittels des Plug-ins "Urban Metric Tool". Die Inputdateien sind die Ergebnisse des Plug-ins in QGIS (data > WUP_richtig).



