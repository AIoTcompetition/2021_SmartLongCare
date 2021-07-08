1. 作品應用主題 : 不倒翁
2. 選用硬體 : NVIDIA Jetson Nano、Webcam、IWR6843AOPEVM mmWave sensor、LDC model、LED model、speaker model
3. 選料說明 : 
    1. NVIDIA Jetson Nano : 開發可用Python，方便撰寫
    2. Webcam : 與IWR6843AOPEVM mmWave sensor一起偵測環境
    3. IWR6843AOPEVM mmWave sensor : 與Webcam一起偵測環境
    4. LDC model : 顯示時間日期資訊
    5. LED model : 環境柔光效果工具
    6. speaker model : 當特殊事件發生時可以提醒現場人員
4. 軟硬體連接架構圖 :  <br/>
    ![](https://firebasestorage.googleapis.com/v0/b/fast-mariner-312118.appspot.com/o/picture%2F%E7%A1%AC%E9%AB%94%E6%9E%B6%E6%A7%8B%E5%9C%96.png?alt=media&token=b78de799-964b-4be4-948e-95c5f5f481a0)<br/>
    ![](https://firebasestorage.googleapis.com/v0/b/fast-mariner-312118.appspot.com/o/picture%2F%E8%BB%9F%E9%AB%94%E6%9E%B6%E6%A7%8B%E5%9C%96.png?alt=media&token=6c79ea78-76ba-4ddc-8f9d-b151ec28d29a)
5. 程式碼說明
    - example.py
