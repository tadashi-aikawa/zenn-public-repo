---
title: "README"
cssclass: zenn
date: 2022-12-19
modified: 2022-12-23
url: "https://zenn.dev/estra/articles/mbo-00-readme"
AutoNoteMover: disable
tags: [" #type/zenn/book #obsidian "]
aliases:
  - OZ-README
  - Obsidian本『Obsidianで記事や本を作ろう』
  - OZ本
---

## MOC

メイン
- [x] [[1-oz-begin]]
- [x] [[2-oz-what-is-obsidian]]
- [x] [[3-oz-thinking-way]]
- [x] [[4-oz-make-zenn-repo]]
- [x] [[a-oz-add-plugins]]
- [ ] [[5-oz-make-article-book]]
- [ ] [[6-oz-reuse-memo]]
- [x] [[b-oz-css-snippets]]

未番号

サブ
[[y-oz-epilogue]]

[[Obsidian本のアイデアキャンバス.canvas]]

## アウトライン

- **Obsidian とは** → [[1-oz-begin|Obsidian本『はじめに』]]
- ナレッジベースを作ろう
- メモを公開しよう
- **プラグインを入れよう** → 
    - リンターを入れよう
    - テンプレートを作ろう
- **Obsidian で記事/本を作成しよう**
    - 記事を本に昇華しよう
    - 本を更新していこう
    - **メモを記事にしよう**
- **見出しの粒度で再利用しよう**
- ~~プラグインを開発しよう~~
- **スタイリングスニペットでカスタマイズしよう** → [[Obsidian 特定クラスのノート背景色を変更|Obsidianで公開ノートに視覚的警告を出す]] → [[b-oz-css-snippets|OZ本『カスタム CSS スニペットでカスタマイズしよう』]]

## テーマ

テーマは「再利用性と結合・分離編集と公開範囲の分割管理」という感じで今までの方法をまとめる方向

- ツーリング (リンター、フォーマッター) 
- GitHub や Publish での公開範囲の分割と統括管理 
- Vscode でのレイヤ移動 (データとアプリケーションの分割) 
- 記事とメモの再利用 (結合編集・分離編集)
    - メモを記事にしよう → メモを移動しよう

## ネタ集め

ベースの説明
[[ohzflow-zenn-hugo-obsidian]]

一般説明
[[lifeHackDougubako_2022_draft_obsidian|『ライフハックの道具箱』2022年版ドラフト_obsidian]]

プラグイン系
[[Obsidian Plugin Linter]]
[[Obsidian Plugin Templater]]
[[Obsidian Plugin Auto Note Mover]]

リポジトリ執筆環境の構築について
[[pnpmの使い方]]
[[npm-about-dependencsies]]

## YAML

```yaml
chapters:
  - mbo-1-bigin # 『はじめに』
```
