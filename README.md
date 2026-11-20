# 🪸🐟 my-nemo

marimo製 個人利用ツール群

|ツール|内容|
|---|---|
|magic_packet|Magic Packet 送信 / RDP 疎通確認ツール|

* 環境構築: `uv sync --compile-bytecode`
  * --compile-bytecode 起動後のレスポンスタイム向上のために事前コンパイル
* 起動: `uv run task app`
  * marimoがギャラリーモードで起動する（[→ 公式ガイド](https://docs.marimo.io/guides/apps/#gallery)）。
  * 自動的に立ち上がるブラウザから、ツールを利用できる。

## 🖊️ 開発

* 実装方針: [docs/dev_guide.md](docs/dev_guide.md)を参照する。
* アーキテクチャ: [pyproject.toml](pyproject.toml)を参照する。
* やれること: `uv run task`で一覧表示する。
* 言語化して残すべき記録:
  * **What / How**: ソースコード上Docstring
  * **Why / Context**: `docs/adr_*.md`
  * **必要な環境変数**: [.env.example](.env.example)
