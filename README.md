# wikibase-docker 1.34-mod-bundle

This is a repository where we publish a modified wikibase 1.34 bundle docker image. It is meant to run with `docker-compose`.

* Build docker image:
```
docker build "1.34-mod/bundle" -t wikibase/wikibase:1.34-mod-bundle
```

* Run with `docker-compose`:

```
docker-compose up -d
```

## What is different?
The docker image adds a ![Powered by Wikibase](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1c/Powered_by_Wikibase.svg/88px-Powered_by_Wikibase.svg.png) footer icon and removes all sitelinks.
