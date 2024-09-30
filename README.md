# hw2

```mermaid
gantt
    title 工作分解結構清單
    dateFormat  YYYY-MM-DD
    section 項目階段
    研擬計劃          :2024-10-01, 1d
    任務分配          :after 研擬計劃  , 4d
    取得硬體          :after 研擬計劃  , 17d
    程式開發          :after 任務分配  , 70d
    安裝硬體          :after 取得硬體  , 10d
    程式測試          :after 程式開發  , 30d
    撰寫使用手冊      :after 安裝硬體  , 25d
    轉換檔案          :after 安裝硬體  , 20d
    系統測試          :after 程式測試  , 25d
    使用者訓練        :after 撰寫使用手冊  , 20d
    使用者測試        :after 系統測試  , 25d

