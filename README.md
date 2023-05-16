# erreichbarkeiten

Proof of concept:
Mithilfe von Graphhopper (localhost) werden Fahrzeiten-Isochrone berechnet für jeden Hex-Mittelpunkt. Es können die Routingeigenschaften ausgewählt, konfiguriert (config-file) und ggf. auch weiter angepasst (Java) werden. In dem Beispiel handelt es sich um "Fahrrad".

Die Attraktionspunkte sind Kneipen/Bars. Je nachdem wie viele davon von den Startpunkten (Hex-Mittelpunkt) aus in den jeweiligen Zeitintervallen erreicht werden können (Scoring), werden die Hexagone bewertet/eingefärbt.



https://radverkehr.github.io/erreichbarkeiten/viz/iso_rad_kneipe_simp.html



Input:

- OSM (Kneipen, Straßen für Viz)
- Graphhopper Routing (nutzt wiederrum OSM pbf als Input)
- Uber Hex H3





Beispielplot

![image-20230516122753318](C:\Users\simon\AppData\Roaming\Typora\typora-user-images\image-20230516122753318.png)

![image-20230516122804026](C:\Users\simon\AppData\Roaming\Typora\typora-user-images\image-20230516122804026.png)
