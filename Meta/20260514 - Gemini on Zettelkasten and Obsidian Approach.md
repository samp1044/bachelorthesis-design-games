```
help me build my knowledge base and organize my research for my bachelors thesis. I am using Zotero to collect papers and roughly categorize them as well as read them, overleaf using latex for writing the paper and obsidian for taking notes. what would be the best approach after collecting the papers in zotero that might seem interesting (I do it based on title). Currently I start reading a paper and then summarize it in my words in a markdown file in obsidian. those notes are unorganized tho and I feel like lossing the essence or important details later. For example I am trying to extract the categorizations for design games from a few papers and then compare then. How would I best approach that? And is a system like zettelkasten an approach that might help me or is that overkill?
```

Ein strukturierter Workflow verhindert, dass Kerninformationen verloren gehen. Hier ist ein optimierter Ansatz für Ihre Bachelorarbeit mit Zotero, Obsidian und Overleaf. [1]

## 🛑 Der Zotero-zu-Obsidian Übergang

Lesen Sie nicht ziellos. Nutzen Sie Zotero für die erste Strukturierung vor dem Export. [2, 3]

- Zotero-Integration nutzen: Installieren Sie das Obsidian-Plugin BibNotes Formatter oder Zotero Integration.
- Metadaten automatisieren: Importieren Sie Zitate, Autoren, PDFs und Ihre farbigen PDF-Markierungen automatisch als Markdown-Kopfzeile.
- Farbcodierung beim Lesen: Verfeinern Sie Ihr Markierungssystem in Zotero.
    
    - Gelb: Kernthesen und Definitionen.
    - Blau: Methodik und Design-Game-Kategorisierungen.
    - Grün: Spannende Ergebnisse oder Zitate.
    - Rot: Widersprüche oder Schwachstellen. [4, 5, 6, 7, 8]
    

## 🗺️ Der „Literature Note“ Standard (Obsidian)

Vermeiden Sie Fließtext-Zusammenfassungen. Nutzen Sie ein festes, scanbares Template für jede Quelle. [9]

Erstellen Sie für jedes Paper eine Notiz mit folgendem Aufbau:

- Kontext: Warum lese ich das? (Bezug zur Forschungsfrage).
- Kernkonzept: Das Paper in einem Satz.
- Kategorisierung von Design Games: (Hier gezielt die extrahierten Typen als Bulletpoints listen).
- Kritik: Limitierungen der Methodik.
- Verknüpfungen: Links zu ähnlichen Papern (`[[Anderes Paper 2024]]`).

## 📊 Extraktion & Vergleich (Ihr konkretes Beispiel)

Um Kategorisierungen von Design Games aus verschiedenen Papern zu vergleichen, nutzen Sie eine Matrix-Notiz in Obsidian.

1. Zentrale Synthese-Notiz anlegen: Erstellen Sie eine Notiz namens `[[Design Games Kategorisierung Vergleich]]`.
2. Obsidian Dataview nutzen: Installieren Sie das Plugin _Dataview_.
3. Metadaten nutzen: Fügen Sie in Ihren Literatur-Notizen Inline-Felder hinzu, z. B.: `Kategorisierung:: [Rollenbasiert, Regelbasiert]`.
4. Tabelle generieren: Lassen Sie Dataview automatisch eine Vergleichstabelle aller Paper und deren Kategorisierungen erstellen. [10]

Alternativ funktioniert eine manuelle Markdown-Tabelle:

|Paper|Fokus der Kategorisierung|Dimensionen / Typen|Besondere Merkmale|
|---|---|---|---|
|`[[Müller 2022]]`|Akteure|Spieler, Facilitator|Fokus auf Machtdynamiken|
|`[[Schmidt 2024]]`|Materialität|Digital, Physisch|Fokus auf Werkzeuge|

## 🧠 Ist Zettelkasten Overkill?

Ja und Nein. Ein strikter Zettelkasten (jede Idee eine atomare Notiz) ist für eine Bachelorarbeit meist zu zeitaufwendig. Eine modifizierte Variante ist jedoch ideal:

- Nutzen Sie „MOCs“ (Maps of Content): Erstellen Sie Sammelnotizen für Ihre Kapitel (z. B. `[[MOC Methodik]]`, `[[MOC Design Games]]`). Diese verlinken auf die einzelnen Literatur-Notizen.
- Atomare Konzept-Notizen: Wenn drei Paper das Konzept "Serious Games" definieren, schreiben Sie _eine_ Notiz `[[Definition Serious Games]]`. Verlinken und vergleichen Sie dort die drei Paper.
- Vorteil für Overleaf: Diese Konzept-Notizen sind die perfekte Rohfassung für Ihre LaTeX-Absätze. [11, 12, 13, 14]

## ✍️ Der Weg nach Overleaf

- Zotero-Export: Nutzen Sie das Zotero-Plugin _Better BibTeX_. Exportieren Sie Ihre Bibliothek als `.bib`-Datei direkt in Ihren Overleaf-Ordner (über die automatische URL-Synchronisation in Overleaf Premium oder manuellen Upload).
- Schreib-Workflow: Öffnen Sie Obsidian auf der linken Bildschirmhälfte und Overleaf auf der rechten. Da Ihre Obsidian-Notizen bereits nach Konzepten und Kapiteln (MOCs) sortiert sind, müssen Sie die Absätze in LaTeX nur noch ausformulieren und mit `\cite{...}` die passenden Keys einfügen. [15, 16, 17]

Wenn Sie möchten, kann ich Ihnen ein konkretes Obsidian-Template für Ihre Literatur-Notizen erstellen oder den Dataview-Code für die Vergleichstabelle schreiben. Wie detailliert soll die technische Einrichtung sein?

  

[1] [https://www.reddit.com](https://www.reddit.com/r/Zettelkasten/comments/vnj3z6/zettelkasten_in_zotero/)

[2] [https://brainresearch.de](https://brainresearch.de/Project_Management/Tools/Zotero_or_Mendeley_for_Referencing.html)

[3] [https://forums.zotero.org](https://forums.zotero.org/discussion/115001/zotero-needs-an-outliner-and-or-project-view)

[4] [https://forum.obsidian.md](https://forum.obsidian.md/t/bibnotes-formatter-new-plugin-to-export-and-format-annotations-from-zotero-into-obsidian/29920?page=6)

[5] [https://forum.obsidian.md](https://forum.obsidian.md/t/bibnotes-formatter-new-plugin-to-export-and-format-annotations-from-zotero-into-obsidian/29920)

[6] [https://thesiswhisperer.com](https://thesiswhisperer.com/2024/04/07/using-obsidian-as-your-writing-work-bench/)

[7] [https://www.lucasmercier.me](https://www.lucasmercier.me/blog/research_workflow)

[8] [https://www.hkmu.edu.hk](https://www.hkmu.edu.hk/oetools/zotero/)

[9] [https://zotlit.aidenlx.top](https://zotlit.aidenlx.top/getting-started/basic-usage/template-basics)

[10] [https://medium.com](https://medium.com/@lennart.dde/obsidian-plugins-that-quietly-transformed-my-phd-workflow-3d1478446360)

[11] [https://medium.com](https://medium.com/obsidian-observer/your-new-obsidian-superpower-how-to-use-folder-notes-eb1dddc88d61)

[12] [https://medium.com](https://medium.com/@theo-james/unable-to-take-book-notes-properly-read-this-guide-959b5431dd5b)

[13] [https://vhbelvadi.com](https://vhbelvadi.com/zettelkasten)

[14] [https://www.linkedin.com](https://www.linkedin.com/pulse/top-10-tools-every-researcher-should-know-2024-fanny-akhile-f46df)

[15] [https://gouldguides.carleton.edu](https://gouldguides.carleton.edu/zotero/advanced)

[16] [https://www.atlasworkspace.ai](https://www.atlasworkspace.ai/blog/academic-research-software)

[17] [https://beingpax.medium.com](https://beingpax.medium.com/zettelkasten-method-with-obsidian-how-to-take-smart-notes-with-examples-cdaf348febbd)

----

```
Ich möchte Design Games auch in Design Thinking einordnen. Dazu muss ich auch zu Design Thinking recherchieren. Zum Beispiel welche Methodiken gibt es da, was ist der State-of-the Art, welche Design Games werden in welchen Methoden/Steps eingesetzt und wo gibt es Potential dass diese eingesetzt werden. Wo gibt es noch Lücken? Welche Herausfoderungen/Shortcomings gibt es? Abschließend sollen auch Beispiele für den Einsatz von Design Games außerhalb der IT gebracht werden. Welchen Weg und welche Obsidian Struktur empfiehlst du mir hier?
```

Für diese tiefe thematische Verknüpfung reicht eine lose Sammlung von Zusammenfassungen nicht mehr aus. Sie benötigen eine Struktur, die das Sammeln von Fakten vom Generieren von eigenen Erkenntnissen trennt.

## 🏛️ Die Obsidian-Ordnerstruktur (Nach dem MOC-Prinzip)

Nutzen Sie ein flaches System mit Fokus auf _Maps of Content_ (MOCs). Das verhindert, dass Notizen in Unterordnern „vergraben“ werden.

```text
📁 00_Meta/            -> Templates, Zotero-Exporte (BibNotes)
📁 10_Literature/      -> Reine Literatur-Notizen (1 File pro Paper/Buch)
📁 20_Concepts/        -> Atomare Fachbegriffe & Frameworks (z.B. Double Diamond)
📁 30_Synthesis/       -> Ihre Verknüpfungen, Tabellen und Argumentationsketten
📁 40_Drafts/          -> Text-Entwürfe, sortiert nach Kapiteln für Overleaf
```

## 🗺️ Die 3 zentralen Synthese-Notizen (MOCs)

Erstellen Sie im Ordner `30_Synthesis/` drei Hauptnotizen. Diese dienen als dynamische Dashboards und Inhaltsverzeichnisse.

## 1. `[[MOC Design Thinking State-of-the-Art]]`

Hier listen Sie strukturiert die Phasen auf und verlinken die konkreten Methoden.

- Phasen & Modelle: Link zu `[[Framework Double Diamond]]`, `[[Stanford d.school Modell]]`.
- Methodiken: `[[Methode Persona-Entwicklung]]`, `[[Methode Brainstorming]]`.
- Shortcomings/Kritik: `[[Design Thinking Herausforderungen]]` (z. B. "Fehlende Struktur in Phase X", "Innovations-Theater").

## 2. `[[Matrix Design Games in Design Thinking]]`

Das Herzstück Ihrer Forschungsfrage. Nutzen Sie hier eine strukturierte Markdown-Tabelle zur Verortung:

|DT-Phase (z.B. d.school)|Eingesetzte Design Games|Potenzielle Games / Lücken|Belegte Quelle / Argumentation|
|---|---|---|---|
|Empathize|`[[Game Empathy Map Pro]]`|–|`[[Müller 2022]]`|
|Define|_Lücke vorhanden_|`[[Game Problem Framing Rollenspiel]]`|Potenzial: Reduziert Bias (`[[Schmidt 2024]]`)|
|Ideate|`[[Game Brainwriting Poker]]`|–|`[[Meier 2021]]`|
|Prototype|–|_Lücke: Zu wenig haptische Games_|Eigene These für die Thesis|

## 3. `[[Design Games außerhalb der IT]]`

Sammelnotiz für Ihre Fallbeispiele. Nutzen Sie Zwischenüberschriften für Branchen:

- `### Stadtplanung & Urban Design` -> Link zu `[[Paper UrbanGame 2023]]` (Einsatz von Legosteinen zur Bürgerbeteiligung).
- `### Organisationsentwicklung / HR` -> Link zu `[[Buch Serious Play im HR]]`.
- `### Gesundheitswesen` -> Pflegeschulungen mittels Rollenspielen.

---

## 🔄 Der operative Arbeitsweg (Schritt-für-Schritt)

## Schritt 1: Gezieltes Einlesen & Tagging (Zotero ➔ Literature)

Wenn Sie ein Paper lesen, extrahieren Sie die Infos direkt mit standardisierten Tags oder Inline-Feldern in Ihrer Obsidian-Literaturnotiz:

- `Thema:: #design-thinking/shortcoming`
- `Kontext:: #non-it-application`
- `Phase:: #dt/ideate`

## Schritt 2: Atomisierung (Literature ➔ Concepts)

Sobald Sie in einem Paper eine spannende Definition oder Herausforderung finden, kopieren Sie diese _nicht_ nur in die Literatur-Notiz. Erstellen Sie eine Konzept-Notiz (z. B. `[[Herausforderung: Ideen-Konvergenz im DT]]`).

- Inhalt dieser Notiz: Ein eigener zusammenfassender Satz, gefolgt von den Verweisen: „_Müller (2021) sieht hier ein Problem durch Gruppenzwang. Schmidt (2024) schlägt Design Games als Lösung vor._“

## Schritt 3: Aggregation (Concepts ➔ Synthesis)

Öffnen Sie Ihre `[[Matrix Design Games in Design Thinking]]`. Fügen Sie die neu gewonnenen Erkenntnisse und Links in die Tabelle ein. Die Lücken (Forschungslücken) ergeben sich nun visuell von selbst: Überall, wo in der Spalte „Eingesetzte Games“ gähnende Leere herrscht, liegt Ihr wissenschaftlicher Mehrwert.

## Schritt 4: Vorbereitung für Overleaf (Synthesis ➔ Drafts)

Wenn Sie das Kapitel „Herausforderungen im Design Thinking“ schreiben:

1. Öffnen Sie eine leere Datei in `40_Drafts/Kapitel_3_Background.md`.
2. Öffnen Sie die Notiz `[[Design Thinking Herausforderungen]]` als Split-Screen daneben.
3. Strukturieren Sie die Absätze vor. Da Sie die Quellen (`[[Müller 2021]]`) bereits an den Argumenten kleben haben, schreiben Sie im Fließtext direkt: `Laut \cite{mueller2021} ist...`.

---

Möchten Sie ein vollständiges Markdown-Template für die `10_Literature/` Notizen, das bereits Felder für DT-Phasen und Shortcomings enthält, oder soll ich Ihnen zeigen, wie Sie die Dataview-Abfrage für die automatische Lücken-Erkennung einrichten?

----

```
macht das tooling zotero, obsidian sinn oder sollte ich überhaupt einen anderen zugang für meine recherche wählen?
```

Ja, diese Kombination ist absolut sinnvoll und gehört aktuell zum State-of-the-Art für wissenschaftliches Arbeiten. Zotero und Obsidian ergänzen sich perfekt, weil sie zwei völlig unterschiedliche Aufgaben trennen: Zotero managt die Daten (Zitate, PDFs, Metadaten), Obsidian managt die Gedanken (Verknüpfungen, Synthese, Argumentation).

Es gibt jedoch spezifische Vor- und Nachteile sowie eine Alternative, die Sie abwägen sollten.

## Warum das Tooling Sinn macht (Die Stärken)

- Zotero ist unschlagbar bei Metadaten: Kein anderes Tool extrahiert bibliografische Daten aus dem Browser so fehlerfrei. Das spart extrem viel Zeit für Ihr LaTeX-`literatur.bib`.
- Obsidian verhindert das „Read-and-Forget“-Syndrom: Herkömmliche Tools (wie Word oder Excel-Tabellen) lagern Notizen linear. In Obsidian sehen Sie über die Verlinkungen (`[[Notiz]]`) sofort, wenn Paper A und Paper B dieselbe Design-Thinking-Lücke kritisieren.
- Zukunftssicherheit & Textbasis: Beide Tools arbeiten lokal und plattformunabhängig. Markdown-Dateien (.md) in Obsidian sind reiner Text. Sie können sie in 10 Jahren noch öffnen, und sie lassen sich perfekt via Copy-Paste in Overleaf/LaTeX einfügen.

## Die größte Gefahr bei diesem Setup

- Das „Prokrastinations-Sumpf“-Risiko: Da Obsidian extrem anpassbar ist, neigen Studierende dazu, tagelang Plugins zu konfigurieren, Themes zu wechseln und das „perfekte System“ zu bauen, statt zu lesen und zu schreiben.
- Regel: Halten Sie das Setup so simpel wie möglich. Jedes Plugin, das Sie installieren, muss Ihnen sofort Zeit sparen.

---

## Die einzige echte Alternative: Citavi (Nur für Windows)

Falls Sie merken, dass Ihnen das manuelle Verknüpfen in Obsidian zu viel Aufwand ist, sollten Sie einen Blick auf Citavi werfen.

- Wie es funktioniert: Citavi vereint Zotero und Obsidian in _einem_ Programm. Sie importieren das Paper, lesen das PDF im Tool, markieren Textstellen und weisen diesen direkt „Wissenselemente“ (Zitate, Kommentare) zu. Diese Wissenselemente können Sie dann in einer hierarchischen Gliederung (Ihrer Bachelorarbeit) per Drag-and-Drop anordnen.
- Nachteil: Citavi exportiert zwar zu BibTeX für Overleaf, die native Integration ist aber spürbar für Microsoft Word optimiert. Zudem ist es proprietäre Software und läuft MacOS-Nutzern oft nur über die Cloud-Version (die weniger mächtig ist).

---

## Fazit & Empfehlung

Bleiben Sie bei Zotero + Obsidian + Overleaf, wenn Sie:

1. Gerne visuell und konzeptionell arbeiten (Wissensnetzwerke aufbauen).
2. Einen Mac nutzen oder Linux/Windows plattformübergreifend arbeiten.
3. Die volle Kontrolle über Ihre Rohdaten (.md und .bib) behalten wollen.

Der minimale Workflow, damit es nicht in Arbeit ausartet:  
Sammeln in Zotero ➔ Einmal pro Woche per Plugin in Obsidian exportieren ➔ In Obsidian nur die Vergleichstabellen und Kernargumente schreiben ➔ Direkt in Overleaf ausformulieren.

Möchten Sie, dass ich Ihnen die konkreten Einrichtungsschritte für das _Zotero Integration_ Plugin in Obsidian zeige, damit der Datenfluss zwischen den beiden Tools mit einem Klick funktioniert?