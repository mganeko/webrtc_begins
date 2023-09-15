# Simple Mosic Background Camera / 簡易背景ぼかしカメラ

Canvasを使った簡易背景ぼかしカメラの実験

## コード

- camera_crop.html … カメラを丸く切り取る
- background_mosaic.html … 背景を簡易ぼかし
- crop_mosaic.html … カメラ切り抜きと背景ぼかしの合成
- crop_mosaic_slim.html … 余計な要素を隠してすっきりさせたもの

## 使い方

- ブラウザで https://mganeko.github.io/webrtc_begins/ を開く
- 希望のリンクをクリックする
- ボタンの説明
  - [Start Video]ボタン ... カメラ映像を取得、Video要素で再生
  - [Stop Vidoe]ボタン ... カメラ映像を停止
  - [Start Draw]ボタン ... Canvasへの連続描画を開始
  - [Stop Draw]ボタン ... Canvasへの連続描画を停止
  - [Start Capture Canvas]ボタン ... Canvasから映像を取得、Video要素で再生
  - [Stop Caputure Canvas]ボタン ... Canvasからの映像を停止
  - [Start All]ボタン ... カメラ映像取得、Canvasへの描画、Canvasからの映像取得を順番に開始
  - [Stop All]ボタン ... 全て停止


## ライセンス

MITライセンス


## ToDo

- [x] cameraを顔の周辺だけ切り取る
- [x] 映像全体をぼかす
- [ ] 2つを合わせたもの
  - [x] 背景ぼかし
  - [ ] 顔ぼかし
    - [x] シンプル（一瞬、顔も描画する）
    - [ ] 丁寧 （一瞬たりとも、顔を描画しない）
  - [x] localVideo 隠す (display:none)
  - [x] OffScreenCanvas
  - [-] captureStream() from OffScreenCanvas --> NG
- [x] 見た目のスリム化 (余計なものは非表示、offScreenCanvas)
  - [x] video非表示 (display:none)
  - [x] canvas非表示 (display:none)
  - [x] workCanvas は offScreenCanvas
- [x] README
- [x] index
- [ ] P2P
  - [ ] Sender - Receiver Skyway


