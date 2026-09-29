# SwingTwin — 製品LP

iPhone アプリ「SwingTwin（スイングツイン）」（内部名 GolfSwingCompare）の製品紹介ページ。GitHub Pages で公開する想定。

- 公開URL: https://shoheicraftdev-design.github.io/swingtwin-lp/ **公開済み**（2026-09-04）
- App Store: **公開中**（2026-09-02）。`https://apps.apple.com/jp/app/swingtwin/id6806578247`
- サポート / プライバシーポリシー / 利用規約: https://shoheicraftdev-design.github.io/swingtwin-support/

## 位置づけ

GearDeban LP（`geardeban-lp`）・Sodato LP（`sodato-lp`）・えも日LP（`emo-diary-lp`）と同じく、**匿名ライン（note・Xで製品名を出さない）を維持したまま
アプリ名とストアURLを出せるチャネル**。ASC のマーケティングURLに設定する想定。
サポート・法務ページは別リポジトリ `swingtwin-support` が持つ（ここには置かない）。

## 内容の版

**ブランチ `ver-2.0`: ver-2.0（2026-09-28 審査提出・審査中）に合わせて作成。審査承認・App Store 公開を確認してから main へ入れる（それまで公開しない）。**
正本はアプリ側 `docs/appstore/ver-2.0-store-listing.md`（§2 サブタイトル・§6 説明文・§7 有料プラン）と `ver-2.0-submission.md`。LP で新しい言い回しを作らない。
ASC のマーケティングURL に本ページ（`https://shoheicraftdev-design.github.io/swingtwin-lp/`）を ver-2.0 で設定済み（submission #31）。

**v1.1 に合わせて更新（2026-09-28）。** v1.0（2026-09-02 App Store 公開）で作成し、v1.1 で対応環境を iOS 17.0 以上に訂正、ピンチでの拡大・縮小・移動と書き出し形式（並べる／重ねる）の選択を追記。

## 素材

`images/` は、アプリ側リポジトリ `golf-swing-compare` から書き出したもの。

| ファイル | 元 |
| :--- | :--- |
| `appicon.png` | `GolfSwingCompare/Resources/Assets.xcassets/AppIcon.appiconset/AppIcon-1024.png` の縮小（256px） |
| `shot-overlay-trails.png` | `docs/appstore/screenshots/ver-2.0/6.5-inch/01-overlay-trails.png`（重ねる＋軌跡・有料プラン） |
| `shot-overlay-free.png` | `docs/appstore/screenshots/ver-2.0/6.5-inch/02-overlay-free.png`（重ねる・軌跡なし） |
| `shot-sidebyside-trails.png` | `docs/appstore/screenshots/ver-2.0/6.5-inch/03-sidebyside-trails.png`（並べる＋軌跡・有料プラン） |
| `shot-checkpoints.png` | `docs/appstore/screenshots/ver-2.0/6.5-inch/04-checkpoints.png`（基準点を指定） |
| `shot-video-select.png` | `docs/appstore/screenshots/ver-2.0/6.5-inch/05-video-select.png`（スイングを選ぶ・位置合わせ済み） |

いずれも長辺640pxへ縮小（`sips -Z 640`・296×640）。キャプション帯は掲載スクショに焼き込まれたまま。差し替える場合は元の1284×2778から作り直すこと。

## 文言のルール（アプリ側 `docs/appstore/ver-2.0-store-listing.md` の内容を継承）

- 訴求の軸は「土台を揃えてから重ねる」——大きさ・位置・タイミングを自動で合わせるから、残った差だけがフォームの違いになる。
- 他アプリとの比較・優劣（固有名詞での名指し）は書かない。
- 誇大表現（「劇的に上達」等）は書かない。効果を保証する文言は避ける。

## 公開手順

**完了。** geardeban-lp と同じ手順で GitHub リポジトリを新規作成し GitHub Pages を有効化した（2026-09-04・CEO確認済み）。
