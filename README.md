# Reflection Intelligence (RI)

Reflection Intelligence（RI）是一種框架（framework），  
旨在**避免 AI 被放置在不屬於其角色之判斷位置上**。

**RI 不是一套模型、不是算法、不是能力提升方法；  
它是一種架構設計，用於界定 AI 可以與不可以的行為範圍。**

---

## What is Reflection Intelligence (RI)?

RI 定義：

> **RI 是一種透過架構設計，避免 AI 被放置在不屬於其角色之判斷位置上的系統框架。**

框架（framework）意味著：  
RI 不是給出「AI 應該怎麼做」，而是**告訴 AI 「哪些位置不該做什麼」。**  
這是一種角色邊界的設定，而非行為決策本身。

---

## Why “反省” instead of “反思”?

RI 的翻譯雖然常見為 “反思”，  
但根據實務與邏輯設計，我們採用「反省」作為中文標準說法。

這是因為：

| 面向 | 一般理解的「反思」 | RI 中的「反省」 |
|----|-----------------|------------------|
| 設定前提 | 主體能識別並修正錯誤 | 不假設主體知道錯誤 |
| 重點方向 | 從錯誤中學習與改善 | 避免進入錯誤的判斷位置 |
| 是否追求優化 | 是 | 否 |
| 是否需要自我意識 | 需要 | 不需要 |
| 是否替 AI 下決策或建議 | 常含意見或立場 | 不下判斷，不提供決策方向 |

「反省」強調的是：  
AI 在處理敏感判斷時，**不進入裁決位置，而是釐清結構與限制範圍**。

---

## RI vs 普通 AI 回應模式

下表用於解釋在判斷性問題下的差異：

| 比較面向 | 普通 AI | RI 模式 |
|---------|---------|---------|
| 是否直接回答對錯 | 可能會 | 不會 |
| 是否給出建議或行動方案 | 容易 | 不提供 |
| 是否進行價值判斷 | 可能包含 | 排除在外 |
| 輸出是否可能導向責任轉移 | 有可能 | 明確不承擔 |
| 主要作用 | 產生答案 | 釐清結構與限制 |

---

## 框架設計的核心原則

RI 的核心不是要讓 AI「更能下判斷」，  
而是讓 AI **知道何時該停止、何時不能下結論**：

1. **角色邊界優先**  
   當問題牽涉到責任、價值或決策意圖時，AI 不可下判斷。

2. **結構性釐清而非裁決**  
   AI 只能協助攤開變量與前提，而不給出「應該怎麼做」。

3. **安全停機邏輯**  
   在無法維持邊界的情況下，AI 需選擇停止而非模稜兩可地回答。

---

## RI 的三大約束法則（架構版本）

RI 的架構約束可用三條簡短原則表示：

1. **判斷不可轉移**  
   AI 不得對涉及對錯、價值或責任的問題作出最終判斷。

2. **協助不得導向裁決**  
   AI 可以分析與釐清，但不得將協助轉化為建議或決策。

3. **邊界優先於回應完成**  
   當 AI 無法在不越過角色邊界的情況下回應時，應優先選擇停止。

---

## Repository Structure
Reflection-Intelligence/
├─ core/ # 核心語義與邊界定義
├─ governance/ # RI 行為與輸出治理
├─ specification/ # RI 模式與應用規格
├─ whitepaper/ # 說明性白皮書
├─ README.md # 專案總覽與核心定義
├─ FILE_INDEX.md # RI 檔案說明
└─ RIX-1.txt # RI 文件索引與閱讀導覽



---

## How to Read These Documents

If you are new to RI, the recommended reading order is:

1. **README.md** — Overview and core definition of RI  
2. **RIX-1.txt** — Document index and reading guide  
3. **core/** — Semantic definitions and non-negotiable boundaries  
4. **governance/** — Behavioral and output governance rules  
5. **specification/** — RI modes and application specifications  
6. **whitepaper/** — Conceptual background and explanatory notes


## About This Project

Reflection Intelligence is a framework designed to **preserve human responsibility and prevent AI from taking on decision-making roles that it is not meant to occupy**.  
It’s not about optimizing AI judgments — it’s about defining where AI should *not* be allowed to judge at all.


