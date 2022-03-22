Tu peux créer des couleurs partiellement transparentes en ajoutant un quatrième nombre à une couleur RVB pour donner « l'opacité ».

Ce code dessine les reflets qui se chevauchent dans l'exemple de fruit Kawaii :

--- code ---
---
language: python
filename: main.py - draw()
---

  # Reflets
  fill(255, 255, 255, 70) # 70 est la transparence/opacité ici
  ellipse(170, 150, 35, 35)
  ellipse(150, 160, 25, 25)

--- /code ---

![image de fruits kawaii avec des reflets à différentes opacités : 30, 70, 150, 255. 30 est plus opaque et 255 est moins opaque](images/opacity.png)
