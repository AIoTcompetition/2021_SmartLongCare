1. 作品應用主題: 智慧型復健評估系統
2. 選用硬體: ToF(Azure Kinect DK)
3. 選料說明:
    i. ToF(Azure Kinect DK): 具備深度攝影功能，且整合骨架追蹤模型，方便開發。
4. 硬體連接架構圖:
    ![硬體連接架構圖](https://github.com/JerryJack121/SmartLongCare/blob/main/%E6%99%BA%E6%85%A7%E5%9E%8B%E5%BE%A9%E5%81%A5%E8%A9%95%E4%BC%B0%E7%B3%BB%E7%B5%B1/image/%E7%A1%AC%E9%AB%94%E6%9E%B6%E6%A7%8B%E9%80%A3%E6%8E%A5%E5%9C%96.jpg?raw=true)
5. 程式碼說明
    - camera_BodyTracking.py: 以相機模式輸入展示人體骨架追蹤模型。
    - Recording.py: 建立錄影檔案。
    - record_BodyTracking.py: 以錄影檔案輸入展示人體骨架追蹤模型。
    - utils 資料夾: 建立 Function 以簡化主程式。
    - pyKinectAzure 資料夾: 基於 Python 建立易於使用的 Library 以使用 Azure Kinect 大部分的 Function。