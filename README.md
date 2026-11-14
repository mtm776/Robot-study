# 로봇 센서 기초 노트

2D LiDAR와 관성 측정 장치(IMU)를 사용하는 이동 로봇을 예로 들어, 좌표 변환부터 시간 동기화와 센서 필터링까지 공부합니다. 각 장은 손으로 계산할 수 있는 예제로 시작합니다.

| 장 | 주제 | 다루는 내용 |
|---|---|---|
| 0 | [IMU와 2D LiDAR의 측정값](docs/00-sensor-measurements.md) | ROS 2 메시지, 단위, 자이로 샘플과 LiDAR 광선 읽기 |
| 1 | [LiDAR와 로봇의 좌표계](docs/01-coordinate-frames.md) | 회전 행렬, 평행이동, 역변환 |
| 2 | [타임스탬프와 스캔 왜곡 보정](docs/02-time-sync-and-deskew.md) | 측정 시각, 보간, 자이로 적분, deskew |
| 3 | [센서의 노이즈·이상치·편향](docs/03-sensor-noise.md) | 정지 실험, 평균과 중앙값, 각도 적분에 미치는 영향 |
| 4 | [이동평균과 중앙값 필터](docs/04-moving-average-and-median.md) | 이상치, 실제 회전의 시작, 필터 지연 |
