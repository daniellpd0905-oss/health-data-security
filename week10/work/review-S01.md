# S01 第一版｜已通過

文件為美國國家標準與技術研究院（NIST）SP 800-53 Rev. 5，Security and Privacy Controls for Information Systems and Organizations。

| 審核項目 | 送審內容 |
|---|---|
| 原文位置 | AC-6 Least Privilege 的 Control 與 Discussion，PDF 閱讀器第 63 頁。[開啟官方 PDF](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r5.pdf#page=63)。 |
| 白話主張 | 使用者及代表使用者執行工作的程式，取得的權限應限於完成指定任務所需的範圍。 |
| 適用界線 | AC-6 支持「依任務限制權限」這項原則。哪個帳號可用、是否可匯出、核准是否為三天，由本案例的授權單決定。[虛構授權單](../raw/CASE.md) |
| 預計更新 | 在 W01「存取申請與審核」加上如何由研究目的列出必要動作；在 W02「身分與權限」以同一個帳號示範「讀取指定欄位」和「匯出」的判定。兩頁均連回本篇通過後建立的正式來源卡。 |

## 擬用於教材的例句

研究任務只需要在核可環境中讀取摘要。依 grant-017，researcher-01 可以讀取 demo-summary 的指定欄位，若要匯出需另行審查。用來判斷「該給多少權限」的原則來自 AC-6，具體核准項目來自 CASE。

作者回覆「通過」。已建立[正式來源卡](../wiki/sources/S01.md)。
