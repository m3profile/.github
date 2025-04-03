name: ✨ Feature Request
description: Schlage eine neue Funktion vor.
title: "[Feature] "
labels: [enhancement]
assignees: []

body:
  - type: textarea
    id: motivation
    attributes:
      label: Motivation
      description: Warum ist dieses Feature hilfreich oder notwendig?
      placeholder: Eine kurze Erklärung des Nutzens.
    validations:
      required: true

  - type: textarea
    id: description
    attributes:
      label: Feature-Beschreibung
      description: Was genau soll umgesetzt werden?
      placeholder: Klar beschreiben, was das Feature tun soll.
    validations:
      required: true

  - type: checkboxes
    id: scope
    attributes:
      label: Gehört zum Umfang
      options:
        - label: UI-Änderung nötig
        - label: API-Änderung nötig
        - label: Datenbankänderung nötig
        - label: Nur Frontend
        - label: Nur Backend

  - type: textarea
    id: done
    attributes:
      label: Definition of Done
      description: Wann gilt die Aufgabe als erledigt?
      placeholder: z. B. Feature ist in Produktion verfügbar, Tests vorhanden etc.
