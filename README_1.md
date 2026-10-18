# らくせんしゃの もり（落選者の森）

選挙で選ばれなかった提案を、森に住む「妖精」として残し、ほかの街や企業、地域の困りごとに出会わせるための civic tech プロトタイプです。

## 遊ぶ

- [よこはま しちょうせん 2026](./yokohama-2026/) — 2026年10月18日 横浜市長選挙の6候補の提案から生まれた6体の妖精と、18の「ちえ」

## つくり

- 1ファイルのHTML（Canvas + 素のJavaScript）。ビルド不要
- 進み具合はブラウザの localStorage にだけ保存されます
- 効果音は WebAudio で生成（初期状態はオフ）

## GitHub Pages で公開するとき

1. Settings → Pages → Branch を `main` / `(root)` にする
2. `yokohama-2026/index.html` の `og:image` と `og:url` を絶対URLに書き換える
   （例：`https://<ユーザー名>.github.io/rakusen-no-mori/yokohama-2026/og.png`）
3. 同ファイル冒頭の `SHARE_URL` に公開URLを入れると、シェア文にそのURLが入ります

## データについて

提案の要約は、2026年10月の候補者公開討論会での発言と、共同通信・日本経済新聞・神奈川新聞などの報道をもとにしています。ご本人の登録・確認は受けていません。妖精の姿は提案のテーマから描いたもので、ご本人の容姿とは関係ありません。顔写真は使用していません。

## 企画

マツノトキヒト（[@tokmatsuno](https://www.facebook.com/tokmatsuno/)）
