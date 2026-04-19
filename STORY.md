# Day054 Story — Desk Checkout Tray

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day054専用にテーマをseed固定して再生成時の見た目を安定化
- productivity用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: desk_checkout_split
- Mechanic: tray_sort
- Input/Output: desk_items -> checkout_trays
- Audience Promise: 今夜持ち帰る物が一目で決まる。
- Publish Hook: 机上の物を分けるだけで今夜持つ物と置く物が固まり、退勤前の迷いが減る。
- Complexity Tier: small
- Selected components: none
- Complexity hint: Implement the locked brief with one clear hero interaction and keep the main screenshot readable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day054｜退勤もちもの分け
持ち帰る物を分けやすくするためのツールです。
