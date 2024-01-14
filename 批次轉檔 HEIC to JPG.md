# HEIC to JPG

MacOS command 批次將 HEIC 轉換成 JPG

// 就是懶，想直接把照片扔進影片剪輯軟體裡 ╮(╯▽╰)╭

## Install

https://formulae.brew.sh/formula/imagemagick

```
brew install imagemagick
```

## Convert

```
magick mogrify -monitor -format JPG *.HEIC
```
