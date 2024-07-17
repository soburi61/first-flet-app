// コンテナを作成
docker run -d --env-file .env -p 8501:8501 --name my-flet-app-container my-flet-app
// コンテナに入る
docker exec -it my-flet-app-container /bin/sh

// コンテナを起動
docker start my-flet-app-container\

pip install --no-cache-dir -r requirements.txt

flet run --android --ios --web [app_directory]