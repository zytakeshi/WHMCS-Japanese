WHMCS8の日本語の言語ファイルです。

英語版の言語ファイルをもとに、Google翻訳を使って翻訳し、構文エラーを手動で直してようやく作成しました。

使用方法について

下記whmcsをあなたの環境でWHMCSがインストールされているパスに直してください。

```
cd /whmcs/lang/
wget https://raw.githubusercontent.com/zytakeshi/WHMCS-Japanese/main/japanese.php
cd /whmcs/admin/lang
wget https://raw.githubusercontent.com/zytakeshi/WHMCS-Japanese/main/admin/japanese.php
```
サーバーで上記のコマンドを入力してください。

クライアント用は `/whmcs/lang/`、管理画面用は `/whmcs/admin/lang/` に配置します。管理ディレクトリ名を変更している場合は `admin` を実際の名前に置き換えてください。クライアント用の配置先は [WHMCS公式ドキュメント](https://developers.whmcs.com/languages/adding-a-language/) を参照してください。

注意：ご使用前には必ずバックアップしてください、何か問題が発生した場合には、ファイルを削除すればサイトが直ります。
