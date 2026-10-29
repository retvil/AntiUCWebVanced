# AntiUC Vanced

**🇬🇧 English** | [🇷🇺 Русский](README.ru.md) | [🇺🇦 Українська](README.uk.md) | [🇰🇿 Қазақша](README.kk.md) | [🇩🇪 Deutsch](README.de.md) | [🇫🇷 Français](README.fr.md) | [🇪🇸 Español](README.es.md) | [🇵🇱 Polski](README.pl.md) | [🇹🇷 Türkçe](README.tr.md) | [🇨🇳 中文](README.zh.md)

## 🌐 Forks

<a href="https://github.com/retvil/AntiBaiduVanced"><img src="https://raw.githubusercontent.com/retvil/AntiBaiduVanced/main/logo.png" alt="AntiBaiduVanced" width="16" height="16" style="vertical-align:middle"> AntiBaiduVanced</a>  |  <a href="https://github.com/retvil/AntiSogouVanced"><img src="https://raw.githubusercontent.com/retvil/AntiSogouVanced/main/logo.png" alt="AntiSogouVanced" width="16" height="16" style="vertical-align:middle"> AntiSogouVanced</a>  |  <a href="https://github.com/retvil/Anti2345Vanced"><img src="https://raw.githubusercontent.com/retvil/Anti2345Vanced/main/logo.png" alt="Anti2345Vanced" width="16" height="16" style="vertical-align:middle"> Anti2345Vanced</a>  |  **AntiUCWebVanced**  |  <a href="https://github.com/retvil/AntiNaverVanced"><img src="https://raw.githubusercontent.com/retvil/AntiNaverVanced/main/logo.png" alt="AntiNaverVanced" width="16" height="16" style="vertical-align:middle"> AntiNaverVanced</a>  |  <a href="https://github.com/retvil/AntiKakaoVanced"><img src="https://raw.githubusercontent.com/retvil/AntiKakaoVanced/main/logo.png" alt="AntiKakaoVanced" width="16" height="16" style="vertical-align:middle"> AntiKakaoVanced</a>  |  <a href="https://github.com/retvil/AntiQQVanced"><img src="https://raw.githubusercontent.com/retvil/AntiQQVanced/main/logo.png" alt="AntiQQVanced" width="16" height="16" style="vertical-align:middle"> AntiQQVanced</a>  |  <a href="https://github.com/retvil/AntiWeChatVanced"><img src="https://raw.githubusercontent.com/retvil/AntiWeChatVanced/main/logo.png" alt="AntiWeChatVanced" width="16" height="16" style="vertical-align:middle"> AntiWeChatVanced</a>  |  <a href="https://github.com/retvil/AntiTencentVideoVanced"><img src="https://raw.githubusercontent.com/retvil/AntiTencentVideoVanced/main/logo.png" alt="AntiTencentVideoVanced" width="16" height="16" style="vertical-align:middle"> AntiTencentVideoVanced</a>  |  <a href="https://github.com/retvil/AntiVKGroupVanced"><img src="https://raw.githubusercontent.com/retvil/AntiVKGroupVanced/main/logo.png" alt="AntiVKGroupVanced" width="16" height="16" style="vertical-align:middle"> AntiVKGroupVanced</a>  |  <a href="https://github.com/retvil/AntiYandexVanced"><img src="https://raw.githubusercontent.com/retvil/AntiYandexVanced/main/logo.png" alt="AntiYandexVanced" width="16" height="16" style="vertical-align:middle"> AntiYandexVanced</a>

## Was ist das?

UC installiert nicht nur einen Browser — es trägt sich still über vierzig Systemmechanismen als Standardsuche und Standardbrowser ein: Registry-Assoziationen, Enterprise-Richtlinien, Profileinstellungen von Browsern, sogar Suchmaschinen-Datenbanken in Chromium-Profilen. Allein das Entfernen des Browsers macht das nicht rückgängig.

**AntiUC Vanced** (ein Fork von [retvil/AntiYandexVanced](https://github.com/retvil/AntiYandexVanced)) findet **alle 28/39 Hijack-Vektoren**, entfernt sie mit einem Klick und **verriegelt dann Ihre Standardsuche** hart auf eine von Ihnen gewählte Suchmaschine über Windows-Enterprise-Richtlinien — damit nichts sie laut zurückholen kann.

## Funktionen

- **Hijack-Scanner** — erkennt 28 Vektoren (VANCED) / 39 Vektoren (EXTENDED): Installationspfade, Uninstall-Registry-Einträge, `UserChoice`-Assoziation, `StartMenuInternet`-Registrierungen, `Software\UC`-Schlüsselbäume, Hijack über `DefaultSearchProvider*`-Richtlinien, Chromium-Profil-`Preferences`, Schlüsselwörter in `Web Data` (SQLite), Firefox `search.json.mozlz4`, Legacy-`SearchScopes`, Autostart-Einträge, geplante Aufgaben, Windows-Dienste, IME Switcher, Dateizuordnungen, UC-Disk-Shell-Integration, deaktivierter Autostart, App Paths, Verknüpfungen, ProgramData/Roaming-Reste, hosts-Einträge, Firewall-Regeln, URI-Protokolle, Browser-Erweiterungen, ucweb.ru-Cookies, „Öffnen mit“-Zuordnungen, Prefetch/WER-Spuren, Defender-Ausschlüsse, Tastaturlayouts, IE-Startseiten-Hijack, Richtlinien für Start-URLs (`RestoreOnStartupURLs`), Firefox-Startseite, IE-Zonemap, RegisteredApplications-Einträge, MUICache-Spuren, %TEMP%-Installer, Store-Apps (UC Music), Produktverzeichnisse, lokale Datenverzeichnisse, UC.DNS
- **Entfernung mit einem Klick** — jeder Vektor hat seinen eigenen Remover; gesperrte Datenbanken werden ehrlich gemeldet, ohne Abstürze
- **Harte Suchrichtlinie** — verriegelt die Standardsuche auf eine von 10 Suchmaschinen (Google, Bing, DuckDuckGo, Brave Search, Startpage, Mojeek, Qwant, Ecosia, Yahoo, SearXNG) über HKLM-Richtlinien für Chrome, Edge, Brave, Vivaldi, Opera und UC Browser + `policies.json` für Firefox/Waterfox
- **Richtlinien-Bereinigung** — entfernt UC-`DefaultSearchProvider*`-Werte aus der Registry
- **10 UI-Sprachen** — ru, en, uk, kk, de, fr, es, pl, tr, zh; Systemsprache wird automatisch erkannt
- **Leichtes UI** — ttkbootstrap, vertikales Layout, fixierte Statusleiste und Fußzeile

## Screenshot

<details>
<summary>Hauptfenster</summary>

![AntiUCVanced Hauptfenster](screenshot.png)

</details>

## Fertige Builds

Download von [Releases](https://github.com/retvil/AntiUCVanced/releases):

- **Windows** — `AntiUCVanced.exe` (portabel, eine Datei, ~35 MB) — entfernt UC Browser und die UC-Suche
- **Windows** — `AntiUCExtended.exe` (portabel, eine Datei, ~35 MB) — Entfernung aller UC-Produkte (UC Disk, ime-Switcher-Verlauf, systemweite Spuren, Store-Apps, UC.DNS)

Als **Administrator ausführen** — HKLM-Richtlinien und Registry-Bereinigung erfordern erhöhte Rechte.

## Installation aus dem Quellcode

Python 3.10+ erforderlich ([python.org](https://python.org)).

```bash
git clone https://github.com/retvil/AntiUCVanced.git
cd AntiUCVanced
pip install psutil ttkbootstrap
python main.py
```

Eigenes EXE bauen: `build.bat` ausführen (PyInstaller, Ergebnis in `dist/`).

## Verwendung

1. **Prozesse beenden** → **UC suchen** → **UC löschen** — den Browser selbst entfernen.
2. **Such-Hijacks scannen** — zeigt alle Wege, wie UC sich ins System eingegraben hat.
3. **Hijacks entfernen** — zuerst alle Browser schließen, dann alles Gefundene entfernen.
4. Suchmaschine wählen → **Richtlinie anwenden** — die Standardsuche ist auf Systemebene verriegelt.

## FAQ

- **Warum Administrator?** Suchrichtlinien liegen in HKLM, die Hijack-Bereinigung berührt die System-Registry — erhöhte Rechte nötig.
- **„Database locked" in den Ergebnissen?** Während der Bereinigung lief ein Chromium-Browser. Alle Browser schließen und die Entfernung wiederholen.
- **Wie entferne ich die Suchrichtlinie?** Die Schaltfläche **UC-Richtlinien entfernen** räumt die Richtlinienwerte weg; in Firefox kann man zusätzlich die Datei `distribution\policies.json` löschen.

## Autor & Support

Изначальная идея: [retvil/AntiYandexVanced](https://github.com/retvil/AntiYandexVanced)

Wenn dich das Tool von UC befreit hat, kannst du die Entwicklung unterstützen:

**Krypto:**

- BTC: `bc1qunld3rsp37qf5gg69aune50y0qqkd0eugg7j97`
- TON: `UQDmvr4SKOxSION3Yky6aOgzAnCDXySPuAbG4EKJa5JUT7tC`
- USDT (TRC20): `TBPJSSLu1mUcX54g9UyxUohYGf2fuRvbwd`
- USDT (ERC20): `0x25CAED3776Ef5b18E03392bC5b254Bbd78E8180C`
- USDT (SOL): `3qgN5z291CEcj2FUi2Zza5DioxKgNw72kC7P52pCcTrG`

## Lizenz

MIT — siehe [LICENSE](../LICENSE).





