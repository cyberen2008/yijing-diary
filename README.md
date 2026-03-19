# yijing-diary
# 易经打卦日记（带个人备注 + Markdown 导出）

**功能**：
- 按阳历日期自动起卦（文王卦序）
- 显示官方卦辞 + 爻辞 + 卦象符号（䷀ ䷁ ...）
- 每卦每爻可无限追加个人解卦备注（带时间戳）
- 查看历史、按卦名筛选、删除单条、导出 Markdown

## 使用方法

### 方法一（推荐）：GitHub Codespaces（浏览器直接跑）
1. 点仓库右上角 **Code → Codespaces → Create codespace on main**
2. 等环境启动后，在终端输入：
   ```bash
   pip install -r requirements.txt
   python main.py
