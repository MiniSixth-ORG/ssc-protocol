# ssc-protocol

三倉唯一耦合點。型別變更會震動 repo-agent 與 trust-platform。

- 改型別**必須**同步更新 CHANGELOG.md 與協定版本
- **不得**內嵌密碼學實作，驗證邏輯一律以 trait 注入
