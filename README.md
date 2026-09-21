# weir releases

公开的面板与 agent 发布产物。源码不在这个仓库。

安装当前版本：

```sh
curl -fsSL https://github.com/xjetry/weir-releases/releases/latest/download/install.sh | sudo sh -s -- --role panel
```

某一版的安装器在 `releases/download/<tag>/install.sh`。安装器只装与它一起发布的那一版，并用它携带的 sha256 核对下载到的字节。
