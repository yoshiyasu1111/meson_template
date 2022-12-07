# コンテナのビルド

## 手動でビルドする場合

```bash
$ docker buildx bake -f docker-compose.yml
$ docker compose up -d
```

## vscodeのremote containerでビルドする場合

`Open Folder in Container`でルートディレクトリを開く

# mesonの利用方法

## 構成

```bash
$ meson setup . build
```

## コンパイル

```bash
$ cd build/
$ meson compile
```

## 実行

```bash
$ ./hello
Hello, World!
```
