```sh
# 合并命令如下
cat ecdict_* > ecdict-sqlite-28.zip
```

```sh
# 切分命令如下
split -b 10M ecdict-sqlite-28.zip ecdict_
```
