# ENV

# Vim
#### 設定
```
vim ~/.vimrc
```
#### Vimの機能に色付けを追加
```
:syntax on
```
#### Vimの機能に行番号を追加 
```
:set number
```
#### 文字列検索
```
/[文字列]
```
#### 同じディレクトリ内のすべてのファイルから文字列を検索
```
:vim [文字列] **/* | cw
```
#### 行番号にジャンプ
```
:[行番号]
```
#### ファイル名の中から文字列を検索し、その行番号を一覧で表示させる
```
:vim [文字列] [ファイル名] | cw
```
#### 終了
```
[esc]
[q]
```
または
```
[esc]
[Shift+ZZ]
```
#### 保存しないで終了
```
[esc]
[q!]
```
#### 一行選択
```
Shift + V
```
#### 一番下まで移動
```
Shift + G
```
#### コピー
```
Y
```


# Terminalの便利な使い方
#### コピー
```
command + C
```
#### ペースト
```
command + V
```
#### 検索
```
command + F
```
#### 使用言語の確認
```
echo $LANG
```
#### EUCに変換
```
nkf -e [file_name] > [new_file_name]
```
#### バイト数を表示
```
wc -c [filename]
```
#### 文字数を表示
```
wc -m [filename]
```
#### 行数を表示	
```
wc -l [filename]
```
#### 単語数を表示
```
wc -w [filename]
```
#### 文字コードを確認
```
nkf -g [file_name]
```
#### UTF-8に変換
```
nkf -w [file_name]
```
#### EUCに変換
```
nkf -e [file_name]
```
#### 一行選択
```
Shift + V
```
#### 一番下まで移動
```
Shift + G
```
#### コピー
```
Y
```
#### 全選択
```
Command + A
```
# Latex
#### パワポで作った画像をEPSファイルに変換する
1. Adobe illustratorを起動

2. 新規作成

3. パワポの画像を貼り付け

4. 書式 -> アウトラインを作成

5. ファイル->保存->EPSファイル->高解像度で保存

# .sh ファイルをダブルクリックで実行する
.sh ファイルを「常にターミナルで開く」に設定

```chmod +x [FileName].sh```をターミナルの.shファイルがある場所で実行
# 仮想環境
```which python 2.7```

（例）```/usr/local/bin/python2.7```

```virtualenv -p /usr/local/bin/python2.7 py2.7```

#### 起動
```source py2.7/bin/activate```

#### 終了
```deactivate```
