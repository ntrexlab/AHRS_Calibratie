# AHRS_RS232_Text
GitHub -> [ntrexlab/AHRS_Calibratie](https://github.com/ntrexlab/AHRS_Calibratie)
***
## **Manual**
***
* ### 1.HardWare
    * #### 사용모델
         - AHRS - [MW_AHRSv1](http://www.devicemart.co.kr/goods/view?no=1310790)
        
    * #### AHRS_USB_TTL to RS232
         - CP2102 Micro USB to TTL 컨버터 모듈 - [SZH-CVBE-037](http://www.devicemart.co.kr/goods/view?no=1326839)
         - MAX3232 초소형 TTL to RS232 컨버터 모듈 - [SZH-CVBE-011](http://www.devicemart.co.kr/goods/view?no=1324909)

      ![ahrscips](https://user-images.githubusercontent.com/85467544/121143026-8c926580-c877-11eb-988e-d54908e76921.png)


***
* ### 2.Tool
    * #### 사용버전
    - AHRS_UI_180808 [설치경로-관련자료](http://www.devicemart.co.kr/goods/view?no=1310790#goods_file)
***

* ### 3. Calibratie 튜닝 순서    
    #### 1. AHRS_USB_TTL to RS232를 제작한다.
    #### 2. AHRS_UI_180808을 설치한다.
    #### 3. AHRS_USB_TTL to RS232를 PC의 연결 후 AHRS_UI_180808 실행한다.
    #### 4. Connect 버튼(1)을 클릭한다.
    #### 5. Connection(2) 창이 뜨면 COM PORT의 연결 USB 번호를 설정한다.
    #### 6. Baudrate를 115200으로 설정한 후 Connect 버튼을 클릭한다.
    ![ahrs연2](https://user-images.githubusercontent.com/85467544/121149422-9dde7080-c87d-11eb-836c-896bacefdc12.png)
    #### 7. Ahrs를 평평한 바닥에 준비한다.
    ![c11](https://user-images.githubusercontent.com/85467544/121115658-5b526f00-c850-11eb-9829-354e7563ae70.png)
    #### 8. Calbratie 버튼을 클릭한다.
    #### 9. Calibration Dialog 창에서 Calibrate Cyro. Accel. 버튼 클릭한다.
    ![ahrs_c1](https://user-images.githubusercontent.com/85467544/121149744-e0a04880-c87d-11eb-996c-881c912789cf.PNG)
    #### 10. 예를 클릭한 후 4초정도 기다린다.
    ![ahrs_c2](https://user-images.githubusercontent.com/85467544/121149750-e1d17580-c87d-11eb-8ed3-9e025c4fc132.PNG)
    #### 11. 변경값을 확인한다.
    ![ahrs_c3](https://user-images.githubusercontent.com/85467544/121149030-4213e780-c87d-11eb-97f7-308263671212.PNG)
    #### 12. 밑에 사진들과 같이 방향을 바꾸며 위에 9~11번 과정을 반복한다.
    ![c21](https://user-images.githubusercontent.com/85467544/121115669-5e4d5f80-c850-11eb-9ce7-2a2808b27ada.png)
    ![c31](https://user-images.githubusercontent.com/85467544/121115674-60172300-c850-11eb-9b54-b31c011fec23.png)
    ![c41](https://user-images.githubusercontent.com/85467544/121115678-61485000-c850-11eb-9b42-d1e9c1cf69ff.png)
    ![c51](https://user-images.githubusercontent.com/85467544/121115685-63121380-c850-11eb-8326-062c7a2ba574.png)
***