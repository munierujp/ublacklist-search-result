# ublacklist-search-result

SNSやショッピングサイトなどの検索結果ページを除外するための、uBlacklistのブラックリスト

## 使い方

[uBlacklist](https://iorate.github.io/ublacklist/)をインストールし、[ブラックリストを購読](
https://iorate.github.io/ublacklist/subscribe?name=ublacklist-search-result&url=https%3A%2F%2Fraw.githubusercontent.com%2Fmunierujp%2Fublacklist-search-result%2Fmaster%2Fblacklist.txt)してください。\
上記のリンクが機能しなければ、以下のURLを手動で登録してください。

```
https://raw.githubusercontent.com/munierujp/ublacklist-search-result/master/blacklist.txt
```

## なぜ？

- その情報について知りたいから検索しているのに、別のサイトの検索結果ページに飛ばされるようなたらい回し状態は望ましくない
- そのサイトの検索結果が見たければ、最初からそのサイトで検索すればいい

## 方針

- `https://example.com/search/?q=<検索ワード>`や`https://example.com/tag/<タグ>`のように、URL内に検索ワードのようなものが含まれ、検索結果ページが動的に生成されるようなサイトを対象とする
- 私が普段検索していて遭遇次第追加していく

## 例

![example.png](docs/example.png)
