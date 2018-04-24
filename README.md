# docker-websocket:
Ouvrez un terminal et tapez les lignes de commande ci-dessous
1. git clone https://github.com/socketio/socket.io
2. cd socket.io/examples/cluster-nginx
3. docker-compose up -d

# dans votre navigateur internet:
4. ouvrir 2 à 4 sessions sur http://localhost:3000
5. bravo

# information:
si vous voulez couper les containers docker du projet
cd socket.io/examples/cluster-nginx
docker-compose down
