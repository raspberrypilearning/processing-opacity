Puoi rendere colori parzialmente trasparenti aggiungendo un quarto numero a un colore RGB per dare l' "opacità".

Questo codice disegna i riflessi di luce sul frutto Kawaii dell'esempio:

--- code ---
---
language: python
filename: main.py - draw()
---

  # Riflessi di luce
  fill(255, 255, 255, 70) # 70 indica il valore di trasparenza/opacità
  ellipse(170, 150, 35, 35)
  ellipse(150, 160, 25, 25)
  
--- /code ---

![immagine di frutta kawaii con riflessi di luce a diverse opacità: 30, 70, 150, 255. 30 è più opaco e 255 è meno opaco](images/opacity.png)

