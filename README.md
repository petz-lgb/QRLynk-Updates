# QRLynk – offizielle macOS-Downloads

Dieses öffentliche Repository stellt ausschließlich die fertigen Installations- und Updatepakete von **QRLynk** bereit. Der Quellcode und die Entwicklungsdateien bleiben im privaten Projekt-Repository.

## Versionen und Updates

Unter [Releases](https://github.com/petz-lgb/QRLynk-Updates/releases) stehen die Installationsdateien für **Apple Silicon** und **Intel** zur Verfügung.

Für den automatischen Aktualisierungsmechanismus verwendet QRLynk die Datei `latest.json` im jeweils neuesten Release sowie die separat kryptografisch signierten `.app.tar.gz`-Archive. Der öffentliche Updater-Schlüssel befindet sich in der installierten Anwendung; **private Schlüssel, Zertifikatspasswörter oder GitHub-Tokens werden hier niemals veröffentlicht**.

Die macOS-Anwendung ist lokal mit einem dauerhaften Codesign-Zertifikat signiert, aber **nicht Apple-notarisiert**. Bei der ersten Installation können deshalb macOS-Gatekeeper-Rückfragen auftreten.

© 2026 by Patric Schaubrenner
