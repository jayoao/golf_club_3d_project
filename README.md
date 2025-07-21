# Golf Club 3D Project 

本專案使用機械手臂旋轉高爾夫球桿頭，透過固定鏡頭拍攝多角度影像，重建 3D 模型並進行瑕疵檢測。

## 📁 專案結構
main.py # 主程式入口
config.py # 參數設定
camera/ # 拍照、校正、影像控制
robot/ # 機械手臂模組
reconstruction/ # 3D 重建流程（如 SfM、融合）
defect_detection/ # AI 或 CV 偵測缺陷
data/ # 圖像與結果（不會上傳）