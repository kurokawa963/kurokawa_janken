
# JS　じゃんけん課題　再魔改造（したい）


## DEMO

  - https://kurokawa963.github.io/kurokawa_janken/

## 紹介と使い方

  - すごろくのように見える結果が最初にわかってるすごろくです。２Pゲーム。

  - ①スタートボタンを押す（前置きが長いので、二回クリックするとゲーム画面に遷移します。）
  - ②「めいちゃんさいころ」と「トトロさいころ」を交互に押していきます。
  - ③最初に20マス目にきた人の勝ち

  - ぴったりにならなくてもゴールします。

  - 再魔改造を試み、配列をつかってクリックによる乱数発生を考えていますが、解決にいたっておりません。土曜まで魔改造がんばります。


## 工夫した点

  - めいちゃんとトトロは動いているように見えて実際は左端からvisibility:hidden;にした●の数によって押し出されています。
  - ●の数が20以下のとき、●の数がぴったり20のとき、●の数が20以上のときを条件分岐してゴールに至るまでの●が乱数で出た目の数を足した数分出現するようにしています。

## 苦戦した点

  - 結局解決に至りませんでしたが、クリックによって乱数を発動させ、その数を足していくことに時間を費やしました。
  - なぜか一回目のクリックと二回目のクリックで最初に出た乱数の数と二回目のクリックで出た乱数の数が一緒にならなかったので、行ったり来たりするすごろくになってしまいました。
  - なのでifの外に変数を持ってきて、乱数を固定させ、クリックでもとから決まってる乱数を出現させる方法にしました。
  - クリックで乱数を発生させようが、最初からどっちが先に合計が20になるかわかってて、クリックによって決まった乱数を出現させようが、表面上は同じなので努力はあきらめました。

## 参考にした web サイトなど

  - https://webcat.work/play-sound/
  - https://zenn.dev/fijii_rin/articles/06e54aa30a5a27
  
