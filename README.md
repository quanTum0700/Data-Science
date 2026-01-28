# Kaggle
Kaggle repository
# 📊 Data Science Templates

个人数据科学/Kaggle 比赛常用模板代码集合。

## 📁 文件说明

| 文件 | 描述 |
|------|------|
| `eda_template.py` | 数据探索与预处理标准流程模板 |

## 🚀 使用方法

1. 复制模板到新项目目录
2. 修改文件路径和目标变量名
3. 按需注释/取消注释相关代码块

```bash
# 示例：开始新的 Kaggle 比赛
cp eda_template.py ~/kaggle/new-competition/eda.py
```

## 📋 EDA Template 包含模块

- [x] 数据加载
- [x] 快速概览 (shape, dtypes, head, describe)
- [x] 缺失值分析
- [x] 重复值检查
- [x] 目标变量分析 (分类任务)
- [x] 特征类型分离 (数值 vs 类别)
- [x] 数值特征分布可视化
- [x] 类别特征统计
- [x] 相关性分析
- [x] 数据划分 (train/val split)
- [x] 常用预处理函数 (缺失值填充、编码)

## 🔧 依赖库

```
pandas
numpy
matplotlib
seaborn
scikit-learn
```

## 📝 TODO

- [ ] 添加特征工程模板
- [ ] 添加模型训练基础模板
- [ ] 添加交叉验证模板
- [ ] 添加提交文件生成模板

---

*持续更新中...*
