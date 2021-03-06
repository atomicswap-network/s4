# Atomic Swap Network Server (ASNS)
[![SecHack365](https://img.shields.io/badge/SecHack365-2020-ffd700.svg)](https://sechack365.nict.go.jp/)
```
License: GPL v3
Author: y-chan
Language: Python (>= 3.8)
```

## What is this?
このソフトウェアはAtomic Swapを支援するクロスチェーンLayer2ネットワーク「Atomic Swap Network」を提供します。(将来的にはSubmarine Swapにも対応予定です)
このソフトウェアがユーザーの秘密鍵を収集することはありません(しかし、信頼せず、検証してください。`Don't trust, Verify.`)

## Getting started
以下のコマンドを実行します
```
git clone https://github.com/atomicswap-network/asns
cd asns
pip3 install -r requirements.txt  # Windowsの場合は requirements-windows.txt
./run_asns  # Windowsの場合は python run_asns
```

## License
このソフトウェアは[GPL v3](LICENSE)でライセンスされています。

## Branch Rules

|ブランチネーミングルール|用途|
|---|---|
|`feature/#{ISSUE_ID}-#{branch_title_name}`|将来的な機能の実装や、緊急ではないバグの修正に用います。|
|`hothix/#{ISSUE_ID}-#{branch_title_name}`|緊急のバグ・脆弱性修正などに用います。|
