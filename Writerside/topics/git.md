# 在 Git 上发布

- 在项目目录内创建 `.github/workflows/build-docs.yml` 文件

1. 修改 on.push.branches 为分支名称
2. 修改 env.INSTANCE 项目名称

```yaml
name: Build documentation

on:
  push:
    branches: ["master"]
  workflow_dispatch:

permissions:
  contents: read
  id-token: write
  pages: write

env:
  INSTANCE: 'Writerside/writerside'
  DOCKER_VERSION: '243.21565'
```
3. 在git上新建仓库（可选）

<img src="git-0.png"  thumbnail="false" width="600" alt="install-0"/>

4. 配置远程仓库
5. 上传到git
