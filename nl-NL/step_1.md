Je kan kleuren gedeeltelijk transparant maken door een vierde getal toe te voegen aan een RGB kleur om de doorzichtigheid aan te geven.

Deze code tekent de overlappende highlights in het Kawaii fruit voorbeeld:

--- code ---
---
language: python
filename: main.py - draw()
---

  # Highlights
  fill(255, 255, 255, 70) # 70 is hier de transparantie/doorzichtigheid
  ellipse(170, 150, 35, 35)
  ellipse(150, 160, 25, 25)

--- /code ---

![kawaii fruit afbeelding met highlights bij verschillende dekkingen: 30, 70, 150, 255. 30 is meer dekkend en 255 is minder dekkend](images/opacity.png)

