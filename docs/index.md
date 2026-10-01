# Verzuimstandaard Werkgevers ↔ Arbodiensten

> **Officiële documentatie en specificaties voor de uitwisseling van verzuimgegevens tussen werkgevers en arbodiensten.**

---

## 1. Doel van dit Koppelvlak
Deze standaard richt zich op het optimaal en transparant inrichten van de processen tussen **werkgever** en **arbodienst**, binnen de kaders van de Wet verbetering poortwachter en de privacywetgeving (AVG).

### Belangrijkste uitgangspunten:
* **AVG-proof:** Beperkt de uitwisseling tot strikt noodzakelijke gegevens; geen medische diagnoses in het werkgeverskanaal.
* **Gebeurtenisgestuurd (Events):** Directe notificatie bij ziekmelding, herstel, spoor 2 en WIA-aanvraag.
* **Modulaire schema's:** Leunt op getoetste XML-berichten (XSD).

---

## 2. Standaardberichten in deze Repository
In de map [`schema/`](https://github.com/dma61/sim-verzuim-werkgevers-arbodiensten/tree/main/schema) vind je de actuele XSD-definities voor:

1. **WerkgeversGegevensBasisregistratie** — Stamgegevens van de werkgever.
2. **Dienstverbanden** — Arbeidsrelaties en contracturen.
3. **WerknemersGegevens** — Identificerende gegevens werknemer (conform AVG).
4. **Verzuimmeldingen** — Ziek-, herstel- en percentage-wijzigingen.
5. **Retourmelding** — Technische en functionele ontvangstbevestiging.
6. **Documenten & Afspraken** — Plan van Aanpak en probleemanalyse.

---

## 3. Releases en Versiebeheer
* **Huidige actieve release:** `Release juli 2026`
* **Releasecyclus:** Jaarlijks begin juli.
* **Codelijsten:** Gedeelde verzuimcontrolecodes worden centraal beheerd.

---

## 4. Vragen & Werkgroep (Community)
Voor vragen, suggesties of het melden van bevindingen specifiek voor dit koppelvlak:
* Bekijk of open een issue in de [GitHub Issue Tracker](https://github.com/dma61/sim-verzuim-werkgevers-arbodiensten/issues).
* Notificaties en discussies blijven strikt binnen deze werkgroep.
