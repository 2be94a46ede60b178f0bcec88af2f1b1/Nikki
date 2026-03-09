# Nikki 自用分流

自用的 **Mihomo/Clash** 分流规则与配置仓库。

特点：
- 按服务拆分规则集（例如 Telegram、TMDB），便于维护
- 主配置文件统一引用本仓库的 rule-providers

## 文件说明

- `nikki`：主配置（Mihomo/Clash 配置文件）
- `Telegram.yaml`：Telegram 相关分流规则（rule-provider payload）
- `tmdb.yaml`：TMDB 刮削相关分流规则（rule-provider payload）

## 规则集引用（raw 链接）

- Telegram：
  - <https://raw.githubusercontent.com/2be94a46ede60b178f0bcec88af2f1b1/Nikki/main/Telegram.yaml>
- TMDB：
  - <https://raw.githubusercontent.com/2be94a46ede60b178f0bcec88af2f1b1/Nikki/main/tmdb.yaml>

## 维护约定

- 仅提交与分流/配置相关文件
- 本地密钥、备份文件等不进入仓库（见 `.gitignore`）

