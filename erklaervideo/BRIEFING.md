# Erklärvideo-Briefing — Garden Park Guest House & Interaktive Highland-Karte

> **Zweck dieser Datei:** Kontext- und Entscheidungs-Dokument für die Erstellung
> des Videos mit **Higgsfield (via Konnektor)**. Im Video-Chat anhängen bzw.
> Repo hinzufügen (`add repo f5yct67kcv-source/GardenParkMap`) — dann liegt
> alles unter `erklaervideo/` bereit.

---

## Projekt-Aufteilung

Das Vorhaben ist in **zwei getrennte Projekte** aufgeteilt:

- **Projekt 1 — Gäste-Video (AKTIV):** bringt den Gästen Zweck **und** Bedienung
  der Mappe näher. Dieses Briefing beschreibt Projekt 1.
- **Projekt 2 — B2B-Video (SPÄTER, geparkt):** vermarktet die Mappe als Produkt
  an weitere Guest Houses / Hotels / regionale Tourismusbüros. Wird später aus
  eigenem Konzept (ggf. aus demselben Material) erstellt.

---

## Auftrag an den Assistenten (Video-Chat)

- Erstelle mit mir zusammen **Projekt 1 — das Gäste-Video**.
- Nutze den **Higgsfield-Konnektor** (`generate_video`, `generate_image`,
  `generate_audio`, `dubbing`, `list_voices`). Prüfe zuerst mit
  `get_workflow_instructions` den passenden Workflow und mit `models_explore`
  das passende Modell (Image-to-Video mit Start-/Endframe, „Seedance 2.0"-Klasse).
- **Arbeite Shot für Shot** und **frag vor jeder Generierung nach** — die
  Detail-Entscheidungen je Shot werden im Chat einzeln abgestimmt
  (siehe Skill `interview-first`).
- Screenshots der Mappe (Start-/Endframes) werden aus der HTML im Repo gerendert.

---

## Fixierte Entscheidungen — Projekt 1 (Gäste-Video)

| # | Punkt | Entscheidung |
|---|---|---|
| 1 | **Ziel & Zielgruppe** | Zweck **und** Bedienung der Mappe vermitteln. Zielgruppe: **nicht-technische** Urlaubsgäste (die Zögerlichen). Ton: ruhig, einfach, ermutigend. |
| 2 | **Visueller Ansatz** | **Echte Screenshots als Start-/Endframes**, dazwischen Image-to-Video (Seedance-2.0-Klasse) cineastisch animiert → echte UI bleibt erhalten. Higgsfield für Highland-Atmosphäre / Intro / Outro. **Fallback:** echtes Screen-Recording. |
| 3 | **Format** | **9:16 als Master**, 16:9-Schnitt für YouTube-Einbettung. Platzierung: Website bei „Places to Visit" (YouTube-CTA) + zweiter **„Need help?"-QR** im Guesthouse (→ Handy). |
| 4 | **Länge** | **~60 Sekunden (±).** |
| 5 | **Dramaturgie** | **Hook („Warum jetzt", Urlaubs-Framing)** → goldener Pfad → CTA. |
| 6 | **Goldener Pfad** | 1) Öffnen · 2) Kategorie filtern/stöbern · 3) Ziel antippen · 4) **Plan My Day** (bis 3 Ziele → Fahrzeit → **In Google Maps öffnen** = Höhepunkt) · 5) kurzer Hinweis „6 Sprachen". **Weglassen:** Wetter, FAQ, Teilen/Drucken, Themen-Unterseiten. |
| 7 | **Voiceover** | **VO + kurze Text-Anker** für Aktionswörter (funktioniert auch stummgeschaltet). |
| 8 | **Sprache** | **Englisch = Master.** Deutsch als erste Dubbing-Fassung (Higgsfield-Dubbing); weitere Sprachen nach Bedarf. |
| 9 | **Perspektive & Stimme** | **Jetzt: neutraler, freundlicher Erzähler.** Später umstellbar auf Gastgeber-„wir" (Sarah & Daniel). Skript **host-swap-fähig** formulieren. **KI-Stimme** (kein Aufnahmegerät nötig), **hohe Audioqualität** ist Priorität. |
| 10 | **Musik** | Dezente, warme **Akustik** (schottisch angehaucht), durchgängig **unter** der Stimme gemischt — darf die Anleitung nie übertönen. |
| 11 | **Call-to-Action** | Warmer Handlungs-CTA („öffne die Mappe, plan deinen Tag") + Endtafel mit ❤️-Logo & Fundort/QR + kleiner Nachsatz „wir sind an der Rezeption für dich da". |

## Ablauf-Skizze (~60 Sek.) — Feinschliff je Shot im Chat

| Zeit | Bild | VO (EN, Entwurf) | Text-Anker |
|---|---|---|---|
| 0–10s | Highland-Stimmung, Gast mit Kaffee/Handy | *„You came to switch off — not to plan spreadsheets. Let us take care of the planning."* | — |
| 10–20s | Screenshot: Mappe öffnet sich, Pins erscheinen | *„This is your map — every great spot around Grantown, hand-picked."* | „Open the map" |
| 20–30s | Kategorie 🥃/🏰 antippen → gefilterte Pins | *„Tap what you love — whisky, castles, coast, family days."* | „Tap a category" |
| 30–38s | Ein Ziel antippen → Detailkarte | *„Tap any place to see what's there."* | „Tap a place" |
| 38–50s | Plan My Day: 3 Ziele → Fahrzeit → **Google Maps** | *„Add up to three, and open your whole route in Google Maps — done."* | „Plan My Day → Google Maps" |
| 50–56s | Sprach-Umschalter kurz | *„In your language, too."* | 6 Sprachen |
| 56–60s | Endtafel: ❤️ Garden Park Logo + Fundort/QR | *„Your Highlands are waiting. And we're right here at reception if you need us."* | „Open the map · Places to Visit" |

> Hinweis: VO-Zeilen sind Entwürfe. Perspektive heute neutral, so formuliert,
> dass sie sich später leicht in die Gastgeber-„wir"-Stimme umschreiben lassen.

---

## Über uns
- **Garden Park Guest House** & **Butterfly Cottage** in **Grantown-on-Spey**,
  im **Cairngorms National Park**, Schottische Highlands.
- **Gastgeber:** Sarah & Daniel (Daniel Muccio, `#ScotlandbyDan`).
- **Auszeichnungen:** Traveller Review Awards 2026 – 10/10; Green Tourism
  Gold Award.
- **Ausstattung/Qualität:** EV-Ladestation; hochwertiges Frühstück (100 % Saft,
  Eier aus Freilandhaltung, regionale Produkte); täglich vegan/vegetarisch.
- **USP:** zentrale Lage als Basis für **„sternförmige" Tagesausflüge** – viele
  Highlights in **20–50 Min.** erreichbar; ~40 Unterkünfte, Shops, Cafés und
  Restaurants im Dorf.
- **Web:** garden-park.co.uk · butterfly-cottage.co.uk
- **Fundort der Mappe:** Website → Menü **„Places to Visit"**.

## Die interaktive Karte (Was sie ist & vermittelt)
Ein kuratierter, interaktiver Highland-Guide + Tagesplaner mit der Botschaft
**„Grantown-on-Spey – Your Perfect Highland Base"**: Der Gast muss nichts selbst
recherchieren — die Gastgeber haben das Beste der Region handverlesen und das
Tagesplanen kinderleicht gemacht.

- **Filterbare Karte**, 50+ kuratierte Ziele nach Kategorie: 🥃 Whisky & Gin,
  🏰 Castles & History, 🔮 Mystic & Ancient, 🌊 Coast & Villages,
  👨‍👩‍👧 Family Fun, 🍽️ Restaurants & Bistros, ☕ Cafés & Takeaway,
  🛍️ Shops & Art.
- **Themen-Seiten:** ⚗️ Speyside Distilleries („whisky capital of the world"),
  🗺️ Day Trip Ideas, 🏘️ Discover Grantown, 🚗 The Way to Grantown.
- **„Plan My Day" (Star-Feature):** bis zu 3 Ziele wählen → Gesamt-Fahrzeit →
  **Open in Google Maps / Share / Print**. („Tap + on any destination to build
  your route", „Please verify times and add 20–30% buffer.")
- **Live-Wetter**, **FAQ**, **6 Sprachen** (EN/DE/FR/IT/ES/NL).
- Technisch: eigenständiges HTML, kein App-Download; Wetter live von
  open-meteo.com, Kartenmaterial OpenStreetMap/CARTO.

## Inhaltliche Highlights (für Story & Bildmaterial)
- **Whisky:** Speyside = Whisky-Welthauptstadt, 50+ Destillerien — Glenfiddich,
  Macallan, Aberlour, Cardhu/Johnnie Walker, Speyside Cooperage (Fassbau).
- **Schlösser & Geschichte:** Craigievar (rosa „Märchenschloss"), Cawdor,
  Ballindalloch, Balmoral, Dunrobin (Château-Stil am Meer), Culloden, Clava
  Cairns (4 000 Jahre alte Steinkreise).
- **Natur:** Loch Ness, Cairngorms, An Lochan Uaine (Green Loch), Anagach Woods
  (2 Min. vom Haus), Loch an Eilein.
- **Wildlife:** Delfine bei Chanonry Point, Kegelrobben bei Portgordon/Cullen,
  Fischadler Loch Garten, Rentiere in den Cairngorms.
- **Küste:** Bow Fiddle Rock, Cullen, Findhorn, Moray Firth; Küstenwanderung
  Portknockie–Cullen.
- **Piktische Steine:** Sueno's Stone, Maiden Stone.

## Marken-Look & Stimmung
- **Farben:** Gold `#c9a227`, dunkles Waldgrün als Hintergrund.
- **Schrift:** Playfair Display (elegant, serif).
- **Symbol:** Herz ❤️ fürs Gästehaus.
- **Tonalität:** hochwertig, warm, einladend — „Tor zu den Highlands".
- **Eigenes Material:** echte Fotos vorhanden (Highland-Cows, Schlösser, Küste,
  Delfine, Whisky) — auf Anfrage lieferbar.

---

## Offene Detail-Entscheidungen (Shot für Shot im Chat)
Die obigen Rahmen-Entscheidungen stehen. Pro Shot werden im Video-Chat noch
Bildidee, Kamera/Bewegung, exaktes VO-Wording, Text-Einblendung und Übergang
festgelegt — jeweils einzeln, mit Empfehlung (Skill `interview-first`).
Aktueller Stand: **Shot 1 (Hook, 0–10s)** wird als Nächstes im Detail behandelt.
