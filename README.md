# ffmpegにlibaribcaptionをリンクするためのコードの差分

## 概要
ffmpegにlibaribcaptionをリンクする[patch](https://patchwork.ffmpeg.org/project/ffmpeg/list/?submitter=1420)が公開されています。
このpatchの内容を、kodiのffmpegバージョンに対応させた差分です。

## 適用方法
 - patchよりlibaribcaption.cを生成します。
 - mpegts、libaribcaptionの差分を当該ファイルに適用します。
 - 上記ファイル以外、残りのpatch内にある差分を手動で適用します。

## 対応バージョン
# ffmpeg-4.3.2-Matrix-19.2 (kodi v19.4用)

## 関連サイト
[add ARIB caption decoder using libaribcaption](https://patchwork.ffmpeg.org/project/ffmpeg/list/?submitter=1420)
[libaribcaption](https://github.com/xqq/libaribcaption)
