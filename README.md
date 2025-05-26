<div align="center">

<svg width="100%" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bgGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#ff6b6b;stop-opacity:0.2" />
      <stop offset="25%" style="stop-color:#4ecdc4;stop-opacity:0.2" />
      <stop offset="50%" style="stop-color:#45b7d1;stop-opacity:0.2" />
      <stop offset="75%" style="stop-color:#96ceb4;stop-opacity:0.2" />
      <stop offset="100%" style="stop-color:#feca57;stop-opacity:0.2" />
    </linearGradient>
    <linearGradient id="textGradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ff6b6b" />
      <stop offset="20%" style="stop-color:#4ecdc4" />
      <stop offset="40%" style="stop-color:#45b7d1" />
      <stop offset="60%" style="stop-color:#96ceb4" />
      <stop offset="80%" style="stop-color:#feca57" />
      <stop offset="100%" style="stop-color:#ff9ff3" />
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge> 
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <!-- Background -->
  <rect width="100%" height="100%" fill="url(#bgGradient)" rx="15"/>
  
  <!-- Decorative bamboo -->
  <g stroke="#96ceb4" stroke-width="4" fill="none" opacity="0.6">
    <line x1="50" y1="20" x2="50" y2="180"/>
    <line x1="45" y1="60" x2="55" y2="60"/>
    <line x1="45" y1="100" x2="55" y2="100"/>
    <line x1="45" y1="140" x2="55" y2="140"/>
    <line x1="750" y1="20" x2="750" y2="180"/>
    <line x1="745" y1="60" x2="755" y2="60"/>
    <line x1="745" y1="100" x2="755" y2="100"/>
    <line x1="745" y1="140" x2="755" y2="140"/>
  </g>
  
  <!-- Cherry blossom petals -->
  <g fill="#ff9ff3" opacity="0.7">
    <circle cx="120" cy="40" r="8"/>
    <circle cx="130" cy="30" r="6"/>
    <circle cx="110" cy="35" r="5"/>
    <circle cx="680" cy="45" r="7"/>
    <circle cx="690" cy="35" r="5"/>
    <circle cx="670" cy="40" r="6"/>
    <circle cx="150" cy="160" r="6"/>
    <circle cx="140" cy="170" r="5"/>
    <circle cx="650" cy="165" r="7"/>
    <circle cx="660" cy="155" r="5"/>
  </g>
  
  <!-- Sparkles -->
  <g fill="#feca57" opacity="0.8">
    <polygon points="200,50 202,54 206,54 203,57 204,61 200,58 196,61 197,57 194,54 198,54" />
    <polygon points="600,60 601,63 604,63 602,65 603,68 600,66 597,68 598,65 596,63 599,63" />
    <polygon points="180,120 181,122 183,122 182,124 182.5,126 180,125 177.5,126 178,124 177,122 179,122" />
    <polygon points="620,130 621,132 623,132 622,134 622.5,136 620,135 617.5,136 618,134 617,132 619,132" />
    <polygon points="250,170 251,172 253,172 252,174 252.5,176 250,175 247.5,176 248,174 247,172 249,172" />
    <polygon points="550,40 551,42 553,42 552,44 552.5,46 550,45 547.5,46 548,44 547,42 549,42" />
  </g>
  
  <!-- Main title -->
  <text x="400" y="80" font-family="Arial, sans-serif" font-size="48" font-weight="bold" text-anchor="middle" fill="url(#textGradient)" filter="url(#glow)">
    🎋 おみくじアプリ ✨
  </text>
  
  <!-- Subtitle -->
  <text x="400" y="110" font-family="Arial, sans-serif" font-size="18" text-anchor="middle" fill="#4ecdc4" opacity="0.9">
    ～ ギャルAI「キラリ」と一緒に運勢チェック ～
  </text>
  
  <!-- Decorative elements -->
  <g stroke="#ff6b6b" stroke-width="2" fill="none" opacity="0.6">
    <path d="M 200 130 Q 300 140 400 130 Q 500 120 600 130" />
  </g>
  
  <!-- Fortune symbols -->
  <text x="320" y="160" font-family="Arial, sans-serif" font-size="24" text-anchor="middle" fill="#ff6b6b">🔮</text>
  <text x="380" y="160" font-family="Arial, sans-serif" font-size="24" text-anchor="middle" fill="#4ecdc4">⭐</text>
  <text x="420" y="160" font-family="Arial, sans-serif" font-size="24" text-anchor="middle" fill="#45b7d1">🌙</text>
  <text x="480" y="160" font-family="Arial, sans-serif" font-size="24" text-anchor="middle" fill="#96ceb4">🍀</text>
</svg>

</div>

# 🎋 おみくじアプリ

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-1.28.0+-red.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Maintenance](https://img.shields.io/badge/Maintained-Yes-brightgreen.svg)

**日本の伝統的なおみくじをモチーフにしたStreamlitベースのWebアプリケーション**

</div>

## 📖 概要

このアプリケーションは、ユーザーが仮想的におみくじを引いて今日の運勢を占うことができるシンプルで楽しいWebアプリです。7種類の運勢結果があり、それぞれに特色のあるメッセージとアドバイスが表示されます。

### 🎯 主な目的
- 日本の伝統文化であるおみくじをデジタル化
- 毎日のモチベーション向上のためのツール
- Streamlitの基本機能を活用したサンプルアプリケーション

## ✨ 機能

- **🎯 おみくじを引く**: ボタンをクリックして運勢を占う
- **🌈 カラフルなUI**: 運勢ごとに異なる色でカードを表示
- **💭 メッセージ表示**: 運勢に応じたメッセージとアドバイス
- **📅 日時表示**: 現在の日時をリアルタイムで表示
- **🔄 再実行機能**: 何度でもおみくじを引き直し可能
- **ℹ️ サイドバー情報**: おみくじの種類と詳細な説明
- **🎈 視覚エフェクト**: バルーンアニメーションで結果を華やかに演出

## 🎲 運勢の種類

| 運勢 | 確率 | 説明 | カラーテーマ |
|------|------|------|-------------|
| 大吉 | 1/7 | 最高の運勢 | #ff6b6b (赤) |
| 中吉 | 1/7 | とても良い運勢 | #4ecdc4 (ターコイズ) |
| 小吉 | 1/7 | 良い運勢 | #45b7d1 (青) |
| 吉 | 1/7 | 普通の運勢 | #96ceb4 (緑) |
| 末吉 | 1/7 | 後半良くなる運勢 | #feca57 (黄) |
| 凶 | 1/7 | 注意が必要 | #ff9ff3 (ピンク) |
| 大凶 | 1/7 | 困難な時期 | #54a0ff (ライトブルー) |

## 🛠️ 技術スタック

- **Python 3.8+**: プログラミング言語
- **Streamlit 1.28.0+**: Webアプリケーションフレームワーク
- **HTML/CSS**: カスタムスタイリング
- **datetime**: 日時処理
- **random**: ランダム選択機能

## 📦 インストール

### 前提条件
- Python 3.8以上がインストールされていること
- pipが利用可能であること

### セットアップ手順

1. **リポジトリをクローンします：**
```bash
git clone https://github.com/Sunwood-ai-labs/claude-code-gh-action-examples-001.git
cd claude-code-gh-action-examples-001
```

2. **仮想環境を作成します（推奨）：**
```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

3. **必要なパッケージをインストールします：**
```bash
pip install -r requirements.txt
```

## 🚀 使用方法

### アプリケーションの起動

```bash
streamlit run omikuji_app.py
```

アプリケーションが起動すると、ブラウザが自動的に開き、通常は `http://localhost:8501` でアクセスできます。

### 基本的な使い方

1. **アプリケーションにアクセス** - ブラウザでローカルホストを開く
2. **おみくじを引く** - 「🎯 おみくじを引く」ボタンをクリック
3. **結果を確認** - カラフルなカードで運勢結果を表示
4. **メッセージを読む** - 今日のメッセージとアドバイスを確認
5. **再挑戦** - 「🔄 もう一度引く」ボタンで再度実行
6. **詳細情報** - サイドバーでおみくじの詳細情報を確認

## 📁 ファイル構成

```
claude-code-gh-action-examples-001/
├── README.md           # プロジェクト説明書（このファイル）
├── omikuji_app.py     # メインアプリケーションファイル
├── requirements.txt   # 必要なPythonパッケージリスト
└── .gitignore         # Git除外ファイル設定
```

### ファイル詳細

- **`omikuji_app.py`**: Streamlitアプリケーションのメインファイル
  - おみくじの結果データ定義
  - UI/UXの実装
  - ランダム選択ロジック
- **`requirements.txt`**: 依存パッケージの管理
- **`README.md`**: プロジェクト情報とドキュメント

## 🎨 デザイン特徴

- **レスポンシブデザイン**: 様々な画面サイズに自動対応
- **日本語対応**: 完全な日本語インターフェース
- **視覚的フィードバック**: バルーンエフェクトと色分けされた結果表示
- **直感的UI**: ワンクリックで簡単操作
- **モダンなスタイリング**: CSS3を活用したグラデーションとシャドウ効果

## 🔧 カスタマイズ

### 運勢の追加・変更

`omikuji_app.py`の`OMIKUJI_RESULTS`リストを編集することで、運勢の種類やメッセージをカスタマイズできます：

```python
OMIKUJI_RESULTS = [
    {
        "result": "超大吉",  # 運勢名
        "color": "#ff0000",  # カラーコード
        "message": "カスタムメッセージ",
        "advice": "カスタムアドバイス"
    }
    # 他の運勢...
]
```

### UIスタイルの変更

HTMLとCSSを直接編集することで、カードのデザインや色彩を変更できます。

## 🧪 テスト

基本的な動作確認：

```bash
# アプリケーションが正常に起動するかテスト
streamlit run omikuji_app.py --server.headless true
```

## 🤝 貢献ガイドライン

プロジェクトへの貢献を歓迎します！以下の方法で参加できます：

### 貢献方法

1. **イシューの報告** - バグや改善提案をGitHub Issuesで報告
2. **機能追加** - 新機能のプルリクエストを作成
3. **ドキュメント改善** - READMEやコメントの改善
4. **翻訳** - 多言語対応への貢献

### プルリクエストのガイドライン

1. フォークしてブランチを作成
2. 変更を加えてテスト
3. コミットメッセージは明確に記述
4. プルリクエストで詳細な説明を提供

## 📋 今後の予定

- [ ] 運勢の詳細情報ページ追加
- [ ] ユーザーカスタマイズ機能
- [ ] 運勢履歴の保存機能
- [ ] 多言語対応（英語、中国語など）
- [ ] モバイルアプリ版の開発
- [ ] API機能の追加

## 📄 ライセンス

このプロジェクトはMITライセンスの下で公開されています。詳細は[LICENSE](LICENSE)ファイルをご覧ください。

## 👥 作者情報

- **開発元**: [Sunwood AI Labs](https://github.com/Sunwood-ai-labs)
- **メンテナー**: Sunwood AI Labs チーム
- **サポート**: GitHub Issues を通じてサポートを提供

## 🙏 謝辞

- Streamlitコミュニティの皆様
- 日本の伝統文化であるおみくじに敬意を表して
- オープンソースコミュニティへの感謝

---

<div align="center">

**Made with ❤️ using [Streamlit](https://streamlit.io/)**

[🏠 ホーム](https://github.com/Sunwood-ai-labs/claude-code-gh-action-examples-001) | 
[📊 Issues](https://github.com/Sunwood-ai-labs/claude-code-gh-action-examples-001/issues) | 
[🔄 Pull Requests](https://github.com/Sunwood-ai-labs/claude-code-gh-action-examples-001/pulls)

</div>