# go-http-clients


### Проверка кеширования DNS запросов
Для локального DNS: 
```
sudo tcpdump -n -nn -tttt -i lo port 53
```

Для DNS по сетевому подключению: 
```
sudo tcpdump -n -nn -tttt -i wlan0 port 53
```
