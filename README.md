## コンペ終わってからの反省点
・目的変数のクラスが不均衡であることは、早々に発見したが、不均衡クラスに対して行う手法がclass_weightしかできなかった。後処理として、閾値を設定しその閾値に基づいて集計し直すっていう処理を入れればよかったなと、、、

・NNと勾配ブースティングはアンサンブルをするとスコアが伸びると知ってたが、自分自身の学習不足でNNの導入をできなかった。
以降のコンペではNNの中でもテーブルデータに対して精度の高い*TabNet,ResNet*を導入する
