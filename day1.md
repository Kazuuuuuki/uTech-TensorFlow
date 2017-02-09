#TensorFlowで学ぶ機械学習勉強会第1回
##初めに
今回の目的 -> TensorFlowの使い方から学び、アウトプットを通じて、機械学習についての理解を深めよう!  
全17回  
***この勉強会は自主ゼミであり、参加する皆さんの自主性を期待します。***  
主催者自身も機械学習はそこまで詳しくなく、あくまで参加者皆さんで協力して学習していくようにお願いします。
##自己紹介
氏名　渡邉知樹  
大学 東京大学理科I類1年生  
Engineer(機会学習、Web、DBなどなど) 
趣味は数学

facebook   
<https://www.facebook.com/profile.php?id=100011591890838&lst=100011591890838%3A100011591890838%3A1485578448>  

Railsやsqlなどの主にWebやデータベース周りが得意。(半年間のエンジニアインターン経験あり)

##団体説明  
***uTech(ゆーてっく)***  

東京大学を活動拠点とする、IT系サークル。

この春から活動を始めました。

扱う領域は
* Web(インターネット)
* 機械学習
* スマホアプリ
* 競技プログラミング
* 情報
* 数学　　

などなど幅広く活動していきます。

##スポンサー  

***Everse Inc.***  

脳波を機械学習を用いて分析し、それに価値生み出していくことを目指す、ITベンチャーを設立します。

機械学習をメインで行うエンジニアインターン生を募集しています。もし興味がある方がいらっしゃれば遠慮なくお声がけください。　　

初回の今回はEverseの経営者かつ、機械学習をメインで行っている難波さんをお呼びしています。機械学習に限らずお聞きしたいことがあれば遠慮なく質問してみてください。  

##自己紹介 && 今後どういう自主ゼミにしたいかトークタイム
##グループ分け
##内容
まず、はじめに一つだけ言っておくと、結構難しいです。</br>
一応動くだけのもの(または大まかな流れと考え方のみ)なら作れますが、ちゃんと理解しようとすると結構しんどいので頑張りましょう。</br>
また、グループで学習がメインとなります。仲間たちと協力しあって進めていくようお願いします。</br>
きっと多くの方が、本格的にDeep Learningに挑戦するのは初めてだと思います。最初は何もわからないかもしれません。</br>
しかし、取り組んでみなければ結果はわかりませんし、取り組み続けていれば、きっとものになると信じて、頑張っていきましょう。
##参考書籍  
パターン認識と機械学習　　
https://www.amazon.co.jp/%E3%83%91%E3%82%BF%E3%83%BC%E3%83%B3%E8%AA%8D%E8%AD%98%E3%81%A8%E6%A9%9F%E6%A2%B0%E5%AD%A6%E7%BF%92-%E4%B8%8A-C-M-%E3%83%93%E3%82%B7%E3%83%A7%E3%83%83%E3%83%97/dp/4621061224</br>
深層学習　</br>
https://www.amazon.co.jp/%E6%B7%B1%E5%B1%A4%E5%AD%A6%E7%BF%92-%E6%A9%9F%E6%A2%B0%E5%AD%A6%E7%BF%92%E3%83%97%E3%83%AD%E3%83%95%E3%82%A7%E3%83%83%E3%82%B7%E3%83%A7%E3%83%8A%E3%83%AB%E3%82%B7%E3%83%AA%E3%83%BC%E3%82%BA-%E5%B2%A1%E8%B0%B7-%E8%B2%B4%E4%B9%8B/dp/4061529021/ref=pd_sbs_14_t_0?_encoding=UTF8&psc=1&refRID=BBSP2P3M3H0830YHYVE7  
##自然言語処理  
http://www.slideshare.net/kazoo04/ss-56821735 
## しょっぱなからグループワーク課題！！  
多層パーセプトロンまでは必須。誤差伝播法は微妙だけど飛ばしてもいい気がします。</br>
http://hokuts.com/category/%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%A0/%E6%A9%9F%E6%A2%B0%E5%AD%A6%E7%BF%92/</br>
勾配降下法　　</br>
http://shironeko.hateblo.jp/entry/2016/10/29/173634</br>
確率的勾配降下法　　</br>
http://sig.tsg.ne.jp/ml2015/ml/2015/06/08/stochastic-gradient-descent.html</br>
Word2vec(今回のテーマ)</br>
http://tkengo.github.io/blog/2016/05/09/understand-how-to-learn-word2vec/?utm_source=dlvr.it&utm_medium=twitter</br>
## ここまで抑えられたらいざチュートリアルへ
***TensorFlow Tutorial***</br>
Vector Representations of Words</br>
<https://www.tensorflow.org/tutorials/word2vec/></br>
<http://tensorflow.classcat.com/2016/02/19/tensorflow-tutorials-vector-representations-of-words/></br>
上記の和訳の記事に従って進めていきます。</br>
解説記事</br>
http://enakai00.hatenablog.com/entry/2016/03/22/102437</br>
基本的にチュートリアルだけではわからないことを補足します 　
* DeepLearning(順伝播型ネットワーク)  
http://qiita.com/ma-oshita/items/99b2cf313494adbb964d  
* 線形識別モデル  
http://sig.tsg.ne.jp/ml2015/ml/2015/05/24/linear-recognition-model.html  
* ベクタ空間モデル</br>
http://user.numazu-ct.ac.jp/~machida/fujii-22.pdf  
* 潜在的意味解析</br>
https://abicky.net/2012/03/24/211818/　  　 
* Word2vec</br>
http://tkengo.github.io/blog/2016/05/09/understand-how-to-learn-word2vec/?utm_source=dlvr.it&utm_medium=twitter    
* ソフトマックス関数　</br>
http://mathtrain.jp/softmax  
* 最尤法</br>
http://mathtrain.jp/mle  
* ロジスティック回帰  
http://blogs.teradata.com/international/ja/hhg10/   
* 多クラス分類(SVM)  
http://qiita.com/shogiai/items/5191be6e27c4ccdfe67f  
* モンテカルロ法  
http://www-fcs.acs.i.kyoto-u.ac.jp/~harada/OC/index.html  
* ドロップアウト  
http://olanleed.hatenablog.com/entry/2013/12/03/010945
* 誤差逆伝播法  
http://qiita.com/Ugo-Nama/items/04814a13c9ea84978a4c  
* 線形代数の基本と固有ベクトルとは?  
http://postd.cc/a-beginners-guide-to-eigenvectors-pca-covariance-and-entropy/  
* CNN(畳込みニューラルネットワーク)  
http://qiita.com/icoxfog417/items/5fd55fad152231d706c2  
* (ロジスティック)シグモイド関数  
http://ibisforest.org/index.php?%E3%82%B7%E3%82%B0%E3%83%A2%E3%82%A4%E3%83%89%E9%96%A2%E6%95%B0  
* RNN  
http://qiita.com/kiminaka/items/87afd4a433dc655d8cfd  
* コード解説(word2vec)  
https://fight-tsk.blogspot.jp/2016/10/word2vecbasicpy.html  
* LSTM  
http://qiita.com/KojiOhki/items/89cd7b69a8a6239d67ca  
* TensorFlowチュートリアル(RNN)
http://tensorflow.classcat.com/2016/03/13/tensorflow-cc-recurrent-neural-networks/  


##次回  　　　　
コードを理解しよう！　　

