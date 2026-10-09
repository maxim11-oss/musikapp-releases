# Musikapp

Desktop-Musikplayer für den eigenen Jellyfin-Server (Windows).

## Installieren

1. Unter [Releases](https://github.com/maxim11-oss/musikapp-releases/releases/latest) die Datei `Musikapp-Setup-….exe` herunterladen und ausführen.
2. Windows warnt beim ersten Start vor einem unbekannten Herausgeber, weil das Programm nicht signiert ist: „Weitere Informationen“ → „Trotzdem ausführen“.
3. Beim ersten Start mit dem eigenen Jellyfin-Konto verbinden. Den Server im Heimnetz findet die App selbst.

## Updates

Die App sucht beim Start und alle paar Stunden nach einer neuen Version, lädt sie im Hintergrund und spielt sie beim nächsten Beenden ein. Unter Einstellungen → Programm steht der Stand; dort lässt sich auch sofort suchen.

Hier liegen nur die fertigen Installer. Die App braucht einen eigenen Jellyfin-Server mit Musik; ohne ihn zeigt sie nur das Anmeldeformular.
