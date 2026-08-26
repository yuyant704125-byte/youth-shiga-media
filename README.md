# youth-shiga-media

Instagram (@youth.shiga) 投稿画像の置き場。

Instagram Graph API は画像ファイルそのものを受け取らず、公開URLを渡すと
Meta のサーバーが取りに来る仕様のため、公開URLが必要になる。

## 使い方

`posts/` に JPEG を置くと、以下のURLで参照できる。

```
https://raw.githubusercontent.com/yuyant704125-byte/youth-shiga-media/main/posts/<ファイル名>.jpg
```

## 制約

- **JPEG のみ**（Instagram API は PNG を受け付けない）
- 1080x1080 推奨
- 8MB 以下

## 注意

public リポジトリ。認証情報・個人情報は絶対に置かない。
