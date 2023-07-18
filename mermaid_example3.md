# ③mermaidで記述できるダイアグラムのチュートリアル
## マーメイドを使ったクラス図の書き方
1. 拡張機能のところから、Markdown All in Oneをインストールします。
2. 拡張機能のところから、Markdown Preview Mermaid Supportをインストールします。

   **（上記二つは検索欄に入力すれば出てくるはずです）**

3. Class diagram.mdというファイルを作ります。（名前は●●●●●.mdというような感じであれば大丈夫です）
4. 以下のコードをファイルの中に書きます。
~~~
``` mermaid
classDiagram
Class01 <|-- AveryLongClass : Cool
Class03 *-- Class04
Class05 o-- Class06
Class07 .. Class08
Class09 --> C2 : Where am i?
Class09 --* C3
Class09 --|> Class07
Class07 : equals()
Class07 : Object[] elementData
Class01 : size()
Class01 : int chimp
Class01 : int gorilla
Class08 <--> C2: Cool label
```
~~~
5. Ctrl+Kを押した後に、vを押してプレビュー画面を表示し、このような図が表示されていれば、成功です。
``` mermaid
classDiagram
Class01 <|-- AveryLongClass : Cool
Class03 *-- Class04
Class05 o-- Class06
Class07 .. Class08
Class09 --> C2 : Where am i?
Class09 --* C3
Class09 --|> Class07
Class07 : equals()
Class07 : Object[] elementData
Class01 : size()
Class01 : int chimp
Class01 : int gorilla
Class08 <--> C2: Cool label
```
参考にさせていただいた記事
(https://mermaid.js.org/intro/)