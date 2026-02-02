# estudoorganizadosite

Comandos:
docker run --rm -it -v ${PWD}:/app -w /app node:20 npx create-react-app frontend

docker compose up --build


Se necessário remover build antigo quebrado
docker compose down
docker builder prune -f
