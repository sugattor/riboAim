# 楽天あとからリボ金額調整ソフト

[ダウンロードはこちらから](https://github.com/sugattor/ribo_aim/releases/download/2018-9-17/ribo_aim.zip)

## 概要
楽天カードのあとからリボ払いで、どれをリボ払いにすると指定した金額に抑えられるのかを計算するソフトです。
[プログラミング言語「Kuin」](http://kuina.ch/kuin)の処女作です。

## 使い方
付属のribo.txtはサンプルですので、これをメモ帳で編集するのが楽だと思います。

楽天e-NAVIの「リボ払い変更」ページから、
表をクリップボードコピーし、ribo.txtに貼り付けて保存してください。
![capture1](https://user-images.githubusercontent.com/20632567/45639845-0690c800-baec-11e8-991f-59ea3d19be2c.png)

![capture2](https://user-images.githubusercontent.com/20632567/45639846-0690c800-baec-11e8-9d5a-b6e2d5bf2185.PNG)

この時、
- ribo.txtはUTF-8で保存されているか
- 書式があっているか（最初のタブスペースが抜けてないか）
を確認してください。

![cap3](https://user-images.githubusercontent.com/20632567/45639847-0690c800-baec-11e8-88d5-b7731e24423c.PNG)

実行すると、目標金額を聞かれるので、入力してください。
2018年8月現在では、30001とするのが良いと思われます。
![cap4](https://user-images.githubusercontent.com/20632567/45639849-07295e80-baec-11e8-8c8f-7119635dfb9f.PNG)

チェックする組み合わせを全通り走査したのち結果が表示されます。
![cap5](https://user-images.githubusercontent.com/20632567/45639850-07295e80-baec-11e8-9f16-db7eb844243b.PNG)

## 開発環境
Kuin Programming Language 2018.8.17

## 更新履歴
- 2018/8/28 初版
- 2018/9/17 GitHubへ移行 終了する際にワンクッション
