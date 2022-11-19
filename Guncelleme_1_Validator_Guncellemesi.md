# Güncelleme 1: Validator Güncellemesi

## Q Client ve Docker Image Güncellemesi
```
cd  $HOME/testnet-public-tools/testnet-validator/
git stash && git pull
QCLIENT_IMAGE=qblockchain/q-client:1.2.1
git stash apply && docker-compose pull
docker-compose up -d
```
