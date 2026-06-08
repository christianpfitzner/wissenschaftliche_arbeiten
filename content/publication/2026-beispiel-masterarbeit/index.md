---
title: 'Fiduzialmarker-basierte Lokalisierung von Drohnen in GPS-verweigerten Umgebungen'

# Autoren
# Verwende den Ordnernamen eines erstellten Profils (z. B. "admin"), um es mit dem Profil zu verknüpfen.
authors:
  - Vorname Nachname  # TODO: echten Studentennamen eintragen
  - admin

date: '2026-06-01T00:00:00Z'
doi: ''

# Veröffentlichungsdatum der Seite (nicht das Datum der Arbeit)
publishDate: '2026-06-08T00:00:00Z'

# Publikationstyp
# Verfügbare Typen: https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ['thesis']

# Publikationsname
publication: "Masterarbeit, TH Nürnberg Georg Simon Ohm"
publication_short: "Masterarbeit, TH Nürnberg"

abstract: |
  Diese Masterarbeit untersucht die fiduzialmarker-basierte Lokalisierung von Drohnen in Innenräumen,
  in denen kein GPS-Signal verfügbar ist. Auf Basis von ArUco-Markern und einer monokularen Kamera
  wird ein Verfahren zur echtzeitfähigen Positionsschätzung entwickelt, das ohne externe
  Infrastruktur auskommt.

  Die vorgestellte Methode kombiniert projektive Geometrie mit einem Extended-Kalman-Filter,
  um Rauschen in den Messungen zu kompensieren und eine stabile 6-DOF-Pose der Drohne zu schätzen.
  Experimentelle Evaluierungen auf einem realen Quadrotor-System zeigen eine Positioniergenauigkeit
  von unter 5 cm bei Fluggeschwindigkeiten bis 1,5 m/s.

# Kurzzusammenfassung
summary: |
  Echtzeitfähige Drohnen-Lokalisierung mittels ArUco-Fiduzialmarkern und Extended-Kalman-Filter
  ohne GPS-Infrastruktur — evaluiert auf einem realen Quadrotor-System.

tags:
  - Drohnen
  - Lokalisierung
  - Fiduzialmarker
  - ArUco
  - Kalman-Filter
  - Autonome Systeme

categories:
  - Masterarbeit

# Auf der Startseite als Featured anzeigen?
featured: true

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Vorschaubild
# Füge ein Bild namens `featured.jpg/png` in diesem Ordner hinzu.
image:
  caption: 'Drohne mit ArUco-Marker-Erkennung'
  focal_point: 'Smart'
  preview_only: false

# Zugehörige Projekte (optional)
projects: []

# Zugehörige Slides (optional)
slides: ''
---

**Kurzfassung:** Diese Masterarbeit entwickelt und evaluiert ein System zur präzisen Innen-Lokalisierung von Mikro-Drohnen ohne GPS auf Basis von ArUco-Fiduzialmarkern und einem Extended-Kalman-Filter.

## Aufgabenstellung

Drohnen, die in Innenräumen oder GPS-verweigerten Umgebungen (z. B. Tunneln, Lagerhallen) navigieren müssen, benötigen alternative Lokalisierungsverfahren. Diese Arbeit untersucht, inwieweit günstig zu druckende ArUco-Marker als Positionsreferenz ausreichen, um eine ausreichend genaue 6-DOF-Schätzung der Drohnenpose zu ermöglichen.

## Ergebnisse

- Positionsfehler < 5 cm bei niedrigen Fluggeschwindigkeiten
- Robuste Detektion bei wechselnden Lichtverhältnissen
- Echtzeitfähige Verarbeitung bei 30 Hz auf einem Raspberry Pi 4

## Betreuer

Prof. Dr. Christian Pfitzner, TH Nürnberg Georg Simon Ohm, Fakultät efi
