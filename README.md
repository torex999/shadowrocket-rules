# Shadowrocket DNS防泄露规则备份

本仓库用于备份 Shadowrocket 使用的防 DNS 泄露规则文件。

## 📦 文件说明

- `nodnsleak-pk.ini`：来自网络的防 DNS 泄露规则（备用），适配 Shadowrocket，避免 DNS 请求暴露给运营商或本地网络。

## 📥 使用方法

在 Shadowrocket 的配置中添加订阅：
https://raw.githubusercontent.com/torex999/shadowrocket-rules/main/nodnsleak-pk.ini
