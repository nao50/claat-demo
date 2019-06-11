# claat demo
This is [claat](https://github.com/googlecodelabs/tools) demo repo

## install
```
$ go get -u github.com/googlecodelabs/tools/claat
```

## usage
1. add dir & markdown file
```
$ mkdir site1 && cd site1 && touch index.md
```

2. edit index.md

3. check preview 
```
$ claat serve # automaticaly open localhost:9090
```
4. Create codelabs files
```
$ claat export index.md
```

5. git push

## demo
The usual GithubPages site
https://naoyamaguchi.github.io/claat-demo/site1/

Codelab site
https://naoyamaguchi.github.io/claat-demo/site1/dist/index.html#1


