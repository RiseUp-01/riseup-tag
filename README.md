# tag.rise-up.store

Die beiden Zuordnungsdateien, mit denen iPhone und Android einen gescannten RiseUp-Tag der App
zuordnen statt dem Browser. Kein Inhalt, keine Anwendung, nur zwei kleine Dateien.

- `.well-known/apple-app-site-association` für iOS
- `.well-known/assetlinks.json` für Android

Beides ist öffentlich und enthält keine Geheimnisse: die App-Kennung und den öffentlichen
Fingerabdruck des Signaturzertifikats. Die Quelle liegt im Hauptprojekt unter
`RiseUp-Dokumente/Website/tag-subdomain/`.
