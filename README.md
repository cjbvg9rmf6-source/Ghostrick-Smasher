# Ghostrick Smasher — プレリリース

ブラウザで遊ぶ横スクロール迎撃ゲーム。タップ／クリックで攻撃。

## 公開予定URL（公開完了後に利用）
- 通常版: https://cjbvg9rmf6-source.github.io/Ghostrick-Smasher/
- 3000m開始版: https://cjbvg9rmf6-source.github.io/Ghostrick-Smasher/test-3000m.html

## GitHub Pages 公開手順
1. cjbvg9rmf6-source に新規リポジトリ `Ghostrick-Smasher` を作成。
2. このフォルダの中身を main の直下にアップロード。index.html をリポジトリ直下へ置く。ZIPのまま置かない。
3. Settings → Pages → Build and deployment → Source: Deploy from a branch。
4. Branch: main、Folder: /(root) を選び Save。
5. 公開処理完了後、上記URLを開いて確認。

スマートフォンで遊ぶときは公開URLを使用。ZIPはGitHubへ配置するための素材一式。

## 準備内容
- 通常版／3000m開始版、全画像・BGM・SEを同梱。
- GitHub Pagesのサブディレクトリに対応した相対パス。
- 投稿URLは閲覧中の公開先を使用し、テスト版でも通常版URLを共有。
- リザルトのランク画像・個別メッセージ、最新の図鑑説明を含む。
- 元ソース: Sites commit e73e41b87f127a5814812ce636cf14caede7d554。

## 確認状況
ローカルで両HTMLの構文と素材の参照先を検査。GitHub Pagesでの実際の公開・iPhone Safari実機確認は未実施。

## 公開後の確認
通常版0m開始、テスト版3000m開始、タップ迎撃、音量調整、BGM／SE、図鑑、リザルト画像と文言、X投稿URLを確認。

公式の遊戯王サービスではないファン制作ゲームです。

## 軽量化
未使用の旧スパンキー1画像・旧デュラハン5画像を削除（1,084,138 bytes）。現行素材194件の参照先が存在することを確認。
