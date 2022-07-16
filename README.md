# データベース及び演習　期末レポート
##車両見積もりサイト及び管理者用見積もり情報閲覧サイトシステム
phpとMySQL/MariaDBを用いて車両見積もりサイト及び管理者用見積もり情報閲覧サイトシステムを作成した
顧客に車両のオプション、顧客情報を入力してもらう。そうすることで管理者が顧客の選択した車両情報や個人情報を閲覧することが可能となる。

環境構築

## 使用したものとバージョン
| 使用したもの | Version|
| :------------| ---------: |
| PHP | 7.4.28 |
| XAMPP | 7.4.28-1 |
| MariaDB | 10.4.21 |
| Apache | 2.4.51 |

```sh
初めにxamppfilesのhtdogsの中にfinaldbを入れます。
```

完了したら

```sh
ユーザ名をfinal
データベースの名前をreport
パスワードをMahiro3054で設定してください
```

## テーブル
下記のテーブルをデータベースに読み込んでください。

```sh
車両別顧客情報　：　2CustomerInformation,2CustomerInformation3,2CustomerInformations,2CustomerInformationy
車両オプション選択　：　xgrade,3grade,sgrade,ygrade
ログイン用：　login
```

実装で使うファイルはstart.phpとsystemtop.phpの2種類です。
