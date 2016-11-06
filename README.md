# Rock, paper, scissors

Sample program for the game of rock, paper and scissors.

## Require

* 二人でじゃんけんをする。

* 三回勝負、うち二回勝った方を勝者とする。

* あいこの場合は勝負がつくまで続ける。

* 手は「グー」「チョキ」「パー」の三種類。

## Flow

* 最初に一人目、二人目の呼び名の入力をそれぞれ促す。

* 勝負の開始を宣言する。以下、勝負がつくまで繰り返す。

    * 一人目、二人目の出す手の入力を促す。

    * それぞれ入力された結果を元に勝敗を判定して表示する。

    * 勝負がついたかどうかを判定する。勝負がついたら繰り返しを終了する。

* 勝者とそれぞれの勝敗数を表示して終了する。

## Run

```sh
$ ./bin/rps
```

## Run Test

```sh
$ bundle install --path=vendor/bundle
$ bundle exec rspec
```

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

[EOF]
