# Getting Start

## Demo docker nginx image

1. docker pull nginx
2. docker images
3. docker run

```

docker run --name test-nginx -d -p 8080:80 nginx
```

4. docker ps

5. access to containner

```

docker exec -it test-nginx bash
```

6. exit containner

```
exit
```