# 游戏抓取项目

## 项目概述
这是一个多功能的游戏相关工具集合，包含以下子项目：

### 1. Selenium WebDriver 自动化工具
**文件**: `selenium_web_driver.py`

**功能描述**: 使用Selenium WebDriver打开chrome浏览器，并且打开"https://www.huya.com/28962587"网址，鼠标放在"更多"按钮上悬停，然后点击弹窗中的"宠物马拉松"，会弹出游戏弹窗页面，在弹窗页面中获取指定按钮（待补充）上面的文案，并打印出来。

**快速开始**:
```bash
# 安装依赖
pip install -r requirements.txt

# 运行自动化脚本
python selenium_web_driver.py

# 或者使用Windows批处理文件
run_automation.bat
```

**详细文档**: 请查看 [README_selenium.md](README_selenium.md)

### 2. 图像分割工具
**目录**: `split_img/`

**功能**: 使用U-2-Net模型进行图像分割和背景移除

### 3. OCR文字识别工具
**目录**: `Umi-OCR-main/`

**功能**: 基于RapidOCR的文字识别工具

### 4. API测试工具
**目录**: `api_test/`

**功能**: API接口测试和验证

## 环境要求
- Python 3.7+
- Chrome浏览器（用于Selenium自动化）
- 相关Python依赖包（见各子项目的requirements.txt）

## 安装和使用
每个子项目都有独立的安装说明和使用文档，请参考相应的README文件。

## 项目结构
```
game_scrach/
├── selenium_web_driver.py      # Selenium自动化主程序
├── test_selenium.py           # Selenium环境测试脚本
├── run_automation.bat         # Windows快速启动脚本
├── README_selenium.md         # Selenium项目详细文档
├── requirements.txt           # Python依赖包列表
├── split_img/                 # 图像分割工具
├── Umi-OCR-main/             # OCR文字识别工具
├── api_test/                 # API测试工具
└── screenshots/              # 截图目录
```

## 许可证
本项目仅供学习和研究使用，请遵守相关网站的使用条款。
# game_scrach_animal
