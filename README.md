```sh
$ cat sample.yaml
- id: kashav.ca
  repo: git@github.com:kashav/kashav.github.io.git
  build: jekyll build
  serve: _site
  ...
$ go build -o foo cmd/foo/main.go
$ ./foo sample.yaml
...
$ xdg-open "http://localhost:8080/?id=kshvmdn.com&rev=ed098544062a80ef2d8b03ca52f43e43194abb0a"
```
