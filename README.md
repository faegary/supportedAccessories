# supportedAccessories

本系統利用`github`作為文件版本管理系統，結合`ReadTheDocs`系統，提供費米的業務與經銷商，作為網頁文件發布系統，可以隨時查詢與檢視智慧家庭整合設備清單。
- 透過 `github` 的帳號提供內容編緝權限管制
- CI/CD 整合提供即時網頁內容更新機制
- 固定網址發布文件 https://supportedaccessories.readthedocs.io/en/latest/
- 提供網頁內容搜索功能，可以輸入設備名稱或是廠牌名稱，快速查找支援設備

## 內容維護人員注意事項

### 檔案目錄結構設計

文件系統入口網頁文欓： docs/source/index.rst

文件系統根目錄： docs/source

根目錄檔案與子目錄的設計：accessory_index_file + accessory_folder + brand_accessory_file

accessory_index_file : 

Accessory Index 檔案設計提供兩個功能：

1. 與 index.rst 掛勾形成網頁的超連結
2. 與 Accessory Folder 內的支援品牌設備檔案 Brand Accessory File 掛勾形成網頁的階層連結


# To-do

- 先支援英文版，之後再整合多國語系功能加入中文
