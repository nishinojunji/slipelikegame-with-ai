# slipelikegame-with-ai
aiで書いてみた

## 最初のプロンプト
> slipe みたいなゲームを javascript で書いて
> 
> https://bodoge.org/2020/01/01/slipe/

https://github.com/nishinojunji/slipelikegame-with-ai/tree/5202eac136a8698942952157cda9fd8b4d2f8e2f

## 2つめのプロンプト

> AI プレイやと人で対戦できるようにして

https://github.com/nishinojunji/slipelikegame-with-ai/tree/adc9f4a4c247b964edc42cda038e3343e37009bc

## 最後のプロンプト

> もう少し強くして

https://github.com/nishinojunji/slipelikegame-with-ai/tree/1628f165a78b9f63c1138669e9463cfe66cf9065

合計４行でできました

## リセットして再開できないバグ発見

> リセットして開始が動かない。直して

-gemini
申し訳ありません。AIの思考開始待ちのタイマー処理とリセット処理がかち合ってしまい、リセットボタンを押しても、直前に予約されていたAIの動作が実行されてしまう（またはエラーになる）バグがありました。
AIの待機時間をキャンセルする処理を追加し、正しくリセットできるように修正しました。 また、AIの読みの深さを調整して、ブラウザが固まりにくく、かつ十分強い設定にしています。

https://github.com/nishinojunji/slipelikegame-with-ai/tree/2e8014f208fe8d200c43d7b0c0b153162158e846

治った

## 弱くできるようにした

> 強さを選べるように1-5で

https://github.com/nishinojunji/slipelikegame-with-ai/tree/3411ae7acde509262c0205b12eb131be3fddbfef

しばしば千日手になる
