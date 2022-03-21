<-- -*- mode:markdown -*- -->

# docker-roswell

Roswell(SBCL)の実行環境を構築するDocker Imageです。

# base

alpineにRoswellを入れただけのimageです。  
Common Lisp実行環境を構築するための基礎をイメージしています。

```bash
docker pull hodumi/docker-roswell
```

# dev

hodumi/docker-roswellにswankサーバを追加しただけのimageです。  
開発用をイメージしています。

```bash
docker pull hodumi/docker-roswell:dev
```

