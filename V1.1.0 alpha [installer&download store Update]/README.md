# このフォルダは？
このフォルダはV1.1.0アップデートのα版です<br>
このフォルダ内のプログラムは別に実行してもいいですが、責任は全く負いません（サポート対象外です）<br>
>あと、内容は全く変更していないので中身はV1.0.1のままです<br>
>zipファイルのほうはインストーラー作成時のソースなので中身自体はexeのアイコンが変更されたV1.0.1と変わりません

> [!TIP]
> インストーラー内は仕様上全て英語です。

## 実行環境
インストーラーはどうやら互換性ツールだとWindows 8以降で実行できるようです

## 生成されるフォルダなど
### フォルダ
* 初期設定では`C:\Users\%USERNAME%\AppData\Local\Programs`にフォルダ生成すると思います<br>
* 実行するとこれまでのバージョンと同様、`C:\Users\%USERNAME%\AppData\Roaming`にもフォルダ生成します<br>
* タスクバーに設定していると`C:\Users\%USERNAME%\AppData\Roaming\Microsoft\Internet Explorer\Quick Launch\User Pinned\TaskBar\Tombstones\`にショートカットが追加されます
### レジストリ
> [!CAUTION]
> レジストリはあんまり操作しないほうがいいと思います<br>
>アンインストーラー使った方がいいと思います

* Geek Uninstallerによると`コンピューター\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\AppListBackup\ListOfEventDrivenBackedUpTiles_**********\ListOfEventDrivenBackedUpTiles_**********`に作成するようです


## アンインストールについて
アンインストールはフリーソフトとかのアンインストーラー使った方がいいと思います（多分標準のだとレジストリとかファイルとか残ります）<br>
個人的にはGeek uninstallerおすすめです（動作が軽い）



