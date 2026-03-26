# 实时汇率走势图分析

一个功能完整的 Python 项目，用于获取、分析和可视化人民币与欧元的实时汇率数据。

## 🎯 项目特性

- ✅ 从欧洲央行 API 获取实时汇率数据
- ✅ 备用 API 自动降级，确保数据获取成功
- ✅ 完整的中文显示支持（无乱码）
- ✅ 美观的双子图表展示汇率走势
- ✅ 清晰的趋势指示（上升↑/下降↓箭头）
- ✅ CSV 数据导出
- ✅ 20 个单元测试（100% 通过）
- ✅ 详细的项目文档

## 📊 Quick Start

```bash
# 安装依赖
pip install requests pandas matplotlib numpy

# 运行程序
python3 exchange_rate_chart.py

# 运行测试
python3 run_tests.py
```

## 📁 项目文件

- `exchange_rate_chart.py` - 主程序代码
- `test_exchange_rate_chart.py` - 单元测试（20个测试）
- `run_tests.py` - 测试执行工具
- `exchange_rate_data.csv` - 汇率数据
- `exchange_rate_chart.png` - 图表输出
- `TEST_GUIDE.md` - 测试指南
- `TEST_REPORT.md` - 测试报告

## ✨ 功能亮点

### 数据获取
- 从欧洲央行(ECB)获取实时汇率
- 备用API自动降级机制
- 支持最近90天的历史数据

### 数据处理
- 使用pandas进行数据清理和处理
- 自动日期格式化
- 数据排序和去重

### 图表展示
- 双子图表展示CNY/EUR和EUR/CNY走势
- 自动调整Y轴范围突出数据波动
- 趋势箭头指示价格涨跌
- 完整的中文字体支持

### 测试覆盖
- 数据处理测试（5个）
- 图表生成测试（3个）
- 数据获取测试（4个）
- 中文显示测试（3个）
- 集成测试（4个）
- 数据验证测试（1个）

**总计: 20个单元测试, 100% 通过率**

##  许可证

MIT License

## License

For more information, visit the [full README](./README.md) on GitHub.