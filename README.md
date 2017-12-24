# CarND-Traffic-Sign-Classifier-Project


https://d17h27t6h515a5.cloudfront.net/topher/2017/February/5898cd6f_traffic-signs-data/traffic-signs-data.zip

dataset x3 : test.p valid.p train.p


opencv_python-3.4.0-cp36-cp36m-win_amd64.whl


（pip install  pillow libpng 失敗するかも？？）
easy_install pillow libpng
※DLLｴﾗｰが生じた際は一度uninstallした後　再インストール！


・padding
また、畳み込み演算を行うと出力のサイズが入力画像よりも小さくなってしまいます。そこで、出力と入力のサイズを同じにするため、畳み込み演算を行う前に入力画像のサイズを縦横何ピクセル分か拡大することがあります。例えば下の画像のように 4×4 の入力画像を、6×6 にしてから 3×3 のカーネルを適用することで、出力画像のサイズは 4×4 のままとなります。
この処理をパディングといい、Tensorflow では SAME を指定すると入力と出力のサイズが同じになるように外周を0で埋めてパディングされます。パディングを行わない場合は VALID を指定します。

https://intheweb.io/content/images/2017/02/padding-1.png

