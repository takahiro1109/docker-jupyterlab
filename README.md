JupyterLab　Docker
# インストール（初回）
　　-  dockerコンポーネントビルド
	　docker compose up -d --build

   - docker環境へ入る
     docker  exec -it jupyterlab-test bash

   - numpyライブラリのインストール
   　　python3 -m pip install numpy


# アクセス
docker logs jupyterlab-test | tail

http://127.0.0.1:8888/lab?token=XXXのURLからアクセス

　
　toke= 以降の文字をコピー

＃JupyterLabを使ってみる。

# 終了
docker compose down

#　再起動
docker compose up -d



