# gen-tool-dm

gentool支持达梦数据库，基于gentool 0.3.27版本进行扩展，将gentool改为gen-tool-dm即可，其余保持不变

## 安装

```shell
 go install github.com/zzlgo/gen-tool-dm@latest
```

## 使用达梦参考

gen-tool-dm -db=dm -dsn "dm://username:password@host:port?schema=database" \
-outPath="./dao" \
-tables="tableName" \
-modelPkgName model