# 一人麻雀 — Solo Mahjong

ブラウザでそのまま遊べる一人用麻雀。山が尽きる前のツモ和了を目指します。

**▶ 遊ぶ / Play: https://chitsng.github.io/solo-mahjong/**

## 遊びかた

- いらない牌をクリックして切るだけ。表示は向聴数と山の残り枚数のみ
- 聴牌したらリーチ、四枚そろえば暗槓。役はツモ和了時に自動判定
- 右上の「？」で和了の形と役の図鑑。一度でも作った役にはチェックが付きます（成就帳）
- 「参考」トグルで切り推奨の上位5枚を表示——向聴が進む順→受け入れ枚数順。
  バッジをクリックすると受け入れ牌の顔ぶれが見えます
- 和了・流局で一筒コインが貯まり、お守り屋で次局の運が買えます
- キー操作: **F** = フルスクリーン

## 技術メモ

- 依存ゼロの単一 HTML。ダウンロードしてダブルクリックでもオフラインで遊べます
- 牌は Unicode 麻雀牌（U+1F000–）を埋め込みフォントで単色描画
- 成就と設定は localStorage に保存されます

---

A single-file, dependency-free solo mahjong game in Japanese.
Download `index.html` and double-click to play offline, or use the link above.
