# konpeto
金平糖の角の数の減少メカニズムシミュレーションプログラム

# 金平糖について
- 金平糖の角の本数は、初期状態を90本程度として時間に従い減じていき、最終的に20~24本程度に至ることが知られています。
 このシミュレーションプログラムは、金平糖の角の本数がどういった過程を経て減じていくのか？を明らかにするためのプログラムです。
 
# 減少メカニズム仮説
- 金平糖表面に存在する無数の角において、隣り合う角同士が結合することで角の総数が減少していること
- 結合は最も近い角同士の間で行われ、結合後は2つの角の中点から真上の位置に角が発生する
という条件のもとシミュレーションをおこなっています。

使用パラメーター
- 金平糖初期状態：核投入後から2時間の状態
- 初期本数:98
- 粒径の半径:0.4916cm
- 結合間隔:0.2204cm
粒径と結合間隔は金平糖の成長を考慮して時間変化（シミュレーション内では結合回数に依存）するものとしている

# 金平糖の研究で本シミュレーションを改善する方に向けて
1. githubのアカウント作成がまだの方はまずアカウント作成してみましょう！
2. このリポジトリをフォークもしくはクローンする。このプログラムファイルを自分のパソコンやgithubのリモートリポジトリにコピーする的な意味合いです！
(フォークしてもらうと僕に通知がくるので、研究が引き継がれたことがわかり嬉しいです。。。)
フォークとは？https://qiita.com/matsubox/items/09904e4c51e6bc267990
3. フォークした場合。後継者さんのリモートリポジトリに僕が作ったプログラムがコピーされたかと思います！このプログラムを用いて自分のパソコンで開発するためにはクローンという操作を行います。
クローンとは、リモートリポジトリをローカルな環境（後継者さんのPC）にコピーすることです。
4. 本シミュレーションの改善をお願いします！充実した研究ライフにしてね＾＾

pythonの環境構築の仕方も載せて置きます。
こちらの記事を参考にやってみてください。
https://qiita.com/oyan29/items/832f0616589c9f0fcf9d
