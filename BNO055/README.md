# BNO055

## データシート
https://www.bosch-sensortec.com/media/boschsensortec/downloads/datasheets/bst-bno055-ds000.pdf

## プログラムの参考サイト
https://www.youtube.com/watch?v=NUAeER-1e4c

## 使用したライブラリ
https://github.com/ivyknob/bno055_stm32

## デバック用のうさぎ
### 参考サイト
https://homemadegarbage.com/bno055-01

### 沼ったところ
- processingのライブラリの置き場は`~/Documents/Processing/libraries/`. \
このディレクトリにライブラリのソースコードをおく.おいた後はprocessingを再起動しないと反映されない.
- IDE側でシリアル通信をキャプチャしていると, うさぎがうまく動かないから, キャプチャは停止しておく.