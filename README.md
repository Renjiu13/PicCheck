# 图片尺寸检查工具

## 来由：
由于工作需求，需要批量检查图片尺寸是否符合1200x1200的要求。为了提高工作效率，开发了这个工具。

## 功能

- 自主选择检查路径
- 设置目标尺寸
- 忽略特定文件夹
- 只检查特定文件夹
- 结果显示
  - 显示不符合目标尺寸的图片数量
  - 显示每张不符合尺寸的图片的路径和实际尺寸

## 使用

### 安装依赖

```
pip install -r requirements.txt
```

### 运行

```
python src/image_size_checker.py
```

### 特性

- 支持选择检查文件夹
- 可设置目标图片尺寸
- 支持忽略特定文件夹
- 可选择检查特定文件夹
- 多线程处理，避免界面卡顿