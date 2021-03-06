# Introduction

GPS　Drawingを使ってサカナクションの「アルクアラウンド」の歌詞を表現する。きっかけは私がサカナクションの山口一郎さんとインスタライブコラボしたことである。サカナクションと日向野邦春という一生切っても切り離せない関係を表すためにこの課題に取り組んだ。

# Methods

地図上で歌詞にあった道を見つけてStravaを起動させて歩いていく。一文字ずつ切り離して表現していくためその都度新しいランニングやウォーキングを作成する。出来るだけ道の上で表現したいが、夜や新などの難しい漢字は公園などで歩いて表現していく。その後はStravaからGPXファイルを抽出してMapboxにアップロードする。そしてこの画面をスクリーンショットしてiMovieで音声を付けながら動画作成していく。とりあえず歩く道を決めるためにgeojson.ioでラインを作ってみる。それをGeojsonファイルで抽出してMapboxに表示させる。GPS Drawingを行う上で注意しなければいけないこととしては私有地に絶対に入らないという事とできる限り昼間に行うという事である。同じ道を何度も行き来することがあるため周りから不審者と思われてしまうことがある。それで警察沙汰になることを防ぐためにもできる限り昼に出歩く。
MapboxstudioにGPXファイルをアップロードした後にはレイヤーとして地図上に追加する。その際に、建物名などは邪魔になるのでラベルから削除しておく。

![ACA03143-610D-460F-B084-DFEAC115F858](https://user-images.githubusercontent.com/40018527/105621520-a04ea980-5e4b-11eb-8039-b01f7bee9665.png)

(3年生でのゴールは1番までのルート策定と動画作成）

# Results
結果として、Mapboxであれば正常にGPXファイルを読み込むことができた。さらに地図の文字や色など多くの部分がいじれる。私は地図上の文字表記が邪魔だったので削除した。歩いたデータの出来としては拡大率をそこまで大きくしなければ文字として認識できることが分かった。今回は今後歩く予定の部分をGeoJson.ioで表現したがGeoJsonがMapboxに対応しているため同じルートをたどることができる。問題点としては漢字の表現だけだと考える。やはり公園で表現するにもかなりの正確性が求められることが分かった。
![4F78A609-7935-484E-AF55-3C684D4D588B_1_201_a](https://user-images.githubusercontent.com/40018527/105623935-0db90500-5e61-11eb-9353-d1a0d3fc3af2.jpeg)
![BBE2808D-83E9-4783-B491-62DE741C7B40_4_5005_c](https://user-images.githubusercontent.com/40018527/105623954-4062fd80-5e61-11eb-9f4b-18f40d865938.jpeg)

# Disscusion
ただでさえ文字を表現するのは難しいのだが、漢字を表現するのはさらに難しくなってくる。しかし、Mapboxに表示させる場合はレイヤーごとに分けて表示できるため「へん」と「作り」で分けて歩いて表示できることに気がついた。今回は難しい漢字に関しては公園で歩くことを仮定してGeojson形式でマッピングした。この歩という時も実際に歩いて作成するとなるとかなり至難の技である。
そして、Mapbox上にアップロードする際はLineではなくCircleで表すことによって何故かサカナクション感が演出できるのではないだろうか。さらにポイントの色をサカナクションカラーである水色にすることによってよりサカナクション感が演出できると考えている。 

# Conclusion
このゼミ論は4年生に持ち越すことを最初から想定していたが、あまりにも行う作業が多いことを改めて痛感した。特に漢字の表現は道上で行おうとするとルート策定からかなりの時間がかかってしまう。今のところGPX形式で表現できているのは10文字程度であるが1番だけでも制覇できれば2番は一部を変えれば応用できる。これからの課題としてはこのプロジェクトをサカナクションファン全体で作り上げることができれば良いと考えている。現在は作成段階であるがこのゼミ論をまとめたスライドを公開して多くのサカナクションファンの方々にシェアしていただければと考えている。そうすることによって私だけでなく他の人々の知恵も加わりより良い作品が出来上がると思う。

# 先行研究
猪苗代湖ズ / I love you & I need you ふくしま [MORE ACTION, MORE HOPE]
https://youtu.be/sQEVUsHt1Bk

沖縄ファミリーマート 国道508号線「結」特別編　180秒CM
https://youtu.be/pUPWhE2Cm4s

THE BOOM 島唄　PV　20周年記念 ver
https://youtu.be/Oq9RkXOyFnY

Stand By Me | Playing For Change | Song Around The World
https://youtu.be/Us-TVg40ExM

Mela! - 全国のアカペラ2年生 & 緑黄色社会
https://youtu.be/bKkXOdZrXVY

# 参考文献リスト 
https://docs.google.com/spreadsheets/d/1g2eXWUpb1BTOZNJHFsx37w00CYwMpBDHIwD3CEFXTY8/edit?usp=sharing

# プレゼンスライド 
https://docs.google.com/presentation/d/1fWd7xpNzOz5NpWgCakVSRwyIfxHfZVovsEYrkeZeEV0/edit?usp=sharing

# プロジェクトリンク
https://github.com/furuhashilab/sotsuron2020/projects/14

