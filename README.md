# LobiAPI
LobiのAPIにメールアドレスとパスワードのみでアクセス可能にするライブラリ

# masterからの変更点(予定も含む)
- HttpWebRequest,HttpWebResponseからHttpClientに変更
- BasicHeaderの削除
- メソッドで使用するヘッダを共通のオブジェクトにまとめる
- 一部、例外処理を追加

## APIの機能一覧
- ログイン(Lobiアカウント, Twitter認証)
- プロフィールの取得
- プロフィールの編集
- 参加しているグループの一覧取得
- 指定したグループのメンバ一覧の取得
- - プライベートグループの作成
- フォロー、フォロワーの一覧取得
- フォロー、フォロー解除
- スレッドの取得
- スレッドの作成、返信
- グー、ブー、それぞれのキャンセル
- チャットにグーブーした人の一覧取得
- ブックマークしているチャットの一覧取得
- お知らせの取得
