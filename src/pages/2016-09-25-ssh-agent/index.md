---
date: '2016-09-25T12:11:46+09:00'
path: '/entry/2016/09/25/ssh-agent/'
title: macOS キーチェインが動かなくなったので keychain を導入する
---
# macOS updateメモ

ssh passphraseを常に問い合わされるようになった。

## 調査

- keychain
- ssh-agent

## keychain入れてみる

- <https://github.com/9renpoto/dotfiles/pull/32>

解決出来た様子。

## Refs

- <http://qiita.com/u6k/items/5970618c4a8c23f71fb9>
- <http://qiita.com/tukiyo3/items/045f86c4242ec53953e2>