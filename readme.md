# これなに？
**MinManager は 無料 の 鉱物標本管理アプリケーション です**  
**ラベル作成**や**画像管理**など、この趣味に特化して作られています  
また、インターネットに接続していない環境でも動作します、外部と通信しないので安心です  

最新バージョンのZIPファイルはここからダウンロードできます 
**[ (64bit版) ](https://github.com/nokatsu/MinManager/releases/download/v1.2.5/MinManager-v1.2.5-win-x64.zip)**
**[ (32bit版) ](https://github.com/nokatsu/MinManager/releases/download/v1.2.5/MinManager-v1.2.5-win-x86.zip)**  
使用方法については本ドキュメントをご参照ください

![demo](https://raw.githubusercontent.com/wiki/nokatsu/MinManager/images/MineralManager2.gif)

※**Windowsのみ**対応です、mac対応はできませんので悪しからずご了承ください  
※初回のみ起動が遅くなります、申し訳ありませんが気長にお待ちください

# 機能紹介
## 画像管理
画像を鉱物情報と一緒に管理できます  
ドラッグ & ドロップ操作で簡単！閲覧もパン & ズームに対応です  
![Photo](https://raw.githubusercontent.com/wiki/nokatsu/MinManager/images/Photo.gif)  
## 簡単ラベル作成
この趣味では必須となるラベル作成もワンクリック！  
豊富なテンプレートからデザインを選べます  
![Label](https://raw.githubusercontent.com/wiki/nokatsu/MinManager/images/Label.gif)  
![LabelTempletes](https://raw.githubusercontent.com/wiki/nokatsu/MinManager/images/LabelTemplates.jpg)

### オリジナルラベル もつくれます！
好きな画像を読み込ませて自分だけのオリジナルラベルをつくれます  
表示項目やフォントも設定可能です  
![UserLabel](https://raw.githubusercontent.com/wiki/nokatsu/MinManager/images/UserLabel.gif)
## かゆい所に手が届く便利機能たち
### オートコンプリート
産地の綴りは覚えられない！過去に入力した情報を自動でサジェストしてくれます  
![AutoComplete](https://raw.githubusercontent.com/wiki/nokatsu/MinManager/images/AutoComplete.gif)
### タグ機能
色、結晶系、雰囲気、等々 自分の好きな切り口でコレクションをジャンル分けできます  
もちろん検索可能です  
![Tag](https://raw.githubusercontent.com/wiki/nokatsu/MinManager/images/Tag.gif)
### 地味に作りこまれた検索機能
検索は入力と同時に動作するインクリメンタルサーチを採用しています(前後一致の曖昧検索)  
スペースを使って複数のキーワードを指定可能なので共生標本も簡単に検索できます(ex. SmokyQuartz Amazonite)  
また、よく使うキーワードを保存して再検索することもできます  
![UserLabel](https://raw.githubusercontent.com/wiki/nokatsu/MinManager/images/Search.gif)
### Excelからの移行支援
今から１件ずつちまちま登録なんてやってられないよ…、なんて方も安心です  
同梱の [omake](#ダウンロード方法) を使えばMinManager用のデータを一括で作成できます
### レポート
コレクションの構成比や推移を表示できます  
この趣味にいくら使ったかもすぐわかります…  
![Report](https://raw.githubusercontent.com/wiki/nokatsu/MinManager/images/Report.jpg)  

## オンライン機能 (※登録制)
MinManagerで登録した鉱物情報をオンライン上で共有できます  
公開範囲が設定可能なので仲間内での **情報共有** や **コレクション交換** などにお役立てください  
※開発者(@no_katsu)は本アプリケーション使用によって生じたいかなる損害に関して、一切の責任を負いかねます

# 履歴
* **v1.2.5 (Latest release)**
    * (BUG FIX)バグ修正
        * (致命バグ)ラベル作成に失敗した際、アプリケーションがハングする問題を修正
* **v1.2.4**
    * (NEW)新機能
        * 検索機能拡充
            * 検索キーワードの保存機能を実装
            * 複数キーワードの指定に対応
                * スペース区切りでAnd検索
            * 検索件数を表示するように変更
    * (BUG FIX)バグ修正
        * カスタムラベル画面でSignetureを非表示にした際、テキストボックスが非活性にならない問題を修正
    * (OTHER)その他
        * Tag選択画面のデザインをFilterChipに変更
        * ラベル作成処理を非同期化
        * 起動時に設定ファイルが存在しなかった場合、異常終了とせずに空ファイルを生成するように変更
* **v1.2.3**
    * (OTHER)その他
        * ラベルデザインを2件追加(PhotoLabel3, MonotoneLabel)
        * 本ドキュメント(readme)を加筆修正
        
[全リリース履歴はこちら](https://github.com/nokatsu/MinManager/releases)

# ダウンロード / アップデート方法
## ダウンロード方法
下記リンクの赤枠部分をクリックしてDLしてください  
(x64が64bit版, x86が32bit版です)  
https://github.com/nokatsu/MinManager/releases/tag/v1.2.5
![dl](https://raw.githubusercontent.com/wiki/nokatsu/MinManager/images/dl.jpg)

## アップデート方法
すでに過去Versionをご使用の方はZIPファイル内 **[MinManager.exe] のみを既存フォルダに上書してください**  
<font color="Tomato">**同梱の [DB] フォルダをコピーすると今までに登録されたデータが上書されてしまいます**</font>  

# 使い方
## 対応OS
* Windowsのみ対応です
    * 他OS(macなど)への対応予定はありません(WPFなのでできません)
## 起動方法
* 解凍したフォルダ内にあるMinManager.exeをダブルクリックしてください
    * 初回のみ起動が遅くなります、申し訳ありませんが気長にお待ちください  
* 解凍したフォルダ内にあるDBフォルダは削除したり移動・改変を行わないでください  
(MinManager.exeと同一フォルダに存在することが求められますのでデスクトップなどに配置したい場合は、MinManager.exeのショートカットを作成してください)
## 操作方法
* 検索
    * メイン画面の上部 [keyword] に検索したい文字を入力してください
    * 入力と同時に検索処理が動作します(前後部分一致、スペース区切りでAnd検索)
    * 検索処理はメイン画面の一覧表に表示されているすべての列を対象に動作します
* 追加
    * メイン画面下部 [Add Mineral]ボタンを押下してください  
    * 詳細画面が開きますので、必要項目を入力して [Save] ボタンを押下してください
        * [MainMineral] は必須項目となっています
* 更新
    * メイン画面中部の一覧表より、対象としたい行をダブルクリックしてください
        * 複数行の更新機能は実装されていません
    * 詳細画面が開きますので、必要項目を修正して [Save] ボタンを押下してください
        * [MainMineral] は必須項目となっています
* 削除
    * メイン画面中部の一覧表より、対象としたい行を選択して、メイン画面下部 [Delete Mineral] ボタンを押下してください
        * 複数行の削除機能に対応しています
        * 確認ダイアログが表示されますが、一度削除した行は復活しないのでご注意ください
* Tag編集
    * メイン画面上部の [Edit Tag] ボタンを押下してください
    * Tag編集画面が開き、現在登録されているTag一覧が表示されます
        * [Refference] 列は現在そのTagが使用されている数を表しています
    * Tagの新規追加を行いたい場合はTag編集画面下部の [Add] ボタンを押下してください  
    一覧表の最終行に新規行が作成されます  
    * Tag名の編集を行いたい場合はTag編集画面の一覧表より、対象としたい行をダブルクリックしてください
    * Tagを削除したい場合は対象としたい行を選択の上、 [Delete] ボタンを押下してください
        * 確認ダイアログが表示されますが、一度削除した行は復活しないのでご注意ください
        * Tagを削除した場合、各鉱物に紐づいていたそのTag情報も合わせて削除されます
* ラベル作成
    * メイン画面中部の一覧表より、対象としたい行を選択の上、画面上部の [Label Create] ボタンを押下してください
        * 複数行の選択に対応しています
    * ラベル選択画面が開き、デザインテンプレートの一覧が表示されます
    * ラベルに記載したい署名情報を [Signeture] に入力して画面下部 [Create] ボタンを押下してください
        * ライセンスの都合で一度に作成できるラベルは1ページまでとなります  
        それ以上は複数回に分けて作成を行ってください  
        1枚を超えた場合はエラーとなります
    * カスタムラベル
        * ラベル選択画面上部の[Custom Label]ボタンを押下するとアップロード画面が開きます
        * 任意の画像をドラッグ&ドロップしてラベル枠を設定してください
            * アップロードする画像は透過pngをおすすめします
            * 画像によってはデザインと文字が被ったり枠からはみ出ることがありますので承知おきください
            * 文字数によってラベルの縦幅は自動拡張されます  
            それに合わせてアップロードした画像のアスペクト比も伸長します
        * ラベルに表示したい項目を選択し、画面下部 [Create] ボタンを押下してください
* 画像閲覧
    * マウスホイールで縮小 / 拡大が可能です
    * ドラッグで画像位置の変更が可能です
    * 右クリックまたは [Esc] キーの押下で元の画像サイズに戻ります
* レポート表示
    * メイン画面上部の [View Reports] ボタンを押下してください
    * レポート閲覧画面が開き、登録されているデータ上最も古い購入日付から現在までの集計レポートが表示されます
        * レポート閲覧画面上部の3つの円グラフはそれぞれ鉱物、国、値段の構成比率を表します
        * レポート閲覧画面下部の積み上げグラフは時系列ごとの鉱物情報を表します
            * 積み上げグラフは、対象とする期間(月単位)を設定可能です。設定後 [Redraw] ボタンを押下することで適用されます
                * [Including NULL Date Data] チェックボックスをオフにすると購入日が設定されていないデータを集計の対象外とすることができます
            * 積み上げグラフと連動して設定された期間に購入した鉱物の合計金額が表示されます
                * 購入日が設定されていないデータは期間の最初に計上されます

# 注意点
* 開発者(@no_katsu)は動作保証をしません、また本アプリケーション使用によって生じたいかなる損害に関して、一切の責任を負いかねます
* 登録した画像データはDBフォルダにコピーされるので大容量データを取り扱う場合にはドライブの残容量にご注意ください

# おねがい
* 要望があったり、バグを踏んだら@no_katsuまでご連絡ください
* おしゃれ CSS を書ける方はぜひ @no_katsu にお送りください、ラベルテンプレートに採用させていただきます
    * LabelデザインはCSSで定義しており、コード内でHTMLを生成 → PDF化しています

# バックアップについて
鉱物やTagのデータはJSON形式でDBフォルダ内に保存されますので定期的にバックアップをお勧めします  

# コピーライト
Copyright 2019, ([@no_katsu](https://twitter.com/#!/no_katsu "twitter@no_katsu")).  

* 再配布およびそれに類する行為を禁止します
    * 正規のダウンロードURLを告知する行為は含みません、本アプリケーションや実行ファイルを直接再配布する行為を指します
    * ユーザ間の設定ファイルの共有を制限しません
* リバースエンジニアリングやデコンパイルおよびそれに類する行為を禁止します
* 改変行為を禁止します
* 商用利用を禁止します
    * 有償無償を問わず本アプリケーションや実行ファイルの販売行為を指します
	* 業務での利用を制限しません  

# 利用ライブラリ
* AngleSharp(https://anglesharp.github.io/)
* SelectPdf(https://selectpdf.com/community-edition/)
* Dropbox Inc.(https://www.dropbox.com/developers)
* James Willock/Mulholland Software Ltd(http://materialdesigninxaml.net/)
* Beto Rodriguez(http://lvcharts.net/)