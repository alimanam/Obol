```shell
https://holesky.launchpad.obol.tech/
```



```shell
for pkg in docker.io docker-doc docker-compose docker-compose-v2 podman-docker containerd runc; do sudo apt-get remove $pkg; done
```


```shell
sudo apt-get update
```

```shell
sudo apt-get install ca-certificates curl
```


```shell
sudo install -m 0755 -d /etc/apt/keyrings
```

```shell
sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg -o /etc/apt/keyrings/docker.asc
```

```shell
sudo chmod a+r /etc/apt/keyrings/docker.asc
```

```shell
echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu \   
  $(. /etc/os-release && echo "$VERSION_CODENAME") stable" | \   
  sudo tee /etc/apt/sources.list.d/docker.list > /dev/nul
```


```shell
sudo apt-get update
```

```shell
sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
```

```shell
apt install git-all
```

```shell
git clone https://github.com/ObolNetwork/charon-distributed-validator-node.git
```

```shell
cd charon-distributed-validator-node
```

```shell
mkdir .charon
```

```shell
sudo chmod -R 777 .charon
```

```shell
docker run --rm -v "$(pwd):/opt/charon" obolnetwork/charon:v0.19.1 create enr
```
تا این مرحله برای گرفتن 
ENR 
بود

-------------------------------------------

```shell
apt install screen
```

```shell
apt install docker-compose
```

```shell
screen -S obol
```

```shell
cd charon-distributed-validator-node
```

```shell
sudo apt upgrade docker
```

```shell
sudo apt upgrade docker-compose
```

```shell
docker compose up -d
```

اگر سالم بود هیچی

---------------------------------

اگر خراب بود و ران نشد درست 

******change yml in your server 
اول فایل YML
رو تغییر بدید بعد کد های پایین رو بزنید
```shell
docker compose up -d
```

```shell
docker compose down
```

```shell
docker compose up -d
```
اینجا دیگه میبینید 8 تا 8 تا اجرایی شده


-------------------------------


https://docs.google.com/forms/d/e/1FAIpQLSdlrt-s5_CtJaebIbts3_p08mT_wo6ejbloBlgBmDWXspFa7Q/viewform


https://holesky.beaconcha.in/validators/deposits

https://holesky.beaconcha.in/


https://discord.com/invite/n6ebKsX46w?ref=blog.obol.tech

https://explorer.rated.network/
