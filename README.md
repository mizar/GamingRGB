# GamingRGB

[sh1mc@BOOTH](https://sh1mc.booth.pm/) さんにて配布が行われているUnity/VRChatシェーダー

- [【無料】ゲーミング発光シェーダー Gaming RGB](https://sh1mc.booth.pm/items/2296573)
- [【無料】ゲーミング発光シェーダー Gaming RGB Line](https://booth.pm/ja/items/2303369)

および、上記の改変版(Cutoff shader)です。

配布元のシェーダーからは、テクスチャが透過になっている部分は発光しないよう改変を行っています。

## 使い方 (Usage)

1. 同梱の以下のshaderを Assets のお好きな場所にインポート
  - [./GamingRGB/GamingRGB.shader](./GamingRGB/GamingRGB.shader)
  - [./GamingRGB/GamingRGBCutoff.shader](./GamingRGB/GamingRGBCutoff.shader)
  - [./GamingRGBLine/GamingRGBLine.shader](./GamingRGBLine/GamingRGBLine.shader)
  - [./GamingRGBLine/GamingRGBLineCutoff.shader](./GamingRGBLine/GamingRGBLineCutoff.shader)
2. 適用したいマテリアルのシェーダーとして `Custom/GamingRGBCutoff`, `Custom/GamingRGBLineCutoff` を選択 (テクスチャの透過が必要ない場合はオリジナルの `Custom/GamingRGB`, `Custom/GamingRGBLine` を選択)
3. 光ります

## License

[CC0 1.0 Universal (CC0 1.0)](https://creativecommons.org/publicdomain/zero/1.0/) / [CC0 1.0 全世界 (CC0 1.0)](https://creativecommons.org/publicdomain/zero/1.0/deed.ja).

## 免責

本データを使用したことによって発生したいかなる損害についても、本データの制作者は一切の責任を負いません。
