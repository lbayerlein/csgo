# csgo
Docker Container Counter Strike Global Offensive Server

## Howto start

### Clone repo

```
git clone [repo]
```

### Build Docker

```
docker build .
```

### Run Docker container

```
docker run lbayerlein/csgo -game csgo -console -usercon +game_type 0 +game_mode 0 +mapgroup mg_bomb +map de_dust2
```

