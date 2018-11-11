# del-bs

Delete backspace charactors.

## Usage

```sh
npx @mstssk/del-bs <file>
```

## Why

Japanese Input method(also CJK?) often outputs broken text that includes unnecessary backspace char.

https://github.com/electron/electron/issues/9173

Above issue was fixed. However it reproducts sometimes with other environment.
<!--
Note:
たぶん漢字変換の候補表示中にバックスペースで戻ったりいろいろしていると再現する。
VSCodeでプレーンテキスト編集モードでは再現しないけど、Markdownモードでは再現したりする。
他のプラグインとの兼ね合いなので、誰が悪いのかわかってない。
-->
