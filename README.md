# docker-ubuntu
Ubuntuコンテナを作成して作業する際の参考に。

# 実行手順
- イメージを作成するためにbuild
`docker build . -t ubuntu_image`

- イメージからコンテナの作成
`docker run -it -d --name my-ubuntu ubuntu_image`

- 作成したコンテナに入る
`docker exec -it my-ubuntu bash`
