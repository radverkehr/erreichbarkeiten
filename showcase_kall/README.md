# showcase kall

###### Reisezeiten/Isochronen:
Mithilfe von Graphhopper (localhost) werden Fahrzeiten-Isochrone berechnet für jeden Mittelpunkt eines 100x100m Bevölkerungsraster mit mehr als 0 Einwohner (hier 720 ). Es können die Routingeigenschaften ausgewählt, konfiguriert (config-file) und ggf. auch weiter angepasst (Java) werden. In dem Beispiel handelt es sich um "Fahrrad".
Für die Isochronen wurden je 6 timebuckets mit 5min gewählt, also 0-30min werden abgedeckt.

https://radverkehr.github.io/erreichbarkeiten/showcase_kall/viz/kall_map_export_30min_6buckets.html

###### Attraktionspunkte:
Die Attraktionspunkte sind bspw. Kosumeinrichtungen, Öffentlichene Einrichtungen oder PT-Haltepunkte. Je nachdem wie viele davon von den Startpunkten (Raster-Mittelpunkt) aus in den jeweiligen Zeitintervallen erreicht werden können (Scoring), werden die Raster bewertet/eingefärbt.

OSM amenity/shop: https://radverkehr.github.io/erreichbarkeiten/showcase_kall/viz/attractions_kall_amenity.html

PT Vergleich OSM, zHV und GTFS: https://radverkehr.github.io/erreichbarkeiten/showcase_kall/viz/attractions_kall_pt.html

###### Gewichtung und Scoring der Attraktionspunkte:

WIP

