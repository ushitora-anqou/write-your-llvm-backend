# 手を動かせばできるLLVMバックエンド チュートリアル（WIP）

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/80x15.png" /></a>
[![Build Status](https://travis-ci.org/ushitora-anqou/write-your-llvm-backend.svg?branch=master)](https://travis-ci.org/ushitora-anqou/write-your-llvm-backend)

自作ISAのためのLLVMバックエンドをイテレーティブに作ります。鋭意執筆中。

[ここからmasterが読めます。](https://ushitora-anqou.github.io/write-your-llvm-backend/)

## ビルド方法

Asciidoctorのmasterを持ってきて`asciidoctor main.asciidoc`とかする。

文章を書くときに、ファイルを更新するたびにコンパイルしたい場合は
付属の`Gemfile`と`Guardfile`を使って`bundle exec guard`とかする。
要`bundle install`。Epiphany（GNU Web）を入れて生成されたHTMLを見ると、
更新時にリロードしてくれるので便利。詳細は[公式ドキュメント](https://asciidoctor.org/docs/editing-asciidoc-with-live-preview/)を参照。

## Author

[艮 鮟鱇（うしとら あんこう／Ushitora Anqou）](https://anqou.net/)

## LICENSE

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
