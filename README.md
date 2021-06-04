# 2kinect


2.단계별 Tutorial

2.1 Kinect for Windows SDK v2 설치
 - 
설치 과정 
 -
[Microsoft Download Center](https://www.microsoft.com/ko-kr/download/)에서 설치 파일 [Kinect for Windows SDK v2](https://developer.microsoft.com/ko-kr/windows/kinect/)을 타운 받는다. 
 최신버전 사용을 추천합니다.

시스템 요구 사항:

지원되는 운영 체제 (Embedded 8 Standard, Windows8, Window 8.1)
- 권장 하드웨어 구성 : 64-bit (x64) 프로세서 / 4 GB 메모리 (이상) / Physical dual-core 3.1 GHz (2 logical cores per physical) 이상 프로세서 /  Kinect for Windows v2 센서 전용 USB 3.0 controller*/ DX11 capable graphics adapter** / 전원 허브 및 USB 케이블이 포함 된 Microsoft Kinect v2 케이블

![](images/kinect%20hardware.png)

- Softerware 요구 사항:
  - Visual 2012 또는 [Visual Studio2013](https://www.microsoft.com/ko-kr/download/details.aspx?id=40784) 

설치하는 동안 :
  1. kinect 센서가 컴퓨터 USB 포트에 연결되어 있지 않은지 확인합니다.
  2. 다운로드 위치에서 KinectSDK_v2.0_1409-Setup.exe를 두 번 클릭합니다.
  3. 설치가 완료되면 Kinect 센서가 전원 허브에 연결되어 있고 전원 허브가 콘센트에 연결되어 있는지 확인합니다. 전원 허브의 USB 케이블을 PC의 USB 3.0 포트에 연결합니다. 드라이버 설치가 자동으로 시작됩니다.
  4. 드라이버 설치 후 장치 관리자를 실행하여 확인할 수 있으며 장치 목록에 "KinectSensor 장치"가 존재합니다.
  5. 설치가 완료되었습니다.

2.2 Pykinect 설치
 - 
