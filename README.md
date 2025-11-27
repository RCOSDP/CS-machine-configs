# mdxにTLJHをインストールする

以下の「launch binder」ボタンをクリックすると、Jupyter Notebook が起動します。

[![Binder](https://binder.cs.rcos.nii.ac.jp/badge_logo.svg)](https://binder.cs.rcos.nii.ac.jp/v2/gh/RCOSDP/CS-machine-configs.git/develop?filepath=tljh_ansible_deployment.ipynb)

Jupyter Notebook の指示に従って、インストール作業を進めてください。

## 既知の問題

* パスワード／パスフレーズ入力時にファイルブラウザの一覧が消える
  * 対策1: シークレットウィンドウで実行してください。（推奨）
  * 対策2: 対象となる Cookie を削除してください。
  * 対策3: タブを複製すると、ファイルブラウザが表示された状態で複製されるので、そこでファイル操作をしてください。

## よくある質問

* Let's Encrypt で証明書が発行／更新されない
  * Jupyter Notebook の指示に従って mdx の ACL の設定がされているかご確認ください。
  * メールアドレスが有効なものかご確認ください。
  * 独自にドメインをお持ちで証明書が発行できる方はそちらを使うことをお勧めします。
