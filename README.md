# 科学上网订阅源

自动采集并检查公开频道中分享的订阅地址，每 6 小时刷新一次。

## 稳定订阅地址

```text
https://raw.githubusercontent.com/straymaplemoon/kexueshangwang/main/latest.yaml
```

该地址始终指向仓库最新提交的 `latest.yaml`。工作流运行结果会同时存入按日期归档的 `sub/` 目录。

## 手动刷新

在 GitHub 仓库的 **Actions → Refresh subscription sources → Run workflow** 中手动启动。

## 注意

订阅地址由公开来源采集，可能过期或不可用；请只在可信客户端中使用，并自行确认所导入节点和服务的可信度。

