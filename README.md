<img width="38" height="38" alt="sub_rclone" src="https://github.com/user-attachments/assets/d56a183e-5011-45e2-8b13-62208257df0b" />
<svg xmlns="http://www.w3.org/2000/svg" width="38" height="38" viewBox="0 0 38 38">
  <rect x="4" y="4" width="30" height="30" rx="6" fill="#0284c7" stroke="#7dd3fc" stroke-width="1.8"/>
  <path fill="#ffffff" d="M12 27a5 5 0 0 1-1-9.8 7 7 0 0 1 13.5-2A4.5 4.5 0 0 1 26 27H12z"/>
  <path fill="none" stroke="#0284c7" stroke-width="2.4" stroke-linecap="round" d="M15 21c-1.5 0-2.5 1-2.5 2s1 2 2.5 2c2 0 4-4 6-4 1.5 0 2.5 1 2.5 2s-1 2-2.5 2c-2 0-4-4-6-4z"/>
</svg>

<img width="420" height="100" alt="watermark-default" src="https://github.com/user-attachments/assets/0fc0c982-d8f5-4ea7-8ba2-a6a32c650818" />


# Rclone Personal Cloud Connector

Diese Anwendung ist ein rein privater, nicht-kommerzieller OAuth2-Client zur Anbindung von `rclone` an das persönliche Google Drive-Konto des Projektinhabers.

- **Status:** Private Einzelplatz-Instanz (Keine öffentliche Registrierung möglich)
    
- **Zweck:** Lokale Dateisynchronisation, Mount und clientseitige Verschlüsselung (`rclone crypt`)
    

## Datenschutzerklärung (Privacy Policy)

### 1\. Zweck der Anwendung

Dieser OAuth2-Client dient ausschließlich dem Kontoinhaber zur direkten Dateisynchronisation und Verschlüsselung zwischen dem lokalen Betriebssystem und dem eigenen Google Drive-Speicher über das Open-Source-Werkzeug `rclone`.

### 2\. Datenerhebung und Datenspeicherung

Diese Anwendung erhebt, speichert, analysiert oder überträgt keinerlei personenbezogene Daten an Dritte oder externe Server. Die Kommunikation findet ausschließlich direkt über verschlüsselte HTTPS-Verbindungen zwischen dem lokalen Endgerät des Nutzers und den offiziellen Google Drive APIs statt.

### 3\. Umgang mit OAuth2-Tokens und Google-Nutzerdaten

Die bei der Authentifizierung generierten OAuth2-Zugriffstokens werden ausschließlich lokal auf dem Endgerät des Projektinhabers (in der lokalen Konfigurationsdatei `rclone.conf` bzw. im lokalen System-Keyring) gespeichert. Die Nutzung und Übertragung von Informationen, die von Google APIs empfangen werden, erfolgt in strikter Übereinstimmung mit der _Google API Services User Data Policy_.

### 4\. Widerruf des Zugriffs

Der Zugriff der Anwendung kann jederzeit in den Google-Kontoeinstellungen unter _Sicherheit → Verbindungen zu Drittanbieter-Apps und -Diensten_ widerrufen sowie lokal durch Löschen des Tokens entfernt werden.

## Nutzungsbedingungen (Terms of Service)

### 1\. Eingeschränkter Nutzerkreis

Diese Anwendung ist privat und ausschließlich für die Nutzung durch den autorisierten Administrator des zugehörigen Google Cloud-Projekts bestimmt. Eine Nutzung durch Dritte ist ausgeschlossen.

### 2\. Haftungsausschluss

Die Bereitstellung und Nutzung erfolgt auf eigenes Risiko des Projektinhabers ohne jegliche Gewährleistung.

_Kontakt: Siehe hinterlegte Entwickler-Kontaktadresse im Google OAuth-Zustimmungsbildschirm._
