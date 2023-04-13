# Gira-X1-Logic
Gira-X1-Logic ist eine Sammlung von Logikbausteinen für den Gira X1 Server. Diese Bausteine sind in C#geschrieben und ermöglichen es Benutzern, benutzerdefinierte Automatisierungsabläufe für ihre Gira X1 Smart Home-Installation zu erstellen. 


# LogivValueTimer: (Steidle: Schwellenwert-Überwachungsbaustein mit Zeitintervall-Logik)
Dieser Baustein überwacht einen Wert und vergleicht ihn mit Schwellenwerten. Wenn der Wert den Schwellwert überschreitet und ein bestimmtes Zeitintervall verstrichen ist, wird der Ausgang ValueExceeded auf true gesetzt. Webb der Wert dann wieder ein Schwellenwert unterschreitet und ein weiteres Zeitintervall verstrichen ist, wird der Ausgang ValueExceededAndUndercutAgain auf true gesetzt. Wenn der Wert jedoch vorzeitig den Schwellenwert unterschreitet, wird der Ausgang ValueExceededAndUndercutAgainToEarly auf true gesetzt. Der Eingang Reset setzt alle Ausgänge zurück, während die anderen Eingänge die Bedingungen für die Aktivierung der Ausgänge festlegen. Der Zustand des Programms wird persistent gespeichert, um den Zustand des Programms wieder herstellen zu können.
