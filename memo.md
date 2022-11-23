# メモ

**▶︎ DOM**
DOMとはDocument Object Modelの略で、HTMLやXML文書を操作するためのAPI（インターフェイス）。
仮想DOMと区別するためにリアルDOMと呼ぶことも。
DOMのモデルは文書をツリー構造で表現する。
このDOMツリーのhtml,bodyといった一つ一つの要素をオブジェクトとして扱い、これらをNode（ノード）と呼ぶ。

**▶︎ 仮装DOM**
リアルDOMを模したJavaScriptのオブジェクト。

仮想DOMをJavascriptで操作
変更前後の仮想DOMの差分を比較
差分だけをリアルDOMに反映

変更があった部分のみレンダリングすることで、ブラウザのレンダリングのコストを軽減できる
またUI/ロジックを分離できる
https://qiita.com/takumi__pro/items/df890ea02250dd29cbc4

**▶︎ vue開発用のChrome拡張機能**
Vue.js devtools

