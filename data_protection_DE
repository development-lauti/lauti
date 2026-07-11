# Datenschutzerklärung für Lauti

Stand: 11. Juli 2026

Diese Datenschutzerklärung informiert Sie darüber, welche Daten bei der Nutzung der App **Lauti** verarbeitet werden und wie damit umgegangen wird.

## 1. Verantwortlicher

E-Mail: development.lauti@gmail.com

## 2. Grundprinzip: lokale Datenspeicherung

Lauti ist eine App zur Wiedergabe von Hörspielen, Musik und Podcasts über NFC-Karten, die insbesondere für die Nutzung durch Kinder ("Kids-Modus") konzipiert ist. Die App funktioniert **ohne Benutzerkonto und ohne Registrierung**. Alle von Ihnen angelegten Inhalte (Kartensets, Karten, Wiedergabelisten, Verlauf) werden ausschließlich **lokal auf Ihrem Gerät** in einer SQLite-Datenbank gespeichert. Es findet **kein automatischer Abgleich mit einem Server des Anbieters statt** – der Anbieter der App hat keinen Zugriff auf diese Daten.

Im Einzelnen werden lokal gespeichert:

- Namen und Beschreibungen von Kartensets
- NFC-Karten-Kennungen (technische UID der Karte, z. B. `aa:bb:cc:dd`) und die ihnen zugeordneten Titel/Symbole
- Wiedergabelisten und die darin enthaltenen Medieneinträge (Pfade zu lokalen Audiodateien, RSS-Feed-URLs oder Titel von Musikserver-Tracks)
- der Wiedergabeverlauf der letzten 50 abgespielten Listen
- das vierstellige Eltern-Passwort zum Verlassen des Kids-Modus (gespeichert über `shared_preferences` auf dem Gerät)

Diese Daten verbleiben auf dem Gerät, bis Sie sie in der App löschen oder die App deinstallieren.

## 3. NFC-Funktion

Lauti nutzt die NFC-Schnittstelle Ihres Geräts, um NFC-Karten/-Tags zu erkennen. Dabei wird ausschließlich die technische Seriennummer (UID) des Tags ausgelesen und lokal einer von Ihnen angelegten Wiedergabeliste zugeordnet. Es werden keine personenbezogenen Daten auf den Tags gespeichert oder von diesen gelesen, und die UID wird nicht an Server Dritter oder des Anbieters übertragen.

## 4. Zugriff auf lokale Mediendateien

Um eigene Audiodateien (z. B. Hörspiele) einer Wiedergabeliste hinzuzufügen, benötigt die App Zugriff auf den lokalen Speicher bzw. die Mediathek Ihres Geräts (Android-Berechtigungen `READ_MEDIA_AUDIO` / `READ_EXTERNAL_STORAGE`). Die ausgewählten Dateien werden ausschließlich lokal abgespielt; es findet kein Upload dieser Dateien statt.

## 5. Internetverbindungen

Die App benötigt die Berechtigung `INTERNET`, die ausschließlich für die folgenden, von Ihnen selbst konfigurierten bzw. ausgelösten Funktionen genutzt wird. Der Anbieter der App selbst betreibt keinen Server, an den App-Daten übermittelt werden, und es kommen keine Analyse-, Tracking- oder Werbedienste zum Einsatz.

### 5.1 RSS-/Podcast-Feeds

Wenn Sie einer Wiedergabeliste einen RSS-Feed (z. B. einen Podcast) hinzufügen, ruft die App die von Ihnen hinterlegte Feed-URL sowie die darin enthaltenen Audiodateien direkt beim jeweiligen Anbieter dieses Feeds ab. Dabei werden technisch bedingt Verbindungsdaten (z. B. IP-Adresse) an den Betreiber dieses Feeds bzw. Servers übermittelt. Es gelten die Datenschutzbestimmungen des jeweiligen Feed-Anbieters, auf die der Anbieter von Lauti keinen Einfluss hat.

### 5.2 Eigener Musikserver (Navidrome/Subsonic-kompatibel)

Lauti bietet optional die Möglichkeit, sich mit einem eigenen, selbst betriebenen oder von Ihnen ausgewählten Musikserver (z. B. Navidrome, Airsonic, Gonic) zu verbinden. Wenn Sie diese Funktion nutzen, geben Sie Server-Adresse, Benutzername und Passwort ein. Diese Zugangsdaten werden:

- **lokal auf Ihrem Gerät** über `shared_preferences` gespeichert,
- ausschließlich zur Authentifizierung gegenüber **dem von Ihnen angegebenen Server** verwendet (Verbindungsaufbau, Suche, Streaming von Titeln über die Subsonic-API),
- **nicht** an den Anbieter von Lauti übertragen.

Das Passwort wird bei jeder Anfrage nicht im Klartext, sondern als gesalzener Hashwert an den Musikserver übermittelt. Für die Verarbeitung Ihrer Daten auf dem von Ihnen konfigurierten Musikserver ist der jeweilige Betreiber dieses Servers verantwortlich.

### 5.3 In-App-Käufe (Unterstützungs-/Spendenfunktion)

Für freiwillige einmalige Unterstützungsbeträge nutzt die App die In-App-Kauf-Schnittstellen von Google Play bzw. dem Apple App Store. Die Zahlungsabwicklung selbst erfolgt vollständig durch Google bzw. Apple; Lauti erhält lediglich eine Bestätigung über den erfolgten Kauf, jedoch keine Zahlungs- oder Kontodaten. Es gelten zusätzlich die Datenschutzbestimmungen von Google bzw. Apple.

## 6. Keine Analyse-, Tracking- oder Werbedienste

Lauti bindet keine Analyse-Tools (z. B. Google Analytics, Firebase), keine Crash-Reporting-Dienste und keine Werbenetzwerke ein. Es findet kein Tracking Ihres Nutzungsverhaltens statt.

## 7. Nutzung durch Kinder (Kids-Modus)

Der Kids-Modus ist so gestaltet, dass Kinder ausschließlich NFC-Karten scannen und Wiedergabelisten abspielen können; eine Bedienung der Geräteeinstellungen oder das Verlassen des Modus ist nur über ein von den Eltern festgelegtes Passwort möglich. Im Kids-Modus werden **keine zusätzlichen Daten** über das Kind erhoben, gespeichert oder an Dritte übermittelt. Es werden keine Werbe- oder Trackingdienste eingeblendet.

## 8. Speicherdauer und Löschung

Die in Abschnitt 2 genannten Daten werden gespeichert, bis Sie sie manuell löschen (z. B. einzelne Karten, Sets oder den Verlauf) oder die App deinstallieren bzw. deren Daten über die Systemeinstellungen zurücksetzen. Der Wiedergabeverlauf wird zusätzlich automatisch auf die letzten 50 Einträge begrenzt.

## 9. Ihre Rechte

Da alle personenbezogenen bzw. nutzungsbezogenen Daten ausschließlich lokal auf Ihrem Gerät gespeichert werden, haben Sie jederzeit vollen Zugriff auf und volle Kontrolle über diese Daten direkt in der App bzw. über die Einstellungen Ihres Betriebssystems. Unabhängig davon stehen Ihnen nach der DSGVO grundsätzlich folgende Rechte zu, soweit personenbezogene Daten betroffen sind: Auskunft (Art. 15 DSGVO), Berichtigung (Art. 16 DSGVO), Löschung (Art. 17 DSGVO), Einschränkung der Verarbeitung (Art. 18 DSGVO), Datenübertragbarkeit (Art. 20 DSGVO) sowie Widerspruch (Art. 21 DSGVO). Für Anfragen wenden Sie sich an die in Abschnitt 1 genannte Kontaktadresse. Zudem besteht ein Beschwerderecht bei einer Datenschutzaufsichtsbehörde.

## 10. Datensicherheit

Da sämtliche App-Daten lokal auf Ihrem Gerät verbleiben, hängt deren Schutz maßgeblich von der Absicherung Ihres Geräts ab (z. B. Bildschirmsperre). Bei Verbindungen zu einem selbst konfigurierten Musikserver empfehlen wir die Nutzung einer verschlüsselten Verbindung (HTTPS).

## 11. Änderungen dieser Datenschutzerklärung

Diese Datenschutzerklärung kann bei Weiterentwicklung der App oder bei Änderungen rechtlicher Vorgaben angepasst werden. Die jeweils aktuelle Fassung finden Sie in der App bzw. auf der zugehörigen Store-Seite.

## 12. Kontakt

Bei Fragen zum Datenschutz wenden Sie sich bitte an: development.lauti@gmail.com
