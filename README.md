# ocean-node
ocean-node命令和状态查询
### 在线状态查询
[oceannodes](https://rewards.autobotocean.com/#)
### docker重启
```
docker restart ocean-node
```
```
docker restart typesense
```
### 关闭重新运行
```
docker stop ocean-node typesense
docker rm ocean-node typesense
```
```
cd $HOME/ocean
docker-compose up -d
```
### 需要开放的端口
```
sudo uwf allow 8000/tcp
sudo uwf allwo 9000:9003/tcp
```
