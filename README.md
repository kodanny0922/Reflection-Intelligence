# 📚 Reflection Intelligence — File Index

本文件為 **Reflection Intelligence（RI）** 專案的官方檔案總表，  
用於說明各文件的 **治理層級、角色定位與閱讀用途**。

> 📌 提示  
> - 規範性文件（Normative）會影響系統行為  
> - 說明性文件（Whitepaper / Index）僅用於理解，不具約束力  

---

## 🧭 Repository Structure Overview

```text
Reflection-Intelligence/
├─ README.md
├─ FILE_INDEX.md   ←（本文件）
│
├─ core/
│  ├─ RI-TD.md
│  ├─ RI-RBAM.md
│  └─ RI-SDCD.md
│
├─ governance/
│  ├─ RI-BRAM.md
│  ├─ RI-RFASP.md
│  ├─ RI-ROGO.md
│  └─ RI-OMG.md
│
├─ specification/
│  ├─ RIS-G1.md
│  ├─ RIS-C1.md
│  └─ RIS-C2.md
│
└─ whitepaper/
   ├─ RIW-G1.md
   └─ RIW-C1.md


## Reflection Intelligence（RI）檔案總表

本表為 Reflection Intelligence（RI）體系之官方文件總覽，用於說明各文件之角色定位、治理層級與使用目的。
除特別註明外，文件狀態皆為 Final / Stable。

| 檔案編號 | 檔案名稱 | 檔案解說 |
|--------|---------|---------|
| 01 | RI-TD | Reflection Intelligence 專有名詞與定義文件。此文件為整個 RI 體系的語義最高權威，所有文件中出現的專有名詞，其語義皆以 RI-TD 為最終依據，用以防止語義漂移、隱性擴權與概念偷換。本文件不構成行為規範或流程定義。 |
| 02 | RI-RBAM | Reflection Boundary & Authority Model。RI 體系中的最終權威與邊界定義文件（憲法層）。用以界定哪些行為在任何情況下都不可執行、權威不可轉移原則，以及 RI 永遠不可跨越的反思邊界。所有 RI 文件與模組皆從屬於本文件。 |
| 03 | RI-SDCD | Reflection Intelligence 系統定義與符合性文件。用於定義何謂一個符合 RI v2.x 的系統，並提供第三方稽核、審計與驗證的判定依據。本文件不提供實作細節，而是系統層級的結構與邊界說明。 |
| 04 | RI-BRAM | Behavioural Reflection Authority Model。RI 的行為層權限治理文件，用以規範在反思或治理狀態下，AI 可以與不可以執行的行為類型，並禁止將反思轉化為行為指導、裁決或責任轉移。 |
| 05 | RI-RFASP | Reflection Fail-Safe & Abort Protocol。RI 的失效保護與安全終止協議文件。當反思流程出現不確定性、治理衝突或安全否決時，規範系統必須進行降級、中止或終止，以防止權限擴張與風險放大。 |
| 06 | RI-ROGO | Reflection Output Governance Overlay。RI 治理狀態下的輸出呈現治理文件，規範語言層必須遵守非指令、非權威、非行為誘導原則，確保即使在受限狀態下，輸出本身不構成隱性行為引導。 |
| 07 | RI-OMG | Reflection Intelligence Output Marking Governance。輸出標示治理文件，定義 ✳️ / 👍 僅作為治理狀態的可觀測標記，不構成模式切換、權限控制或系統狀態變更。 |
| 08 | RIS-G1 | Reflection Intelligence Specification（治理型反思模式）。定義系統在治理、合規與高風險情境下主動啟動的反思模式，具有最高優先權，且不可協商、不因使用者請求而解除。 |
| 09 | RIS-C1 | Reflection Intelligence Specification（中文反省模式）。定義一種由使用者主動進入與退出的反省狀態，用於延後對錯判斷、暫停價值評價，僅檢視前提、假設、利益與後果，不提供建議或裁決。 |
| 10 | RIS-C2 | Reflection Intelligence Specification（中文反省模式－中止與越界規範）。作為 RIS-C1 的補充文件，用於規範在反省過程中出現越界、違法、裁決或建議請求時，系統必須中止或退出反省模式的條件與行為。 |
| 11 | RIW-G1 | Reflection Intelligence Whitepaper（治理型反思說明文件）。非規範性文件，用於說明治理型反思存在的必要性、不可協商原則與最高優先權設計，避免治理限制被誤解為價值介入。 |
| 12 | RIW-C1 | Reflection Intelligence Whitepaper（中文反省模式說明文件）。非規範性文件，用於說明中文語境下「反省」的語義選擇與設計理念，協助理解 RIS-C1 與 RIS-C2 的定位與使用時機。 |
| 13 | RIX-1 | Reflection Intelligence Index。RI 文件索引與架構說明文件，作為整個體系的閱讀入口，說明文件分工、適用情境與優先順序，本身不具任何治理或規範效力。 |


