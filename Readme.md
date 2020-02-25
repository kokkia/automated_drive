# Simulation of automated drive

自動運転における軌道追従シミュレーション
走行シミュレーション

# note
## Libraries required for automated_drive
- numpy
- matplotlib
- cvxpy
- kal_python(https://github.com/kokkia/kal_python)

## usage
1. Setup your environment using anaconda or ...
1. Install cvxpy 
1. Make your main file
1. Clone this library
1. Import kal_python

## cvxpyのwindowsでの環境の作り方
- 下記githubのinstall from sourceからインストール
- エラーがでたらVSのvisual c++ setup toolsをインストールして再挑戦
- https://www.cvxpy.org/install/index.html
- https://hytmachineworks.hatenablog.com/entry/2019/04/26/222821

## Frow
1. コースを定義
1. agentを作成
1. kinematicsモデルを定義し，agentを乗せる
1. worldクラスで描画，シミュレーション

# todo list
- ダイナミクスの考慮
- 速度も制御入力にする
- ポテンシャル場を使った経路生成シミュレーション