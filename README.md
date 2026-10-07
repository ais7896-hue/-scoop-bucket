# 🪣 Kyte Scoop Bucket

這是 **Kyte 系列軟體**（KyteView、KyteRename、KyteShelf）的專屬官方 [Scoop](https://scoop.sh/) 軟體庫（Bucket）。

---

## 🚀 快速安裝與使用

### 1. 新增此 Bucket 到 Scoop

```powershell
scoop bucket add kyte https://github.com/ais7896-hue/-scoop-bucket
```

### 2. 安裝軟體

```powershell
# 安裝全能極速媒體與文檔預覽工具
scoop install kyte/kyteview

# 安裝現代化批次檔名重命名工具
scoop install kyte/kyterename

# 安裝桌面檔案暫存與工作區整理工具
scoop install kyte/kyteshelf
```

### 3. 更新軟體

```powershell
scoop update kyteview
scoop update kyterename
scoop update kyteshelf
```

---

## 📦 收錄軟體列表

| 軟體名稱 | Manifest | 說明 | 授權 |
| :--- | :--- | :--- | :--- |
| **KyteView** | [`kyteview.json`](bucket/kyteview.json) | 毫秒級極速檔案預覽神器（支援圖片、影片、音訊、PDF、Office、壓縮檔、程式碼） | Freeware |
| **KyteRename** | [`kyterename.json`](bucket/kyterename.json) | 專業批次重新命名工具（即時預覽、正則替換、前綴後綴、流水號） | Freeware |
| **KyteShelf** | [`kyteshelf.json`](bucket/kyteshelf.json) | 桌面邊緣抽屜與檔案暫存抽屜工具 | Freeware |

---

## 🔄 自動更新機制

所有 Manifest 均已配置 `checkver: "github"` 與 `autoupdate` 規則，發布新版本時將自動跟進。