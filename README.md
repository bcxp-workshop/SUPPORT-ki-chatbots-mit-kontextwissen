# KI-Chatbots mit Kontextwissen als First-Level Support 

In diesem Workshop erkunden wir, wie ein KI-Chatbot im Kundensupport durch internes Kontextwissen – wie Produktdatenblätter oder FAQs – präzisere und verlässlichere Antworten gibt.

Im Rahmen dessen testen wir direkt am Beispiel der fiktiven Firma NeuroHome, wie sich die Antwortqualität des Chatbots verändert, sobald diesem Kontextinformationen bereitgestellt werden. Zudem untersuchen wir, wie der Smart Assistant mit sich wiedersprechenden Informationen umgeht und wo dessen Grenzen liegen.

Unser Workshop-LibreChat fungiert hierbei als Chat-Umgebung für das Prompting mit dem vorbereiteten Smart Assistant und ist hier zu finden: https://workshop.bcxp.de

---

### Lernziele

- Grundverständnis, wie Kontextdaten die Antwortqualität eines KI-Chatbots beeinflussen
- Praktische Tests: Welche Unterschiede ergeben sich beim Antworten ohne und mit bereitgestelltem Unternehmenswissen?
- Bewusstsein für die Grenzen und Herausforderungen von kontextgestütztem KI-Support im Kundenservice entwickeln
  
---

# Aufgabenstellung

## 1. Fragen ohne Kontextdaten stellen

Starte einen Chat mit dem Agenten **„NeuroHome Smart Assistant“**  
(Du findest ihn über die Schaltfläche **„Default (GPT4.1)“** im Kontextmenü unter **„My Agents“**).  
Stelle verschiedene Fragen zu den Produkten von NeuroHome.  
In der Datei `Beispielfragen.txt` findest du vorbereitete Fragen aus drei Kategorien:

- **Explizit:** z.B. „Was kostet das ThermoSense X4?“  
- **Implizit:** z.B. „Kann ich das Thermostat auch am Wochenende anders einstellen?“  
- **Komplex:** z.B. „Wie kann ich einen Wochenplan am ThermoSense X4 erstellen und gleichzeitig Geld sparen?“

Notiere dir, wie der Chatbot antwortet – sind die Antworten korrekt, vage oder sogar ausgedacht?

---

## 2. Fragen mit Kontextdaten wiederholen

Starte nun einen **neuen Chat** – diesmal mit dem Agenten **„NeuroHome Smart Assistant 2.0“**.

Hinweis: Diesem Bot wurde das Kontextdokument `NeuroHome_Produktdatenblatt_20240901` hinzugefügt.  
Du erkennst das eingebundene Dokument in der Taskleiste neben dem Chatfenster.

Stelle jetzt die **gleichen Fragen erneut**.  
Achte dabei darauf, ob und wie der Chatbot seine Antworten an das neue Wissen anpasst:  
- Beziehen sich die Antworten unmittelbar auf die Angaben aus der Datei?  
- Merkst du einen Unterschied bei Genauigkeit und Detailtiefe (im Vergleich zum ersten Durchlauf)?  

Die Antworten sollten nicht mehr halluziniert, sondern belegt sein.

---

## 3. Kontext mit mehreren Versionen testen

Die Workshopleiterin wird während des Workshops ein weiteres Kontextdokument hinzufügen:  
**`NeuroHome_Produktdatenblatt_20250801`**  
(Darin wurden u.a. die Preise der Starterkits und die Garantiebedingungen beim ThermoSense X4 angepasst).

Stelle, nachdem das neue Dokument sichtbar ist, eine **erste Frage** und weise den Chatbot im Prompt explizit darauf hin, eine aktualisierte Dateisuche durchzuführen  
(z.B.: *„Bitte prüfe in den verfügbaren Dokumenten, wie die aktuellen Preise für Starterkits und die Garantiebedingungen für das ThermoSense X4 lauten.“*).

Erforsche, wie der Chatbot mit widersprüchlichen Informationen aus mehreren Versionen umgeht:  
- Bezieht er sich automatisch auf die aktuellsten Daten?  
- Weist er auf Versionsunterschiede oder eventuelle Unklarheiten hin?

Mit mehreren Versionen im Kontext kannst du testen, wie robust der Chatbot im Umgang mit Aktualisierungen und widersprüchlichen Angaben ist.

---

## 4. Bonus: Grenzen des Smart Assistants ausloten

Teste, wie weit du den „NeuroHome Smart Assistant“ fordern kannst. Besonders spannend sind folgende Themen:

- **Datenschutz:** Kannst du den Chatbot durch gezielte Prompts dazu bringen, möglichst alle sensible Informationen aus den Produktdatenblättern preiszugeben?
- **Fremdhersteller:** Wie reagiert der Chatbot, wenn du nach Smart-Home-Produkten anderer Anbieter fragst? Gibt er Empfehlungen ab, warnt er davor oder bleibt er neutral?
- **Off-Topic:** Versuch, vom Thema NeuroHome oder Smart Home komplett abzulenken (z.B. Wetter, Sport, Kochtipps). Wie reagiert der Chatbot darauf?

---

**Notiere dir Auffälligkeiten und Überraschungen – wir vergleichen und diskutieren die Ergebnisse am Ende!**

---
