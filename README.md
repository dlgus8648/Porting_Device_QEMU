# SPI Controller & Driver DEMO
Porting a Device to QEMU
Commit Test
# 1. 데모 
  - ## A. 초기상태
![spi3](https://github.com/user-attachments/assets/ebaf84a1-56a5-4612-a3c3-303b9746b08b)
  - ## B. QMP로 25Kg 전송
![spi4](https://github.com/user-attachments/assets/a99ff37e-5c47-471e-8db0-1488de0a2850)
  - ## C. 수신확인
![spi5](https://github.com/user-attachments/assets/d9b87662-f3cb-44ab-8750-fa3b9ae25692)
  - ## D. 영점 조정
![spi6](https://github.com/user-attachments/assets/6f665fd0-2cba-40b2-9bfa-a6261157bdfe)
  - ## QMP로 35Kg 전송
![spi7](https://github.com/user-attachments/assets/24891bbb-fc2b-4caa-b6be-edd3e187f6a2)
  - ## F (35-25) =10 Kg 스케일링완료
![spi8](https://github.com/user-attachments/assets/49c0a67d-47af-43ca-9125-0fa5733c62a9)






# 2. 시나리오

- ## A. QEMU 새 SoC에 SPI 컨트롤러 추가하기
- ## B. 디바이스 트리에 SPI 컨트롤러 추가하기
- ## C. QEMU SPI를 사용하는 Peripheral 추가하기 
