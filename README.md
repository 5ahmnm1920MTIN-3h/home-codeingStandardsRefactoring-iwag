# Ausarbeitung Refactoring

## Definition Refactoring
Als "Refactoring" bezeichnet man den Prozess, den Code effizienter zu gestalten, wobei er auch leserlicher und somit leichter verwendbar wird. 

## Vor- und Nachteile von Refactoring

### Vorteile
 - schneller verarbeitbar für Maschine
 - leichter zum Einfinden für andere Contributors

### Nachteile
- mehr Arbeitsaufwand
- möglicherweise hierdurch Einbringung von Fehlern

## Refactoring-Schritte
 - Testcase definieren  
 - funktioniert Programm? 
 - Beseitigung etwaiger Codesmells  
 - Testcase: testen, ob alles funktioniert wie zuvor
 - ja -> committen

## Prinzipien von gutem Code
 - DRY -Don’t Repeat Yourself
 - KISS -Keep it Simple
 - StupidYAGNI -You Ain’t Gonna Need Principle of least Astonishment 
 - SoC-Separation of Concerns

## Code Smells
Als sogenannte "Code Smells" bezeichnet man allgemein Code, der nicht sinnvoll strukturiert ist. Darunter fallen etwa "Magical Strings" und "Magical Values" (plötzlich auftauchende, hardgecodete Werte im Code) oder überflüssige (z.B. leere) Methoden.

