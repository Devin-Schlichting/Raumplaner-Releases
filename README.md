# Raumplaner – Downloads

Windows-Programm, mit dem du Räume mit exakten Maßen anlegst und Möbel virtuell umstellst, bevor du real umräumst: 2D-Plan, 3D-Ansicht, Laufmodus, Layouts.

Hier liegen nur die Installer. Der Raumplaner schaut hier einmal täglich nach neuen Versionen und installiert sie auf Knopfdruck.

## Installieren

1. Unter [Releases](https://github.com/Devin-Schlichting/Raumplaner-Releases/releases/latest) `Raumplaner-Setup.exe` herunterladen und starten.
2. Keine Administratorrechte nötig; installiert wird für den aktuellen Benutzer.
3. Der Installer ist nicht signiert. Windows zeigt deshalb „Der Computer wurde durch Windows geschützt“ → *Weitere Informationen* → *Trotzdem ausführen*. Bei eingeschaltetem *Smart App Control* blockiert Windows unsignierte Programme ganz.

Pläne, Einstellungen und *Meine Möbel* liegen in `Dokumente\Raumplaner` und bleiben bei Updates und beim Deinstallieren erhalten.

## Prüfsumme

Jedes Release nennt die SHA-256-Prüfsumme des Installers. Selbst prüfen (PowerShell):

```powershell
Get-FileHash .\Raumplaner-Setup.exe -Algorithm SHA256
```
