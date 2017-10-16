# ラズパイマウスで演奏

## 使い方
演奏させたいmidiファイルを用意し、midi再生ソフトなどを使用して、再生したいチャンネルを確認します。
(ラズパイマウスで再生可能なチャンネルは2つまでです)

チャンネルの確認が出来たら、以下のように実行します。
```
$ ./midi2pim.sh [midiファイル] [右車輪用チャンネル] [左車輪用チャンネル] [オクターブ]
```
```
# サンプル
$ ./midi2pim.sh aaa.mid 0 1 1
```
※オクターブの指定は倍率になっています。
例) 2の場合　➡　オクターブが1上がる。
例) 3の場合　➡  オクターブが2上がる。

