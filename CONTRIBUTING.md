# 貢献の仕方

本リポジトリの改善・発展にご協力いただき，誠にありがとうございます！　このページには，issue や pull request を作成する際に順守していただきたい内容が記載されています。必ずご一読ください。

## 不具合報告・機能の追加要望について

何らかの修正・変更などを行いたい場合，まずは [issue](https://github.com/Meiryo7743/railway-maps-for-omawari/issues/new/choose) を建てるようお願いいたします。ただし，「[invalid](https://github.com/Meiryo7743/railway-maps-for-omawari/issues?q=label%3Ainvalid)」や「[duplicate](https://github.com/Meiryo7743/railway-maps-for-omawari/issues?q=label%3Aduplicate)」のラベルが付いた issue，またはそれに相当する内容の場合は受け付けいたしかねますので，あらかじめご了承ください。

不具合報告をなさる場合，画像を添付いただけますと大変助かります。また，大回り乗車の規則に反する事項をご指摘の場合は，検証できるようにすべく，その典拠も併せてご提示ください。お手数をおかけしますが，何卒よろしくお願いいたします。

新たな路線図の追加及びその図案のご提示は大歓迎です。ただし，作成にはかなりの時間を要することがありますので，あらかじめご了承ください。

## 開発環境

路線図は全て [draw.io](https://app.diagrams.net) で作成しております。

## ブランチ

本リポジトリは，main ブランチのみが存在します。ただし，このブランチに直接 push してはなりません。何かしらの変更をする際は，事前に issue を建てたうえで pull request をお送りください。なお，ブランチの命名規則は次の通りです。

| 種類       | 規則                        | 例                     |
| ---------- | --------------------------- | ---------------------- |
| 不具合修正 | `bug/{ISSUE_ID}-{NAME}`     | `bug/#1-fix-something` |
| 機能の追加 | `feature/{ISSUE_ID}-{NAME}` | `feature/#1-add-a-map` |
