# templae-dic-jp

辞書リポジトリのテンプレートです  
ご自由にお使いください

## リリースファイルの作成について
tagをpushするとリリースファイルが作成されます  
事前にリポジトリの設定を変更する必要があります
  Settings → Actions → General  
  → `Workflow permissions` (一番下の方)  
  → `Read and write permissions`を選択

## 以下、READMEのテンプレートです  
適宜修正して使ってください  
(ダウンロードURLは`https://github.com/utubo/template-dict-jp/`を自分のリポジトリのものへ一括置換してください)

----

## xx-dict-jp

xxの変換辞書です  
google日本語入力とAndroidのGboardのユーザー辞書に登録できます

## 辞書ファイル

📕[ダウンロード](https://github.com/utubo/template-dict-jp/releases/latest)

### Windows用

|ファイル名         |備考    |
|-------------------|--------|
|xx-dict-jp-all.txt |全部入り|

### Android用

|ファイル名         |備考                  |
|-------------------|----------------------|
|xx-dict-jp-xx.zip  |サンプル              |

- Androidは1ファイル2000件という制限があるのでファイルを分けています
- 更新日は[ここ](https://github.com/utubo/template-dict-jp/tree/main/src)を参考に
(ダウンロードは[ダウンロードページ](https://github.com/utubo/template-dict-jp/releases/latest)から)

## ユーザー辞書への追加の仕方
### Windows google日本語入力
1. [ここ](https://github.com/utubo/template-dict-jp/releases/latest)から`mh-dict-jp-all.txt`をダウンロードしておく
2. Google日本語入力のメニューを表示する(タスクトレイの`A`とか`あ`とかを右クリック)
3. 辞書ツール
4. 管理
5. 新規に辞書をインポート
6. `mh_dict_jp.txt`を選択。辞書名は自由
7. インポートボタンをクリック

- なんかエラーが出るかも…
- 更新時は`2. 辞書ツール`の後、辞書を右クリックして`この辞書にインポート`でOK

### Android Gboard
**⚠削除は1単語ずつ行う必要があるため、一度追加すると取り消しが大変です。自己責任でお願いします。**
1. [ここ](https://github.com/utubo/template-dict-jp/releases/latest)から`mh-dict-jp-○○.zip`をダウンロードしておく(ZIPファイルのままでOK)
2. 適当な入力欄でキーボードを表示する
3. 歯車マークをタップ
4. 単語リスト
5. 単語リスト
6. 日本語
7. 右上の`︙`をタップ
8. インポート
9. ダウンロードしたZIPファイルを選択

## License

TODO

