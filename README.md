# redmine-storage

redmine-storage コンテナの使用方法

redmineサーバの添付ファイルなどのデータ保持用コンテナになります。
redmineサーバコンテナとは分離して管理します。

## 1.git clone

```
git clone git@github.com:hidetarou2013/redmine-storage.git
```


## 2.docker build

```
cd redmine-storage
docker build -t hidetarou2013/redmine-storage .
```

## 3.docker create

```
docker create --name redmine-storage hidetarou2013/redmine-storage
```

