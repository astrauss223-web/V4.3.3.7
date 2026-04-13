# 📊 Robustes Portfolio – Benutzerhandbuch (V4.3.3.7)

---

## Was ist das „Robuste Portfolio"?

Das **Robuste Portfolio** ist ein interaktives Planungstool für die strukturierte Zusammenstellung eines individuellen Anlageportfolios. Es unterstützt Berater und Anleger dabei, Fonds aus verschiedenen Anlagekategorien systematisch auszuwählen, zu gewichten und auf einen Blick zu analysieren – ohne externe Software oder Fachkenntnisse in Tabellenkalkulation.

Das Tool funktioniert vollständig im Browser (offline, keine Internetverbindung nötig) und speichert das Portfolio automatisch lokal.

---

## 🎯 Mehrwert des Tools

| Vorteil | Beschreibung |
|---|---|
| **Strukturierte Auswahl** | Fonds werden nach Managementansatz in klar abgegrenzte Schichten (Schichten-Turm) eingeordnet |
| **Automatische Gewichtung** | Sobald Beträge eingegeben werden, errechnet das Tool prozentuale Gewichtungen automatisch |
| **Geographische Transparenz** | Die Länder- und Regionalverteilung des Gesamtportfolios wird visuell aufbereitet (6 Regionen) |
| **Zeitphasen-Logik** | Fonds können nach Anlagehorizont und Lebensphase (Zeitphasen 1–6) gefiltert werden |
| **Sofort-Export** | Das fertige Portfolio kann jederzeit als PDF gedruckt oder heruntergeladen werden |
| **Datensicherung** | Das Portfolio kann als JSON-Datei gespeichert und später wiedergeladen werden |

---

## 🖥️ Erste Schritte

### 1. Gesamtvermögen eingeben
Tragen Sie im Bereich **„Anlageplanung"** (rechts neben dem Turm) das anzulegende Gesamtvermögen ein und bestätigen Sie mit der **Enter-Taste**.

Optional: Geben Sie auch eine monatliche Sparrate ein.

### 2. Fonds auswählen
Klicken Sie auf eine der **farbigen Schichten im Turm** (z. B. „Märkte", „Ausgewogene Vermögensverwalter"), um die verfügbaren Fonds für diese Kategorie zu sehen.

Im Auswahlfenster können Sie:
- Nach Fonds oder WKN **suchen** (Suchfeld oben links)
- Nach **Managementansatz filtern** (Dropdown)
- Den **Einmalbeitrag** und/oder die **monatliche Sparrate** für jeden Fonds eingeben
- Fonds durch Klick auf **„+ Auswählen"** dem Portfolio hinzufügen

> 💡 Das 🌍-Symbol neben dem Fondsnamen zeigt beim Darüberfahren die **Top-5-Ländergewichtungen** des Fonds – inklusive Aufschlüsselung nach **Aktien** (blau) oder **Anleihen** (grün), sofern der Fonds eindeutig einer Anlageklasse zugeordnet werden kann.

### 3. Portfolio verwalten
In der Spalte **„Mein Portfolio"** (rechts) sehen Sie alle ausgewählten Fonds. Einzelne Fonds können mit dem **✕-Button** wieder entfernt werden.

### 4. Zeitphasen nutzen (optional)
Klicken Sie auf einen der **Zeitphasen-Buttons** (Zeitphase 1–6), um zu sehen, welche Managementansätze für diese Lebensphase empfohlen werden. Die entsprechenden Schichten im Turm werden optisch hervorgehoben.

---

## 📋 Features im Überblick

### Anlageplanung-Karte
| Element | Funktion |
|---|---|
| **Anzulegendes Gesamtvermögen** | Eingabe des Gesamtbetrags in € |
| **Anzulegende Sparrate monatlich** | Optionale monatliche Zusatzsparrate |
| **Einmal Verplant / Verbleibend** | Zeigt, wie viel bereits auf Fonds verteilt wurde |
| **Sparrate Verplant / Verbleibend** | Gleiche Übersicht für die Sparrate |
| **🌍 Länder aktualisieren** | Nur für Administratoren (siehe unten) |
| **🖨️ Drucken** | Druckt die Anlageplanung-Karte im A3-Querformat |

### Portfolio-Info-Leiste (unterhalb des Turms)
| Bereich | Funktion |
|---|---|
| **Verteilung nach Schicht** | Zeigt, wie viel € je Investmentschicht eingeplant ist – in Turm-Reihenfolge (unten nach oben) |
| **Länderverteilung nach Region** | Zeigt die geographische Aufteilung des Portfolios in 6 Regionen, jeweils mit Aktien- und Anleihen-Anteil |

> 💡 **Tipp:** Fahren Sie mit der Maus über einen Regions-Cluster (z. B. „Nordamerika 65,2%"), um die **Top-5-Länder** dieser Region zu sehen – jeweils mit Gesamtanteil und Unterzeile für **Aktien** (blau) / **Anleihen** (grün). Die Summe aller Regionen ergibt stets **100%**.

### Regionale Cluster (ab V4.3.3.6) – Aktien/Anleihen-Aufschlüsselung (neu ab V4.3.3.7)

Das Portfolio wird automatisch in **6 Weltregionen** eingeteilt. Die Prozentsätze werden auf Basis aller Fonds berechnet, für die Ländergewichtungen vorliegen, und auf 100% normalisiert.

Neu ab **V4.3.3.7**: Jeder Cluster zeigt zusätzlich zum Gesamtanteil die Aufschlüsselung nach Anlageklasse:
- 🔵 **Aktien-Anteil** – aus reinen Aktien- und Rohstofffonds (z. B. EB Aktien, WB Aktien)
- 🟢 **Anleihen-Anteil** – aus reinen Anleihenfonds (z. B. EB Anleihen, WB Anleihen, Geldmarkt)
- Mischfonds (VV-Fonds, WB Aktien/Anleihen) fließen nur in den **Gesamtanteil**, nicht in Aktien oder Anleihen – da die interne Aufteilung nicht bekannt ist.

| Region | Enthält | Farbe |
|---|---|---|
| 🔵 **Nordamerika** | USA, Kanada, Mexiko | Blau |
| 🟢 **Europa** | DE, FR, GB, CH, NL, AT, BE, SE, NO, DK, FI, ES, IT, PT, PL, CZ, HU, RO, GR, Baltikum … | Grün |
| 🟣 **Schwellenländer** | China, Indien, Brasilien, Mexiko, Türkei, Südafrika, Nigeria, Ägypten, Israel, Kasachstan, Pakistan, Emerging Markets … | Lila |
| 🩵 **Pacific** | Japan, Australien, Neuseeland, Südkorea, Taiwan, Hongkong, Singapur, Thailand, Vietnam, Philippinen, Indonesien, Malaysia … | Petrol |
| ⬜ **Sonstige ETF** | Irland, Luxemburg (erscheinen in Gewichtungen als Fondsdomizil-Proxy) | Dunkelgrau |
| ⬜ **Sonstige** | Sammel-Label wie „global", „sonstige", „Asien" (zu uneindeutig für eine klare Region), Frontier Markets | Hellgrau |

> **Hinweis Sonstige ETF:** Taucht „Irland" oder „Luxemburg" als Ländergewichtung auf, handelt es sich in der Regel um das rechtliche Domizil eines ETFs, nicht um eine echte Investition in dieses Land. Diese werden daher gesondert ausgewiesen.

> **Hinweis Sonstige:** Der generische Begriff „Asien" wird bewusst nicht Schwellenländern oder Pacific zugeordnet, da er in Fondsdaten sowohl entwickelte als auch aufstrebende Märkte umfassen kann.

### Fondsklassifizierung (neu ab V4.3.3.7)

Für die Aktien/Anleihen-Aufschlüsselung wird jeder Fonds anhand seines **Typs (Managementansatz)** automatisch klassifiziert:

| Klassifizierung | Fondstypen | Farbe |
|---|---|---|
| **Aktien** | EB Aktien, WB Aktien, EB Rohstoffe, EB Edelmetalle | 🔵 Blau |
| **Anleihen** | EB Anleihen, WB Anleihen, Anleihen Euro kurz, Anleihen flexibel, Geldmarkt, Renten, EB Anleihen (Kasse) | 🟢 Grün |
| **Gemischt** | VV defensiv, VV ausgewogen, VV dynamisch, WB Aktien/Anleihen, alle anderen | ⬜ Grau / kein Ausweis |

> **Hinweis:** Bei Mischfonds ist die interne Aktien-/Anleihenquote je nach Marktlage variabel und wird daher nicht aufgeteilt. Der gesamte Betrag fließt in die Gesamtregion, aber nicht in Aktien oder Anleihen.

### Verteilung nach Schicht

Die Aufschlüsselung folgt derselben **Reihenfolge wie der Turm** (von unten nach oben):

| Reihenfolge | Schicht |
|---|---|
| 1 | Tagesgeld |
| 2 | Kapitalreservefonds |
| 3 | Defensive Vermögensverwalter |
| 4 | Ausgewogene Vermögensverwalter |
| 5 | Dynamische Vermögensverwalter |
| 6 | Märkte |
| 7 | Spezialitäten / Themen |

### Mein Portfolio (rechte Spalte)

| Symbol | Funktion |
|---|---|
| 💾 **Diskette** | Erstellt und öffnet das Portfolio als PDF in einem neuen Tab (dort speicherbar) |
| ⬇ **Pfeil unten** | Exportiert das Portfolio als JSON-Datei zur späteren Wiederherstellung |
| ⬆ **Pfeil oben** | Lädt eine gespeicherte JSON-Datei und stellt das Portfolio wieder her |
| ↺ **Reset** | Setzt das gesamte Portfolio zurück |

---

## 🌍 „Länder aktualisieren" – Was steckt dahinter?

Der Button **„🌍 Länder aktualisieren"** ist nur für den **Administrator** zugänglich.

### Was macht er?
Er startet einen automatischen Datenabrufs-Prozess, der für jeden Fonds im System die aktuellen **Ländergewichtungen** (also: wie viel Prozent des Fonds sind in welchem Land investiert) aus den Factsheets der jeweiligen Fondsgesellschaften abruft und in das System einspielt.

Diese Daten sind die Grundlage für die **Länderverteilung nach Region** – ein zentrales Analyse-Feature des Tools.

### Voraussetzungen
- Lokaler Crawler-Server läuft: `python3 crawler_server.py`
- Google Gemini API-Key ist konfiguriert (in `update_country_data.py`)
- Dauer: ca. 3–5 Minuten für alle Fonds

> **Für Benutzer:** Die Ländergewichtungen sind bereits vorausgefüllt und werden regelmäßig vom Administrator aktualisiert. Sie müssen diesen Button nicht betätigen.

---

## 💾 Portfolio speichern & wiederherstellen

### Speichern
1. Klicken Sie auf das **⬇-Symbol** (Pfeil nach unten) in „Mein Portfolio"
2. Eine JSON-Datei wird erstellt (z. B. `portfolio_setup_05-04-2026.json`)
3. Speichern Sie diese Datei an einem sicheren Ort

### Wiederherstellen
1. Öffnen Sie das Tool im Browser
2. Klicken Sie auf das **⬆-Symbol** (Pfeil nach oben)
3. Wählen Sie Ihre gespeicherte JSON-Datei aus
4. Das Portfolio wird vollständig wiederhergestellt

---

## 🖨️ PDF exportieren

1. Wählen Sie Fonds aus und geben Sie Beträge ein
2. Klicken Sie auf das **💾-Diskettensymbol** oben in „Mein Portfolio"
3. Ein neuer Browser-Tab öffnet sich mit dem fertigen PDF
4. Klicken Sie auf **„⬇ PDF speichern"** oder drücken Sie **Cmd+S**

> **Hinweis:** Falls Chrome einen Popup-Blocker anzeigt, erlauben Sie Popups einmalig für diese Seite.

---

## 🗂️ Dateien im Ordner

| Datei | Zweck |
|---|---|
| `index.html` | Einstiegspunkt – im Browser öffnen |
| `app_v4.3.3.7.js` | Gesamte Anwendungslogik (inkl. Aktien/Anleihen-Aufschlüsselung) |
| `styles_v4.3.3.7.css` | Styling und Layout |
| `fund_data.js` | Alle Fondsdaten inkl. Ländergewichtungen |
| `crawler_server.py` | Lokaler Server für Länder-Update (Administrator) |
| `update_country_data.py` | Skript zur manuellen Aktualisierung der Ländergewichtungen |

---

## ⚙️ Technische Hinweise

- Das Tool läuft vollständig **lokal im Browser** (keine Serververbindung nötig für normale Nutzung)
- Das Portfolio wird automatisch im **Browser-LocalStorage** gespeichert (Schlüssel: `portfolioV4337_setup`)
- Bei Änderungen an der Software: **Cmd+Shift+R** (Hard-Reload) im Browser ausführen
- Empfohlene Browser: **Google Chrome** oder **Safari** (aktuellste Version)
- Getestet auf: macOS

---

## 📝 Versionshistorie

| Version | Wichtigste Änderungen |
|---|---|
| **4.3.3.7** | Aktien/Anleihen-Aufschlüsselung in der Länderverteilung (Cluster-Ebene + Fonds-Tooltip); gemeinsame `classifyFund()`-Logik; Fondsklassen-Badge im Länder-Tooltip |
| 4.3.3.6 | Neue 6-Regionen-Länderverteilung (Nordamerika · Europa · Schwellenländer · Pacific · Sonstige ETF · Sonstige); 100%-Normalisierung der Regionanteile; Schicht-Reihenfolge an Turm angeglichen |
| 4.3.3.5 | Crawler-Button für automatische Ländergewichtungs-Extraktion; Info-Bar mit Schicht- und Länderverteilung nebeneinander |
| 4.3.3.4 | Robuste Ländergewichtungs-Berechnung; `fund_data.js` ausgelagert |
| 4.3.3.3 | EB Aktien-Fondsliste vervollständigt |
| 4.3.3.2 | JSON-Import/Export für Portfolio-Sicherung |
| 4.3.3.1 | Sparrate pro Fonds; Layout-Verbesserungen |
| 4.3.3 | Ländergewichtungs-Tooltips im Fonds-Modal |

---

*Version 4.3.3.7 – Zuletzt aktualisiert: April 2026*
