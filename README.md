## lexpp resources

### このリポジトリについて

辞書を使った前処理ツール[lexpp](https://github.com/earlsuke/lexpp)用の追加リソースファイル置き場です．
標準辞書以外のリソースを使用することで語彙の追加を行うことが可能です．
各配布物は個別のライセンスに基づいて利用することができます．

### 使い方

``` pip install lexpp ```
``` python3 -m lexpp.dict_builder --input {file} --output {file} ```

* 日本語WordNet

単語と単語の間にある情報をまとめたデータベースをベースに作成した辞書です．
SynsetIDをGroupIDとみなし，子要素すべてを同義語として登録しています．各Groupの代表表記としては，独自の基準でタグを付与しています．語彙番号，略語，展開，表記ゆれに関しては代表表記以外のタグをアサインしていません．品質向上を目的としたバージョンアップによって，ファイル内容が変化する予定です．

この言語資源はこの[ライセンス](http://compling.hss.ntu.edu.sg/wnja/license.txt)に則って配布します．

### 参考文献

* [日本語ワードネット (1.1版)© 2009-2011 NICT, 2012-2015 Francis Bond and 2016-2017 Francis Bond, Takayuki Kuribayashi
]( http://compling.hss.ntu.edu.sg/wnja/index.ja.html)


### How to use

``` pip install lexpp ```
``` python3 -m lexpp.dict_builder --input {file} --output {file} ```

* Japanese WordNet
[Japanese Wordnet (v1.1) © 2009-2011 NICT, 2012-2015 Francis Bond and 2016-2017 Francis Bond, Takayuki Kuribayashi](http://compling.hss.ntu.edu.sg/wnja/index.en.html)
This resource is distributed under [this license](http://compling.hss.ntu.edu.sg/wnja/license.txt)
