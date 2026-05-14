# PerlinNoise.js

PerlinNoise.jsは、1D、2D、3D実装向けのPerlinノイズジェネレータのコレクションです。

## デモ
- [PerlinNoise1D DEMO](https://code4fukui.github.io/PerlinNoise/1d.html)
- [PerlinNoise2D DEMO](https://code4fukui.github.io/PerlinNoise/2d.html)
- [PerlinNoise3D DEMO](https://code4fukui.github.io/PerlinNoise/3d.html)

## 特徴
- 1D、2D、3D用のPerlinノイズジェネレータ
- 滑らかなノイズ生成
- カスタマイズ可能なパラメータ

## 要件
なし

## 使い方
Perlinノイズジェネレータを使用するには、それぞれのクラスをインポートします：

```javascript
import { PerlinNoise1D } from './PerlinNoise1D.js';
import { PerlinNoise2D } from './PerlinNoise2D.js';
import { PerlinNoise3D } from './PerlinNoise3D.js';
```

その後、目的のジェネレータのインスタンスを作成し、`noise()`メソッドを使用してPerlinノイズを生成します。

## ライセンス
MIT License — 詳細は[LICENSE](LICENSE)を参照してください。
