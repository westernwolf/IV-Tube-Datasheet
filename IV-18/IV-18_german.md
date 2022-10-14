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
|  2 | u~1~...u~8~ - Anoden-Segment, 1. bis 8. Segment |
|  3 | x~1~...x~8~ - Anoden-Segment, 1. bis 8. Segment |
|  4 | e~1~...e~8~ - Anoden-Segment, 1. bis 8. Segment |
|  5 | r~1~...r~8~ - Anoden-Segment, 1. bis 8. Segment |
|  6 | r~9~ - Anoden-Segment, 9. Segment |
|  7 | s~9~ - Anoden-Segment, 9. Segment |
|  8 | a~9~ - Anoden-Segment, 9. Segment |
|  9 | s~1~...s~8~ - Anoden-Segment, 1. bis 8. Segment |
| 10 | b~1~...b~8~ - Anoden-Segment, 1. bis 8. Segment |
| 11 | o~1~...o~8~ - Anoden-Segment, 1. bis 8. Segment |
| 12 | a~1~...a~8~ - Anoden-Segment, 1. bis 8. Segment |
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
|  2 | u~1~...u~9~ - Anoden-Segment, 1. bis 9. Segment |
|  3 | x~1~...x~8~ - Anoden-Segment, 1. bis 8. Segment |
|  4 | e~1~...e~8~ - Anoden-Segment, 1. bis 8. Segment |
|  5 | r~1~...r~8~ - Anoden-Segment, 1. bis 8. Segment |
|  6 | Nicht Verbunden |
|  7 | Nicht Verbunden |
|  8 | Nicht Verbunden |
|  9 | s~1~...s~9~ - Anoden-Segment, 1. bis 9. Segment |
| 10 | b~1~...b~8~ - Anoden-Segment, 1. bis 8. Segment |
| 11 | o~1~...o~8~ - Anoden-Segment, 1. bis 8. Segment |
| 12 | a~1~...a~8~ - Anoden-Segment, 1. bis 8. Segment |
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

