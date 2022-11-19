# Güncelleme 1.2.1: Validator Güncellemesi

## Q Client ve Docker Image Güncellemesi
```
cd  $HOME/testnet-public-tools/testnet-validator/
git stash && git pull
git stash apply && docker-compose pull
docker-compose up -d
```

## Logları Çalıştırma
Oluşturduğumuz screen içerisine girelim loglar durmuşsa logları çalıştıralım.
```
screen -r qnetwork
docker-compose logs -f --tail "100" 
```
