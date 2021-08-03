You can make partly transparent colours by adding a fourth number to an RGB colour to give the 'opacity'.

This code draws the overlapping highlights in the Kawaii fruit example:

--- code ---
---
language: python
filename: main.py - draw()
---

  # Highlights
  fill(255, 255, 255, 70) # white transparent
  ellipse(170, 150, 35, 35)
  ellipse(150, 160, 25, 25)
--- /code ---

![kawaii fruit image with highlights, more transparent](images/transparency_70.png)

If you change the `70` to `30`, the transparency will change:

---
language: python
filename: main.py - draw()
---

  # Highlights
  fill(255, 255, 255, 30) # less transparent
  ellipse(170, 150, 35, 35)
  ellipse(150, 160, 25, 25)
--- /code ---

![kawaii fruit image with highlights, less transparent](images/transparency_30.png)

--- /code ---
