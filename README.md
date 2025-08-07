# uchiake_demo
うちあけのhtmlでのデモページです。
各ボタンを押すと、画面遷移するようにしています。

8/6時点で実装済みのページ
ログイン前ページ（index）
ログイン後ページ/マイページ（profile）
ガイドライン（guideline）
投稿（new/form）
投稿閲覧/検索※アカウント登録前（search）
投稿閲覧/検索※アカウント登録後（search-user）
通知（notification）
通知内　公式からのお知らせ（official-news）
通知内　投稿詳細画面（post-detail）
マイページ　プロフィール編集（profile-edit）
投稿編集　投稿種類別（form-edit-talk）（form-edit-journal）（form-edit-contribute）
※マイページの自分の投稿のところの3つをそれぞれの投稿種別のものにしているので、編集を押すと各種別ごとの編集画面に飛びます。

コミュニティ（community）
コミュニティ詳細（community-detail）
コミュニティ内トピック詳細（topic-detail）
コミュニティ追加（new/community）
コミュニティ内トピック追加（new/topic）


【実装時に確実に修正が必要な部分】
・投稿送信、投稿の表示や検索結果の表示など実際のバックエンドとの連携
・auth0のURL置き換え→現在のindex.htmlでは、リンクをsignupまでにしていますが、正しくIDまで含んだものに置き換えが必要
・現状は会員登録なしでも見れる機能「閲覧」は、searchとsearch-userでhtmlページ自体を分けていますが、実装時にはどうするか
・投稿、投稿編集コミュニティ、コミュニティ内トピックなどは実際には投稿IDで表示されるように変更が必要（現在は仮でpost-detailなどのページを表示）
