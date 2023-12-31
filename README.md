# gr_keycap

カラムスタッガードや格子配列のキーボードでの打ちやすさを意識したキーキャップセットです。

## exportフォルダ

汎用的な3Dファイルに書き出したモデルです。
3Dプリンタでそのまま出力する際はこちらを使用してください。

STL形式だとファイルサイズが大きくなりすぎるので、3mf形式で保存しています。  
Windowsの場合、3D Builderを使うことでSTL形式へ変換できます。

- ブランクキーのセット
- 左手用キーセット
- 右手用キーセット
- 日本語配列用キーセット

## srcフォルダ

ファイルサイズが大きすぎるため、releaseにのみ含まれています。

3Dデータ出力前のCADファイルです。FreeCADで自由に編集できます。

文字の刻印に使用しているフォントは [Kumbh Sans](https://fonts.google.com/specimen/Kumbh+Sans)です。  
モデルを修正した場合は `C:/font/font.ttf` に置いたフォントファイルが使われます。

軸の太さについてはパラメータ化しているので、 FreeCAD内の `Spreadsheet` の値を変更することで一括変更できます。  
