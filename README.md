Survey-Observations-Generator
=============================

Survey Observations Generator written on pure JavaScript

Input data consists of points in the following format:

pointNumber X Y

Every point record shoud be placed on a new line.

The output data have the following structure:

Stn stationNumber1 Vi 0.000
 Nt observationPointNumber1 R horizontalAngle1 S distance1 Vs 0.000
 Nt observationPointNumber2 R horizontalAngle2 S distance2 Vs 0.000
 Nt observationPointNumberN R horizontalAngleN S distanceN Vs 0.000
Stn stationNumber2 Vi 0.000
 Nt observationPointNumber1 R horizontalAngle1 S distance1 Vs 0.000
 Nt observationPointNumber2 R horizontalAngle2 S distance2 Vs 0.000
 Nt observationPointNumberN R horizontalAngleN S distanceN Vs 0.000
...
Stn stationNumberN Vi 0.000
 Nt observationPointNumber1 R horizontalAngle1 S distance1 Vs 0.000
 Nt observationPointNumber2 R horizontalAngle2 S distance2 Vs 0.000
 Nt observationPointNumberN R horizontalAngleN S distanceN Vs 0.000
 
Генератор на геодезически измервания
=============================

Генератор на геодезически измервания, написан на чист JavaScript

Входните данни имат следния формат:

номерТочка X Y

Данните за всяка точка трябва да бъдат на нов ред.

Изходните данни са във формат DPI (Tplan).
