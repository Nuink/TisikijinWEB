# 知識人WEB

wip is here https://nuink.github.io/TisikijinWEB/

## changelog
### 9/20 made title-bg 'fixed' <br>
・TIGWEBの背景オブジェクトが固定されてるのが良さげだったのでこっちにも適用した<br>
### 9/19 new user comment implemented <br>
・一般の人の視点を投稿、表示できるように　教員のは紫色に対してこれはオレンジ色<br>
  -視点を表示する枠の最下部に投稿ボタンを表示->投稿フォームの表示->正常に入力されていれば確認画面->投稿完了<br>
・視点を表示する枠をスクロールするように　どんなに要素が長くなってもheightは一定にして画面からはみ出さないようにするため<br>
・視点を表示する枠の最上部にそのトリガーの名前を表示<br>
・1枚目の中央柱、左下自転車群にトリガーを設定<br>


## Todo
<s>like</s><br>
<s>comment</s><br>
more flexible for any window sizes<br>
for mobilephone<br>
もろもろ文の見直し<br>
視点ボックスを画面内に確定で収まるように表示させる<br>


## 不具合
・Likeをつけたあと視点のボックス閉じてもう一回開くとLikeの状態が失われたまま数は増えてるよ<br>
・DB(視点の情報)を読み込む前に写真を開いて視点を覗こうとできちゃう トリガーが失われてる　なんとなく解決できそう
