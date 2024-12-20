# ヘルプ

## 事前準備
本アプリとDAWの接続には[loopMIDI](https://www.tobias-erichsen.de/software/loopmidi.html)が必要です。以下の手順に従ってください：
1. loopMIDIを起動します。
2. MIDIポートを作成します。
3. 作成したMIDIポートをDAWに接続します。

## スキャン
アプリのスキャン機能を使用して、周辺のデバイスを検出します。以下の手順に従ってください：
1. アプリが起動すると自動的にスキャンが開始します。
2. スキャンは一定時間経過後に自動的に終了します。
3. スキャン終了後、表示されるスキャンボタンを押してスキャンを再開できます。

<img src="./../../img/スクリーンショット ScanButton.png" width="35%">

## MIDIポート選択
本アプリではMIDIポートの選択が可能です。以下の手順で行ってください：
1. デバイスリストから「MIDIポート選択」ボックスを開きます。
2. 使用するMIDIポートをリストから選択します。

<img src="./../../img/スクリーンショット MIDIPorts.png" width="35%">

## 接続
デバイスを接続するには、以下の手順を参考にしてください：
1. 「接続」ボタンをクリックします。
2. 接続が確立されると、状態が「接続済み」と表示されます。

<img src="./../../img/スクリーンショット Disconnected.png" width="15%">

<img src="./../../img/スクリーンショット Connected.png" width="15%">

## 自動接続
ピン止め機能を利用すると、自動接続が可能です。設定方法は以下の通りです：
1. 設定したいデバイスの「ピン止め」ボタンを押して、自動接続を有効にします。
2. アプリが起動している間はデバイスと自動的に接続します。
3. ピン止めされたデバイスはアプリに保存されます。ピンを外すと削除されます。

<img src="./../../img/スクリーンショット Pin.png" width="5%">

<img src="./../../img/スクリーンショット Pinned.png" width="5%">
