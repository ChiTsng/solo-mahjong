# 一人麻雀 — Solo Mahjong

**▶ 遊ぶ / 开始游玩 / Play: https://chitsng.github.io/solo-mahjong/**

---

## 日本語

ブラウザでそのまま遊べる一人用麻雀。山が尽きる前のツモ和了を目指します。

### 遊びかた

- いらない牌をクリックして切るだけ。表示は向聴数と山の残り枚数のみ
- 聴牌したらリーチ、四枚そろえば暗槓。役はツモ和了時に自動判定
- 右上の「？」で和了の形・役の図鑑・成就帳。初めて作った役や初めての体験
  （初和了・見逃し・初リーチ など）は達成の瞬間トーストで知らせ、図鑑にチェックが付きます
- 電球ボタンで切り推奨の参考表示——向聴が進む順→受け入れ枚数順の上位5枚。
  バッジをクリックすると受け入れ牌の顔ぶれが見えます
- 和了・流局で一筒コインが貯まり、お守り屋で次局の運が買えます
- 円環矢印ボタンで全記録を初期化（誤爆防止に二度押しで確定）
- キー操作: **F** = フルスクリーン

### 技術メモ

- 依存ゼロの単一 HTML。ダウンロードしてダブルクリックでもオフラインで遊べます
- 牌は Unicode 麻雀牌（U+1F000–）を埋め込みフォントで単色描画
- 成就・硬貨・買い置きの御守・設定は localStorage に保存されます

---

## 中文

在浏览器里直接游玩的单人麻将。目标是在牌山摸完之前自摸和了。

### 玩法

- 点击不要的牌切掉即可。界面只显示向听数和牌山余量
- 听牌后可以立直,凑齐四张可以暗杠。役种在自摸和了时自动判定
- 右上角「？」打开和牌形、役种图鉴与成就帐。首次做成的役与各种初体验
  (首次和牌、见逃、首次立直等)达成瞬间弹出提示,并在图鉴里打勾
- 灯泡按钮开启切牌参考——先按是否前进向听排序,再按进张枚数排序,标出前五选。
  点击徽章可查看具体的进张牌面
- 和了、流局都会积攒一筒硬币,可以在御守屋为下一局买点运气
- 圆圈箭头按钮重置全部记录(防误触,需二次点击确认)
- 快捷键: **F** = 全屏

### 技术说明

- 零依赖单文件 HTML,下载后双击即可离线游玩
- 麻将牌使用 Unicode 麻将区字符(U+1F000–),以内嵌字体单色渲染
- 成就、硬币、已购御守与设置保存在 localStorage

---

## English

A solo mahjong game playable right in the browser. Win by tsumo before the wall runs out.

### How to play

- Click the tile you don't need to discard it. The UI shows only the shanten count and the remaining wall
- Declare riichi when tenpai; call a concealed kan with four of a kind. Yaku are scored automatically on a tsumo win
- The "？" button opens the guide: winning shapes, a yaku encyclopedia and an achievement book.
  First-time yaku and milestones (first win, a deliberate win pass, first riichi, …) pop a toast and get checkmarks
- The lightbulb toggle shows the top-5 recommended discards — ordered by shanten advance first, then by tile acceptance count.
  Click a badge to see exactly which tiles it accepts
- Wins and exhaustive draws earn coin; spend it at the charm shop for luck next hand
- The circular-arrow button resets all records (click twice to confirm)
- Keyboard: **F** = fullscreen

### Technical notes

- A single dependency-free HTML file — download and double-click to play offline
- Tiles are Unicode mahjong characters (U+1F000–) rendered monochrome with an embedded font
- Achievements, coins, purchased charms and settings persist in localStorage
