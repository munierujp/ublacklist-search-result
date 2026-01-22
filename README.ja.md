[English](README.md) | **日本語**

# ublacklist-search-result

🚫 検索結果からSNSやショッピングサイトなどの検索結果ページを除外するための、uBlacklistのブラックリスト

## 使い方


1. [uBlacklist](https://ublacklist.github.io/)をインストール
3. [ブラックリストを購読](https://iorate.github.io/ublacklist/subscribe?name=ublacklist-search-result&url=https%3A%2F%2Fraw.githubusercontent.com%2Fmunierujp%2Fublacklist-search-result%2Fmaster%2Fblacklist.txt)するか、uBlacklistに以下のURLを手動で登録：
    ```
    https://raw.githubusercontent.com/munierujp/ublacklist-search-result/master/blacklist.txt
    ```

## なぜ？

- その情報について知りたいから検索しているのに、別のサイトの検索結果ページに飛ばされるのは二度手間
- そのサイトの検索結果が見たければ、最初からそのサイトで検索すればいい

## 方針

- URL内に検索ワードやタグのようなものが含まれ、それらの値によって検索結果ページが動的に生成されるようなサイトを対象とする
  - `https://example.com/search/?q=<検索ワード>`
  - `https://example.com/tag/<タグ>`

## 関連リポジトリ

- [munierujp/ublacklist-qa](https://github.com/munierujp/ublacklist-qa)
