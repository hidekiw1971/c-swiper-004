# compornent（共通部品）

## イメージ画像
<img width="410" alt="image" src="https://user-images.githubusercontent.com/99580997/162555278-209ae869-3626-4aa6-a754-1b5d7760596c.png">
<img width="776" alt="image" src="https://user-images.githubusercontent.com/99580997/162555288-4b0eb6d2-d184-4cf4-91fc-225dbcd04482.png">


## 概要
- `html`
- `<div class="box__swiper">` ←`swiper`の外側を`box`で囲み、`position: relative;`を設定する。
- `<!-- Slider main container -->`
- `<div class="swiper">`
- `<!-- Additional required wrapper -->`
- `<div class="swiper-wrapper">`
- `<!-- Slides -->`
- `<div class="swiper-slide"><img src="images/mameta1.JPG" alt=""></div>`
- `<div class="swiper-slide"><img src="images/mameta2.JPG" alt=""></div>`
- `<div class="swiper-slide"><img src="images/mameta3.JPG" alt=""></div>`
- `</div>`
- `</div>`
- `<!-- If we need pagination -->`
- `<div class="swiper-pagination"></div>` ←`swiper`のboxから`swiper-pagination`を外に出す。（`box__swiper`のbox内に設置し、`position: absolute;`を設定する。）
- `</div>`
- 
- css
- `.swiper-pagination {`
- `position: absolute;`
- `text-align: center;`
- `transition: 0.3s opacity;`
- `transform: translate3d(0, 35px, 0);`　←`translate3d(0, 0, 0)`を`translate3d(0, 35px, 0)`に調整した。
- `z-index: 10;`


- https://www.notion.so/000_web-component-index-c4b399010bf342e9b4e2ed516cf9c730

## 仕様

- スマホファースト
- rem 記述
- ルートフォントを vw で設定していることから PC サイズのレイアウトをタブレットで表示させることが出来ます（rem で書いた場合のみ）。
- xxx

## 注意事項

- xxx

## 使い方

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> box をコピペ。

## w3c html チェック結果

- https://validator.w3.org/nu/
- <img width="744" alt="image" src="https://user-images.githubusercontent.com/99580997/162555300-69cd96a2-19d0-47bb-9aee-ef2fa269024f.png">


## w3c css チェック結果

- https://jigsaw.w3.org/css-validator/
- <img width="942" alt="image" src="https://user-images.githubusercontent.com/99580997/162555321-bdab6ae1-8606-47ff-aaa9-46ae1871fcc2.png">


## portfolio url:

- https://c-0048.wtb.cfbx.jp/

## 参考にしたサイト

- swiperjs.com
- https://swiperjs.com/

## 更新履歴

- 2022/4/9 完成（意図的に配置を右側にしてます。swiper の pagination も swiper 直下で中央寄せできるのを確認。）
- 2022/4/9 swiper(dl、pagination を外側に設置が上手く行って無かったので再作成（指定の幅で中央に寄らなかったので調整）)

## 環境・使い方

- ダウンロードしたフォルダを開く。
- ターミナルを開き、 npm i とコマンドを入力する。
- node_modules と package-lock.json が生成されるのを確認する。
- 「 npx gulp 」とコマンドを入力すると動き出します。

## 備考
