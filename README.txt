ZapBox - IPTV-Player
1. Android Studio öffnen -> "Open" -> diesen Ordner wählen, Gradle-Sync abwarten.
2. Emulator "Android TV" oder Fire-TV-Stick (ADB) wählen, Run drücken.
3. Xtream-Daten oder M3U-Link (+ optional XMLTV-URL) eingeben.

Funktionen: Xtream/M3U, Kategorien, Suche, Favoriten, Zuletzt gesehen,
Jetzt/Danach im Player, Programmführer (XMLTV-Raster), Profile,
Kinderprofile, PIN-Kindersicherung für Kategorien.
Player: Hoch/Runter = Sender wechseln, Zurück = zurück.

Performance: Playlist und EPG werden lokal gecacht (sofortiger Start),
Aktualisierung läuft im Hintergrund. Zappen mit kleinem Puffer und kurzer
Verzögerung, Senderlogos mit Bild-Cache (Coil).
Für den Alltag eine signierte Release-APK bauen (Build > Generate Signed Bundle / APK).

APK über GitHub bauen: Projekt in ein neues GitHub-Repository hochladen (Branch "main"),
dann Tab "Actions" > "Build APK" > "Run workflow". Nach ca. 5-10 Min. unter
"Artifacts" die Datei ZapBox-APK herunterladen und entpacken.
