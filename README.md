# 期末實作
題目: Puzzle-CAM

課程: 電腦與機器人視覺

組別: 第二組
## Reference
Paper: Jo, S., & Yu, I. J. (2021). Puzzle-CAM: Improved localization via matching partial and full features. arXiv preprint arXiv:2101.11253.

Official implementation: https://github.com/OFRIN/PuzzleCAM
## Results
實驗中我們嘗試使用兩種 backbone 進行比較: ResNet-101 & ResNet-269
### Generated Pseudo-label
	ResNet-101(上圖) ResNet-269(下圖)
![image](https://user-images.githubusercontent.com/43518459/147661905-84b11d41-5653-4c20-b41e-3580735e4a3a.png)
![image](https://user-images.githubusercontent.com/43518459/147662369-8a8fc3c3-f8f4-4932-85a1-3d27a7da9dd8.png)
### Prediction
	ResNet-101(上圖) ResNet-269(下圖)
![image](https://user-images.githubusercontent.com/43518459/147662299-c4f14a8e-0c3f-442b-adb7-55b702bd2e8c.png)
![image](https://user-images.githubusercontent.com/43518459/147662408-154a5d27-dd01-4b2e-8af9-31d145201c95.png)

