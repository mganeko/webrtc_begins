# Simple Mosic Background Camera / 簡易背景ぼかしカメラ

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
- [ ] 見た目のスリム化 (余計なものは非表示、offScreenCanvas)
  - [ ] video非表示 (display:none)
  - [ ] canvas非表示 (display:none)
  - [ ] workCanvas は offScreenCanvas
  
