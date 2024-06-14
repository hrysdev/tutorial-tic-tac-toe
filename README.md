# Tutorial: Tic-Tac-Toe

React + TypeScript + Vite による「[チュートリアル：三目並べ](https://ja.react.dev/learn/tutorial-tic-tac-toe)」の実装例 + α

## Requirement

- Node: v22.1.0

## Usage

```
// パッケージのインストール
npm install

// 開発サーバを起動
npm run dev
```

## Next Level

1. 現在の着手の部分だけ、ボタンではなく “You are at move #…” というメッセージを表示するようにする。
1. マス目を全部ハードコードするのではなく、Board を 2 つのループを使ってレンダーするよう書き直す。
1. 手順を昇順または降順でソートできるトグルボタンを追加する。
1. どちらかが勝利したときに、勝利につながった 3 つのマス目をハイライト表示する。引き分けになった場合は、引き分けになったという結果をメッセージに表示する。
1. 着手履歴リストで、各着手の場所を (row, col) という形式で表示する。
