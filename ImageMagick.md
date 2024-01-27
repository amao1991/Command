# ImageMagick

https://imagemagick.org/index.php

圖檔批次處理系列

## Install

https://formulae.brew.sh/formula/imagemagick

```
brew install imagemagick
```

## HEIC to JPG

MacOS command 批次將 HEIC 轉換成 JPG

```
magick mogrify -monitor -format JPG *.HEIC
```

## Resize 

```
mogrify -resize 80% *.JPG
```
