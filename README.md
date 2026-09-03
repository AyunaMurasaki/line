# 紫あゆな 公式LINE 友だち追加バナーページ

公式LINE（@977kuadq）へのタップ誘導だけを目的にした、1枚だけの単機能ページです。
GitHub Pages で公開します。

- 公開URL: https://ayunamurasaki.github.io/line/
- 所有者: AyunaMurasaki（紫あゆな 様）
- 保守: 立元（tattsun0827）

姉妹ページに [ファンクラブLP](https://ayunamurasaki.github.io/fanclub/)・
[英語教室LP](https://ayunamurasaki.github.io/english/) がありますが、
どちらも申し込みフォームを持つ案内ページです。このページはフォームを持たず、
**画面のどこをタップしても公式LINEの友だち追加（`https://lin.ee/VMailZP`）へ飛ぶだけ**の入口です。

## できること・できないこと

- 画像1枚（バナー）をSNSやトークに貼っただけでは、タップしても何も起きません（画像はリンクを持てないため）
- このページはその代わりに使います。ページ全体がリンクなので、URLを貼って開いてもらえば、タップで直接LINEアプリの友だち追加画面が開きます
- ページを開かず lin.ee/VMailZP のリンク文字列だけを直接送っても同じ動作になります。このページは「バナーの見た目も見せたい」ときに使います

## 中身

| ファイル | 何か |
|---|---|
| `index.html` | ページ本体。文章・CSSをすべてこの1枚に入れてあります |
| `images/portrait.jpg` | 05_応答1の元データと同じ（`ayuna-english-lp` と共通） |
| `images/qr.png` | 公式LINEの友だち追加QR（LINE公式の実物データ・チラシと共通） |

送信フォームは無いため、GAS・名簿・自動返信のしくみは一切関係しません。

## 直すとき

`index.html` を書き換えて push すれば、1分ほどで公開ページに反映されます。
配色はチラシのLINEバナー（`chirashi/組版_20260901/`）と合わせたターコイズ `#0FA3A3` です。
