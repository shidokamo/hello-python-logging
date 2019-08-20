# Hello Python Logging Rotate
Python の logging モジュールのサンプルです。

* ログを標準出力とファイルの両方に吐きます。それぞれに違う敷居値を設定しています。
* ファイルへのログは、毎分ローテートされます。
  ローテート前後で欠損がないことやファイル生成の様子をを確認してください。

## 使い方
```
pipenv install
make log
```


