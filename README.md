# Pandora-Cloud

![Python version](https://img.shields.io/badge/python-%3E%3D3.7-green)
[![Issues](https://img.shields.io/github/issues-raw/pengzhile/pandora-cloud)](https://github.com/pengzhile/pandora-cloud/issues)
[![Commits](https://img.shields.io/github/last-commit/pengzhile/pandora-cloud/master)](https://github.com/pengzhile/pandora-cloud/commits/master)
[![PyPi](https://img.shields.io/pypi/v/pandora-cloud.svg)](https://pypi.python.org/pypi/pandora-cloud)
[![Downloads](https://static.pepy.tech/badge/pandora-cloud)](https://pypi.python.org/pypi/pandora-cloud)

[![PyPi workflow](https://github.com/pengzhile/pandora-cloud/actions/workflows/python-publish.yml/badge.svg)](https://github.com/pengzhile/pandora-cloud/actions/workflows/python-publish.yml)

### A package for Pandora-ChatGPT

<br><br>
### 手动编译和启动项目

在workspace中使用下载好`pandora`和`pandora-cloud`项目：

```sh
git clone https://github.com/pengzhile/pandora.git
git clone https://github.com/pengzhile/pandora-cloud.git
```

- 先后进入这两个项目的根目录，执行手动编译代码：

```sh
git install .
```

**启动项目:**

```sh
pandora-cloud
```



**代码更新：**

修改完`pandora-cloud`的代码后，更新：

```
git install .
```

这会重新编译，覆盖掉原来的打包文件。