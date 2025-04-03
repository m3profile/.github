name: 🐞 Bug Report
description: Melde einen Fehler, der behoben werden soll.
title: "[BUG] "
labels: [bug]
assignees: []

body:
  - type: textarea
    id: description
    attributes:
      label: Beschreibung
      description: Was ist das Problem? Wann tritt es auf?
      placeholder: Ein kurzer Überblick über das Problem.
    validations:
      required: true

  - type: textarea
    id: steps
    attributes:
      label: Schritte zur Reproduktion
      description: Welche Schritte führen zuverlässig zum Fehler?
      placeholder: |
        1. ...
        2. ...
        3. Fehler tritt auf
    validations:
      required: true

  - type: textarea
    id: expected
    attributes:
      label: Erwartetes Verhalten
      placeholder: Was sollte stattdessen passieren?
    validations:
      required: true

  - type: input
    id: environment
    attributes:
      label: Umgebung
      description: Systeminfos wie Browser, Node-Version, OS etc.
      placeholder: z. B. Firefox 124 / Node 20 / Debian Bookworm
