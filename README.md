雑多なscript置き場
===

## counter ワンライン文字カウント
```sh
echo -n $1 | wc -m
```

### usage
```sh
$ counter "hogehoge"
8
```

## setmeta2flac
metadataのset。カレントディレクトリ内のflac全てに作用。  
**仮定**
- カレントディレクトリ内のflacファイルはアルバム名、アーティスト、アルバムアーティストが共通。  
- トラック順にソートされている。

### usage
```sh
$ setmeta2flac [artist] [album] [album artist] [artwork(picture)]
```

## wav2flac
カレントディレクトリ内のwavを根こそぎflacにする。  

### usage
```sh
$ wav2flac
```

