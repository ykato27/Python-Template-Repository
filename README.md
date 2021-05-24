# python-template-repository

本リポジトリはPython 環境のテンプレートリポジトリです。


## リポジトリ構成
```
.
├── Dockerfile
├── README.md
├── example
│   ├── datatime_features_example.ipynb
│   └── eval_model_example.ipynb
├── requirements.txt
└── src
    ├── __init__.py
    ├── evaluation
    │   ├── __init__.py
    │   └── eval_model.py
    └── features
        ├── __init__.py
        └── make_features.py
```

## 環境詳細

- Python : 3.9.4


## 事前準備

- Docker インストール


## 環境構築

* Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/Regression-Models）
```
cd Desktop/Regression-Models
```

* Dockerによる環境構築（フォルダをマウント：Desktop/Regression_Models）
```
docker-compose up --build
```

* ブラウザーを立ち上げてlocalhost:8888へアクセス
* ローカルフォルダがマウントされている


## 動作環境
マシンスペック（Mac)
- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
