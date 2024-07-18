You can make partly transparent colours by adding a fourth number to an RGB colour to give the 'opacity'.

This code draws the overlapping highlights in the Kawaii fruit example:

--- code ---
---
language: python
filename: main.py - draw()
---

  # Highlights
  fill(255, 255, 255, 70) # 70 is transparency/opacity here
  ellipse(170, 150, 35, 35)
  ellipse(150, 160, 25, 25)
  
--- /code ---

![kawaii fruit image with highlights at different opacities: 30, 70, 150, 255. 30 is less opaque and 255 is fully opaque](images/opacity.png)

