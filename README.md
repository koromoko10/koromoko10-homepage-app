# koromoko10-homepage-app
自分でいうのもあれだけど世界一いらないソフトだと思う。

## ダウンロード
| プラットフォーム  | [V1.1.1](https://github.com/koromoko10/koromoko10-homepage-app/tree/main/V1.1.1%20%5Bpatch%5D) | [V1.1.0](https://github.com/koromoko10/koromoko10-homepage-app/releases/tag/V1.1.0) | [V1.0.1](https://github.com/koromoko10/koromoko10-homepage-app/releases/tag/V1.0.1_Win-Update) | [V1.0.0](https://github.com/koromoko10/koromoko10-homepage-app/tree/main/V1.0.0) |
|:-----|:-----|:-----|:-----|:-----|
| Windows(ポータブル版) | [.json (patch)](https://github.com/koromoko10/koromoko10-homepage-app/blob/main/V1.1.1%20%5Bpatch%5D/project.json) , [.zip (full)](https://github.com/koromoko10/koromoko10-homepage-app/blob/main/V1.1.1%20%5Bpatch%5D/koromoko10-homepage-app.zip) | [.zip](https://github.com/koromoko10/koromoko10-homepage-app/releases/download/V1.1.0/Win.V1.1.0-koromoko10-homepage-app.zip) | [.zip](https://github.com/koromoko10/koromoko10-homepage-app/releases/download/V1.0.1_Win-Update/Win_koromoko-homepage-app.zip) | [.zip](https://github.com/koromoko10/koromoko10-homepage-app/blob/main/V1.0.0/V1.0.0%20Win_koromoko10%E3%83%9B%E3%83%BC%E3%83%A0%E3%83%9A%E3%83%BC%E3%82%B8%E3%82%A2%E3%83%97%E3%83%AA%20%5B%E4%B8%96%E7%95%8C%E4%B8%80%E3%81%84%E3%82%89%E3%81%AA%E3%81%84%E3%82%BD%E3%83%95%E3%83%88%5D.zip) |
| Windows(インストーラー版) | N/A | [.exe](https://github.com/koromoko10/koromoko10-homepage-app/releases/download/V1.1.0/Win.V1.1.0-koromoko10-homepage-app.Setup.exe) | N/A | N/A |
| Mac | N/A | [.zip](https://github.com/koromoko10/koromoko10-homepage-app/releases/download/V1.1.0/Mac.V1.1.0-koromoko10-homepage-app.zip) | N/A | [.zip](https://github.com/koromoko10/koromoko10-homepage-app/blob/main/V1.0.0/V1.0.0%20Mac_koromoko10%E3%83%9B%E3%83%BC%E3%83%A0%E3%83%9A%E3%83%BC%E3%82%B8%E3%82%A2%E3%83%97%E3%83%AA%20%5B%E4%B8%96%E7%95%8C%E4%B8%80%E3%81%84%E3%82%89%E3%81%AA%E3%81%84%E3%82%BD%E3%83%95%E3%83%88%5D%20Mac%E7%89%88.zip) |
| Linux | N/A | [.zip](https://github.com/koromoko10/koromoko10-homepage-app/releases/download/V1.1.0/Linux.V1.1.0-koromoko10-homepage-app.zip) | N/A | [.zip](https://github.com/koromoko10/koromoko10-homepage-app/blob/main/V1.0.0/V1.0.0%20Linux_koromoko10%E3%83%9B%E3%83%BC%E3%83%A0%E3%83%9A%E3%83%BC%E3%82%B8%E3%82%A2%E3%83%97%E3%83%AA%20%5B%E4%B8%96%E7%95%8C%E4%B8%80%E3%81%84%E3%82%89%E3%81%AA%E3%81%84%E3%82%BD%E3%83%95%E3%83%88%5D%20Linux%E7%89%88.zip) |
| Android | N/A | N/A | N/A | [.apk](https://github.com/koromoko10/koromoko10-homepage-app/blob/main/V1.0.0/V1.0.0%20Android_20240107221116-app-debug.apk) |

## 起動方法
1.zipファイルを展開する（7-zipおすすめ）

2.**Linux版**に関しては`start.sh`で起動するハズ

## ユーザーデータの初期化
### Windowsポータブル版
Electronソフトなので初期化したい場合は`c:\Users\user\Appdata\Local`か`Roaming`かのどちらかに**Win_koromoko-homepage-app**みたいな感じのフォルダがあるのでそれ削除したらいいです<br>
おそらく起動時に作ってるフォルダはそれだけです<br>
### MacOS版
私はMacを持っていないので詳しく分かりませんが、Electronソフトなので `~/Library/Application Support/` 以降に **Mac_koromoko-homepage-app** みたいな感じのフォルダがあるのでそれを削除したらいいです<br>
おそらく起動時に作ってるフォルダはそれだけです<br>
## 動作確認済み
* Windows版--- ***Windows 11 Pro*** で実機確認済み
  * 互換性モード上だとWindows XP (SP2)から動作できるっぽいですが、<br>
  大体 ***Windows 7/8/10/11*** ぐらいだと思います
* Android版--- ***Walkman NW-A306***で実機確認済み<br>
実機動作といってもスマホではないので実質動作確認できてません
## 文字が表示されない(V1.1.0以降)
 `Arial` フォントが入っている必要があります（Windows標準・Mac標準であるはず）

## 最後に
ちなみにこのソフト実際はElectronのテストで作っただけ()
