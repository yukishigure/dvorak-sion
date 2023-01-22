# SiON式Dvorak配列
SiON式Dvorak配列は、キー刻印はJIS配列のままでDvorak配列を使いやすくするため、以下の特徴を持たせてカスタマイズしたキー配列です。  

## 主な特徴
- 記号の配置は、なるべくJIS配列に準拠
- `L Shift`以外の修飾キー押下時は、QWERTYとして動作

# キー配列
## 直接入力, `L Shift`押下時  
<img src="docs/images/keyboard-dvorak.png">  
Dvorak配列として動作します。本家Dvorak配列と比較して、以下の違いがあります。  

- 1段目がJIS配列に完全準拠しています  
- `[`, `]`, `_`キーは、JIS配列通りに配置しています  
- 3段目の英字キーの右端に`;`を配置した都合上、`:`キーを上に逃がしています  
- 残った2つの`/`, `@`キーは、それぞれ2段目と4段目の左端に配置しています  

## `L Shift`以外の修飾キー押下時  
<img src="docs/images/keyboard-qwerty.png">  
JIS配列として動作します。`Ctrl`や`Alt`, `Win`キーなどは勿論、`R Shift`押下時もQWERTYとして動作します。  

# ソフトウェアを用いた配列変更
## Karabiner-Elements
Macでは、Karabiner-Elementsを使用して配列変更を行うことができます。  
Karabiner-Elementsインストール後、 以下のディレクトリに`dvorak-sion.json`を配置してください。  
 > `~/.config/karabiner/karabiner/assets/complex_modifications/dvorak-sion.json`  
その後、Karabiner-Elementsの`Complex Medifications`メニューから`Add rule`を選択し、`Dvorak SiON`をEnableすることで使用できます。
