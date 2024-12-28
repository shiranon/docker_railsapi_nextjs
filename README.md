# Docker + Rails api + Next.js + postgreSQL

## 初回実行
1. 初期設定用スクリプトに実行権限与える。`chmod +x -R ./bin/`
2. `bin/init`を実行。
3. `docker-compose up -d`で起動

## Rails api
option `--skip-git --force --api --database=postgresql`  
Pumaのポートを8000に変更  
`rack-cors`のインストール

## Next.js
option `--typescript --tailwind --eslint --app --src-dir --import-alias "@/*" --no-git --turbopack --use-yarn`

## postgreSQL初期ユーザー
username: postgres  
password: password