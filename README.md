# LeadOS Arbeitsstand

Öffentlich erreichbare Status- und Arbeitsstand-Seite des Pilotprojekts **„Digitales Führungswerkzeug für die Aufgabenübergabe zwischen Inhaber und Mitarbeiter“** des Hanseatischen Instituts LeadOS. Die Seite wird über GitHub Pages ausgeliefert und besteht aus einer einzigen Datei, `index.html`.

**Live-Seite:** <https://leados-org.github.io/leados-arbeitsstand/>

## Aufbau der Seite

Die Seite zeigt in dieser Reihenfolge: **Wo wir stehen** (Etappen von den Grundlagen bis zur Pilotentscheidung), **Was jetzt gebraucht wird** (offene Fragen an das Team), **Nächste Schritte**, **Offene Punkte**, **Verlauf** (Entwicklungsverlauf und Entscheidungen) sowie die Bereiche **Aktuelle Berichte** und **Alle Berichte & Dokumente**.

## Berichte

Die Berichte werden nicht in dieser Seite gepflegt. Die Seite liest sie zur Laufzeit per `fetch()` aus dem öffentlichen Repository [`LeadOS-Org/leados-reports`](https://github.com/LeadOS-Org/leados-reports) (Index `index.json` und einzelne JSON-Berichte).

## Änderungen

- Änderungen erfolgen direkt in `index.html`. Es gibt keinen Build-Schritt; lokal genügt es, die Datei im Browser zu öffnen.
- Schriften werden von Google Fonts geladen.
- Nach dem Commit und Push auf `main` aktualisiert GitHub Pages die Seite.
- Commits bitte **signiert**.

## Verwandte Projekte

- Prototyp: <https://leados-design-foundation.lovable.app>
- Produktcode des Prototyps (privat): [`LeadOS-Org/leados-design-foundation`](https://github.com/LeadOS-Org/leados-design-foundation)
- Berichte: [`LeadOS-Org/leados-reports`](https://github.com/LeadOS-Org/leados-reports)
