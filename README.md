# haproxy-samples

## run
```
docker-compose up -d
```
## Test on browser
```
http://localhost
http://localhost/api
http://localhost:8404
```

## Logs
```
docker-compose logs -f
```

## Validate config
```
docker run --rm -it \
-v $(pwd)/haproxy/haproxy.cfg:/usr/local/etc/haproxy/haproxy.cfg \
haproxy -c -f /usr/local/etc/haproxy/haproxy.cfg
```