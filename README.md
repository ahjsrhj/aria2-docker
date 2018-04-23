# aria2-docker
仅包含Aria2的极简docker镜像
使用方法:
```
sudo docker run -d --name aria2-docker -p 6800:6800 -v /yourdownloadpath:/data -v /yourconfigpath:/conf aria2-docker:latest
```

