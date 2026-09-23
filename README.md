# 页面内容指纹监测器

通过内容指纹观察页面是否发生异常变化，帮助发现空页面、模板故障和批量内容被替换等问题。

## 核心功能
- 计算页面内容摘要
- 对比不同时间的页面指纹
- 标记大范围同时变化的 URL
- 生成可归档的变化记录

## 使用
```powershell
python tool.py --demo
python tool.py --input sample.csv --json
```
内容变化监测用于质量和稳定性排查，不代表搜索引擎已经重新抓取或更新索引。

官网：https://jta.mobi  
QQ群：1039545483

## 许可证
MIT License
