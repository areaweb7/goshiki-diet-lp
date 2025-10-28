# 五色ダイエット お菓子痩せLP - 更新方法

## 📍 公開URL
https://areaweb7.github.io/goshiki-diet-lp/

## 📂 ファイル構成
```
goshiki-diet-lp/
├── index.html          # メインのLPファイル
├── .nojekyll          # GitHub Pages設定用
├── .github/
│   └── workflows/
│       └── static.yml  # 自動デプロイ設定
└── README.md          # このファイル
```

## 🔄 更新方法

### 1. ファイルを編集
元ファイルの場所：
```
/Users/yi/Documents/Obsidian Vault/五色ダイエット/03_お菓子痩せ/LP_お菓子痩せプログラム_v2.html
```

または、直接以下のファイルを編集：
```
/Users/yi/Documents/Obsidian Vault/goshiki-diet-lp/index.html
```

### 2. Gitにコミット＆プッシュ

ターミナルで以下のコマンドを実行：

```bash
# リポジトリディレクトリに移動
cd "/Users/yi/Documents/Obsidian Vault/goshiki-diet-lp"

# 変更されたファイルをステージング
git add .

# コミット（メッセージは自由に変更可）
git commit -m "Update landing page"

# GitHubにプッシュ
git push
```

### 3. 自動デプロイ
プッシュすると、**自動的に**GitHub Actionsが起動して、1〜2分でサイトが更新されます。

### デプロイ状況の確認
https://github.com/areaweb7/goshiki-diet-lp/actions

## ⚡ クイックコマンド

```bash
# ワンライナーで更新（コミットメッセージ付き）
cd "/Users/yi/Documents/Obsidian Vault/goshiki-diet-lp" && \
git add . && \
git commit -m "Update LP content" && \
git push
```

## 🎨 デザイン仕様

### カウントダウンタイマー
- **開始**: 2025年10月29日（水）12:00
- **終了**: 2025年10月30日（木）23:59
- 自動的にカウントダウン（JavaScript実装済み）

### カラースキーム
- **パープル**: #9b87d1 → #7b68b8（グラデーション）
- **ピンク**: #ff6b9d → #ff4d7d
- **ホワイト**: #ffffff
- **テキスト**: #4a4a4a

### フォント
- メイン: 'Hiragino Maru Gothic ProN', 'Hiragino Sans', 'Yu Gothic', YuGothic, Meiryo

## 📝 重要なリンク

### フッターリンク
- プライバシーポリシー: https://sub.goshiki-diet.or.jp/p/privacy
- 特定商取引法: https://sub.goshiki-diet.or.jp/p/VYnavgonUMrK
- 会社概要: https://sub.goshiki-diet.or.jp/p/company

### 動画URL（Utageシステム）
- プロモーション動画: https://utage-system.com/video/4aLBGzjAUmwA
- 石原愛様: https://utage-system.com/video/ThvPCvlSYhl4
- 甲斐かずよ様: https://utage-system.com/video/bcBssnD1CYln
- 松井たう様: https://utage-system.com/video/CeuVuWr8g2dt

## 🛠️ トラブルシューティング

### サイトが更新されない場合
1. GitHub Actionsのログを確認
2. ブラウザのキャッシュをクリア（Cmd + Shift + R）
3. 5分ほど待ってから再度アクセス

### 404エラーが出る場合
- GitHub Pages設定を確認: https://github.com/areaweb7/goshiki-diet-lp/settings/pages
- Source: "GitHub Actions" になっているか確認

## 📌 注意事項

- ファイル名は必ず英字を使用（日本語は文字化けの原因）
- HTMLファイルの文字コードは UTF-8
- 決済リンクはダミー（#）なので、本番前に実際のURLに差し替え

## 🔗 関連ファイル

元ファイル（日本語名）も保持：
- LP_お菓子痩せプログラム_v2.html
- LP_お菓子痩せプログラム.html
- LP_お菓子痩せプログラム_glass.html

---

**作成日**: 2025年10月28日  
**最終更新**: 2025年10月28日

