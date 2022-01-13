# ROSプログラミング
ロボットシステム学の講義で行ったROSのパッケージ、ノード、パブリッシャ、サブスクライバの作成  
count.py…一秒間に10ずつ数が増えていく  
twice.py…count.pyで増やす個数の2倍の数が増えていく
# 使用機器
Raspberry Pi3
# 実行方法  
`$ chmod +x count.py  　 　　//count.pyに実行権限を付与`  
`$ chmod +x twice.py  　 　　//twice.pyに実行権限を付与`  
端末を4つ用意する  
端末1  
`$ roscore　　　　　　　　　 //roscoreの起動`  
端末2  
`$ rosrun mypkg count.py　　//count.pyの実行`  
端末3  
`$ rosrun mypkg twice.py　　//twice.pyの実行`  
端末4  
`$ rostopic echo /twice　　 //動作の確認`
# 実行動画
count.pyの動画  
https://youtu.be/JL8sz5lpPKE  
twice.pyの動画
https://youtu.be/9xIX35mETUI
# ライセンス
BSD 3-Clause License
