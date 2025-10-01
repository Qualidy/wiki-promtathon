# Prompting – kurz & knackig

Ein guter Prompt liefert **konkrete Anweisungen** und macht der KI **Kontext, Ziel, Umfang und Stil** klar.  

**Goldene Regel:** *Je konkreter, desto besser.*

---

## Die 4 Bausteine eines starken Prompts

!!! note "Merksatz"
    **Klarer Prompt = Kontext + Klarheit + Umfang + Stil**

    **Kontext**

    - Wer/was/worum geht’s? (Rolle, Zielgruppe, Hintergrund, Domäne)
    - *Beispiel:* „Mein Freund **Paul** wird **40**, wir kennen uns seit dem **Kindergarten**, wir gehen **regelmäßig Fußball** spielen.“

    **Klarheit**

    - Eindeutige Aufgabe formulieren, Begriffe erklären, Fachlevel setzen.
    - *Beispiel:* „**Schreibe** ein **Geburtstagsgedicht** für Paul mit den genannten Infos.“

    **Umfang**

    - Länge, Struktur, Format, Anzahl der Varianten festlegen.
    - *Beispiel:* „**Drei Strophen**, **vier Verse** pro Strophe.“

    **Stil**

    - Tonalität, Stilvorlage, Zielgruppe.
    - *Beispiel:* „**Im Stil eines Kinderbuchs**.“


## Praktische Prompting-Tipps

<div class="grid cards" markdown>

* 🧠 **Zum Denken auffordern**

    ---

    Mit der Promptergänzung **"Denke besonders lange darüber nach"** kann das *Reasoning*-Model
    angestoßen werden.
    
    Es liefert allgemein bessere Ergebnisse, brauch aber mehr Zeit.
    
    Man erkennt, dass es angestoßen wurde daran, dass die Antwort nicht sofort erscheint, 
    sondern erst nach einigen Sekunden/Minuten.

* **💫 Wiederholung/Varianten**

    ---

    **Mehrere Antworten generieren**, beste auswählen.  
    * *"Gib mir **5 Varianten**!"*
    * *"Geht das auch kürzer?"*

* **🕵️‍♀️ Rollenzuweisung**

    ---

    KI eine **Rolle geben**

    * "Du bist **Fertigungsplaner**..."
    * "Du bist ein **Schulkind in der 4. Klasse..."

* **💬 Neues Thema → neue Unterhaltung**

    ---

    Chat-Verlauf beeinflusst Antworten
    
    → **Themenwechsel = neuer Chat**.

* **📚 Kontext durch Dokumente schaffen**

    ---

    * Lade Dokumente hoch, die die KI verwenden soll.
    * Gebe so Beispiele, wie die erwartete Lösung aussieht.
    * Wird der selbe Kontext mehrfach genutzt, kann es sich lohnen einen **Agenten** dazu zu erstellen.

* **🙌 Große Aufgabe in kleine Aufgaben teilen**

    ---

    * KI hat nur eine begrenzte Rechenkraft pro Prompt
    * Verschiedene **Aufgaben in mehrere Prompts aufteilen** (die sinnvolle Aufteilung kann mit der KI besprochen werden)
    * Wenn die selbe Aufgabe mehrfach ausgeführt werden soll, diese aber sehr umfangreich ist,
    lohnt es sich der KI jede Aufgabe einzeln zu geben.
    * Verlange nicht zu viel (verschiedenes) auf ein Mal von deiner KI.

</div>

!!! tip "Template: Rollenprompt"
    **Rolle:** Du bist _[Rolle/Zielgruppe]_ in _[Branche/Abteilung]_.  
    **Aufgabe:** _[konkrete Aufgabe]_  
    **Kontext:** _[Wer/Was/Wozu]_  
    **Umfang:** _[Länge/Struktur/Anzahl]_  
    **Stil:** _[Ton/Format/Leserlevel]_  
    **Ausgabe:** _[Formatvorgabe: Bullet-Points, Tabelle, JSON, …]_  
    **Qualität:** Prüfe _[Kriterien]_ und biete **2 Alternativen**.

    Sofort einsetzbare Prompt-Bausteine:

    ??? example "Standard-Analyse (Daten/Prozess)"
        **Rolle:** Du bist Lean-Experte in der Automobilfertigung.  
        **Aufgabe:** Analysiere die folgenden Qualitätsdaten und nenne **Top-3 Auffälligkeiten**.  
        **Kontext:** Wir untersuchen Fehlercodes der KW 37–39 für Werk A–C.  
        **Umfang:** Max. 120 Wörter + **Tabelle (Code, Trend, Hypothese)**.  
        **Stil:** Klar, präzise, ohne Jargon.  
        **Ausgabe:** Erst Bullet-Summary, dann Tabelle.

    ??? example "Schreibstil anpassen (Dokumentation)"
        **Rolle:** Du bist Technischer Redakteur.  
        **Aufgabe:** Formuliere den Text **leicht verständlich für Auszubildende** um.  
        **Kontext:** Sicherheitsanweisung für die Schweißlinie.  
        **Umfang:** 1 Absatz, max. 80 Wörter.  
        **Stil:** Aktiv, klare Verben, kurze Sätze.  
        **Ausgabe:** Nur den überarbeiteten Text liefern.

    ??? example "Varianten generieren (Kommunikation)"
        **Rolle:** Du bist Servicekommunikator.  
        **Aufgabe:** Erzeuge **5 Antwortvarianten** auf eine Lieferverzögerung (freundlich/sachlich/technisch/kurz/formell).  
        **Kontext:** Ersatzteil verspätet, neue Lieferung in 5 Tagen.  
        **Umfang:** Je Variante max. 60 Wörter.  
        **Ausgabe:** Nummerierte Liste.

## Qualität sichern (Self-Check)

- **Faktencheck:** Stimmen Daten/Termini – oder braucht es Quellen? Quellen angeben lassen! PRÜFEN, PRÜFEN, PRÜFEN!
- **Kürzen:** Häufig füllt die KI den Text mit Phrasen oder gibt Inhalte mehrfach wieder. Kürzen (lassen)!
- **Iterieren:** *„Mach die Einleitung straffer, füge 1 KPI hinzu.“*

## Recht & Nutzung – Reminder für Copilot
- **Nur dienstlich**, Anmeldung mit Geschäftskonto (Schutzschild beachten).  
- **Keine** urheberrechtlich geschützten Inhalte oder personenbezogenen Daten eingeben.  
- **Ausgaben prüfen**, insbesondere auf Schutzrechtsverletzungen.  
- **Softwarecode** darf intern generiert werden (Freigabe beachten).
