Normal build:
```
docker run --rm -it -v $(pwd):/src klakegg/hugo:0.62.0-ext
```

Run server:

```
docker run --rm -it -v $(pwd):/src -p 1313:1313 klakegg/hugo:0.62.0-ext server
```