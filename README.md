# Stickie durch die Schattenwelt

[**Spiel öffnen**](https://u4600395921-sys.github.io/stickie-schattenwelt/)

Kostenloses 2D-Abenteuer im Querformat: 100 Level, neue Bosskämpfe und eine Reise durch die Zeit, Nahkampf und Fernkampf, Lichtdorf, Waffenladen, zusätzliche Lebenspunkte und deutsche Boss-Dialoge.

## Auf dem iPhone

1. Öffne den Spiel-Link in Safari.
2. Drehe das iPhone ins Querformat und tippe auf **Spiel starten**.
3. Über **Teilen → Zum Home-Bildschirm** kannst du ein App-Symbol hinzufügen.

Auf Android funktioniert derselbe Link in Chrome; dort kannst du das Spiel ebenfalls zum Startbildschirm hinzufügen. Es gibt keine Werbung und keine echten Geldkäufe.

## Schatten-Update

Nach dem Schattenkönig geht die Reise auf der Lichtwiese weiter. Boss 60 ist besiegbar. Nur bei Boss 70 gehört die Niederlage zur Geschichte: Danach erhältst du Sense und Krone, und im Lichtdorf erscheint das Haus der Helden. Dort wechselst du zu Sticky Lina und ihren eigenen Waffen. Mit nach oben gehaltenem Waffenstick gleitet Lina; auf dem Computer geht das auch mit G.

Die Schatten-Sense macht 5 Grundschaden. 50 erfolgreiche Treffer laden sie auf. Ihre Spezialattacke verwandelt dich für zehn Sekunden: fünffacher Schaden (25 mit der Sense) und vollständiger Schutz vor Schaden. In dieser Form reicht es, Gegner beim Laufen zu berühren, um ihnen 25 Schaden zuzufügen. Pro Gegner gibt es eine halbe Sekunde Trefferpause. Während der Verwandlung sammelt sich keine neue Ladung. Angefangene Ladung bleibt beim Levelwechsel und am Kontrollpunkt erhalten: 48/50 bleiben im nächsten Level 48/50. Sie wird auch im Spielstand gespeichert. Die riesige Sense hat in der Schattenform eine 2,35-fache Reichweite; ihre gebogene Klinge trifft dort, wo sie zu sehen ist.

Die Kapitel-Cutscenes fahren mit weichen Zooms zur sprechenden Figur und kehren zum Schluss in die Übersicht zurück. Untertitel und Überspringen bleiben fest am Bildschirm.

Der Dieb stiehlt die Krone. Nach seiner Gefangennahme wird Sticky Lina enttarnt. Dein jüngeres Ich fordert dich heraus; dein Sieg verändert die Vergangenheit und zerbricht die Welt. In Level 100 erzählst du dem obersten Strichmännchen deine Geschichte, bis es der Reparatur zustimmt.

Die Hintergründe werden jetzt als vorbereitete Bilder gezeichnet. Das Spiel rendert intern mit höchstens 1280 × 720 und läuft mit maximal 60 Bildern pro Sekunde, in Menüs mit 30. Vorhandene Spielstände derselben Web-Adresse werden weiterhin unterstützt. Durch den Wechsel des GitHub-Kontos hat diese Veröffentlichung eine neue Web-Adresse. Spielstände vom bisherigen Link werden nicht automatisch übertragen; sie bleiben beim bisherigen Link gespeichert.

## Levelauswahl

Die beiden festen Knöpfe **1–50** und **51–100** wechseln zur jeweiligen Levelseite. Auch wiederholtes Tippen bleibt auf der gewählten Seite. Zusätzliche simulierte Mausklicks eines Touchscreens werden nicht doppelt verarbeitet. Bereits freigeschaltete Level können erneut gespielt werden, ohne den höchsten Fortschritt zu verlieren.

## Codes

Öffne **Codes eingeben**, gib `/giveadmin_lv100` ein und bestätige mit **Code einlösen**. Der Befehl schaltet alle 100 Level dauerhaft frei und startet sofort Level 100. Coins, Zusatzleben und vorhandene Waffen bleiben erhalten. Der Abschlussdialog wird dadurch nicht automatisch gewonnen.

## Spielstände

Fortschritt, Coins, Waffen und Zusatzleben werden in diesem Browser auf diesem Gerät gespeichert. Benutze keinen privaten Browsermodus. Das Löschen der Websitedaten entfernt auch den Spielstand. Spielstände werden nicht zwischen Geräten synchronisiert.

## Updates

`stickie-web.zip.b64` enthält die fertige Web-App als Textkodierung. Der Workflow wandelt sie in die ZIP-Datei zurück und veröffentlicht das Spiel. Wird das Paket auf `main` ersetzt, erscheint die neue Version automatisch unter **demselben Link**. Ein normaler Upload als `stickie-web.zip` wird ebenfalls unterstützt und hat Vorrang. Keine neue App-Installation nötig. Der Godot-Export erzeugt für jeden Build einen neuen Cache-Stand. Der Update-Knopf bleibt während des Downloads sichtbar und zeigt die geladenen Dateien. Erst wenn alle Spieldateien vollständig geprüft sind, wird die neue Version gestartet. Bei einem Fehler bleibt **Update erneut versuchen** stehen. Ein laufendes Spiel wird nicht ungefragt neu gestartet. Falls eine alte Installation festhängt: [Spiel aktualisieren](https://u4600395921-sys.github.io/stickie-schattenwelt/aktualisieren.html). Dabei bleiben Spielstände, Coins und Waffen gespeichert.

Die Web-App wurde mit Godot 4.7.2 aus dem vorhandenen Spielprojekt exportiert. Sie verwendet **keine Threads**, sodass keine speziellen COOP/COEP-Header erforderlich sind. Das bearbeitbare Quellprojekt wird lokal aufbewahrt und gehört nicht zum öffentlichen Repository.

## Veröffentlichung

GitHub Pages verwendet **GitHub Actions** als Quelle. Der Workflow entpackt die geprüfte Web-App und veröffentlicht sie. Das Hosting des öffentlichen Repositorys über GitHub Pages ist im kostenlosen GitHub-Tarif enthalten.

Die erste Version wurde im Desktop-Browser geprüft. Ein Test auf einem echten iPhone bleibt notwendig, besonders für Touch-Steuerung, Bildschirmtastatur und Leistung.
