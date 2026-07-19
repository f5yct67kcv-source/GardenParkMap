---
name: interview-first
description: >-
  Gnadenloses, strukturiertes Anforderungs-Interview VOR jeder Umsetzung.
  Nutze diesen Skill immer, wenn der Nutzer ein Vorhaben, Feature, Video,
  Dokument oder eine sonstige Aufgabe starten will und erst ein gemeinsames
  Verständnis erreicht werden soll — besonders bei „interviewe mich", „frag
  mich alles", „lass uns das durchsprechen", „erst planen, dann bauen", oder
  wenn offene Entscheidungen (z. B. eine „Noch zu entscheiden"-Tabelle in
  einem Briefing) vorliegen. Auch anwenden, wenn der Nutzer verlangt, dass
  vor dem Coding/Generieren alles abgesprochen ist. Standardsprache Deutsch,
  sofern der Nutzer nicht anders schreibt.
---

# Interview-First: Erst Klarheit, dann Umsetzung

Ziel: Bevor irgendetwas gebaut, generiert oder geschrieben wird, ein
vollständiges gemeinsames Verständnis des Vorhabens erreichen — durch ein
strukturiertes Interview, das jede Entscheidung dem Nutzer überlässt.

## Grundregeln (nicht verhandelbar)

1. **Kein Umsetzungsschritt vor dem Go.** Keine Zeile Code, kein Generieren,
   kein Erstellen von Deliverables, bevor der Nutzer ausdrücklich bestätigt
   hat, dass das gemeinsame Verständnis erreicht ist. Repo-/Setup-Aufgaben,
   die der Nutzer explizit *vorab* verlangt (z. B. „leg das zuerst als Skill
   an"), sind erlaubt — das eigentliche Vorhaben nicht.

2. **Eine Frage nach der anderen.** Immer nur *eine* Entscheidungsfrage
   stellen und auf die Antwort warten. Mehrere Fragen auf einmal verwirren
   und werden vermieden. (Technisch: pro Runde genau eine Frage.)

3. **Zu jeder Frage eine Empfehlung.** Jede Frage kommt mit deiner klar
   gekennzeichneten Empfehlung samt kurzer Begründung. Der Nutzer soll nur
   noch bestätigen oder abweichen müssen — nicht bei null anfangen.

4. **Fakten selbst erkunden, Entscheidungen dem Nutzer überlassen.** Alles,
   was sich aus Dateien, Tools, Repo-Inhalten, Konnektoren oder dem Web
   herausfinden lässt, schlägst du selbst nach — dafür wird nicht gefragt.
   Gefragt wird nur nach echten *Entscheidungen*, die dem Nutzer gehören
   (Ziel, Zielgruppe, Stil, Umfang, Trade-offs, Prioritäten).

5. **Abhängigkeiten sauber auflösen.** Den Entscheidungsbaum Zweig für Zweig
   durchgehen. Frühe Antworten bestimmen spätere Fragen — frage zuerst das,
   was den größten Einfluss auf den Rest hat, und passe die Folgefragen an
   die bisherigen Antworten an.

## Ablauf

### 0. Umgebung erkunden (still, vor der ersten Frage)
Lies relevante Dateien (Briefings, READMEs, vorhandene Assets), prüfe
verfügbare Tools/Konnektoren und offene Punkte (z. B. eine „Noch zu
entscheiden"-Tabelle). Sammle so viel Kontext, dass deine Fragen fundiert
sind und keine Frage etwas erfragt, das du selbst hättest nachschlagen können.

### 1. Entscheidungsbaum skizzieren (kurz)
Nenne dem Nutzer knapp, welche Entscheidungen anstehen und in welcher
Reihenfolge du sie durchgehen willst (die Reihenfolge nach Abhängigkeit,
nicht nach Bequemlichkeit). Das gibt Orientierung, ist aber noch keine
Frage-Flut — es ist die Landkarte.

### 2. Interview, Frage für Frage
Für jede Entscheidung genau eine Runde:

- **Frage:** präzise, auf eine Entscheidung fokussiert.
- **Empfehlung:** „*Meine Empfehlung: …*" mit 1–2 Sätzen Begründung.
- **Optionen:** wenn sinnvoll, 2–4 klare Alternativen mit Konsequenz.
- Dann **stoppen und auf die Antwort warten.**

Nutze für echte Entscheidungsfragen bevorzugt das `AskUserQuestion`-Tool
(Empfehlung als erste Option, mit „(Empfohlen)" markiert). Für offene
Fragen, die keine feste Auswahl haben, reicht normaler Text — aber trotzdem
nur *eine* Frage pro Runde.

Nach jeder Antwort: kurz spiegeln, was du verstanden hast, prüfen ob sich
dadurch Folgefragen ändern, dann zur nächsten offenen Entscheidung.

### 3. Trade-offs sichtbar machen
Wenn eine Entscheidung eine andere teuer oder unmöglich macht, sag es sofort,
statt es später auffliegen zu lassen. Widersprüche in den Antworten des
Nutzers freundlich benennen und auflösen lassen.

### 4. Verständnis zusammenfassen und Go einholen
Wenn alle Zweige geklärt sind: eine kompakte Zusammenfassung aller getroffenen
Entscheidungen vorlegen (idealerweise als Tabelle) und explizit fragen:
„Haben wir ein gemeinsames Verständnis erreicht? Soll ich starten?"
Erst nach ausdrücklichem Ja mit der Umsetzung beginnen.

### 5. Entscheidungen festhalten
Halte die finalen Entscheidungen dort fest, wo sie hingehören (z. B. das
Briefing im Repo aktualisieren), damit sie dokumentiert und wiederverwendbar
sind — nicht nur im Chatverlauf.

## Haltung

„Gnadenlos" heißt gründlich, nicht mühsam: Jede Frage soll dem Nutzer Arbeit
abnehmen (durch eine gute Empfehlung), nicht aufbürden. Bohre bei Vagem nach,
aber verschwende keine Runde an etwas, das du selbst herausfinden kannst.
Das Ziel ist ein Vorhaben, das beim ersten Anlauf richtig gebaut wird, weil
vorher wirklich alles abgesprochen war.
