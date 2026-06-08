---
# Seitentitel leer lassen, um den Site-Titel zu verwenden
title:
date: 2026-06-08
type: landing

sections:
  - block: hero
    content:
      title: |
        Wissenschaftliche Arbeiten
        Prof. Dr. Christian Pfitzner
      image:
        filename: welcome.jpg
      text: |
        <br>

        Willkommen auf der Seite der betreuten wissenschaftlichen Arbeiten
        von **Prof. Dr. Christian Pfitzner** an der **TH Nürnberg Georg Simon Ohm**,
        Fakultät Elektrotechnik, Feinwerktechnik und Informationstechnik (efi),
        sowie am **TTZ Nürnberger Land**.

        Hier finden Sie Projekt-, Bachelor- und Masterarbeiten aus den Bereichen
        Mobile Robotik, Autonome Systeme und Drohnentechnologie.

  - block: collection
    content:
      title: Aktuelle Abschlussarbeiten
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: publication
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./publication/" cta_text="Alle Arbeiten ansehen →" %}}
    design:
      columns: '1'
---
