Puedes hacer colores parcialmente transparentes agregando un cuarto número a un color RGB para dar la 'opacidad'.

Este programa dibuja los reflejos superpuestos en el ejemplo de la fruta Kawaii:

--- code ---
---
language: python
filename: main.py - draw()
---

  # Reflejos
  fill(255, 255, 255, 70) # La transparencia/opacidad aquí es 70
  ellipse(170, 150, 35, 35)
  ellipse(150, 160, 25, 25)
  
--- /code ---

![imagen de fruta kawaii con reflejos en diferentes opacidades: 30, 70, 150, 255. 30 es más opaco y 255 es menos opaco](images/opacity.png)

