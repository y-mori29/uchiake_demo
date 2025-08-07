# uchiake_demo
うちあけのhtmlでのデモページです。
各ボタンを押すと、画面遷移するようにしています。<br><br>

8/6時点で実装済みのページ<br>
ログイン前ページ（index）<br>
ログイン後ページ/マイページ（profile）<br>
ガイドライン（guideline）<br>
投稿（new/form）<br>
投稿閲覧/検索※アカウント登録前（search）<br>
投稿閲覧/検索※アカウント登録後（search-user）<br>
通知（notification）<br>
通知内　公式からのお知らせ（official-news）<br>
通知内　投稿詳細画面（post-detail）<br>
マイページ　プロフィール編集（profile-edit）<br>
投稿編集　投稿種類別（form-edit-talk）（form-edit-journal）（form-edit-contribute）<br>
※マイページの自分の投稿のところの3つをそれぞれの投稿種別のものにしているので、編集を押すと各種別ごとの編集画面に飛びます。<br><br>

コミュニティ（community）<br>
コミュニティ詳細（community-detail）<br>
コミュニティ内トピック詳細（topic-detail）<br>
コミュニティ追加（new/community）<br>
コミュニティ内トピック追加（new/topic）<br><br><br>


【実装時に確実に修正が必要な部分】<br>
・投稿送信、投稿の表示や検索結果の表示など実際のバックエンドとの連携<br>
・auth0のURL置き換え→現在のindex.htmlでは、リンクをsignupまでにしていますが、正しくIDまで含んだものに置き換えが必要<br>
・現状は会員登録なしでも見れる機能「閲覧」は、searchとsearch-userでhtmlページ自体を分けていますが、実装時にはどうするか<br>
・投稿、投稿編集コミュニティ、コミュニティ内トピックなどは実際には投稿IDで表示されるように変更が必要（現在は仮でpost-detailなどのページを表示）<br>
