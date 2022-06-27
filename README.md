# AR_Buchungstool

![signal-2022-02-21-111424_002](https://user-images.githubusercontent.com/57839896/175962500-e8579040-64be-4093-a0a4-77ffb98b96eb.jpeg)

## About

Dieser Prototyp unterstützt die Planung eines Flohmarkts im (halb-)öffentlichen
Raum und ermöglicht es, Flohmarktstände einfach vor Ort schon im Voraus zu reservieren
und zu bezahlen. Mit dem entwickelten Prototyp soll die Frage geklärt
werden, inwiefern organisatorische Prozesse in AR abgewickelt werden können und
welche Vorteile dies haben könnte.
Der Prototyp wurde in der 3D Software Rhino entwickelt. Zur Verbindung mit der
Hololens und anderen Devices wie Tablets, wurde das Plugin Fologram verwendet.
Bei diesem Prototyp kommen QR-Codes als Tracking-Verfahren zum Einsatz. Diese
können ausgedruckt und räumlich verortet werden. Nachdem man den QR-Code
mit dem genutzten Device gescannt hat, werden die digitalen Inhalte in einem lokalen
Koordinatensystem, basierend auf Position und Ausrichtung des QR-Codes,
platziert.
Die Anwendung zeigt ein einfaches Raster aus Quadraten (1 Meter x 1 Meter). Anwender:
innen können durch Klicken auf eines der Quadrate beispielsweise einen
Tisch für ihren Marktstand hinzufügen und durch erneutes Anklicken wieder löschen.
Die so visualisierten Tische zeigen Informationen über Preis, Quadratmeterzahl
und Namen. Außerdem werden auch die schon reservierten Flächen anderer
Anwender:innen angezeigt. Zum jetzigen Entwicklungszeitpunkt war es möglich, mit
einem technisch kompatiblen Smartphone, einem kompatiblen Tablet, sowie einer
Hololens zeitgleich die selbe Anwendung zu verwenden. In weiteren Entwicklungsschritten
müsste eine Datenbank für die Implementierung eines Buchungssystems
aufgebaut werden.

## Diagram

Verwendete Grasshopper Plugins:

Pufferfish (austauschbar)
ShapeDiver (austauschbar)
Lunchbox (austauschbar)
Fologram (wesentlich)

Zur besseren Nachverfolgung werden zwei aufgedruckte QR-Codes empfohlen (siehe auch Fologram Dokumentation).

Funktioniert mit allen von Fologram unterstützten Geräten und mit mehreren Benutzern gleichzeitig.

![Flowcharts für Publikation - 2 4  AR basiertes Buchungstool mit Hilfe von Fologram und QR-Codes](https://user-images.githubusercontent.com/57839896/175962684-6f0a5c13-6568-43c5-b8e5-73ee57184ee0.jpg)
