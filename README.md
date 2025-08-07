# detect-iam-user-login-failures-revoke-permissions

[IAM ユーザーのログイン失敗を検知して複数回失敗すると権限を剥奪する仕組みを作ってみた](https://dev.classmethod.jp/articles/detect-iam-user-login-failures-revoke-permissions/) のリポジトリです。

## リソース

- loginfailure.yml
  - バージニア北部にて構築するリソーステンプレート
- loginfailure_other_region.yml
  - その他のリージョンで構築するリソーステンプレート
 
```
ブログとREADME内の図中には3リージョンのみ記載されていますが、
現在時点ではConsoleLoginのリージョンエンドポイントがサポートされたため全リージョン対象となります
```

## 構成図

<img src="/img/iam_account_lock_none.png">
