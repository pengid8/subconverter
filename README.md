# Subconverter (Custom Fork)

本项目为 [subconverter](https://github.com/asdlokj1qpi233/subconverter) 的个人定制/修改版本。

## 本版本修改说明 (Modifications)

1. **自定义 HTTP 请求头支持**：
   - 修复/增加了从配置文件（如 `generate.ini`）中直接读取并添加 HTTP 请求头（如 `User-Agent`）的功能。

---

## 配置文件示例 (generate.ini)

在使用本项目时，你可以在配置文件中指定所需参数（支持自定义请求头）：

```ini
[test]
path=test.yaml
target=clash
url=订阅链接
config=config/mine.ini
# 如需自定义 User-Agent，可直接取消下方注释或自行添加：
# User-Agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64)