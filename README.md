# Saml-Backend

## 環境セットアップ
秘密鍵と公開鍵を作成し、ルート直下に配置する。
```
openssl req -x509 -new -newkey rsa:2048 -nodes  -keyout idp-private-key.pem -out idp-public-cert.pem -days 7300
```

## 参考文献/引用元
- [ローカル環境のみで完結するSAML SSOサンプル - Qiita](https://qiita.com/murasuke/items/9bf5ca8083d1da3dd66f)
- [Samlサンプルソース - GitHub](https://github.com/murasuke/simple-saml-auth)