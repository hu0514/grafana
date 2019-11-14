启动命令
docker run -d \
  --name=grafana \
  --network host \
  --restart always \
  -v /data/grafana:/var/lib/grafana \
  grafana/grafana

url     : ip:3000
user    : admin
password: admin
注：
挂载目录grafana拥有者为grafana 或权限777