# 🐍 Taotaospyder

Taotaospyder 是一个基于 Selenium 的淘宝商品评论爬虫，用于抓取商品评论数据并保存为 Excel 文件，适合数据挖掘、文本分析、情感分析等任务。

> ✅ 支持自动登录、模拟滚动、评论去重  
> ✅ 针对淘宝网页结构适配，适合课程项目与学术实验使用  


## 🔧 功能特性

- 📌 自动打开浏览器并扫码登录淘宝账号（每次强制重新登录）
- 📦 模拟滚动加载淘宝商品评论
- 🧹 自动清洗评论中的表情符号等无效内容
- 💾 数据保存为 Excel 文件（包含昵称、时间与型号、评论内容）



## 🚀 使用方式

1. 克隆仓库

```bash
git clone https://github.com/amonguevara/taotaospyder.git
cd taotaospyder

	2.	安装依赖

建议使用虚拟环境：

pip install -r requirements.txt

	3.	运行程序

python taotaospyder.py

浏览器将自动打开淘宝登录页，使用淘宝 App 扫码登录，程序随后自动抓取并保存评论。


💼 输出数据示例

用户昵称	评论时间与型号	评论内容
g**7	2025年4月19日 原色钛金属/256GB	第一次在淘宝买手机…
