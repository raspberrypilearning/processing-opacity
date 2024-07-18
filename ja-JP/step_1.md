RGBの色指定に続けて4番目に「不透明度」を指定する数値を付け加えると、部分的に透明な色を作成できます。

このコードは、カワイイフルーツにハイライト当てたような図形を描画します。

--- code ---
---
language: python
filename: main.py - draw()
---

  # Highlights fill(255, 255, 255, 70) # 70 is transparency/opacity here ellipse(170, 150, 35, 35) ellipse(150, 160, 25, 25)

--- /code ---

![さまざまな不透明度（30、70、150、255）でハイライトされたカワイイフルーツ画像。 30 is less opaque and 255 is fully opaque](images/opacity.png)

