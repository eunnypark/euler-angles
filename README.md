# Euler Angles 3D Visualizer

오일러각(Roll, Pitch, Yaw)과 3차원 회전 행렬의 동작을 슬라이더로 조작하며 확인할 수 있는 시각화 스크립트이다.

## ✨ 주요 기능
- **Z-Y-X 회전 행렬 구현**: Yaw $\rightarrow$ Pitch $\rightarrow$ Roll 순서로 적용되는 3차원 회전 행렬 계산 로직 포함
- **인터랙티브 슬라이더**: `ipywidgets`를 활용해 실시간으로 각도를 변경하며 3D 좌표축(X, Y, Z)의 변화를 시각적으로 확인
- **라이브러리**: `numpy`, `matplotlib`
