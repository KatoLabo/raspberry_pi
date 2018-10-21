cover.py : 


Name
====

Overview
raspberry Pi上で動作するプログラム

## camera_dif.py
カメラで部屋を撮影し，学習データで解析された部屋の綺麗さのパラメータを返却する
## dust.py
ホコリセンサから入力を受け取り入力値を返却する
## smell.py
においセンサから入力を受け取り入力値を返却する
## cover.py
camera.py, ust.py,smell.pyを実行し，それらの戻り値をpost.pyに渡す
## post.py
cover.pyから渡された値をサーバに投げる
## res_json.py
アプリからリクエストがあったらcover.pyを実行する
