# Site Estimates

SEOクロールレポートからサイト構造を分析し、システムの機能構成と開発規模の概算見積もり（ROM）をまとめたリポジトリです。

## 対象サイト

| サイト | ページ数 | 見積レポート（HTML） | 見積レポート（Markdown） | 元データ |
|---|---|---|---|---|
| urakare.jp | 108 | [urakare.jp/estimate.html](urakare.jp/estimate.html) | [urakare.jp/estimate.md](urakare.jp/estimate.md) | [urakare.jp/](urakare.jp/) |
| story-tokyo.com | 408 | [story-tokyo.com/estimate.html](story-tokyo.com/estimate.html) | [story-tokyo.com/estimate.md](story-tokyo.com/estimate.md) | [story-tokyo.com/](story-tokyo.com/) |
| topclass-tokyo.com | 103 | [topclass-tokyo.com/estimate.html](topclass-tokyo.com/estimate.html) | [topclass-tokyo.com/estimate.md](topclass-tokyo.com/estimate.md) | [topclass-tokyo.com/](topclass-tokyo.com/) |

`estimate.html` はブラウザで直接開くとデザイン付きの見積書として、`estimate.md` はGitHub上でそのまま整形されたテーブルとして確認できます（内容は同一です）。

`crawl-report/` 配下は各サイトのSEOクロールツールが出力した生データ（SEO-full.csv、リンク解析、重複タイトル検出など）です。
