# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## リポジトリの目的

これはGitHubの特殊なプロファイルリポジトリ（`eno-conan/eno-conan`）です。`README.md` の内容が GitHub プロファイルページ（https://github.com/eno-conan）にそのまま表示されます。

ソースコード・ビルドシステム・テスト・CI/CD は存在しません。変更は `README.md` を編集して `main` ブランチにプッシュするだけで即座に反映されます。

## ファイル構成

```
eno-conan/
├── README.md          # GitHubプロファイルページに表示されるコンテンツ
└── .claude/
    └── settings.local.json
```

## README.md の構成

| セクション | 内容 |
|---|---|
| About Me | 自己紹介・現在の活動 |
| 2026年の予定 | 今年の技術目標 |
| Tech Stack | 使用技術のバッジ一覧 |
| GitHub Stats | GitHub統計・使用言語の動的表示 |
| GitHub Trophies | トロフィー表示 |
| Contribution Graph | コントリビューショングラフ |
| Dev Quote | 開発者名言 |

## 動的コンテンツ（外部サービス）

README.md 内のコンテンツは以下の外部サービスから動的に生成されます。URLの `username` パラメータはすべて `eno-conan` を使用しています。

| サービス | 用途 |
|---|---|
| `shields.io` | テックスタックバッジ |
| `komarev.com/ghpvc` | プロフィールビューカウンター |
| `github-readme-stats.vercel.app` | GitHub統計・使用言語ランキング |
| `github-profile-trophy.vercel.app` | GitHubトロフィー |
| `github-readme-activity-graph.vercel.app` | コントリビューショングラフ |
| `quotes-github-readme.vercel.app` | 開発者名言 |

## バッジの追加パターン

テックスタックにバッジを追加する場合は `shields.io` の以下の形式を使用してください：

```
https://img.shields.io/badge/-{ラベル}-{背景色HEX}?style=for-the-badge&logo={SimpleIconsのロゴ名}&logoColor={文字色}
```

例（Kotlinバッジ）:
```html
<img src="https://img.shields.io/badge/-Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" />
```

ロゴ名は [Simple Icons](https://simpleicons.org/) で検索できます。
