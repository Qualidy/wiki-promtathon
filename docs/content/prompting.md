# Prompting – kurz & knackig

Ein guter Prompt liefert **konkrete Anweisungen** und macht der KI **Kontext, Ziel, Umfang und Stil** klar.  

**Goldene Regel:** *Je konkreter, desto besser.*

---

## Die 4 Bausteine eines starken Prompts

!!! note "Merksatz"
    **Klarer Prompt = Kontext + Klarheit + Umfang + Stil**

### 1) Kontext
- Wer/was/worum geht’s? (Rolle, Zielgruppe, Hintergrund, Domäne)
- *Beispiel:* „Mein Freund **Paul** wird **40**, wir kennen uns seit dem **Kindergarten**, wir gehen **regelmäßig Fußball** spielen.“

### 2) Klarheit
- Eindeutige Aufgabe formulieren, Begriffe erklären, Fachlevel setzen.
- *Beispiel:* „**Schreibe** ein **Geburtstagsgedicht** für Paul mit den genannten Infos.“

### 3) Umfang
- Länge, Struktur, Format, Anzahl der Varianten festlegen.
- *Beispiel:* „**Drei Strophen**, **vier Verse** pro Strophe.“

### 4) Stil
- Tonalität, Stilvorlage, Zielgruppe.
- *Beispiel:* „**Im Stil eines Kinderbuchs**.“

!!! example "Von vage → gut (Progression)"
    **Vage:**  
    „Schreib mir ein Gedicht zum Geburtstag.“ (zu unspezifisch)

    **Besser (Kontext):**  
    „Paul wird 40, wir kennen uns seit dem Kindergarten, wir spielen Fußball.“ 

    **Noch besser (Klarheit & Umfang):**  
    „Schreibe ein Gedicht mit drei Strophen und vier Versen …“

    **Sehr gut (Stil):**  
    „… im Stil eines Kinderbuchs.“


## Praktische Prompting-Tipps

### A) Wiederholung/Varianten
- **Mehrere Antworten generieren**, beste auswählen (Stochastik!).  
  *„Gib mir **5 Varianten**, nummeriert, jeweils max. 80 Wörter.“*

### B) Rollenzuweisung
- KI eine **Rolle geben** (z. B. „Du bist **Fertigungsplaner** …“).  
  *Wirkt wie ein „Briefing“ und erhöht die Passgenauigkeit.* 

### C) Neues Thema → neue Unterhaltung
- Chat-Verlauf beeinflusst Antworten → **Themenwechsel = neuer Chat**.

!!! tip "Template: Rollenprompt"
    **Rolle:** Du bist _[Rolle/Zielgruppe]_ in _[Branche/Abteilung]_.  
    **Aufgabe:** _[konkrete Aufgabe]_  
    **Kontext:** _[Wer/Was/Wozu]_  
    **Umfang:** _[Länge/Struktur/Anzahl]_  
    **Stil:** _[Ton/Format/Leserlevel]_  
    **Ausgabe:** _[Formatvorgabe: Bullet-Points, Tabelle, JSON, …]_  
    **Qualität:** Prüfe _[Kriterien]_ und biete **2 Alternativen**.

## Sofort einsetzbare Prompt-Bausteine (Automotive)

!!! example "Standard-Analyse (Daten/Prozess)"
    **Rolle:** Du bist Lean-Experte in der Automobilfertigung.  
    **Aufgabe:** Analysiere die folgenden Qualitätsdaten und nenne **Top-3 Auffälligkeiten**.  
    **Kontext:** Wir untersuchen Fehlercodes der KW 37–39 für Werk A–C.  
    **Umfang:** Max. 120 Wörter + **Tabelle (Code, Trend, Hypothese)**.  
    **Stil:** Klar, präzise, ohne Jargon.  
    **Ausgabe:** Erst Bullet-Summary, dann Tabelle.

!!! example "Schreibstil anpassen (Dokumentation)"
    **Rolle:** Du bist Technischer Redakteur.  
    **Aufgabe:** Formuliere den Text **leicht verständlich für Auszubildende** um.  
    **Kontext:** Sicherheitsanweisung für die Schweißlinie.  
    **Umfang:** 1 Absatz, max. 80 Wörter.  
    **Stil:** Aktiv, klare Verben, kurze Sätze.  
    **Ausgabe:** Nur den überarbeiteten Text liefern.

!!! example "Varianten generieren (Kommunikation)"
    **Rolle:** Du bist Servicekommunikator.  
    **Aufgabe:** Erzeuge **5 Antwortvarianten** auf eine Lieferverzögerung (freundlich/sachlich/technisch/kurz/formell).  
    **Kontext:** Ersatzteil verspätet, neue Lieferung in 5 Tagen.  
    **Umfang:** Je Variante max. 60 Wörter.  
    **Ausgabe:** Nummerierte Liste.

## Qualität sichern (Self-Check)

- **Zielerfüllung:** Trifft die Antwort genau die gestellte Aufgabe?  
- **Faktencheck:** Stimmen Daten/Termini – oder braucht es Quellen?  
- **Form/Format:** Entspricht die Ausgabe dem gewünschten **Format** (Länge, Struktur, Tabellen/JSON)?  
- **Iterieren:** *„Überarbeite Variante 2. Straffe Einleitung, füge 1 KPI hinzu.“*

## Recht & Nutzung – Reminder für Copilot
- **Nur dienstlich**, Anmeldung mit Geschäftskonto (Schutzschild beachten).  
- **Keine** urheberrechtlich geschützten Inhalte oder personenbezogenen Daten eingeben.  
- **Ausgaben prüfen**, insbesondere auf Schutzrechtsverletzungen.  
- **Softwarecode** darf intern generiert werden (Freigabe beachten).
