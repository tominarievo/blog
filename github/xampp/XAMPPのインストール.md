# XAMPPのインストール
## 公式サイトからダウンロード
https://www.apachefriends.org/jp/index.html <BR>
お使いの環境に合致したプログラムをダウンロードしてください。<BR>
（このサイトでは、Windows版をインストールします）
![alt text](xampp_img_1.png)

XAMPPのダウンロードが始まります。
![alt text](xampp_img_2.png)

ダウンロードしたインストーラーを実行します。<br>
記事作成時点では、xampp-windows-x64-8.2.12-0-VS16-installer でした。
実行すると警告が表示されます。警告は、C:\Program Filesフォルダは避けてくれという意味のようです。
![alt text](xampp_img_3.png)

インストールが起動したら、まずは、「Next」を押します。
![alt text](xampp_img_4.png)

インストールするコンポーネントを選択します。今回は、デフォルトのままインストールを行います。「Next」を押して、進めます。
![alt text](xampp_img_5.png)

次に、インストール先を指定します。今回は、デフォルトのまま「C:\xampp」で進めます。「Next」を押してください。
![alt text](xampp_img_6.png)

言語は、英語かドイツ語しかないので、英語を選びます。
![alt text](xampp_img_7.png)

選択肢は、これで終わりです。「Next」を押してください。
![alt text](xampp_img_8.png)

XAMPPのインストールが始まります。
![alt text](xampp_img_9.png)

途中、Apacheの通信許可の確認がでますので、「許可」を選びます。その後、インストールが完了します。
![alt text](xampp_img_10.png)

インストールが完了すると、以下の画面が表示されます。
![alt text](xampp_img_11.png)

## Apacheの動作確認
まずは、WEBサーバーであるApacheの動作確認をします。Apacheの行にある、「Start」を押します。
![alt text](xampp_img_12.png)

その後、WEBブラウザを立ち上げて、http://localhost を表示します。以下の画面(ダッシュボード)が表示されば、Apacheの動作確認は、完了です。
![alt text](xampp_img_13.png)

## MySQL(MariaDB)の動作確認
次に、MySQL(・・・というよりは、MariaDBが正しい)の動作確認をします。表示しているダッシュボードから、「phpMyAdmin」を押します。

![alt text](xampp_img_14.png)

画面の左側には、データベース（infomation_schemaやmysqlなど）が表示されていれば動作しています。
![alt text](xampp_img_15.png)