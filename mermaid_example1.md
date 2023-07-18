# ①VSCodeでmermaidを利用する方法や便利な拡張機能
## mermaidの使い方
1. `を３つ、そしてその横にmermaidを書く。

2. その中に、書きたい図のコードを入れる。

3. 最後に、`を３つ書いて閉じる。

**例**
~~~
``` mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
~~~
を書くと、↓こんな感じで図が表示される。

**フローチャート**
``` mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

## 便利な拡張機能
1. Markdown All in One

    *Markdownが使えるようになる*
2. Markdown Preview Mermaid Support

    *プレビューを表示して、リアルタイムで変化を確認しながら、作業できる*
3. Mermaid Markdown Syntax Highlighting

    *マーメイド記法で書いたところをハイライト表示してくれる*
4. Markdown PDF

    *Markdownファイルを様々なファイルに変化してくれる。*
    - HTML
    - PNG
    - JPEG
    - PDF

参考にさせていただいた記事
(https://qiita.com/sato_kana/items/2a13f19017576488f017)