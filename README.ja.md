
# FreeStyle Libre 3 patch

このテキストは自動翻訳されています。最新のアップデートについては、英語版またはドイツ語版をお読みください。

<a href="README.md"><img alt="EN" src="https://user-images.githubusercontent.com/65506676/190852356-073bf576-6e3a-45f3-a658-be1c4a8d7286.png" width="18px" /> 英語版Readme</a>をご覧ください。

Libre 3 の開発を推進するための公開レポです。このレポは、Libre 3 に関する情報を交換するために使われるべきものです。目標は、復号化と Xdrip 用のインターフェースの作成です。

## 免責事項

github.comの情報およびアプリの使用は、あなた自身のリスクで、いかなる種類の保証や正式なサポートなしに行われます。

## Juggluco ソリューション

jkaltes](http://jkaltes.byethost16.com/)に大感謝です。新しい FSTL3 パッチ](http://jkaltes.byethost16.com/Juggluco/libre3/) を使って。
ルートアクセスを必要とせず、Xdripと完全に統合されたオフラインのソリューションがついに登場しました！手順はこちら。[Jugglucoを使ったLibre3パッチの手順](./Juggluco-solution/instructions/ja/instructions.md). または、[ダウンロードリンク](./Juggluco-solution/versions/latest/Libre-3-patch.apk?raw=1)を使ってください。注意：このソリューションは、あなた自身のリスクで、いかなる種類の保証や正式なサポートがありません。このプロジェクトは、アボット社とは関係がなく、またアボット社によって承認されているわけではありません。

注意：私はJugglucoと最終的なLibre 3パッチの開発に関与していませんが、進行中のすべての開発作業を共有するのが大好きです。

## FSL 3 の他のソリューション (ルートまたはオンライン接続が必要)

- Free Three。オフラインの解決策 -> rootといくつかのノウハウが必要、またバージョン3.3.1までのリブレ3アプリにのみ対応。[リンク (ドイツ語)](https://insulinclub.de/index.php?thread/33795-free-three-ein-xposed-lsposed-modul-f%C3%BCr-libre-3-aktueller-wert-am-sperrbildschir/)
    ->最新版をダウンロードする。[リンク](https://mega.nz/file/H51h3ILS#65mfhvDvPbtnbdWSOeXHHNxABDD60nP7iODxaDN_QPk)
- LibrelinkからNightscoutへのサイドローディング。[Githubレポ](https://github.com/timoschlueter/nightscout-librelink-up)
- Linkupデータをダウンロードし、Xdripと共有するためのアプリ(LLU Client)（ソースはLibre 2）です。[リンク（ドイツ語）](https://insulinclub.de/index.php?thread/33987-llu-client/&postID=654144#post654144)
- LinkUpConnect](https://github.com/cmtjk/LinkUpConnect): LLU Clientの代替品で、Xdrip+でBGを通知として表示することができる。
- Web Follower](https://xdrip.readthedocs.io/en/latest/install/webfollower/): Xdrip+のナイトリービルドの機能 (キャリブレーションはできません)
- iOS向けに開発中。DiaBLE -> FSTL3の機能を活用しようとしている。[Githubレポ](https://github.com/gui-dos/DiaBLE)

## 現在の状況

復号化が壊れただけ :smiley:. AndroidとXdripで動作する、非Root化された携帯電話向けのソリューションがようやく登場しました。

## How to contribute

Libre 3 に関する有用な情報をお持ちの方は、[discussion tab](https://github.com/maheini/FreeStyle-Libre-3-patch/discussions) で共有してください。

## 暗号化に関する情報

libre 3 アプリについて、以下のことが分かっています。起動後、アプリに変更が加えられていないかチェックされます。そこでWhiteCryptionによるコード保護が行われています。

##WeAreNotWaiting
