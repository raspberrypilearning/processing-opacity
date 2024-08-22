Du kannst teilweise transparente Farben erzeugen, indem du einer RGB-Farbe eine vierte Zahl hinzufügen, welche die „Deckkraft“ regelt.

Dieser Code zeichnet die überlappenden Highlights im Kawaii-Fruchtbeispiel:

--- code ---
---
language: python
filename: main.py - draw()
---

  # Highlights
  fill(255, 255, 255, 70) # 70 ist hier Transparenz/Deckkraft
  ellipse(170, 150, 35, 35)
  ellipse(150, 160, 25, 25)

--- /code ---

![Kawaii-Fruchtbild mit Highlights in unterschiedlicher Deckkraft: 30, 70, 150, 255. 30 hat eine geringere Deckkraft und 255 ist vollständig deckend](images/opacity.png)

