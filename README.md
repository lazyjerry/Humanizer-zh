# Humanizer-zh: AI 寫作去痕工具（台灣繁體中文版）

> **聲明：**
> - 本專案的核心文件翻譯自 [blader/humanizer](https://github.com/blader/humanizer/tree/main)
> - 實用工具部分（核心規則、快速檢查清單、質量評分）參考了 [hardikpandya/stop-slop](https://github.com/hardikpandya/stop-slop)
> - 原專案基於維基百科的 [Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing) 指南

---

## 專案簡介

Humanizer-zh 是一個用於去除文字中 AI 生成痕跡的工具，幫助你將 AI 生成的內容改寫得更自然、更像人類書寫的文字。

本專案適用於：
- 編輯和審閱 AI 生成的內容
- 提升文章的人性化程度
- 學習識別 AI 寫作的常見模式

## 安裝

### 方法一：透過 npx 一鍵安裝（推薦）

```bash
npx skills add https://github.com/op7418/Humanizer-zh.git
```

這是最簡單的安裝方式，會自動將技能安裝到正確的目錄。

### 方法二：透過 Git 複製

```bash
# 複製到 Claude Code 的 skills 目錄
git clone https://github.com/op7418/Humanizer-zh.git ~/.claude/skills/humanizer-zh
```

### 方法三：手動安裝

1. 下載本專案的 ZIP 檔案或複製到本機
2. 將 `Humanizer-zh` 資料夾複製到 Claude Code 的 skills 目錄：
   - **macOS/Linux**: `~/.claude/skills/`
   - **Windows**: `%USERPROFILE%\.claude\skills\`

3. 確保資料夾結構如下：
   ```
   ~/.claude/skills/humanizer-zh/
   ├── SKILL.md       # 技能定義文件（中文版）
   └── README.md      # 說明文件
   ```

### 驗證安裝
