# set-up-env
设置环境变量


| 变量名       | 值                                   | 说明           |
|-----------|-------------------------------------|--------------|
| ENV       | dev,qa,prod                         | 根据事件推断的环境    |
| OWNER     | {owner}                             | 仓库所有者        |
| REPO_NAME | {repo_name}                         | 仓库名          |
| APP_NAME  | {ENV}-{repo_name}                   | 应用名          |
| IMAGE     | {DOCKER_REGISTRY}/{ENV}-{repo_name} | 镜像名，用于Docker |
| 版本号       | {DOCKER_REGISTRY}/{ENV}-{repo_name} | 版本号，用于Docker |


