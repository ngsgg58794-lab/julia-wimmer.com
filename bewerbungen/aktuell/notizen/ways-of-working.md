# Arbeitsweise im Projekt

## Kommunikation

- Sehr knapp und direkt: kurze Kommandos, einzelne Screenshots, URLs ohne Kontext. Claude soll die nötige Aktion ableiten
- Wenig Erklärung, außer etwas ist wirklich erwähnenswert. Keine unnötigen Rückfragen
- Feedback ist direkt und konkret, iteriert schnell
- Kommunikation auf Deutsch, Bewerbungsunterlagen auf Englisch (oder Deutsch, wenn ausdrücklich verlangt)

## Tracker-Workflow

- Julia lädt den aktualisierten Tracker (HTML) manuell ins Projekt hoch
- HTML/JS-Datei mit Status: offen, bestätigte Absage, vermutete Absage, Gespräch (gelb), bearbeitet, ausgeschlossen (kein AT)
- AT-Badge über `at:true` pro Eintrag
- Bestätigte Bewerbungen („applied" / „done ✅") gelten als Tracker-Update

## Anschreiben und PDF-Erzeugung

- Anschreiben mit ReportLab (`reportlab.pdfgen.canvas`), A4
- Schrift: Poppins
- Design-System: dunkler Hintergrund `#15171c`, Mint-Akzent `#1fd8a4` / `#0dbe94`, dunkle Header-/Footer-Bänder
- wkhtmltopdf vermeiden (weiße Streifen bei verschachtelten Divs in A4)

## Recherche und Filter

- Nicht passende Rollen sofort melden (falsches Land, Teilzeit wenn nicht gewünscht, nur Hybrid, keine AT-Eligibility)
- Ashby-Boards (`jobs.ashbyhq.com/[company]`) sind am zuverlässigsten erreichbar. LinkedIn-Job-URLs liefern Login-Wall, daher Firmenname oder Stellenbeschreibung direkt erfragen
- Eligibility-Suche: Firmenname + „Austria" oder „remote countries hiring policy". Direkte Karriereseiten sind verlässlicher als Aggregatoren
