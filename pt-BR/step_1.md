Você pode deixar cores parcialmente transparentes adicionando um quarto número a uma cor RGB para dar a "opacidade".

Este código desenha os realces sobrepostos com o exemplo da fruta Kawaii:

--- code ---
---
language: python
filename: main.py - draw()
---

  # Realces 
  fill(255, 255, 255, 70) # 70 é a transparência/opacidade aqui 
  ellipse(170, 150, 35, 35) 
  ellipse(150, 160, 25, 25)

--- /code ---

![imagem da fruta Kawaii com realce em diferentes opacidades: 30, 70, 150, 255. 30 é mais opaco e 255 é menos opaco](images/opacity.png)

