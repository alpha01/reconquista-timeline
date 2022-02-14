# Reconquista Timeline

https://alpha01.github.io/reconquista-timeline/

This app is a slightly modification of [cheeaun/life](https://github.com/cheeaun/life). It uses the same configuration, with additional mandatory fields needed for [custom event styling](./timeline.css).


Development
-----------

```bash
docker run --rm -d --name timeline -p 8080:80 -v $PWD:/usr/share/nginx/html nginx:1.21.6-alpine
```

License
-------

[MIT](http://cheeaun.mit-license.org/)
