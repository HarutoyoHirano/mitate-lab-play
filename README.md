# 見立てラボ（試用版）

**同じに見える。でも、測り方を変えると違う。**

ブラウザで遊べる試用版です：https://harutoyohirano.github.io/mitate-lab-play/

- ログインなしで、謎1（人工軟骨）・謎2（人工血管）・謎3（神経の膜）・まとめ・つづきの謎まで遊べます
- この試用版はサーバーを使わず、ページの中で計算します。Claude はページから呼ばないので、つづきの謎は、Claude が組み立てて計算プログラムの確かめに通った記録で動きます（画面に「記録」と出ます）
- 謎1の隠れた試作品Bの値もページの中にあります（コードを読めば分かります）
- ラボ・試作品・検査ロボは架空です。値は、一般的なヒトの値を目安に置いた模型の値で、実際の機器を測った値や、病気の判定ではありません

このリポジトリには、本体（HarutoyoHirano/mitate-lab）から `npm run build:trial` でつくった一枚の HTML だけを入れています。

## ライセンスとソース
GNU Affero General Public License v3.0（AGPL-3.0-only。全文は `LICENSE`）。Copyright (C) 2026 Harutoyo Hirano

この HTML のソースは https://github.com/HarutoyoHirano/mitate-lab にあります。

## 使っている外部のソフトウェア
この HTML には @anthropic-ai/sdk（MIT License、Copyright 2023 Anthropic, PBC.）のコードが含まれています。MIT License の全文と著作権表示は、`index.html` の先頭の注釈に入れています。
