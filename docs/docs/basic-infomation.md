---
tags: [docs]
---

# Basic Infomation

- BaseURL: `https://api.jaoafa.com/`
- Available Version: `v1` (`https://api.jaoafa.com/v1/`)
- バージョンを指定せずリクエストすることもできます。その場合、最新バージョンが選択されます。
- GET リクエストにおいて、同一エンドポイントに対してのリクエストで同一フィールドを複数指定した場合、?で指定されたフィールドを優先して使用します。
  - `v1/users/X4Z?mcid=mine_book000`: mcid=`mine_book000`のデータを取得
  - `v1/users/X4Z?uuid=xxxxx`: uuid=`xxxxx`のデータを取得
