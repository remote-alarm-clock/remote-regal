# remote-regal
In diesem Repo finden sich weitere Informationen zu unserem IKEA-Lack-Regal Mod.

Wir haben unter das Furnier der Frontseite eine Reihe LED-Matrizen eingesetzt, um das Regal als verstecktes Display zu nutzen.

---
# Aufbau

## Leuchttest durch unterschiedliche Furnierdicken

<img src="images/leuchtstaerke.png" width="400">


## kapazitive Sensoren und LED-Matrix auf dem Furnier

<img src="images/kapazitiv_und_LEDs.png" width="400">


## Wemos und USB-C Port auf der Rückseite des Regals

<img src="images/wemos_und_usbc.png" width="400">


# Informationen zur Konfiguration des USB-C Ports

Die VBUS-Versorgungsleitung eines USB-C Kabels ist standardmäßig spannungsfrei. Das ist grundsätzlich anders als bei USB-A oder USB-B Verbindungen. 
Damit USB-C Netzteile eine Spannung ausgeben, muss diesem über einen sogenannten CC (Configuration Channel) mittgeteilt werden, das ein Gerät angeschlossen ist. Um eine Spannung von 5V zu erhalten, reichen zwei 5.1kOhm Widerstände zwischen CC1/CC2 und GND.
Diese sind praktischerweise auf USB-C Breakout Boards direkt verbaut.

## Abdeckung des Ports

Den USB-C Port haben wir mit einer kleinen 3D-gedruckten Abdeckung in Regalfarbe versehen. So ist die Buchse ordentlich im Regal versteckt.