# csgo
Docker Container Counter Strike Global Offensive Server

## Howto start

git clone [repo]


docker build .
docker run lbayerlein/csgo -game csgo -console -usercon +game_type 0 +game_mode 0 +mapgroup mg_bomb +map de_dust2

