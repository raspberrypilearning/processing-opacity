يمكنك إنشاء ألوان شفافة جزئيًا عن طريق إضافة رقم رابع إلى لون RGB لإعطاء "عتامة".

يرسم هذا الرمز النقاط البارزة المتداخلة في مثال فاكهة الكيوي:

--- code ---
---
language: python
filename: main.py - draw()
---

  # Highlights fill(255, 255, 255, 70) # 70 is transparency/opacity here ellipse(170, 150, 35, 35) ellipse(150, 160, 25, 25)

--- /code ---

![صورة فاكهة الكيوي مع الإبرازات بدرجات تعتيم مختلفة: 30 ، 70 ، 150 ، 255. 30 is less opaque and 255 is fully opaque](images/opacity.png)

