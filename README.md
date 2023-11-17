# release-please-playground

- standard-version が deprecated になった
- release-please に乗り換えるたい
- リリースとパブリッシュが GitHub 上で完結することを目指す

## このリポジトリを参考にリリースとパブリッシュするときに気をつけること

### リポジトリを操作する権限を付ける

https://github.com/p-chan-sandbox/release-please-playground/issues/1

### 最初のバージョンを v0.x にしたい場合、Release-As というメッセージの空コミットする

https://github.com/p-chan-sandbox/release-please-playground/issues/3

ちなみに、v0.x から v1.x にメジャーバージョンアップしたいときも同じ

### npm のトークンを追加する

secret に追加しないと publish がうまくいかないはず
