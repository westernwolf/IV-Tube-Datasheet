## Digitale Segmentanzeige mit Segment-Multiplexing
## Vakuum-Fluoreszenzanzeige
# IV-18

Die digitale mehrzeichige Vakuum-Fluoreszenzanzeige dient zur Anzeige von Informationen in Form von Zahlen von 0 bis 9 und einem Dezimalpunkt.
Jede der 8 Segmente und dem Zusatzsegment kann einzel oder als Gruppe verwendet werden.
Der Körper ist zylindrisch und besteht aus Glas.
Die Leitungen sind flexibel.
Das Gewicht beträgt weniger als 30 Gramm.

--> Editor-Note: Vermutlich verwendest du einen Typ 2. So weit ich erkennen kann, erkennt man den Typ 2 daran, dass er als Sonderzeichen nur - & . besitzt und drei Leitungen  (die vordesten 3 Leitungen) nicht verbunden sind. (insert Picture here !!!!

### Betriebsbedingungen

Vibrationsbelastungen:
| | |
| --- | --- |
| Frequenzbereich [Hz] | 1-60 |
| Beschleunigung [m/s^2^] ([g]), nicht mehr als | 19.2 (2) |

Schock-Mehrfachbelastung:
| | |
| --- | --- |
| Beschleunigung [m/s^2^] ([g]), nicht mehr als | 147 (15) |
| Stossdauer [ms] | 15 |

| | |
| --- | --- |
| Umgebungstemperatur [°C] | -45 ... +70 |
| relative Luftfeuchtigkeit bei T = +25°C [%], nicht mehr als | 98 |

### Pinbelegung (Typ 1)
| Pin | Funktion/Name der Elektrode |
| --- | --- |
|  1 | Kathode, die leitende Schicht der inneren Oberfläche des Zylinders |
|  2 | DP<sub>1</sub>...DP<sub>8</sub> - Anoden-Segment, 1. bis 8. Segment |
|  3 | D<sub>1</sub>...D<sub>8</sub> - Anoden-Segment, 1. bis 8. Segment |
|  4 | C<sub>1</sub>...C<sub>8</sub> - Anoden-Segment, 1. bis 8. Segment |
|  5 | E<sub>1</sub>...E<sub>8</sub> - Anoden-Segment, 1. bis 8. Segment |
|  6 | E<sub>9</sub> - Anoden-Segment, 9. Segment |
|  7 | G<sub>9</sub> - Anoden-Segment, 9. Segment |
|  8 | A<sub>9</sub> - Anoden-Segment, 9. Segment |
|  9 | G<sub>1</sub>...G<sub>8</sub> - Anoden-Segment, 1. bis 8. Segment |
| 10 | B<sub>1</sub>...B<sub>8</sub> - Anoden-Segment, 1. bis 8. Segment |
| 11 | F<sub>1</sub>...F<sub>8</sub> - Anoden-Segment, 1. bis 8. Segment |
| 12 | A<sub>1</sub>...A<sub>8</sub> - Anoden-Segment, 1. bis 8. Segment |
| 13 | Kathode |
| 14 | Gitter des 9. Segment |
| 15 | Gitter des 1. Segment |
| 16 | Gitter des 3. Segment |
| 17 | Gitter des 5. Segment |
| 18 | Gitter des 8. Segment |
| 29 | Gitter des 7. Segment |
| 20 | Gitter des 6. Segment |
| 21 | Gitter des 4. Segment |
| 22 | Gitter des 2. Segment |

### Pinbelegung (Typ 2)
| Pin | Funktion/Name der Elektrode |
| --- | --- |
|  1 | Kathode, die leitende Schicht der inneren Oberfläche des Zylinders |
|  2 | DP<sub>1</sub>...DP<sub>9</sub> - Anoden-Segment, 1. bis 9. Segment |
|  3 | D<sub>1</sub>...D<sub>8</sub> - Anoden-Segment, 1. bis 8. Segment |
|  4 | C<sub>1</sub>...C<sub>8</sub> - Anoden-Segment, 1. bis 8. Segment |
|  5 | E<sub>1</sub>...E<sub>8</sub> - Anoden-Segment, 1. bis 8. Segment |
|  6 | Nicht Verbunden |
|  7 | Nicht Verbunden |
|  8 | Nicht Verbunden |
|  9 | G<sub>1</sub>...G<sub>9</sub> - Anoden-Segment, 1. bis 9. Segment |
| 10 | B<sub>1</sub>...B<sub>8</sub> - Anoden-Segment, 1. bis 8. Segment |
| 11 | F<sub>1</sub>...F<sub>8</sub> - Anoden-Segment, 1. bis 8. Segment |
| 12 | A<sub>1</sub>...A<sub>8</sub> - Anoden-Segment, 1. bis 8. Segment |
| 13 | Kathode |
| 14 | Gitter des 9. Segment |
| 15 | Gitter des 1. Segment |
| 16 | Gitter des 3. Segment |
| 17 | Gitter des 5. Segment |
| 18 | Gitter des 8. Segment |
| 29 | Gitter des 7. Segment |
| 20 | Gitter des 6. Segment |
| 21 | Gitter des 4. Segment |
| 22 | Gitter des 2. Segment |

### Anschluss der Segmente zur Darstellung von Zahlen und Zeichen (Typ 1)
| Zahlen (& Zeichen)  | Anzusteuernde Pins |
| --- | --- |
|  0  | 12, 11 3, 5, 4, 10 |
|  1  | 10, 4 |
|  2  | 12, 10, 9, 5, 3 |
|  3  | 12, 10, 9, 4, 3 |
|  4  | 11, 9, 10, 4 |
|  5  | 12, 11, 9, 4, 3 |
|  6  | 12, 11, 5, 3, 4, 9 |
|  7  | 12, 10, 4 |
|  8  | 12, 11, 9, 4, 3, 5, 10 |
|  9  | 9, 11, 12, 10, 4, 3 |
| Dezimalpunkte | 2|
| vertikaler Balken | 6 |
| Minuszeichen | 7 |
| Servicepunkt (grosser Punkt) | 8 |

### Anschluss der Segmente zur Darstellung von Zahlen und Zeichen (Typ 2)
| Zahlen (& Zeichen)  | Anzusteuernde Pins |
| --- | --- |
|  0  | 12, 11 3, 5, 4, 10 |
|  1  | 10, 4 |
|  2  | 12, 10, 9, 5, 3 |
|  3  | 12, 10, 9, 4, 3 |
|  4  | 11, 9, 10, 4 |
|  5  | 12, 11, 9, 4, 3 |
|  6  | 12, 11, 5, 3, 4, 9 |
|  7  | 12, 10, 4 |
|  8  | 12, 11, 9, 4, 3, 5, 10 |
|  9  | 9, 11, 12, 10, 4, 3 |
| Dezimalpunkte & Servicepunkt (grosser Punkt) | 2|
| Minuszeichen | 9 |

### Grundinformationen
| | | 
| --- | --- | 
| Leuchtfarbe| grün|
| Anzeigehelligkeit [cd/m^2^], min: |   |
| -> eine digitale Ziffer | 900 |
| ???-> offizieller Rang | 200 | 
| Heizspannung [V] | 5.0 |
| Glimmstrom [mA] | 85+/-10 |
| Anodensegmentspannung [V] | 50 |
| Gesamter Anodensegmentstrom [mA]: | |
| -> neun Ziffern für IV-18 (Typ 1) | 45 |  
| -> acht Ziffern für IV-18 (Typ 2) | 40 |
| Gitterspannung gepulst [V] | 50 |    
| Gesamter Gitterstrom für 8 und 9 Segmente [mA] | 10^+10^ ????  |
| Auslastungsgrad ???? | 10 +/- 1 |
| Mindestbetriebsdauer [h] | 10000 |
| Abnahme der Leucchtidichte eines Segments während der Mindestbetreibsdauer [cd/m^2^], min. | 100 |
| Mindesthaltbarkeit [Jahre] | 4 |

###  Maximal zulässiger elektrischer Betrieb
| | | 
| --- | --- | 
| Spannang über den Glimmdraht [V] | 4.3 ... 5.5 | 
| Höchste Spannung bei U_{Anodensegment}=U_[Gitter] = 50 V, [V] | 70 | 
| Höchste gepulste Gitterspannung [V]| 70 | 
| Höchster Anoden-Segmentstrom [mV] | 1.3 | 
| Geringste Einschaltdauer | U_{Gitter}/25 | 

### Empfehlung für Verwendung
Bei einer positiven Segmentspannung von 2.5 bis 3.0 Volt wird ein sichtbares Glühen des Segments beobachtet, wenn eine Spannung an das Gitter angelegt wird. 
Die Drähte sollten wenn möglich nur einmal, bei einem Abstand von 0.5 bis 1.0 mm vom Glas entfernt, gebogen werden.
Vom Betrieb der Anzeige bei zwei oder mehr Spannungen/Stömen am Maximum wird abgeraten ( ausser bei den Grenzspannungen der Anode und des Gitters).

![grösse eines Segments](Sign.png)
!!!! add same thing for special char
