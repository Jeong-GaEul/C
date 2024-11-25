README.md

# 2024.11.22

## 11_ADC_DMA_MultiChannel

여러 아날로그 입력 채널의 데이터를 동시에 샘플링하여 메모리에 저장

CPU의 개입 없이 DMA를 통해 데이터를 자동으로 전송

ADC 핸들러를 설정하고 다중 채널 구성을 추가

DMA를 ADC와 연결하여 자동 데이터 전송 설정

DMA가 메모리에 저장한 데이터를 활용하여 원하는 작업 수행


## 14_UART_DMA

UART를 통해 데이터를 송수신할 때 CPU 부하를 줄이고 효율적으로 데이터를 처리

송신과 수신 모두에 DMA 활용

순환 모드 활성화로 지속적인 데이터 전송 및 수신 가능

DMA 수신 버퍼에 저장된 데이터를 읽어 작업 수행