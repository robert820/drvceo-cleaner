<div align="center">

<a href="https://blog.dei3c.com" target="_blank" rel="noopener noreferrer">
  <img src="https://github.com/user-attachments/assets/2830eb70-512c-4ddb-87ec-5213a6e465b1" alt="得翼科技 | 驅動總裁殘留清理與首頁修復工具 (DrvCeo Cleaner)" height="70" />
</a>

<br /><br />

**繁體中文** · [简体中文](docs/readme/README_zh-CN.md) · [English](docs/readme/README_en.md)

# 驅動總裁殘留清理與首頁修復工具 (DrvCeo Cleaner)

### 徹底清除驅動總裁垃圾殘留、修復瀏覽器首頁綁架與異常捷徑參數
專為日常使用、電腦維修、裝機技術人員與 WinPE 維護環境打造

[![Platform](https://img.shields.io/badge/Platform-Windows%207%20%7C%208%20%7C%2010%20%7C%2011%20%7C%20WinPE-blue?style=flat-square&logo=windows)](https://github.com/robert820/drvceo-cleaner)
[![License](https://img.shields.io/badge/License-Freeware-informational?style=flat-square)](LICENSE)
[![Type](https://img.shields.io/badge/Type-Freeware%20%7C%20Portable-success?style=flat-square)](#-下載與使用說明)
[![GUI](https://img.shields.io/badge/GUI-Modern%20Native%20UI-blueviolet?style=flat-square)](#)
[![Download](https://img.shields.io/badge/Download-GitHub%20Releases-blue?style=flat-square&logo=github)](https://github.com/robert820/drvceo-cleaner/releases)

**告別惱人的瀏覽器導航綁架、告別無用驅動快取與殘留註冊表！一鍵還原乾淨純淨的 Windows。**

[軟體簡介](#-軟體簡介) · [功能介紹](#-功能介紹) · [軟體操作畫面](#-軟體操作畫面) · [下載與使用說明](#-下載與使用說明) · [系統需求](#-系統相容性與需求) · [常見問題](#-常見問題-faq) · [問題反饋](#-問題反饋與支援)

</div>

---

## 📖 軟體簡介

在日常組裝電腦、系統重灌或硬體驅動更新時，使用「驅動總裁 (DrvCeo)」安裝驅動後，您是否曾遇過以下惱人困擾？

- **瀏覽器首頁遭竄改綁架**：Chrome、Edge、Firefox 等瀏覽器首頁被非預期鎖定或重新導向至未授權的第三方導航網站。
- **桌面快捷方式暗藏小尾巴**：桌面、開始選單或工作列上的瀏覽器捷徑被悄悄附加了未授權的推廣導航網址參數。
- **大量佔用空間的安裝快取**：系統碟（C 槽）或隨身碟被佔用了大量硬碟空間，殘留著無用的驅動壓縮包、暫存快取、安裝日誌與無用資料夾（如 `DrvCeo`、`SysCeo`、`DriverCeo`）。
- **後台服務與登錄檔殘留**：在 Windows 註冊表中留下了開機自啟動、背景監控服務與冗餘機碼，拖慢開機速度。

**「驅動總裁殘留清理與首頁修復工具 (DrvCeo Cleaner)」** 是專為徹底解決上述痛點量身打造的原生綠色免安裝實用工具，支援從 Windows 7 至 Windows 11 全系列系統及 WinPE 離線維護環境，一鍵安全抹除所有殘留，重現純淨高速的系統環境！

---

## ✨ 功能介紹

### 1. ⚡ 一鍵深度清理驅動總裁殘留檔案與快取
- 自動巡檢全硬碟與外接隨身碟，智慧定位 `DrvCeo`、`SysCeo`、`DriverCeo`、`DrvCeo_Backup` 等殘留安裝包、解壓縮快取、暫存檔與運作日誌。
- 採用智慧進階刪除技術，自動解除唯讀屬性並支援 Windows 超長路徑，確保徹底連根拔除。

### 2. 🌐 瀏覽器首頁還原與捷徑參數修復（反綁架防禦）
- 深度掃描桌面、開始選單、工作列與快速啟動中的所有瀏覽器快捷方式（Chrome、Edge、Firefox、Brave 等主流瀏覽器）。
- 自動偵測並徹底剝離快捷方式目標路徑中未授權附加的第三方推廣導航參數，還原為乾淨官方啟動路徑。
- 自動修復並清除登錄檔中被竄改的瀏覽器首頁與默認重定向機碼。

### 3. 🧹 註冊表深度除垢與啟動項清理
- 精準檢測 `HKEY_LOCAL_MACHINE` 與 `HKEY_CURRENT_USER` 下的 Run、RunOnce 開機自啟動項、背景服務 (Services) 與檔案關聯上下文選單。
- 徹底清除驅動總裁留下的後台監視行程與服務項目，杜絕開機暗中喚醒，還原純淨系統開機速度。

---

## 📸 軟體操作畫面

<div align="center">
  <img src="images/應用程式執行畫面.png" alt="驅動總裁殘留清理與首頁修復工具操作介面" width="720" />
</div>

---

## 📦 下載與使用說明

### 📥 下載方式
前往本專案的 [Releases 頁面](https://github.com/robert820/drvceo-cleaner/releases) 下載最新版執行檔。

### 🚀 使用指南
1. 對 `drvceo_cleaner.exe` **連點左鍵兩下執行**。
2. 進入主畫面後，點擊藍色 **「開始清理」** 按鈕。
3. 程式將自動依序執行硬碟掃描、驅動殘留垃圾清除、註冊表除垢及瀏覽器快捷方式修復。
4. 清理完成後，可點擊「開啟日誌」查看詳細成果。

---

## 🖥️ 系統相容性與需求

- **作業系統**：Windows 11 / 10 / 8.1 / 8 / 7 (SP1) 及 Windows PE 維護環境
- **架構支援**：32 位元通用相容架構 (x86 / PE32，原生相容 32 位元與 64 位元作業系統)
- **執行權限**：具備系統管理員身分（雙擊自動提權）
- **執行環境**：單一綠色原生執行檔，無須額外安裝 .NET Framework 或 VC++ 執行庫

---

## ❓ 常見問題 (FAQ)

<details>
<summary><b>Q1: 這款軟體完全免費嗎？</b></summary>
A: 是的！本軟體完全免費（Freeware）。個人使用者、企業資訊人員或電腦維修工作室均可免費使用本工具為電腦進行檢測與清理。惟嚴禁將本軟體單獨販售、出租或捆綁收費營利。
</details>

<details>
<summary><b>Q2: 清理過程會不會誤刪我正常運作的硬體驅動程式？</b></summary>
A: <b>絕不會！</b>本工具僅精準清除驅動總裁遺留在磁碟中的「安裝暫存檔」、「解壓縮快取目錄」、「日誌」與「未授權綁架項」。已經成功安裝至 Windows 系統核心儲存庫（DriverStore）中的硬體裝置驅動完全不受影響，確保硬體穩定運作無虞。
</details>

<details>
<summary><b>Q3: 為什麼防毒軟體偶爾會提示或誤報？</b></summary>
A: 本工具為純淨綠色軟體，絕無任何惡意代碼、木馬或後門。由於本工具需調用底層 Windows API 修復受損的瀏覽器快捷方式、停止殘留背景服務與清理註冊表，部分啟發式防毒引擎可能會以較嚴格的標準判定。若遇防毒軟體警示，請安心將 <code>drvceo_cleaner.exe</code> 加入信任名單。
</details>

---

## 💬 問題反饋與支援

- 🐛 **錯誤回報與功能建議**：歡迎至本專案的 [Issues 頁面](https://github.com/robert820/drvceo-cleaner/issues) 提出。
- 🌐 **得翼科技官方網站**：[https://blog.dei3c.com](https://blog.dei3c.com)

---

## 📄 授權條款 (License)

本軟體採用專有免費軟體授權（Proprietary Freeware），完整授權規範、使用條款與免責聲明請參閱 [LICENSE](LICENSE) 檔案。
