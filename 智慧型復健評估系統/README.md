1. 作品應用主題：智慧型復健評估系統

2. 選用硬體：ToF(Azure Kinect DK)

3. 選料說明：
    - ToF(Azure Kinect DK): 具備深度攝影功能，且整合骨架追蹤模型，方便開發。

4. 硬體連接架構圖：
    <div align=center><img src='https://github.com/JerryJack121/SmartLongCare/blob/main/%E6%99%BA%E6%85%A7%E5%9E%8B%E5%BE%A9%E5%81%A5%E8%A9%95%E4%BC%B0%E7%B3%BB%E7%B5%B1/image/%E7%A1%AC%E9%AB%94%E6%9E%B6%E6%A7%8B%E9%80%A3%E6%8E%A5%E5%9C%96.jpg?raw=true' alt='硬體連接架構圖'/></div>

5. 程式碼說明：
    - demo.py：體適能動作計數主程式。
    - camera_BodyTracking.py：相機模式展示人體骨架追蹤模型。
    - Recording.py：建立錄影檔案。
    - record_BodyTracking.py：錄影模式展示人體骨架追蹤模型。
    - utils 資料夾：建立 Function 以簡化主程式。
    - pyKinectAzure 資料夾：基於 Python 建立易於使用的 Library 以使用 Azure Kinect 大部分的 Function。
    - requirements.txt：環境需求。

6. 環境需求：
    - [Azure Kinect Sensor SDK](https://docs.microsoft.com/zh-tw/azure/kinect-dk/sensor-sdk-download)
    - [Body Tracking SDK](https://docs.microsoft.com/zh-tw/azure/kinect-dk/body-sdk-download)
    - firebase_admin==5.0.1
    - opencv_python==4.2.0.34
    - numpy==1.17.0

6. 貢獻：
    1. 使用 3D 骨架計算關節角度。  
    2. 整合體適能規則計算完成次數。  
        - 肱二頭肌趨舉
        - 椅子坐立
        - 原地坐立抬膝
    3. 完善 Python 環境下錄影與播放紀錄檔功能。

7. 致謝：
    - Github [pyKinectAzure](https://github.com/ibaiGorordo/pyKinectAzure) @[Ibai Gorordo](https://github.com/ibaiGorordo)