# hw2后端部分

[![Docker](https://github.com/ds-hw-fuuzen/hw2-backend/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/ds-hw-fuuzen/hw2-backend/actions/workflows/docker-publish.yml)

[使用 VSCode + docker 开发](https://github.com/ds-hw-fuuzen/.github/blob/main/profile/README.md)

[使用 VSCode + docker 开发](https://github.com/ds-hw-fuuzen/.github/blob/main/profile/README.md)

为了实现前后端对接，请在 VSCode 创建开发容器之前先创建这样一个 docker bridge：

```shell shell
docker network create hw2_bridge
```

这个网桥 `hw2_bridge` 名称已经硬编码在 `.devcontainer/docker-compose.yml` 中。

当需要对接的时候，请打开两个 VSCode 窗口，分别在开发容器中打开项目目录，分别运行程序即可。