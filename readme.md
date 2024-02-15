![image](https://github.com/molla202/subsquid-task/assets/91562185/02086ae2-fa38-468c-b514-fbf6e1bf9259)


👉 Sırasıyla yükleyelim
```
sudo apt update && sudo apt upgrade -y && sudo apt install nodejs && sudo apt install git
```
```
sudo apt install apt-transport-https ca-certificates curl software-properties-common -y
```
```
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable"
```
```
sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin -y
```
```
curl -sL https://deb.nodesource.com/setup_20.x | sudo -E bash -
```
```
sudo apt-get install -y nodejs
```
```
sudo npm install -g npm@10.1.0
```
```
npm install --global @subsquid/cli@latest
```
```
sqd init uniform-load-squid -t https://github.com/subsquid-quests/network-test-one-uniform-load-squid
```
```
cd uniform-load-squid
```
```
npm ci
```

👉 Siteden keyi indirin ve ./query-gateway/keys  içine atın

👉 Peer id nizi aşağdaki komutla alın
```
sqd get-peer-id
```

https://app.subsquid.io/profile/gateways/add?testnet

👉 Yukarıdaki adrese peer id nizi girin register yapın. public kapalı kalsın.

👉 Açtığınız gateaway e 10 token stake edin. 15 dk kadar bekleyin.
```
screen -S sq
```
```
sqd up
```
```
sqd build
```
```
sqd run .
```
