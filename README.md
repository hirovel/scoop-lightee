# scoop-lightee

[![Tests](https://github.com/hirovel/scoop-lightee/actions/workflows/ci.yml/badge.svg)](https://github.com/hirovel/scoop-lightee/actions/workflows/ci.yml) [![Excavator](https://github.com/hirovel/scoop-lightee/actions/workflows/excavator.yml/badge.svg)](https://github.com/hirovel/scoop-lightee/actions/workflows/excavator.yml)

[Lightee（轻小译）](https://github.com/hirovel/lightee-translator) 的 [Scoop](https://scoop.sh) bucket。

## 安装

```pwsh
scoop bucket add lightee https://github.com/hirovel/scoop-lightee
scoop install lightee
```

升级 `scoop update lightee`，卸载 `scoop uninstall lightee`。

## 还没有 Scoop？

在 PowerShell 里执行，不需要管理员权限：

```pwsh
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```

装好后回到上面一步。

## 说明

- 需要 Windows 10 / 11 64 位。
- 翻译需要 AI 服务商的 API Key，在应用设置里填写。Key 经 Windows DPAPI 加密后存在本机。
- 用户数据在 `~/.lightee`，`scoop uninstall` 不会删除它。
- 这个渠道装的版本由 `scoop update` 管理，应用不会自行更新。

## 反馈

应用本身的问题请提到[主仓库](https://github.com/hirovel/lightee-translator/issues)；只有这个 bucket 的清单问题（下载地址、校验和）提到本仓库。
