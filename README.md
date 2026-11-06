# TankWiki Android – Test-Releases

Dieses öffentliche Repository enthält ausschließlich fertige signierte Android-Test-APKs, Prüfsummen, eine kurze Anleitung und Update-Metadaten. Der Quellcode wird getrennt privat entwickelt.

## Installation

Die APK unter [Releases](https://github.com/Snip3r-1408/TankWiki-Android-Releases/releases) herunterladen und auf dem Android-Gerät öffnen. Voraussetzung: Android 7 oder neuer und ein aktueller TWA-fähiger Browser, zum Beispiel Chrome.

Version `0.0.2-test` muss einmal manuell über die bisherige `0.0.1-test` installiert werden. Ab dann prüft die App bei jedem normalen Start über das App-Symbol `main/update.json` und lädt eine neuere APK herunter. Vor der Übergabe an Android werden Dateigröße, SHA-256, Paketkennung, Versionscode und der Signierer geprüft. Android benötigt eine Installationsbestätigung. Offline oder bei unveränderter Version bleibt TankWiki nutzbar.

PDF-Teilen und direkte Weblinks gehen unmittelbar zur Web-App; ein Wechsel aus dem Hintergrund ist kein neuer App-Icon-Start. Die APK ist unabhängig von Core-/AddOn-Versionen. Eine APK-Veröffentlichung installiert keine Serverupdates.

## Updatekanal

`update.json` verweist nur auf ein bereits veröffentlichtes APK-Asset dieses Repositories. Zuerst APK samt Prüfsumme veröffentlichen und prüfen; danach den Kanal aktualisieren. APKs verwenden den Paketnamen `de.snip3r.tankwiki.test` und denselben Test-Signierschlüssel. Keine Schlüssel oder Zugangsdaten werden hier hinterlegt.

Android-Tests sind Vorabversionen. Build- und Signaturprüfungen ersetzen keine Geräteabnahme. Die Domain-Verknüpfung für Darstellung ohne Browserleiste ist separat einzurichten.
