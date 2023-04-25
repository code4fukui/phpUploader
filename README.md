# phpUploader with key

サーバーに設置するだけで使える簡易PHPアップローダー

- UPLOADキーを知る人のみアップロードできます
- アップロードする際にDELキーを設定できます

## Requirement

- PHP Version 5.3.3+
- SQLite (PHPにバンドルされたもので可、一部の環境によってはphp○-sqliteのインストールが必要です。)

## Usage

- config/config.php 編集（必須: master, uploadkey）

```sh
php -S 127.0.0.1:8888
```

## Files

- DBファイル 既定値 ./db/uploader.db
- アップロードファイル 既定値 ./data/*

## Licence

Code for FUKUI released under the MIT license

- original license

Copyright (c) 2017 shimosyan
Released under the MIT license
<https://github.com/shimosyan/phpUploader/blob/master/MIT-LICENSE.txt>
