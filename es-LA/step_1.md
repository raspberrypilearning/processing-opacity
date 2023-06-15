Puedes hacer colores parcialmente transparentes agregando un cuarto número a un color RGB para dar la 'opacidad'.

Este codigo dibuja los reflejos superpuestos en el ejemplo de la fruta Kawaii:

--- code ---
---
language: python
filename: main.py - draw()
---

  # Highlights fill(255, 255, 255, 70) # 70 is transparency/opacity here ellipse(170, 150, 35, 35) ellipse(150, 160, 25, 25)

--- /code ---

![imagen de fruta kawaii con reflejos en diferentes opacidades: 30, 70, 150, 255. 30 es más opaco y 255 es menos opaco](images/opacity.png)

