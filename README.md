# Practice Misskey Docker Compose

- 参考 : [Docker Composeを使ったMisskey構築 | Misskey Hub](https://misskey-hub.net/ja/docs/for-admin/install/guides/docker/)

```bash
$ docker compose run --rm web pnpm run init
$ docker compose up -d

$ curl http://localhost:3000/
$ docker exec -it misskey-db-1 psql -U example-misskey-user -d misskey

$ docker compose down
```


## Links

- [Neo's World](https://neos21.net/)
