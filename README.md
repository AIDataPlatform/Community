# AI Data Platform Community

**Phison AI Data Platform** 的官方社群入口 — 技術交流、產品討論、功能建議與最佳實踐分享。

本 repository **不含應用程式原始碼**；主要用途為 [**GitHub Discussions**](https://github.com/AIDataPlatform/Community/discussions)。請在 Discussions 發文，而非開 Issue（Issue 保留給可重現的缺陷回報）。

---

## 快速連結 · Quick Links

| 資源 | 連結 |
|------|------|
| **加入討論** | [Discussions](https://github.com/AIDataPlatform/Community/discussions) |
| **產品官網** | [ai-data-plateform.pages.dev](https://ai-data-plateform.pages.dev) |
| **GitHub 組織** | [AIDataPlatform](https://github.com/AIDataPlatform) |
| **Phison 官網** | [phison.com](https://www.phison.com) |

### 相關 Repositories

| Repository | 說明 |
|------------|------|
| [AI-Data-Plateform](https://github.com/AIDataPlatform/AI-Data-Plateform) | 產品官網（Astro 靜態站，Cloudflare Pages 部署） |

---

## 討論區怎麼用 · How to Participate

1. 需要 GitHub 帳號（[免費註冊](https://github.com/signup)）。
2. 前往 [**Discussions**](https://github.com/AIDataPlatform/Community/discussions)。
3. 選擇合適的 **Category**，撰寫清楚標題與內容。
4. 技術問題請附上：產品型號、軟體／韌體版本、環境描述、已嘗試步驟。
5. 功能建議請說明使用情境與預期效益。

**搜尋優先**：發文前先搜尋是否已有類似討論。

---

## 建議分類 · Suggested Categories

管理員可在 **Settings → General → Discussions** 啟用並建立下列分類（可依需求調整）：

| Category | 用途 | 範例主題 |
|----------|------|----------|
| **📣 Announcements** | 官方公告、活動、社群政策 | 社群上線、維護時段 |
| **📋 Release Notes** | 版本更新、變更說明 | 韌體、軟體、文件更新 |
| **🗄️ Cache Server** | aiDAPTIV+ Cache Server（GPU KV Cache） | 容量規劃、GPU 節點連線、Hit Rate |
| **💾 Storage Server** | PASCARI Storage Server | Block / File / Object 存取、叢集配置 |
| **🖥️ HCI** | Hyper-Converged Infrastructure | 資源編排、GPU 網格、超融合部署 |
| **📐 Platform & Architecture** | 平台架構、Sizing、整合設計 | Platform Sizing、多產品拓撲 |
| **❓ Q&A** | 跨產品技術問答 | 安裝、故障排除、相容性 |
| **💡 Ideas** | 功能建議與投票 | 新協定支援、API、管理介面 |
| **📚 Guides** | 教學、最佳實踐、設定範本 | 初始部署、效能調校 |
| **🏆 Showcase** | 案例分享、架構展示 | 客戶 POC、效能實測 |

發文時請加上 **Labels**（若已設定）標示產品線，例如：`cache-server`、`storage-server`、`hci`。

---

## 產品線簡介 · Product Lines

| 產品 | 說明 |
|------|------|
| **Cache Server** | 企業級 GPU KV Cache 加速層，降低推理延遲、提升 GPU 利用率 |
| **Storage Server** | AI 工作負載專用儲存，支援 Block、File、Object 多協定存取 |
| **HCI** | 超融合基礎設施，統一管理運算、儲存與 GPU 資源 |
| **Platform Sizing** | 推理與儲存容量規劃工具（官網互動計算器） |

詳細產品說明請見 [官網](https://ai-data-plateform.pages.dev)。

---

## 社群守則 · Community Guidelines

- **尊重與專業**：對人友善，對技術嚴謹。
- **公開討論優先**：除非另有 NDA 管道，請勿在此張貼機密或客戶敏感資訊。
- **建設性回饋**：功能建議請附情境；批評請附可行替代方案。
- **不重複發文**：相似主題請在既有討論串回覆或引用。
- **標記已解決**：問題解決後請回覆說明，方便他人搜尋。

違反守則的內容可能被隱藏或移除；嚴重違規者將被限制參與。

---

## Issue vs Discussion

| 情境 | 建議管道 |
|------|----------|
| 使用問題、架構討論、教學分享 | **Discussions** |
| 功能點子、投票、路線圖意見 | **Discussions → Ideas** |
| 官網明顯錯字、連結失效（可重現） | [AI-Data-Plateform Issues](https://github.com/AIDataPlatform/AI-Data-Plateform/issues) |
| 安全漏洞 | 請透過 Phison 官方資安通報管道（**勿**公開 PoC） |

---

## 語言 · Language

歡迎 **中文** 與 **English** 發文。標題建議使用發文語言；跨語言討論可在內文雙語補充。

---

## 給維護者 · For Maintainers

### 首次設定 Checklist

- [ ] **Settings → General → Features**：勾選 **Discussions**
- [ ] 建立上方建議的 Categories
- [ ] 設定 Labels（產品線、優先級等）
- [ ] 發布置頂歡迎帖（Announcements）
- [ ] 將官網 `Discussions` 連結指向本 repo：  
  `https://github.com/AIDataPlatform/Community/discussions`
- [ ] （可選）在組織 Profile 加入 Community repo 連結

### 建議置頂帖

1. **歡迎帖** — 社群目的、守則、分類說明  
2. **發文指南** — 技術問題應附資訊、如何選 Category  
3. **產品索引** — 各產品官網頁面與對應 Discussion 分類

---

<p align="center">
  <strong>AI Data Platform</strong> · Enterprise AI Infrastructure<br>
  GPU Inference · KV Cache · Storage · Hyper-Converged Management
</p>

<p align="center">
  <a href="https://github.com/AIDataPlatform/Community/discussions">Join Discussions</a> ·
  <a href="https://ai-data-plateform.pages.dev">Visit Website</a> ·
  <a href="https://www.phison.com">Phison</a>
</p>
