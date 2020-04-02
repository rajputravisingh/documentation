---
title: ホスト総数
type: apicontent
order: 14.2
external_redirect: /api/#host-totals
---

## ホスト総数

このエンドポイントは、Datadog アカウントでアクティブなホストと作動中のホストの総数を返します。アクティブなホストとは、過去 1 時間以内に報告を行ったホストで、作動中のホストとは、過去 2 時間以内に報告を行ったホストです。

**引数**:

* **`from`** [オプション、 デフォルト = **now - 2 hours**]:
    アクティブかつ動作中のホスト総数を取得するUNIX エポックからの経過秒数。