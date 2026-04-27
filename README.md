# 現場の日本語 PWA

## ファイル構成
```
genba-pwa/
  index.html    ← メインアプリ
  manifest.json ← PWA設定
  sw.js         ← オフライン対応（Service Worker）
  icons/        ← アプリアイコン（別途追加）
```

## スマホで使う方法

### 無料で今すぐ公開する手順

1. **GitHub アカウントを作る**（無料）
   https://github.com

2. **新しいリポジトリを作成**
   - Repository name: genba-nihongo
   - Public を選択
   - Create repository

3. **ファイルをアップロード**
   - index.html
   - manifest.json
   - sw.js

4. **GitHub Pages を有効にする**
   - Settings → Pages → Branch: main → Save

5. **URLが発行される**
   例: https://あなたのID.github.io/genba-nihongo/

6. **スマホで開いてホーム画面に追加**
   - Android: ブラウザメニュー →「ホーム画面に追加」
   - iPhone: Safari の共有ボタン →「ホーム画面に追加」

## アイコンの作り方（無料）
https://www.favicon-generator.org/
に画像をアップロードして 192x192 と 512x512 を生成
→ icons/ フォルダに入れる

## 今後の改善
- [ ] 単語数を増やす（CSVで管理）
- [ ] 音声録音機能
- [ ] 進捗のローカル保存
- [ ] Flutter化（iOS/Android正式版）
