# git submodule

> Inspects, updates and manages submodules.
> More information: <https://git-scm.com/docs/git-submodule>.

- Install a repository's specified submodules:

`git submodule update --init --recursive`

- 下载子模块:

`git submodule add {{repository_url}}`

- 下载子模块到指定目录:

`git submodule add {{repository_url}} {{path/to/directory}}`

- 更新子模块:

`git submodule foreach git pull`
