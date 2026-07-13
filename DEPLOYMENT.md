# Veröffentlichung der Hagi-Mechanik-Konzeptvorschau

## Empfohlene Lösung: GitHub Pages

GitHub Pages liefert eine dauerhafte HTTPS-Adresse, beispielsweise:

`https://<github-benutzername>.github.io/hagi-mechanik-preview/`

Die Website bleibt ausdrücklich als Konzeptvorschau gekennzeichnet und enthält `noindex`, `nofollow` sowie eine sperrende `robots.txt`. Die URL ist technisch öffentlich und kann an ausgewählte Personen versendet werden, soll aber nicht beworben werden.

Benötigte Schritte:

1. GitHub-Anmeldung für das lokale Veröffentlichungswerkzeug erlauben.
2. Ein neues Repository `hagi-mechanik-preview` anlegen.
3. Nur die Website-Dateien und Bilder hochladen.
4. GitHub Pages für den Hauptbranch aktivieren.
5. Die erzeugte HTTPS-Adresse prüfen und weitergeben.

## Sofortlösung: ngrok

Ngrok erzeugt innerhalb weniger Sekunden eine HTTPS-Adresse zur lokal laufenden Vorschau. Sie bleibt nur erreichbar, solange der lokale Webserver und der Tunnel auf diesem Mac laufen. Das eignet sich für eine kurzfristig vereinbarte Präsentation, nicht als dauerhafte Kunden-URL.

## Uploadfertiges Paket

`hagi-preview-deploy.zip` enthält ausschliesslich die für das Hosting benötigten Dateien:

- `index.html`
- `styles.css`
- `script.js`
- `robots.txt`
- `assets/`

Das Paket kann alternativ bei einem bestehenden Schweizer Webhoster in ein passwortgeschütztes Unterverzeichnis hochgeladen werden. Dafür werden FTP-/SFTP- oder Hosting-Panel-Zugangsdaten und die gewünschte Domain benötigt.
