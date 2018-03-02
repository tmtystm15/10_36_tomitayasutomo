
====

login.php
ログイン、新規ユーザー登録、ログインせずに使用の３行動

ログイン→ユーザー登録済み（gs_user_tableに登録済み）ユーザーはID/PASSの入力でログイン。
ID・PASSが一致した場合、select.phpに遷移し、情報一覧を表示。ログイン後は情報の新規登録、修正、削除が可能。
ID・PASSが一致しない場合はcant_login.phpでエラーメッセージを出しログイン画面に戻る。

新規登録→new_user.phpに遷移し、新規ユーザー登録行動。
登録ボタンでregistration.phpでdbのgs_user_tableに情報を追加。
追加後login.phpに戻ってログイン。

ログインせずに見るだけ→情報の新規登録、修正、削除不可の一覧画面（select2.php)に遷移。

index.php → 情報の新規登録
insert.php → 登録情報をdbに追加
delete.php → 削除
update.php → 情報の更新
logout.php → ログアウト

====

