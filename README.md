# LuKasIT 아두이노 교재 프로젝트

이 프로젝트는 출판사 LuKasIT의 아두이노 교재를 위해 제작된 예제 코드 및 관련 자료 모음입니다. 아두이노를 처음 접하는 학습자들이 다양한 센서와 모듈을 활용하여 실습할 수 있도록 구성되었습니다.

## 프로젝트 개요

*   **프로젝트명**: LuKasIT 아두이노 교재 프로젝트
*   **목적**: 아두이노 학습자를 위한 실습 예제 및 강의 자료 제공
*   **저자**: 박재홍
*   **이메일**: jaehong1972@gmail.com
*   **라이선스**: MIT License

## 폴더 구조 및 설명

```
.
├── .gitignore
├── README.md
├── LICENSE
├── DATA-for-Dust-measuring-lecture/
│   ├── 부품리스트.txt
│   ├── 아두이노-미세먼지측정기-3D-KIT-만들기-v1.xps
│   ├── 아두이노-미세먼지측정기-3D-KIT-만들기-v2.pdf
│   ├── 한달코딩_미세먼지프로젝트_박재홍_draft#1.hwp
│   ├── CH341SER.ZIP
│   ├── Fritzing-Library-master.zip
│   ├── 0.시작하기 전/
│   │   ├── 라즈베리파이사진.png
│   │   ├── 마이크로비트사진.png
│   │   ├── 아두이노우노호환보드.png
│   │   └── 1.아두이노스케치다루기/
│   │       ├── 케이블사진.jpg
│   │       ├── dht11모듈사진.jpg
│   │       ├── DSM501A사진.jpg
│   │       ├── I2C LCD사진.jpg
│   │       └── RGB LED사진.jpg
│   ├── 1.RGB LED/
│   │   ├── 아두이노우노보드사진.png
│   │   ├── BB내부전기배선사진.png
│   │   ├── BB사진.png
│   │   ├── RGB LED 부품사진.png
│   │   ├── RGB LED의 원리.jpg
│   │   └── RGBLED회로도.jpg
│   ├── 2.시리얼모니터/
│   │   ├── SerialMonitor사진#1.png
│   │   ├── SerialMonitor사진#2.png
│   │   └── sketch-coding.png
│   ├── 3.DHT11온습도/
│   │   ├── 섭씨온도값시리얼모니터.png
│   │   ├── 습도값시리얼모니터.png
│   │   ├── 온습도센서회로연결#1.jpg
│   │   ├── BlueLED동작사진.jpg
│   │   ├── DHT_sensor_library-1.3.2.zip
│   │   ├── dht11센서모듈사진.jpg
│   │   └── RedLED동작사진.jpg
│   ├── 4.미세먼지센서/
│   │   ├── 동작사진결과.jpg
│   │   ├── 새 텍스트 문서.txt
│   │   ├── 시리얼모니터결과사진#2.png
│   │   ├── 아두이노-미세먼지측정기-3D-KIT-만들기-v1.xps
│   │   ├── 아두이노-미세먼지측정기-3D-KIT-만들기-v2.pdf
│   │   ├── datasheet_Specification DSM501.pdf
│   │   ├── DSM501 Arduino Demo Code.zip
│   │   ├── DSM501.pdf
│   │   ├── DSM501A_dust_sensor_kit_Diy_Temperature_Humidity_dumy.zip
│   │   ├── DSM501A_dust_sensor_kit_Diy_Temperature_Humidity_v2.zip
│   │   ├── DSM501A_Dust_Sensor630081629_datasheet.pdf
│   │   └── GP2Y1010AU0F_Dust_Sensing_Device.zip
│   ├── 5.LCD/
│   │   ├── 미세먼지LCD출력화면.jpg
│   │   ├── Humi값LCD출력화면.jpg
│   │   ├── LCD_Address확인.png
│   │   ├── LCD_HelloWorld출력결과.jpg
│   │   ├── LCD회로연결.png
│   │   └── Temp값LCD출력화면.jpg
│   └── 6.Fianl_LCD_Temp_Humi_Dust/
│       └── All동작화면사진.jpg
├── LukasIT_All_final/
│   └── LukasIT_All_final.ino
├── LukasIT_DHT11___/
│   ├── LukasIT_DHT11/
│   │   └── LukasIT_DHT11.ino
│   └── LukasIT_DHT11_Temp_Humi/
│       ├── LukasIT_DHT11_Humi/
│       │   └── LukasIT_DHT11_Humi.ino
│       ├── LukasIT_DHT11_Humi_RGBLED_Anodetype/
│       │   └── LukasIT_DHT11_Humi_RGBLED_Anodetype.ino
│       ├── LukasIT_DHT11_Temp/
│       │   └── LukasIT_DHT11_Temp.ino
│       ├── LukasIT_DHT11_Temp_Humi/
│       │   └── LukasIT_DHT11_Temp_Humi.ino
│       └── LukasIT_DHT11_Temp_RGBLED_Anodetype/
│           └── LukasIT_DHT11_Temp_RGBLED_Anodetype.ino
├── LukasIT_DSM501A_DustSensor_ugm3/
│   └── LukasIT_DSM501A_DustSensor_ugm3.ino
├── LukasIT_I2CLCD_Address/
│   └── LukasIT_I2CLCD_Address.ino
├── LukasIT_I2CLCD_Proj/
│   ├── LukasIT_I2CLCD_Proj.ino
│   ├── LukasIT_I2CLCD_DHT11_Humi/
│   │   └── LukasIT_I2CLCD_DHT11_Humi.ino
│   ├── LukasIT_I2CLCD_DHT11_Temp/
│   │   └── LukasIT_I2CLCD_DHT11_Temp.ino
│   └── LukasIT_I2CLCD_DSM501A_DustSensor_ugm3/
│       └── LukasIT_I2CLCD_DSM501A_DustSensor_ugm3.ino
├── LukasIT_RGBLED/
│   └── LukasIT_RGBLED.ino
├── LukasIT_RGBLED_AnodeType/
│   └── LukasIT_RGBLED_AnodeType.ino
├── LukasIT_SerialMonitor/
│   └── LukasIT_SerialMonitor.ino
└── LukasIT_SerialMonitor_AnodeType/
    └── LukasIT_SerialMonitor_AnodeType.ino
```

### 파일 및 폴더 상세 설명

*   `.gitignore`: Git 버전 관리에서 제외할 파일 및 폴더를 정의합니다.
*   `README.md`: 이 프로젝트에 대한 전반적인 정보를 담고 있는 문서입니다.
*   `LICENSE`: 이 프로젝트의 라이선스 정보 (MIT License)를 포함합니다.
*   `DATA-for-Dust-measuring-lecture/`: 미세먼지 측정 강의를 위한 자료들을 모아둔 폴더입니다.
    *   `부품리스트.txt`: 실습에 필요한 부품들의 목록입니다.
    *   `아두이노-미세먼지측정기-3D-KIT-만들기-v1.xps`, `아두이노-미세먼지측정기-3D-KIT-만들기-v2.pdf`: 미세먼지 측정기 3D KIT 제작 가이드 문서입니다.
    *   `한달코딩_미세먼지프로젝트_박재홍_draft#1.hwp`: 미세먼지 프로젝트의 초안 문서입니다.
    *   `CH341SER.ZIP`: CH341 USB-Serial 드라이버 압축 파일입니다.
    *   `Fritzing-Library-master.zip`: Fritzing 회로 설계 프로그램용 라이브러리 압축 파일입니다.
    *   `0.시작하기 전/`: 아두이노 학습을 시작하기 전에 필요한 기본적인 정보와 준비물에 대한 자료입니다.
        *   `라즈베리파이사진.png`, `마이크로비트사진.png`, `아두이노우노호환보드.png`: 다양한 마이크로컨트롤러 보드 사진입니다.
        *   `1.아두이노스케치다루기/`: 아두이노 스케치(IDE) 사용법에 대한 자료입니다.
            *   `케이블사진.jpg`, `dht11모듈사진.jpg`, `DSM501A사진.jpg`, `I2C LCD사진.jpg`, `RGB LED사진.jpg`: 각 부품의 사진 자료입니다.
    *   `1.RGB LED/`: RGB LED의 원리 및 제어 방법에 대한 강의 자료입니다.
        *   `아두이노우노보드사진.png`, `BB내부전기배선사진.png`, `BB사진.png`, `RGB LED 부품사진.png`: RGB LED 실습 관련 사진 자료입니다.
        *   `RGB LED의 원리.jpg`, `RGBLED회로도.jpg`: RGB LED의 동작 원리 및 회로도 이미지입니다.
    *   `2.시리얼모니터/`: 아두이노 시리얼 모니터 사용법에 대한 강의 자료입니다.
        *   `SerialMonitor사진#1.png`, `SerialMonitor사진#2.png`, `sketch-coding.png`: 시리얼 모니터 사용 예시 및 스케치 코딩 화면 사진입니다.
    *   `3.DHT11온습도/`: DHT11 온습도 센서 사용법에 대한 강의 자료입니다.
        *   `섭씨온도값시리얼모니터.png`, `습도값시리얼모니터.png`: DHT11 센서로 측정한 온도/습도 시리얼 모니터 출력 예시입니다.
        *   `온습도센서회로연결#1.jpg`, `BlueLED동작사진.jpg`, `dht11센서모듈사진.jpg`, `RedLED동작사진.jpg`: DHT11 센서 실습 관련 사진 자료입니다.
        *   `DHT_sensor_library-1.3.2.zip`: DHT 센서 라이브러리 압축 파일입니다.
    *   `4.미세먼지센서/`: 미세먼지 센서 (DSM501A, GP2Y1010AU0F) 사용법에 대한 강의 자료입니다.
        *   `동작사진결과.jpg`, `새 텍스트 문서.txt`, `시리얼모니터결과사진#2.png`: 미세먼지 센서 실습 결과 및 시리얼 모니터 출력 예시입니다.
        *   `아두이노-미세먼지측정기-3D-KIT-만들기-v1.xps`, `아두이노-미세먼지측정기-3D-KIT-만들기-v2.pdf`: 미세먼지 측정기 3D KIT 제작 가이드 문서입니다.
        *   `datasheet_Specification DSM501.pdf`, `DSM501.pdf`, `DSM501A_Dust_Sensor630081629_datasheet.pdf`: DSM501/DSM501A 센서 데이터시트입니다.
        *   `DSM501 Arduino Demo Code.zip`, `DSM501A_dust_sensor_kit_Diy_Temperature_Humidity_dumy.zip`, `DSM501A_dust_sensor_kit_Diy_Temperature_Humidity_v2.zip`, `GP2Y1010AU0F_Dust_Sensing_Device.zip`: 미세먼지 센서 관련 데모 코드 및 키트 자료 압축 파일입니다.
    *   `5.LCD/`: I2C LCD 모듈 사용법에 대한 강의 자료입니다.
        *   `미세먼지LCD출력화면.jpg`, `Humi값LCD출력화면.jpg`, `LCD_Address확인.png`, `LCD_HelloWorld출력결과.jpg`, `LCD회로연결.png`, `Temp값LCD출력화면.jpg`: LCD 출력 예시 및 회로 연결 사진입니다.
    *   `6.Fianl_LCD_Temp_Humi_Dust/`: LCD, 온도, 습도, 미세먼지 센서를 통합하여 동작하는 최종 프로젝트의 결과 사진입니다.
        *   `All동작화면사진.jpg`: 모든 센서가 통합되어 동작하는 화면 사진입니다.
*   `LukasIT_All_final/`: 모든 센서(온도, 습도, 미세먼지)와 LCD를 통합하여 제어하는 최종 아두이노 스케치 코드입니다.
    *   `LukasIT_All_final.ino`: 최종 통합 프로젝트 스케치 파일.
*   `LukasIT_DHT11___/`: DHT11 온습도 센서 관련 아두이노 예제 코드들을 모아둔 폴더입니다.
    *   `LukasIT_DHT11/`: DHT11 센서의 기본적인 사용 예제.
    *   `LukasIT_DHT11_Temp_Humi/`: DHT11 센서를 이용한 온도 및 습도 측정 예제들을 포함합니다.
        *   `LukasIT_DHT11_Humi/`: DHT11 습도 측정 예제.
        *   `LukasIT_DHT11_Humi_RGBLED_Anodetype/`: DHT11 습도 측정과 애노드 타입 RGB LED 제어 예제.
        *   `LukasIT_DHT11_Temp/`: DHT11 온도 측정 예제.
        *   `LukasIT_DHT11_Temp_Humi/`: DHT11 온도 및 습도 동시 측정 예제.
        *   `LukasIT_DHT11_Temp_RGBLED_Anodetype/`: DHT11 온도 측정과 애노드 타입 RGB LED 제어 예제.
*   `LukasIT_DSM501A_DustSensor_ugm3/`: DSM501A 미세먼지 센서의 기본적인 사용 예제 코드입니다.
    *   `LukasIT_DSM501A_DustSensor_ugm3.ino`: DSM501A 미세먼지 센서 스케치.
*   `LukasIT_I2CLCD_Address/`: I2C LCD 모듈의 주소를 찾는 예제 코드입니다.
    *   `LukasIT_I2CLCD_Address.ino`: I2C LCD 주소 확인 스케치.
*   `LukasIT_I2CLCD_Proj/`: I2C LCD 모듈을 활용한 다양한 프로젝트 예제 코드들을 모아둔 폴더입니다.
    *   `LukasIT_I2CLCD_Proj.ino`: I2C LCD 기본 프로젝트 스케치.
    *   `LukasIT_I2CLCD_DHT11_Humi/`: I2C LCD에 DHT11 습도 값을 출력하는 예제.
    *   `LukasIT_I2CLCD_DHT11_Temp/`: I2C LCD에 DHT11 온도 값을 출력하는 예제.
    *   `LukasIT_I2CLCD_DSM501A_DustSensor_ugm3/`: I2C LCD에 DSM501A 미세먼지 값을 출력하는 예제.
*   `LukasIT_RGBLED/`: RGB LED의 기본적인 제어 예제 코드입니다.
    *   `LukasIT_RGBLED.ino`: RGB LED 기본 스케치.
*   `LukasIT_RGBLED_AnodeType/`: 애노드 타입 RGB LED 제어 예제 코드입니다.
    *   `LukasIT_RGBLED_AnodeType.ino`: RGB LED (애노드 타입) 스케치.
*   `LukasIT_SerialMonitor/`: 아두이노 시리얼 모니터의 기본적인 사용 예제 코드입니다.
    *   `LukasIT_SerialMonitor.ino`: 시리얼 모니터 기본 스케치.
*   `LukasIT_SerialMonitor_AnodeType/`: 시리얼 모니터와 애노드 타입 LED를 함께 사용하는 예제 코드입니다.
    *   `LukasIT_SerialMonitor_AnodeType.ino`: 시리얼 모니터 (애노드 타입) 스케치.

## 사용 방법

각 폴더 내의 `.ino` 파일을 아두이노 IDE로 열어 아두이노 보드에 업로드하여 실습할 수 있습니다. 필요한 라이브러리는 각 예제 코드에 명시되어 있거나 `DATA-for-Dust-measuring-lecture/` 폴더 내에 포함되어 있습니다.

## 기여

이 프로젝트는 LuKasIT의 교재를 위해 제작되었으며, 외부 기여는 현재 받지 않습니다.

## 문의

프로젝트 관련 문의는 저자 박재홍(jaehong1972@gmail.com)에게 연락 주시기 바랍니다.