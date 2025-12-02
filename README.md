# 文字差異與相似度比對工具 (Text Diff & Similarity Tool)
基於瀏覽器的文字比對工具，專注於解決「標點符號」與「純文字」分離比對的需求。
https://progress01.github.io/text-diff-tool/

## 功能
- **採用雙模式比對**：
  - **純文字模式**：自動過濾全形/半形空格與標點符號，專注比對文字內容。
  - **標點符號模式**：獨立檢視標點符號的差異，對於校對排版非常有用。
- **相似度計算**：使用 Levenshtein Distance 演算法計算修改前後的相似度百分比。
- **視覺化差異**：使用紅/綠色塊直觀顯示刪除與新增的文字。
## 使用技術
- **UI 框架**: [Tailwind CSS](https://tailwindcss.com/) (CDN)
- **核心算法**: [jsdiff](https://github.com/kpdecker/jsdiff) (CDN)
- **圖標庫**: [Lucide Icons](https://lucide.dev/)
- **字體**: Noto Sans TC (思源黑體)
## 📖 如何使用
1. 在左側 **原始文本 (Old)** 貼上舊文章。
2. 在左側 **修改後文本 (New)** 貼上新文章。
3. 點擊 **開始分離比對**。
4. 右側將自動生成兩份報告：純文字差異與標點符號差異。
