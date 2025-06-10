## REPLで立ち上げる場合
```
docker run -it --rm racket/racket
```

## ファイルをマウントして実行したい
```
docker run --rm -v $(pwd):/usr/src/app -w /usr/src/app racket/racket racket youfile.rkt
```
