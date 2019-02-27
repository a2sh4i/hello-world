Lubuntu18.04 LTS インストール手順


## １．Live USBの作成 

- lubuntu18.04本体をダウンロード（リンク先のページを下にスクロールすると18.04があります）[Lubuntu](https://lubuntu.me/downloads/)  
- 次にLiveUSBを作成するためのアプリ（balenaEtcher) をダウンロード 
　 [balenaEtcher](https://www.balena.io/etcher/)
  - balenaEtcherを起動、`Select image`でLubuntu18.04のイメージを選択
  - `Flash`で実行
***

## 2．インストール
- 2-1 USBからインストールするにはUSB起動させる必要があります。 
  - 2-1-1 macの場合はオプションキーを押しながら起動でLubuntuを選択、Lubuntuが表示されていない場合はEFI bootを選択。
  - 2-1-2 Windowsはだいたい*FN2*でBIOSが起動しますが、各社で違う場合もあるので[**こちら**](https://freesoft.tvbok.com/tips/peripherals/bios_boot_fn-key_list.html)を参照してください。
- 2-2 USBから起動出来たら言語タイプを選びます。  
日本語の場合は「日本語」、英語で使う場合は「英語」を選択。  
- 2-3 キーボードレイアウト  
日本語配列で使う場合`日本語/日本語`






- インストールのタイプを選択します  
1. インストールせずにLubuntuを試す（こちらは文章の通りインストールはしないでお試しのようなものです。） 
1. Lubuntuをインストール（デュアルブートをする場合やパーティションなどの割当等、細かい設定を行いインストール出来ます。）
1. ディスクを消去してインストール （以前のOSを消去してLubuntuのみインストール出来ます。） 
## ***※ディスクの中身を全て消去してインストールを行うので、重要なデータがある場合要注意*** 
- windowsやmacが必要ない、軽い動作のOSにしたいという方はディスク消去インストールを推奨します。  
ですが、もしもの為にリカバリーメディアを作成しておく事をおすすめします。  
リカバリーメディア作成手順リンク [win10](　http://shuttle-japan.jp/wp-content/uploads/2018/05/manual_recovery_win10.pdf) [mac](https://support.apple.com/ja-jp/HT201372)

- 