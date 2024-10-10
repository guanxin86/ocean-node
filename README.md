# ocean-node
ocean-node命令和状态查询
### 在线状态查询
[reward](https://rewards.autobotocean.com/#)
[oceannode](https://nodes.oceanprotocol.com/?source=post_page-----6d53e757cbb1--------------------------------)
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
sudo ufw allow 8000/tcp
sudo ufw allwo 9000:9003/tcp
```
### 查看日志
```
docker logs --tail 100 -f ocean-node
```
