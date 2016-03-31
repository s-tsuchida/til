# go getのオプション

## -d

パッケージのダウンロードのみ行う

## -fix

パッケージのダウンロードの際に、依存関係の解決やビルド前にfix toolを実行する

※fix toolはGoのプログラム内に古いAPIが使われていないかチェックし、使われている場合は新しいAPIに置換する。

詳しくは[ここ](https://godoc.org/github.com/gophersjp/go/src/cmd/fix)

## -t

パッケージのテストをビルドするのに必要なパッケージもダウンロードする

## -u

指定したパッケージと依存関係をアップデートする