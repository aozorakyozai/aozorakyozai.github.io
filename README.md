# aozorakyozai.github.io

aozorakyozai のデベロッパ Web サイト（GitHub Pages / ユーザーページ）。

## app-ads.txt

AdMob は「App Store 掲載のデベロッパ Web サイトのドメイン直下」を巡回して
`app-ads.txt` を探す。ここに置くことで広告在庫が正規のものだと宣言でき、
なりすまし在庫を排除する買い手からの入札が入るようになる（配信上限が上がる）。

- 配信 URL: `https://aozorakyozai.github.io/app-ads.txt`
- パブリッシャー ID: `pub-7505158016747432`（aozorakyozai の AdMob アカウント）
- 形式: `<広告システムのドメイン>, <パブリッシャーID>, <DIRECT|RESELLER>, <認証局ID>`
  - `f08c47fec0942fa0` は Google の TAG ID（全パブリッシャー共通の固定値）

AdMob 側に検出させるには、App Store Connect のアプリ情報で
**マーケティング URL を `https://aozorakyozai.github.io/` に設定**しておく必要がある。
（未設定だと AdMob は巡回先ドメインを特定できない）

メディエーションのパートナーを追加したときは、そのパートナーが指定する行を追記すること。

## 関連

- SUDOKU³ サポートページ: https://aozorakyozai.github.io/Sudoku3D/support.html
  （別リポジトリ `aozorakyozai/Sudoku3D`）
